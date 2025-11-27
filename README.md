# papers-please
Application for access to many gov.resources from **one** entrypoint
## ![Architecture Overview](/documents/images-src/overall-architecture.png)
### Workflow
General workflow must follow the next rules:
* All new branches must create from `development` branch
* All new branches start their name from IU-xxxx-[changename in kebab case]
* Сommit name should start with the IU-code and have a short, concise description of the changes.
* Commits should be merged into corresponding pull requests on the  `development` branch and include extended changelogs, if possible.
* After code review and approval, merge pull requests to `development`.
* Huge stable versions from `development` must be merged into `master` branch.
