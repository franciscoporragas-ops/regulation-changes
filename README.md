# regulation-changes

A public, searchable tracker of legal regulatory changes for law firms, one country at a time (UK or Australia).

The design concept is in `mockup/index.html`.

## How it works

1. **Sources.** Official regulators, government and the published law only.
   - **UK:** SRA, Legal Services Board, HM Treasury, FCA, Companies House, OFSI, ICO, Home Office and legislation.gov.uk.
   - **Australia:** AUSTRAC, Legal Services Council, OAIC, Home Affairs, the state law societies and regulators, and the Federal Register of Legislation.
2. **Gathering.** Every morning, a script checks each source and keeps only what is new or changed. AI drafts the entry, and a person at Legl checks it against the source before it is published.
3. **Storage.** There is one record per change. When a change moves from proposed to decided to in force, the same record is updated and its history keeps every step with a date. Search and the ask box both read these records.
4. **Display.** At the top is an ask box. Below it are a "Now in force" highlight and the list of changes. The list can be filtered by:
   - **Stage:** in force, coming up, proposed or guidance.
   - **What the firm does:** for example, holds client money or does AML-regulated work.
   - **Topic.**

## Why filter by what the firm does

Most rules apply across practice areas. What decides whether a rule applies is what the firm does. For example: holding client money, doing AML-regulated work, acting for companies or reaching a size threshold. Each record lists who it applies to, and changes that apply to all firms always show.
