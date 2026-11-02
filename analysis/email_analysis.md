# Email Sample Analysis

**Project:** FUTURE_CS_02 — Phishing Email Detection & Awareness System  
**Dataset:** Five fictional training examples created for this project.

## Review approach
Each sample was reviewed using the visible sender string, subject, message wording, requested action, urgency and any stated link or attachment indicators. The classifications are educational judgments based on the simulated content.

## Results

### E01 — Routine account notification
**Classification:** Safe-style control  
The message gives a routine statement notification and advises users not to share passwords or verification codes. It contains no obvious sensitive-data request, embedded link, attachment or pressure tactic. It is included as a benign-looking comparison only; it is not a verified legitimate email.

**Recommended action:** In real use, independently verify the sender and context.

### E02 — Unexpected invoice notification
**Classification:** Suspicious  
The sender is unfamiliar, the invoice is unexpected, and an attachment is mentioned. The example does not establish an existing vendor relationship. These points justify caution, but the text alone does not prove phishing.

**Recommended action:** Do not open an unexpected attachment. Check purchase records and contact the vendor through independently verified details.

### E03 — Bank account verification request
**Classification:** Phishing  
The message asks for account details and a one-time verification code, and applies immediate-action pressure. These are strong phishing indicators.

**Recommended action:** Do not reply or disclose codes. Contact the bank through its official app or another independently verified channel.

### E04 — Parcel delivery payment request
**Classification:** Phishing  
The message claims a parcel is held until an unexpected fee is paid and uses a same-day deadline and threat of return. This pattern is consistent with parcel-delivery phishing lures.

**Recommended action:** Do not use the payment route in the message. Check tracking directly through the courier's official app or website.

### E05 — Urgent password reset notification
**Classification:** Phishing  
The message requests the recipient's current password and verification code and threatens loss of account access. An unsolicited request for these credentials is a strong phishing indicator.

**Recommended action:** Do not enter credentials through the message. Access the service through a known bookmark or official app and report the email.

## Summary
- Safe-style control: 1 (E01)
- Suspicious: 1 (E02)
- Phishing: 3 (E03, E04, E05)

These counts describe only this five-example training set. They are not prevalence estimates or measured detection accuracy.

## Evidence and limitations
All examples are fictional. No live emails, raw headers, authentication records, DNS records, URL destinations, attachments or malware were examined. SPF, DKIM, DMARC, sender ownership and URL reputation were not tested. The report therefore demonstrates content-based awareness review, not a deployed or validated automated detection system.
