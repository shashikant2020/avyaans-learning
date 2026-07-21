# Workspace Rules for Avyaan's Learning

## Git Credentials & Repository Access
- **Personal Workspace Constraints**: This is a personal workspace and must always use the personal GitHub account credentials for `shashikant2020`.
- **Forbidden Profiles**: Under no circumstances should corporate credentials (`sprasad` / `shashikant-prasad_zse`) or data pilot (`datapilot.in`) profiles be used for Git operations in this repository.
- **Local Helper Configuration**: A local Git credential helper is configured inside `.git/config_credentials`. Bypassing or modifying this helper is forbidden. Any git push/pull/fetch commands must be run standardly (e.g. `git push`), and they will automatically route through the personal token stored locally.
