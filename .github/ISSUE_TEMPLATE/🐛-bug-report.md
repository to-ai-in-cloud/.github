---
name: "\U0001F41B Bug report"
about: Report a reproducible problem or regression
title: "[Bug] ◄ BRIEF SUMMARY ►"
labels: bug
assignees: ''

---

## 1️⃣ Summary
<!-- One concise sentence describing the bug. -->
<WRITE A CLEAR DESCRIPTION HERE>

---

## 2️⃣ Steps to Reproduce
<!-- Bullet or numbered list that anyone can follow to trigger the bug. -->
1. …
2. …
3. …

> **Tip:** If code or cURL is needed, paste a **minimal** snippet between triple back-ticks.

---

## 3️⃣ Current Behaviour
<!-- What *actually* happens after following the steps above. -->
<OBSERVED RESULT>

### Expected Behaviour
<!-- What *should* have happened instead. -->
<EXPECTED RESULT>

---

## 4️⃣ Screenshots / Logs
<!-- Drag-and-drop images or paste log lines that show the failure. -->
<details>
<summary>Click to expand logs</summary>

```text
PASTE RELEVANT LOGS HERE
```
</details>

---

## 5️⃣ Environment ⏲️
| Item | Value |
|------|-------|
| **App / API version** | <vX.Y.Z or commit SHA> |
| **Deployment** | prod / staging / local |
| **OS / Browser** | <e.g. Windows 11 / Chrome 124> |
| **DB / Service versions** | <PostgreSQL 16, Redis 7> |

---

## 6️⃣ Impact & Severity
<!-- How many users affected? Is there a workaround? -->
<LOW / MEDIUM / HIGH — EXPLAIN>

---

## 7️⃣ Tried / Possible Fix
<!-- Optional: notes, bisect results, or ideas for a fix. -->
<ANY INVESTIGATION NOTES>

---

## 8️⃣ Definition of Done ✅
- [ ] Reproduction case committed (failing test or script)
- [ ] Fix implemented & builds pass
- [ ] **Regression test** added
- [ ] Docs / changelog updated
- [ ] Deployed to staging & verified
- [ ] QA sign-off

---

<!--
TEMPLATE HINTS – these comments disappear in the rendered issue:

• Keep the title short but precise: “[Bug] 500 on /checkout when cart is empty”.
• Security‑sensitive? E‑mail security@your‑org.com instead of opening a public issue.
-->
