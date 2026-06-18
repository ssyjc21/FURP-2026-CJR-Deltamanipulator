# Weekly Progress Log

> Update this file **every week**. Add a new entry at the top for each week.
> This is the first thing we check during review. Keep it honest and specific — it also feeds your attendance record (Rule 1).

**How to use:** copy the *Week template* block below for each new week. Newest week goes at the top.

---

## Week template — copy me

### Week N — YYYY-MM-DD

**Attended this week's meeting:** Yes / No (if No, did you email leave? Yes / No)

**Progress this week**
- _What did you actually do / finish?_

**Challenges & blockers**
- _What got in the way? What are you stuck on?_

**Next steps**
- _What will you do next week?_

**Hours spent (optional):** _e.g. 6h_

**Links (optional):** _commits, notebooks, docs, datasets..._

---

<!-- =================  YOUR ENTRIES BELOW  ================= -->

### Week 0 — 2026-6-12
**Attended this week's meeting:** Yes

**Progress this week**
- _Joined the FURP kickoff meeting and discussed the project objectives, expected outcomes, and development tools.
- _Attended the 3-DoF project meeting andreviewed the project topic: "3-DoF Aerial Manipulator for Physical Interaction". 
- _Set up the project github repository based on the FURP template, Familiarized myself with the github interface that will be used throughout the project.
- _Organized project resources and collected the initial documentation provided by the supervisor.

**Challenges & blockers**
- _Limited background knowledge in aerial manipulation systems and UAV-manipulator coupled dynamics.
- _still developing revelent skills of matlab control system programming/simulink software

**Next steps**
- _decide the rough dimension of solidworks model we're going to make with groupmates., model the cad file
- _figure out the requires of matlab/simulink usage for my computer
- _Study the actuator control methods


**Links (optional):**
- _project repository: FURP-2026-CJR-Deltamanipulator/docs/00_weekly.md

### Week 1 — 2026-6-18
**Attended this week's meeting:**  No meeting arranged

**Progress this week**
- _Reviewed the existing Delta manipulator assembly provided by the supervisor and confirmed it is a standard 3-DoF Delta parallel mechanism (base platform, 3 driving arms, 6 Link2 parallelogram linkages, moving platform).
- _Identified the original actuators used in the assembly as 4310 geared motors ×3, and confirmed the replacement actuator is the DM-S3519-1EC ×3.
- _Reviewed DM-S3519-1EC manufacturer documentation, test data, and 2D/3D CAD files to extract key mounting specs (flange OD, mounting hole pattern, output shaft diameter) for the upcoming motor swap.
- _Diagnosed a CAD environment issue: the supervisor-provided assembly file only contains the top-level .SLDASM, without the referenced individual part files, which prevents editing any component.
  
**Challenges & blockers**
- _The assembly displays full geometry correctly but individual parts cannot be edited (no "Edit Part" option, edit attempts prompt a locate-file dialog), because the referenced part files were not included with the assembly.
- _Still waiting on the supervisor to provide the complete project folder (all referenced part files) before actuator mounting comparison and bracket redesign can begin.

**Next steps**
- _Resolve the missing part files issue, either by requesting the full folder from the supervisor or running SolidWorks "Pack and Go" to generate a missing-file diagnostic report.
