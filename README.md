# FUTURE_CS_02 – Phishing Email Detection & Awareness System

**Future Interns | Cyber Security Internship | Task 2**

## 1. Project Overview

This project demonstrates how phishing emails can be identified through suspicious sender details, deceptive subject lines, urgent language and requests for sensitive information.

It focuses on analysing email characteristics, classifying potential threats and promoting cybersecurity awareness through practical examples and documented analysis.

## 2. Objectives

- Understand common phishing techniques.
- Identify suspicious email characteristics.
- Classify email samples as Safe, Suspicious or Phishing.
- Analyse email content and potential security risks.
- Promote safe email practices.
- Develop cybersecurity awareness.

## 3. Project Structure

The repository contains the following files and folders:

- `analysis/` – Email analysis and classification documentation.
- `dataset/` – Simulated email samples and supplementary public dataset analysis.
- `evidence/screenshots/` – Project evidence screenshots.
- `references/` – Research and awareness references.
- `README.md` – Project documentation.
- PDF report – Final project report in the repository root.

### Analysis Files

- `classification_criteria.md`
- `email_analysis.md`
- `header_analysis_method.md`
- `real_world_case_ftc.md`

### Dataset Files

- `email_samples.csv`
- `public_dataset_analysis.md`

## 4. Dataset – Simulated Email Samples

The project includes five fictional email examples created for educational analysis.

- **E01 – Routine account notification:** Safe-style control.
- **E02 – Unexpected invoice notification:** Suspicious.
- **E03 – Bank account verification request:** Phishing.
- **E04 – Parcel delivery payment request:** Phishing.
- **E05 – Urgent password reset notification:** Phishing.

These examples are simulated training scenarios and are not presented as actual received emails.

## 5. Supplementary Public Dataset Analysis

In addition to the five fictional training examples, this project includes a supplementary analysis of selected examples from a publicly available phishing validation dataset.

**Dataset source:** Zenodo – Phishing Validation Emails Dataset

- Published: 29 August 2024.
- Dataset size: 2,000 email examples.
- Format: CSV.
- Original labels: Safe Email and Phishing Email.
- The dataset contains a mixture of real-world and artificially generated examples.

### Selected Examples

- **PUB-01 – Gift card prize message:** Phishing.
- **PUB-02 – Bank secure message:** Phishing.
- **PUB-03 – Purchase confirmation:** Safe-style control.

PUB-01, PUB-02 and PUB-03 are project-assigned identifiers, not original dataset identifiers.

**Detailed analysis:** [View Public Dataset Analysis](dataset/public_dataset_analysis.md)

**Dataset reference:** https://doi.org/10.5281/zenodo.13474746

The public dataset uses binary labels. The Suspicious category in this project is an additional analyst classification for ambiguous examples.

## 6. Methodology

The email samples were reviewed using the following criteria:

- Sender information and sender-domain characteristics where available.
- Subject lines and message context.
- Suspicious or urgent language.
- Requests for personal or financial information.
- Unexpected links or payment requests.
- Original dataset labels where applicable.

The analysis combines simulated email examples with supplementary public-dataset text analysis.

## 7. Important Limitations

- The original samples E01–E05 are fictional educational examples.
- The supplementary dataset contains a mixture of real-world and artificially generated examples.
- Individual public-dataset samples have not been independently authenticated as real-world emails.
- The selected public-dataset records do not provide raw email headers or actual URL destinations.
- Sender identity, domain authenticity and spoofing cannot be independently verified from those selected records.
- SPF, DKIM and DMARC results were not independently tested.
- No attachments or malware behaviour were analysed.
- This project is an educational assessment and not a live phishing detection engine.

## 8. Prevention Guidelines

- Never share passwords or OTPs through email.
- Verify unexpected requests independently.
- Check sender addresses carefully.
- Avoid interacting with suspicious links and attachments.
- Use official websites and applications.
- Enable multi-factor authentication.
- Report suspected phishing emails.
- Stay informed about emerging email-based threats.

## 9. References

1. Miltchev, Rangelov and Genchev (2024). *Phishing Validation Emails Dataset*. Zenodo. https://doi.org/10.5281/zenodo.13474746
2. Federal Trade Commission (FTC) – Consumer Advice: https://consumer.ftc.gov/
3. Anti-Phishing Working Group (APWG): https://apwg.org/
4. OWASP Foundation: https://owasp.org/

Additional project references and supporting documentation are available in the `references/` and `analysis/` directories.

## 10. Author

**Aliya Amjad**

Cyber Security Intern  
Future Interns – Task 2

**Project ID:** FUTURE_CS_02

---

*This project was developed for educational purposes as part of the Future Interns Cyber Security Internship.*
