## Summary
<!-- Describe your science -->

## Author Checklist
- [ ] This repository has a Lasseigne Lab ruleset configured.
  See instructions [here](https://github.com/lasseignelab/project-template/blob/main/DEVELOPMENT.md).
- [ ] A singularity container has been created with all dependancies and the
  cap_container command has been included in each script using a container.
- [ ] All of the necessary scripts, dependencies, and inputs have been included
  in this pull request.
- [ ] Only files relevant to this change are included; no temporary, generated,
  or unrelated files are part of this pull request. Use `.gitignore` to prevent
  irrelevant files from accidentally being included.
- [ ] Results have been reproduced and verified with `lasseignelab` and
  `default` environments by running the job until two consecutive runs produce
  the same results. Code comments (per script) have been added for
  non-reproducible scripts. Include information about why the script is not
  reproducible.
- [ ] All automated code checks have passed. The "All checks have passed"
  message should show in the GitHub pull request status box above the
  "Merge pull request" button.
- [ ] No merge conflicts exist. Merge conflicts are indicated by the "This
  branch has conflicts that must be resolved" message in the GitHub pull
  request status box above the "Merge pull request" button.
- [ ] Primary and secondary reviewers have been requested to review this
  pull request.

## Self/Peer Review Checklist ([Coding Guidelines](https://docs.google.com/document/d/1h1hxQGrqnQqo1pAxrrtX1OtjHddRTqtgsgDFSXOQpzk/edit?usp=sharing))
- Meaningful variable and function names
- File header comments
- Function comments
- In-line comments summarize logical sections of code by concisely explaining
  why, not what the code is doing.  Avoid excessive or redundant commenting.
- Random seed is set
- Reasonable processing time for each job or script is specified
- All outputs have been saved
- Session info included in the scripts
- Cross-reference the working draft of the paper
- Confirm the code performs the intended analysis
- Confirm the code reproduces the reported results

## Setup
<!-- How to setup the project before reproducing results? -->

## Reproduce results
<!-- How to reproduce the results? -->

## Verification
<!-- How to verify the results? -->

