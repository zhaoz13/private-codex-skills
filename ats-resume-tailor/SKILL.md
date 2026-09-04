---
name: ats-resume-tailor
description: Create an ATS-tailored, one-page software-engineering resume from a job URL or pasted posting, using a candidate profile in a user-specified folder. Use when the user asks to tailor a resume or apply to a specific software-engineering role.
---

# ATS Resume Tailor

Create a polished, ATS-readable, one-page resume for the target software-engineering position.

## Candidate source folder

Before drafting, ask for a candidate folder if one was not supplied. Read `<candidate-folder>/candidate-profile.md` for verified facts and `<candidate-folder>/base-resume.pdf` or another provided base resume when available. Use only supported claims from those sources. Do not infer direct experience with a technology, domain, certification, or credential solely because it appears in the posting.

If `candidate-profile.md` does not exist, create a draft from [the profile template](references/profile-template.md) and ask the user to verify missing or uncertain facts before representing them externally.

## Tailoring

Extract the role's core responsibilities, required technologies, and domain. Put verified matching keywords naturally in the summary, experience bullets, and skills. Present adjacent experience accurately when a requirement is missing; never present it as direct experience.

Optimize for both ATS parsing and a human HR review. In a quick scan, make the target role, strongest relevant experience, measurable outcomes, and verified technical fit easy to find. Integrate keywords into natural, evidence-based language; never use keyword blocks, inflated claims, cramped typography, or dense unreadable bullets merely to improve ATS coverage.

Keep a traditional single-column layout with parseable text and Times-style typography. Preserve the most relevant demonstrated achievements from the base resume; do not make the resume shorter merely to repeat generic keywords. Keep it to one page unless the user requests otherwise.

Create `ZhiChun_Zhao_Tailored_Resume.pdf` (or the user-requested generic filename), `APPLICATION_NOTES.md`, and `JOB_DESCRIPTION.md` in `<candidate-folder>/work/<application-folder>/`. `JOB_DESCRIPTION.md` must preserve the posting title, employer, location, source URL, capture date, and complete description text used for tailoring. The notes must record ATS coverage and accuracy boundaries.

## Application archive

Treat the local `<candidate-folder>/work/` as the primary work directory and the configured Google Drive `work/` folder as its backup mirror. Keep the skill itself in its private Git repository; do not store resumes, application answers, job descriptions, or other personal application data in that repository.

When the user supplies or has previously approved the Drive `work/` root, create the same dated subfolder locally and in Drive for each application. The folder name should be `YYYY-MM-DD - Company - Role`; upload the tailored resume, application notes, job description, and any user-approved supporting materials. Approval of that Drive root is standing approval for this same application-archive scope, so do not request confirmation for each routine backup. Request approval only for a new destination or materially broader file scope. Never remove or replace the local work copy after backup. Do not reconstruct a historical job description unless its source URL or original content is available.

## Skill maintenance and distribution

Treat the local skill and the user's private GitHub `ats-resume-tailor/SKILL.md` as synchronized copies. Whenever a reusable rule, resource, or workflow changes, update the corresponding GitHub skill files in the same task without requesting a separate confirmation. Keep only reusable skill instructions and non-personal templates in that repository; never sync application archives or other personal job materials there.

## Verification and applications

Use the PDF workflow's create/edit marker and render the final PDF for visual QA before delivery. If the user asks to apply, complete preparation and upload only when authorized, stop for missing factual answers, login/verification challenges, and explicit confirmation immediately before the final submission.
