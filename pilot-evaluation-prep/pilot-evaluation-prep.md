# Core assignment: Pilot + Evaluation Prep [+4.5] Group

Phase: Evaluation

Due date: Friday, March 7  at 11:59pm PT

The goal of this stage of the project is to evaluate your high-fidelity prototype with potential users. 

Course learning objectives this assignment facilitates: (1) Create an interactive system grounded in user research, iterative prototyping, and evaluation; (2) Explore and express complex problems, design choices; and (3) Reflect on what you know, don’t know, and how to learn what you don’t know. 

Grading: This is a group assignment. All members of the group are expected to participate fully. Each group will receive one grade. / Every member will receive the same number of points.

What to submit: Add a .MD file in your Github repo with the responses to the following questions. Submit the github repo link to BruinLearn. Only one person needs to submit for the group.

## Pilot [+1]

1. [+0.5] Present the pilot user with a brief statement of the scenario and task. Ask the pilot user to complete the task. Note: You might feel (very) nervous that something will break. That is OK. It's ok for the pilot user to break things as they test out your system. Be prepared to restart/recover your system when things break. Note what happened step by step. Include 0.5-1p of notes on one pilot user. Additionally, summarize in a few sentences: What happened? Why? What changes do you need to make to your system before the next pilot?

Notes:

- We asked the user to link nodes, able to identify the link button and establish links 
  - Used links to group terms that are similar to each other together
  - Had initial confusion about the temporal links 
  - Asked if it was possible for user to use drawing as linking mechanism instead of selection
- Highlighted as they skimmed the paper
  - Lengths seem to vary - word, sentence, phrase etc.
  - Note: keyword + references might be challenging if highlighting full phrases/sentences
- No delete? User wanted to delete previously drawn links but still no feature to do this 

Summary:

At the time of our pilot, we did not have a functioning code prototype, hence we used a pseudo-system where we took elements from our Figma interactive prototype and the iPad’s note taking app. We used an iPad with a pdf opened on a note taking app and then let the user highlight areas. on a separate screen, we drew a node corresponding to that highlight. Once the user made several highlights, we allowed them to draw connections. During this process, the user had varied highlight lengths – varying from the word level, up to full sentences. This can cause a problem, especially for the definition and references extraction. For single words, this problem is trivial, however, when a user highlights phrases/sentences, how can we figure out which words in that sentence are deemed to be the most important and relevant? This prompted us to explore things such as keyword extraction and using LLMs to identify important words to focus on. The linking mechanism was also very intuitive as they figured out how to link multiple nodes without us telling them how to do it. However, they did bring up that our flow did not have the ability to revert linking, prompting us to implement a feature to delete links. 

2. [+0.5] Involve another pilot user outside of the course. Include 0.5-1p of notes on this second pilot user. Summarize in a few sentences: What happened? Why? What changes do you need to make to your system before the next pilot?

Notes:

- In ui/ux industry, does not read too many research papers
- Highlighted mostly words – some phrases – no diagrams were highlighted
- Used a single color the whole time
  - Did not prompt them to use multiple reads
  - Is our nav bar not as intuitive as we think?
- No delete was mentioned – have to be implemented. 
- Suggested a walkthrough that a user can go through before using the app for the first time

Summary:

We tested our pilot with a peer who works in UI/UX and got a lot of helpful insights to allow us to improve our product moving forward. Because this individual was someone from outside our class, they were not familiar with the multi-read approach when reading a paper, since in class we often discussed reading academic papers through multiple passes. This led to our user not utilizing the multi-color highlight feature, as they stuck with a single color the whole time. After the pilot, they mentioned that the nav bar should be more apparent as they did not clearly see the option to pick multiple colors. In addition, they mentioned that an introductory walkthrough would be helpful (i.e. taking the user through a “getting started” explanation before they use it for the first time.)

## Before conducting an evaluation [+3]

