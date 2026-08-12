# myskill

A personal collection of reusable Agent Skills.

Each skill lives in its own directory so it can be reviewed, modified, and installed independently.

## Skills

| Skill | Description | Source |
|---|---|---|
| [`pristine`](./pristine/) | First-Time Principle: root-cause fixes, single source of truth, no patch piles or residue. | [`newbanser/pristine-skill`](https://github.com/newbanser/pristine-skill) |
| [`gathered-scenes-zine`](./gathered-scenes-zine/) | Visual zine creation skills with real-scene collage and image-distillation workflows. | [`Zeejay0/gathered-scenes-zine-skill`](https://github.com/Zeejay0/gathered-scenes-zine-skill) |

## Layout

```text
myskill/
├── README.md
├── pristine/
│   ├── SKILL.md
│   ├── README.md
│   ├── README.en.md
│   ├── LICENSE
│   ├── cover.png
│   ├── examples/
│   │   └── before-after.md
│   └── scripts/
│       ├── pristine-scan.js
│       └── session-watch.js
└── gathered-scenes-zine/
    ├── README.md
    ├── README.en.md
    ├── LICENSE
    ├── assets/
    ├── examples/
    └── skills/
        ├── scene-distillation-zine-v1-3/
        └── scenes-gathered-zine-v1-3/
```

> Third-party skills retain their original license and attribution inside their own directories.
