# Set up NAVI in ChatGPT

You will create a private job-search workspace, a tracker, and a simple routine. Do one step at a time. You can stop after the first application and improve the system later.

## 1. Start a job-search conversation

Open ChatGPT. If **Projects** is available, create a project called **Job Search — NAVI**. A project keeps related chats, files, and instructions together. Start your job-search chats inside it.

Copy [PROJECT_INSTRUCTIONS.md](PROJECT_INSTRUCTIONS.md) into the project's instructions area, if available. Otherwise, paste it into the first chat and keep a private copy you can supply again. Upload or paste the [application standard](NAVI_APPLICATION_STANDARD.md) and your completed profile when useful. Menu names can vary; ask ChatGPT for help with the screen you see.

You can also begin in an ordinary chat. Do not assume a new chat knows your latest tracker or document versions: supply the current sources or authorized links when continuing.

## 2. Tell ChatGPT your preferences and evidence

Copy [My Job Search Profile](My_Job_Search_Profile.md), fill it in privately, and provide it to ChatGPT. Start with your target roles, location, work arrangement, minimum pay, resume, and any excluded employers. Add evidence of achievements as you go.

Use this request:

> Help me complete my private NAVI profile. Ask a few clear questions at a time. Separate my preferences from hard requirements, and do not guess missing facts or qualifications.

You do not need to provide government identifiers, passwords, financial account details, or unrelated personal records. Provide only the job-search information needed. Decide which contact details belong in materials shared with employers or the public.

## 3. Create your private folders

In Google Drive, create **Job Search**, then **02 — Companies**. Keep one folder per company and one subfolder per role:

```text
Job Search / 02 — Companies / Company / Role — Job Reference Number
```

A **requisition ID** is the employer's job reference number, often starting with R, JR, or digits. Save it exactly. If none is available, write **ID unknown** and keep the title, source link, and date.

Keep restricted-employer historical records separately if your profile requires it. Reuse existing folders rather than making duplicates.

## 4. Create your tracker

Create a private Google Sheet named **NAVI Applications**. Download the [blank tracker CSV](NAVI_Applications.csv), then import it into an **empty** tab named **NAVI Applications**. Do not replace an existing tracker. Use [TRACKER_GUIDE.md](TRACKER_GUIDE.md) for readable columns, dates, status colors, and sorting.

You can ask ChatGPT:

> Help me set up this blank tracker. Explain the columns in plain language. If you can edit my sheet, first confirm the correct account and empty destination. Preserve any existing data and formatting.

A prepared tracker file is not proof that a live Google Sheet was created or updated. Open the sheet and check the result.

## 5. Choose manual or connected access

**Manual:** upload your resume, paste the job description, and provide selected confirmation emails or screenshots. ChatGPT prepares text and tracker updates; you save or enter them. You can use NAVI this way without connecting your inbox.

**Connected:** where available, open ChatGPT's **Plugins** or connected-app area and find **Gmail** and **Google Drive**. In ChatGPT Work, select/install the relevant plugin and follow the provider sign-in prompts. Confirm the intended account and review the permissions. Ask ChatGPT to check whether it can search/read email, read the tracker, edit specific cells, and save files. Do not assume every account supports every action.

Use this capability check:

> Check what you can access for NAVI. My intended email account is [account], my tracker is [private URL], and my company folder is [private URL]. Tell me what you can read and edit. Do not send mail or change sharing. If a capability is missing, give me the manual step instead.

Never put passwords or access tokens in a chat or this repository. Use the service's secure sign-in flow. A pasted link or a project name alone does not grant access to private files or your computer.

## 6. Start with one role

Provide the official job posting and your current resume. Ask:

> Use the NAVI Application Standard for this role. Verify the posting, job reference number, location eligibility, and salary if available. Check for an existing application before adding a tracker row. Explain my strongest fit and gaps, then prepare materials grounded in my evidence. Mark the application Preparing. Save a checklist with a status and evidence for all 18 items. Do not submit.

If the posting cannot be opened, supply its complete text or PDF. Ask ChatGPT to label anything it could not verify. It must not treat a job-board alert as an application you submitted.

## 7. Review the form, then submit yourself

Check the final form, not just the resume. Verify employer/title/dates, education, required yes/no answers, contact details, portfolio links, and attachment names. Pay special attention to work authorization, licenses, internet requirements, and compensation questions. Do not answer something just because ChatGPT suggested it.

Use:

> Review this final application page against my approved materials. Flag parsing errors, missing fields, unsupported answers, and incorrect attachments. Ask me about unknown personal facts. Save every question and my final answer. Do not click Submit.

When ready, submit through the employer's official site and save the confirmation. Then say:

> I submitted [company/role/reference] on [date/time/time zone]. Here is the confirmation [or check my authorized email]. Update the existing row, save the evidence and final answers, and set a next action. Report any materials you cannot verify as submitted.

## 8. Keep it current

Return to the project and ask ChatGPT to reconcile new email and outcomes. If you want recurring checks, explicitly request a schedule in a supported tool and confirm it was actually created. A sentence in project instructions is not a running schedule. Without one, run the [inbox review prompt](PROMPTS.md) when you return.

If a connection fails, use selected copies and manual updates. Record the last successful check so the next review includes anything missed. Keep the originals and report gaps rather than inventing dates or outcomes.

## Definitions

| Word | Meaning |
| --- | --- |
| Prompt | A request you type into ChatGPT. |
| Tracker | Your spreadsheet of applications and next steps. |
| Requisition | The employer's reference number for a job. |
| ATS | The employer's application website, such as Workday or Greenhouse. Use it when the company links to it. |
| Archive | Your saved copy of a document or evidence. It does not mean deleting anything. |
| Evidence | A source supporting a fact, such as a role-specific receipt. |
| Prepared / submitted | A document you created / a document actually sent with an application. These are different. |
| Pending | Work still needed, with a next action. |

Product guidance checked November 5, 2026. See [official sources](SOURCES.md); availability and labels may change.
