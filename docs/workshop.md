# ChatGPT for Content and Item Generation

Antony J. Kunnan & Geoffrey T. LaFlair

<img src="logo.png" alt="logo" width="20%" height="20%">

## Goals
Reconceptualize test development 
- digital fist perspective
- leverage large language models

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

## Papers

- [Rating Short L2 Essays on the CEFR Scale with GPT-4](https://aclanthology.org/2023.bea-1.49.pdf)
- [Automated Evaluation of Written Discourse Coherence Using GPT-4](https://aclanthology.org/2023.bea-1.32.pdf)


# Aaron's group

# Reading
## Passage
### Prompt
```
You are an expert language test developer. Please write a 2-3 paragraph passage for a second-language English reading test. It should conform to the following:

- It should be in newspaper style
- It should be a news article about typhoons
- It should be written in very easy English, at a 3,000 frequency vocabulary level
```
### Output
```
Title: Typhoon Alert: Prepare for Severe Storms

(Place and Date) - Authorities have issued a warning about an approaching typhoon in the (region/country). It is important to be ready and stay safe during this strong storm. Typhoons are powerful storms that bring heavy rain, strong winds, and can be dangerous.

Typhoons, also called hurricanes or cyclones in other places, form over warm ocean waters. They can cause damage to buildings and roads, and they can be harmful to people. It is important to get prepared and take care of yourself.

To stay safe during a typhoon, make sure things outside your home, like plants and furniture, are secure. Have food that does not spoil, water to drink, flashlights, and a radio with batteries. Listen to the news and follow what the local government says about leaving or staying safe.

Remember, typhoons can be hard to predict, so be ready and stay safe.
```
## Questions
### Prompt
```
You are an expert language test developer. Write a multiple-choice comprehension question about what someone should do in case of a typhoon based upon the above output. It should conform to the following:

- The choices should be the same length
- Use plain language at the same level as the passage
- The wrong answers should be completely wrong
- The wrong answers should be related to the topic, but wrong!
```
### Output
```
What is the best way to stay safe during a typhoon?

A) Wear a raincoat and go outside to observe the storm
B) Open all windows and doors to let the wind pass through
C) Stay near tall trees for protection from strong winds
D) Secure loose objects and have emergency supplies ready

Correct answer: D) Secure loose objects and have emergency supplies ready
```
# Speaking
## Task
### Prompt 1
```
You are a language assessment expert. Write an interview speaking prompt. It will meet the criteria below:
- Generate five questions for a ice-cream store job interview
- The dialogue should last for five minutes
- The question should be in easy English
```
### Output 1
```
Interviewer: Good day! Thank you for coming in for this interview at our ice-cream store. Let's get started. Please introduce yourself and tell us a bit about your background.

Candidate: Hi, my name is [Candidate's Name]. I'm from [Candidate's Hometown], and I've always loved ice cream. I have some experience working in a cafe before.

Interviewer: Great to hear that! Ice cream is definitely a favorite for many people. Can you tell me, what do you enjoy most about ice cream, and why do you want to work at our store?

Candidate: Well, I think ice cream makes people happy, and I love seeing people smile when they enjoy their favorite flavor. I want to work here because I want to be a part of making people happy and trying out new flavors.

Interviewer: That's a wonderful perspective! Customer service is a big part of this job. Can you share an experience from your previous job where you had to deal with a difficult customer, and how did you handle it?

Candidate: Sure. Once, a customer at the cafe I worked at was upset because their coffee was too cold. I apologized, remade the coffee, and offered a discount on their next visit. They left happy, and I learned the importance of quick problem-solving.

Interviewer: Handling situations like that can be challenging but rewarding. Speaking of challenges, can you describe a time when you had to work as part of a team to complete a task or project? What was your role, and how did you contribute?

Candidate: Of course. At my previous job, we had a rush during the lunch hour. I was in charge of taking orders, and my co-worker was making sandwiches. I made sure to keep the orders organized and communicated effectively with my co-worker to ensure all orders were prepared accurately and quickly.

Interviewer: Teamwork is crucial in our store too, especially during busy times. Now, let's talk about ice-cream flavors. Our store offers a wide variety of flavors. What is your favorite ice-cream flavor, and how would you recommend it to a customer?

Candidate: My favorite flavor is chocolate chip cookie dough. I would recommend it by saying, "Chocolate chip cookie dough is a classic flavor that combines the richness of chocolate with the sweetness of cookie dough pieces. It's like having a little dessert surprise in every bite."

Interviewer: That sounds delicious! Lastly, our store values cleanliness and hygiene. Can you explain how you would ensure that the serving area and equipment are always clean and safe for customers?

Candidate: To maintain cleanliness and hygiene, I would regularly wipe down the serving area and equipment, making sure there are no spills or drips. I'd also wash my hands frequently and use gloves when handling food. It's important to follow food safety guidelines to ensure our customers have a safe and enjoyable experience.

Interviewer: Thank you, [Candidate's Name], for sharing your experiences and thoughts with us. We appreciate your interest in joining our team. We'll be in touch soon with our decision. Have a great day!

Candidate: Thank you for considering me. Have a wonderful day too!
```
### Prompt 2
```
No! Just the questions!
```
### Output 2
```
Certainly! Here are five easy English questions for an ice-cream store job interview:

1. Can you introduce yourself and tell us a bit about your background?
2. What do you enjoy most about ice cream, and why do you want to work at our store?
3. Could you share an experience from your previous job where you had to deal with a difficult customer, and how did you handle it?
4. Can you describe a time when you had to work as part of a team to complete a task or project? What was your role, and how did you contribute?
5. What is your favorite ice-cream flavor, and how would you recommend it to a customer?
```
## Rubric
### Prompt 1
```
Make an analytical rubric for scoring the responses. The rubric will have a 0 to 4 point scale. The rubric will measure the following within each point

- Vocabulary & Grammar
- Pronunciation & Fluency
- Task achievement
```
### Output 1
```
Certainly! Here's an analytical rubric for scoring responses to the ice-cream store job interview questions on a 0 to 4 point scale, with specific criteria for each point:

**Vocabulary & Grammar:**

0 - Inadequate (Response includes numerous grammatical errors and limited vocabulary, making it difficult to understand.)

1 - Limited (Response contains several grammatical errors and limited vocabulary, affecting clarity.)

2 - Adequate (Response includes some grammatical errors and basic vocabulary, but it is generally understandable.)

3 - Good (Response demonstrates good grammar and vocabulary usage, with only minor errors that do not hinder comprehension.)

4 - Excellent (Response showcases impeccable grammar and a rich vocabulary, enhancing clarity and effectiveness.)

**Pronunciation & Fluency:**

0 - Incomprehensible (Response is difficult to understand due to severe pronunciation issues, and there is no fluency.)

1 - Poor (Pronunciation is unclear, and there is no fluency; response is disjointed.)

2 - Fair (Pronunciation is somewhat clear, with occasional fluency, but still challenging to follow.)

3 - Good (Pronunciation is clear, and there is consistent fluency, though some minor stumbling may occur.)

4 - Excellent (Pronunciation is excellent, and the response flows fluently with no issues.)

**Task Achievement:**

0 - Non-responsive (The response does not address the question and is completely unrelated to the topic.)

1 - Insufficient (The response is partially related to the question but lacks specific details or relevant information.)

2 - Basic (The response is related to the question and provides some relevant details, but it may be vague or incomplete.)

3 - Proficient (The response directly addresses the question with relevant and specific information.)

4 - Exceptional (The response is exceptionally detailed, directly addressing the question with specific and insightful information.)

Each question response should be assessed based on these three criteria, and the total score for each question can be calculated by adding the scores from each category (Vocabulary & Grammar, Pronunciation & Fluency, Task Achievement). The maximum possible score for each question is 12 points (4 points in each category).
```
### Prompt 2
```
Can you put that in a table please
```
### Output 2
Certainly! Here's the rubric for scoring responses in a table format:

| Criteria                  | 0          | 1         | 2           | 3          | 4          |
|---------------------------|------------|-----------|-------------|------------|------------|
| **Vocabulary & Grammar**  | Inadequate | Limited   | Adequate    | Good       | Excellent  |
| **Pronunciation & Fluency**| Incomprehensible | Poor | Fair    | Good       | Excellent  |
| **Task Achievement**      | Non-responsive | Insufficient | Basic | Proficient | Exceptional |

To evaluate a candidate's response, you would assign a score of 0 to 4 in each category (Vocabulary & Grammar, Pronunciation & Fluency, Task Achievement) for each question, and then sum up these scores to get the total score for that question.
### Prompt 3
```
No! All of it. Make the scores in the rows and criteria in the columns.
```
### Output 3
I apologize for the confusion. Here's the rubric with scores in the rows and criteria in the columns:

| Score                     | Vocabulary & Grammar | Pronunciation & Fluency | Task Achievement |
|---------------------------|----------------------|-------------------------|------------------|
| 0                         | Inadequate           | Incomprehensible        | Non-responsive    |
| 1                         | Limited              | Poor                    | Insufficient     |
| 2                         | Adequate             | Fair                    | Basic            |
| 3                         | Good                 | Good                    | Proficient       |
| 4                         | Excellent            | Excellent               | Exceptional      |

To evaluate a candidate's response, you would assign a score in each category (Vocabulary & Grammar, Pronunciation & Fluency, Task Achievement) for each question, using the scale from 0 to 4.
### Prompt 4
```
No, put the following descriptors in the table:

Vocabulary & Grammar:

0 - Inadequate (Response includes numerous grammatical errors and limited vocabulary, making it difficult to understand.)

1 - Limited (Response contains several grammatical errors and limited vocabulary, affecting clarity.)

2 - Adequate (Response includes some grammatical errors and basic vocabulary, but it is generally understandable.)

3 - Good (Response demonstrates good grammar and vocabulary usage, with only minor errors that do not hinder comprehension.)

4 - Excellent (Response showcases impeccable grammar and a rich vocabulary, enhancing clarity and effectiveness.)

Pronunciation & Fluency:

0 - Incomprehensible (Response is difficult to understand due to severe pronunciation issues, and there is no fluency.)

1 - Poor (Pronunciation is unclear, and there is no fluency; response is disjointed.)

2 - Fair (Pronunciation is somewhat clear, with occasional fluency, but still challenging to follow.)

3 - Good (Pronunciation is clear, and there is consistent fluency, though some minor stumbling may occur.)

4 - Excellent (Pronunciation is excellent, and the response flows fluently with no issues.)

Task Achievement:

0 - Non-responsive (The response does not address the question and is completely unrelated to the topic.)

1 - Insufficient (The response is partially related to the question but lacks specific details or relevant information.)

2 - Basic (The response is related to the question and provides some relevant details, but it may be vague or incomplete.)

3 - Proficient (The response directly addresses the question with relevant and specific information.)

4 - Exceptional (The response is exceptionally detailed, directly addressing the question with specific and insightful information.)
```
### Output 4
I apologize for the misunderstanding earlier. Here's the rubric with the descriptors included in the table:

| Criteria                  | 0 - Inadequate (Response includes numerous grammatical errors and limited vocabulary, making it difficult to understand.) | 1 - Limited (Response contains several grammatical errors and limited vocabulary, affecting clarity.) | 2 - Adequate (Response includes some grammatical errors and basic vocabulary, but it is generally understandable.) | 3 - Good (Response demonstrates good grammar and vocabulary usage, with only minor errors that do not hinder comprehension.) | 4 - Excellent (Response showcases impeccable grammar and a rich vocabulary, enhancing clarity and effectiveness.) |
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| **Vocabulary & Grammar**  |                                                                                                                             |                                                                                                      |                                                                                                                          |                                                                                                                        |                                                                                                                        |
| **Pronunciation & Fluency**|                                                                                                                             |                                                                                                      |                                                                                                                          |                                                                                                                        |                                                                                                                        |
| **Task Achievement**      |                                                                                                                             |                                                                                                      |                                                                                                                          |                                                                                                                        |                                                                                                                        |

To evaluate a candidate's response, assign a score in each category (Vocabulary & Grammar, Pronunciation & Fluency, Task Achievement) for each question using the descriptors provided in the table.
### Prompt 5
```
What are you doing??? Read your own output. Take the following and put it into a table with the scores on the rows, the criteria in the columns, and the descriptors in the cells!
```
### Output 5
I apologize for the previous confusion. Here is the rubric in the format you requested:

| Score | Vocabulary & Grammar                                       | Pronunciation & Fluency                                      | Task Achievement                                         |
|-------|-----------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------|
| 0     | Inadequate (Response includes numerous grammatical errors and limited vocabulary, making it difficult to understand.) | Incomprehensible (Response is difficult to understand due to severe pronunciation issues, and there is no fluency.) | Non-responsive (The response does not address the question and is completely unrelated to the topic.) |
| 1     | Limited (Response contains several grammatical errors and limited vocabulary, affecting clarity.)                     | Poor (Pronunciation is unclear, and there is no fluency; response is disjointed.)                                      | Insufficient (The response is partially related to the question but lacks specific details or relevant information.) |
| 2     | Adequate (Response includes some grammatical errors and basic vocabulary, but it is generally understandable.)           | Fair (Pronunciation is somewhat clear, with occasional fluency, but still challenging to follow.)                       | Basic (The response is related to the question and provides some relevant details, but it may be vague or incomplete.) |
| 3     | Good (Response demonstrates good grammar and vocabulary usage, with only minor errors that do not hinder comprehension.)  | Good (Pronunciation is clear, and there is consistent fluency, though some minor stumbling may occur.)                   | Proficient (The response directly addresses the question with relevant and specific information.) |
| 4     | Excellent (Response showcases impeccable grammar and a rich vocabulary, enhancing clarity and effectiveness.)           | Excellent (Pronunciation is excellent, and the response flows fluently with no issues.)                               | Exceptional (The response is exceptionally detailed, directly addressing the question with specific and insightful information.) |

