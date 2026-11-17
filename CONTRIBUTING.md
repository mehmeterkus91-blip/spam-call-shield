# Contributing

The most wanted contribution is **a new country**, especially EU member states. See [regions/eu/COUNTRY-TEMPLATE.md](regions/eu/COUNTRY-TEMPLATE.md).

## The one hard rule

**No legal claim without an official source.** Every deadline, amount and procedure must link to:
- the law or regulation text (official gazette or government legal database), or
- the regulator's own page (for example a data protection authority, consumer agency or telecom regulator).

Blogs and law firm articles can be extra context, but they never replace a primary source. Write the date you checked each source.

## Also important

- **Be honest about limits.** If citizens get no money, say so in the first table. If spoofed numbers can't be traced, say so.
- **Recording laws.** State clearly whether recording a call you are part of is legal in that country.
- **Privacy first.** Use placeholders in templates and fictional data in examples. Use reserved or obviously fake numbers, never real ones.
- **Keep the agent leashed.** Prompts must keep the rule that the agent never files, sends or calls without the user's explicit approval.
- **Local language plus English.** Write the region guide in the local language and add a short English summary at the top of its README.

## Pull request checklist

- [ ] Every legal statement has a source link and a check date in `sources.md`
- [ ] The "what can you realistically get" line is accurate and not hyped
- [ ] No real phone numbers, names or IDs
- [ ] The agent prompt keeps the approval rule from `core/agent-rules.md`
- [ ] The region is linked from the main README table

## Reporting an outdated fact

Open an issue titled `[outdated] <region>: <topic>` and add the new official source.
