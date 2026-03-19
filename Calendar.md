<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Automate Your Calendar with AI

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-agent-nocode)

**Author:** Marielle Lois Bahuyo  
**Email:** mariellelois9@gmail.com

---

---

## Introducing Today's Project!

In this project, I will demonstrate AI Workflow automation. I'm doing this project to learn how to use n8n to create automated workflows for scheduling events in my Google Calendar.

### Key tools and concepts

The key tools I used include n8n and AI-agents. Key concepts I learnt include dynamic expression and workflows. 

### Challenges and wins

This project took me approximately 50mins The most challenging part was getting the AI to book meeting

### Why I did this project

I did this project today to learn how to use an n8n Another skill I want to learn is openclaw or Langflow

---

## Exploring n8n

In this step, I will sign up to n8n ans explore the workspace because i will using this to create an n8n AI workflow

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_c9d8f7a2)

---

## Starting an AI Workflow

In this step, I will create a new workflow in n8n, add a chat trigger to the workflow and to test the chat trigger because want to test this workflow by triggering in the chat


![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_a4b3c2d1)

### Understanding workflows

A workflow is set of steps that complete the task. A workflow becomes an AI workflow when it uses AI to automate tasks or decisions.

### Configuring workflow triggers

To set up a workflow, I first configured a workflow My trigger is a trigger for chat messages. Other options include on manual trigger

---

## Integrating ChatGPT

In this step, I will Add an AI Agent node to my workflow because it can connect an OpenAI Chat Model.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_fmtkjyrg)

### Connecting AI agents

I connected my trigger with an AI agent node. AI Agents are sub-process which rely on AI. But, in this project, I am building an AI workflow

### Key components of an AI workflow

An AI workflow can be broken into three key components, which are Chat Model, Memory, Tool.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_o5p6q7r8)

### Choosing the AI model

My workflow's chat model uses an gpt-4o-mini.  I connected with OpenAI by using free credits.

---

## Integrating Google Calendar

In this step, I will add a connection to Google Calendar because i'll set up an dynamic expressions for event scheduling.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_c9d8dfgv2)

### Understanding tools in AI workflows

In this workflow, the tool is a piece of code, or a piece of third party software because it needs this to interract with third party app's

### Security considerations for integrations

To connect with Google Calendar, I allowed n8n access to my Google Calendar viewing and editing. This is needed because workflow would not function.

---

## Configuring Dynamic Expressions

I updated the start and end times to read data from the AI because dynamic expression are required for this use case.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_897rg465e)

---

## Writing a System Message

In this step, I will write a system message. I also need to set the mode to expression mode.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_rfgdhn456)

### Understanding system messages

A system message is test that gets passed to your AI every message. I configured it to include times and timezone I set it to Expression mode because the times we pass wont always be same.

---

## Testing the Workflow

In this step, I will test my workflow by test my AI workflow with a chat message I expect it verifies the calendar event was created at the correct time.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_w3x4y5z6)

### Verifying the results

I tested my workflow by asking the AI chat to creat a booking at 4pm. I validated whether it was successful by checking the Google Calendar and saw it was created successfully.

---

## Changing My AI Agent's Personality

In this project extension, I will change how my assistant talks and books meetings and showcase more advanced prompt engineering skills because this is quite a generic sounding AI.

### Updating system messages

I updated the system message. Changes I made include asking the AI to be more upbeat and high energy.

### Observing agent behavior changes

When I tested my workflow again, I noticed it way much more detailed and more information rather than the first one.

### Adding constraints with system messages

You can also set up constraints with your system message! I did this by including constraints for booking times like primes numbers, odd days, etc. As a result it doesn't let me book on non-prime minutes and odd.

![Image](http://learn.nextwork.org/serene_gray_noble_ruru/uploads/ai-agent-nocode_fewargtr52)

---

---
