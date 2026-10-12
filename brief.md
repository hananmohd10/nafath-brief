Version: NAFATH-V1
Track: Networking

## Overview

A government Single Sign-On (SSO) service allows citizens to access multiple government services using one account. Software defines how users authenticate, while AI helps detect suspicious login attempts. Mobile security protects access through smartphones and limits applications’ permissions. Networking secures communication between users and online services. Cybersecurity protects accounts from threats such as phishing and unauthorized access. Data protection helps keep citizens’ personal information private and secure. These six areas work together to make government digital services safer, more reliable, and easier to use. Each area has a different role, but weaknesses in one area can affect the security of the entire service. My Networking track focuses on DNS over HTTPS (DoH), examining how it protects DNS queries, improves privacy, and what security limitations remain.

## Software

OAuth 2.0 is an authorization framework that allows applications to access protected resources with the user's permission, without sharing their password. OpenID Connect (OIDC) builds on OAuth 2.0 by adding an authentication layer that verifies the user's identity. Therefore, OAuth 2.0 is designed for delegated access to resources, while OpenID Connect is designed for user login and authentication. They can work together in a secure Single Sign-On (SSO) service.

Resource: OpenID Connect vs OAuth2: The Differences and How to Choose - https://supertokens.com/blog/openid-connect-vs-oauth2

## AI

Before launching an AI model to detect suspicious logins, the authority should identify and assess risks such as harmful bias, privacy loss, security threats, and unreliable results. The NIST AI Risk Management Framework provides four functions: Govern, Map, Measure, and Manage. These help organizations establish accountability, identify potential harms, evaluate risks, and apply mitigations. The model should also be tested and monitored to help ensure secure and reliable operation.

Resource: NIST AI Risk Management Framework (AI RMF) Explained: What It Is and How Organizations Use It - https://orca.security/resources/blog/nist-ai-risk-management-framework-ai-rmf/

## Mobile

Android limits a login app’s access by isolating it in a sandbox, which restricts access to other apps’ data. Runtime permissions also protect sensitive resources, such as the camera, microphone, and location. The app must request permission when it needs to access a protected resource that requires runtime approval. Users can grant or deny the request, helping them control access to their device data.

Resource: How Android Runtime Permissions Influence Enterprise Mobile Risk - https://www.ninjaone.com/blog/how-android-runtime-permissions-influence-enterprise-mobile-risk/

## Networking

DNS over HTTPS (DoH) encrypts DNS queries using HTTPS, helping protect them from being read or altered while travelling across the network. For users of the service, it improves privacy by making it harder for internet service providers and network observers to see which domains they look up. However, DoH does not hide all browsing activity, guarantee protection from malicious websites, or prevent the DoH provider from seeing DNS queries.

Resource: What is DNS over HTTPS (DoH)? - https://www.ssl.com/faqs/what-is-dns-over-https-doh/

## Cybersecurity

Phishing-resistant authentication prevents fake websites from stealing authentication secrets or reusing login responses. Passkeys and FIDO2 security keys qualify because they verify the genuine website’s domain. Certificate-based authentication can also qualify when implemented with appropriate protections. Passwords, SMS codes, email codes, authenticator-app codes, and push approvals are not considered phishing-resistant because attackers may trick users into sharing or approving them. Strong authentication also requires secure account recovery methods.

Resource: Phishing-resistant MFA: what qualifies and what does not - https://www.openideurope.eu/login-security/phishing-resistant-mfa/

## Data

Under Oman’s Personal Data Protection Law, the authority must obtain consent before processing citizens’ personal data, unless a legal exception applies. It must explain the purpose of processing, protect data confidentiality and privacy, and implement appropriate technical and procedural safeguards. The authority must also respect individuals’ rights to access, correct, update, or request deletion of their data, where applicable. If a personal data breach occurs, it must notify the relevant parties as required by law.

Resource: Personal Data Protection - https://www.mtcit.gov.om/sectors/governance/personal

## Misconception in My Track

A common misconception is that DNS over HTTPS (DoH) provides complete privacy. Although DoH encrypts DNS traffic between the user and the DNS resolver, the resolver may still be able to associate queries with the user. Therefore, DoH improves privacy from network observers but does not guarantee complete anonymity.

Resource: DNS Queries over HTTPS (DoH) - RFC Editor - https://www.rfc-editor.org/rfc/rfc8484.html

## Open Question

How can a government authority use DNS over HTTPS to protect citizens’ privacy while still detecting malicious websites and cybersecurity threats?
