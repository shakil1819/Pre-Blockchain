
https://codevoweb.com/django-implement-2fa-two-factor-authentication/
# Django – Implement (2FA) Two-Factor Authentication

The **one-time passcode** (OTP) tokens can be delivered to the user’s mobile device via SMS, Email, Push notification, Voice call, and more but we’ll use an Authenticator app instead. An Authenticator app is more secure than the other methods because it uses strong encryption to generate **time-based one-time passwords** (TOTP) based on the time of day.

![[Pasted image 20230329071332.png]]

## Prerequisites

-   Python **3.6+** installed. Download the latest version of Python from [https://www.python.org/downloads/](https://www.python.org/downloads/).
-   A basic understanding of REST API will be beneficial
-   Basic knowledge of Django and Django REST framework.
-   An authenticator app like Authy or Google Authenticator.

