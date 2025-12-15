# Developer guidelines
These are general developer guidelines. There could be per-repo guidelines as well.

- Fast, lightweight dev environment is must. Ensure that code-test-fix cycles are fast, there is no productivity loss.
- Low overhead communication channel with other project stakeholders: matrix, slack as applicable.

# Dev tools to install on typical dev machine
- IDE: VSCode with needed plugins. Common ones for toml, gitlens, mise, are useful.
- Repository: git, gpg keychain for commit signing
- Project environment setup: mise (like asdf)
- Build target orchestration: mise (like just or make)
- File watch to trigger tasks: mise (like entr)
- Build: Repo specific, e.g. cargo, gradle, make
- Shell accelerators: Warp or iterm terminal, Zsh extensions
- CI: CI commandline tools e.g. `gh` commandline for github actions
- AI Assistants: CoPilot, Gemini Code Assist or others.

