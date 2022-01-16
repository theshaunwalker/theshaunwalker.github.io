---
title: Projects
layout: default
---

# Current Projects

## Configurable Lexer

A lexer that is configured with regex token finders and an expected pattern. A simplistic solution intended to lower the barrier
of entry to throwing together new configuration/description file ideas.

## Event sourced app skeleton generator

Using the above configurable lexer. A very BDD approach to description files (think similar to user stories), which are parsed into Domain models, and code is generated for a basic skeleton app.
Domain entities, repositories, events, CQRS commands & queries.
Intended as a basic rapid app development tool to just describe an idea, and then have a functioning proof of concept. 
With events and CQRS at the core, the idea is that whatever domain concepts survive the proof of concept to a proper full app development.
The events and CQRS classes should be able to be copy pasted, with just the architectural specifics like repositories fleshed out to their full app equivalent.


# Project Ideas

###Domain knowledge wiki generator

Take markdown files and compile into a domain wiki for holding domain knowledge about a business.
Automatically linking references of Domain Entities to their single source of truth descriptions
