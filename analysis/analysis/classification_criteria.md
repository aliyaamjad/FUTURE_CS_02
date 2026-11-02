Email Classification Criteria

1. Purpose

This framework defines how email samples are classified in the FUTURE_CS_02 Phishing Email Detection & Awareness System.

Each email is reviewed using observable indicators such as sender information, message content, urgency, unexpected requests, and link-related warning signs.

2. Classification Categories

A. Safe

An email may be classified as Safe when the available evidence shows no clear phishing indicators and the message is consistent with an expected, independently verified communication.

Examples of observations:

- Expected communication from a known service.
- No unexpected request for passwords or verification codes.
- No suspicious payment demand.
- Sender and message context are consistent with the expected communication.

Recommended action: Continue to use normal security practices. A Safe classification does not guarantee that an email is harmless.

B. Suspicious

An email is classified as Suspicious when one or more warning signs are present, but the available evidence is insufficient to confidently identify it as phishing.

Possible indicators:

- Unexpected invoice or payment notification.
- Unfamiliar sender.
- Unusual attachment.
- Unexpected account warning.
- Unverified link or request.

Recommended action: Do not interact with suspicious links or attachments. Verify the message through an independently obtained official contact channel.

C. Phishing

An email is classified as Phishing when strong evidence indicates an attempt to deceive recipients into revealing sensitive information, making fraudulent payments, or visiting a deceptive website.

Possible indicators:

- Requests for passwords or one-time verification codes.
- Deceptive account-verification requests.
- Impersonation of a trusted organisation.
- Fraudulent payment requests.
- Strong pressure to follow an unexpected link.

Recommended action: Do not respond, click links, or provide information. Report the message through the appropriate email or organisational reporting process.

3. Indicator Review Table

Indicator| What the reviewer checks
Sender identity| Whether the sender is expected and independently verifiable.
Domain| Whether the domain appears consistent with the claimed organisation.
Urgency| Whether the message pressures the recipient to act immediately.
Links| Whether the destination is unexpected or inconsistent with the claimed organisation.
Attachments| Whether an unexpected attachment is included.
Sensitive information| Whether passwords, payment details, or verification codes are requested.
Message context| Whether the recipient expected the communication.
Header evidence| Whether available authentication and routing information raises concerns.

4. Example Classification

Sample ID| Scenario| Classification
E01| Routine account notification| Safe-style control
E02| Unexpected invoice| Suspicious
E03| Bank verification request| Phishing
E04| Unexpected parcel delivery fee| Phishing
E05| Urgent password-reset request| Phishing

These are fictional training examples from the project's sample dataset, not verified real-world emails.

5. Important Limitations

- Classification depends on the evidence available to the reviewer.
- A single indicator does not automatically prove phishing.
- A familiar sender name or logo does not guarantee authenticity.
- Authentication results should be interpreted alongside message content.
- This framework documents a manual review process; it does not represent a tested automated detection engine.

6. Conclusion

A consistent classification framework helps reviewers identify suspicious communication, explain potential risks, and recommend appropriate preventive action.

The three categories—Safe, Suspicious, and Phishing—provide a simple and understandable structure for phishing awareness and email review.
