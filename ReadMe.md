# Human Trafficking Public Records Index

Welcome to the Human Trafficking Public Records Index project. This repository serves as a centralized metadata registry to track public records requests, state and local portals, and information disclosures from Law Enforcement (LE) agencies.

---

## Important Guidelines and Project Scope

WARNING: Do NOT upload raw public record documents or Personally Identifiable Information (PII) to this GitHub repository.

To protect privacy, ensure safety, and comply with GitHub usage policies, please adhere strictly to the following rules:

### 1. No Personally Identifiable Information (PII)

* Do NOT post or commit real names, home addresses, phone numbers, email addresses, Social Security Numbers, or any sensitive personal identifiers of victims, witnesses, or law enforcement personnel.
* If a record or portal contains sensitive personal data, strip or omit those details before documenting the entry in our tracker.

### 2. No Uploading of Raw Public Record Files

* Do NOT upload PDF downloads, audio/video recordings, transcripts, or raw document files directly to this repository (no git commits, releases, or issue attachments for raw files).
* Raw records should be stored in our team's designated secure storage location (e.g., private cloud storage), NOT in this public/collaborative GitHub repo. This repo is strictly for building the code and dataset for central storage and analysis.

---

## Current Focus & Dataset

Our current primary task is to build, verify, and maintain the central CSV database of public records request portals, and collecting LE records via crowdsourced records requests.

### Primary File to Work On
* `request-info.csv` — Central metadata index tracking agency portals.
* `WA-Request-Template.txt` — Standardized public records request template for Washington state agencies.

### Required CSV Schema

Each row in the CSV file must contain the following fields:

* Agency Name — Full official name of the LE agency (e.g., Seattle Police Department)
* Agency State — Two-letter state abbreviation or full state name (e.g., WA)
* Agency County — County where the agency operates (e.g., King)
* Agency City — Primary city where the agency is located (e.g., Seattle)
* Agency Request Portal — Direct web link or contact email to submit FOIA / Public Disclosure requests

---

## How to Contribute

You can contribute to this project by submitting public records requests to law enforcement agencies:

1. **Find an Agency**: Use the CSV file (`request-info.csv`) to locate an agency portal that hasn't already been requested (see `Already Requested` Row in `request-info.csv`).
2. **Submit a Request**: Use the provided request template (`WA-Request-Template.txt`) to file your public records request through the agency's portal or email.
3. **Forward Communications & Responses**: Once you receive correspondence, tracking updates, or response files from the agency, **do not upload raw files or PII to GitHub**. Instead, forward all communications and responses directly via email to **cm.stupak@gmail.com**.
4. **Database Access & Sharing Requests**: If you need access to the central database, or wish to request and share records/findings, please email **cm.stupak@gmail.com** directly.
5. **Adding New States**: If you're working on public records portals for another state outside of Washington (like Oregon), add a folder named with its official two-letter state code and submit via Pull Request.

---

## Questions or Safety Issues

If you identify an accidental upload of sensitive data, notice broken portal links, or need clarification on cataloging an entry, please contact the project lead immediately via **cm.stupak@gmail.com** or open a non-sensitive GitHub Issue.
