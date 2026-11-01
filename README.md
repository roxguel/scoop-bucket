# Scoop bucket

Manifests for [roxguel](https://github.com/roxguel)'s tools.

```powershell
scoop bucket add roxguel https://github.com/roxguel/scoop-bucket
scoop install roxguel/gdt
```

| Manifest | What it is |
|---|---|
| `gdt` | [Godot Development Tools](https://gdt.roxguel.dev): version manager, addon manager and test runner for Godot. Windows, x64 and arm64. |

The manifests install the archives from each project's GitHub releases, checked against the SHA-256 in the manifest. The Windows binaries are not code-signed, so SmartScreen can warn the first time you run one.

This bucket is not affiliated with Scoop.

## AI-assisted development

Developed with Claude Code; every change is reviewed and merged by the maintainer.

## License

MIT, see [LICENSE](LICENSE).
