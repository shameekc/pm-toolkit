# Impact Estimation Framework

**Purpose:** Estimate the business impact of new features before investing engineering time. Use it to build ROI models that inform prioritization and secure leadership buy-in.

---

## The Formula

```
Impact = Users Affected × Current Rate × Expected Lift × Value per Action
```

### Breaking It Down

**Users Affected**
- How many users will experience this feature?
- Consider adoption rate (not everyone uses every feature).

**Current Rate**
- What's the baseline metric you're trying to improve?
- Use historical data to establish the baseline.

**Expected Lift**
- How much will the feature improve the metric?
- Express as percentage points (e.g., 45% → 55% = +10pp).
- Base on similar features, competitor benchmarks, industry data.

**Value per Action**
- What's the business value of one more converted user?
- LTV, ACV, or downstream metrics.

---

## The Three-Scenario Approach

Never present a single number to leadership. Always model three scenarios:

### Pessimistic (20th percentile)
- Conservative adoption rate, modest lift, lower-bound assumptions.
- "Even in the worst case, here's the ROI."

### Realistic (50th percentile)
- Your best judgment. Median adoption and lift estimates.
- "This is what we expect to happen."

### Optimistic (80th percentile)
- Strong adoption and lift, upper-bound (but still realistic).
- "If things go well, here's the upside."

---

## Template

```markdown
## Impact Estimation: [Feature Name]

### Key Assumptions
| Input | Value | Source |
|-------|-------|--------|
| Monthly users affected | [number] | [source] |
| Baseline metric | [rate] | [source] |
| Engineering cost / month | [amount] | [source] |
| Build duration | [months] | [estimate] |
| Team size | [engineers] | [scope] |
| **Total investment** | **[amount]** | [calculation] |

### Scenarios
| Scenario | Adoption | Lift | Incremental users/mo | 3-year revenue | ROI |
|----------|----------|------|----------------------|----------------|-----|
| Pessimistic | [low %] | [+Xpp] | [number] | $[amount] | [X]x |
| Realistic | [mid %] | [+Xpp] | [number] | $[amount] | [X]x |
| Optimistic | [high %] | [+Xpp] | [number] | $[amount] | [X]x |

### Strategic Value (Beyond ROI)
- [Non-financial value: learning, competitive positioning, etc.]

### Sensitivity Notes
- [What happens if adoption is lower? If LTV is higher?]
```

---

## Key Principles

- **Be conservative:** Better to under-promise, over-deliver. Pessimistic case should still show positive ROI if you're recommending the feature.
- **Show your work:** Document all assumptions; make the model auditable.
- **Update post-launch:** Track actual vs projected; calibrate your estimation skills.
- **Strategic value matters:** Not everything is about immediate ROI.

---

## Common Pitfalls

- Single-point estimates (always show a range)
- Optimistic bias (be honest about realistic outcomes)
- Ignoring adoption (not everyone uses every feature)
- Forgetting costs (include engineering time, maintenance, support)
- No validation (test assumptions with data when possible)

---

## When to Use

- Features requiring >2 weeks engineering time
- When leadership asks "What's the business case?"
- Prioritization decisions between competing ideas
- Securing headcount or budget

**Skip for:** Small bug fixes, hygiene work, when you need to move fast and iterate.
