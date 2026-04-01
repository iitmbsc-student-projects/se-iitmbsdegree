---
nav_exclude: true
---

# AI Agent for Academic Guidance

The primary way in which learners engage with content in the **IITM BS degree program** is through the **SEEK portal**. This portal includes:  
- Learning videos  
- Assignments  
- Resources  
- Practice and graded assignments  
- Programming quizzes  

The SEEK portal serves as a **learning environment**, enabling students to **learn at their own pace** and schedule.  

## Project Overview  

With the rapid advancement of **Generative AI (GenAI) technologies**, there are promising opportunities to integrate AI into learning environments. The goal of this project is to develop an **AI agent** that enhances the learning experience for students enrolled in the IITM BS program.  

### Role of the AI Agent  

The agent will function as a **virtual guide**, assisting students in:  
- Navigating course material  
- Improving study habits  
- Adhering to **academic integrity principles**  

### Key Guidelines  
- The agent **should not provide direct answers** to assignments or quizzes.  
- Instead, it should **nudge students** toward better learning strategies and suggest helpful resources.  
- Course-specific guidance should be **dynamic**, reflecting available assignments and materials.  
- The agent should direct students to **credible references, official materials, and discussions** to address queries.  

## Technical Constraints  

### Standard Conversational Features  
The agent should include core functionalities of modern conversational AI, such as:  
- **Conversation threading** to maintain context across interactions  
- **Artifact storage** for key interactions and recommendations  
- **Rate limits and defined context window** to optimize performance  

### Retrieval-Augmented Generation (RAG) Architecture  
- The agent should use a **pre-indexed knowledge base** for handling common queries.  
- This **minimizes** unnecessary calls to the Language Model (LLM) for frequently asked questions.  

### Academic Integrity  
- The agent must strictly **adhere to academic ethics**.  
- It should **avoid** providing specific solutions for assessments.  
- Instead, it should focus on **general learning strategies and guidance**.  

## Additional Considerations  
The examples provided are just to give an idea of possible features. You are encouraged to explore additional **innovative ideas** to improve the AI agent's capabilities.  
