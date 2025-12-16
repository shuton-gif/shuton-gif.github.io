---
layout: essay
type: essay
title: "How to use AI"
date: 2025-12-8
published: true
labels:
  - Software Engineering
  - AI
  - Code ADT
---

## i. Introduction:

I believe that artificial intelligence is becoming one of the most powerful tools available for programmers today. Before I started using AI, when I did not understand something or ran into compile errors caused by syntax mistakes, I had to search through websites such as MDN or Stack Overflow to find possible answers. This process was often very tedious and time-consuming, especially when learning new libraries or frameworks. With AI, however, I can immediately receive feedback on what is wrong and gain knowledge about concepts that I have not yet encountered. Because of this, I see AI as especially powerful for finding solutions and fixing syntactic errors.

At the same time, I understand that AI generates responses based on majority patterns, which means the code it provides is not always optimized or ideal. For this reason, even after receiving a solution from AI, I always verify it by going to the official documentation and learning how the feature is intended to be used. Additionally, when I encounter deeper semantic or logic-based problems, I have learned that AI is often not the best solution, and that is when I rely on my own thinking and problem-solving skills.

During this course, I primarily used Claude as my main AI tool because it provides specific prompting guides that helped me practice prompt engineering. I believe this experience will be useful in real job environments in the future, especially when giving precise instructions as a senior developer. Since each person has a different way of understanding systems and structures, coding standards exist to help unify development. However, for more complex structures such as database design, interpretations can still vary. For example, some developers argue whether the primary key should be an ID or a name, which shows how subjective design choices can be.

In ICS 314, we mainly used Next.js and React Bootstrap, but we did not go deeply into React Hooks. During the first half of this year, I took a leave from school and completed a web development internship in Japan. At my internship, I was also required to use Next.js, but I used React Hooks extensively, including tools such as useReducer and useRef. Because of this background, using React Bootstrap in this course felt new to me, and I was surprised by how clean and simple it was to use for building user interfaces.

## ii. Personal Experience with AI:

### Experience WODs
For most Experience WODs, I did not rely on AI because the tasks repeated patterns from earlier assignments, and I wanted to reinforce my own understanding. After finishing some WODs, however, I experimented with AI to extend the code using reducers, VAOs, and DAOs. AI generated working solutions but often included unnecessary logic and magic numbers. This taught me that giving AI only a concept leads to messy results; defining strict structures produces cleaner, more relevant code.
### In-class Practice WODs
I rarely used AI during practice WODs except for resolving small syntactic deadlocks. Simple prompts like “Why is this line causing an error?” helped me keep moving. Looking back, I could have used AI more strategically to explore cleaner component structures or practice precise prompting under time pressure. While relying on my own problem-solving strengthened my skills, a balanced approach might have improved my architectural thinking as well.

### In-class WODs
I did not use AI during in-class WODs because the timed environment made it unrealistic. Opening AI, reading responses, and adapting them would take longer than writing the solution myself. I also viewed WODs as preparation for interview-style situations, where independent recall matters. Sometimes I reviewed syntax with AI before class, but during the actual WODs I relied solely on practice and familiarity with the material.
### Essays
I used AI mostly for grammar checks and reorganizing sentences for clarity. It helped me express ideas more professionally while keeping my own thoughts intact. The design-related essays especially made me reflect on balancing aesthetics with functionality, too many UI elements cause clutter, but too few reduce usability. AI helped refine my wording without replacing my personal insights about design principles.

### Final project
For the final project, I used AI to understand unfamiliar concepts rather than to generate code. Coming from a Japanese internship background, this was my first time working with a culturally diverse team and building something for IV&V. At first, I was unsure about the project’s purpose and whether my implementations aligned with the team's expectations. AI helped me clarify terminology and domain ideas so I could collaborate more confidently.

### Learning a concept / tutorial
I frequently used AI when learning new concepts because, in the early stages, it is easy to miss important details. Errors often reveal what you do not yet understand, and AI helped me fill those gaps quickly. Whether learning TypeScript features, React Hooks, or Next.js routing, AI provided alternative explanations that helped me build a more complete understanding.

