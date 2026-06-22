---
layout: page
title: About
permalink: /about/
---
# `obiwan.say("hello there")`
---
I'm **John Davidson** - a senior engineer from the greater Chicago area who's been around the block a few times. 
Always looking for the next puzzle to solve. If I'm not hacking away at some backend problem, I'm tinkering with 
electronics, mechanical keyboards, guitars, retro CRT gaming, or disc golf. 

I consider myself a backend engineer and Python enthusiast, but I've touched a ton of different things over the years across many different applications.
If you navigated here, you probably want to run `--verbose` on my CV, so here you go.


# `history | grep "work"`
---

### Hungryroot — Sr. Software Engineer
**Remote · Nov 2025 – Present**

I'm a senior engineer on the Backend/Platform team at Hungryroot, working on Django components, REST APIs, and orchestrated task management combined with message-driven back-office systems for getting food orders fulfilled and delivered for millions of Hungryroot subscribers.

- Owned Celery task orchestration for order lifecycle — ~900K tasks/day across 8+ workers with near-zero failure rate, supporting 4,000–5,000 daily checkouts
- Rebuilt dynamic config and feature-flagging system from unstructured Django admin string configs to Pydantic-validated structures with a local-memory caching layer backed by Redis pub/sub, eliminating read bottlenecks
- Replaced per-worker Chromium instances (causing weekly OOM crashes) with a dockerized sidecar; reduced active Chromium processes 6x per ECS task, cut memory footprint ~75% (~900MB → ~175MB), and eliminated all manual restart incidents
- Built navigation API endpoints for Marketing and Product, modeling hardcoded JSON configs as Django ORM entities with admin preview, publish/hide controls, and A/B experiment hook-in per user segment
- Migrated legacy Reports system (single-threaded hourly bottleneck) to a Workflows framework, centralizing order step insights and eliminating the processing bottleneck

**Stack:** Python, Django, DRF, Pydantic, Celery, Redis, MySQL, AWS, EKS, Docker, GitHub Actions, Datadog, Sentry, Terraform



### Komodo Health — Sr. Software Engineer
**Remote · May – Sep 2025**

Komodo provides a massive data analytics platform for healthcare industry trends nationwide, used by everyone from research universities to pharmaceutical companies. 
I had a brief but thrilling stint at Komodo Health, prior to the all-too-common startup restructuring woes. I was a backend engineer on the Data org's "Customer Universe" pod, 
building services/APIs and orchestrated business-critical DAG workflows for maintaining continual updates to massive customer datasets in Snowflake.
- Architected and led development of a metrics API serving patient insights using FastAPI, DynamoDB, and Kafka event streaming. Designed for client frontend and internal LLM consumption.
- Built healthcare data processing workflows to calculate aggregate metrics for LLM ingestion using TemporalIO orchestration and Snowflake
- Drove org-wide Python modernization initiative: led adoption of UV package management and Docker build optimization, cutting CI/CD resource usage by 20%
- Built unit and integration testing frameworks via GitHub Actions, raising team coverage from 10% to 90%+
- Deployed services on Kubernetes via Helm; orchestrated CI/CD pipelines with Argo Workflows

**Stack:** Python, FastAPI, DynamoDB, Kafka, TemporalIO, Snowflake, GitHub Actions, Helm, Argo Workflows, AWS EKS



### Atlassian — Software Engineer
**Remote · Mar 2022 – May 2025**

I had a long tenure at Atlassian, a name we all know in the SaaS big tech world. 
Initially, I joined as a Python dev in the Bitbucket team, embedding in the "Developer Acceleration" pod. In English, that means "work on the services and tools that make us be able to build Bitbucket inside of Bitbucket".
We got absorbed with a few other dev productivity teams after a year to an Atlassian-wide "Dev Experience" org, charged with 
finding ways to improve the velocity and reliability of 4,000+ software engineers across nearly 1,000 different services.

Throughout the evolution of DevEx, I got to work on tools and services that helped entire cohorts of devs with specific language stacks and needs, from build improvement services to local orchestrated e2e setups of a production distributed platform clone (search: "Atlassian Micros") to experimental tooling for creating new stack-based git management toolsets.
Plenty of Java, Go, and even a bit of Rust.

