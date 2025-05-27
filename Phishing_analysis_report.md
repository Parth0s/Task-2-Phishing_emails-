# Phishing Email Analysis Report

## Sample Email Analyzed
Email claiming to be from PayPal Support, requesting urgent account verification.

## Phishing Indicators Found
1. **Spoofed Sender Address:** The `From` address (`support@paypal.com`) does not match the `Reply-To` (`customer.service@secure-paypal.org`) or `Return-Path` (`customer.service@secure-paypal.org`), indicating email spoofing.
2. **Suspicious Header:** The header contains `X-Mailer: CustomPhish v1.0`, a clear sign of a phishing tool.
3. **Mismatched URL:** The link in the email points to `http://paypal-secure-login.net/verify`, which doesn’t match the sender’s domain (`paypal.com`).
4. **Urgent Language:** The email uses phrases like “verify your account immediately” and “account will be locked within 24 hours,” creating urgency to prompt action.
5. **Suspicious Tone:** The alarmist tone (“Don’t risk losing access to your funds!”) is uncharacteristic of official PayPal communication.

## Conclusion
The email exhibits multiple phishing characteristics, including spoofing, suspicious headers, mismatched URLs, and urgent language. It is highly likely a phishing attempt designed to steal user credentials.
