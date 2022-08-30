---

layout: col-sidebar
title: OWASP API Security Project
tags: api security top10 translations acknowledgments join roadmap news

---

[&#8962; Home](/www-project-api-security)

## Call for Data

The OWASP API Security Project team plans to build and release a new edition of
the OWASP API Security Top 10 in 2022.

This is the first time we're calling for data. Unlike in 2019 when the API
Security Top 10 was first published, we believe the API industry is now more
mature and should be able to contribute valuable data.

### Goals

Collect comprehensive data regarding **API** vulnerabilities to-date in order
to build a new top 10 of the most critical **API** security risks.

### Contributions

To make things smoother we're adhering to the OWASP Top Ten Project
contribution process and data contribution templates that most vendors/security
practitioners are already familiar with.

#### Contributors

We're expecting data coming from a variety of sources, such as security
vendors and consultancies, bug bounties programs, and security practitioners in
general such as pentesters.

#### Period

This call for data will be open during September-November of 2022.

Contribute data should date **from 2019 to the end of 2021** and it **should be
API-specific** e.g. REST, GraphQL, gRPC, JSON-RPC, XML-RPC, etc.

#### Process

Data can be [uploaded here].

If for some reason you're not comfortable using the form to contribute data,
please reach out to `paulo.silva@owasp.org` for an alternative method.

#### Data Structure

We're providing two submission templates: [CSV] and [JSON].

The data structure is very similar to the one used by the OWASP Top Ten Project
with an additional attribute: `apiProtocol`. In case you already have automated
tools to compile and output one of these file formats, you should be able to
use it with little changes.

##### Per Dataset

| Attribute | Required? | Description |
| :-------- | :-------: | :---------- |
| NumberofAppsTested | Yes | How many APIs were tested |
| CWE | Yes | ID of the weakness found in tested APIs |
| NumberofAppsPer | Yes | Number of APIs the CWE was found in |
| TimePeriod | No | When (year) the weakness was first found: 2021/2020/2019 |
| ContributorName | No | Who's contributing the data |
| ContributorContactEmail | No | Email of who is contributing the data |
| TypeofTesting | No | Type of test performed to identify the weakness: TaH<sup>1</sup>/HaT<sup>2</sup>/Tool |
| APIProtocol | No | Type of API protocol: REST/GraphQL/gRPC/SOAP/... |
| PrimaryLanguage | No | What programming language was used to implement the API logic |
| Region | No | Global/North America/EU/Asia/Other |
| Industry | No | Primary industry: Multiple/Financial/Industrial/Software/...|
| Retest | No | Whether the data contains retests or the same applications multiple times: T/F |

---

1. Tool assisted Human
2. Human assisted Tool

[uploaded here]: https://docs.google.com/forms/d/e/1FAIpQLSdcZU3cbkcGtpS9-2wMH0WMbT3H4ZFC9QOOSh2d0v67B2nUuA/viewform
[CSV]: ./sample-data-submission.csv
[JSON]: ./sample-data-submission.json
