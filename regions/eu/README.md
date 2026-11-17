# 🇪🇺 European Union: 🤝 contributions wanted

This region isn't ready yet. **Help us build it.** Each country needs someone who can check the official sources.

## Why the EU is different

The EU has 27 sets of telemarketing rules but **one powerful common tool: the GDPR.** Under the GDPR you can, in general:

- **Ask where your data came from:** a right of access that includes the source of the data (GDPR Art. 15)
- **Object to direct marketing.** The company must then stop using your data for marketing (GDPR Art. 21)
- **Demand erasure** (GDPR Art. 17)
- **Complain** to your national data protection authority (GDPR Art. 77)

Companies generally have **one month** to answer such requests (GDPR Art. 12(3)).

In many cases, the access request is the strongest tool. It forces the caller to reveal which data broker sold your number.

> ⚠️ The summary above is an outline to be verified. A contributor must check it against the [GDPR text on EUR-Lex](https://eur-lex.europa.eu/eli/reg/2016/679/oj) before it counts as ready.

## Country status

| Country | National opt-out register | Status | Maintainer |
|---|---|---|---|
| 🇩🇪 Germany | none; prior consent required for calls | 🤝 wanted | |
| 🇫🇷 France | Bloctel | 🤝 wanted | |
| 🇪🇸 Spain | Lista Robinson | 🤝 wanted | |
| 🇮🇹 Italy | Registro Pubblico delle Opposizioni | 🤝 wanted | |
| 🇳🇱 Netherlands | | 🤝 wanted | |
| others | | 🤝 wanted | |

The register names above haven't been verified yet either. Confirm them in your country's guide.

## How to add a country

1. Copy [COUNTRY-TEMPLATE.md](COUNTRY-TEMPLATE.md) to `regions/eu/<country-code>/README.md`, for example `regions/eu/fr/README.md`.
2. Fill in every section with **official sources** and the date you checked them.
3. Write a GDPR access + objection letter template in the local language.
4. Adapt an agent prompt (start from `regions/us/prompts/agent-prompt.md` and keep the hard rules from `core/agent-rules.md`).
5. Open a pull request. See [CONTRIBUTING.md](../../CONTRIBUTING.md).
