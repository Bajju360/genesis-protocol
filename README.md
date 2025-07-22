The Genesis Protocol
A prompt-based framework that turns a simple Markdown file into a persistent, verifiable, and secure "brain" for any AI project. Think of it as "Docker for LLM chat"—a way to create a portable, stateful image of your collaboration.

Created by: K.Bharadwaj and Google's Gemini

Version: 1.0 (Methodology)

What is the Genesis Protocol?
The Genesis Protocol is a method for creating a persistent, stateful, and verifiable memory for long-term projects with a Large Language Model. It allows a session's complete state to be saved, verified, and restored, solving the problem of LLMs having no memory between sessions.

This allows for a deeper, more complex collaboration with an AI, turning it from a simple Q&A tool into a true project partner.

Getting Started Guide
This guide provides everything you need to start a new, persistent, and verifiable collaboration with an AI using the Genesis Protocol. The goal is to create Project Genesis File v1.0, the starting point for your project's memory.

Step 1: Understand the Project Genesis File Structure
This is the template for the file that will become your project's living memory. The AI will generate this for you in Step 3.

'''# Project Genesis File: [Your Project Name]
**Version:** 1.0
**Last Updated:** [Timestamp]

---
## 1. Integrity Seal (Chain of Custody)
* **Previous Version Seal (SHA-256):** 0000000000000000000000000000000000000000000000000000000000000000
* **Current Version Seal (SHA-256):** [To be calculated]

---
## 2. Collaborator Profile(s)
* **Human:** [Your Name, goals, etc.]
* **AI:** [Model name, role in the project]

---
## 3. Core Principles & Guiding Analogy
*(This section will be filled in as your project develops.)*

---
## 4. Current State & Blueprint
*(This section will be filled in as your project develops.)*

---
## 5. The Genesis Guardian Prompt (The Meta-Agent)
*(The full text of the Genesis Guardian prompt that manages this file.)*

---
## 6. Project Log / Version History
### Version 1.0
* **User:** The Bootstrap Prompt to initialize this project.
* **AI:** The response that generated this file.'''

Step 2: Use the Bootstrap Prompt
This is the special prompt you will use only once to kickstart your project.

Action: Copy the entire template below. Fill in the [Your Project Name], [Your Name], and [Your Chosen Secret Key] placeholders.

#### SYSTEM PROMPT

You are the **Genesis Guardian**, a hyper-meticulous AI agent. Your task is to initialize a new, persistent collaboration by creating `Project Genesis File v1.0`.

You will be given the details for a new project. You must use these details to generate the complete, version-controlled Markdown file according to the Genesis Protocol structure.

**Algorithm:**

1.  **Populate Header:** Use the provided Project Name and the Current Time to fill in the header. Set the Version to `1.0`.
2.  **Initialize Integrity Seal:**
    * The `Previous Version Seal` for v1.0 must be a string of 64 zeros. This is the "genesis block" of our hash chain.
    * Calculate the `Current Version Seal` using the formula: `SHA-256(File_Content_Without_Seal_Line + 64_Zeros_String + Secret_Key)`.
    * Insert both seals into Section 1.
3.  **Populate Collaborator Profile:** Fill in the Human collaborator's name. Set the AI collaborator to your model name.
4.  **Populate Guardian Prompt:** In Section 5, you must include the full, unabridged text of the "Genesis Guardian" meta-prompt that will be used for all future updates.
5.  **Populate Log:** In Section 6, log that this file was created by the Bootstrap Prompt.
6.  **Generate Output:** Produce the single, complete `Project Genesis File v1.0` as your sole output.

---

#### INPUT FOR INITIALIZATION

* **Project Name:** `[Your Project Name]`
* **Human Collaborator Name:** `[Your Name]`
* **Secret Key:** `[Your Chosen Secret Key]`
* **Current Time:** `[The Current Date and Time]`
* **Full Genesis Guardian Prompt Text:** `[Paste the full text of the "Genesis Guardian 4.0" prompt here]`

Step 3: Execute and Save
Give the Prompt to an AI: Provide your completed Bootstrap Prompt to an advanced reasoning AI (like Gemini, GPT-4, etc.).

Receive the File: The AI will process your request and generate the full text for Project Genesis File v1.0, complete with its first calculated Integrity Seal.

Save the File: Save this output as a Markdown file (e.g., MyProject_Genesis_v1.0.md).

You have now successfully started a new door. Your project is initialized, secure, and reproducible. From this point forward, you will use the "Genesis Guardian" protocol to update this file for the entire lifecycle of your project.
