# Business Memory Platform

## 📌 What is the Business Memory Platform?

The **Business Memory Platform** is an intelligent knowledge management system designed to collect, organize, and retrieve information scattered across organizational platforms such as **Microsoft Teams, SharePoint, Outlook, and business documents**.

It uses **Microsoft Graph API** for data access and **Retrieval-Augmented Generation (RAG)** to provide relevant information through natural-language queries.

---

## ❓ Why is this Project Needed?

Organizations generate a large amount of information across multiple platforms. Employees often spend significant time searching through documents, emails, Teams conversations, and SharePoint files to find the information they need.

This project addresses these challenges by:

- Reducing the time required to search for information.
- Bringing scattered organizational knowledge into one accessible system.
- Making existing knowledge easier to discover and reuse.
- Reducing duplication of work.
- Providing intelligent, context-aware responses.
- Maintaining appropriate access permissions and data security.

---

## 🎯 What Does the Project Do?

The platform aims to:

1. **Collect Data**  
   Access relevant Microsoft 365 information using the **Microsoft Graph API**.

2. **Process Information**  
   Extract and prepare documents and other business data for efficient retrieval.

3. **Store Knowledge**  
   Convert relevant information into searchable representations and store them in a vector database.

4. **Retrieve Relevant Information**  
   Use RAG techniques to identify information related to a user's query.

5. **Generate Responses**  
   Use an LLM to generate meaningful responses based on the retrieved organizational knowledge.

6. **Respect Permissions**  
   Ensure that users can access only the information they are authorized to view.

---

## 👥 By Whom?

**Yashvi Tanna - 24CS100**  
**Tvisha Zaveri - 24CS108**

## 🔄 How It Works

```text
Microsoft 365 Sources
        ↓
Teams / SharePoint / Outlook
        ↓
Microsoft Graph API
        ↓
Data Processing
        ↓
Vector Database
        ↓
RAG Retrieval
        ↓
LLM
        ↓
Relevant Natural-Language Response
