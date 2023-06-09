<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [What/why is this?](#whatwhy-is-this)
- [The Challenge](#the-challenge)
  - [Challenge tl;dr](#challenge-tldr)
- [The Response](#the-response)
  - [1. POC](#1-poc)
  - [2. Response to Challenge](#2-response-to-challenge)
  - [3. Innovation/Creative engineering](#3-innovationcreative-engineering)
  - [4. Project Plan](#4-project-plan)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

Links
| [Home](https://sramam.github.io/work-sample/)
| [Challenge](https://sramam.github.io/work-sample/challenge)
| [Response](https://sramam.github.io/work-sample/solution)
| [zero-downtime migration](https://sramam.github.io/work-sample/zero-downtime-migrations#zero-downtime-migrations)
|| Git Repo
| [Source Code](https://github.com/sramam/work-sample)
| [Readme](https://github.com/sramam/work-sample#readme)
| [Code Design](https://github.com/sramam/work-sample/blob/main/DESIGN.md)

---

## What/why is this?
> I am actively interviewing for senior engineering roles.
> Each interview process tries to establish a base-line in it's own way - some better than others.
>
> I spent considerable time on one of these assignments. I decided to anonymize and adapt the work and share it via github.
> The hope is prospective employers get a preview of my work style and output (and hopefully more 👍 and less 👎?!)

## The Challenge
The challenge was to convert a traditional multi-tenant architecture to one that  enables multi-tenant inter-connectivity for a slack-like system.
See this [for a fuller description of the problem](./challenge.md)

### Challenge tl;dr 

- Before
![challenge2](./challenge2.jpg)

- After 
![challenge3](./challenge3.jpg)

## The Response

A high level view of the system design. [More details here](./solution.md)

![app-arch](./app-arch.jpg)


Since a rabbit-hole was entered with the assignment, a highlights reel in summary:


### 1. POC 
This POC was implemented pre-interview, from a problem stated in the job description (...I had some time to spare). [github link](https://github.com/sramam/work-sample)
  - [design doc](https://github.com/sramam/work-sample/blob/main/DESIGN.md)
  - [Read me](https://github.com/sramam/work-sample#readme)
  - Uses [oso](https://www.osohq.com/) as the authorization library
  - Implements the [smallest possible POC of the policy requirement](https://github.com/sramam/work-sample/blob/main/gsb.polar)
  - Accomplishes [100% coverage](https://github.com/sramam/work-sample#quality)

### 2. Response to Challenge
During the interview process, a more formal system design assignment was requested. This aligned well with the
POC implemented above, but had enough differences to require some effort.

  - [Approach](./solution.md#approach)
  - [Design](./solution.md#design)
  - [Challenge Questions](./solution.md#responses-to-followup-questions)

### 3. Innovation/Creative engineering
An example of solving by tacking the root of the problem instead of just treating the symptoms.

  - [Zero-downtime mongoDB migrations](./solution.md#1-db-schema-migrations)

### 4. Project Plan
Preliminary project planning activity
  - [Project Plan](./solution.md#5-migration-plan)

---

Links
| [Home](https://sramam.github.io/work-sample/)
| [Challenge](https://sramam.github.io/work-sample/challenge)
| [Response](https://sramam.github.io/work-sample/solution)
| [zero-downtime migration](https://sramam.github.io/work-sample/zero-downtime-migrations#zero-downtime-migrations)
|| Git Repo
| [Source Code](https://github.com/sramam/work-sample)
| [Readme](https://github.com/sramam/work-sample#readme)
| [Code Design](https://github.com/sramam/work-sample/blob/main/DESIGN.md)


---
