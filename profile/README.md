# DamageBDD

**Behaviour verification at planetary scale.**

DamageBDD lets humans describe expected software behaviour in plain language, then verify that behaviour against real systems.

It is built around **Gherkin**, **BDD**, high-scale execution, cryptographic accountability, and machine-readable evidence.

```gherkin
Feature: Public API health

  Scenario: The service is reachable
    Given I am using server "https://damagebdd.com"
    When I make a GET request to "/version/"
    Then the response status must be "200"
````

## What DamageBDD does

DamageBDD turns behaviour into executable verification.

Instead of hiding quality behind specialist test tooling, DamageBDD lets product owners, engineers, auditors, operators, and customers define what a system must do in language everyone can read.

If the behaviour can be defined, DamageBDD can verify it.

## Core capabilities

* **BDD execution** using human-readable Gherkin feature files
* **HTTP/API verification** with reusable steps for requests, headers, JSON, YAML, status codes, and response bodies
* **Load and scalability testing** through concurrent execution
* **Regression verification** for CI/CD pipelines
* **Cryptographic result publishing** for durable evidence
* **Bitcoin Lightning aligned execution economics**
* **Aeternity smart-contract integration**
* **Damage node execution** for distributed verification work

## Why it matters

Modern software systems fail when behaviour is assumed instead of verified.

DamageBDD makes behaviour explicit, repeatable, and accountable.

It gives teams a shared language for quality, while giving infrastructure a way to prove that work was executed.

## Damage Token

Damage Token is not a yield promise.

It is an execution utility: a fee mechanism for behaviour verification, node execution, and contract-backed verification workflows.

Value is unlocked when behaviour is verified and execution is completed.

## Built for

* Engineering teams
* CTOs and founders
* Auditors
* DevOps and platform teams
* Security-conscious organizations
* Distributed node operators
* Bitcoin-first builders
* Anyone who needs proof that software behaves as claimed

## Repositories

This organization contains the core DamageBDD platform, Erlang services, execution steps, blockchain integrations, Lightning/NWC tooling, node registry logic, and behaviour contracts.

## Philosophy

Software quality should not depend on trust.

It should be described clearly, executed repeatably, and recorded honestly.

**Define the behaviour.
Run the verification.
Record the damage.**

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
