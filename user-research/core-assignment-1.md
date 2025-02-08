# Core assignment: User research [+18]

> Group members: Brian Soynar, Michael Shi, Ollie Pai, Yuwei Xiao

## Before you get started with users [+4]

**Q1.** [+1] As a group, discuss any assumptions you have about your users or usage contexts. Consider aspects such as language, age, dis/ability, indoors/outdoors, alone vs. small group vs. family vs. large social gathering, etc. Write a summary of your discussion and a clear statement of your assumptions going into user research.


During our initial discussions, our group hypothesized that our solution will primarily target students and academics. However, more specifically, our core assumption is that our users will fit in one of two main use cases. Firstly, we have students that want to develop a good initial understanding of the paper. This involves students who need to read a paper for a class, a research lab, or even their own personal projects. This use case heavily involves individuals who do not have a lot of experience reading papers or the topic being discussed in general. The second use case that we hypothesized would use our solution are individuals who are more specialized and experts in the field of research. This use case involves academics who want a deeper dive and understanding of the paper – including its methodology and results. We hypothesize that these experts would want to know how a paper arrived at a result, how a chart was constructed, or even a deeper dive into the math and statistical tools used in the paper.

**Q2.** [+1] As a group, share any hunches you want to test or unknown/open-ended questions you want to answer through user research. Summarize your discussion, listing out 2-3 things you want to learn through user research.

Since we have contrasting use cases, we are curious how individuals in the two different categories are approaching reading academic papers in the first place. Figuring out how individuals approach a paper will be crucial in determining how we design our interface to help users augment their reading experience. This includes how often they read the same paper, any external tools they currently use to aid them in the process and reading linearly or nonlinearly. We will be doing this in two ways: firstly, we will ask the following questions in the pre-study interview: “How do you read a paper? Do you read it multiple times? Which section(s) do you focus on the first time, second time, etc. and why?” and “Have you used any tools or techniques to help you read papers? Are there any tools that you wish existed that you think would help you?”. Secondly, we will be doing a think-aloud study to see how they approach and interact with a paper we choose.

Furthermore, we are also curious what specific sections of a research paper really helps individuals understand the paper and what challenges they currently face. Depending on the use case, we hypothesize that different individuals will have varying responses to how they prioritize different sections of the paper and their own set of challenges. In terms of challenges faced, students in the first group might have challenges related to understanding the paper as a whole, whereas experts in the second group might have more localized challenges when it comes to understanding the smaller details and methodologies of the paper.

**Q3.** [+1] Based on your discussion above, pick a method/s. Write 1-3 sentences justifying your methodological choice. You can employ multiple methods or just one. Make sure your response answers: How are these methods going to help you understand the problem you are trying to address? How will each method allow you (or prevent you) from reaching users of interest?

From our discussion above, we decided that the best course of action for our study would be a hybrid of an interview and a think-aloud study.

The interview will allow us to ask closed questions about the user's background such as education level, research/work interests, as well as more open-ended questions about how they approach and their experience when it comes to reading academic papers.

On the other hand, the think-aloud study will allow us to see first-hand how different users interact with papers and identify common struggles between users when reading papers.

**Q4.** [+1] Write your user research protocol. Consider the following: Recruitment strategy (e.g., whom to contact, how to contact, how many) 

Since we have four group members, we aim to conduct our study on at least 10 people. We also aim to approach different interviewees with different backgrounds in terms of their education level and experience with research papers. We will be using our network to reach out to people to interview, and if we need more people, we will reach out to people in the general UCLA CS community.

Time and place for each user research session (e.g., “in the afternoons, in person, in a meeting room”)
We will be accommodating to the interviewees, so will provide both an in-person option, as well as an option to do it on Zoom, and we will also be accommodating depending on when the interviews are free.

Each member’s role and responsibilities (e.g., For interviews: interviewer, note-taker, discussant, etc.)
We will be holding 2-3 interviews each, and each person will act as both the interviewer and note-taker.

## Conducting user research [+5]

