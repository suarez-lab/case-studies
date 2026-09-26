# Case Studies

**English** · [Español](README.es.md)

Production systems we designed, built and operate. Each one states the constraints that
shaped it, the alternatives we rejected and why, and what it cost us to be wrong.

**Two rules govern this repository.** Clients are identified by sector, geography and
year only — never by name, even where we have permission. And a figure is published only
if it was measured: numbers here come from code or from production data we can re-run,
not from a proposal or a status report.

| Case | Sector · Geography | The short version |
| --- | --- | --- |
| [Classifying real-estate leads from WhatsApp noise](whatsapp-lead-classification/README.md) | `Real estate` · `Latin America` | Rules first, model last: 11% miss rate and 1/12th the LLM bill |
| [Collections messaging on WhatsApp](debt-collection-automation/README.md) | `Financial services` · `Europe` | One message every nine minutes; a coverage gap closed from 179 loans to 13 |
| [Two document channels into one back office](document-ingestion-ai/README.md) | `Real estate` · `Europe` | An LLM that fills a form but is never allowed to write to the database |
| [The evaluation loop we built first](market-signal-pipeline/README.md) | `Financial markets` · `Global` | It told us the signals were right 46.1% of the time — below a coin flip |
| [A native social app with no over-the-air escape hatch](native-social-app/README.md) | `Consumer / social` · `Europe` | Every JavaScript change is a store submission |
| [Does the assistant actually converse, or just dispatch?](conversational-quality-evaluation/README.md) | `Real estate` · `Latin America` | Measuring dialogue instead of accuracy |

## How to read these

Every case follows the same structure, so they can be compared: *problem → constraints →
architecture → decisions worth explaining → results → the incident worth reading → what
we would do differently*.

The **decisions** section is the one we would point a reviewer at. It names the
alternative we considered, why we rejected it, and what the choice cost us — because an
architecture note that only lists what was chosen is a sales document.

The **incident** section exists because systems teach you things documentation does not.
Where a lesson generalises beyond one client, it also has an entry in the
[engineering handbook](https://github.com/suarez-lab/engineering-handbook).

## Elsewhere

- [engineering-handbook](https://github.com/suarez-lab/engineering-handbook) — what production taught us, one entry per lesson
- [reference-architectures](https://github.com/suarez-lab/reference-architectures) — shapes we have built more than once
- [toolkit](https://github.com/suarez-lab/toolkit) — what we actually build with, counted from manifests
- [profiles](https://github.com/suarez-lab/profiles) — who we are

<sub>Clients are identified by sector only, by our own policy. No client is named in this repository.</sub>
<sub>No client code, credentials or user data appears in these documents.</sub>
