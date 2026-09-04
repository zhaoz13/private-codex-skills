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

Keep a traditional single-column layout with parseable text and Times-style typography. Preserve the most relevant demonstrated achievements from the base resume; do not make the resume shorter merely to repeat generic keywords. Keep it to one page unless the user requests otherwise.

Create `ZhiChun_Zhao_Tailored_Resume.pdf` (or the user-requested generic filename) and `APPLICATION_NOTES.md` in `<candidate-folder>/output/`. The notes must record ATS coverage and accuracy boundaries.

## Verification and applications

Use the PDF workflow's create/edit marker and render the final PDF for visual QA before delivery. If the user asks to apply, complete preparation and upload only when authorized, stop for missing factual answers, login/verification challenges, and explicit confirmation immediately before the final submission.
