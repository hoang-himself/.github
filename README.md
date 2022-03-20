# Default `.github` folder

Main thread: [Community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types)

These files don't have to be created immediately.
If there are lot of bugs reported in your project, create ISSUE_TEMPLATE.
If several people wants to support you, create FUNDING.yml.
You will create more and more files when the need comes.

## The following directories live in the `.github` folder per project

- `LICENSE.md`: [License files must be added to individual repositories so the file will be included when a project is cloned, packaged, or downloaded](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types). Moreover this file should be put at the root of the repository.
- `workflows/`: [Understanding GitHub actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
- `CODEOWNERS`: [About code owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
- Configurations of repository-specific bots, e.g.: `dependabot.yml` for Dependabot, `stale.yml` for Probot, etc.
