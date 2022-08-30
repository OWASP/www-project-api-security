---

layout: col-sidebar
title: OWASP API Security Project
tags: api security top10 translations acknowledgments join roadmap news
level: 3
type: documentation

---

<div class="alert">
  <p style="text-align:center">OWASP API Top 10 2022 call for data is open!
  Check out <a href="announcements/cfd/2022/">how to contribute</a>.</p>
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

## API Security Top 10 2019

Here is a sneak peek of the 2019 version:

* **[API1:2019 Broken Object Level Authorization][API1:2019]**

  APIs tend to expose endpoints that handle object identifiers, creating a wide
  attack surface Level Access Control issue. Object level authorization checks
  should be considered in every function that accesses a data source using an
  input from the user. [Read more][API1:2019].
* **[API2:2019 Broken User Authentication][API2:2019]**

  Authentication mechanisms are often implemented incorrectly, allowing
  attackers to compromise authentication tokens or to exploit implementation
  flaws to assume other user's identities temporarily or permanently.
  Compromising a system's ability to identify the client/user, compromises API
  security overall. [Read more][API2:2019].
* **[API3:2019 Excessive Data Exposure][API3:2019]**

  Looking forward to generic implementations, developers tend to expose all
  object properties without considering their individual sensitivity, relying on
  clients to perform the data filtering before displaying it to the user. [Read
  more][API3:2019].
* **[API4:2019 Lack of Resources & Rate Limiting][API4:2019]**

  Quite often, APIs do not impose any restrictions on the size or number of
  resources that can be requested by the client/user. Not only can this impact
  the API server performance, leading to Denial of Service (DoS), but also
  leaves the door open to authentication flaws such as brute force. [Read
  more][API4:2019].
* **[API5:2019 Broken Function Level Authorization][API5:2019]**

  Complex access control policies with different hierarchies, groups, and roles,
  and an unclear separation between administrative and regular functions, tend
  to lead to authorization flaws. By exploiting these issues, attackers gain
  access to other users’ resources and/or administrative functions. [Read
  more][API5:2019].
* **[API6:2019 Mass Assignment][API6:2019]**

  Binding client provided data (e.g., JSON) to data models, without proper
  properties filtering based on an allowlist, usually leads to Mass Assignment.
  Either guessing objects properties, exploring other API endpoints, reading the
  documentation, or providing additional object properties in request payloads,
  allows attackers to modify object properties they are not supposed to. [Read
  more][API6:2019].
* **[API7:2019 Security Misconfiguration][API7:2019]**

  Security misconfiguration is commonly a result of unsecure default
  configurations, incomplete or ad-hoc configurations, open cloud storage,
  misconfigured HTTP headers, unnecessary HTTP methods, permissive Cross-Origin
  resource sharing (CORS), and verbose error messages containing sensitive
  information. [Read more][API7:2019].
* **[API8:2019 Injection][API8:2019]**

  Injection flaws, such as SQL, NoSQL, Command Injection, etc., occur when
  untrusted data is sent to an interpreter as part of a command or query. The
  attacker's malicious data can trick the interpreter into executing unintended
  commands or accessing data without proper authorization. [Read
  more][API8:2019].
* **[API9:2019 Improper Assets Management][API9:2019]**

  APIs tend to expose more endpoints than traditional web applications, making
  proper and updated documentation highly important. Proper hosts and deployed
  API versions inventory also play an important role to mitigate issues such as
  deprecated API versions and exposed debug endpoints. [Read more][API9:2019].
* **[API10:2019 Insufficient Logging & Monitoring][API10:2019]**

  Insufficient logging and monitoring, coupled with missing or ineffective
  integration with incident response, allows attackers to further attack
  systems, maintain persistence, pivot to more systems to tamper with, extract,
  or destroy data. Most breach studies demonstrate the time to detect a breach
  is over 200 days, typically detected by external parties rather than internal
  processes or monitoring. [Read more][API10:2019].

## Licensing

**The OWASP API Security Project documents are free to use!**

The OWASP API Security Project is licensed under the [Creative Commons
Attribution-ShareAlike 3.0 license][license], so you can copy, distribute and
transmit the work, and you can adapt it, and use it commercially, but all
provided that you attribute the work and if you alter, transform, or build upon
this work, you may distribute the resulting work only under the same or similar
license to this one.

[license]: https://creativecommons.org/licenses/by-sa/3.0/
[API1:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa1-broken-object-level-authorization.md
[API2:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa2-broken-user-authentication.md
[API3:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa3-excessive-data-exposure.md
[API4:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa4-lack-of-resources-and-rate-limiting.md
[API5:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa5-broken-function-level-authorization.md
[API6:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa6-mass-assignment.md
[API7:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa7-security-misconfiguration.md
[API8:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa8-injection.md
[API9:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xa9-improper-assets-management.md
[API10:2019]: https://github.com/OWASP/API-Security/blob/master/2019/en/src/0xaa-insufficient-logging-monitoring.md

