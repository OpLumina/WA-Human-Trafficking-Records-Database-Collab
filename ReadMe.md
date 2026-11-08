# Human Trafficking Public Records Index

Welcome to the Human Trafficking Public Records Index project. This repository serves as a centralized metadata registry to track public records requests, state and local portals, and information disclosures from Law Enforcement (LE) agencies.

---

## How to Contribute

We welcome contributions! Here are the primary ways you can help build and maintain this project:

1. **Submit Public Records Requests**:
   * **Find an Agency**: Use `request-info.csv` to find an agency portal that needs a records request (check the `Already Requested` column).
   * **File the Request**: Use our standardized template (`WA-Request-Template.txt`) to submit the public records request via the agency's portal or contact email.
   * **Forward Responses**: When you receive updates or responsive records, **do not upload raw files or PII to GitHub**. Forward all agency communications and record files directly to **cm.stupak@gmail.com**.

2. **Update the Portal CSV Index**:
   * Edit `request-info.csv` to add new agency request portals, fix broken links, or update portal contact information. Ensure all entries follow our [Required CSV Schema](#required-csv-schema).

3. **Expand to New States**:
   * If adding public records portal data for a new state outside of Washington (e.g., Oregon), create a new directory named with its official two-letter state code and submit your changes via a Pull Request.

4. **Access Data or Share Findings**:
   * To request access to our central records database or share findings, contact project lead directly at **cm.stupak@gmail.com**.

---

## Important Guidelines and Project Scope

**WARNING**: Do **NOT** upload raw public record documents or Personally Identifiable Information (PII) to this GitHub repository.

To protect privacy, ensure safety, and comply with GitHub policies, adhere strictly to these rules:

### 1. No Personally Identifiable Information (PII)
* Do **NOT** post or commit real names, home addresses, phone numbers, email addresses, Social Security Numbers, or any sensitive personal identifiers of victims, witnesses, or law enforcement personnel.
* If a record or portal contains sensitive personal data, strip or omit those details before documenting the entry in our tracker.

### 2. No Uploading of Raw Public Record Files
* Do **NOT** upload PDF downloads, audio/video recordings, transcripts, or raw document files directly to this repository (no git commits, releases, or issue attachments for raw files).
* Raw records must be stored in our team's designated secure storage location, **NOT** in this repository. This repo is strictly for managing metadata, code, and portal tracking.

### 3. No Using Unapproved Request Templates for Records Requests
---

## Current Focus & Dataset

Our primary objective is to build, verify, and maintain a central CSV database of public records request portals and collect LE records via crowdsourced public records requests.

### Key Files
* `request-info.csv` — Central metadata index tracking agency portals.
* `WA-Request-Template.txt` — Standardized public records request template for Washington state agencies.

### Required CSV Schema

Each row in `request-info.csv` must include the following fields:

* **Agency Name** — Full official name of the LE agency (e.g., Seattle Police Department)
* **Agency State** — Two-letter state abbreviation (e.g., WA)
* **Agency County** — County where the agency operates (e.g., King)
* **Agency City** — Primary city where the agency is located (e.g., Seattle)
* **Agency Request Portal** — Direct web link or contact email to submit public records requests
* **Request Type** — Type of request to be made (e.g. Email, Phone, Form, Web Portal)
* **Priority** — How high the priority is to request that department's records (High, Medium, Low & Completed), Completed means the records have already been processed
* **Already Requested** — If the records request has already been submitted, please generate a PR or email cm.stupak@gmail.com if a request is made so others don't request the same thing
---

## Questions or Safety Issues

If you spot an accidental upload of sensitive data, notice broken portal links, or need clarification on cataloging an entry, please contact the project lead immediately at **cm.stupak@gmail.com** or open a non-sensitive GitHub Issue.
