<p align="center"><strong>CareerLens</strong><br>by NAVIFLARE</p>

# Get past the first filter.

**Help your CV get through ATS and AI recruitment screening, fill in your resume and prepare a relevant application.**

CareerLens is a service concept for job seekers who want their actual qualifications to be understood by recruitment software and the person hiring. It brings together guided CV completion, vacancy analysis, relevant experience selection and reviewed applications.

**Project stage: documentation and concept illustrations. The application is not implemented in this repository.** There is no released service, executable prototype, installation command or working integration here. Features below describe the intended product.

[Русская версия](README.ru.md) · [Project website](https://naviflare.com/projects/careerlens/) · [Capabilities](#planned-capabilities) · [Workflow](#from-vacancy-to-reviewed-application) · [Roadmap](docs/ROADMAP.md)

![Concept: experience reorganised for automated screening and human review](docs/images/ats-screening.webp)

*Concept illustration. This is neither an application screenshot nor an ATS-certified resume template or evidence of a hiring result.*

## Why CareerLens

A candidate may have suitable experience and still struggle to present it clearly. A general CV can bury the relevant work. A blank form can make it difficult to describe achievements. Repeated applications can mean entering the same information again and again.

CareerLens is intended to help with that practical work:

- Understand what the vacancy asks for.
- Complete a CV through guided questions and reviewed suggestions.
- Make genuine, relevant qualifications easier for ATS and AI screening to identify.
- Adapt the presentation to a role without changing the underlying facts.
- Prepare a cover letter and supported application fields.
- Check the exact documents and answers before submission.
- Track what was prepared, sent and actually confirmed.

The goal is to help suitable candidates get through the first screening and reach human consideration. It is not a promise that every application will pass or produce an interview.

## Planned capabilities

Every capability in this table is **planned**, not available software.

| Area | Intended candidate benefit | Planned behaviour |
| --- | --- | --- |
| Guided CV completion | Get help filling in a resume | Start with an existing CV or reviewed profile; ask for missing roles, dates, education, skills and achievements. |
| Wording assistance | Describe real experience clearly | Suggest phrasing for the candidate to check; keep claims grounded in confirmed facts. |
| ATS preparation | Make the document easier to read | Review section structure, readable text and the information represented in the exported document. |
| AI screening preparation | Show why the experience fits | Connect vacancy requirements to supporting experience; use relevant terminology where it is true. |
| Vacancy analysis | Understand requirements before applying | Separate essential conditions, useful skills, evidence and unanswered questions. |
| Professional Lenses | Choose the appropriate experience | Create reviewed selections for different professional directions from one private career history. |
| CV Studio | Prepare a relevant document | Assemble and review a CV from the selected facts while retaining original titles, dates and qualifications. |
| Cover letters | Prepare a grounded introduction | Draft an application-specific message based on the same reviewed information. |
| Assisted application fields | Reduce repeated typing | Reuse confirmed details in supported forms; keep personal declarations and the final decision with the candidate. |
| Application review | Know exactly what will be shared | Show the employer, vacancy, recipient, message, answers and precise CV version before approval. |
| Campaigns and tracking | Organise different searches | Keep criteria, shortlists, CV selections, application history and confirmed outcomes by direction or country. |
| Market research | Explore opportunities with context | Show observed listings with sources, collection dates, coverage limitations and unknowns. |
| Private career record | Keep facts consistent | Store the full reviewed history separately from the shorter information shared in a particular application. |

## From vacancy to reviewed application

1. **Understand the vacancy.** Identify the role, essential requirements and points that need clarification.
2. **Complete the profile.** Import or enter existing information, answer guided questions and confirm dates, titles and achievements.
3. **Choose the professional focus.** Select the genuine experience relevant to the direction.
4. **Review the CV.** Check structure, wording, readable content and the evidence behind each claim.
5. **Prepare the application.** Draft the cover letter and supported form answers, then review the exact result.
6. **Submit deliberately and track the outcome.** Keep preparation, approval, sending and delivery confirmation separate.

![Interface concept: guided experience, skills and education fields feed a CV preview](docs/images/guided-cv.webp)

*Proposed interface concept, not a screenshot of working software. Placeholder labels explain the information flow; no real candidate data is shown.*

## What “ATS and AI screening support” means

ATS stands for applicant tracking system. Reading a resume into candidate fields and comparing a candidate with job requirements are different operations.

CareerLens is intended to help candidates prepare for both by reviewing document structure, filling missing information and making the connection between requirements and real experience explicit. Matching terms should describe skills the candidate actually has; missing qualifications should remain visible as gaps.

As examples of these distinct operations, [Greenhouse documents resume parsing problems](https://support.greenhouse.io/hc/en-us/articles/200989175-Unsuccessful-resume-parse), and [Workable describes AI comparisons against job requirements](https://help.workable.com/hc/en-us/articles/23685011706775-Using-the-AI-Screening-Assistant). These links explain hiring-system behaviour. They are not CareerLens integrations or endorsements.

There is no universal “ATS pass” certificate. Employer criteria and systems differ, and the eventual software would not know every hidden rule. CareerLens will not promise an interview, invent an outcome score or claim that a formatting check predicts a hiring decision.

## One true history, relevant CVs

The private career record is the foundation. A **Professional Lens** is a reviewed selection of that record for a particular direction.

For example, a fictional candidate might have experience in site operations, team coordination and digital delivery. A construction-focused CV could emphasise the first two. A digital-project CV could emphasise the last two. The person, actual roles and dates remain the same.

| View | Intended scope |
| --- | --- |
| Focused | Only reviewed experience marked essential for that direction. |
| Standard | Essential experience plus approved optional context. |
| Extended | A broader reviewed selection within that direction; not the entire private career archive. |

An item marked **never to show** must stay absent from every representation, including summaries, skills, projects and letters. A longer CV must not bring it back. A selective document should state its scope, for example “Selected relevant experience”.

The candidate's confirmation establishes that they reviewed a fact. It does not mean CareerLens performed an independent background check.

## Human control over applications

![Concept: a candidate controls the gate before a prepared application is delivered](docs/images/reviewed-application.webp)

*Concept illustration of review before delivery, not an observed application or implemented sending feature.*

The intended flow is **Prepared → Reviewed → Approved → Submitted → Confirmed**. If delivery cannot be established, the outcome remains unknown until checked.

Assisted filling should reduce repetitive work while leaving the final submission with the candidate. Any future direct sending would require an explicitly enabled supported channel and approval for that exact application. Changing the recipient, message or CV would invalidate the earlier approval.

Generic automatic submission to every job site is not part of the documented initial scope. CAPTCHA, authentication challenges and personal or legal declarations require the person's involvement. Preparing or opening a form must never be reported as a sent application.

## Privacy and truthful claims

The intended architecture starts with private local storage. Hosted operation, external AI processing and optional integrations would require clear disclosure and explicit access boundaries. “Local first” is a design direction, not a claim that an unimplemented service already keeps all data on the device.

- Different candidates' profiles, CVs, campaigns and approvals must stay separate.
- Public vacancy information may be shared; private candidate material may not.
- Missing language levels, work authorisation or qualifications stay unknown until reviewed.
- Suggestions may improve wording, but must not invent achievements, change dates or fabricate job titles.
- Hidden keywords, fake credentials and misleading application answers are outside the product's purpose.
- Progress reports should describe observed outcomes with sample sizes, not invented success rates.

This repository contains no personal CVs, credentials, candidate database or uploaded application documents.

## Repository contents

```text
README.md                 English product overview
README.ru.md              Russian product overview
docs/FEATURES.md          Scope and acceptance expectations
docs/ROADMAP.md           Planned implementation stages
docs/MEDIA.md             Illustration provenance and limitations
docs/images/              Concept illustrations used in the documentation
```

There is nothing to install or run at this stage. The next development task should begin with the documented scope and its acceptance conditions, rather than treating the illustrations as an existing interface.

## Development direction

The project specification considers [career-ops](https://github.com/career-ops-hq/career-ops) as an upstream foundation. This repository is a separate NAVIFLARE documentation project, not an official career-ops product or an implemented fork. No upstream application source is included here. Any future reuse must retain the applicable notices and be reviewed at a pinned revision.

The application license and tested setup instructions will be specified when implementation is introduced. No application release or open-source license for future code is implied by this documentation publication. Illustration provenance is recorded in [docs/MEDIA.md](docs/MEDIA.md).

## Feedback

Useful feedback includes unclear CV fields, difficulties describing genuine experience, examples of confusing application forms and questions about the intended workflow. Please use fictional or redacted examples; do not post a real CV or private employment information in public issues.

Product questions: [support@naviflare.com](mailto:support@naviflare.com). More about the project: [NAVIFLARE CareerLens](https://naviflare.com/projects/careerlens/).
