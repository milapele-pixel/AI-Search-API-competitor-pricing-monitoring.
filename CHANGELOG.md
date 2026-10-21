## [v0.5] - 2026-10-21
### Changes
- Updated n8n workflow ( [workflow_v0.5.json](workflow_v0.5.json)).
- Added the workflow JSON file to the GitHub repository.
- Added an IF node to prevent unnecessary email notifications.

### Reason
- To prevent unnecessary email notifications.
- To resolve the issue identified in test T06.
  
### Status
- Candidate for publication.
- Workflow with the IF node.
- T06 issue resolved based on previous testing in v0.4.

### Notes:
- Candidate for publication
- In need to fix also the test T03 and T02


## [v0.4] - 2026-10-21
### Changes
- Added [CI_for_T06](CI_for_T06.md)
- Added an IF node to the testing workflow copy.

### Reason
- Fiximg the mistake of T06 test
- Check other changes from previous testing
### Status
- Created a copy of the original n8n workflow for testing.
- The original n8n workflow remained unchanged.
- 5/6 tests passed the test from previous [Tests for workflow_v0.1json.md](Tests%20for%20workflow_v0.1json.md).
- T03 partially passed; T06 succeded.
### Notes
- T06 issue was resolved in the testing workflow copy.
- The fix has not yet been applied to the original workflow.



## [v0.3] - 2026-10-21
### Changes
- Added [Tests for workflow_v0.1json.md](Tests%20for%20workflow_v0.1json.md)
### Reason
- To check which tests passed and which did not
- To analyze what changes will be needed for original workflow.
  
### Status
- Executed 6 tests for the workflow without an IF node.
- Created a copy of the original n8n workflow for testing.
- The original n8n workflow remained unchanged.
- 4/6 tests passed the test.
- T03 partially passed; T06 failed.
- 
### Notes
- Original Tests for workflow_v0.1json.md created on 2026-10-20.
- Version recorded in CHANGELOG on 2026-10-21.
- Version documented retrospectively.



## [v0.2] - 2026-10-21
### Changes
- Added [README.md](README.md)

- Added [Documentation](Documentation)
### Reason
- for easier workflow understanding, if another person takes it over
### Status
- Documented prototype for the workflow without IF node.
- No changes to the n8n workflow JSON.
### Notes
- Original README.md created on 2026-10-20.
- Documentation version recorded in CHANGELOG on 2026-10-21.
- Version documented retrospectively.


## [v0.1] - 2026-10-21
### Changes
- Added initial n8n workflow ( [workflow_v0.1.json](workflow_v0.1.json)).
- Added the workflow JSON file to the GitHub repository.
### Reason
- Initial version saved for tracking and documentation.
### Status
- Unpublished prototype.
- Workflow without the IF node.
### Notes
- Original workflow created 2026-10-20.
- Version added to GitHub on 2026-10-21.
