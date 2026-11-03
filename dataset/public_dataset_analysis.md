# Public Dataset Analysis – Phishing Email Detection

## 1. Purpose

This supplementary analysis reviews selected email-text examples from a publicly available phishing validation dataset. It extends the project's existing fictional training examples without replacing or modifying them.

## 2. Dataset Source

- **Title:** Phishing validation emails dataset
- **Creators:** Miltchev, Rangelov and Genchev
- **Published:** 29 August 2024
- **Platform:** Zenodo
- **DOI:** https://doi.org/10.5281/zenodo.13474746
- **Dataset size:** 2,000 email examples
- **Format:** CSV
- **Available labels:** Safe Email and Phishing Email

The dataset contains a mixture of real-world and artificially generated examples. The original source labels are retained for the selected examples. The individual examples are not independently authenticated as real-world emails.

## 3. Selected Examples

The identifiers PUB-01, PUB-02 and PUB-03 are project-assigned identifiers, not original dataset IDs.

### PUB-01 – Gift Card Prize Message

- **Original dataset label:** Phishing Email
- **Project classification:** Phishing
- **Observed indicators:** An unexpected prize claim and a request to click a link.
- **Risk explanation:** Prize-related messages can use excitement and curiosity to encourage recipients to interact without checking the message.
- **Evidence limitation:** The dataset entry does not provide a sender address or actual link destination. A malicious destination cannot therefore be verified.

### PUB-02 – Bank Secure Message

- **Original dataset label:** Phishing Email
- **Project classification:** Phishing
- **Observed indicators:** A bank-related message claiming that a secure message is waiting, followed by a request to click a link.
- **Risk explanation:** Bank-related wording can create concern or urgency and encourage recipients to interact with an unverified message.
- **Evidence limitation:** No sender address, domain, raw email header or actual link destination is supplied.

### PUB-03 – Purchase Confirmation

- **Original dataset label:** Safe Email
- **Project classification:** Safe-style control
- **Observed indicators:** A routine purchase confirmation and a straightforward transactional message.
- **Risk explanation:** This example provides a comparison with the phishing-labelled messages.
- **Evidence limitation:** A Safe Email label in a dataset does not independently prove that a real sender or message is trustworthy.

## 4. Classification Summary

| Project ID | Original label | Project classification |
|---|---|---|
| PUB-01 | Phishing Email | Phishing |
| PUB-02 | Phishing Email | Phishing |
| PUB-03 | Safe Email | Safe-style control |

The source dataset uses binary labels. The project's Suspicious category is an additional analyst classification for ambiguous cases and is not an original label in this dataset.

## 5. Analysis Method

The selected examples were reviewed using:
- Message wording and context
- Unexpected prize or financial claims
- Requests to click links
- Attempts to create urgency or curiosity
- The original dataset classification

The analysis is limited to the email text and labels supplied by the dataset.

## 6. Limitations

The selected dataset entries do not provide the information needed to verify:
- Sender identity or spoofing
- Sender-domain authenticity
- Actual URL destinations
- Raw email headers
- SPF, DKIM or DMARC authentication results
- Attachments or malware behaviour

No live links were opened, and no sender or infrastructure verification was performed.

The original project CSV remains a separate collection of fictional educational examples. These public-dataset examples are supplementary and are not presented as part of that original fictional dataset.

## 7. Conclusion

The selected examples demonstrate how message wording, unexpected offers and requests for interaction can help identify phishing patterns.

Combining clearly labelled simulated examples with supplementary public-dataset analysis improves the project's educational value while maintaining transparency about evidence and limitations.

## 8. Reference

Miltchev, Rangelov and Genchev (2024). *Phishing validation emails dataset*. Zenodo.

https://doi.org/10.5281/zenodo.13474746
