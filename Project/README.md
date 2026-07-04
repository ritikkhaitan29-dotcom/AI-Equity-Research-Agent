# Project Documentation

## Project Background

This project began with a simple question.

> Why does understanding a single company require opening so many different websites?

Whenever I came across an interesting stock, my research process looked almost identical.

I would start with Screener for financial ratios, move to the latest annual report to understand the business, read investor presentations for management commentary, check exchange filings for corporate announcements, browse recent news, review shareholding patterns, and often revisit the same information multiple times before I could form a basic understanding of the company.

The information was available.

The problem was that it was scattered.

More importantly, there was no structured process to ensure that every company was analysed consistently. Some aspects would receive significant attention while others could easily be overlooked depending on the questions being asked.

As a Chartered Accountant with an interest in long-term investing, I wanted to build a workflow that could organise this information into a repeatable research process.

The objective was never to automate investment decisions.

Instead, the goal was to automate the repetitive process of gathering, organising and evaluating publicly available information so that more time could be spent applying judgement rather than collecting data.

That idea eventually became the AI Equity Research Agent.

## Project Objectives

Before writing the first version of the prompt, I defined what I wanted the final solution to achieve.

The objective was not to build another chatbot that could answer questions about companies.

Instead, I wanted to create a structured research workflow that could consistently produce a comprehensive first-level understanding of any listed company using only publicly available information.

The solution needed to satisfy a few non-negotiable requirements.

### 1. Bring Information Together

Instead of switching between multiple websites, reports and filings, I wanted a single report that consolidated the information most relevant for fundamental analysis.

### 2. Follow a Fixed Research Framework

Every company should be analysed using the same sequence of research regardless of the prompt. This reduces inconsistency and ensures that important aspects of the business are not overlooked.

### 3. Look Beyond Financial Statements

Financial performance is only one part of investment research. The workflow should also evaluate business quality, competitive advantages, governance, promoter behaviour, capital allocation, institutional ownership, valuation, industry dynamics and key risks.

### 4. Prioritise Capital Preservation

The framework should not begin by searching for reasons to buy a company. It should first attempt to identify governance concerns, weak business economics and other factors that could lead to permanent capital loss.

### 5. Produce Actionable Research

The final output should be more than a collection of facts. It should connect observations, explain their investment implications and present them in a structured format that helps investors decide whether a company deserves deeper research.

These objectives became the foundation for every design decision made throughout the development of the project.

## Design Decisions

From the beginning, I wanted the workflow to produce consistent outputs regardless of how a company was prompted.

Rather than relying on open-ended conversations, every company follows the same structured research process. The objective was to improve consistency, reduce subjectivity and ensure that important aspects of a business were not overlooked.

Several design decisions were intentional.

### Structured Research Before Conclusions

The workflow first gathers and evaluates information before arriving at an investment view. This reduces the likelihood of forming conclusions based on incomplete evidence.

### Seven Fundamental Research Pillars

Rather than treating equity research as only financial statement analysis, I divided the evaluation into seven distinct pillars covering the business, governance, financial quality, management, valuation and market expectations. This ensures that no single aspect disproportionately influences the overall assessment.

### Governance as a High-Weight Factor

Financial performance can improve over time, but poor governance often causes permanent destruction of shareholder value. For that reason, governance is deliberately treated as one of the most influential factors within the framework.

### Evidence Before Opinions

The workflow attempts to distinguish observations from conclusions. Wherever possible, investment implications should be supported by publicly available evidence instead of management narratives or market sentiment.

### Technical Analysis as a Secondary Layer

Technical analysis is included to provide additional context for timing and risk management. It is intentionally kept separate from the fundamental scoring framework so that short-term price movements do not influence long-term business quality assessments.

Every design decision was made with one objective in mind: improving consistency without removing human judgement.

## Development Journey

This project was not built in a single weekend.

The first working version was relatively simple and focused mainly on collecting financial information. While the output appeared comprehensive, it often missed important qualitative aspects such as governance, capital allocation, promoter behaviour and competitive positioning.

Over the following months, I continued refining the workflow whenever I analysed a new company or came across new investment frameworks in books, annual reports and professional research.

Each iteration exposed a different weakness.

Sometimes the reports became excessively optimistic.

Sometimes important information was repeated across multiple sections.

Sometimes the output exceeded the response limits of the AI model.

Sometimes the scoring framework rewarded growth while overlooking governance concerns.

