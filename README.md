# Composed explanation experiments

### Introduction

Over time, software systems have reached a level of complexity that makes it difficult for their developers and users to explain particular decisions made by them. For component-based system we've developed an approach to tackle this problem.

There, we utilize the data of each component and try to verbalize it in a way that provides meaningful insights into the component and the system as a whole. The verbalization, or, explanation is further created in two ways:

1) via pre-defined templates
2) via LLMs (currently ChatGPT w/o fine-tuning).

In the first step, we focused on explaining input and output data separately as this builds the foundation for any further considerations. In the next step, we try to summarize multiple explanations (scenario: a system with sub-components).
