In this document, you will discover below:


*   [Heading Color Codes](#TechnicalWritingSampleDocument-HeadingColorCodes)
*   [Active Voice vs. Passive Voice](#TechnicalWritingSampleDocument-ActiveVoicevs.PassiveVoice)
*   [Clear Sentences](#TechnicalWritingSampleDocument-ClearSentences)
*   [Think Like Your Audience](#TechnicalWritingSampleDocument-ThinkLikeYourAudience)
*   [Forbidden Words](#TechnicalWritingSampleDocument-ForbiddenWords)
*   [Right Sentences](#TechnicalWritingSampleDocument-RightSentences)
*   [Read it Out Loud](#TechnicalWritingSampleDocument-ReaditOutLoud)
*   [Come Back to it Later](#TechnicalWritingSampleDocument-ComeBacktoitLater)
*   [Tell Your Story](#TechnicalWritingSampleDocument-TellYourStory)
*   [Introduce a Document](#TechnicalWritingSampleDocument-IntroduceaDocument)
*   [Add Navigation](#TechnicalWritingSampleDocument-AddNavigation)
*   [Attract With Pictures](#TechnicalWritingSampleDocument-AttractWithPictures)
*   [Constrain the Amount of Information in a Single Drawing](#TechnicalWritingSampleDocument-ConstraintheAmountofInformationinaSingleDrawing)
*   [Illustration Tools](#TechnicalWritingSampleDocument-IllustrationTools)
*   [Creating Sample Code](#TechnicalWritingSampleDocument-CreatingSampleCode)
*   [Summary](#TechnicalWritingSampleDocument-Summary)

Heading Color Codes
===================

Below are the heading colors that should be used on technical documents.

**Heading 1** – Dark Gray

**Heading 2** – Dark Blue

**Heading 3** – Dark Purple

**Heading 4** – Dark Teal

Active Voice vs. Passive Voice
==============================

Below, some examples that describe the difference between Active and Passive Voice. Always try to use Active ones.

|     |     |
| --- | --- |
| **Active** | **Passive** |
| We are going to watch a movie tonight. | A movie is going to be watched by us tonight. |
| Mom read the novel in one day. | The novel was read by Mom in one day. |
| I will clean the house every Saturday. | The house will be cleaned by me every Saturday. |

Clear Sentences
===============

Make sure that you always stick to the point with clear and understandable.

*   Place conditional clauses before an instruction rather than after. [\[MORE\]](https://developers.google.com/style/clause-order)
    
    *   If you want to tell the reader to do something, try to mention the circumstance or goal before providing the instruction. Mentioning the circumstance first lets the reader skip the instruction if it doesn't apply.
        
*   Format code-related text as code font or put the code into the code section like below:
    
    *   ```
        #This code is not doing anything!
        ```
        

Think Like Your Audience
========================

Who is your audience? Step back and try to read your draft from their point of view. Make sure the purpose of your document is clear, and provide definitions for any terms or concepts that might be unfamiliar to your readers.

Forbidden Words
===============

Using the below words in technical documents is not allowed:

*   Would – revise the sentence to have present simple
    
*   Should – always use instead: must; need
    
*   Will – write in present simple
    
*   Could – use instead: can
    
*   So – use instead: thus
    

Right Sentences
===============

|     |     |
| --- | --- |
| **Wrong** | **Right** |
| Should be like below | Must appear as |
| Should have | Need, Must |
| Contents should be like | Contents must be displayed as shown |

Read it Out Loud
================

To check your writing is conversational, read it out loud. Listen for awkward phrasing, too-long sentences, or anything else that doesn't feel natural. Alternatively, consider using a screen reader to voice the content for you.

You may download [Screen Reader for Google Chrome](https://chrome.google.com/webstore/detail/screen-reader/).

Come Back to it Later
=====================

After you write your first draft (or second or third), set it aside. Then, come back to it after an hour (or two or three) and try to read it with fresh eyes. You'll almost always notice something that you could improve.

Tell Your Story
===============

Your reader probably doesn't need to know (or want to know) about the history of the project in the introductory sections of your document when they're just getting started with the basics. However, if you feel the project's history is useful, include a link to this type of information at the end of your document.

Introduce a Document
====================

If readers of your documentation can't find relevance in the subject, they are likely to ignore it. Therefore, to set the ground rules for your users, we recommend providing an introduction that includes the following information:

*   What the document covers.
    
*   What prior knowledge you expect readers to have.
    
*   What the document doesn't cover.
    

> Remember that you want to keep your documentation easy to maintain, so don't try to cover everything in the introduction.

Add Navigation
==============

Providing navigation and signposting for your readers ensures they can find what they are looking for and the information they need to get unstuck.

Clear navigation includes:

*   introduction and summary sections
    
*   a clear, logical development of the subject
    
*   headings and subheadings that help users understand the subject
    
*   a table of contents menu that shows users where they are in the document
    
*   links to related resources or more in-depth information
    
*   links to what to learn next
    

Attract With Pictures
=====================

Viewing illustrations was so much more fun than reading text. In fact, when it comes to reading technical material, the vast majority of adults are still little kids—still yearning for pictures rather than text.

![Sleepy fox is sleeping.](https://ucraft.atlassian.net/wiki/download/attachments/2083880961/FvOCR3MRCI0r_QV8MqwocEw9AAdJV0uwoisXVlsrGIU.jpg?api=v2)

Constrain the Amount of Information in a Single Drawing
=======================================================

By contrast, highly complex technical illustrations like the following tend to discourage most readers.

Below diagram was drawn by [Ehsan Soltani Azad](https://ucraft.atlassian.net/wiki/people/5ffe9e24208dbf0107f0c8d4?ref=confluence) to demonstrate the architecture of the “Wallet Application”:

![](https://ucraft.atlassian.net/wiki/download/attachments/2083880961/GetImage.png?api=v2)

Describe project phases with a Roadmap diagram to simplify steps with illustration rather than writing long paragraphs or bullet points.

![](/wiki/plugins/servlet/roadmap/image/2083880961/22/8b9be2f07ca9fb3eb57c7ae3ee6c5f79.png)

Illustration Tools
==================

There are many options available for creating diagrams. Three options that are free or have free options include:

*   [Google Drawings](https://drawings.google.com/)
    
*   [http://diagrams.net](http://diagrams.net) (Recommended when using Confluence)
    
*   [LucidChart](https://www.lucidchart.com/pages/)
    

When exporting diagrams from these tools to use in documentation, it is usually best to export the files as [Scalable Vector Graphics](https://wikipedia.org/wiki/Scalable_Vector_Graphics) (SVG). This is because the SVG format easily scales diagrams based on space constraints so that no matter the size, you end up with a high-quality image.

Creating Sample Code
====================

Good sample code is often the best documentation. Even if your paragraphs and lists are as clear as blue water, programmers still prefer good sample code. After all, text and code are different languages, and it is code that the reader ultimately cares about. Trying to describe code with text is like trying to explain an Italian poem in English.

Good samples are **correct** and **concise** code that your readers can **quickly understand** and **easily reuse** with **minimal side effects**.  

Below is a sample [YAML](https://en.wikipedia.org/wiki/YAML) file to deploy [Redis](https://redis.io/) Server in the [Kubernetes](https://kubernetes.io/) environment.

```
apiVersion: apps/v1
kind: StatefulSet
metadata:
  name: redis
  namespace: hoory
spec:
  serviceName: redis
  selector:
    matchLabels:
      app: redis
  template:
    metadata:
      labels:
        app: redis
    spec:
      containers:
        - name: redis
          image: redis:alpine
          env:
            - name: REDIS_PASSWORD
              value: admin
          ports:
            - containerPort: 6379
          args:
            - --requirepass
            - $(REDIS_PASSWORD)
```

Summary
=======

This document has been created with the help of [Technical Writing Courses](https://developers.google.com/tech-writing/) from Google Developers. Some of the contents have been modified and localized for UCRAFT. This document is [Ehsan Soltani Azad](https://ucraft.atlassian.net/wiki/people/5ffe9e24208dbf0107f0c8d4?ref=confluence) first practice to create clear writing style practice. Feel free to use it in your own favor.
