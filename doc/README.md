Table of content

- [Project Introduction](#project-introduction)
  - [Assumptions](#assumptions)
  - [Goals](#goals)
  - [Features](#features)
- [Development Process](#development-process)
  - [Architecture overview](#architecture-overview)
    - [Microsoft Orleans and the **Actor Model**](#microsoft-orleans-and-the-actor-model)
  - [Workflow Engine](#workflow-engine)
  - [Rule Engine](#rule-engine)
  - [Real-time Monitoring](#real-time-monitoring)
  - [Reporting and Analytics](#reporting-and-analytics)
  - [Integration Capabilities:](#integration-capabilities)
  - [Scalability and Customization](#scalability-and-customization)


# Project Introduction

## Assumptions

This project **will**:
- Be mainly developed in C# with Microsoft .Net Core 8.0 and above.
- Overall architecture will leverage Microsoft Orleans Framework 7.0 and above.
- Extensively use of asyncronous messaging systems (queue, stream, cqrs, eventing...)
- Software architecture best practices (design patterns, TDD, QA...).
- Using [FOSS](https://itsfoss.com/what-is-foss/) (Free/Libre Open Source Software) technologies as much as possible.

## Goals

## Features

Key features of our Manufacturing Execution System include:

- Workflow Engine: Our system comes with a robust workflow engine that allows you to define and manage complex manufacturing processes. You can easily create and modify workflows, assign tasks to different teams or individuals, and track the progress of each step.

- Rule Engine: The rule engine enables you to define and enforce business rules and logic within your manufacturing processes. You can set up rules to validate inputs, trigger actions based on specific conditions, and ensure compliance with industry standards and regulations.

- Real-time Monitoring: Our system provides real-time monitoring capabilities, allowing you to track the status of your manufacturing processes at any given time. You can view live dashboards, monitor key performance indicators (KPIs), and identify bottlenecks or issues that may impact production efficiency.

- Reporting and Analytics: Generate comprehensive reports and gain valuable insights into your manufacturing operations. Our system offers built-in analytics tools that allow you to analyze historical data, identify trends, and make data-driven decisions to optimize your processes.

- Integration Capabilities: Seamlessly integrate our Manufacturing Execution System with your existing enterprise systems, such as ERP (Enterprise Resource Planning) or MES (Manufacturing Execution System). This ensures data consistency and enables end-to-end visibility across your organization.

- Scalability and Customization: Our system is designed to scale with your business needs. Whether you have a small manufacturing facility or a large enterprise, our solution can adapt to your requirements. Additionally, we offer customization options to tailor the system to your specific workflows and business processes.

# Development Process

## Architecture overview

### Microsoft Orleans and the **Actor Model**

Orleans is based on the "actor model". The actor model originated in the early 1970s and is now a core component of Orleans. The actor model is a programming model in which each actor is a lightweight, concurrent, immutable object that encapsulates a piece of state and corresponding behavior. Actors communicate exclusively with each other using asynchronous messages. Orleans notably invented the Virtual Actor abstraction, wherein actors exist perpetually.

Actors are purely logical entities that always exist, virtually. An actor cannot be explicitly created nor destroyed, and its virtual existence is unaffected by the failure of a server that executes it. Since actors always exist, they are always addressable.

This is a novel approach to building a new generation of distributed apps for the Cloud era. The Orleans programming model tames the complexity inherent to highly parallel distributed apps without restricting capabilities or imposing constraints on the developer.

For more information, see [Orleans: Virtual Actors](https://www.microsoft.com/research/project/orleans-virtual-actors) via Microsoft Research. A virtual actor is represented as an Orleans grain.

__Reference taken from [Microsoft Orleans Getting Started](https://learn.microsoft.com/en-us/dotnet/orleans/overview)__

## Workflow Engine

> TODO

## Rule Engine

> TODO

## Real-time Monitoring

> TODO

## Reporting and Analytics

> TODO

## Integration Capabilities:

> TODO

## Scalability and Customization

> TODO