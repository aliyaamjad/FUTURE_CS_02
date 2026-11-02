Email Header Analysis Methodology

1. Purpose

Email header analysis helps security reviewers examine the technical information associated with an email. It can provide useful clues about the sender, message routing, and email authentication.

This document explains a safe, repeatable method for reviewing email headers as part of the FUTURE_CS_02 Phishing Email Detection & Awareness System.

2. Tools Used

- Gmail – Show Original: Displays the original message headers and authentication summary.
- Google Admin Toolbox – Messageheader: Helps interpret and examine email header information.

Official references:

- Gmail Help: https://support.google.com/mail/answer/29436
- Google Admin Toolbox: https://toolbox.googleapps.com/apps/messageheader/

3. Header Inspection Procedure

Step 1: Open the email

Open the email you want to review in Gmail using a trusted account.

Step 2: Display the original message

1. Open the email.
2. Select the three-dot menu beside the reply option.
3. Choose Show original.
4. Review the authentication summary and original header information.

Step 3: Review important fields

Header field| What it helps identify
From| The sender address displayed to the recipient.
Reply-To| The address where replies are directed.
Return-Path| The address associated with handling delivery failures.
Received| Information about servers involved in message delivery.
Message-ID| A unique identifier assigned to the message.
Authentication-Results| Authentication results reported by receiving mail infrastructure.

Step 4: Review authentication results

Where available, examine:

- SPF: Indicates whether the sending server is authorised under the domain's SPF policy.
- DKIM: Indicates whether the message has a valid domain-associated digital signature.
- DMARC: Indicates whether the message aligns with the domain's authentication policy.

Authentication results should be interpreted in context. A successful result does not automatically prove that an email is safe, and a failed result should be investigated rather than treated as conclusive proof of phishing.

Step 5: Use the Messageheader tool

Google Admin Toolbox Messageheader can help interpret copied email header information.

Only use headers from a message you are authorised to inspect. Do not publish private email addresses, IP addresses, message IDs, or other identifying information in the public repository.

4. Applying the Method to the FTC Case Study

The FTC phishing example used in this project describes a fraudulent billing notification. However, the FTC webpage does not provide the original raw email or complete technical headers.

Analysis item| Result
Displayed sender address| Not available
Reply-To address| Not available
Return-Path| Not available
Received routing information| Not available
SPF result| Not available
DKIM result| Not available
DMARC result| Not available
Destination URL details| Not available

These fields are marked as unavailable because the required technical evidence was not published with the example.

No header authentication or routing result is claimed for this case study.

5. Safe Analysis Practices

1. Do not open unexpected attachments or suspicious links.
2. Do not enter passwords or verification codes on pages reached through unexpected email links.
3. Do not upload private or unredacted email headers to a public repository.
4. Use authorised samples and trusted analysis tools.
5. Record unavailable evidence honestly.
6. Combine header observations with the message content and sender context.

6. Conclusion

Email header inspection is an important part of phishing investigation. It can help reviewers examine sender information, message routing, and authentication results.

For this project, the procedure is documented, but technical header results for the FTC example remain unavailable because its original headers were not published.

Documentation references:

- Google Gmail Help – Show original: https://support.google.com/mail/answer/29436
- Google Admin Toolbox – Messageheader: https://toolbox.googleapps.com/apps/messageheader/
