<div align="center">
  <img src="https://raw.githubusercontent.com/Obelyth/.github/main/profile/assets/obelyth-banner.png" alt="OBELYTH — Data. Infrastructure. Assured." width="900">
</div>

<div align="center">

**THE STRUCTURAL LAYER FOR MODERN AI DATA SYSTEMS**

Capture, validate, and ship robot-manipulation data with full operational assurance.

</div>

---

### WHAT WE BUILD

We work at the seam where physical data collection meets the training pipeline: the field rigs, the
operations layer around them, and the memory infrastructure that keeps operators and agents working
from the same record.

**Capture.** Multi-camera field rigs. Bluetooth pairing, network-attached camera control, synchronized
start and stop across a cohort, tagging mid-take, and an ingest loop built so footage is never
silently lost.

**Validate.** Claim-gated collection pools. Reserve, lock, auto-return, reconcile at end of day.
Coverage is measured against target, not against optimism.

**Ship.** Verification is a first-class state. A capture is confirmed, unverified, or failed — and we
never record the first without evidence.

### OPEN SOURCE

| Repository | What it does | Stack |
| :--- | :--- | :--- |
| **[cortex](https://github.com/Obelyth/cortex)** | A private markdown knowledge base served to every Claude surface over MCP, with a read path that proves its own citations. | `TypeScript` `MCP` `AGPL-3.0` |
| **[cold-read](https://github.com/Obelyth/cold-read)** | Rewrites context-heavy text so a reader with zero background can follow it, and flags what is missing instead of inventing it. | `Shell` `MIT` |
| **[taskflow](https://github.com/Obelyth/taskflow)** | Claim-gated collection pool, in production at [tisktask.space](https://tisktask.space). Internal tool; source private. | `Next.js` `Apps Script` |
| **[grain-community](https://github.com/Obelyth/grain-community)** | The crowd's read on any video — community verdict on AI-generated media. Docs, releases, and feedback. | `PWA` `Media provenance` |

### HOW WE WORK

- **Honest state over optimistic state.** `unverified` is a valid answer. `confirmed` requires evidence.
- **Design for the after.** Setup is 20 percent of a build. Day-2 operations are the other 80 — what
  drifts, what gets fat-fingered, what has to heal itself without a maintainer on the line.
- **Fail loudly into a log.** Silent failure is the only unrecoverable kind.
- **Structure over decoration.** Hairlines, hierarchy, and a single accent. Nothing on screen that is
  not load-bearing.

---

<div align="center">
  <sub><code>DATA. INFRASTRUCTURE. ASSURED.</code></sub>
</div>
