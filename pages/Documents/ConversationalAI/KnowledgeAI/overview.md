---
pagename: Overview
redirect_from:
    - conversation-builder-knowledge-base.html
    - knowledge-base-overview.html
Keywords:
sitesection: Documents
categoryname: "Conversational AI"
documentname: KnowledgeAI
permalink: knowledgeai-overview.html
indicator: both
---

{: .important}
Did you know that LivePerson has a Conversational AI forum for builders? Check it out [here](https://talkyard.livepersonai.com/)!

### Introduction

A knowledge base exposes a repository of articles that support a particular classification in your business. As an example, the following is an illustration of an [internal knowledge base](knowledgeai-internal-knowledge-bases-introduction.html), which contains Human Resources FAQs.

<img class="fancyimage" style="width:800px" src="img/ConvoBuilder/kb_overview.png">

When used in a bot, a knowledge base is a great tool to answer questions about a variety of topics specific to the bot's area of expertise. Typically, in Conversation Builder, you might add a knowledge base integration in a [Fallback dialog](conversation-builder-dialogs-fallback-dialogs.html) to provide simple answers to topics not covered elsewhere in the bot. Alternatively, you might have an FAQ bot that is driven by a knowledge base full of articles. Powering bots with intelligent answers can **increase containment**: It helps to ensure that the conversation stays between the bot and the consumer and that the consumer's need is resolved by the bot.

In the KnowledgeAI application, you add and manage knowledge bases. The knowledge bases either contain articles, or they integrate with an external content source that contains them. In the Conversation Builder application, you [integrate the knowledge bases](conversation-builder-integrations-knowledge-base-integrations.html) with your bots.

### Content sources
You can create knowledge bases using a variety of content sources:

* Content management system (CMS)
* Google sheet
* CSV file

You can also start from scratch and author articles directly in a knowledge base.

#### Content management systems (CMS)
If you have a CMS with well-curated content that you want to leverage in bot conversations, you can [add an external knowledge base](knowledgeai-external-knowledge-bases-introduction.html). This is one where the content is authored and managed entirely within the external CMS application. Integrating with your CMS lets your content creators use familiar tools and workflows to author and manage the content. You can integrate with any CMS that has the capability, i.e., an API connector. Notable examples include Salesforce and Zendesk.

#### Google sheets
If your tool of choice is a simple Google sheet, you can [add an internal knowledge base](knowledgeai-internal-knowledge-bases-knowledge-bases.html) and link the sheet to it. Once you add the knowledge base using the sheet, you can follow one of two workflows:

* Add and update the articles in the linked Google sheet as needed, and then [sync the knowledge base](knowledgeai-internal-knowledge-bases-knowledge-bases.html#sync-with-a-google-sheet) to overwrite the knowledge base with the contents in the sheet.
* [Add](knowledgeai-internal-knowledge-bases-articles.html) and update the articles directly in the knowledge base as needed. They are editable within the UI to support this workflow. Sync plays no role in this workflow.

#### CSV files
If your tool of choice is a simple CSV sheet, you can [add an internal knowledge base](knowledgeai-internal-knowledge-bases-knowledge-bases.html) and import the contents of the CSV file when you do. The import is a one-time operation when you add the knowledge base. Thereafter, you add and update the articles directly in the knowledge base.

#### Starting from scratch
If you’re starting a knowledge base from scratch, and you prefer to work directly in the KnowledgeAI application, you can also do this. Simply [add an internal knowledge base](knowledgeai-internal-knowledge-bases-knowledge-bases.html) and start [adding articles](knowledgeai-internal-knowledge-bases-articles.html).

### Access KnowledgeAI

**To access the KnowledgeAI application**

1. On the left sidebar in Conversational Cloud, click the <img style="width:30px" src="img/ConvoBuilder/icon_cb.png"> icon.
2. In the Conversational AI dashboard, click **KnowledgeAI**.