- Architected language-agnostic CI/CD platform in Java enabling Go and Python build support with 50%+ performance gains across 100+ internal services
- Owned Bitbucket Deployment Tooling Service in Python/Go, providing configurable rollout and rollback pipelines with metric collection via Datadog
- Led monorepo stacked-diffs PR toolset development in Go and Rust used by 100+ engineers, reducing PR cycle time by 40% through concurrent processing
- Drove org-wide Python modernization initiative: organized adoption of UV, Ruff, and modern async patterns; achieved 10x reduction in build times for enrolled services
- Mentored 3 junior engineers; established code review standards and engineering best practices across the team
- Built Datadog observability dashboards for deployment platform analytics and service health monitoring

**Stack:** Python (Flask/FastAPI), Go, Java (Spring), Rust, Kotlin, Bitbucket Pipelines, Datadog, AWS, Docker



### SteelSeries — Sr. Software Engineer
**Chicago / Remote · Nov 2018 – Mar 2022**

SteelSeries is a leading PC gaming peripheral company, known for high-quality headsets, keyboards, mice, and more. 
I joined as a senior backend engineer on the web team. We were in charge of the entire direct business online marketplace, which was a
custom-built Django/React app. Throughout my long time there, I eventually became the lead dev on our team of 6, helping build out the ops side of our team
as well as upskilling various devs from just frontend/backend to be able to jump into full-stack work. I also had the fun job of hiring a manager for our org, 
pushing the business to standardize the report structure and rectify people management/mentorship/leadership gaps of our side of the business.

- Led architecture for high-scale e-commerce backend handling $50M+ annual transaction value using Python, Django, and React/TypeScript.
- Designed dynamic product configuration system in Elasticsearch, achieving 40% improvement in direct business conversion rates
- Built mission-critical inventory APIs serving a global fulfillment network, maintaining 99.95% uptime SLA
- Implemented Infrastructure as Code with Terraform on AWS while leading team to move into EKS/Dockerized deploys from old manual processes.
- Led technical direction for Frontend/Backend Web Marketplace team of 6; hired and mentored engineers and established technical interview processes

**Stack:** Python, Django, Elasticsearch, AWS, Terraform, React, TypeScript, and a bit of GraphQL



### Wargaming — Software Engineer
**Chicago, IL · May 2015 – Aug 2018**

Wargaming Chicago was once the video game developer "Day 1 Studios", makers of Mechassault 1+2, F.E.A.R., and a bunch of other classic Xbox/Xbox 360 titles. 
When I joined, they had been acquired by Wargaming, Inc, tasked with creating a console version of the gargantuanly massive PC MMO "World of Tanks". 
I was a software engineer on the web services team, meaning the mishmash of various Django + Flask services used to help the online parts of the game work.
I even got to work a bit on some game server orchestration layer tools in Python. 
- Supported authentication microservices for 3M+ registered MMO World of Tanks users across PlayStation and Xbox platforms
- Designed high-throughput game replay storage system using async Python, handling 20K+ daily retrievals
- Built analytics service powering real-time game metrics and player behavior insights for product teams
- Worked on game server internal monitoring/alerting service

**Stack:** Python, Django, Flask, Redis, RabbitMQ, PostgreSQL, even a bit of Lua



### Conversant (Epsilon) — Software Engineer
**Chicago, IL · Jul 2014 – May 2015**

First non-intern job right out of college, working in the ad tech space at Conversant (now known as Epsilon post 2016).
I got to do an associate engineer rotation program, embedding with the Data Engineering team and Core Ad Tech Team. At the time, 
Data Engineering was a lot of working on Java Hadoop batch jobs while looking into integrating Spark into the stack, as well as 
an internal business metrics portal built with Flask + Grafana. The core ad-tech team was Java/Spring services which bid on real-time advertising
spots for tracked users on behalf of the businesses we ran advertising campaigns for.

- Created metrics display service for advertising revenue insights in Python, Flask, and Grafana
- Enhanced real-time bidding platform in Java, supporting programmatic advertising volume at scale

**Stack:** Python, Flask, Grafana, Java


# `history | grep "school"`
---
I went to DePaul University in Chicago from 2010-2014, majoring in Computer Science.
I kept going and got my combined Master's in CS from DePaul in 2016. My master's focus was on backend web servers and my capstone
project work was a service to manage a fleet of Docker containers with local agents/metrics front-end server. Basically, trying
to make a really amateur EKS dashboard and Kubernetes right before that stuff got popular.

I still think it's fascinating how we build, compose, and deploy the code we write, as it informs the design decisions we make. 
Treating software engineering as a holistic field of study is tantamount to creating good software.


