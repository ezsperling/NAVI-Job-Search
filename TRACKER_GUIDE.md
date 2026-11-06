# Your private application tracker

A tracker is your spreadsheet of jobs, evidence, and next steps. Start by importing the [blank CSV](NAVI_Applications.csv) into an empty Google Sheets tab named **NAVI Applications**. It contains headers only. Keep your own sheet private and supply its link to ChatGPT only when useful.

You can ask ChatGPT to format a connected sheet if editing is supported. Otherwise, use these settings yourself. This file does not create or connect a live spreadsheet.

## The columns

| Column | Header | What to enter |
| --- | --- | --- |
| A | Company | Employer name |
| B | Job Title | Official role title |
| C | Requisition ID | Employer's job reference number; keep as text |
| D | Official Posting URL | Link from the company careers site |
| E | Status | Preparing, Applied, Under Review, Screening, Interviewing, Assessment, Offer, Rejected, Closed, or Withdrawn |
| F | Date Applied | Supported local application date; leave unknown dates blank |
| G | Salary Min | Posted annual base minimum, when known |
| H | Salary Max | Posted annual base maximum, when known |
| I | Work Arrangement | Remote/hybrid/onsite and posted geography |
| J | State Eligible | Eligibility for your state/country with evidence, or Unconfirmed |
| K | Resume Version/Link | Saved version and prepared/submitted evidence level |
| L | Contact | Verified recruiter/referral, if known |
| M | Next Action | Specific action and who owns it |
| N | Follow-up Date | Planning date unless identified as employer deadline |
| O | Interview Date | Date; exact time/time zone in Notes |
| P | Confirmation Evidence/Link | Receipt/page or labeled candidate report |
| Q | Application Key | Consistent company plus reference number |
| R | Last Updated | Last successful record reconciliation |
| S | Updated By | Person or assistant |
| T | Notes | Evidence gaps, timestamps, deadlines, outcome dates, and priority |
| U | Live Deck URL | Optional application-specific presentation link |
| V | Archived Deck/Files | Saved files or private archive folder link |
| W | Saved JD | Complete dated description or explicit recovery gap |
| X | Company Folder/Planned Path | Actual private role folder |
| Y | Last Employer Email | Latest relevant message date; may be automated |
| Z | Site Review Date | Optional deck retirement review planning date |
| AA | Deck/Site Status | Live, archived, review pending, or not applicable |

Your minimum acceptable salary belongs in your private profile; G:H contain the employer's published range. Do not convert unknown pay to zero. You may rename State Eligible to your state, but keep the meaning clear.

## Keep it readable

Freeze the top row and first two columns. Use a consistent 10-point font, bold headers, clipped text, and compact 24-pixel body rows. Put long evidence details in cell notes or the application record. Suggested column widths in pixels: A 150; B 280; C 130; D 220; E 145; F 105; G:H 110; I:J 145; K:L 200; M 320; N:O 110; P 230; Q 220; R 105; S 100; T 360; U:X 220; Y:Z 115; AA 240. These are starting settings; preserve existing user-approved formatting later.

Use dates for F, N, O, R, Y, Z, such as `M/d/yyyy`. Use currency/numbers for G:H. Keep C and Q as plain text so leading zeros and hyphens survive. Add a filter over the populated table.

Use these status colors with conditional formatting on E2:E1000, or a bounded range matching your sheet:

| Color | Status group |
| --- | --- |
| Green #D8EFDB | Applied, Under Review, Screening, Interviewing, Assessment, Offer |
| Beige #EFEDE0 | Preparing |
| Gray #E8EAEF | Closed, Withdrawn |
| Muted red #F4E5E2 | Rejected |

Ask ChatGPT to create rules for those exact labels if it can edit. Plain-text cells keep the view compact; color indicates stage, not certainty about a hiring outcome.

## Avoid duplicates and keep dates straight

An application key might be `example-health|R1001`. Match company names and ID case/spacing consistently, preserving the raw ID in C. If the ID is unknown, compare company, title, posting URL, and date; record a provisional key. Update the same record when the ID is recovered.

Sort **all populated columns A:AA together**, excluding the header, by Date Applied newest first. Keep undated Preparing/unknown-date rows at the bottom and preserve existing order for equal dates. Never sort only the date column. Store exact within-day timestamps in Notes.

An employer receipt supports an application, not the exact uploaded file contents. An automatic email does not prove human review. A candidate report is evidence when labeled as such. No email is not rejection. Use file creation dates as historical proxies only when explicitly authorized and labeled; a recent cloud copy date is not a past application date.

## Deck retirement review

Set Z for review at explicit rejection/closure, or 60 calendar days after application or the latest substantive hiring update, whichever is later. Record the substantive update's source/date in the application record. **Do not use Y automatically:** the latest employer email might be a routine acknowledgment or job alert. An ongoing interview, offer, or agreed future timeline can change the review decision.

The date does not remove a site or create a reminder. Archive first and obtain approval before unpublishing. Never retire a shared portfolio for one application's closure.

## After every update

Confirm the existing application was matched, reread the changed row, check links, and preserve the layout. If an edit had an uncertain result, check the current state before retrying. Keep status history and the checklist in the role folder. Track inbox check windows separately in a private activity log so missed periods can be recovered.
