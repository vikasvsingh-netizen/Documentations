1) What is Agentic AI?
Ans : 
The AI does not only answer your questions , it does your task.
eg : 
Human:
"Authentication module implement karo"
AI Agent:
1. Project samjhta hai
2. Existing code dekhta hai
3. Architecture analyze karta hai
4. Plan banata hai
5. Files modify karta hai
6. Tests likhta hai
7. Errors fix karta hai
8. Review suggest karta hai

Difference:
Normal AI = Answer generator
Agentic AI = Goal complete karne wala system

2) Agentic AI me "Skill" kya hoti hai?
Ans : 
Ek software engineer ke paas skills hoti hain:
       React development,Database design,API security,Testing,Debugging,Code review
AI agent ke liye bhi same concept hai.
Skill = AI agent ko diya gaya reusable capability package
Ek skill batati hai:
"Agar ye type ka kaam aaye, toh kaise sochna hai, kya steps follow karne hain, kaunsi knowledge use karni hai."

Without skill:
AI sirf code likh sakta hai.

With skill:
AI engineer jaisa behave karta hai.

3)Real-world software example
ans : 
skills/

 ├── backend-development
 ├── security-review
 ├── database-design
 ├── testing
 └── deployment

 Human say : you want checkout feature
 agent understands your requirement and understand which skills are required and use those skills and activate those skills
 Checkout Feature
        |
        |
        +--> Backend Skill
        |
        +--> Database Skill
        |
        +--> Security Skill
        |
        +--> Testing Skill
  
4) AI coding agents ko Skills ki zarurat kyun hai?
Ans : 
AI ko nahi pata:
  company coding style
  architecture rules
  security expectations
  testing standards
  deployment process

so you must provide it how you want your project to be :
eg:
Follow Netflix backend standards
Follow security rules
Follow monitoring practices
Follow architecture pattern

5. Skill vs Prompt
Ans:
Prompt = ek request
it's temporary

Skill = reusable knowledge + process
eg:
Authentication Skill
Rules:
  - Always use JWT
  - Password bcrypt se hash karo
  - Rate limiting add karo
  - Unit tests mandatory
  - OWASP rules follow karo

Difference :
| Prompt           | Skill                           |
| ---------------- | ------------------------------- |
| One-time request | Reusable capability             |
| User deta hai    | Agent ke paas stored hoti hai   |
| Task batata hai  | Task karne ka method batata hai |
| Short            | Detailed                        |

6. Skill vs Instruction
Ans :
Instruction: Always write clean code
Skill : "Kaise karna hai"
  eg : 
    Clean Code Skill:
      - Function < 20 lines
      - Single responsibility
      - Meaningful names
      - No duplicate logic
      
Instruction: What 
Skill : How

7. Skill vs System Prompt
Ans : 
System Prompt : AI ka highest-level behaviour.
Ye AI ki personality/role define karta hai.

Skill : Specific expertise.
eg : Database optimization skill

8. Skill vs Rules
Ans :
Rules : Fixed constraints.
Rules = boundaries
eg : 
    Never commit secrets
    Always use TypeScript
    No console.log in production

Skill : Capability
eg : 
Security Skill
  Detect:
  - SQL injection
  - XSS
  - auth issues
  - secrets leakage

Difference:
Rule:"Don't do X"
Skill: "Do X correctly"

9. Skill vs Memory
Memory : AI ko previous information yaad rehna.
eg :
  Project uses PostgreSQL
  Team prefers REST APIs
  Developer likes functional style

Skill: Ability
eg : PostgreSQL optimization skill

eg : 
Memory : "Company ka tech stack kya hai?"
Skill : "Mujhe database optimize karna aata hai."

10. Skill vs Context
Ans :
Context : Current information available to AI.
eg : 
you give prompt : Fix login bug 
in context : 
  loginController.js
  auth.service.js
  database schema
  error logs
comes

Skill : AI ka method.
  eg : 
  Debugging Skill:
    1. Reproduce issue
    2. Check logs
    3. Trace execution
    4. Write fix
    5. Add regression test
    
11. Skill vs Tools
Ans : 
Tool : AI ka external action.
Examples: File editor , Terminal , Git , Browser, Database

Skill: Tool ko kaise use karna hai.
eg :
Tool : Terminal
Skill : 
      Deployment Skill
      
      Use terminal:
      npm build
      docker build
      deploy
      verify logs

12. Skill vs Agent
ans: 
Skill : Capability eg : Coding Skills
Agent  :  Decision Maker eg : Engineer

13.  Skill vs Workflow
Ans : 
Workflow: Fixed sequence.
eg : 
  Feature development workflow:
  
  1. Requirement
  2. Design
  3. Code
  4. Test
  5. Review
  6. Deploy

Skill : Ability inside workflow.
eg : step 3 code uses (  Backend skill , Security skill , Testing skill ) 

14. Skill vs Plugin / Extension
Plugin: IDE me extra functionality.
eg :
VS Code extension:
  GitHub Copilot
  ESLint
  Docker extension

Skill : AI reasoning capability.
eg :
plugin : GitHub Copilot extension
skill : Code Review Skill

Professional companies skills kaise use karte hain?
Ans : 
Large teams:
Example:
    Banking software:
    Skills:
      skills/
      security-engineering
      payment-processing
      database-design
      api-development
      testing
      cloud-deployment

Developer Says : "Create loan approval API"
agent : chooses relevant skills ( 
                  API skill
                  +
                  Security skill
                  +
                  Database skill
                  +
                  Testing skill
                  )

Common Mistakes
Mistake 1: Har baar long prompt likhna 
Bad : Create API. ,  Remember validation. , Remember security. ,Remember testing.
Better: Create skill: Enterprise API Development Skill

Mistake 2: Too many skills
Ai Can get confused 
Better : Focused skills.

Mistake 3: Not Updating Skills
Old skill: Use old framework version
Problem : Use old framework version

-------------------------------------------------------------------------------------------------------------------------------------------------------------
Topic 2: How AI IDE Actually Works Internally
-------------------------------------------------------------------------------------------------------------------------------------------------------------


