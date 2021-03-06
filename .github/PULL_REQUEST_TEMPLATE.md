## Additional Information
<!-- Add any additional information needed. Such as the Jira or GH issue this PR relates to or any other context you feel is necessary.) -->

## Verification Steps
As the verifier of the PR the following process should be done:

### Installation Verification
- Ensure the author of the PR has attached a log of the installation run from his branch to the jira or pr and check that it exited as expected.
- Verify the fresh installation is correct on cluster provided by PR author 
### Upgrade Verification
- After installation verification, notify the PR author to begin an upgrade on their cluster
- Ensure the developer of the PR has attached a log of the upgrade run from his branch to the jira or pr and check that it exited as expected. 
- If possible, look at the tasks that ran and see they match the PR
- Verify the upgrade is correct on cluster provided by PR author 

<!--
Add the steps required to check this change. Following an example.

1. Go to `XX >> YY >> SS`
2. Create a new item `N` with the info `X`
3. Try to edit this item
4. Check if in the left menu the feature X is not so long present.
-->

## Checklist
<!-- If there is an upgrade required, either outline the steps to test it or link to the issue for the upgrade -->

- [ ] Updated [Changelog](https://github.com/integr8ly/installation/blob/master/CHANGELOG.md)
- [ ] Tested Installation
- [ ] Tested Uninstallation
- [ ] Tested or Created follow on for Upgrade

Is an upgrade task required and are there additional steps needed to test this?
- [ ] Yes
- [ ] No