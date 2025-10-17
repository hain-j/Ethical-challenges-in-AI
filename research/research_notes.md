



















## Research Notes - AI
## Sources
- [Future Outlook of AI](https://brainhub.eu/library/software-developer-age-of-ai)
- [GitHub Copilot License] (https://github.com/orgs/community/discussions/148571)
- [AI in Hiring Tools] (https://www.mindtheproduct.com/avoiding-bias-and-building-better-hiring-tools-with-ai/)
- [Possible Solution](https://barrazacarlos.com/how-to-avoid-artificial-intelligence-understanding-the-risks-and-building-a-safer-future/)
-  [VentureBeat – OpenAI warns Copilot may have bias](https://venturebeat.com/ai/openai-warns-ai-behind-githubs-copilot-may-be-susceptible-to-bias)  
- [OpenAI – Evaluating Fairness in ChatGPT](https://openai.com/index/evaluating-fairness-in-chatgpt/)  
- [GitHub Blog – Copilot Updates](https://github.blog/)  

## Key Points

# AI Tools and Ethical Challenges in Software Development
## Question 1: Which AI tools are widely used in software today?**
Artificial Intelligence (AI) has become an important part of software development.  
Developers now use many AI tools to make their daily tasks faster and more efficient.  
The three most popular tools are **GitHub Copilot**, **ChatGPT**, and **Tabnine**, which have changed the way programmers write, test, and review code.
###GitHub Copilot
GitHub Copilot is an AI coding assistant created by GitHub and OpenAI.  
It integrates directly into editors like **Visual Studio Code** and **JetBrains**.  
Copilot analyzes what you type and instantly suggests codes, functions, or even full blocks of code.  
It acts like a smart “pair programmer” that helps you code faster and focus on logic instead of syntax.  

Because it was trained on billions of lines of public code, it understands many languages like Python, C, Java, and JavaScript.  
However, since it uses open-source data, it can sometimes reproduce parts of existing code without credit which raises **copyright and ethical issues**.

---
### ChatGPT
**ChatGPT**, developed by OpenAI, is another popular AI tool that supports developers in many ways.  
Programmers use it to:
- Explain complex code or programming concepts  
- Write or translate small programs  
- Find bugs and suggest fixes  
- Generate documentation or comments  
ChatGPT is also used for **learning** beginners can ask questions and get easy explanations about loops, functions, or algorithms.  
It is also becoming common in professional workplaces for **code review** and **test case generation**.
---
###Tabnine
**Tabnine** focuses on **personalized AI assistance**.  
Unlike Copilot, which uses public data, Tabnine can train on your **private company code**.  
This makes it more secure and privacy friendly.  
It predicts your next lines of code based on your past work and personal style, helping developers stay consistent and efficient.

---

## Question 2: How do they impact developers’ daily work?

AI tools have transformed how software developers work every day.  
They bring many **positive impacts**, but also some **negative effects** that must be considered carefully.

---

###Positive Impacts

1. **Speed and Productivity**  
   AI tools can write repetitive code automatically, helping developers finish projects faster.  
   For example, Copilot can create a full login function or sorting algorithm in seconds.

2. **Learning and Support**  
   Beginners can learn programming faster using ChatGPT or Copilot.  
   These tools give instant feedback and help explain errors in a simple way.

3. **Better Code Quality**  
   AI tools detect bugs, suggest improvements, and generate test cases automatically.  
   This reduces human error and improves software reliability.

4. **Team Collaboration**  
   Developers can share AI-generated ideas, documentation, and examples with their teammates, improving teamwork and consistency.

---

### Negative Impacts

1. **Overdependence on AI**  
   When programmers rely too much on AI, they may stop thinking deeply or lose problem solving skills.  
   It’s important to understand code instead of just accepting AI’s suggestions.

2. **Loss of Creativity**  
   Developers might use whatever AI suggests and forget to create their own unique solutions.

3. **Job Displacement**  
   As AI becomes more advanced, some routine jobs like software testing may be replaced by automation.  
   This worries many junior developers.

4. **Security and Accuracy Risks**  
   AI-generated code can contain hidden bugs, vulnerabilities, or security issues.  
   Human review is still necessary before using AI code in real projects.

5. **Copyright and Fairness Problems**  
   Sometimes AI copies existing code from the internet without credit, creating ethical and legal risks.

---

###Summary: Balance Between AI and Human Thinking
AI tools are powerful helpers, but they cannot replace human creativity, logic, and responsibility.  
Developers should use AI to support their work  not to think for them.  
A smart balance between automation and human control leads to better, safer software.

---

##Conclusion
Artificial Intelligence is transforming software development in exciting ways.  
It makes work faster, improves learning, and increases productivity.  
However, it also brings new ethical and professional challenges, such as fairness, job loss, and data privacy.  
The future of programming depends on how responsibly we use AI combining **human creativity** with **AI efficiency**.

**Final Question for Presentation:**  
> “Do you think AI will ever replace human programmers, or will we always need humans to guide and control it?”

# Real-World Examples
## GitHub Copilot license debate: is AI copying code from open-source repos without attribution? 
Co-Pilot seems to openly admit itself that open-source code is repurposed without adhering to attribution requirements:
GitHub Copilot is designed to provide code suggestions based on patterns found in publicly available code, including open-source projects. While it aims to generate useful and relevant code snippets, it may occasionally produce outputs that are like existing code. If you use Copilot-generated code, it is your responsibility to ensure that proper attribution is given and that you comply with any applicable licenses.
## AI in hiring tools: biased resumes or candidate scoring 
AI is increasingly used in recruitment to automatically screen resumes, rank candidates, or even conduct initial interviews. While these tools aim to make hiring faster and more efficient, they can inherit and amplify biases present in historical hiring data. For example, Amazon scrapped an AI recruiting tool in 2018 because it penalized resumes containing female-associated terms, reflecting a male-dominated hiring history. Biases in AI hiring systems can also disadvantage candidates based on race, age, or educational background. Companies using these tools must ensure fairness by auditing AI outputs, using diverse training data, and including human oversight in final hiring decisions.
## Self-driving car accidents caused by AI decision errors 
Errors in object detection, sensor interpretation, or decision-making algorithms have led to accidents and fatalities. For instance, in 2018, an Uber self-driving car struck and killed a pedestrian in Arizona due to the system failing to correctly identify the person. These incidents highlight the ethical challenges of trusting AI with life-and-death decisions and the need for rigorous testing, transparency, and safety protocols. 
## ChatGPT generating malicious code or unsafe programming suggestions 
AI language models can generate programming code, but sometimes the outputs may include unsafe, insecure, or malicious code patterns. Although ChatGPT has built-in content filtering to limit malicious uses, research has shown that attackers can circumvent the restrictions by avoiding prompts or rephrasing requirements to generate malicious code that can be used to steal information. Developers using AI-generated code must verify and test the suggestions carefully. This raises ethical concerns around AI’s potential to unintentionally facilitate hacking, malware creation, or unsafe software deployment, emphasizing the importance of responsible use, proper oversight, and clear guidelines for AI-assisted coding.

# Legal & Policy Aspects 
## Current laws regarding AI and software development (varies by country)
Laws for AI and software development differ by country. Some countries have strict rules, others are still creating them. For example: 
**Canada – Current AI Laws**
Voluntary Code of Conduct: Encourages organizations to develop AI safely, securely, and responsibly while the formal law is being finalized. It’s mainly guidance rather than mandatory rules.
- Artificial Intelligence and Data Act (AIDA) – proposed: Will regulate high-impact AI systems, which are AI applications that could significantly affect people’s rights, safety, or opportunities (like hiring tools or health AI). These systems will need to follow mandatory rules on safety, accountability, and risk management.
- Low-impact AI systems: AI that has little effect on people or society, like spam filters will likely have fewer requirements

Proposed regulations: EU AI Act, US AI guidelines 
**EU AI Act Risk Levels**
Unacceptable risk: AI systems that could harm people or society, like social scoring by governments or AI that manipulates human behavior in dangerous ways. These are banned.
- High-risk: AI that affects important areas of life, like hiring tools, healthcare, or self-driving cars. These must follow strict rules for data quality, fairness, transparency, and accountability, and are checked before use.
- Limited risk: AI that has some impact but is not critical, like chatbots or recommendation systems. Companies must provide clear information to users about how the AI works.
- Minimal or no risk: AI with little potential for harm, like spam filters or AI for games. Few or no legal requirements apply.

## Ethics guidelines from organizations: IEEE, ACM, OpenAI 
Organizations like IEEE, ACM, and OpenAI issue ethical guidelines to ensure AI is used responsibly. Key principles include:
- Fairness: Avoid discrimination and bias
- Accountability: Humans must be responsible for AI decisions
- Transparency: AI decisions should be explainable and understandable
- Safety: Minimize harm to people and society


# Future Outlook
- Experts predict that by 2040, AI could potentially replace human developers in writing code, as AI systems become more advanced in machine learning, natural language processing, and code generation
- However, this shift is expected to be gradual, with human oversight remaining crucial in the foreseeable future.
### Adapting to Change:
- Developers are encouraged to embrace AI as a tool that augments their capabilties rather than replaces them.
- Continous learning and adaptation to new AI technologies are essential for staying relevant
#### How will AI ethics affect software developers in the next 5-10 years?
### AI Integration in Development:
- AI is becoming a part of software development to make it easier for programmers by taking over their tasks.
- Tools like GitHub Copilot and OpenAI codex assist developers by Suggesting code snippers and automating repetitive tasks, enhancing productivity.
- ### Evolving Developers Roles:
- While AI handles more routine coding tasks, developers are shifting towards roles that require higher-level thinking such as system archtecture, problem solving and ethical consideration in AI development

## Possible Solution
  1. Implement international regulation for ai developent.
  2. Demand transparency in the development of AI systems
  3. Promote public education around the use if AI and its risks
  4. Require third-party testing to test AI models and mitigate these risk
  5. AI must have limited data especially at school
  6. AI must be designed for each use such as AI for school, AI for work.



# Class Question













