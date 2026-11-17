# 🇺🇸 United States: Do Not Call Registry + TCPA

**Last checked:** 2026-11-17 · Sources: [sources.md](sources.md)

## What you can realistically get

| Possible | Not guaranteed / not possible |
|---|---|
| Fewer sales calls from legitimate companies | The Registry doesn't **block** calls, and scammers ignore it |
| A private lawsuit for up to **$500 per violating call** once you get **more than one** call within 12 months from or for the same company (47 U.S.C. § 227(c)(5)) | Triple damages: only if the court finds the violation willful or knowing, and only at its discretion |
| A separate claim for **prerecorded or robocall sales calls** without your written permission, Registry or not (47 U.S.C. § 227(b)(3)) | Tracing spoofed numbers: usually impossible without a subpoena |
| Demand letter → settlement, or small claims court without a lawyer | Payment from a company you can't identify |

A company has a defense if it proves it had reasonable procedures, used with due care, to prevent such calls. Courts also disagree on whether one call can count as more than one violation. Treat the numbers as a ceiling, not a promise.

---

## Step 1: Register (once, free)

1. Go to **DoNotCall.gov**, or call **1-888-382-1222** from the phone you want to register. It's free. Anyone charging you is a scam.
2. If you register online, click the confirmation link in the email **within 72 hours**.
3. Save the confirmation email. That's your **registration date**. You can check it later with "Verify Registration" on DoNotCall.gov.

- Your number shows up on the Registry the next day, but **sales calls can take up to 31 days to stop.** (Companies must use a copy of the Registry no older than 31 days.)
- Registration **never expires**. Cell phones are covered too.

**Calls that are still allowed:** political calls, charities, debt collectors, purely informational calls and surveys, as long as there is no sales pitch. Also allowed: companies you have an **established business relationship** with, meaning a purchase within the last **18 months** or an inquiry within the last **3 months**, and companies you gave **written permission** to call.

**Turn those off too:** Tell any company: *"Put me on your internal do-not-call list."* That ends the business-relationship exception. The company must honor the request within a reasonable time, no more than **10 business days**, and keep it for **5 years**. Write down the date, time and the name of the person you spoke to.

## Step 2: Log every unwanted call or text

For each call, write down:
- Date, time, caller ID number
- **Who they said they were calling for.** Ask politely: *"What company are you calling on behalf of?"*
- What they were selling
- Whether it was a **live person or a prerecorded voice** (prerecorded calls are a separate claim)
- Whether you asked to be put on their do-not-call list

📱 Take a screenshot of your call history. For texts, screenshot the message with the sender and timestamp visible. **Don't click links.**

⚠️ **About recording calls:** Federal law allows recording a call you're part of, but about a dozen states require **everyone's consent** (including California, Florida, Pennsylvania, Washington and Massachusetts). If you or the caller might be in one of those states, don't record unless you have the caller's clear consent. Saying "this call is being recorded" isn't automatically enough everywhere. When in doubt, use screenshots and written notes instead.

Use [templates/call-log.csv](templates/call-log.csv). Tell the agent "they called at 2:05 pm from …, selling …" and it adds the row for you.

## Step 3: Identify who is behind the calls

You need the **legal entity** to send a demand letter or sue. Checklist: [core/caller-research.md](../../core/caller-research.md). US-specific sources:
- The company's website footer, privacy policy or terms page (legal name and address)
- Your **state's Secretary of State** business search (legal name and **registered agent** for service)
- FCC Robocall Mitigation Database (for the phone carrier, when relevant)
- Sellers are often liable for calls made **on their behalf** by lead generators. Log both names.

If the trail ends at a spoofed number, mark it ⛔ and keep logging.

## Step 4: Report, demand, or sue

**Report (free, no money for you, helps enforcement):**
- FTC: the reporting form on DoNotCall.gov (if you lost money: ReportFraud.ftc.gov)
- FCC: consumercomplaints.fcc.gov
- Your state attorney general

**Demand letter:** Send a factual letter to the company's registered agent listing each call and the damages you're claiming, and offer to settle before you sue. Template: [templates/demand-letter.md](templates/demand-letter.md).

**Small claims court:** You can bring TCPA claims in state court "if otherwise permitted by the laws or rules of court of a State," and many people use small claims, where dollar limits vary by state. Bring your log, screenshots and Registry confirmation.

**Talk to a lawyer** if there are many calls or robocalls. Many TCPA attorneys work on contingency, so you pay nothing upfront.

**Deadline:** TCPA claims are generally treated as having a **4-year** limitation period (28 U.S.C. § 1658). Confirm this for your case with an attorney.

## Is it a scam?

If the caller asks for card numbers, codes, gift cards or payment, or claims to be the IRS, Social Security, your bank or the police, it's not telemarketing. Hang up, report it at **ReportFraud.ftc.gov**, and call your bank using the number on your card.

## Not covered yet

Several states have their own, stronger telemarketing laws ("mini-TCPAs"). They aren't covered here yet. Contributions welcome, with sources.

## Use the agent

Paste [prompts/agent-prompt.md](prompts/agent-prompt.md) into Claude, ChatGPT or Gemini.
