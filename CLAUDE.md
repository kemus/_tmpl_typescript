# _tmpl_ecmascript

ECMAScript/TypeScript subtemplate (stage 1) for the copier template system.

## Structure

- `copier.yml` — copier config (no questions; variables arrive via `--data-file`)
- `post-task.sh` — leaf post-task (no children)
- `template/` — ECMAScript/TypeScript-specific files to copy into the generated project
- `children/` — empty (leaf template)
