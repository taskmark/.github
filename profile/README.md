# Taskmark

**Plain-text todos that work everywhere.**

Taskmark is an open standard for managing tasks in plain Markdown files. It combines the simplicity of plain text with powerful features like metadata inheritance, recurring tasks, and seamless Git integration.

## About This Organization

Taskmark is an informal, community-driven initiative created by [Ricardo Gemignani](https://github.com/ricksaarge) to promote and develop the Taskmark standard as a hobby project. It is not a legally established entity—just a shared space for building tools around a common specification.

## Projects

### [taskmark-spec](https://github.com/taskmark/taskmark-spec)

The core specification defining the Taskmark format. Key features include:

- **Task states:** `[ ]` open, `[x]` done, `[-]` cancelled, `[!]` blocked
- **Rich metadata:** priorities `(A)`, dates, `@assignments`, `+projects`, `#tags`, `due:` deadlines, `~2h` estimates
- **Metadata inheritance:** Properties defined on headers cascade to child tasks
- **Subtasks:** One level of indented subtasks for breaking down work
- **Multi-file support:** Link related task files together

### [taskmark-python](https://github.com/taskmark/taskmark-python)

A Python library for parsing and manipulating Taskmark files:

```bash
pip install taskmark
```

Features:
- Parse markdown strings or files
- Follow linked files automatically
- Update tasks and write changes back
- Automatic recurring task generation

## Why Taskmark?

- **Future-proof:** Plain text works in any editor, forever
- **Version control friendly:** Diffs make sense, merges work
- **Renders everywhere:** GitHub, VSCode, any Markdown viewer
- **No lock-in:** Your data stays yours

## Contributing

Contributions are welcome! Whether it's improving the spec, building parsers for other languages, or creating editor plugins—open an issue or submit a PR in the relevant repository.

## License

Projects in this organization are released under the MIT License.
