# Task 2: Phishing Email Analysis

## Objective
The goal of this task was to analyze multiple phishing email samples and identify key indicators that suggest they are fraudulent. This helps in understanding how phishing attacks work and improves our ability to detect them in the future.

## About the Task
I examined three different phishing email samples that pretended to be from well-known organizations: Google, Paytm, and SBI Bank. Each email was reviewed for signs of phishing such as fake sender addresses, suspicious links, urgent or threatening messages, lack of personalization, and poor grammar.

In addition to this, email headers were checked using an online tool to detect spoofing attempts.

## Samples Analyzed
1. **Fake Google Login Alert**
2. **Fake Paytm Verification Request**
3. **Fake SBI KYC Alert**

## Tools Used
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Browser tools to inspect and hover over URLs
- Manual inspection for grammar, sender domain, and structure

## Key Phishing Indicators Identified
- Misspelled domain names (e.g., "gooogle", "paytm-verifier")
- Use of insecure HTTP links
- Generic greetings like "Dear User" instead of using the recipient’s name
- Scare tactics such as account suspension or blocking
- Mismatch in "Reply-To" and "Return-Path" fields in email headers

## Attachments
None of the analyzed emails had attachments, but phishing attempts often include malicious files (e.g., .zip, .exe, .pdf). This was noted as part of the risk evaluation.

## Outcome
This task helped in understanding how attackers try to manipulate users using social engineering techniques. By learning to identify phishing indicators, one can stay safer while handling emails, especially those asking for personal or financial information.

## Report
Detailed phishing email analysis can be found in the `Phishing Analysis.txt` file in this repository.
