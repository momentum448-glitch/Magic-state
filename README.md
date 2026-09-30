# Magic-state

Public mutable state store for the Magic live-performance prototype.

## Rules

- Contains only non-sensitive trick state.
- Never store GitHub tokens, personal data, or application secrets here.
- One JSON file per performer channel under `channels/`.
- The performer write token should be scoped to this repository only.
