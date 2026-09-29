# BTR Blockout

A to-scale block-layout tool for **Butler Tech Robotics** (FRC 144 Operation Orange and FRC 325 Respawn). It's for early-season "crayon CAD": checking whether a mechanism reaches, sizing the chassis, and walking the team through ideas on the big screen, without making SolidWorks sketches.

**Open it:** https://aydenlo17.github.io/btr-blockout/

It runs in any modern browser (Chromebooks included) with no install and no account.

## What it does

- **Side and top views, linked.** Every part lives in both. Swing an arm in side view and its footprint in top view changes to match.
- **Parts:** tubes, blocks, pivot arms (with limits and a movable 0°), elevators (set stages, stage length and overlap and it works out the max lift; cascade or continuous rigging, optional carriage, optional lift limit, lowest position), four-bar linkages you can reshape point by point, wheels, rollers, sprockets, and motors (Kraken X60/X44, NEO Vortex, NEO 550; sizes are approximate).
- **Attach parts to each other.** A part can move and turn with its parent, move but keep its angle, or only slide along a line (for example a hopper wall that pushes out when an intake folds over the bumper).
- **Poses:** save Stow, Intake, Score and similar, then click to animate between them.
- **Rule checks:** frame perimeter, extension, max height, starting height and bumper zone, with presets for 2025 REEFSCAPE and 2026 REBUILT. Choose Custom and type the new numbers at kickoff.
- **Field elements:** 2025 reef, barge, coral station and processor; 2026 hub, trench, bump, tower, outpost and depot. You can also import a DXF exported from the field CAD.
- **Simple and Advanced modes** (Settings), a quick-start guide, copy/paste, locking, undo, and **Present** mode for the projector.

## Saving and sharing layouts

Your work autosaves in your browser. To share a layout, use **File → Save .json** and post the file on Teams; anyone can open it with **File → Open .json**. **Export PNG** saves a picture of the current view.

## Feedback

Click **Feedback** in the app to send an idea, complaint or bug report. It opens the team's Google Form with your note already filled in; press **Submit** there. Mentors get an email for every response.

## Updating the app

The whole app is `index.html`. Replace that file and commit, and GitHub Pages republishes in about a minute.
