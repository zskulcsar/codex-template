## Init

- create project directory
- create .envrc file
- create .codex  and supprting directories `mkdir -p .codex/skills`
- run `codex` in project root (login, etc.
- Create the `AGENTS.MD` for skills
- Update the `.codex/config.toml` and add:
    ```toml
    # Limited network
    [sandbox_workspace_write]
    network_access = true
    ```
