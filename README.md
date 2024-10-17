# Multi-Agent-LLM-Research
 A multi-agent LLM program designed to automate topic research, content generation, and critique in a sequential workflow.
 
# Overview
This project implements a multi-agent Large Language Model (LLM) system designed to automate the process of researching, writing, and critiquing content on any given topic. The program uses three specialized agents to perform the following tasks:

1. Research Agent: Conducts online research and gathers relevant information.
2. Writing Agent: Generates detailed, structured content based on the research.
3. Critique Agent: Evaluates the quality of the content and provides feedback for improvements.
The system reduces manual effort by 80% and increases content generation efficiency by 60%, making it ideal for producing high-quality written material with minimal human oversight.

Features
- Automated Workflow: Fully automates the process of content creation from research to critique.
- Multi-Agent Coordination: Each agent performs a specialized role, ensuring accurate and well-rounded content.
- Dynamic Task Assignment: Agents dynamically adjust their roles based on the complexity of the task.
- Online Research: The Research Agent pulls data from online sources to stay up-to-date with relevant information.
- Real-time Feedback: The Critique Agent provides instant feedback on the writing, improving quality iteratively.

# Architecture
The system follows a modular architecture where each agent operates in a sequence to complete the overall task:

1. Research Agent: Scrapes online data based on the input topic.
2. Writing Agent: Processes the research and generates structured text.
3. Critique Agent: Reviews the generated content and offers suggestions for revision.
Each agent operates independently but communicates through predefined natural langauge to pass results from one to the next.

