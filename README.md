# myskill

A personal collection of reusable Agent Skills.

Each skill lives in its own directory so it can be reviewed, modified, and installed independently.

## Skills

| Skill | Description | Source |
|---|---|---|
| [`pristine`](./pristine/) | First-Time Principle: root-cause fixes, single source of truth, no patch piles or residue. | [`newbanser/pristine-skill`](https://github.com/newbanser/pristine-skill) |

## Layout

```text
myskill/
├── README.md
└── pristine/
    ├── SKILL.md
    ├── README.md
    ├── README.en.md
    ├── LICENSE
    ├── examples/
    │   └── before-after.md
    └── scripts/
        ├── pristine-scan.js
        └── session-watch.js
```

> Third-party skills retain their original license and attribution inside their own directories.
