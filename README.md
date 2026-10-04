# FC 26 Palermo Squad Manager

**Diagnose → Prioritise → Shortlist → Decide → Stop**

A functional Squad Analysis & Transfer Management system built specifically for your FC 26 Palermo career mode.

## Features

### 1. Squad Entry
- Add players with: Name, Position, OVR, Age, Squad Status, Role, Notes
- Secondary positions for versatility tracking
- View and manage your entire squad in one table
- Import/Export squad as JSON

### 2. Squad Positional Analysis
Evaluates every position on **three tiers**:

- **🟢 Starter** — Is there someone good enough to start?
- **🟠 Natural Rotation** — Do we have a usable backup?
- **🔵 Emergency Cover** — Can another squad player realistically fill in?

Each position gets a **verdict**:
- 🔴 **Critical** — No starter
- 🟠 **Depth Risk** — Starter exists, no natural rotation/emergency cover
- 🟡 **Adequate** — Starter + emergency cover (no natural backup)
- 🟢 **Covered** — Complete depth chart

### 3. Now/Next/Future Timeline

**NOW** — This transfer window
- Critical gaps (missing starters)
- Depth risks (one starter, no cover)

**NEXT** — 1-2 seasons ahead
- Succession risks (aging starters with no younger heir)
- Declining backups

**FUTURE** — Long-term
- Blocked youth prospects
- Development pathways
- Loan/positional shift recommendations

### 4. Transfer Priorities

Generated intelligently based on:
- **Priority 1**: Actual starter gaps (must sign)
- **Priority 2**: Rotation risks (only if fixture congestion/injuries); otherwise wait
- **Priority 3**: Long-term succession (plan ahead, don't panic buy)

**Anti-Overthinking Rule:**
- Maximum 3 permanent signings per window
- Once a need is filled, stop shopping
- Existing squad versatility counts as depth

### 5. Palermo Recruitment Rules

Hard-coded philosophy:
- ✓ Only sign if there's a genuine squad reason
- ✓ Prioritise Italian/Serie A/Serie B markets
- ✓ Focus on young players & development
- ✓ Don't automatically sell veterans; keep if useful
- ✓ Role compatibility > OVR rating
- ✓ Loans are valid solutions
- ✓ One-in, one-out only if needed

## How to Use

### Local
Open `index.html` in any modern browser.

### Live
Deploy to GitHub Pages or any static host.

## Workflow

1. **Enter your squad once** → Tab: Squad Entry
2. **Review positional analysis** → Tab: Squad Analysis
3. **Check timeline risks** → Tab: Now/Next/Future
4. **Identify actual transfer needs** → Tab: Transfer Priorities
5. **Execute transfers based on priorities**
6. **Update squad, reassess, repeat**

## Key Distinction

This app asks:

**"Does Palermo actually need to make a transfer here?"**

Not:

**"Is there an empty slot at this position?"**

The difference:
- Empty RW slot ≠ must buy RW
- Almqvist (72) starting RW + CAM backup (68) ≠ automatic need for rotation RW
- Position covered by versatility ≠ must sign natural position player

## Export/Import

Save your squad data as JSON and reload it later.

Useful for:
- Tracking squad changes over time
- Testing different transfers scenarios
- Keeping backups of your analysis

## Philosophy

Built to stop overthinking and prevent:
- Buying 5 alternatives for 1 need
- Automatically filling every empty slot
- Panic buying for future risks
- Treating every backup as insufficient

Instead, it focuses on:
- Actual gaps vs perceived gaps
- Role & playstyle fit
- Realistic squad depth (starter + 1-2 covers)
- Long-term planning without panic

---

**Your mantra: Diagnose → Prioritise → Shortlist → Decide → Stop**

This app is built around it.
