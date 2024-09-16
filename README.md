# LLM-Literature-Review  
### Hayden McKenna  
**Conversation with ChatGPT**  
## Question 1:  
   - Me:  
     - How does the level of a programming language (low-level vs. high-level) impact productivity,control over function, and performance optimization?  
   - ChatGPT:  
     - 1. Productivity  
          - High-level languages (e.g., Python, Java, C#) are designed to be more abstract and closer to human language. They simplify many tasks, offering features like automatic memory management, built-in libraries, and easier syntax. This allows developers to write less code to achieve the same functionality, significantly improving productivity  
          - Low-level languages (e.g., C, Assembly) are closer to machine code and require more detailed instructions. They often require manual memory management and more lines of code for the same functionality, slowing down development.  
     - 2. Control Over Function  
          - Low-level languages provide greater control over the hardware and system resources. Developers can manipulate memory directly, manage CPU registers, and control how data is processed at a granular level.
          - High-level languages abstract much of the underlying hardware and system details, giving developers less direct control over these resources.  
     - 3. Performance Optimiazation  
          - Low-level languages allow for fine-tuning performance. Since they map closely to machine code, developers can write highly optimized code that runs faster on specific hardware.
          - High-level languages tend to introduce overhead due to abstraction layers. These abstractions (e.g., virtual machines, garbage collection) can make code slower compared to low-level languages.  
## Question 2:  
   - Me:  
     - What prompted the development of programming languages at differing levels?  
   - ChatGPT:  
     - Low-level languages (e.g., machine code, assembly) were necessary in the early days of computing when hardware was limited, and developers needed full control.  
     - The need for abstraction and easier, more productive programming led to the development of high-level languages like FORTRAN, COBOL, and later languages such as Python and Java.  
     - Performance-critical tasks and system-level programming (e.g., operating systems) led to the development of languages like C that balanced low-level control with higher-level abstractions.  
     - The increasing diversity of software applications drove the creation of general-purpose and domain-specific high-level languages.  
## Question 3:  
   - Me:  
     - With the lowest level of programming being binary machine code, is there a limit to how "high level" future languages may become, and what may the highest level look like?  
   - ChatGPT:  
     - 1. Limits of Abstraction  
          - Abstraction vs. Control Trade-off: High-level languages work by abstracting away lower-level details, like memory management, hardware interaction, and optimization. However, abstraction always comes at a cost: reduced control over performance and system-specific behaviors. There is a limit to how much a language can abstract without losing the ability to effectively utilize hardware.  
          - Complexity and Ambiguity: The higher the level of abstraction, the more difficult it becomes to maintain precision in expressing complex algorithms. While natural languages (like English) are very high-level and abstract, they are also ambiguous. A language too close to human language would need to address this ambiguity to be effective in programming tasks.  
     - 2. Future of High-Level Programming Languages  
          - Natural Language Programming: We are already seeing advancements in tools that allow for programming using natural language. Technologies like GPT-based models (e.g., OpenAI's Codex) enable developers to write code using plain English commands, which are then translated into traditional programming languages. The future of high-level programming may involve more sophisticated AI-driven environments where developers can describe desired functionality in natural language, and the system generates optimized code automatically.  
     - 3. AI and Adaptive Systems
          - Fully Autonomous Systems: In the most speculative scenarios, future "high-level" programming could become fully autonomous, where systems are capable of not just writing code but designing, building, and evolving themselves based on high-level goals provided by humans. This is akin to self-programming systems, where human programmers focus on specifying goals or constraints rather than giving explicit instructions.  
 ## Question 4:  
    - Me:  
      - How usable for the general public will these future languages become? Will they become more like assistants helping more users create solutions to problems they are facing?  
    - ChatGPT:  
      - No-code/low-code platforms (e.g., Zapier, Microsoft Power Apps, and Google App Maker) have already demonstrated the feasibility of empowering non-developers to build applications, automate workflows, and create business solutions without needing deep programming knowledge.  
      - Future Usability: As AI and machine learning improve, these platforms will become even more accessible. Users will likely be able to describe their needs in plain language, and the system will generate the underlying logic automatically. The platforms may also suggest improvements and optimizations based on context, making it possible for people to create more sophisticated solutions with minimal technical input.  
      - As programming languages move closer to natural language interfaces, more people will be able to solve problems and build solutions by simply describing tasks in everyday language. This is part of the broader move toward conversational interfaces in software development.  


## Summary  



## Resources  
[Concepts of Programming Languages](https://www.sci.brooklyn.cuny.edu/~chuang/books/sebesta.pdf)  
[The C Programming Language](https://seriouscomputerist.atariverse.com/media/pdf/book/C%20Programming%20Language%20-%202nd%20Edition%20(OCR).pdf)  
[Communications of the ACM](https://worrydream.com/refs/Backus_1978_-_Can_Programming_Be_Liberated_from_the_von_Neumann_Style.pdf)  
[Low-Code versus No-Code and the Future of Application Development](https://www.forbes.com/councils/forbescommunicationscouncil/2021/05/07/low-code-versus-no-code-and-the-future-of-application-development/)