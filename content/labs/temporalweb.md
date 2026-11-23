---
title: "TemporalWebLab"
draft: false
params:
  subtitle: "Evaluating Recency and Change across the Web"
  url: https://clef-temporalweblab.github.io/2027/
menu:
  main:
    identifier: "lab-temporal"
    parent: "labs"
    weight: 140
---

 

TemporalWebLab aims to advance research on temporal information retrieval and question answering by addressing the challenges of information freshness and change on the Web. The lab provides shared evaluation benchmarks to support the development and assessment of systems that account for the temporal validity of information and leverage changing Web evidence.

<!--more-->

## Tasks

TemporalWebLab features two complementary tasks:

{{< accordion  open_all="true" >}}
  {{< accordion-item title="Question Recency Requirement Estimation" >}}
  Participants estimate how soon a currently correct answer to a question may become outdated. Given a question and optional context, systems assign one of 12 ordered recency classes, ranging from "An-Hour" to "Never", reflecting how frequently the information may need to be updated.
  {{< /accordion-item >}}
  {{< accordion-item title="Question Answering over Web Archives" >}}
  Participants answer questions on how information has changed over time using archived Web pages. Given a question, systems must retrieve relevant snapshots of Web pages captured at different points in time and use them to construct an answer. Questions may ask what information was available at a particular time, how it differed between two time periods, or how it evolved across multiple archived versions. The task evaluates both the retrieval of relevant archived evidence and the correctness of the generated answers.

  {{< /accordion-item >}}
{{< /accordion >}}


## Organizers

- Bhawna Piryani (University of Innsbruck, Austria)
- Jamshid Mozafari (University of Innsbruck, Austria)
- Sawood Alam (Internet Archive, USA)
- Ricardo Campos (University of Beira Interior / INESC TEC, Portugal)
- Avishek Anand (Delft University of Technology, Netherlands)
- Adam Jatowt (University of Innsbruck, Austria)
