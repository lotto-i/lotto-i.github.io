---
layout: default
title: "[World’s First External Public Verification · Public Verification Chain] LOTTOi Public Result Verification Whitepaper (English Version)"
permalink: /whitepaper-en.html
---

# [World’s First External Public Verification · Public Verification Chain] LOTTOi Public Result Verification Whitepaper
*(LOTTOi Public Verification Chain Whitepaper – EN)*

---

> **Since 2025. 02. 08.**  
> [LOTTOi](https://www.lottoi.kr) has applied a Google-based external public verification method since February 8, 2025.  
> Since January 29, 2026, LOTTOi has also operated a public verification chain that anchors the Google document URL on GitHub before the draw.
>
> The term “World’s First” in this whitepaper does not refer to lottery services as a whole.  
> It refers to:  
> ① the design and operation of a Google-based external public verification method, and  
> ② the design and operation of a Google·GitHub-linked public verification chain.
>
> Based on the fact that LOTTOi has not identified a similar overseas case for more than one year,  
> LOTTOi uses this expression based on its judgment that the two verification design and operation methods above represent a world-first-level case.

---

## 1. Document Overview

[LOTTOi](https://www.lottoi.kr) designs and operates a public verification method that records generated numbers in an external public document before the draw, so that anyone can compare the pre-draw record with the round result.

LOTTOi has applied a Google-based external public verification method since February 8, 2025.  
The basic principle of this method is not to keep generated numbers only inside the internal system, but to record them in an external public document before the draw.

Since January 29, 2026, LOTTOi has further strengthened round-by-round public record verification by operating a public verification chain that anchors the Google document URL on GitHub before the draw.

LOTTOi’s current public verification method is based on the following two standards.

1. Generated number records are stored in a Google document.
2. The corresponding Google document URL is anchored on GitHub before the draw.

Through this structure, anyone can check whether the Google document URL disclosed after the draw was arbitrarily changed later, and compare it with the actual records in the Google document.

On February 19, 2026, LOTTOi published this public verification whitepaper, which summarizes these public verification principles and operating standards.

---

## 2. Scope of the “World’s First” Expression

LOTTOi does not use the expression “World’s First” in a broad or ambiguous sense.

The term “World’s First” in this whitepaper refers to the following two public verification methods.

First, it refers to the design and operation of the Google-based external public verification method applied since February 8, 2025.  
This method records generated numbers in an external public document before the draw, instead of keeping them only inside the internal system, so that anyone can directly check them afterward.

Second, it refers to the design and operation of the Google·GitHub-linked public verification chain applied since January 29, 2026.  
This method anchors the Google document URL containing the actual generated number records on GitHub before the draw, so that anyone can check whether the verification URL disclosed after the draw was changed afterward.

Based on the fact that LOTTOi has not identified a similar overseas case for more than one year, LOTTOi uses this expression based on its judgment that the two verification design and operation methods above represent a world-first-level case.

However, this expression does not imply any guarantee of winning probability, prediction performance, profit, or results.  
It is a judgment regarding a public verification design method that combines pre-draw records with external verification standards.

---

## 3. Definition of External Public Verification

LOTTOi’s external public verification is a method designed so that anyone can directly check whether generated numbers were recorded in an external public document before the draw, and whether those records were changed after the draw.

In a typical internal record system, it is difficult for anyone, regardless of whether they use the service, to directly confirm whether the numbers actually existed before the draw.

To reduce this limitation, LOTTOi records generated numbers in an external public document and allows anyone to check the records and change history after the draw.

The key principles of external public verification are as follows.

- Generated numbers are not kept only inside the internal system.
- Generated numbers are recorded in an external public document before the draw.
- After the draw, anyone can directly check the records regardless of whether they use the service.
- If a change occurs, the time and content of the change can be checked.

LOTTOi does not aim simply to prevent records from being modified.  
The key objective is to make it impossible to hide the time and content of a change if a change occurs.

Through this, LOTTOi provides a verification standard that reduces post-draw manipulation concerns and allows anyone to check the records directly, regardless of whether they use the service.

---

## 4. Definition of the Public Verification Chain

The public verification chain is a structure designed so that anyone can continuously verify when, where, and under what standard a pre-draw record was made through external records.

LOTTOi’s public verification chain separates the roles of Google documents and GitHub.

The actual generated number records are stored in a Google document.  
The corresponding Google document URL is recorded on GitHub before the draw.

Therefore, anyone can use GitHub commit history to check whether the Google document URL disclosed after the draw was arbitrarily changed afterward.

This structure is not simply a method of storing numbers externally.  
It is a public verification chain designed to allow anyone to verify both the document containing the actual records and whether the URL pointing to that document was anchored before the draw.

---

## 5. Overall Structure of the Public Verification Chain

LOTTOi’s public verification chain is structured as follows based on actual operating standards.

```text
[Pre-creation of a Google public document for each round]
└ Create an external public document where actual generated number records will be stored
└ The document creation time and permission change history are recorded by Google systems
↓
[GitHub URL anchoring]
└ Record the Google document URL for that round on GitHub before the draw
└ The GitHub commit history allows verification of the URL’s pre-draw existence
↓
[Generated numbers finalized and system closed]
↓
[On draw day, after lottery purchase closing and before the draw begins]
└ Store generated number data in the Google public document
└ The storage time and change history are recorded by Google systems
↓
[Lottery draw proceeds]
↓
[Post-draw verification by anyone]
└ Check on GitHub whether the Google document URL was anchored before the draw
└ Check generated number records and version history in the Google document
└ Check whether the data was modified after the draw
```

In this structure, Google documents and GitHub have different roles.

The Google document is the standard for checking the actual generated number records.  
GitHub is the standard for checking whether the corresponding Google document URL was anchored before the draw.

By comparing these two records together, the existence of pre-draw records and any post-draw changes can be verified more clearly.

---

## 6. Role of the Google Document

The Google document is the external public document where actual generated number records remain in LOTTOi’s public verification method.

LOTTOi creates a Google document for each round and records the necessary generated number data in that document based on the pre-draw standard.

The Google document allows the following items to be checked.

- Actual generated number records
- Document creation time
- Data storage time
- Permission change history
- Version history
- Whether any modification occurred after the draw

The core role of the Google document is to provide a standard for checking whether the actual generated numbers were recorded in an external document before the draw.

After the draw, anyone can review the records and version history of the Google document to check whether the data existed before the draw or whether it was changed after the draw.

---

## 7. Role of GitHub

GitHub is not used simply as a record storage location.

In LOTTOi’s public verification chain, the core role of GitHub is to anchor the Google document URL as an external record before the draw.

The actual generated number records are stored in a Google document.  
The corresponding Google document URL is recorded on GitHub before the draw.

Therefore, anyone can directly check whether the Google document URL disclosed on the LOTTOi site after the draw had already been recorded on GitHub before the draw.

GitHub records provide the following standards.

- Whether the Google document URL was recorded before the draw
- Whether the URL was modified later
- If it was modified, when the modification occurred
- Whether the final confirmed URL existed before the draw

The core verification standard is whether the Google document URL used as the final public verification standard was anchored on GitHub before the draw.

---

## 8. Google Document Permission Operation Method

LOTTOi operates Google documents so that pre-draw records and permission changes remain based on an external time standard.

### 8-1. When the Document Is First Created

A Google document for each round is created in advance.  
The document creation time and later permission change records remain in Google systems.

### 8-2. Operation on Draw Day

After lottery purchase closing, the necessary permission changes and data storage are carried out to store generated numbers.

At this time, the generated number data is recorded in the Google document.  
The storage time and later change history can be checked through the version history of the Google document.

This operation method is intended to record major points where operator intervention may occur in an external system.

---

## 9. Post-Draw Verification Method

Anyone can directly check the integrity of the data and the public verification standard through the following paths.

### 9-1. Checking GitHub Records

On GitHub, the following items can be checked.

- Whether the Google document URL was recorded before the draw
- Whether the URL was modified later
- If it was modified, when the modification occurred
- Whether the final confirmed URL existed before the draw

The core role of GitHub is to provide an external reference point where the Google document URL was anchored before the draw.

### 9-2. Checking the Google Document

In the Google document, the following items can be checked.

- Actual generated number records
- Document creation time
- Data storage time
- Version history
- Whether any modification occurred after the draw

In particular, it is important to check whether the record based on the pre-draw standard matches the result currently disclosed.

### 9-3. Comparing the Two Records

GitHub and Google documents have different roles.

GitHub is the standard for checking whether the URL was anchored in advance.  
The Google document is the standard for checking the actual generated number records.

By comparing these two records together, the existence of pre-draw records and any post-draw changes can be verified more clearly.

---

## 10. Standards for Modification Possibility and Change History

It is not technically possible to completely rule out the possibility that a public document may be modified after the draw.

However, the important standard in LOTTOi’s public verification chain is not a claim that modification is impossible.  
The important point is that if a modification occurs, the traces of that modification cannot be hidden.

The Google document may contain the following information.

- Change time
- Change content
- Change order
- Document version history

GitHub may contain the following information.

- Initial recording time of the Google document URL
- URL modification time
- Content before and after the modification
- Commit history

Therefore, anyone can verify afterward whether the data was changed after the draw time.

LOTTOi does not claim that post-draw modification is impossible.  
Instead, LOTTOi aims to provide a verification environment where post-draw modification can be checked through external records.

---

## 11. Operating Principles When Operational Modifications Occur

GitHub records may be modified before the draw due to operational issues such as an incorrect URL entry, document connection error, or input mistake.

In this case, LOTTOi considers the following standards important.

- Initial recording time
- Modification time
- URL before modification
- URL after modification
- Whether the final confirmed URL existed before the draw
- Whether the modification was completed before the draw time

The core verification standard is whether the Google document URL used as the final public verification standard was anchored on GitHub before the draw.

If a URL change occurs after the draw, the verification standard and change history for that round must be checked separately.

---

## 12. Why LOTTOi Designed This Public Verification Method

After encountering lottery-related services, LOTTOi identified a lack of standards for judging actual service value.

Many services explain their results, but there were not enough standards that users could directly check.  
LOTTOi judged that explanations such as photos, testimonials, and interviews alone were not enough to confirm whether generated numbers actually existed before the draw.

For this reason, LOTTOi began looking for a technical method to prove facts.

As a result, LOTTOi designed a public verification method that records generated numbers externally before the draw and allows the existence time and public standard of those records to be checked through external records.

This awareness became a major background for LunaSG’s design and operation of LOTTOi.

---

## 13. Technical Limitations and Operating Environment Notice

Due to unavoidable factors such as external network delays, Google or GitHub platform issues, or permission change delays, the timing of record creation or public standard confirmation may be temporarily delayed.

The purpose of this structure is not to claim a perfect system without delays.

Its purpose is to ensure that if delays or modifications occur, those facts remain in external records and can be checked afterward.

Because the actual creation time and change history remain on external platforms, the time relationship with the draw can be checked afterward.

---

## 14. Expandability of the Public Verification Chain

LOTTOi’s current public verification chain is operated mainly through Google document records and GitHub URL anchoring.

In the future, LOTTOi may also consider adding other external public record methods such as GitLab.

However, this whitepaper does not describe future plans as confirmed features.  
At the current stage, it only states that the public verification chain is a structure that can be expanded by adding external public record methods.

Whether and how to expand the structure will be reviewed based on actual operating stability, user understanding, and the reliability of external platform records.

---

## 15. Scope and Limitations of This Document

This whitepaper was prepared for the following purposes.

- To explain the structure for checking the pre-draw existence of generated number records
- To explain the operating standards of the external public verification method
- To explain the operation of the public verification chain
- To distinguish the roles of Google documents and GitHub
- To provide standards that anyone can directly verify, regardless of whether they use the service
- To explain the technical design intended to reduce post-draw manipulation concerns

This document does not guarantee winning probability, prediction performance, profit, or results.  
Under no circumstances should it be interpreted as an investment, prediction, or guarantee document.

---

## 16. Closing Statement

[LOTTOi](https://lottoi.kr) aims to leave behind a verification standard before speaking about results.

LOTTOi’s public verification whitepaper has one goal.

It is to help the public verification system we designed become a more transparent standard for lottery-related services and contribute to a lottery market without manipulation concerns.

LOTTOi records generated numbers externally before the draw and operates a public verification chain so that those records can be connected and verified through external public record methods.

We hope this model will go beyond the differentiation of a single service and become a trust standard for lottery-related services as a whole.

To support a transparent environment that helps users make rational choices, LOTTOi will continue to treat record standards as important.

---

## Summary

> **Actual generated number records are stored in Google documents.**  
> **The corresponding Google document URL is anchored on GitHub before the draw.**  
> **After the draw, anyone can compare the two records and check whether any post-draw change occurred.**

---

## Key Timeline

| Date | Description |
|---|---|
| 2025. 02. 08. | Applied the Google-based external public verification method |
| 2026. 01. 29. | Applied the public verification chain that anchors the Google document URL on GitHub before the draw |
| 2026. 02. 19. | Published the public verification whitepaper |

---

## Short Introduction

LOTTOi has applied a Google-based external public verification method since February 8, 2025.  
Since January 29, 2026, LOTTOi has operated a public verification chain that anchors the Google document URL on GitHub before the draw.  
Based on the fact that LOTTOi has not identified a similar overseas case for more than one year, LOTTOi uses this expression based on its judgment that the external public verification method and public verification chain design and operation represent a world-first-level public verification method.
