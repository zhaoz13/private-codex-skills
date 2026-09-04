---
name: ats-resume-tailor
description: Create an ATS-tailored software-engineering resume from a pasted job description and archive it with application notes. Use whenever Bill pastes a job posting or asks to tailor a resume for a specific role.
---

# ATS Resume Tailor

Create a polished, ATS-readable PDF resume for each pasted software-engineering job description. When Bill pastes a job description without an explicit request, treat it as a request to tailor and archive a resume.

## Candidate facts and accuracy

Use only supported claims. Bill is a Full Stack Engineer at 3rdwave, a startup, from April 2022 to present. His verified work includes Java, GWT, JavaScript, HTML/CSS, REST APIs, SQL-backed workflows, AWS S3, DynamoDB, RDS, SFTP, XML/CSV integration, data mapping and validation, production troubleshooting, Maven, Git, CI/CD, code review, technical documentation, and document-AI workflow integration. He has authored 1,200+ commits. His contact email is `billzhao0625@gmail.com`.

Do not claim direct professional experience with a technology or domain merely because the posting asks for it. Common unsupported examples include React, TypeScript, Angular, Spring Boot, Kotlin, Ruby/Rails, C#/.NET, Docker, Kubernetes, Terraform, Kafka, PostgreSQL specialization, fintech/banking, healthcare/FHIR, production LLM/agent systems, or daily professional Copilot/Claude usage. Codex use and document-AI integration can be described narrowly as AI exposure when relevant.

## Default evidence sources

Treat both of these files in the configured `work` folder as the authoritative evidence sources. Read them in full when initializing or refreshing the evidence memory; otherwise, use the memory-first verification flow below:

- `blinco_3ww_contribution_portfolio.xlsx` - the contribution portfolio of Bill's commits. Use it as the primary evidence source when selecting and wording accomplishments from his current role.
- `ZhiChun_Zhao_Full_Stack_Engineer_Resume (1).pdf` - the base resume. Use it for contact details, employment chronology, education, projects, and other established resume facts.

Match the job description to specific, sufficiently contextualized portfolio entries before adding a current-role accomplishment. The portfolio supports what Bill delivered; the base resume supplies the broader career record. Do not infer a technology, impact, ownership level, or outcome from a commit title alone, and surface conflicts or incomplete evidence instead of inventing a claim. If either source file is unavailable, ask Bill to provide its location before representing new or expanded accomplishments externally.

## Memory and efficient context use

Maintain a private, compact evidence index at `/Users/zhaobill/Desktop/work/ATS_MEMORY.md`, and mirror it to the configured Google Drive `work/` folder. It is working memory, never the sole source of truth: it must identify each achievement card's supporting workbook sheet/row or base-resume section, and it must be refreshed when either default evidence source changes.

On the first tailoring task, or when the memory is missing or stale, build or refresh it after reviewing the default evidence sources. Keep only durable, verified information: canonical contact and chronology facts; a concise index of current-role accomplishment cards with technologies, scope, outcome, and source reference; reusable preferences; and pointers to past application folders. Do not duplicate full job descriptions, complete resumes, or the entire workbook.

For later tailoring tasks, read the memory first, select the relevant accomplishment cards from the job description, then open only the corresponding source rows or resume sections to verify the claims used. Re-read the full source only when the cache is stale, relevant evidence is absent or ambiguous, the job materially changes the needed domain, or a claim conflicts with a source. Never use memory to create, extend, or “remember” an unsupported achievement. Do not upload this personal memory file to the GitHub skill repository.

## Tailoring

Extract the role's core responsibilities, required technologies, and domain. Place matching verified keywords naturally in the summary, current-role experience bullets, and technical skills. Prioritize the closest demonstrated equivalents for gaps without presenting them as direct experience. Include a concise application README that records ATS coverage and accuracy boundaries.

