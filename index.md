---
layout: default
---

# Methodology Assignment 4, Task 2

**Name:** Daniel Budidharma

**UCSD email:** vbudidharma@ucsd.edu

**Section:** D28

**Mentor:** Ryan Lingo

**1. What is the most interesting topic covered in your domain this quarter?**

Probably evals for AI products. I never considered what the development cycle of AI agents these days looks like. They seem so effortlessly capable that it never crossed my mind the amount of effort it took devs to make them this good. Turns out they probably always needed to make these robust and thoughtful evaluations, with clear and measurable objectives. 

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to evaluate different approaches for natural-language dataset search. Specifically our questions are: What representations of datasets (metadata, schema, content samples, embeddings) best support natural-language dataset search? What retrieval methods best support natural-language dataset search?

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

In Quarter 1 we've made a simple version 0 for querying data using Keyword Search, Vector Search, and AI Search. I'd like to expand on Vector Search and AI Search by creating more sophisticated workflows and data structures to systematically find data. For example, datasets can be organized in trees or graphs to better connect complex relations between them. Another issue is that our version 0 is currently only built for excel files, but should be able to query PDFs and other types of professional documents too. 

**4. What other techniques would you be interested in using in your project?**

Our mentor mentioned using Langfuse and Laminar to look at agent traces and gain a deeper understanding of how they work and where we can improve their workflows. I'd like to explore that. I would also like to test different embedding models, right now we defaulted to EmbeddingGemma2. s