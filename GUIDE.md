# Teaching Guide: ECG in Motion (for the instructor)

[日本語版 (GUIDE_JA.md)](GUIDE_JA.md) · [README.md](README.md)

A session plan for teaching clinic staff (nurses, technicians and others) in about 30 minutes to see an ECG as one vector. It assumes one instructor and a few to a dozen learners. The plan is built around what the tool can do; its teaching effect has not been tested, so change it freely.

## Goals

By the end, learners should be able to say:

1. The 12-lead tracing is the "shadow" of one heart arrow cast onto each lead axis.
2. A finding in one lead sees only part of the arrow's direction, so do not decide from one lead.
3. In this model, ST elevation and the opposite ST depression (the reciprocal change) are the front and back of the same arrow. In real patients ST depression can have other causes, so it is judged with the clinical picture and several leads.

## Preparation (5 minutes before)

- Open `index.html` (or the artifact link) on a computer and project it. On a phone you move back and forth between the planes and the stacked 12 leads, so with a group, use the computer screen as the main view.
- The tool opens on *All at once*. Keep it that way while teaching.
- Learners can open the same page and trace the arrow themselves. The language switch (日本語 / English) is at the top right.
- With two monitors, open *Vector & controls* and *ECG & notes* in separate windows (*Open in a new window*, next to the tabs). The two windows stay in sync.

## Session plan (about 30 minutes of explanation; about 35 minutes including learners' hands-on time)

### 0. How to read the screen (2 min)

- Point to the frontal plane (limb leads), the horizontal plane (chest leads), the 3D view and the 12-lead tracing.
- Say only this: when the arrow points close to a lead's axis, that lead goes up (positive); when it points away, it goes down (negative).
- The segments (P, QRS, ST-T) are color-coded. ST-T groups the ventricular recovery (repolarization) into one segment.
- Use the small figure at the top right of each plane to check the viewing direction. The frontal plane is a front view. The horizontal plane can be switched with the buttons next to its title between *From head* and *From feet* (it starts with *From head*). In every view, the patient's left (L) is on the right of the screen.
- The two horizontal views are a good teaching point. *From head* (back at the top, front at the bottom) is the traditional ECG / vectorcardiogram view and matches the frontal-plane convention (+90° = down). *From feet* (front at the top) is the imaging and anatomy view used for CT sections. The same section appears upside down between the two, so teach learners to check first which way a figure is viewed. In the 3D view, the small body figure at the top right turns with the view when you drag.
- To show everything at once, press *Show waveforms*. A one-beat waveform appears at the end of each lead axis, so learners can see at a glance that leads pointing closer to the vector show larger upward deflections. It works well to leave it off at first, trace the arrow one lead at a time, and then turn it on.
- The thick arrow is the heart's instantaneous vector. It always points from the centre to the tip. While the tip is returning toward the centre, a small triangle just behind it shows the direction of time.

- The figure *How excitation spreads through the heart, and the ECG waves*, below *About this tool* on the *Vector & controls* screen (on a phone, tap the heading to open it), shows which part of the heart each wave comes from (P, PQ segment, QRS, T). Showing it first makes the rest easier to follow.

### 1. Normal: see one arrow (5 min)

- Play the *Normal* case. The speed already starts at 0.1× (slow).
- Show: the frontal-plane arrow moves through P, QRS and T while the 12 leads draw at the same time.
- Ask: "Why does II show the tallest R and aVR the deepest negative wave?"
- Answer: the main vector points about 60° (down and to the left), close to the axis of II and opposite to aVR.
- Switch to *Trace through time* and drag the tip along its loop: the 12-lead cursor moves to the same moment. Every lead at that moment comes from the same arrow.
- Ask (while tracing): "The arrow is a good size, yet aVL is almost flat. Which way does the arrow point?"
- Answer: nearly at right angles to aVL (−30°), about 60° or about −120°. A near-zero arrow also gives a flat line, so ask while the arrow has some size.

### 2. Acute inferior MI: see the reciprocal change (8 min)

- Choose *Acute inferior MI* and press *Show the ST vector*. The time jumps to the ST segment and stops.
- Show: the ST vector is a small arrow pointing to the injured inferior wall (down and to the right).
- Read the *Shadow of the ST vector* card: elevation in III, aVF, II; depression in aVL and others.
- Ask: "Where does the ST depression in aVL come from?"
- Answer: in this model, it is the same arrow seen from the opposite side. That is the reciprocal change.
- Teach mainly elevation in III and depression in aVL. The model also shows depression in V5–V6, but that comes from the fixed chest-lead axes; in real inferior infarction it is not a consistent finding.

### 3. Acute posterior MI: see a hidden wall in a mirror (5 min)

- Choose *Acute posterior MI* and press *Show the ST vector*.
- Show: the ST vector points to the back, so the chest leads, which look from the front, go down.
- Ask: "Is there a lead in the 12-lead ECG that faces the posterior wall directly?"
- Answer: no. That is why it shows up as a mirror image, ST depression in V1–V3. In real patients, ST depression in V1–V3 (often with upright T waves) is the clue, and recording V7–V9 may confirm ST elevation.

### 4. Quick quiz (7 min)

- Open the *Quiz* screen (the fourth tab).
- *Arrow → leads*: from the arrow, mark each of the six limb leads ↑ (elevation), = (almost unchanged) or ↓ (depression). After checking, tap a lead button to draw a perpendicular from the arrow tip to that lead axis. If its foot lies beyond the grey band on the + side, ↑; on the − side, ↓; inside the band (within half the arrow length from the centre), =. Half the length corresponds to 60° and 120°.
- *ST pattern → wall*: choose which of the model's four MI cases gives the pattern. Elevation and depression are thresholds inside the model, not clinical ST criteria.
- Let learners answer first, then check and explain.

### 5. Wrap-up (2 min)

Ask learners to say the three goals in their own words.

## If there is time

- **Axis deviation**: with *Left* and *Right axis deviation*, only the frontal direction changes. Leads I and aVF together give the quadrant. In this model the horizontal direction is kept close to normal.
- **Bundle branch blocks**: in *Left bundle branch block* the arrow stretches posteriorly and to the left and the QRS lengthens. In *Right bundle branch block* the first half of the QRS is normal, and a terminal component pointing right and anterior is added in the second half. *Show the terminal vector* jumps there; its shadow is the R′ in V1 and the broad S in I, V5 and V6.
- **Lateral and anterior MI**: as the ST vector turns, the leads that rise and fall swap. Chest-lead deflections come out large in this model. The distribution of ST elevation is a clue to the territory but cannot fix its extent.
- **Build your own arrow**: *Edit the arrow (advanced)* makes a vector no case has. Useful for questions on the spot (for example, "If the arrow points straight down, which lead is largest?" → aVF).

## Things to keep in mind

- This is an idealized teaching model, not a measured ECG, and not for diagnosis. Tell learners this at the start.
- Each chest lead is really a potential measured at its own electrode and cannot be derived exactly from six fixed axes. The model's horizontal axes and 1.8× chest gain are assumptions to show projection; fine chest-lead shapes differ from real ECGs.
- The MI cases add only an ST vector to the same QRS and T as the normal case. Pathological Q waves and T-wave changes are not shown.
- The time scale follows ECG paper; the vertical scale is arbitrary.
- Window synchronization was checked in Chrome, not in Safari.
- Please check the medical wording of the explanations yourself before a session.
