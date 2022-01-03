# Avoiding Social Engineering

*   Verify requests that you receive via email or messaging
*   Verify the request out of band, when possible
*   Alert the Security Officer if you are targeted. Don’t delete evidence!
*   Use hardware security keys for MFA/2FA

Aside from pattern recognition, how can we avoid phishing and other social engineering?

**First, recognize that anyone can send you an email, and emails are easy to fake.** Email headers can be spoofed easily and the content of the email can contain malicious links to fake sites or malware.

**Second, remember that attackers try to upset you.** We saw the fake Google account compromise email - very clever. Other times the email may say you have been sued and because you didn’t respond, a default judgment against you has been awarded, and possibly a warrant for your arrest. Attackers try to use whatever they can to trip you up and make you forget to verify the request.

**Third, tell your Security Officer immediately if you receive any phishing or other social engineering scams.** Most likely you are not alone. Even if you catch one, the rest of your organization needs to be aware that we are under attack.

**Never delete emails or other evidence before your Security Officer can investigate.**

**Fourth, even though MFA won’t save you, hardware security keys do offer some protection against phishing. Use them wherever you can.** A universal 2-factor (U2F) hardware security key (such as a Yubikey) generates a new ECC key pair for each service it registers with. When authenticating, the web service must provide a valid authentication request that includes some of that previously agreed-upon information, or else the hardware will not sign the authentication request.
