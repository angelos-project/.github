# Angelos Project™ Contributing Guidelines

## 1. Introduction

Welcome to the Angelos Project™! We are excited that you are interested
in contributing to our project. This document is intended to provide you
with all the information you need to get started with contributing to
the project. Whether you are a seasoned developer or new to open source,
we hope this guide will help you navigate the contribution process and
make it as smooth as possible.

**Note**: This document is currently under active development and may be
updated, revised, or refined at any time. Changes can be made whenever
questions or issues arise regarding contributor conduct, development
procedures, or contribution processes, and similar matters. Please check
back over time for updates and revisions.


### 1.1. Executive Summary
### 1.2. What This Document Is About
### 1.3. Credits
### 1.4. The Importance of Getting Code Into the Mainline
### 1.5. Licensing

It is imperative that all code contributed to the Angelos Project™ be
legitimately free software. For that reason, code from contributors
without a known identity or anonymous contributors will not be accepted.
All contributors are required to “sign off” on their code, stating that
the code can be distributed with the Angelos Project™ under the
appointed license already put in place in the repository. Code which has
not been licensed as free software by its owner, or which risks creating
copyright-related problems for the Angelos Project™ (such as code which
derives from reverse-engineering efforts lacking proper safeguards)
cannot be contributed. The appointment of license for future (new) 
repositories is ruled by governance at any time to ensure overall 
alignment of usability.


## 2. How the Development Process Works

We use the [Fork and Pull Request model](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) for the moment.
The contributor is expected to keep their fork up to date 
with the main repository.


### 2.1. The Big Picture
### 2.2. The Lifecycle of a Patch
### 2.3. How Patches Get Into the Software
### 2.4. Next Trees
### 2.5. Staging Trees
### 2.6. Tools
### 2.7. Mailing Lists
### 2.8. Getting Started With Angelos Development

## 3. Early-Stage Planning

### 3.1. Specifying the Problem
### 3.2. Early Discussion
### 3.3. Who Do You Talk To?
### 3.4. When to Post?
### 3.5. Getting Official Buy-in

## 4. Getting the Code Right

(To be revised)

The project has a structure that builds on several low-level libraries
that need to be compatible with each other in order to work together.
This is part of the Kotlin/Multiplatform nature as developed by
JetBrains and is a legacy for the whole Kotlin ecosystem. Also Kotlin is
keeping up with emerging commercial platforms which it add support for,
and also deprecated when they are not viable. Therefore, it is necessary
to keep in sync with the further development. Because of limited
developers and contributors, we need to minimize the risk of coming
quirks in Kotlin and its libraries. Thereby it is imperative to follow
best practices to not shoot ourselves in the foot. By having ourselves
rewrite things all the time but rather letting the codebase mature for
high security and stability. All for the sake of maintaining usability,
reliability and security, and minimize any risk of regression and
related issues. Urges to write one owns coding style must be permanently
limited for best practices and survivability of the project as an
organization.

### 4.1. Pitfalls
### 4.2. Code Checking Tools
### 4.3. Documentation
### 4.4. Internal API Changes

## 5. Posting Patches

### 5.1. When to Post
### 5.2. Before Creating Patches
### 5.3. Patch Preparation
### 5.4. Patch Formatting and Changelogs
### 5.5. Sending the Patch

## 6. Followthrough

### 6.1. Working With Reviewers
### 6.2. What Happens Next
### 6.3. Other Things That Can Happen

## 7. Advanced Topics

### 7.1. Managing Patches With Git
### 7.2. Reviewing Patches

## 8. For More Information


## 9. Conclusion


## 10. Attribution
The layout of this guide is inspired by [A guide to the Kernel Development Process](https://docs.kernel.org/process/development-process.html) hosted at [https://docs.kernel.org/process/development-process.html]() as of February 19, 2026.
