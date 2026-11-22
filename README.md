# Policy Summary 保单摘要

A one-page web app for Malaysian insurance advisors. Upload a client's policy documents and get, in a few minutes:

1. **保单总览 Policy summary:** insurer, start date, owner, insured, beneficiary and premium for up to 4 policies.
2. **保障利益 Benefits table:** life/TPD, critical illness, medical card, hospital income, waiver, accident cover, with totals.
3. **每月缴费日历 Monthly payment calendar:** what is due each month for the next 12 months.
4. **保障缺口分析 Coverage shortfall:** current cover against common rules of thumb, with plain-language advice.
5. **需确认资料 Items to confirm:** anything blank, unclear or contradictory. The app never guesses a figure.

If the documents include a restructured (调整后) version, current and proposed are compared side by side.

## How to use

1. Open the site.
2. Paste your **Anthropic API key** (create one at console.anthropic.com → API Keys). It is kept only in your own browser and sent only to Anthropic.
3. Upload policy PDFs, photos/screenshots (JPG/PNG) or Excel, or paste text.
4. Tap **读取保单 Read policies**, then check the yellow cells. Fix anything under **修改数字 Edit figures**.
5. **复制摘要** copies a WhatsApp summary. **下载报告** saves the report as an HTML file you can print to PDF.

Cost: each review is billed to your own API key, usually about RM0.50–2 depending on document size.

## Privacy

- Everything runs in your browser. There is no server and nothing is stored on GitHub.
- Documents go only to Anthropic's API, to be read.
- The app drops IC numbers and keeps only the last 4 digits of each policy number.
- "Recent reviews" are saved only on the device you use.

## Benchmarks used

Life/TPD 10× annual income · critical illness 5× annual income (women's/specific riders not counted) · medical card ≥ RM1.5M per year · personal accident ≥ RM100k · premiums ≤ 15% of income. These are general rules of thumb, not company or regulatory requirements.

**For reference only. The insurer's policy contract always prevails.**
