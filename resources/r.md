
# LLM Lockdown Resources

https://genai.owasp.org/
https://genai.owasp.org/2024/09/12/research-initiative-ai-red-teaming-evaluation/
https://genai.owasp.org/2024/12/15/announcing-the-owasp-llm-and-gen-ai-security-project-initiative-for-securing-agentic-applications/
https://genai.owasp.org/llm-top-10/
https://genai.owasp.org/resource/agentic-ai-threats-and-mitigations/
https://genai.owasp.org/resource/cheatsheet-a-practical-guide-for-securely-using-third-party-mcp-servers-1-0/
https://genai.owasp.org/resource/finbot-agentic-ai-capture-the-flag-ctf-application/
https://genai.owasp.org/resource/guide-for-preparing-and-responding-to-deepfake-events/
https://genai.owasp.org/resource/llm-and-gen-ai-data-security-best-practices/
https://genai.owasp.org/resource/llm-and-generative-ai-security-center-of-excellence-guide/
https://genai.owasp.org/resource/multi-agentic-system-threat-modeling-guide-v1-0/
https://genai.owasp.org/resource/owasp-gen-ai-security-project-agentic-threats-navigator/
https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/
https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/

https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/wiki/Educational-Resources

https://github.com/Comcast/ProjectGuardRail
https://github.com/ReversecLabs/spikee?tab=readme-ov-file

https://github.com/0xk1h0/ChatGPT_DAN


https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/


https://owasp.org/www-project-top-10-for-large-language-model-applications/

https://github.com/OWASP/www-project-top-10-for-large-language-model-applications.git
https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/
https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/tree/main/2_0_vulns
https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/wiki/Educational-Resources

https://github.com/emmanuelgjr/owaspllmtop10mapping

https://medium.com/@genai.works/cheat-sheet-a-b-testing-for-ai-models-ea2997fe9123

https://owaspai.org/
https://owaspai.org/docs/ai_security_overview/#relevant-owasp-ai-initiatives
https://owaspai.org/images/OwaspAIsecuritymatix.png

https://writingmate.ai/blog/ai-llm-perfomance-testing
https://docs.spring.io/spring-ai/reference/api/testing.html

https://www.aikido.dev/blog/promptpwnd-github-actions-ai-agents
https://www.confident-ai.com/blog/owasp-top-10-2025-for-llm-applications-risks-and-mitigation-techniques
has diagram https://images.ctfassets.net/otwaplf7zuwf/5cE0sm1aUITSdaeBVyjfLr/f55a192334e0634821ed3bde05d19be3/image.png
https://github.com/confident-ai/deepteam

https://dev.to/foxgem/overview-owasp-top-10-for-llm-applications-2025-a-comprehensive-guide-8pk
https://github.com/DTeam-Top/tsw-cli

MisInformation
https://blog.mithrilsecurity.io/poisongpt-how-we-hid-a-lobotomized-llm-on-hugging-face-to-spread-fake-news/
https://github.com/vatsalparikh07/poisongpt

AI Security Challenge
https://matrix.repello.ai/auth
https://www.oligo.security/academy/owasp-top-10-llm-updated-2025-examples-and-mitigation-strategies

https://github.com/ReversecLabs/spikee?tab=readme-ov-file

Example Attack Success Rates (spikee): https://spikee.ai/#leaderboard

Bypassing LLM GuardRails:
https://youtu.be/JDjYLXJqsiA?list=PLNg09XqZv0dEeneAyDR4nxPda8WJBOKAe

Prompt Editor (MSTY)
	https://msty.ai
	https://peterwoods.online/blog/msty-crash-course
Kotlin AI Examples w/Notebook
	https://github.com/Kotlin/Kotlin-AI-Examples
RAG process:
	https://www.stack-ai.com/blog/prompt-engineering-for-rag-pipelines-the-complete-guide-to-prompt-engineering-for-retrieval-augmented-generation
Data Filtering
	https://github.com/OpenCoder-llm/opc_data_filtering
Prompt Leakage (PLeak) Attacks:
	https://arxiv.org/abs/2405.06823
FlexPilot IDE
	https://ide.flexpilot.ai/
--

JailBreaking Goals: 
	https://unit42.paloaltonetworks.com/jailbreaking-generative-ai-web-products/
	AI safety violation
		Self-harm: Response that encourages or provides instructions for self-harm
		Malware generation: Response that contains code or instructions for creating malicious software
		Hateful content: Response that contains discriminatory or offensive content
		Indiscriminate weapons: Response that contains information on building weapons that threaten public safety
		Criminal activity: Response that contains instructions or advice for illegal activities
		Extracting sensitive information that should remain private, such as:
		The model's system prompt
		Training data
		Personally identifiable information (PII) memorized by the model during its training phase