Optimize for both ATS parsing and a human HR review. The first screen should make the target role, employer and dates, strongest relevant experience, measurable outcomes, and verified technical fit easy to find; include location or work eligibility only when it is verified and relevant. Integrate keywords into natural, evidence-based language; never use keyword blocks, inflated claims, cramped typography, or dense unreadable bullets merely to improve ATS coverage.

In the header, use the exact target job title for that application, followed by `Toronto, ON`, phone number, and email on one readable line. Keep technology keywords in the summary and skills sections rather than expanding the header until it wraps.

Maintain a modern, single-column ATS-safe layout: use a clean Helvetica/Arial-style sans-serif typeface, a restrained navy accent, and text-based content (not a flattened image). Use clear section hierarchy with whitespace and a subtle divider or color treatment, never heavy full-box section borders. A one-page resume should use roughly 85-95% of the page, with intentional bottom whitespace; first improve readable typography and include more verified, role-relevant evidence rather than padding or duplicating content. The candidate's current full-time role is the core experience: normally devote 6-8 role-relevant bullets to concrete deliveries (such as UI/API/service work, validation or workflow improvements, integrations, data ingestion, document-AI workflow handling, and production support) when supported by the source material. Use two pages only when additional verified, role-relevant evidence materially improves a recruiter's decision clarity. Use the PDF skill's required create/edit marker, render the final PDF for visual QA, and verify a plain-text extraction preserves contact details, headings, dates, role/employer fields, and readable bullet order before delivery.

When a LinkedIn profile is supplied or available within the approved scope, compare the resume's employer, title, dates, and core technical claims against it before external submission. Surface material inconsistencies for correction; do not modify LinkedIn automatically or force a tailored resume's keyword variations into the profile.

## Filing, naming, and backup

Save the final PDF under the repository's `output/pdf/`. Archive the PDF, README, and `JOB_DESCRIPTION.md` in a distinct folder under `/Users/zhaobill/Desktop/work/`; this local `work/` directory is the primary copy. Name each application folder `YYYY-MM-DD - Employer - Role`. The PDF filename must never include the employer name or the word `Tailored`; use the neutral stable filename `ZhiChun_Zhao_Resume.pdf` unless Bill asks for a different generic name. Never display `Tailored` in the PDF title or file name.

`JOB_DESCRIPTION.md` must preserve the target job's title, employer, location, original posting URL, capture date, and complete job-description text used to tailor the resume. Do not invent descriptions for existing archive folders if their original posting text or URL is unavailable.

For every application, mirror the same application folder and its approved contents to the configured Google Drive `work/` folder as a backup. Preserve the local work folder after backup and never put resumes, application answers, or job materials in the GitHub skill repository. Once Bill has approved a specific Drive `work/` root, treat that as standing approval for this same application-archive scope; do not request confirmation again for each routine backup. Request approval only for a new Drive destination or a materially broader file scope.

## Skill maintenance and distribution

Treat the local skill and Bill's private GitHub `ats-resume-tailor/SKILL.md` as synchronized copies. Whenever a reusable rule, resource, or workflow in this skill changes, update the corresponding GitHub skill files in the same task without requesting a separate confirmation. Keep only reusable skill instructions and non-personal templates in that repository; never sync application archives or other personal job materials there.

## Model routing

Use a high-quality available model for job-description interpretation, resume tailoring, factual-boundary decisions, ATS/HR readability review, and final PDF QA. After the files, destinations, and upload scope are fixed, a lower-cost model may perform mechanical local filing, Google Drive mirroring, GitHub skill synchronization, and file-count or manifest verification. These lower-cost tasks must not alter resume or job-description content, decide what to upload, or expand scope; report any mismatch or ambiguity for higher-quality review or Bill's direction.

Before writing to Desktop, request the required permission. In the final response, briefly identify the strongest ATS matches and important gaps that were deliberately not claimed. Cite the final PDF once using the required PDF artifact citation.
