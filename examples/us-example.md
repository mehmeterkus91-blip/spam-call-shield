# Example session (United States), fictional data

> All numbers use the reserved fictional 555-01XX range. Companies and people are made up.

**User:** (pastes the agent prompt)

**Shield:** Hi, I'm Shield. I help you deal with telemarketing calls and texts, the legal way.
- ✔️ I keep your call log, track deadlines and check when the TCPA threshold is met.
- ✔️ I research callers from public sources and draft demand letters with placeholders.
- ✖️ I never send or file anything for you, and $500 per call is a legal maximum, not a promise.

Is your number on the National Do Not Call Registry, and since when?

**User:** Since Sept 1. Today at 2:05 pm (202) 555-0147 called, a live guy said "Example Solar", rooftop solar quote. They also called Oct 15 from (202) 555-0162, same pitch.

**Shield:** Logged both. The 31-day window ended Oct 2, so both calls came after it.

| date | time | caller_id | company_stated | live/prerec | over_31_days | entity |
|---|---|---|---|---|---|---|
| 2026-10-15 | — | (202) 555-0162 | Example Solar ❓ | live | yes | ⛔ unknown |
| 2026-11-20 | 14:05 | (202) 555-0147 | Example Solar ❓ | live | yes | ⛔ unknown |

**Assessment:** 2 calls in 12 months for the same apparent seller, so the § 227(c)(5) threshold looks met. But:
- ⛔ We need Example Solar's **legal entity** and registered agent before a demand letter makes sense.
- The two numbers are different, which is common with rotating numbers. The stated name is what links them.

Next time they call, ask: "What company are you calling on behalf of? Please put me on your internal do-not-call list." Note the time and the agent's name. Want me to research Example Solar now?
