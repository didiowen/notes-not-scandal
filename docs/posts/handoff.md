# Handoff — Weekly Journal Digest

## 2026-05-21 — today's bug fix

### Summary

- Cloud `daily-medical-lit` 07:00 run failed: PubMed MCP renamed to `mcp__claude_ai_PubMed__*`, no entry in committed `settings.json`.
- Two fixes shipped: PR #115 (MCP + Bash allowlist), PR #117 (PubMed `YYYY/MM/DD` + `pubdate` hyphenation).
- Local smoke test produced today's digest (40 articles), pushed to notes-not-scandal.

### Pending

- [ ] Verify tomorrow's cloud run (2026-05-22, 07:00 Asia/Taipei) — success = PR titled `journal digest 2026-05-22` merged on GitHub.

### Git

`2aa26a6 daily-medical-lit: fix date formats` · `claude-playground` · dirty: `.claude/skills/hematology-event/events.json`, `.claude/skills/tbmt-event/tbmt_events.json` _(unrelated calendar refresh)_

### Next session

Skill: `daily-medical-lit` — only needed if tomorrow's cloud run fails again

```sh
gh pr list --state merged --search "journal digest 2026-05-22" --json number,mergedAt
```

---

## 2026-05-19 — weekly-journal-digest subagent refactor

### Summary

- SKILL.md 重構為兩個平行 subagent（Subagent A: PubMed；Subagent B: Gmail）— PR #105
- 發現並修正 dedup/filter 交互 bug：newsletter Editorial 若有當週 PMID，會同時被 dedup 和 Step 3 過濾而從輸出消失
- Step 3 過濾移入 subagent（A3/B4），dedup 只比對 Original+Review — PR #106

### Pending

_Nothing pending._

### Git

`eb95402 fix: move Step 3 filtering into subagents` · `claude-playground` · clean

---

## 2026-05-19 — weekly digest newsletter link fixes

### Summary

- 2026-W20 digest：23 篇 newsletter 文章補齊 `[**NEJM Newsletter**](tracking_url)` 連結（PRs #89, #94, #95, #97）
- SKILL.md：加入 Gmail-link fallback 規則、newsletter 與 NEJM section title dedup 規則、連結格式修正、Step 2.5b Editorial 不過濾警告（PRs #90, #94, #96）
- 確認 NEJM Editorial/Perspective 可在 PubMed 找到（非索引延遲，是 agent 誤套過濾規則）

### Pending

- [x] Weekly digest 2026-05-18 — verify NEJM monthly sections render correctly in notes-not-scandal *(resolved 2026-05-19)*

### Git

Covered by PRs #89–#97 on `main`.
