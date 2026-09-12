# Security Policy

PDFNoLimit is built on a single promise: **your documents never leave your browser.** A vulnerability that breaks that promise is the most serious kind of bug this project can have, and it will be treated that way.

## Reporting a vulnerability

**Please do not open a public issue for a security problem.**

Two ways to reach us privately:

1. **GitHub private vulnerability reporting** — use the **Report a vulnerability** button in the [Security tab](https://github.com/zedredwed/pdfnolimit/security). This is the preferred route: it is private, it threads, and it keeps everything in one place.
2. **Email** — <pdfnolimit@gmail.com>, the same address as the contact link on the site.

## What to include

The more of this you can give, the faster it gets fixed:

- What the vulnerability allows an attacker to do
- The exact steps to reproduce it
- The affected page or tool, with its URL
- Your browser and version, and your operating system
- Any proof-of-concept you have — **without a real confidential document**

## What we ask of you

- Give us reasonable time to fix the issue before disclosing it publicly.
- Do not access, modify, or destroy data that is not yours.
- Do not run attacks that degrade the service for other people — no denial of service, no traffic flooding, no spam.
- Stay within the law.

Act in good faith and we will not pursue you for your research.

## What you can expect from us

- **An acknowledgement within 72 hours** that your report arrived and was read.
- An initial assessment, and our view of the severity, shortly after.
- Progress updates while we work on it.
- Credit in the release notes when the fix ships, if you want it. Say so in your report, and tell us how you would like to be named.

## Scope

**In scope**

- `www.pdfnolimit.com` and all of its tool pages
- Anything that causes a user's file or its contents to leave the browser
- Cross-site scripting, content injection, or clickjacking on the site
- Flaws in how documents are processed that lead to data disclosure
- Weaknesses in password protection, unlocking, or redaction — in particular, **redaction that can be undone** or content that survives where it should not

**Out of scope**

- Vulnerabilities in third-party advertising served on the page, which we do not control — report those to the ad provider, though we still want to hear about it
- Reports produced only by an automated scanner, with no demonstrated impact
- Missing hardening headers with no exploitable consequence
- Social engineering, phishing, or physical attacks
- Denial of service through volume

## A note on the privacy claim

If you find a way to prove that a document **does** leave the browser under some condition — a specific file type, a particular tool, an edge case in a conversion path — that is the single most valuable report you could send. It goes to the top of the queue.
