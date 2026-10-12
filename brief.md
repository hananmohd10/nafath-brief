Version: NAFATH-V1
Track: <one of: Software | AI | Mobile | Networking | Cybersecurity | Data>

## Overview

A government Single Sign-On (SSO) service allows citizens to access multiple services with one account. Software defines authentication, AI helps detect suspicious logins, and mobile security protects device access. Networking secures communication, cybersecurity protects accounts, and data protection safeguards personal information. These fields work together to provide a secure and reliable service. My track focuses on DNS over HTTPS (DoH) and its security and privacy limitations.

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

## Data

## Misconception in My Track

## Open Question
