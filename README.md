# Beyond Paper

A free web tool that helps skilled people who lost their certificates, IDs and records show what they can do.

Built for the Power Learn Project Africa Mini Hackathon, "Unlocking Displaced Talent: Pathways for Skilled Refugees" (November 24 to 27, 2026).

## The problem

Many skilled refugees fled without their documents. Credential recognition, job applications and professional registration usually start with paperwork, so people with years of real experience can be treated as if they have none.

## What it does

Beyond Paper lets a person build a skills portfolio without the paperwork. It works on a phone or a computer, in five short steps:

1. **Your details.** Name, profession, years of experience, last workplace, country and an optional photo.
2. **Your skills.** Rate the core tasks of the profession honestly, then answer two practical scenarios from the same field.
3. **Your work.** Add up to six case studies. Each has the problem, what the person did, the result, skills and tools used, an optional reference and photos of the work.
4. **People and documents.** Add a supervisor and a colleague with their contact details. Mark which documents are missing, say who issued them, attach photos of any copies, and explain in your own words how they were lost.
5. **Review and build.** Confirm that everything is true, build the portfolio, sign it and save it as a PDF.

The tool supports 20 professions plus an "Other" option where people write their own profession and tasks:

- **Health:** nurse or midwife, medical doctor or clinical officer, pharmacist, laboratory technologist
- **Education:** teacher
- **Engineering and trades:** civil engineer, electrical engineer, mechanical engineer, electrician, automotive mechanic
- **Technology:** software developer
- **Business and law:** accountant, lawyer or paralegal, project manager
- **Community and land:** social worker, agricultural officer or agronomist, veterinary officer
- **Media and language:** journalist, translator or interpreter
- **Hospitality:** chef or cook

## What the person receives

The result has two parts.

**The portfolio** contains only what the person entered: a summary, the tasks they have actually done, their scenario answers, case studies with photos, referees, missing documents and their statement. It ends with a declaration and a confirmation block for the supervisor and the colleague. Each has a signature pad, so people can sign on screen with a finger, mouse or pen, or print the page and sign on paper.

**The next steps** hold guidance: how to show skills without documents, a recovery plan that names who to contact for each missing document, and a draft letter asking a former employer for a reference.

Both parts can be saved as a PDF or printed. The PDF is generated in the browser and supports any script, including Arabic.

## Showing skills without ID or certificates

The portfolio shows skills in layers: case studies, practical verification, people who can confirm the work, and a recommendation to ask for a live skills test or interview. It does not prove identity. Identity and skills are usually checked separately, so the tool tells users to ask their registering agency or a recognised refugee or community organisation how their identity can be confirmed.

## Hackathon tracks it supports

- **Credential recognition:** builds structured evidence of skills when documents are missing and points users to alternative assessment routes.
- **Local professional networks:** includes referees who can confirm the person's work and encourages finding former colleagues.
- **Legal and financial access:** covers identity and registration documents and warns users to confirm fees and rules before paying for any assessment.

## Important limits

- The portfolio is a **self-declared** document. The tool cannot approve or certify it. It becomes stronger when backed by the people who sign it and by an assessment from a recognised authority.
- The tool gives **general guidance, not legal advice**. Recognition rules differ by country, profession and authority, so users must confirm requirements with the authority that will assess them.
- It does not guarantee that any authority or employer will recognise a person's skills.
- The practical scenarios are general and are not official exam content. They should be reviewed by professionals in each field.

## Privacy

Everything a user enters, including photos and signatures, is processed in the browser. The site has no server component, no database, no accounts, no cookies and no analytics. Nothing is sent anywhere. Attached files are not saved and disappear when the page is closed or refreshed, so users should save their portfolio as a PDF before leaving. The hosting provider may keep standard technical logs, as any website host does. The site includes a privacy policy page and a terms and conditions page.

## How it is built

- A single `index.html` file with plain HTML, CSS and JavaScript.
- No frameworks, no build step and no external dependencies.
- Built with Claude as the AI development tool.
- Light and dark themes that follow the device setting.
- Responsive layout for phones, computers and large screens, with a print stylesheet.
- A built-in PDF generator and signature pads that work without any outside service.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

## Deploy with Vercel

1. Push this repository to GitHub, with `index.html` at the top level.
2. In Vercel, choose **Add New**, then **Project**, and import the repository.
3. Set **Framework Preset** to `Other`. Leave the **Build Command** and **Output Directory** empty.
4. Click **Deploy**. Vercel gives the site a `.vercel.app` address.
5. To use your own domain, open **Settings**, then **Domains**, add it, and create the DNS records that Vercel lists at your domain registrar.

The site is a single static file, so it also works on GitHub Pages, Netlify or any other static host.

## Roadmap

- Arabic, Somali, Swahili and French versions.
- Country guidance that links to official recognition authorities, each verified against its source.
- Scenarios and task lists reviewed by professionals in each field.
- Optional secure storage of portfolios, with its own privacy policy.
- An optional writing assistant that turns rough notes into clear wording, with a clear notice about data leaving the device.

## Files

- `index.html`: the whole application, including the privacy and terms pages.
- `README.md`: this file.

## Copyright

Copyright 2026 Ali Abdullah. All rights reserved.
