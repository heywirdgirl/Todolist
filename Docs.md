```
docs/
├── product/
│   ├── PRD.md
│   ├── USER_STORIES.md
│   └── ERROR_HANDLING_MAP.md
│
├── technical/
│   ├── TECH_STACK.md
│   ├── ARCHITECTURE.md
│   ├── DATA_SCHEMA.md
│   ├── API_CONTRACT.md
│   ├── STATE_MANAGEMENT_MAP.md
│   ├── AUTH_FLOW.md
│   ├── NAMING_CONVENTIONS.md
│   └── DEPENDENCY_LIST.md
│
├── ai/
│   ├── AGENT_BRIEFING.md        ← paste đầu mỗi session
│   ├── AGENT_RULES.md           ← luật cứng AI không được phá
│   └── DECISIONS.md             ← log mọi quyết định kiến trúc
│
├── design/
│   ├── ui-screenshots/          ← ảnh Figma hoặc màn hình
│   └── UI_BEHAVIOR_NOTES.md     ← ghi chú hành vi từng màn hình
│
└── ops/
    ├── ENV_VARIABLES.md         ← danh sách .env cần có
    └── SETUP.md                 ← hướng dẫn chạy local
```

---

Kèm theo trong mỗi feature:

```
features/
├── timer/
│   └── README-AI.md
├── auth/
│   └── README-AI.md
└── cycles/
    └── README-AI.md
```

---

Và 2 file gốc ở root:

```
/
├── AGENT_BRIEFING.md   ← symlink hoặc copy từ docs/ai/
└── .env.example
```