### Answering a question in class
I did not use AI when answering questions in class. Effective communication first requires understanding what the other person sees or struggles with. During the final project, team discussions taught me that shared context is essential. What seems obvious to me may not be obvious to others. So I focused on mutual understanding rather than relying on AI-generated explanations.

### Asking a smart-question
Similar to answering questions, I did not use AI for crafting smart questions. A good question requires clearly stating the problem, describing the steps already attempted, and explaining your intention. Doing this myself helped me think more critically about my own process and allowed others to provide more accurate and useful guidance.

### Coding example
I used AI to gather example snippets, especially for unfamiliar use cases such as using React Hook "useEffect" for browser-based animation frames. Seeing examples helped me understand patterns I had not encountered yet. These examples were not copied directly but helped me understand alternative approaches.

### Explaining code
I used AI to clarify dense or deeply nested callback functions, especially when the logic became hard to read. AI’s explanations helped me understand the flow more clearly, allowing me to refactor the code into a more readable structure.

### Writing code
I did not use AI for graded course assignments, but I used it for personal experiments outside of class. These small projects let me explore patterns, test ideas, and practice prompts without affecting the integrity of my coursework.

### Documenting code
I did not use AI for documenting code. I preferred writing comments myself because documentation reflects how I understand the system. Writing it manually helped reinforce my thinking.

### Quality assurance
For quality assurance, I experimented with CodeRabbit, an AI reviewer. It provided useful feedback on potential edge cases and minor errors. I also used AI occasionally to understand ESLint rules, although I disagreed with the strict ban on nested ternaries. I believe small ternaries for color or severity mapping can improve readability rather than harm it.

### Other 
Outside of specific tasks, I often used AI to test my understanding. Sometimes it showed solutions or questions I had not encountered yet, helping me deepen my knowledge. AI served as a tool for exploration rather than a shortcut for assignments.

## iii. Impact on Learning and Understanding:
The incorporation of AI had a positive impact on my overall learning experience in ICS 314 and out. It exposed me to new possibilities in software engineering, such as alternative use cases, cleaner syntax patterns, and different design approaches that I might not have discovered on my own. I primarily used AI to confirm my ideas, especially when thinking about database structures such as one-to-one and one-to-many relationships or deciding when foreign keys should be used. These checks helped me better understand design choices rather than memorize rules.

AI also encouraged me to think more broadly about optimization and future scalability. For example, I asked questions about whether switching to languages like Go could improve performance, or how to patch potential vulnerabilities—such as those recently found in certain React packages. These conversations helped me see software engineering not only as writing code, but also as anticipating long-term reliability, security, and maintainability.

While AI occasionally provided oversimplified or overly generic answers, the process of verifying its responses strengthened my problem-solving skills. It pushed me to compare AI’s suggestions with official documentation, testing my own understanding along the way. Overall, AI enhanced my comprehension and encouraged deeper learning without replacing the need for critical thinking.

## iv. Practical Applications:
Outside of ICS 314, AI has played a meaningful role in several of my real-world projects, both academic and personal. During my web development internship in Japan, I frequently used AI to understand complex React patterns, verify database schemas, and explore alternatives for state management using tools like useReducer and useRef. Although I never relied on AI to write production code, it served as a reliable assistant for clarifying concepts quickly or comparing architectural choices before implementing them.

AI was also helpful in my personal software engineering projects, such as building automated trading tools, web scrapers using Playwright, and Unity game prototypes. In these projects, AI assisted by explaining APIs, suggesting performance optimizations, and helping me debug platform-specific issues. It was especially useful when I needed to understand foreign frameworks such as MQL5, yfinance behaviors, or the structure of Japanese financial data sources. In these situations, AI accelerated learning that would otherwise require extensive documentation reading.

At times, AI demonstrated limitations. Its suggestions occasionally included non-existent library functions, outdated syntax, or overly generic patterns. However, these failures pushed me to validate answers through official documentation. Overall, AI proved effective as a learning accelerator and architectural consultant, especially when addressing real-world software engineering challenges that extend beyond the classroom.

