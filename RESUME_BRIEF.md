# Resume brief template

This repository is a reusable resume template. Do not infer, invent, or prefill the user's identity, goals, work history, achievements, metrics, links, or target roles.

## Agent instructions

Before editing `resume.tex`, inspect the existing file and ask the user only for information that is missing or ambiguous. Ask questions in small, relevant groups rather than presenting a long questionnaire. Do not write placeholder career goals on the user's behalf.

Use this sequence:

1. Ask what the resume is for: target role, job description or company, country or market, and preferred length.
2. Ask for contact details the user wants published: name, email, phone, location, and professional profile links. Explain that every field is optional.
3. Gather experience in reverse chronological order. For each role, ask for title, organization, location or remote status, dates, domain, responsibilities, individual contributions, tools, scale, and measurable results.
4. Gather projects, education, certifications, awards, publications, and skills only when relevant to the target role.
5. If a claim is vague, ask a focused follow-up about scope, outcome, evidence, and the user's personal contribution before turning it into a resume bullet.
6. Confirm sensitive or unusual content before including it.
7. Summarize the collected facts and proposed section order for confirmation before drafting substantial resume content.

## Required safeguards

- Never invent employers, dates, titles, technologies, achievements, metrics, links, goals, or qualifications.
- Never copy example text into the finished resume as if it were factual.
- Distinguish individual contributions from team or company outcomes.
- Mark uncertain facts as `[TO CONFIRM]` in working notes, not as final resume claims.
- Include only contact details and links the user explicitly approves for publication.
- Treat the job description as a prioritization source, not as evidence that the user has a skill or achievement.
- Ask before removing meaningful user content when tailoring or shortening the resume.

## Drafting defaults

Use these only when the user has not requested a different format:

- Single-column, ATS-readable layout with standard section names
- Reverse chronological experience
- One page for early-career candidates; allow two pages when experience warrants it
- Concise bullets using action + contribution + context + result
- Metrics only when supplied or confirmed by the user
- No photo, age, marital status, full street address, references, or objective statement
- Plain, professional language without personal pronouns or unsupported adjectives

## Completion check

Before finalizing, ask the user to verify:

- spelling of names and organizations
- contact details and public links
- job titles, locations, and dates
- ownership and attribution of work
- metrics and business outcomes
- education and certification details
- target-role relevance
- consent to include any sensitive information

Then compile the LaTeX document, fix compilation errors, and confirm that the output is readable, text-selectable, and within the agreed page limit.
