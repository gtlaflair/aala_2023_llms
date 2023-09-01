# ChatGPT for Content and Item Generation

Antony J. Kunnan & Geoffrey T. LaFlair

## Goals
- Reconceptualize test development 
- from a digital fist perspective
- in the age of large language models

## Be able to generate 
- content for reading assessments
- multiple choice questions, keys and distractors
- prompts and rubrics for performance assessments

| Time        | Topic                                                                              | Activity                                                                                                                                               |
|-------------|------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| 10:00-10:05 | Welcome, introductions, overview of the workshop                                   | Antony introduction Geoff introduction Goals of the workshop	                                                                                           |
| 10:05-10:20 | Digital-first assessment and AI in test development                                | Presentation: What is digital-first assessment is and why is it important Ideas about how AI (LLMs) can be used in test development                    |
| 10:20-10:30 | Technology check                                                                   | Does everyone have ChatGPT working?                                                                                                                    |
| 10:30-10:40 | Reading demo                                                                       | My test specs My prompt Three types of prompting Zero-shot (mine) Few-shot/in-context Chain of thought Questions                                       |
| 10:40-10:45 | Groups of 3-4                                                                      |                                                                                                                                                        |
| 10:45-11:00 | Create reading test specs                                                          | Text type Style Topic Length Level (low, mid, high; grad, undergrad; CEFR) Language Sub-constructs (for questions)                                     |
| 11:00-12:00 | Turn the test specs into a prompt and solicit passages and items                   | Iterate on approaches to prompting                                                                                                                     |
| 12:00-1:30  | Lunch                                                                              |                                                                                                                                                        |
| 1:30-2:00   | Share what you made                                                                | What were you aiming for? Did you get there? How did you prompt GPT to get your outputs                                                                |
| 2:00-2:15   | Specs for performance assessment                                                   | Mode (Speaking / Writing) Purpose Type (independent integrated) Scoring criteria Rubric type (holistic, analytic, primary trait)                       |
| 2:15-3:00   | Turn the test specs into a prompt and solicit writing/speaking prompts and rubrics | Iterate on approaches to prompting                                                                                                                     |
| 3:00-3:10   | Share what you made                                                                | What were you aiming for? Did you get there? How did you prompt GPT to get your outputs                                                                |
| 3:10-3:20   | Discussion of digital-first assessment and AI in test development                  | What did you find most interesting? How do you think you will incorporate digital-first test development in your assessment development in the future? |
| Wrap-up     | Thank you's and putting our resources in a shared place                            |                                                                                                                                                        |


## Examples

### Bioluminescence

```
You are a biology expert. Write a passage about bioluminescence that meets four criteria:

It is three paragraphs long
It contains examples of both plants and animals
It is written at a high school level


Write a multiple choice question vocabulary question based about the meaning of bioluminescence using plain language

Example:
What is bacteria?

<<<<<<<<<<<<<<<<<<<<<<<<<<

Possible bad answer:
Bacteria are microbes with a cell structure simpler than that of many other organisms

<<<<<<<<<<<<<<<<<<<<<<<<<<

Possible good answer:
Very small living things, or “bugs,” that can be helpful (they help to digest food) or can cause illness (strep throat, for example).
```

### Value of college education

#### Chain of thought (kinda)

##### Thought 1


```
You are a language assessment expert. Write an argumentative writing prompt. It will meet the criteria below:

- Be about the value of a college education
- Be at the undergraduate level
- Be answerable in 15 minutes
- Be about two sentences long
```

##### Thought 2

```
Make a rubric for scoring the responses. The rubric will have a 5-point scale. The rubric will measure the following within each point

- Organization
- Argumentation
- Vocabulary use
- Grammar
```

##### Thought 3

```
Don't enumerate within points
```

##### Thought 4

```
Don't separate the four categories
```

##### Thought 5

```
Turn it into a table
```

##### Thought 6

```
Combine the four categories
```
