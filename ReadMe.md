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

## Current Focus

Our current primary task is to build, verify, and maintain the central CSV index tracking public record portals across agencies.

### Primary File to Work On

* `public_records_portals.csv`

### Required CSV Schema

Each row in the CSV file must contain the following 5 fields:

* Agency Name — Full official name of the LE agency (e.g., Seattle Police Department)
* Agency State — Two-letter state abbreviation or full state name (e.g., WA)
* Agency County — County where the agency operates (e.g., King)
* Agency City — Primary city where the agency is located (e.g., Seattle)
* Agency Request Portal URL — Direct web link to submit FOIA / Public Disclosure requests

---

## CSV Format Example

```csv
Agency Name,Agency State,Agency County,Agency City,Agency Request Portal URL
Seattle Police Department,WA,King,Seattle,https://seattlewa.govqa.us/WEBAPP/_rs/
Texas Department of Public Safety,TX,N/A,Austin,https://www.dps.texas.gov/section/media-and-communications/public-information-act

```

---

## How to Contribute

1. Clone or Fork the repository.
2. Edit `public_records_portals.csv` using a text editor or spreadsheet tool (exporting back to raw CSV format).
3. Double-Check Before Committing: Ensure no extra files, raw records, or PII were inadvertently included.
4. Submit a Pull Request (PR) with a clear commit message indicating which agency entries were added or updated.

---

## Questions or Safety Issues

If you identify an accidental upload of sensitive data, notice broken portal links, or need clarification on cataloging an entry, please contact the project lead immediately or open a non-sensitive GitHub Issue.
