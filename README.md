# Software-Testing-Capstone-Clean
# Honey & Crumb Bakery — Software Testing Capstone

A full QA testing project built from the ground up as part of an 8-week software testing bootcamp. This repo contains the clean (post-fix) version of the test site along with all testing documentation.

---

## Project Overview

This capstone required testing an ecommerce site against three defined requirements, documenting findings in a test plan and test cases, and tracking defects through their full lifecycle in Jira.

Rather than testing an existing live site, I built my own ecommerce site from scratch using HTML, CSS, and JavaScript. This gave me a controlled environment where I could test thoroughly without depending on a third-party site that may already have dedicated QA coverage.

To introduce bugs without knowing where they were, I provided the three requirements to an AI tool and had it modify the code to create defects that aligned with those requirements. This kept the testing unbiased — I had no prior knowledge of where the bugs were or how many there were.

---

## About the Site

Honey & Crumb Bakery is a fictional Italian bakery ecommerce site. It includes a homepage, menu, order form, about page, and contact page. The site was purpose-built as a testing environment and is not a real business.

- **Clean Site (this repo):** The verified, post-fix version of the site
- **Buggy Site:** The defect version used during active testing → [View Buggy Site](https://kbyeee-getaways.github.io/Software-Testing-Capstone-Defects/index.html)

---

## Testing Scope

Three requirements were assigned for this capstone:

1. **Navigation & Link Functionality** — All internal and external links must be functional and direct users to the correct pages without errors.
2. **Form Validation & Submission** — Forms must validate required fields and handle submissions correctly.
3. **Cross-Browser & Mobile Responsiveness** — The site must render and function correctly across browsers and screen sizes.

---

## Methodology

Testing was conducted manually following a structured QA process:

- **Test Plan** — Defined the scope, objectives, approach, test environment, entry and exit criteria, deliverables, and risks before any testing began.
- **Test Cases** — Written prior to testing. Each requirement has its own tab documenting every scenario that should pass, with expected and actual results recorded.
- **Defect Tracking** — Bugs were logged in Jira with full reproduction steps, expected vs. actual results, environment details, and screenshot/video evidence.
- **Bug Documentation** — Each defect received its own detailed tab in the test case sheet to support Jira ticket creation and bug lifecycle tracking.
- **Visual Evidence** — The Snipping Tool was used to record screen captures of each bug and its verified fix.

The capstone required a minimum of one bug per requirement. Testing uncovered three bugs per requirement, nine total, all of which were documented and resolved.

---

## The AI Angle

Using AI to introduce the bugs was an intentional decision rooted in testing best practices. A tester should not know where defects are before testing begins. By providing only the requirements and letting AI modify the code, the bugs remained a genuine unknown — making the testing process more realistic and the findings more credible.

---

## Deliverables

| Document | Link |
|---|---|
| Test Plan | [View Test Plan](https://docs.google.com/document/d/1WrDE1idM1QkvefAK7Jqnd3m2hO9nyYTS7y5-YBqbIGE/edit?usp=sharing) |
| Test Cases | [View Test Cases](https://docs.google.com/spreadsheets/d/1RqCAwIx8auJTo6aOR72KQpZpyFlJHM23kgWbukvUpNQ/edit?usp=sharing) |
| Buggy Site | [View Buggy Site](https://brandi-jeff.github.io//Software-Testing-Capstone-Defects/index.html) |
| Clean Site (Live) | [View Clean Site](https://brandi-jeff.github.io//Software-Testing-Capstone-Clean/index.html) |

---

## For Fellow Testers

The buggy site is publicly available and intentionally left in its defective state for anyone who wants to practice finding and documenting bugs. Feel free to use it as a sandbox. If you do, the three requirements above are your starting point.

---

## Tools Used

- **Jira** — Defect tracking and bug lifecycle management
- **ReqTest** — Test case management reference
- **Google Sheets** — Test case documentation
- **Google Docs** — Test plan
- **Snipping Tool** — Visual bug and fix recording
- **GitHub Pages** — Site deployment
- **HTML / CSS / JavaScript** — Site development

---

*Capstone completed as part of the Tek's software testing cohort, April 2026.*

