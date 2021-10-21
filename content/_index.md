---
title: Introduction
type: docs
---

# Azulejo Guide
## About Azulejo
Azulejo is an application for creating Ceramic Network DataModels using data from schema.org to bootstrap the process.
## Ceramic Network
Ceramic is a platform for storing and sharing streams of data.

Examples of streams are a social media feed, a list of transactions, and a collaborative document. Anything where changes are made over time.

The Ceramic system is designed to provide Self-Sovereign Identity and data.

In Ceramic you control your own identities and the data that is recorded with them. This is in contrast to social media companies, who control your feed; a centralized bank, that controls your transactions, or a cloud provider like Google/AWS that controls your documents.

The system is also decentralized, providing censorship resistance.

### Ceramic Data Models
Ceramic uses Data Models to allow new applications to build on existing data.

Data Models are essentially a collection of schemas, which describe the format of data that can be stored, along with some metadata such as a human readable name to make interacting with the schemas easier.

They are wrapped in npm packages so that they can be easily reused within different applications.