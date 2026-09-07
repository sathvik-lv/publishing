# publishing — public research dashboards

Public research dashboards, linked from the GitHub line on the owner's resume.
`index.html` is the hub; each dashboard is its own page.

**This repo is public and is read by strangers.** Signal inputs, parameters, data
sources and repo internals stay private — only rendered results are published. Pages
carry their own caveats rather than burying them (proxy-series badges, post-friction
central estimates, discarded contaminated selections). Figures come from the source
research repos; do not hand-edit numbers into the HTML.

## Cross-device sync — read this first

This repo is worked on from **three devices**: **Windows PC**, **MacBook**, and
**Mobile** (Claude on the web/phone). They share no chat history, no memory and no
disk. `WORKLOG.md` at the repo root is the *only* thing that carries context between
them, so it is treated as part of the code, not as a diary.

**Start of every session, before touching anything:**

1. `git pull` — never begin from a stale checkout.
2. Read `WORKLOG.md` from the top until you have the current state. Newest entries
   are first.
3. Treat it as authoritative. **Work recorded there is done** — re-deriving it,
   re-running it or "just double-checking" it is waste, not diligence. Decisions
   recorded as rejected stay rejected unless there is a stated reason to revisit.
4. Read the newest entry's **Next** line before planning: it names work already
   claimed or in flight on another device.

**End of every session that changed anything** — append a new entry at the *top* of
`WORKLOG.md`, under the header, in this shape:

```markdown
## YYYY-MM-DD — <Windows PC | MacBook | Mobile> (short topic)

- What changed, and the reasoning behind anything non-obvious.
- What was tried and rejected, and why — so the next device does not retry it.
- **Next:** the concrete next step, or `nothing open`.
```

then **commit and push**. An entry that is not pushed does not exist to the other two
devices — that is the single most common way work gets repeated.

Use exactly one of `Windows PC`, `MacBook` or `Mobile` as the device label. The
`brain` repo parses that field to build the cross-repo timeline and open-threads
view, and an unrecognised label drops the entry into `unknown`.

**Ask before re-doing.** If something looks unfinished but the worklog says it was
completed, ask rather than redo — the other device may simply not have pushed yet.
