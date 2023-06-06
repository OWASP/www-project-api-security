---

layout: col-sidebar
title: OWASP API Security Project
tags: api security top10 translations acknowledgments join roadmap news
level: 3
type: documentation

---

<div class="alert">
  <p style="text-align:center">
    Check out the new 
    <a href="https://owasp.org/API-Security/editions/2023/en/0x00-header/">
      OWASP API Security Top 10 2023
    </a>! 
  </p>
</div>

## What is API Security?

A foundational element of innovation in today’s app-driven world is the API.
From banks, retail and transportation to IoT, autonomous vehicles and smart
cities, APIs are a critical part of modern mobile, SaaS and web applications and
can be found in customer-facing, partner-facing and internal applications. By
nature, APIs expose application logic and sensitive data such as Personally
Identifiable Information (PII) and because of this have increasingly become a
target for attackers. Without secure APIs, rapid innovation would be impossible.

API Security focuses on strategies and solutions to understand and mitigate the
unique vulnerabilities and security risks of Application Programming Interfaces
(APIs).

## API Security Top 10 2023

Here is a sneak peek of the 2023 version:

* **[API1:2023 - Broken Object Level Authorization][API1:2023]**

  APIs tend to expose endpoints that handle object identifiers, creating a wide
  attack surface of Object Level Access Control issues. Object level
  authorization checks should be considered in every function that accesses a
  data source using an ID from the user. [Continue reading][API1:2023].
* **[API2:2023 - Broken Authentication][API2:2023]**

  Authentication mechanisms are often implemented incorrectly, allowing
  attackers to compromise authentication tokens or to exploit implementation
  flaws to assume other user's identities temporarily or permanently.
  Compromising a system's ability to identify the client/user, compromises API
  security overall. [Continue reading][API2:2023].
* **[API3:2023 - Broken Object Property Level Authorization][API3:2023]**

  This category combines [API3:2019 Excessive Data Exposure][API3:2019] and
  [API6:2019 - Mass Assignment][API6:2019], focusing on the root cause: the lack
  of or improper authorization validation at the object property level. This
  leads to information exposure or manipulation by unauthorized parties.
  [Continue reading][API3:2023].
* **[API4:2023 - Unrestricted Resource Consumption][API4:2023]**

  Satisfying API requests requires resources such as network bandwidth, CPU,
  memory, and storage. Other resources such as emails/SMS/phone calls or
  biometrics validation are made available by service providers via API
  integrations, and paid for per request. Successful attacks can lead to Denial
  of Service or an increase of operational costs. [Continue reading][API4:2023].
* **[API5:2023 - Broken Function Level Authorization][API5:2023]**

  Complex access control policies with different hierarchies, groups, and roles,
  and an unclear separation between administrative and regular functions, tend
  to lead to authorization flaws. By exploiting these issues, attackers can gain
  access to other users’ resources and/or administrative functions. [Continue
  reading][API5:2023].
* **[API6:2023 - Unrestricted Access to Sensitive Business Flows][API6:2023]**

  APIs vulnerable to this risk expose a business flow - such as buying a ticket,
  or posting a comment - without compensating for how the functionality could
  harm the business if used excessively in an automated manner. This doesn't
  necessarily come from implementation bugs. [Continue reading][API6:2023].
* **[API7:2023 - Server Side Request Forgery][API7:2023]**

  Server-Side Request Forgery (SSRF) flaws can occur when an API is fetching a
  remote resource without validating the user-supplied URI. This enables an
  attacker to coerce the application to send a crafted request to an unexpected
  destination, even when protected by a firewall or a VPN. [Continue
  reading][API7:2023].
* **[API8:2023 - Security Misconfiguration][API8:2023]**

  APIs and the systems supporting them typically contain complex configurations,
  meant to make the APIs more customizable. Software and DevOps engineers can
  miss these configurations, or don't follow security best practices when it
  comes to configuration, opening the door for different types of attacks.
  [Continue reading][API8:2023].
* **[API9:2023 - Improper Inventory Management][API9:2023]**

  APIs tend to expose more endpoints than traditional web applications, making
  proper and updated documentation highly important. A proper inventory of hosts
  and deployed API versions also are important to mitigate issues such as
  deprecated API versions and exposed debug endpoints. [Continue
  reading][API9:2023].
* **[API10:2023 - Unsafe Consumption of APIs][API10:2023]**

  Developers tend to trust data received from third-party APIs more than user
  input, and so tend to adopt weaker security standards. In order to compromise
  APIs, attackers go after integrated third-party services instead of trying to
  compromise the target API directly. [Continue reading][API10:2023].

## Licensing

**The OWASP API Security Project documents are free to use!**

The OWASP API Security Project is licensed under the [Creative Commons
Attribution-ShareAlike 4.0 license][license], so you can copy, distribute and
transmit the work, and you can adapt it, and use it commercially, but all
provided that you attribute the work and if you alter, transform, or build upon
this work, you may distribute the resulting work only under the same or similar
license to this one.

[license]: https://creativecommons.org/licenses/by-sa/4.0/
[API1:2023]: https://owasp.org/API-Security/editions/2023/en/0xa1-broken-object-level-authorization/
[API2:2023]: https://owasp.org/API-Security/editions/2023/en/0xa2-broken-authentication/
[API3:2023]: https://owasp.org/API-Security/editions/2023/en/0xa3-broken-object-property-level-authorization/
[API3:2019]: https://owasp.org/API-Security/editions/2019/en/0xa3-excessive-data-exposure/
[API6:2019]: https://owasp.org/API-Security/editions/2019/en/0xa6-mass-assignment/
[API4:2023]: https://owasp.org/API-Security/editions/2023/en/0xa4-unrestricted-resource-consumption/
[API5:2023]: https://owasp.org/API-Security/editions/2023/en/0xa5-broken-function-level-authorization/
[API6:2023]: https://owasp.org/API-Security/editions/2023/en/0xa6-unrestricted-access-to-sensitive-business-flows/
[API7:2023]: https://owasp.org/API-Security/editions/2023/en/0xa7-server-side-request-forgery/
[API8:2023]: https://owasp.org/API-Security/editions/2023/en/0xa8-security-misconfiguration/
[API9:2023]: https://owasp.org/API-Security/editions/2023/en/0xa9-improper-inventory-management/
[API10:2023]: https://owasp.org/API-Security/editions/2023/en/0xaa-unsafe-consumption-of-apis/
