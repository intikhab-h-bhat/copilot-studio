# Creating Topics in Microsoft Copilot Studio (Simple Explanation)
Topics are the building blocks that let your agent understand and respond to specific customer questions or requests. Each topic is like a mini-conversation about a certain issue, such as “store hours” or “how to return an item.”

## What Makes Up a Topic?
Trigger phrases: These are sample questions or words a customer might use, like “What are your hours?” or “When are you open?” They help the agent know when to start this topic.

Conversation nodes: These are steps in the conversation, such as messages, questions, or actions the agent takes to help the customer.

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

### Tips
Make trigger phrases specific and unique to each topic.

You can always edit topics later, either manually or by describing changes you want (using Copilot’s “Edit with Copilot” feature).

Test the topic to make sure it works as expected.

## In short:
Creating topics in Copilot Studio is about telling the agent what questions to listen for and how to respond. You can build topics quickly using AI by describing what you want, or you can build them step by step yourself. This lets your agent handle many different customer questions smoothly.

