# Update your problem statement.

We define cognitive goals as the specific mental objectives that readers adopt to extract, interpret, and synthesize information. The dense structure of scientific papers necessitates that readers manage multiple cognitive goals. Many encounter challenges in recalling key details or bridging knowledge gaps between these goals across multiple readings.

This revised problem statement captures the idea that we observe a problem that involves changing cognitive goals over multiple readings. The following are not part of problem statement, but cognitive goals include:

- Adjusting one’s depth of reading
- Focusing on specific sections
- Shifting between statistical analysis and conceptual understanding

The above cognitive goals will be used as examples for new scenarios.

# Create a paper prototype. Take + upload pictures or a video of your paper prototype.

[Paper prototype](https://drive.google.com/file/d/1zxHY7KV0yLztl7lwCUNvVVLrkEAa6Q2f/view?usp=sharing)
[Figma prototype](https://www.figma.com/design/uzOCvWy2yBI3iTuMX57TO8/prototype?node-id=0-1&t=oNajR2pkllFLbl40-1)

# Summarize 1-3 takeaways from the feedback you received in class.

1. Add support to name nodes instead of just using the highlighted text so nodes are more distinguishable.
2. Clarify what is the purpose of adding reading intentions and what each highlight color represents.
3. Establish a justification for adding temporal links. Consider adding links based on the content’s position in the paper instead of the time it was highlighted.

# Articulate your design goals as you start to implement a high-fidelity prototype of your interactive system.

Design Goal 1: Design an interface to enable readers to visually capture and externalize a single cognitive goal, enabling them to track key pieces of information during the reading process.

- Importance: We observed users highlighting key sections of information that capture the main ideas of a paper as well as looking for “waypoints” that might be helpful to return to in the future. One user even mentioned that she printed out papers in order for her to better understand where she was in the paper spatially.
- Implementation: We will provide a multi-paned window that consists of (1) a PDF viewer where readers can highlight important pieces of text on the paper, and (2) a canvas containing a graph of nodes each representing a reader’s highlighted content. We will enable connection between the nodes through both temporal and context links.

Design Goal 2: Provide tools that help readers to bridge the gap between multiple cognitive goals by connecting insights and relationships between important parts of the paper.

- Importance: Our second round of user research revealed users reread papers and focus on different aspects of the paper upon each read. Some of these cognitive goals include adjusting one’s depth of reading, focusing on specific sections, and shifting between statistical analysis and conceptual understanding. Our user interviews also revealed that a primary struggle was recall from previous reads.
- Implementation: We will provide a tool to represent different cognitive goals through a different highlight color. These will be reflected on the canvas as a different type of node. Users will be able to select which cognitive goals to view (through a selection window) and to select which cognitive goal will be associated with new highlights.

Design Goal 3: Accommodate multiple levels of readers.

- Importance: Our initial personas involved the distinction between experts and non-experts. This design goal is of less priority given our time constraints with this project, but we would like our tool to be used by readers of both demographics.
- Implementation: Provide AI-generate summaries of a user’s highlighted text and incorporate sentiment-based context links between nodes on the graph. This will provide a more guided system for non-expert users.

# Provide a plan for implementation. Create a timeline. Suggestion: Work backwards from the March 4 pilot deadline.

- Feb 17-21: Brainstorm features and create/test paper prototype.
- Feb 22-25: Refine features and create working Figma prototype.
- Feb 26-27: Select tech stack, write tickets for implementation.
- Feb 28-Mar 4: Code out tickets.

# What did each member contribute to this phase of the project?

- All members: Brainstorm feature ideas.
- Michael: Sketch out paper prototype.
- Brian and Yuwei: Create working Figma prototype.
- Ollie: Complete Core Assignment writeup.

# Did you use a generative AI tool? If so, which and how?

AI was used to provide better flow to the prose of the problem statement.

# How much time did you spend on this assignment

- Group: 3 hours to brainstorm ideas and implement paper prototype.
- Michael: 2 hours to sketch out paper prototype.
- Brian and Yuwei: 3 hours to implement working Figma prototype.
- Ollie: 2 hours to revise problem statement, establish design goals, and complete Core Assignment writeup.