1. [+0.5] Articulate1-2 questions motivating the evaluation. In other words, what are the 1-2 things you want to prioritize learning through the evaluation?

How does our interface enable users to capture and externalize their cognitive goals while reading data-intensive scientific papers?

What is the efficacy of our interface in bridging different cognitive goals across multiple reading sessions? Further, do users use the multiple reads feature through its intended purpose, or do they use their own approach?

2. [+0.5] What metrics will you use to answer the above research questions? Why are these metrics appropriate? What are the benefits and drawbacks of using these metrics?

- Requirements: You are required to conduct a mixed-methods study where you collect qualitative and quantitative data. In your response to this question, describe what kind of data (e.g., open-ended survey, interview, time, clicks, etc.) will be useful for answering your motivating questions.

**Methods used.** This will be used to see the methods in which users engage with a tool. Qualitative.

- Describing a user’s approach to our highlight tool (for one specific cognitive goal/color). This will enable us to evaluate the externalization capabilities of our tool and whether the highlight/node tool provides a meaningful means of developing insights.
  - What they chose to highlight + why
  - What they took notes on + why
  - How did they make contextual connections + why
- Describe a user’s approach to the multiple reads feature.
  - Does the user use our tool as intended (multiple reads)?
  - If not, why? Was it unclear, or unnecessary?

**Categorization metrics.** This will help us determine what kinds of information was highlighted as well as identify trends in highlighted content across multiple reads These trends are both useful from an evaluation standpoint but could also be useful data for users themselves. Quantitative.

- Obtain data on what kinds of things people highlighted. Essentially, performing coding on a user’s highlights posthumously.
  - Categories: Charts, statistics, key ideas, definitions, methods
- Obtain data on what contextual links people made: Identify link types via a tuple of two highlight codes (based on the previous categories).
  - Would enable analysis of within-category links, cross-category links, within-single-read links, cross-read links, etc.

**Key insights.** This will allow us to determine if our interface enhances reading comprehension and insights from the user’s perspective. Qualitative.

- Ask the user about key insights they derived from their highlighted content/node graphs.
- Ask the user would they have acquired these insights without the highlight tool? Or were they enabled by the tool?

3. [+1] Specify a plan for recruiting participants.
How will you contact participants (e.g., mailing lists, in-person, etc)?
What are your inclusion/exclusion criteria for participants? 
Will you include participants you interviewed for user research? Why or why not?
Where will you perform the evaluation?
What data will you collect from participants? How will you inform them of this and obtain informed consent?

We will contact participants via direct email. Our inclusion/exclusion criteria will be the same as for when we conducted our user-research interviews—in fact, our primary means of finding participants will be to directly contact people who we interviewed during the user research phase. These participants, who are individuals who encounter research papers through their work or academia (with varying levels) are still the intended users of our tool. We will perform the evaluation online through Zoom, which will enable us to record the user’s screen as they use our tool. The data we collect from the participants will consist of our recording of their screen (just the window for our interface) as well as the follow up questions we will ask during the open-ended survey portion of the evaluation. We will inform participants of the data collected and obtain their consent when we request for their participation in the evaluation.

4. [+1] Write out a step-by-step protocol for conducting each user evaluation. Getting on the same page is important for more easily conducting studies and analyzing data across participants. Your protocol should include: (1) a script of what you will say to each participant; (2) what behaviors/responses you expect from participants and how that may change the flow of the study, if at all; and (3) how you will transition between phases of the study (e.g., from a task to an interview).

### Introduction

Script:

“Hi [Participant’s Name], thank you for joining us today. We’re conducting a study to understand how people engage with digital reading tools, particularly our highlight and multi-read features. This session will take about 45 minutes, and we’ll ask you to read a short text using our tool, interact with the features, and then answer some questions.

Before we begin, we want to assure you that there are no right or wrong ways to use the tool—we’re just interested in how you naturally interact with it. Your responses will remain confidential and will only be used for research purposes.

