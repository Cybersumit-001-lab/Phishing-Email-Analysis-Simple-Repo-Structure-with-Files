Detailed Phishing Email Analysis Report

Objective: To analyze a suspicious Microsoft-themed email and identify phishing characteristics.

Overview

The received email claims to be from Microsoft, warning the recipient about an unusual login from Moscow. Upon investigation, it is confirmed that the message is a phishing attempt designed to steal user credentials by redirecting them to a fake login page.

Findings

Fake Sender Domain: The email originates from access-accsecurity.com, not an official Microsoft domain. Attackers commonly use similar-looking domains to trick users.

Failed Authentication: SPF, DKIM, and DMARC all failed, confirming it was not sent from Microsoft servers.

Deceptive Reply-To Address: Replies are directed to a Gmail account (solutionteamrecognizd03@gmail.com), which is not legitimate.

Mismatched Links: The hyperlink text appears safe but redirects to a phishing page hosted on verify-login-secure-access.xyz.

Urgency and Threats: The message uses time pressure (“within 24 hours”) to provoke immediate reaction.

Tracking Pixel: Hidden image used to track email opening activity.

Spelling and Format: Minor grammar issues and unprofessional formatting reduce credibility.

Technical Indicators

Sending IP: 89.144.9.88

Mail Server: access-accsecurity.com (unauthorized server)

Return-Path: bounce@inlkrqa.co.uk

SPF/DKIM/DMARC: Failed

Fake Link: http://verify-login-secure-access.xyz

Risk Level

High — This phishing email aims to collect Microsoft login credentials and possibly deploy further attacks.

Recommendations

Do not click any links or reply.

Delete the email immediately.

Report to Microsoft via phish@office365.microsoft.com.

Change passwords if credentials were entered.

Enable MFA (Multi-Factor Authentication) for all accounts.

Conclusion

This email is a confirmed phishing attempt with multiple strong indicators: spoofed sender domain, failed authentication, mismatched URLs, and psychological manipulation. It demonstrates classic phishing behavior targeting Microsoft account users.
