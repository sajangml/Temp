Here is a **concise, clean version** suitable for direct inclusion in the document:

---

### Version Numbering Standard

GAT Layer-2 configuration automation uses semantic versioning in the format:

```
MAJOR.MINOR.PATCH
```

* **MAJOR** – Breaking or structural changes
* **MINOR** – New features or non-breaking enhancements
* **PATCH** – Bug fixes or minor corrections

Each version maps to a specific Git commit or tag and is updated before changes are committed. Rollback is achieved by reverting to a previous version and regenerating configurations.

---

If you want it **even shorter (2–3 lines)**, I can compress it further.


Examples

1.0.0 – Initial approved baseline

1.1.0 – New site or feature added

1.1.1 – Minor fix or correction

2.0.0 – Major redesign or breaking change

Version Management Rules

The current version is documented in:

The repository README

Commit messages (where applicable)

Generated configuration headers (optional but recommended)

Version changes are applied before committing to Git

Each version corresponds to a specific Git commit or tag

Rollback is performed by reverting to a previous version and regenerating configurations