Do you have any questions before we begin?”

Expected Participant Behavior:

- Some participants may ask about how the tool works → If so, provide a high-level overview without leading them toward specific behaviors.
- Some may be hesitant or unsure about what is expected → Reiterate that there are no right or wrong answers and that we’re interested in their natural approach.

### Using the tool

Transition: “If you’re ready, let’s begin with the first task.”

Task Setup:

- Give the participant a research article (or an excerpt).
- Ask them to read as they normally would, using the highlight and note-taking features as they see fit.

Script:

“Please take your time reading this passage. As you go, feel free to use the highlight tool and take notes however you normally would. We encourage you to engage with the text in a way that helps you understand and remember it. After you finish reading, we’ll ask you a few questions about what you highlighted and why.”

Expected Participant Behavior:

- Some participants may ask for instructions on how to highlight or take notes → Briefly explain the mechanics without influencing their choices.
- Some may hesitate to highlight anything → Reassure them that there is no requirement to highlight, and they should do whatever feels natural.
- If a participant highlights extensively, selectively, or not at all, simply note this behavior without interfering.

Notes:

- How often participants highlight (extensively vs. selectively).
- What types of information they highlight (definitions, key ideas, statistics, etc.).
- Whether they take notes in addition to highlighting.
- Whether they make links between highlights.

### Open-ended survey & discussion

Transition: “Great, now that you’ve gone through the reading, let’s discuss your approach.”

Script:

“Now, I’d like to ask you a few questions about how you engaged with the text.”

Understanding Highlighting Behavior

- “Can you walk me through what you highlighted and why?”
- “Did you take notes on any of your highlights? If so, what kind?”
- “Did you find yourself connecting different highlights together? What was your reasoning?”

Evaluating Multi-Read Feature

- “Did you go back and re-read any part of the passage or your highlights?”
- “Did your reading goal change between different parts of the session?”
- “Did you make new highlights or connections based on previous highlights?”

“Thanks for sharing! Now, let’s talk about any insights you gained from this reading.”

“Before reviewing your highlights, can you summarize the most important takeaways from this reading?”

“Now, take a look at your highlights and notes. Do you notice any additional insights that you might not have remembered otherwise?”

- “Did your highlights help you recall more insights?”
- “Would you have made the same connections without the tool?”
- “Do you think using this tool helped deepen your understanding of the text?”

Expected Participant Behavior:

- Some participants may give detailed explanations of their thought process → Follow up with “Can you elaborate?” to uncover deeper insights.
- Some may struggle to articulate why they highlighted something → Ask, “Was this for future reference, understanding, or another reason?”
- If a participant mentions they didn’t use the multi-read feature, ask, “Did you feel like you needed it? What would make it more useful?”
- Some participants may recall new insights after reviewing their highlights → Ask, “What about this highlight triggered that memory?”
- Others may feel they would have retained the same information without the tool → Ask, “What could improve the tool’s usefulness?”

### Conclusion

“That concludes our session! Thank you so much for your time and valuable insights. Your feedback will help us improve the tool to better support users like you. If you have any follow-up thoughts, feel free to reach out.”

## For fun [+0.5]

[+0.5] Name your system!

*re:ad*

[+0.5] DEPTH: Design a logo for your system. Include a PNG in your repo. Add it to the README. 

![re:ad logo](./re-ad-logo.png)

Did you use a generative AI tool for this assignment? If so, which tool(s) and how?

We used ChatGPT to help format our script’s prose. In the prompt, we provided a specific structure and guideline for each section, the specific steps/actions to take, what questions to ask, etc. ChatGPT provided a smooth script according to this.

How much time did you spend on this assignment

- Group: 2 hours to discuss goals, metrics, evaluation protocol.
- Ollie and Brian: 2 additional hours to complete Core Assignment writeup.
- Yuwei and Michael: 2 additional hours of coding the pilot.
