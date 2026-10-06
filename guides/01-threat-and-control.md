# Exercise 1: connect threats, controls and evidence

Level: beginner · Format: paper exercise · Prerequisites: none

## Outcome

Produce a one-page worksheet for a fictional file-sharing lab. No scanning or configuration changes are required.

## Work through an example

| Asset | Unwanted event | Proposed control | Evidence to seek |
| --- | --- | --- | --- |
| Sample files | Accidental deletion loses the only copy | Separate backup and restore process | Successful isolated restoration of a sample file |
| Administrator account | An unauthorized person gains access | Appropriate authentication and restricted privileges | Reviewed account settings and an access test in the lab |
| Service configuration | A change prevents normal use | Reviewed change and recovery steps | Successful recovery rehearsal |

These rows are hypotheses to investigate, not proof that controls are implemented.

## Try it

1. Sketch a fictional system with users, an application and storage.
2. Pick three assets and identify who should be allowed to use each one.
3. For each asset, describe one unwanted event in ordinary language.
4. Propose a control and a concrete observation that could show whether it works.
5. Mark each control `not tested`, `pass`, `fail` or `not applicable` and explain why. With no lab execution, the honest starting state is `not tested`.
6. Describe how a failed or disruptive control could be reversed in a disposable lab.

## Check your work

A useful worksheet distinguishes the desired configuration from evidence. 'We have backups' is weaker than 'we restored the chosen sample and checked its contents on this date.' A screenshot of a setting may demonstrate configuration, but not every end-to-end behavior.

## Next step

Choose one row to turn into a lab using the [tutorial template](../templates/tutorial.md). Define the authorized scope, prerequisites, recovery path and expected results before adding commands.
