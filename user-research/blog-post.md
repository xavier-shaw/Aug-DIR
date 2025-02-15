User Research Blog: Augment Data-Intensive Reading
==================================================

Members: Yuwei Xiao, Ollie Pai, Michael Shi, Brian Soynar

[Read this in Medium](https://medium.com/@xshaw2002/user-research-blog-augment-data-intensive-reading-d3fd5546ad55) 

> **TL;DR**: Scientific papers are more than just words on a page — they are packed with data, figures, tables, and statistical analyses that researchers must interpret alongside the main text. Navigating these dense, data-rich papers requires more than traditional reading skills; it demands the ability to extract key insights, synthesize information across different formats, and assess the reliability of presented evidence. However, the challenge doesn’t end with the first reading. Researchers often need to revisit papers days, weeks, or even months later, only to struggle with recalling key insights, retracing their thought process, or relocating important sections. Without effective tools to capture and organize their evolving understanding, readers may find themselves repeating work, losing track of their reasoning, or missing crucial details.
> 
> Our project, Augment Data-Intensive Reading, seeks to address this challenge by exploring how researchers engage with data-heavy papers and identifying ways to improve their reading experience. Through user research, we found that researchers do not follow a single, linear approach to reading. Instead, their reading processes vary significantly, shaped by shifting intentions that influence how they engage with different parts of a paper. Understanding these intentions — and developing tools to help researchers navigate them — could lead to a more effective and seamless reading experience, not only in the moment but also when revisiting papers over time.

![Image Credit: https://www.wikihow.com/Remember-What-You-Read](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*FoM0pkEzg6ZFRFVu)

**Hypothesis: Reading is hard, as well as Communicate what you read**
---------------------------------------------------------------------

Jack, an undergraduate student, stared at his laptop, overwhelmed by a data-intensive research paper assigned for class. Complex formulas, algorithmic descriptions, and figures filled the pages, making it difficult to follow. Lacking deep expertise, he skimmed the abstract and conclusion, jumping between sections to piece together key insights. Each unfamiliar term sent him searching online, breaking his reading flow. Despite multiple passes, he struggled to fully grasp the paper and decided to ask his mentor, Violet, for guidance next week.

Violet, a PhD student and experienced researcher, had read this paper months ago during her literature review. She had skimmed it first for relevance, then returned to specific sections for a deeper dive, annotating key points along the way. But now, when Jack asked about it, she found it hard to recall the details or retrace her exact thought process. Her notes helped, but without a clear way to track how she had engaged with the paper, reconstructing her insights was frustratingly slow.

![Image Credit: https://www.wikihow.com/Remember-What-You-Read](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*rDgEPh0VxvRUOmo9)

As they sat down to discuss, their differing reading strategies and the difficulty of recalling their thought processes over time made communication difficult. **This disconnect highlights a core challenge in data-intensive reading: not only is understanding a dense paper difficult, but revisiting it — recalling insights, retracing thought processes, and retrieving key information — is just as daunting.**

**User Research: How Do People Read Scientific Papers?**
--------------------------------------------------------

Motivated by our hypothesis scenario, we conducted user research to explore the following questions:

1.  How do readers currently approach reading scientific papers?
2.  What are their pain points and struggles in the reading process?
3.  How do readers interact with data within the paper while reading?

Since many reading challenges, subtle behaviors, and cognitive processes occur unconsciously, we chose the **think-aloud protocol** as our primary method. This approach allowed us to observe the natural reading flow and uncover the underlying rationale behind how readers engage with academic papers. However, to gain a more comprehensive understanding — including past reading behaviors and unspoken thoughts during the think-aloud session — we supplemented the study with **pre-study and post-study interviews**.

Given our focus on digital reading experiences, we conducted the study in a digital environment. This setup enabled us to observe how users interact with papers through a digital interface, providing valuable insights into designing a more intuitive reading tool.

**Study Structure**

Our mixed-method study consisted of three main components:

1. **Pre-Study Interview**

We conducted a structured interview to understand participants’ backgrounds, reading habits, and the tools they currently use or wish existed to support their reading process.

2. **Think-Aloud Study**

Participants were asked to read a data-intensive paper for approximately 10–15 minutes while verbalizing their thoughts, questions, and reactions. Throughout the session, we encouraged them to articulate their reasoning and any difficulties they encountered. After reading, they answered a set of questions related to the paper’s content:

*   What are the key contributions of this paper?
*   How do the authors accomplish these contributions?
*   In what ways do these contributions improve upon prior work?

This phase provided first-hand insights into how readers engage with and interpret data in research papers.

3. **Post-Study Interview**

Using a semi-structured interview format, we asked participants to reflect on their reading experience, discuss challenges they faced, and share their perspectives on how data was presented in the paper. This helped us capture additional insights that may not have surfaced during the think-aloud session.

Key findings: Reader Personas, Scenarios, and Process Map
---------------------------------------------------------

Our research revealed that readers engage with scientific papers in highly dynamic ways, shaped by their **expertise level, purpose, and reading depth**. We identified two primary reader personas and common scenarios they would run into:

*   **Violet — The Expert Researcher:** A PhD student in a data-intensive field, Violet conducts frequent literature reviews, balancing **depth and breadth** as she processes numerous papers. She skims some papers quickly for relevance but deep-dives into others, often struggling to **retrieve context, cross-reference materials, and manage large volumes of information efficiently**.

![Persona 1: Violet](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*IOnmaRVf43cn9FlC)

*   **Jack — The Novice Learner:** An undergraduate student required to read research papers for his coursework, Jack prioritizes **high-level understanding** over deep technical details. He **jumps between sections, frequently searches for unfamiliar terms, and struggles with fragmented comprehension**, making it difficult to piece together key contributions.

![Persona Jack](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*fhVMe3FOsj27WQtH)

Additionally, the personas and scenarios we identified inspired us to **map out two common reading processes** that illustrate how readers navigate scientific papers.

**Skimming a Paper**

*   **Violet** may apply this process when she encounters a paper referenced in another work she is analyzing or when she comes across a new contribution she hasn’t heard of and wants to quickly assess its relevance to her research.
*   **Jack** may skim a paper because it has been assigned for class or because it is related to another assigned paper, prompting him to seek more background knowledge.

![Process Map 1: Skimming](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*HJVShVu_D5bivlFn)

**Deep-Diving into a Paper**

*   **Violet** needs to perform this process multiple times throughout a literature review, making efficiency a priority. She may start with a skim before returning to specific sections for a more detailed analysis.
*   **Jack** may engage in this process when preparing a **deep critique of a paper** or making a deliberate effort to expand his knowledge beyond the coursework.

![Process Map 2: Deep-Diving](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*QDhlNFW9q_7vP0Tu)

**Identifying Key Challenges in Data-Intensive Reading**
--------------------------------------------------------

From our user research findings, we identified four key challenges readers face when engaging with data-intensive papers:

1.  **Managing Information Overload:** Violet needs to process a high volume of papers efficiently but often loses time manually cross-referencing key concepts and prior work.
2.  **Navigating Complex Content:** Jack struggles with technical depth, frequently interrupting his reading flow to search for explanations.
3.  **Tracking Thought Processes:** Both readers find it difficult to **recall past insights** and retrace their reasoning, especially when revisiting papers later.
4.  **Balancing Intention Shifts:** Readers shift between quick scans and in-depth analysis, but without structured ways to manage this process, they risk missing critical details or losing track of their progress.

By identifying these challenges, we gain insight into how readers **navigate and adapt their reading strategies**, reinforcing the need for tools that help structure and retain knowledge more effectively.

Problem statement
-----------------

**Scientific reading is a dynamic process, shaped by shifting intentions** — whether to grasp high-level insights, analyze technical details, or verify findings. However, the complexity of these papers makes switching between these intentions **cognitively demanding and time-consuming**.

Without effective ways to **track their engagement**, readers struggle to retain insights, leading to **redundant effort and difficulty reconstructing their understanding later**. This not only impacts individual productivity but also makes communicating findings and revisiting past work inefficient.

Our project aims to bridge this gap by **identifying readers’ intentions and developing tools that help them track and structure their engagement**, ensuring that data-intensive reading becomes more **efficient, recallable, and structured** over time.

Storyboard
----------

To vividly illustrate the reading process and its challenges, we created a storyboard that shows how readers engage with data-intensive papers — and how our tool can assist them.

![captionless image](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*puqrFA0JLkgXI0Rf)![captionless image](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*EDOiFzKQtwy5cBC_)![captionless image](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*dvRLEbiDe0kwn0IC)![captionless image](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*1QS5cZb_QOabDsPk)![captionless image](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*TcQ5qKu2lZVtlWiu)

To Be Continue…
---------------

Reading research papers is challenging — not just in understanding the content, but in **organizing thoughts, retaining insights, and efficiently revisiting information.** By designing tools that help readers **track their engagement, surface key context, and streamline reading strategies**, we can make scientific reading **less overwhelming and more intuitive.**

Stay tuned for updates on our next steps in tackling this problem!
