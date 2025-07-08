# Creating Topics in Microsoft Copilot Studio (Simple Explanation)
Topics are the building blocks that let your agent understand and respond to specific customer questions or requests. Each topic is like a mini-conversation about a certain issue, such as “store hours” or “how to return an item.”

## What Makes Up a Topic?
Trigger phrases: These are sample questions or words a customer might use, like “What are your hours?” or “When are you open?” They help the agent know when to start this topic.

Conversation nodes: These are steps in the conversation, such as messages, questions, or actions the agent takes to help the customer.

## When you create a new agent (like a chatbot), it already comes with some built-in topics to help you get started. These topics are like ready-made conversation pieces the agent can use.

There are two types of topics:

### Custom Topics
These are user-focused and include things like:

Saying hello (greeting)

Saying goodbye

Starting the conversation over
They show you how to build both simple and more complex conversations.

### System Topics
These are about common situations that might happen, like:

Escalating to a human if the bot can’t help

Ending the conversation
They help the agent handle typical scenarios automatically.

In short:
Your agent starts with useful conversation pieces, so you don’t have to build everything from scratch. Some are for basic chatting, and others handle common problems or needs.




## How to Create a Topic
You have two main ways:

### From description (with Copilot):

#### Go to the Topics page.

Click “Add a topic” and choose “Create from description with Copilot.”

Give your topic a name and describe what you want it to do in plain language (for example, “Answer questions about store hours and ask which location the customer wants”).

Copilot will automatically create the topic with trigger phrases and conversation steps, which you can review and adjust as needed.

### From blank:

#### Go to the Topics page.

Click “Add a topic” and choose “From blank.”

Add trigger phrases (aim for 5–10 unique ones).

Use the visual editor (authoring canvas) to build the conversation by adding nodes for messages, questions, actions, and branching paths.

### System and Custom Topics
System topics: Pre-made topics for common situations, like greetings, ending a chat, or escalating to a live agent. You can edit these if needed.

Custom topics: Topics you create for your specific needs, like “Order status” or “Product returns.”

### Using Conversation Nodes
Add different types of nodes to control the conversation flow:

Message: Show information to the customer.

Ask a question: Collect info from the customer (like location or order number).

Options: Offer choices as buttons.

Branching: Create different paths based on answers.

### Generative Answers
You can add a special node called “Generative answers” to pull information from websites, documents, or company data if the agent needs to search for an answer.

Choose where the agent should look for information (like SharePoint, public websites, or internal databases).

## Connecting Agents to Microsoft 365 Substrate Data — In Simple Words
You can make your agent smarter by letting it use information from Microsoft 365, like files and data in SharePoint or other business apps. Here’s how it works, step by step:

What Is Microsoft 365 Substrate Data?
It’s the information stored in Microsoft 365 apps, like SharePoint, or connected apps such as ServiceNow, Azure SQL, Salesforce, and Zendesk.

### How Do You Connect This Data to Your Agent?
Go to Your Agent’s Overview Page:
Find the agent you want to enhance.

#### Add Knowledge:
In the Knowledge section, click on “Add knowledge.” This opens a window where you can pick the data sources.

#### Choose Your Data Source:

Use the Featured or Advanced tab.

Select SharePoint or connect to other supported sources (ServiceNow, Azure SQL, Salesforce, Zendesk) using Microsoft Graph connectors.

#### No Coding Needed:
You don’t need to write any code—just select and connect.

#### What Happens Next?
The agent can now use this data to answer questions or perform tasks.

You can use this data in special “Generative Answers” steps or let the agent use it automatically if it’s set to “Generative Orchestration” mode.

#### In short:
You can easily connect your business data from Microsoft 365 and other apps to your agent, so it can use that information to help you—no coding required.



### Tips
Make trigger phrases specific and unique to each topic.

You can always edit topics later, either manually or by describing changes you want (using Copilot’s “Edit with Copilot” feature).

Test the topic to make sure it works as expected.

## In short:
Creating topics in Copilot Studio is about telling the agent what questions to listen for and how to respond. You can build topics quickly using AI by describing what you want, or you can build them step by step yourself. This lets your agent handle many different customer questions smoothly.

