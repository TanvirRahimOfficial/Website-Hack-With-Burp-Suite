* Website-Hack-With-Burp-Suite
This repository contains my work for a university-authorized penetration-testing project performed on a controlled, intentionally vulnerable web application. The objective was to assess authentication robustness, identify weaknesses, and develop ethical exploitation PoCs within a legal academic environment.

* Burp Suite Testing

* The primary tool used during this assessment was Burp Suite community edition, specifically:

Intruder → Clusterbomb Attack Type
Used to systematically test combinations of multiple input parameters during the brute-force phase.
This allowed structured enumeration of credentials in a controlled and rate-limited environment.

* Payload configuration included:

Usernames from a wordlist.

Password from a wordlist.

* Result

Due to poor username & password I have successfully crack it.

* Remediation

* Provided recommendations such as:

Use stronger password.

Add captcha on login page.

Limit the number of retry attempts when logging in (per each IP).

Multi-factor authentication (MFA).