## v. Challenges and Opportunities:
Although I have not used AI to generate production-level code, my experiences in this course made me think about both the limitations and future possibilities of AI in software engineering. One major challenge is that AI still struggles to produce consistent, high-quality code without human guidance. The issue is not only unnecessary logic or magic numbers, but also the absence of what I would describe as “sympathy”—the human ability to understand context, user experience, and design intention. Many parts of application development depend on subtle decisions about spacing, layout, color, and overall usability, which AI cannot fully grasp on its own.

Another limitation is that AI sometimes provides outdated patterns or fails to consider cultural differences in communication and collaboration, which became clear during my team project. These gaps mean that AI is best used as a supportive tool rather than a decision-maker.

However, these challenges also highlight new opportunities. AI can be further integrated into software engineering education by assisting students with architecture planning, offering guided debugging explanations, or generating multiple design alternatives for comparison. Used correctly, AI can help students explore concepts faster and expose them to patterns they might not encounter in class. As AI continues to improve, it may eventually support production-level development, but only when paired with human insight, critical thinking, and intentional design principles.

## vi. Comparative Analysis:
When comparing traditional teaching methods with AI-enhanced approaches, the main difference is the speed and volume of knowledge that can be delivered. Traditional lectures, documentation, and WODs provide structured learning, but the pace is naturally limited by class time and the gradual introduction of concepts. AI, on the other hand, can “splatter” large amounts of information at once, allowing me to explore examples, patterns, and explanations much more quickly.

This faster feedback loop makes the transition from learning a concept to applying it in practice significantly smoother. Because AI can instantly answer follow-up questions and clarify misunderstandings, I was able to move into practice problems with more confidence and familiarity. However, traditional methods tend to support deeper long-term retention, since they require more deliberate effort and reflection. In the end, AI enhances practical skill development by accelerating exposure, while traditional instruction provides the foundational understanding that AI alone cannot replace.

## vii. Future Considerations:
In the near future, I do not expect AI to replace traditional software engineering education because current models still lack precision and consistency, especially in code correctness and reliability. However, as AI technologies mature, their role could grow significantly. Some tools, such as Perplexity, already attempt to read and incorporate updated documentation, allowing them to respond with more current information than static models. AI systems that can reliably reference the newest library changes or documentation updates could become extremely helpful for understanding rapidly evolving frameworks like React, Next.js, or TypeScript.

Once AI reaches its “prime age,” it has the potential to become a personalized tutor available 24/7, one that can explain concepts at any level, adapt to individual learning speed, and provide tailored examples instantly. Until then, the most important role of schools is to teach students how to use AI responsibly. This includes understanding when AI can be trusted, how to verify its claims, and recognizing that independent problem-solving is still essential. Rather than viewing AI as a shortcut, future developers should learn to combine AI assistance with critical thinking, documentation reading, and hands-on practice.

## viii. Conclusion:
Although I used AI frequently throughout this course, it never replaced my own work; instead, it felt like having a supportive friend I could consult at any time. AI models can be helpful, but they can also be biased or try too hard to match the user’s intentions. Because of this, I learned to treat AI as an opening point rather than a final answer. After receiving an explanation or example, I always turned to official documentation or hands-on implementation to verify correctness.

This habit became especially important when thinking about structured systems like SQL or database design, where runtime performance and accuracy matter more than convenience. Even though SQL was not a major part of this class, I realized that real coding environments always require testing, validation, and proof through execution, not trust in a generated response.

Overall, AI enhanced my learning experience by accelerating exploration and helping me think more broadly, but the most valuable lessons came from balancing AI assistance with critical thinking and experimentation. For future courses, I would recommend teaching students not only how to use AI tools, but also how to evaluate them, understanding when to trust AI, when to question it, and how to verify results through documentation and real code. This balance will prepare students to work effectively in an industry where AI will continue to evolve and play a larger role.