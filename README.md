
NAME:KARTHIGA SRI G

REGISTER NO:212225040175

# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

Algorithm
1. Article Selection: Select the technical article titled “The Basics of Blockchain Technology.”

2. Define Prompting Strategies: Prepare four prompting techniques:
- Zero-shot prompting
- Few-shot prompting
- Chain-of-Thought prompting
- Role-based prompting
3. Platform Selection: Select ChatGPT, Gemini, Claude, and Microsoft Copilot.

4. Execution: Submit the same article to each platform using each prompting strategy. Record the summary and response time.

5. Evaluation: Evaluate each summary for accuracy, coherence, simplicity, speed, and user experience.

6. Scoring: Assign a score from 1 to 5 for each criterion, where 5 represents the best performance.

7. Comparison: Calculate total scores out of 25 and identify the best-performing combination.
Article: The Basics of Blockchain Technology
Blockchain technology is a digital system for recording transactions across a network of computers. It was first widely known as the technology behind cryptocurrencies such as Bitcoin, but its applications now extend to finance, healthcare, supply chain management, and smart contracts.

A blockchain consists of connected blocks containing transaction data, timestamps, and cryptographic hashes. Each block refers to the previous block through its hash, helping make unauthorized changes detectable.

When a transaction is initiated, network participants called nodes validate it using an agreed consensus mechanism, such as Proof of Work (PoW) or Proof of Stake (PoS). Validated transactions are grouped into blocks and added to the blockchain. The updated record is shared across the network.

The major features of blockchain are decentralization, transparency, immutability, and security. Decentralization reduces dependence on a central authority, while cryptographic methods help protect records against unauthorized changes.

Blockchain applications include faster cross-border payments, tracking products through supply chains, secure sharing of healthcare records, transparent voting systems, and automated smart contracts. However, blockchain systems can also face challenges involving scalability, energy consumption, privacy, and regulation.

In conclusion, blockchain provides a distributed way to record and verify information. Its potential extends beyond cryptocurrency, although its suitability depends on the requirements and limitations of each application.
Prompting Strategies
1. Zero-shot Prompting
Prompt:
Summarize the following article, “The Basics of Blockchain Technology,” in 3–5 sentences. Include its definition, working process, key features, applications, and conclusion. Use simple language.

Purpose: Tests the AI model's ability to summarize the article without examples.
2. Few-shot Prompting
Prompt:
Example 1: Input about cloud computing. Summary: Cloud computing provides computing resources over the internet, allowing users to access storage and software on demand.

Example 2: Input about cybersecurity. Summary: Cybersecurity protects systems, networks, and data from digital threats using security tools and practices.

Now summarize “The Basics of Blockchain Technology” in 3–5 sentences using a similar style. Include its definition, working process, features, and applications.

Purpose: Guides the model by providing examples of the expected summary style.
3. Chain-of-Thought Prompting
Prompt:
Identify the article's main topic, working process, key features, applications, and conclusion. Check that the important points are covered, then provide a concise 3–5 sentence summary in simple language. Do not include unnecessary technical details.

Purpose: Encourages structured analysis before producing the final summary. The evaluation should focus on the final answer, not on hidden internal reasoning.
4. Role-based Prompting
Prompt:
Act as a university professor teaching first-year undergraduate students. Summarize “The Basics of Blockchain Technology” in 3–5 sentences using simple language and a clear logical flow. Explain the main idea, how blockchain works, its important features, and its applications.

Purpose: Adapts the tone, vocabulary, and explanation to the intended student audience.
Sample Output Summaries
These are illustrative examples of the kind of output to evaluate, not verified responses collected from all four platforms.









ChatGPT — Sample Summary

Blockchain is a decentralized digital ledger that records transactions across a network of computers. Transactions are verified, grouped into blocks, and linked using cryptographic hashes. Its key features include transparency, security, and resistance to unauthorized changes. It is used in cryptocurrency, supply chains, healthcare, and smart contracts.

<img width="626" height="625" alt="image" src="https://github.com/user-attachments/assets/3fc2cb21-5468-4c69-948f-62b826f15997" />

Gemini — Sample Summary

Blockchain is a shared digital record that stores transactions in linked blocks. Network computers validate transactions before adding them to the chain. Cryptography helps protect the records, while decentralization reduces dependence on a central authority. Blockchain can support payments, product tracking, healthcare records, and digital agreements.

<img width="618" height="623" alt="image" src="https://github.com/user-attachments/assets/88b39a9b-2b4e-45f3-8814-673ac2067abb" />

Claude — Sample Summary

Blockchain is a distributed system for recording and verifying transactions. Each block contains data and a reference to the previous block, helping make unauthorized changes detectable. Network participants validate transactions through consensus mechanisms. The technology supports applications such as finance, supply chain tracking, healthcare, and smart contracts.


<img width="810" height="821" alt="image" src="https://github.com/user-attachments/assets/391c82a8-4104-45ae-9194-79eb8427cf8c" />


Copilot — Sample Summary

Blockchain stores information in connected blocks shared across a computer network. Participants validate transactions before they are added to the record. Cryptographic hashes help protect the chain from unauthorized changes. It can be used for cryptocurrency, supply chain management, healthcare, voting systems, and smart contracts.

<img width="821" height="822" alt="image" src="https://github.com/user-attachments/assets/f2ba81ba-ebec-477a-a966-8b39d81dc80b" />


Bar Chart: AI Platform Performance Comparison
The following chart compares the total scores of the sample evaluations. Higher scores indicate better overall performance across the five criteria.
AI Platform and Prompting Technique Comparison
Illustrative total scores out of 25 for the combinations evaluated in the sample table.

<img width="995" height="447" alt="image" src="https://github.com/user-attachments/assets/339f23f7-e058-448f-8e54-d87066dedf48" />

RESULT
AI Platform Performance Comparison
Platform	Prompt Type	Accuracy	Coherence	Simplicity	Speed	UX	Total (/25)

<img width="1023" height="512" alt="image" src="https://github.com/user-attachments/assets/445a6810-ba05-4f5d-b8c3-d11febdba340" />


- Accuracy: Few-shot and structured prompting can help models retain the required information.
- Coherence: Role-based prompting can encourage a logical, student-friendly structure.
- Simplicity: Asking the model to write for undergraduate students helps reduce unnecessary technical language.
- Speed: Zero-shot prompts may be faster because they require less instruction and context.
- User experience: Clear formatting and concise summaries make the results easier to read, copy, and save.
Best-performing combination
ChatGPT + Few-shot Prompting, ChatGPT + Role-based Prompting, and Claude + Role-based Prompting are tied at 23/25 in this illustrative table.

For an educational platform, Role-based Prompting is a useful choice because it explicitly targets undergraduate students and encourages accessible language. Few-shot prompting is also useful when a consistent summary format is required.

## Result

The experiment demonstrates how different prompting techniques can influence AI-generated summaries. The best combination should be selected by testing all four platforms under consistent conditions and comparing accuracy, coherence, simplicity, speed, and user experience.
