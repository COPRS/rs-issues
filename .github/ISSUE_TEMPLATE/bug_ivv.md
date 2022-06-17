---
name: 🐞 Bug IVV
about: File a bug/issue
title: '[BUG] <title>'
labels: bug, ivv, CCB
assignees: ''

---

<!--
Note: Please search to see if an issue already exists for the bug you encountered.
Note: A closed bug can be reopened and affected to a new version of the software.
-->

 
**Environment:**
<!-- 
- Delivery tag: release/0.1.0
- Platform: IVV Orange Cloud
- Configuration:
-->
  
**Test:**
<!-- 
- Name: TST_INFRA_DEP_orange
- Traçability (requirements): NA
-->
  
**Current Behavior:**
<!-- A concise description of what you're experiencing. -->

**Expected Behavior:**
<!-- A concise description of what you expected to happen. -->

**Steps To Reproduce:**
<!--
Example: steps to reproduce the behavior:
1. In this environment...
2. With this config...
3. Run '...'
4. See error...
-->

**Test execution artefacts (i.e. logs, screenshots…)**
Tip: You can attach images or log files by dragging & dropping, selecting or pasting them.

**Whenever possible, first analysis of the root cause**
<!-- A concise description of the first analysis. -->
 
  
 **Bug Generic Definition of Ready (DoR)**
- [ ] The affect version in which the bug has been found is mentioned
- [ ] The context and environment of the bug is detailed
- [ ] The description of the bug is clear and unambiguous
- [ ] The procedure (steps) to reproduce the bug is clearly detailed
- [ ] The failed tests is linked to the bug : failed result % expected result
- [ ] The tested User Story / features is linked to the bug
- [ ] Logs are attached if available 
- [ ] A data set attached if available
- [ ] Category label is link to the bug <!-- infra, mon, pro, perfo, hmi, secu -->
 

**Bug Generic Definition of Done (DoD)**
- [ ] the modification implemented (the solution to fix the bug) is described in the bug.
- [ ] Unit tests & Continuous integration performed  - Test results available - Structural Test coverage reported by SONAR
- [ ] Code committed in GIT with right tag or Analysis/Trade Off documentation up-to-date in reference-system-documentation repository
- [ ] Code is compliant with coding rules  (SONAR Report as evidence)
- [ ] Acceptance criteria of the related User story are checked and Passed
