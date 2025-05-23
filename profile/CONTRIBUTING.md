# Contributing to the Digital Health Section Code Repositories

Before getting started, you should know what GitHub is and how it works. Here is a [written introduction](https://docs.github.com/en/get-started/start-your-journey/hello-world) and a [video](https://youtu.be/tRZGeaHPoaw?si=abV6YoBKByy66G4S) tutorial.

## Code of conduct

We expect contributors to act professionally and respectfully; contributors are expected to maintain the safety and dignity of the social environment on GitHub. 

Specifically:

* Respect people, their identities, their culture, and their work.
* Be kind. Be courteous. Be welcoming.
* [Document](#Document) your code - put yourself in the shoes of others.

## What Code should be Added?

This site hosts code repositories made by researchers and students affiliated with the Digital Health Section at DTU Health Tech. In Denmark, the Intellectual Property Right (IPR) legislation works differently whether you're a student or an employee at DTU.

* As a **student**, you own the IPR of your work, including the copyright to any code you write.
* As an **employee**, including PhD students and Research Assistants, DTU owns the IPR and has the copyright to your code.

Thus, adding code to this organization differs in the two cases.

### Student

As a student, you can decide to hand over the code to DTU and add it to this GitHub site. This is something you decide in collaboration with your supervisor and can happen if, for example, you continue some prior work based at DTU, if you want future students to continue working on your project, or if your code is part of a bigger set of projects at DTU. If you wish to transfer the ownership of your code to DTU, you and your supervisor should:

* Create and sign the "Declaration of confidentiality and assignment of intellectual property rights" also known as the "G Declaration" (available at [DTU INSIDE](https://www.inside.dtu.dk/en/medarbejder/forskning-innovation-og-raadgivning/forskningssamarbejde-jura-og-kontraktforhold/for-kontraktansvarlige/download-templates?rfb=eyJ2IjoxLCJwIjpmYWxzZSwiZGV2IjoiIiwidWlkIjoiMjYzMTA5ODgtYWViOS00YzAyLWI1ZWQtNDg0NDIwZTZjZGJhIiwic2NwIjoiaW50ZXJuYWwiLCJrYmlkIjozNTAsInNpZCI6ImFKTktQcFJWLW5KQ0FqZnJCWkFqSnciLCJhaWQiOjUzMzI3MDQsInNlY2lkIjoxNTQ3ODMwNTgsInN0Ijoid2ViX3NjcmFwZSIsInQiOiJzZWFyY2gifQ))
* Create and use a code repository in this GitHub organization (or transfer the repository from another GitHub account, like your own).
* Make sure that your code is [documented](#Documentation) correctly (see below)

### DTU Employee

If you are a DTU employee, e.g., a PhD Student (note that in Denmark you are legally speaking **not** a student if you are a PhD "Student", but en employee at the university), a Research Assistant, Researcher, or Professor, DTU has all rights to any IPR you may create, including copyright to any software you may create. To quote the "[About software](https://www.inside.dtu.dk/en/medarbejder/forskning-innovation-og-raadgivning/forskningssamarbejde-jura-og-kontraktforhold/om-software)" section on DTU INSIDE:

> [!IMPORTANT]
> _DTU automatically acquires all rights to software that has been developed by DTU employees during the performance of their work at DTU. It is of no importance whether the software was written within normal working hours or during leisure time._

This entails:

* Any software project you own or lead should be part of this GitHub organization (as one or more repositories).
* Any software you contribute to other repositories needs to be covered by a collaboration agreement with DTU that explains IPR ownership ( but this is not relevant for this GitHub setup).
* You cannot share your code (e.g., as open source) with anyone without permission from DTU (see below).
* You should file a software notification form (SNF) to DTU on any software you have created.

As written on INSIDE:

> [!CAUTION]
> _Because software belongs to DTU, it is important that it is handled according to DTU’s software procedures, including submission of a Software Notification Form (SNF), which depends on whether or not the department wants to commercialize the software or not._


## Open Source

Since DTU owns all software, you cannot open-source any software (i.e., make a repository "public") without the permission of DTU. This process starts with going over a [Checklist](https://www.inside.dtu.dk/-/media/dtu-inside/medarbejder/forskning-innovation-raadgivning/forskningssamarbejde-jura-og-kontraktforhold/software/checklist-software_rev-23-04-2024.docx) that asks about the nature of your software. As stated on INSIDE:

> [!NOTE]
> _If you [...] prefer to share software developed at DTU on a non-commercial basis, and if no third-party rights prevent such publication or sharing of the software, then you [...] may publish or share the software under a license of your own choice – provided, however, that you can answer “no” to all questions in the Checklist._
> _If the answer to one or more questions in the Checklist is “yes”, you must complete a simple non-commercial Software Notification Form (SNF), which then will be reviewed by DTU Legal & Technology Transfer before your software may be published or shared with anyone._

## Copyright Statement

Since DTU owns all software created by its employees, software published, or made available in any other way, must always state DTU as the copyright holder of the software with the following copyright notice:

```
Copyright (c) [YYYY] Technical University of Denmark (DTU).
```
This copyright notice should be added to **ALL** files in the repository.

If preferred, the names of the developers can be added in addition to the general copyright notice, e.g.:

```
Copyright (c) [YYYY] Technical University of Denmark (DTU).

The original version of the software was developed by
  * [Name, Position, Department],
  * [Name, Position, Department],
  * [Name, Position, Department]. 
```

Or the names can be added to the `AUTHORS.md` file in the repository.


## Documentation

If and when you contribute code to a repository - be it your own or others - please ensure it is well-documented. This entails:

* Write a thorough and programmer-friendly README for each repository.
* Write proper API documentation for your code (see below).
* Create additional markdown (`.md`) files or wiki pages that explain and document how to use your code
* Provide example code to get people started.
* Write correct and concise English documentation (avoid Danish or other non-English documentation)

For example, look at the [CARP Core Kotlin](https://github.com/cph-cachet/carp.core-kotlin) repository, which provides exemplary documentation and works as an example of the level of documentation expected.

### API Documentation

Depending on your programming language, there are the following API documentation guides to follow:

* **Python** - please follow the "[Documenting Python Code: A Complete Guide](https://realpython.com/documenting-python-code/)" guidelines.
* **Dart/Flutter** - please follow the "[Effective Dart: Documentation](https://dart.dev/effective-dart/documentation#doc-comments)" guidelines.
* **MATLAB** - please follow the "[MonkeyProof Coding Standard for MATLAB](https://doc.monkeyproofsolutions.nl/code-checker-for-matlab/monkeyproof-coding-standard-for-matlab/title.html)" guideline when writing MATLAB code and the "[MATLAB Style Guidelines 2.0](https://nl.mathworks.com/matlabcentral/fileexchange/46056-matlab-style-guidelines-2-0)" for documentation.
* **Kotlin** - please follow the "[Best practices for library authors to create informative documentation](https://kotlinlang.org/docs/api-guidelines-informative-documentation.html)" guide in general and the "[KDoc](https://kotlinlang.org/docs/kotlin-doc.html)" style / tool for documenting code and APIs.

  