Each of these observations resulted in another round of refinement.

The project evolved through continuous testing, practical usage and incremental refinement rather than a single major redesign.
Even today, I consider the workflow to be an evolving framework rather than a finished product.
## Engineering Challenges

Although the final output appears straightforward, designing a consistent research workflow required solving several practical challenges.

### Maintaining Objectivity

Large language models often favour balanced or optimistic language. One of the biggest challenges was encouraging objective analysis while ensuring that governance concerns, weak economics and business risks received appropriate attention.

### Reducing Hallucinations

The workflow encourages the model to distinguish between verified information, assumptions and missing data. Where sufficient evidence is unavailable, the report is designed to acknowledge uncertainty instead of presenting unsupported conclusions.

### Managing Output Length

The framework needed to provide comprehensive analysis while remaining within practical response limits. This required carefully balancing analytical depth with report length.

### Eliminating Repetition

Many aspects of equity research naturally overlap. Considerable effort was spent restructuring the workflow so that each section contributed new information rather than repeating previous observations.

### Consistent Decision Making

Perhaps the most difficult challenge was designing a scoring framework that remained reasonably consistent across different industries without oversimplifying the investment process.

## Key Learnings

Building this project reinforced an important lesson.

The quality of an AI solution depends far less on the model itself than on the framework that guides it.

Throughout the development process, I realised that improving the output was rarely about writing longer prompts. Instead, the biggest improvements came from refining the research methodology, defining clearer objectives and introducing better constraints.

Another key learning was the importance of iteration.

Every company that I analysed exposed a different weakness in the workflow. Some highlighted missing information, others revealed repetitive sections, while some challenged the scoring framework itself. Rather than treating these as failures, I used them to refine the next version of the agent.

The project also reinforced my belief that AI should support human judgement rather than replace it.

The workflow is intentionally designed to automate repetitive research while leaving the final investment decision to the user.

## Skills Demonstrated

This project represents more than an AI-generated report. It demonstrates the ability to combine domain expertise, structured thinking and AI to solve a practical business problem.

### Finance & Investment Research

- Fundamental equity research
- Financial statement analysis
- Business and industry assessment
- Corporate governance evaluation
- Valuation and capital allocation analysis
- Investment risk assessment

### AI & Prompt Engineering

- Designing structured AI workflows
- Advanced prompt engineering
- Output standardisation and response constraints
- Iterative prompt refinement
- Building consistent AI-assisted research processes

### Product & Workflow Design

- Converting a manual research process into a repeatable AI workflow
- Designing structured decision-support frameworks
- Improving consistency across analyses
- Balancing analytical depth with usability

### Problem Solving

- Breaking complex business problems into structured workflows
- Applying AI to reduce repetitive work
- Continuously improving solutions through testing and iteration
- Combining finance knowledge with emerging technology

More importantly, this project reflects my approach to learning: identifying real problems, building practical solutions and refining them through continuous improvement.

## Future Direction

This repository represents the first project in a broader portfolio of AI applications for finance.

The objective is not to build AI tools for the sake of automation, but to develop practical workflows that improve productivity, reduce repetitive work and support better decision-making.

Projects currently planned include:

- AI Portfolio Analysis Agent
- AI Technical Analysis Assistant
- AI Annual Report Review Assistant
- AI Financial Modelling Copilot
- AI FP&A & Management Reporting Assistant
- Workflow automation using APIs and structured financial data

Alongside these projects, I plan to continue refining the underlying research methodology by improving the scoring framework, incorporating additional investment frameworks and enhancing the consistency of AI-generated outputs.

Each new project is intended to demonstrate another practical application of AI within finance.

## Closing Thoughts

When I started this project, my objective was simple: make my own equity research process more structured and less repetitive.

As the project evolved, it became something more than a personal productivity tool. It became a practical demonstration of how finance knowledge and AI can be combined to solve real business problems.

One of the biggest lessons I learned is that building effective AI solutions is not about writing longer prompts. It is about understanding the problem, designing a structured workflow and continuously improving it through testing and iteration.

As a Chartered Accountant, I don't see AI as a replacement for professional judgement. I see it as a tool that enables finance professionals to spend less time gathering information and more time analysing it.

This repository represents the beginning of that journey. My goal is to continue building practical AI solutions across investment research, FP&A, finance transformation and other areas where structured thinking and AI can create meaningful value.