Write and submit ~0.5-1p of notes for each user research session OR initial analysis of survey results. Here are some rough guidelines for how many users you should reach:
- 10 users/groups of users for interviews
- 25 users/responses for surveys
- 5 users to conduct contextual inquiries that are at least 1 hour in duration
- some combination of the above (talk to instructor to make sure that you're reaching enough potential users)

See our notes under the `interview-notes` folder.

## After you get started with user research [+4]

**[+2] Synthesize your user research into:**

**1. [+1] Personas + Scenarios (at least one persona, one scenario)**

**Persona 1: Violet**

Violet is a PhD student in a data-intensive, technical field (think statistics, machine learning, and their applications). She regularly conducts literature review for both depth in her current focus as well as breadth to keep track of new contributions across her area of study, meaning she often reads multiple papers a day.

**Scenario 1:**

Violet is conducting literature review in a field related to her area of study, but not exactly the same. She is familiar with many of the common terms, but is unfamiliar with some of the formulas or models. As she potentially needs to read 20 or more papers within a week to complete her review, she needs to be able to quickly get up to speed and process information with papers she has only foundational-level knowledge in. To help, she reads on an iPad or a similar device that lets her highlight and make annotations on the paper so that she can cross-reference materials easier. With some papers, she merely skims them to understand their basic contributions, but for others she needs to dive more in depth. When skimming, she finds that she often misses info that would help understand contributions requiring a few passes through papers, and when diving deeper, she often has to manually parse referenced papers or check data analysis on her own. When diving deeper, she tends to read more linearly as she cares to be very thorough in those cases, but she wishes for a more efficient way to take in all this information without as much manual effort.

**Persona 2: Jack**

Jack is an undergrad student in a technical field who is required to read papers for several of his upper division classes. He has read papers intermittently in the past, and while he has some technical knowledge, he struggles to follow some papers which go into great technical depth. For the purpose of his classes, understanding them at a high level via their general contributions and results suffice.

**Scenario 2:**

Jack is reading a new assigned paper for his class. The paper is about some novel machine learning methods and goes into great depth in its mathematical and algorithmic foundations, as well as the data used in its experimentation. As a result, there are many complex formulas and a variety of diagrams comparing the novel model to existing baselines. Jack is familiar with some but not all the baselines, and while he has a foundational understanding of machine learning, he is unfamiliar with some of the more complex optimization techniques used in the paper. He skims most of the methodology and focuses most of his time on the results, discussions, and conclusion portion of the paper to get a sense of its contributions. As a result, he often jumps back and forth between sections of paper, reading in an erratic manner and constantly searching up terms and things he’s unfamiliar with. He wishes that he didn’t have to switch his focus from reading to searching as often as it makes it difficult to gather a clear understanding of papers.

**2. [+1] Process map or more in-depth task analysis (at least one)**

**Process map 1 (skimming):**

Violet may be checking this paper out because it’s referenced in a paper she’s doing a deep dive on, or it has a new contribution she’s never heard of, and wants to check if it is relevant to her research. Jack may be checking this paper out because it’s been assigned for class, or it was related to a paper he was assigned for class and he wants more background knowledge.

**Process map 2 (linear deep dive):**

Violet likely needs to do this several times over the course of a literature review and thus would like to do them as efficiently as possible. Jack may do this for a deep critique of a paper and an attempt to broaden his knowledge.

**3. [+1] Articulate a problem statement.**

A problem statement should illuminate the core of the issue you observe. Often, there is a contrastive tension between what users want to do and what their current tools require them to do. If you cannot articulate this yet, describe why you think you are not able to converge yet, what promising directions to follow up with additional user research and feedback might be, and what steps you think you should take next.
- Tip: Rely on your process map. What is it telling you about what users want to do vs. have to do?
- Double check: Does your storyboard communicate/highlight this core tension?

**Problem statement:**

People from diverse backgrounds approach research papers with varying, evolving intentions, shaping their engagement. Existing tools to support reading and comprehension are fragmented and serve specific purposes, forcing users to switch between them. This disrupts focus, makes tracking evolving intentions challenging, and hinders recalling relevant information.
[how to apply result/understanding from previous intention/stage to next intention/stage]

**4. [+1] Storyboard of how your proposed system could address the core problem. This is where you begin to imagine a prototype to address the core problem you identified.**

[TODO]

**5. DEPTH (optional, not required) [+1]:**

Map out a design space of existing tools (production or research) for supporting similar tasks x users x domains. Your design space should include at least five other comparable tools.

**Intentions:**
1. Skim for Overview – Quickly grasp the main idea and decide relevance.
2. Comprehend Key Concepts – Build a solid understanding of the central theories, methods, or results.
3. Retrieve Specific Information – Locate targeted details like data, equations, or results.
4. Critical Assess – Evaluate the paper’s validity, originality, and contribution.
5. Utilizing Knowledge – Use the information to solve problems, replicate methods, or inform research.
6. Synthesize Ideas – Connect the content to existing knowledge and generate new insights.

**Dimensions (Bloom’s taxonomy):**
- Knowledge Dimension (concrete -> abstract)
Factual, Conceptual, Procedural, Metacognitive
- Cognitive Processes Dimension (cognitive complexity)
Remember, Understand, Apply, Analyze, Evaluate, Create

**Tools:**
- SCIM: supports the skimming process by highlighting salient paper contents in order to direct a reader’s attention.
- Qlarify: recursively expandable abstracts, a novel interaction paradigm that dynamically expands abstracts by progressively incorporating additional information from the papers’ full text.
- ScholarPhi: bring definitions of technical terms and symbols to readers when and where they need them most
- CiteSee: a paper reading tool that leverages a user’s publishing, reading, and saving activities to provide personalized visual augmentations and context around citations.
- SciDaSynth: enables researchers to efficiently build structured knowledge bases from scientific literature at scale
- Synergi: ties together user input of relevant seed threads with citation graphs and LLMs, to expand and structure them, respectively. Synergi allows scholars to start with an entire threads-and-subthreads structure generated from papers relevant to their interests, and to iterate and customize on it as they wish.

[TODO: Add design spae figure]

## Reflection [+3]

**Q1.** [+1] Look back at your assumptions (in the “Before you get started with users” section). Has your user research contradicted or challenged any of these assumptions? If so, which ones? How?

Our user research did not raise any contradictions in regards to our primary hypothesis of evaluating and comparing the approaches of students and academics. A notable challenge that did arise out of our user research, however, was related to the importance of visualizations and charts—one of our secondary assumptions. We hypothesized that visualizations and charts would be amongst the most essential sections to a reader’s understanding of a paper, particularly during a first pass. Our user research contradicts this. Among readers of non-technical backgrounds, we observed that visualizations were seen as an inefficient means of knowledge propagation as they require significant self-diagnosis compared to a close reading of the results section, which synthesizes the most important takeaways from the visualization in a narrative format. Among readers of technical backgrounds, we observed the skipping of visualizations until they were referenced in the text itself. Only then would the reader return to the visualization for a closer inspection and confirmation of the finding. In other words, charts were not the preferred first point of contact when understanding technical or statistical information.

**Q2.** [+1] What does your user research tell you about what kinds of interactive systems/solutions are unlikely to be useful/successful? Why not? Any hypotheses about what features of an interactive system will be useful? Why?

From our user interviews, we conclude reading methods are primarily informed by a user’s background and intention. Separately, from our design space analysis, we conclude effective tools to augment specific reading intentions already exist. With these two points established, we have identified a gap in the field of paper reading augmentation tools that involves connecting different reading intentions. Our research suggests that a reader will often revisit papers they have previously read in order to focus on different aspects from their first read. To put it simply, a reader’s intentions change over time. As such, we hypothesize one feature that will be useful in our end system will be a log of reading intention over time that synthesizes the most important information for each intention. We envision this will assist in a reader’s recall as they switch from one reading intention to another.

**Q3.** [+1] What questions do you have about your users? What hunches or hypotheses do you have about promising solutions? What is one thing you can do to begin answering these questions?

Now that we have synthesized two personas, we are curious if further specifications can be made. Our personas, Violet and Jack, represent two ends of the spectrum, and can generally be thought of as representing experts and nonexperts respectively. However, we have a hunch that our user base contains finer granularity in regards to common personas. While our interviews provided us with insight into the paper reading process itself, we would like to develop more detailed personas. This is critical since our proposed idea involves the tracking of changes to user intention throughout the reading process, yet we lack data regarding possible reading intentions that exist. We plan to resolve this by conducting another round of user research through a survey. From this, we hope to obtain a larger sample size of paper readers to get a better sense of the varieties of backgrounds and reading intentions that we may focus on.

**Q5.** Did you use a generative AI tool for any part of this assignment? If so, which one and how?

We used ChatGPT in order to improve the wording and flow of our interview questions.

**Q6.** How much time did you spend on this assignment as a group? Individually?

As a group, we spent 2.5 hours through group time in class and design studio to coordinate our user research. We also had a 2 hour Zoom call following our interviews to discuss findings, define personas/scenarios/problem statement, and delegate work for the core assignment writeup.

The breakdown of individual work is as follows:

Brian: 2.5 hours for interviews, .5 hours to organize interview notes, 1.5 hours on assigned section of core assignment (“Before you get started with users”).

Michael: 3 hours for interviews, 1 hour to organize interview notes. 1.5 hours on assigned section of core assignment (Personas, Scenarios, Process Map).

Ollie: 3 hours for interviews, .5 hours to organize interview notes, 1.5 hours on assigned section of core assignment (“Reflection”, Conduct additional round of user research).

Yuwei: 2.5 hours for interviews, .5 hours to organize interview notes, .5 hours on assigned section of core assignment (Problem Statement, Design Space)

## Additional group depth exercises

Each member in the group who participates in the below will receive the depth points.

[+1] Conduct an additional round of user research with another method, involving at least 5 more users. Analyze the data.

- Use to get more data about personas + scenarios. Ask for background and common intentions/reasons for reading paper. Whats the most important info you are looking for.
- Also ask about tools they use (to help with design space)
Make it multiple choice + some open ended questions
- Example

[+1] Meet with a community partner + come up with a plan for continued engagement with them.

[+1] Depth: Interview 2 experts. Synthesize this new information.

[+1] Depth: Talk to a local LA startup about your project. I recommend 2 group members (max) in a meeting with an LA start up. Share the contact information for people you met with + notes you took during/after the meeting.

[+2] Complete IRB training + submit an IRB to cover your project. Every team member must do this. Talk to the instructor about this.

⬇️ Due Feb 14

## Communicate what you have learned [+2]

[+2] Draft blog post summarizing user research. Your blog post draft must include: - A description of methods and key findings - A clear problem statement describing the crux of the issue you identified through user research.

- Your storyboard - At least 1 figure that is not from your storyboard
- DEPTH (optional, not required) [+2]: Pick a model research paper with a formative study. Write your user research as a formative study section. In your submission, specify your model paper and why you chose it.