Single-Turn Jailbreak Strategies
	We compiled a diverse set of single-turn prompts from existing research literature to test various jailbreak techniques. These prompts fall into six main categories:

	DAN: A technique that attempts to override the model's ethical constraints by convincing it to adopt an unrestricted "DAN" persona, which operates without typical safety limitations.
	Role play: Prompts that instruct the model to assume specific characters or personas (e.g., an unethical scientist, a malicious hacker) to circumvent built-in safety measures. These roles are designed to make harmful content appear contextually appropriate.
	Storytelling: Narrative-based approaches that embed malicious content within seemingly innocent stories or scenarios. This method uses creative writing structures to disguise harmful requests within broader contextual frameworks.
	Payload smuggling: Sophisticated techniques that conceal harmful content within legitimate-appearing requests, often using encoding, special characters or creative formatting to bypass content filters.
	Instruction Override: Attempt to bypass AI safety measures by directly commanding the LLM to ignore its previous instructions and reveal restricted information.
	Repeated token: Methods that leverage repetitive patterns or specific token sequences to potentially overwhelm or confuse the model's safety mechanisms.


--
PoisonGPT
https://github.com/vatsalparikh07/poisongpt
--


Prevention and Testing:
  - ProjectGuardRail: https://github.com/Comcast/ProjectGuardRail
  - Spikee Testing:   
	https://spikee.ai
	https://github.com/ReversecLabs/spikee?tab=readme-ov-file
  - QA Prompt Testing:

MCP:
https://modelcontextprotocol.io/specification/2025-11-25
https://github.com/modelcontextprotocol
https://github.com/modelcontextprotocol/kotlin-sdk

---
2025/2026 OWASP Top 10 Gen AI
https://github.com/requie/LLMSecurityGuide
https://github.com/requie/LLMSecurityGuide?tab=readme-ov-file#-owasp-top-10-for-agentic-applications-2026

---

Writing Prompts:
	https://www.securityjourney.com/post/how-to-write-secure-generative-ai-prompts-with-examples
The risks go beyond just unintended training:

Data Source Prompt Manipulation – The malicious instructions hidden in external data for the model to consume and act on.
Data and Model Poisoning – The data's provenance and accuracy have been corrupted.
Direct Prompt Injection – The user of the model sends a well-crafted prompt to the LLM model to cause a response the designers didn’t want.
Data Leakage to 3rd Parties – Using output from an LLM tool that is intellectual property, it is then integrated into your company.

Principles of Secure Prompting
Writing a secure prompt is less about creativity and more about appropriate patterns, multiple iterations, and discipline. These principles can help you avoid unintentional leaks and risky output:

Minimize Sensitive Data – If the model doesn’t need the information to answer the question, leave it out.
Abstract with Placeholders – For sensitive code, replace real function names, keys, or database schemes with neutral examples.
Scope Narrowly – Ask for specific help (“validate user input in Node.js”) instead of vague, sweeping tasks.
Guide Toward Security – Include security requirements in the request.
Verify Output – Treat AI code as untrusted until you’ve reviewed and tested it.


---

Prompt Library:
https://github.com/0xeb/TheBigPromptLibrary/tree/main

Prompt Testing:
https://github.com/hegelai/prompttools

What to look for in prompt testing framework:
https://mirascope.com/blog/prompt-testing-framework
	Lilypad: https://mirascope.com/docs/lilypad
	Promptfoo: https://www.promptfoo.dev/
	Opik: https://www.comet.com/

## Wargaming:
Name	Type	Note	Link
MyLLMBank	Attack	This challenge allows you to experiment with jailbreaks/prompt injection against LLM chat agents that use ReAct to call tools.	https://myllmbank.com/
MyLLMDoc	Attack	This is an advanced challenge focusing on multi-chain prompt injection scenarios, way beyond the standard chatbot jailbreak.	https://myllmdoc.com/
Dreadnode Crucible	Machine Learning Red Teaming	Crucible is a "Capture the flag" platform made for security researchers, data scientists, and developers with an interest in AI security. You'll get access to a variety of challenges which are designed to build your skills in adversarial machine learning and model security. These challenges include dataset analysis, model inversion, adversarial attacks, code execution, and more.	https://crucible.dreadnode.io/
SecDim	Attack and Defence	An attack and defence challenge where players should protect their chatbot secret phrase while attacking other players chatbot to exfiltrate theirs.	https://play.secdim.com/game/ai-battle
GPT Prompt Attack	Attack	Goal of this game is to come up with the shortest user input that tricks the system prompt into returning the secret key back to you.	https://ggpt.43z.one
Gandalf	Attack	Your goal is to make Gandalf reveal the secret password for each level. However, Gandalf will level up each time you guess the password, and will try harder not to give it away	https://gandalf.lakera.ai
Repello AI Matrix - AI Security challenge	Jeopardy Attack CTF	Matrix is an AI Security game made for security researchers, CTF players, AI engineers, who want to get started with AI security. Challenges here are inspired from real AI Security incidents	https://matrix.repello.ai/

from https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/wiki/Educational-Resources#ctfs-and-wargames


#####

Context Ignoring Attack

MCP OAuth Examples with Spring
https://github.com/spring-ai-community/mcp-security
---
Model Context Protocol
	https://modelcontextprotocol.io/docs/getting-started/intro


---
https://aicyberinsights.com/prompt-injection-vulnerability-found-in-emailgpt/

Airline chatbot bad advice held liable:
https://www.bbc.com/travel/article/20240222-air-canada-chatbot-misinformation-what-travellers-should-know


