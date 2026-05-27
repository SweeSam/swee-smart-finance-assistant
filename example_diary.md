# Developer Diary — Smart Finance Assistant

## Student Name
Swee Sam Kok

---

# Week 8 — Project Planning and Idea Development

## Goal
Develop a project idea that meets all assignment requirements while remaining realistic and achievable within one notebook.

## AI Collaboration
I used ChatGPT to brainstorm possible project ideas such as:
- Budget Buddy
- Investment Tracker
- Savings Coach
- Currency Converter

After comparing complexity and assignment requirements, I selected the “Budget Buddy / Smart Finance Assistant” concept because it naturally supported:
- CSV processing
- AI chatbot integration
- custom tools
- Gradio UI
- testing

I also used AI to help interpret the assignment rubric and identify what markers were likely prioritising.

## What Worked
AI helped break down the assignment into manageable components instead of trying to build an overly advanced AI system. This made the project feel much more achievable.

## Challenges
Initially I was overwhelmed by the amount of template code and AI concepts such as RAG and agent tools.

## Improvements Made
I simplified the project scope and focused on:
- completeness
- documentation
- testing
- integration

rather than trying to build a highly complex finance platform.

---

# Week 9 — CSV Processing and Data Cleaning

## Goal
Create functions to load, clean, and process CSV transaction data reliably.

## AI Collaboration
I used both ChatGPT and Gemini to assist with:
- pandas CSV loading
- handling dollar signs in transaction amounts
- converting data types
- cleaning invalid rows
- debugging errors

AI-generated suggestions were reviewed and modified before implementation.

## What Worked
The AI tools successfully helped create:
- transaction validation logic
- amount cleaning functions
- missing value handling
- date conversion logic

The cleaning function was able to process realistic finance data with:
- dollar signs
- refunds
- missing values

## Challenges
I encountered several errors related to:
- undefined variables
- incorrect imports
- dataframe formatting

Some AI-generated code also required adjustments because it did not fully match my notebook structure.

## Improvements Made
I added:
- error handling
- column validation
- missing value replacement
- clearer business-focused output messages

This improved the reliability and professionalism of the finance assistant.

---

# Week 10 — Spending Analysis and Recommendations

## Goal
Develop spending analysis functions and generate useful financial recommendations for users.

## AI Collaboration
I used ChatGPT to help:
- calculate category spending totals
- compute percentages
- identify highest spending categories
- generate financial insights

Gemini was also used to debug logic issues and improve formatting.

## What Worked
The spending analysis successfully generated:
- category summaries
- spending percentages
- top spending categories
- recommendation messages

The recommendations section helped make the project feel more like a real finance assistant rather than simple spreadsheet analysis.

## Challenges
Some AI-generated recommendation logic was too generic and did not sound realistic for a finance application.

## Improvements Made
I refined the outputs to:
- sound more user-friendly
- provide actionable advice
- include estimated savings opportunities
- produce cleaner formatting

I also added refund detection and high-spending warnings.

---

# Week 11 — AI Chatbot and Gradio Interface

## Goal
Integrate AI chatbot functionality and create a user-friendly interface using Gradio.

## AI Collaboration
I used ChatGPT to:
- build the chatbot structure
- create a finance-focused AI personality
- connect chatbot inputs and outputs
- generate Gradio interface layouts

Gemini was mainly used for:
- debugging notebook errors
- fixing import issues
- resolving runtime problems

## What Worked
The chatbot was successfully integrated using the hands-on-ai package. The Gradio UI launched successfully and included:
- chatbot tab
- savings calculator
- interactive user inputs

The public Gradio link allowed the project to function like a real web application.

## Challenges
I encountered issues with:
- missing imports
- undefined functions
- Gradio configuration
- package installation confusion

Some runtime errors also occurred because cells were executed out of order.

## Improvements Made
I reorganised the notebook structure and ensured:
- imports were correctly loaded
- functions were defined before use
- Gradio components were connected correctly

This improved overall stability and usability.

---

# Week 12 — Testing, Integration, and Final Improvements

## Goal
Test the complete Smart Finance Assistant and prepare the final submission.

## AI Collaboration
I used ChatGPT to generate:
- integration tests
- error handling tests
- assert statements
- workflow validation logic

AI was also used to improve:
- README structure
- developer diary organisation
- final project polish

## What Worked
The final system successfully supported:
- CSV loading and cleaning
- spending analysis
- financial recommendations
- chatbot responses
- savings calculations
- Gradio UI interaction

Testing confirmed that major functions worked correctly under different scenarios.

## Challenges
The biggest challenge was integrating all project sections into one complete workflow while ensuring the notebook still ran correctly from top to bottom.

## Improvements Made
I:
- removed placeholder code
- cleaned notebook formatting
- added testing coverage
- improved documentation
- verified all cells executed correctly after restarting runtime

This significantly improved the professionalism and completeness of the final submission.

---

# Final Reflection 

This project helped me understand how AI tools can support software development when used critically and collaboratively. Instead of relying on AI to fully complete the project, I used ChatGPT and Gemini as development assistants to:
- generate ideas
- improve structure
- suggest testing strategies
- refine outputs

I learned the importance of:
- testing edge cases
- improving readability
- integrating multiple components into a complete application

The final Smart Finance Assistant demonstrates both technical implementation skills and the ability to collaborate effectively with AI tools in a business programming environment.

# Additional Reflection
During the final stages of submission, I encountered a major issue where my notebook repeatedly switched into raw code mode after saving. This caused formatting and execution problems and took approximately 1–2 hours to troubleshoot and resolve.

I used both ChatGPT and Gemini to help diagnose the issue, identify possible causes, and recover the notebook formatting without losing project progress. This experience taught me the importance of creating backup versions, committing work regularly to GitHub, and testing notebook execution before submission.

I also used AI tools to help polish and improve the wording of this developer diary based on my own notes and development experiences. The final diary reflects my actual workflow, debugging process, and learning throughout the project.
