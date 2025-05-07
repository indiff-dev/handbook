+++
date = '2025-04-08T21:52:07+09:00'
title = 'Problem Discovery'
author = ['Kento Maruyama']
weight = 10
+++

This page defines the problem domain that we aim to address. It outlines the challenges that our final product is designed to solve and verifies whether these problems truly exist in the market and cause significant pain to the target audience. Problem Discovery is the phase where we identify and validate these problems.

Key Steps in Problem Discovery

1. Problem Identification and Hypothesis Formation
2. Persona Definition
3. Problem Hypothesis Validation

---

## Problem Hypothesis

We have formulated the following hypothesis based on our observations of many software development teams:

> **Many development teams struggle to reflect user needs and feedback in their products, preventing them from building products that people are willing to pay for – and keep paying for – over time.**
> 
> **There is often a weak connection, low engagement, and insufficient communication between development teams and their users.**

This lack of connection leads to several critical issues for development teams:

- Inability to decide which features to prioritize and build
- Lack of insight into how implemented features are actually being used, making it difficult to plan meaningful improvements
- Failure to reach Product-Market Fit (PMF), as their products fail to deliver enough value for users to pay for them and perceive them as worth the price

We have established this as the primary problem to address moving forward. Solutions and products that fall outside this problem scope will not be included in our efforts. We will dive deeper into this hypothesis during the Problem-Solution Fit phase.

> {{< collapse summary="Problem Discovery Process" >}}

### 1. Initial Market and Problem Exploration

We began by interviewing a few developer friends to understand the market and uncover potential problems. We asked the following questions to gain insight into their pain points:

- Are you satisfied with your work as part of a development team?
- Can you share a recent situation at work that you found particularly stressful?

**We spoke with three individuals, all of whom reported being generally satisfied with their work.** While they did share some stressful experiences, their responses lacked consistency and common themes, making it challenging to draw meaningful conclusions. We realized that this approach would not effectively reveal the core problems we were seeking.

---

### 2. Reflecting on Personal Experience

Next, we turned the same questions inward, conducting a self-assessment to identify our own frustrations.
The results were as follows:

- Dissatisfaction with work as part of a team
- Significant stress from **seeing a product I had invested considerable time and effort into go completely unused** (at that time, I was not in a position to influence major product decisions, and I was doing the best I could as an engineer)

Upon further analysis, we identified the following potential reasons for this frustration:

- **Lack of thorough user validation and market testing in the early stages of product development**

---

### 3. Reassessing Market Fit and Problem Scope

In Japan, deep conversations with users are often not part of the standard development culture. This led us to question **whether most development teams are even engaging with their users in a meaningful way.**
To test this, we adjusted our interview approach as follows and conducted another round of conversations:

- Have you recently experienced any tasks or processes in your development work that felt cumbersome or unnecessarily complicated?
- **How confident are you that you are building what your users truly want?**
- **Do you have any thoughts about the direction of your product or decision-making within your team?**

From interviews with two additional individuals, we gathered the following insights:

- Those working at startups expressed confidence in building what their users wanted, while those at larger companies felt uncertain.
- Even those at startups admitted to not fully understanding how their features were being used.
- Neither respondent said they always had a clear understanding of which features to build next.

From this and our own past experiences, we began to suspect that a deeper, more systemic disconnect exists between development teams and their users. This hypothesis became the foundation for our further problem analysis.

---

### 4. Difficulty Reaching Target Users in Japan

To deepen our understanding of this problem, we attempted to gather insights from additional developers beyond the two we had already interviewed.
Specifically, we aimed to connect with developers at startups and venture companies, who were not within our immediate network of friends or acquaintances. However, our attempts to reach these target users faced significant challenges:

1. Direct Messaging on X (formerly Twitter) and LinkedIn
    - **Most people had disabled their DM functionality,** making outreach nearly impossible.
2. Contacting Recently Funded Startups via Corporate Websites
    - Many contact forms on corporate websites **explicitly prohibit use for purposes like survey requests,** making this approach ethically questionable or outright against their terms.
3. Networking at Tech Events
    - While we tried attending tech events and networking sessions to naturally meet potential users, it proved inefficient. Establishing meaningful connections often required attending multiple events, and the probability of encountering high-value users was low.
    - **The time investment and cost were disproportionate to the potential benefit.**

From these attempts, we learned the following:

- **Connecting with target users can be extremely time-consuming and labor-intensive.**

---

### 5. Weak Connections Between Development Teams and Users

To overcome this, we considered alternative approaches to reaching our target users:

- Posting on platforms like Medium to share our findings and attract developers who sense similar challenges. We included links to our Slack community to encourage more direct and frequent interactions.
- Hosting our own events where developers could gather, fostering a more engaged community that we could directly connect with.

However, as we experimented with building a Slack community, we discovered several additional challenges:

- It might be possible to attract users, but sustaining close, passionate engagement over time **requires significant effort:**
    - Users need to feel a deep sense of ownership and participation, as if they are co-creating the product.
    - An incentive structure must be in place to motivate ongoing collaboration.
    - For those not accustomed to using Slack, additional communication methods like LINE or email might be needed to keep them engaged.
    - Effective community management is essential to create a psychologically safe space where everyone feels comfortable sharing ideas, regardless of group size.

From this, we realized that even after successfully connecting with users, maintaining meaningful relationships requires ongoing effort and thoughtful management. To truly enable development teams to create convenient and cool products, we need more than just user voices – we need deep, continuous collaboration.

This led us to the realization that the following development approach might be essential:

- **A community-driven, co-creative approach where development teams and users function as a single, unified team.**

We began to think that this approach, similar to open-source projects where users actively open issues and contribute feedback, could be the key to building truly impactful products. This became our new working hypothesis, which we decided to validate further in the next phase.

{{</ collapse >}}

---

## Persona Definition

We have identified the following persona as our initial target user:

> Our target persona is a decision-maker (CEO, CTO, Tech-Lead Manager, Tech-Lead, or Manager) within a development team at a startup company providing web-based SaaS. These companies are typically in the phase between MVP development and achieving Product-Market Fit (PMF), and they feel significant challenges in maintaining connections, relationships, and engagement between the development team and users.

> {{< collapse summary="Detailed Persona" >}}

### Company Type

**Companies that provide web-based SaaS. While we primarily target startups and venture companies, we also include larger enterprises.**

We chose web-based SaaS companies because we can leverage our existing knowledge in this domain.
Startups and venture companies are our primary focus because they tend to have a faster decision-making process when it comes to adoption.

### Industry

**Prioritizing B2C over B2B.**
We focus on B2C because building relationships with users is inherently more challenging and perceived as a bigger problem compared to B2B.

### Development Team Phase

**Targeting development teams that are in the phase from MVP development to achieving PMF.**
These teams have the highest need for stronger connections, relationships, and engagement with their users.

### Key Individuals to Approach

**Focusing on individuals who play a critical role in decision-making and product adoption within the team.**

- CEO or CTO
- Tech-Lead Manager, Tech-Lead, or Manager within the development team

### Level of Problem Awareness

We specifically target those who **feel a medium to high level of pain** related to weak connections, relationships, and engagement with their users.

{{</ collapse >}}

---

## Problem Hypothesis Validation

To validate whether a problem hypothesis is a "clearly existing" and "painful" problem in the market, we look for the following three indicators:

- We can extract multiple "specific episodes" and "emotional pain" from different users.
- There is evidence that users are either "already taking action" to address the problem or have "attempted to solve it unsuccessfully."
- The problem is clearly influencing "decision-making and actions."

If the hypothesis scores 7 or more points on the following checklist, it is ready to move to the Problem-Solution Fit phase.

Validation Criteria | Standard | Score
| --- | --- | ---
Emotional Pain | Clear episodes + well-expressed emotions | 3
Evidence of Action | Clear evidence of attempts to address the problem | 3
Impact on Decision-Making | Influences at least one management, product, or implementation decision | 3
Total Score | 7 or more out of 9 points indicates a genuine problem | –

> {{< collapse summary="Further Details on the 3 Key Indicators" >}}

### 1. Extracting "Specific Episodes" and "Emotional Pain" from Multiple Users

- Are users sharing concrete stories of "failures" or "losses" rather than just vague complaints about being "frustrated"?
- Are these experiences not isolated incidents but shared by multiple people?
- Do they clearly remember the emotions (e.g., frustration, confusion, sadness, fear) they felt at the time?

Example:

*"We released a feature without consulting our users, and retention rates plummeted. The sales team got angry, and it killed the team's morale."*

### 2. Evidence that Users are "Already Taking Action" or "Have Tried and Failed" to Solve the Problem

- Are users already trying to address the problem through their own creative workarounds? (e.g., creating user groups in Slack, logging feedback in Notion)
- Do they admit that these solutions are either "not satisfying" or "not working well"?

Example:

*"We've been logging user feedback in Notion, but we never actually go back to review it, so it's just become a pointless ritual..."*

### 3. Evidence that the Problem is "Impacting Decision-Making or Actions"

- Is this problem causing misalignment in the team’s direction, development mistakes, or poor prioritization decisions?
- Are they explicitly saying, "We can't do X because of this problem"?

Example:

*"Because we don't really understand what our users want, we can't decide which feature to build next. We just end up going with whatever our boss decides."*

{{</ collapse >}}

---

## Problem Validation Process

To validate our problem hypothesis, we planned the following steps to engage in meaningful conversations with as many target users as possible:

1. Establish contact with users who fit our persona and resonate with the problem.
2. Conduct interviews to confirm the three key criteria for problem validation.

Our initial goal was to speak with 30 target users.
For user outreach, we adopted a content-driven approach, aiming to attract users through posts that share relatable stories about the problem.

> {{< collapse summary="Detailed Strategy" >}}

### 1. Establishing Contact with Target Users

To reach potential target users, we chose to publish highly relatable stories on platforms like Medium. These posts aim to resonate deeply with our target personas and encourage them to reach out via the contact information or comments provided in the posts. We drew inspiration from content like [Rahul Vohra's post on Superhuman](https://medium.com/swlh/rip-mailbox-or-founders-how-to-stop-worrying-and-love-being-acquired-261da4f6d566) to craft our messaging.

---

### 2. Conducting Interviews and Confirming the 3 Key Criteria

First, verify that the person you are speaking with fits the target persona:

> - Can you tell me about the product you are currently developing?
> - What stage is your product in? Has it been officially released?
> - What is your role within the development team, and what type of company do you work for?

If the person fits the target persona, proceed to schedule an interview. Clearly explain the background, purpose, and key questions you plan to cover:

> I believe that many development teams today face the "challenge of weak connections with their users."
> This distance between developers and users can lead to the following issues:
>
> - Teams struggle to decide which features to build for their users.
> - Products fail to grow into PMF-achieving solutions.
>
> I am confident that a product capable of solving this problem could be a significant growth opportunity for your product as well!
> I would love to spend about 30 minutes discussing this topic with you. Here are some of the key things I would like to understand:
>
> - Are you currently building a feedback loop with your users? How do you incorporate user feedback into your product?
> - Are you dissatisfied with your current feedback loop? Have you ever tried to change it?
> - How much impact do user voices and feedback have on your company and team? Please answer with High, Medium, or Low for the following levels:
>     - Company-Level: Overall goals, business strategy, or management decisions (CEO, CTO level)
>     - Product-Level: Product direction, roadmap, or development plans (Tech-Lead Manager, Tech-Lead, or Manager level)
>     - Team-Level: UI/UX, design choices, or detailed implementation decisions (engineers or designers)

Follow this script to guide the conversation and aim to uncover the following critical insights:

- "Specific episodes" of problems caused by the lack of user connection, along with the "emotional pain" these incidents caused.
- Evidence that the user has "already taken action" to address the problem, or has "tried and failed" to resolve it.
- Clear understanding of how this problem "impacts decision-making and actions" within the organization.

Achieving these goals will confirm whether the "weak connections between development teams and their users" problem meets the following criteria:

- It clearly exists in the market and represents a significant pain point for users.
- It is a problem that cannot be easily solved or satisfactorily addressed by existing solutions.
- It significantly impacts multiple levels within an organization, from executives to frontline team members.

Only when all three of these points are confirmed can we consider this a validated problem worth pursuing.

{{</ collapse >}}

---

## Validation Results

The final score was 6.5 out of 9 points:

- Emotional Pain: 1.5
- Evidence of Action: 3
- Impact on Decision-Making: 2

From this, we concluded that the problem is not strongly felt by most development teams, making it a **"pain without awareness" type of problem.** Despite this, based on our conversations and personal experiences, we remain convinced that this problem has a significant impact on both development teams and their products. In essence, this is a "problem that is troubling, but not obviously troubling."

With this assessment, we decided to move to the Problem-Solution Fit phase for this problem. We plan to build a "Problem Awareness" mock-up to further validate whether this is a genuine pain point for users. Through this, we aim to confirm whether this problem is truly significant or simply an unnoticed obstacle before committing further resources.

> {{< collapse summary="Validation Process" >}}

### 1. Establishing Contact with Problem-Aware Users

We attempted a post-driven validation approach by publishing articles that share our problem hypothesis on [Zenn](https://zenn.dev/sakanate/articles/9a87f93f79df05) and [note](https://note.com/sakanate/n/n8b4c1323036c).
The results were disappointing:

- The articles received very few views, as our target persona likely never had the chance to see them.
- The engagement was minimal, with just 2 likes per day and 0 comments over several days.

We didn't consider the quality of our posts to be particularly poor, as we had sought direct feedback from ChatGPT and friends before publishing. However, Zenn has a high posting volume, causing new articles to quickly become buried within 2 hours of being published, making them nearly impossible to find.

Despite making a strong push for comments – even providing clear guidance on what kind of comments we hoped to receive – the posts still received 0 comments. This reinforced our suspicion that Zenn lacks a strong commenting culture, making it more of a "read-only" platform, and thus unsuitable for validating deep, nuanced problem hypotheses.

Given these challenges, we decided to pivot our approach to include:

- Publishing English versions on Medium
- Exploring threads on Indie Hackers, ProductHunt, and Reddit

However, we identified several concerns with this approach, leading us to prioritize building an MVP for Problem Awareness as a more direct method of validation:

- Many users on these platforms are English speakers, potentially creating a language barrier during deeper interviews.
- It is difficult to obtain contact information or secure follow-up interviews through thread-based discussions.
- Many founders in these communities tend to take a "Build First" approach, which we felt might downplay the importance of validating problem hypotheses.

---

### 2. Conducting User Conversations to Confirm Problem Validation Goals

Although we struggled to reach a large number of potential users, we did manage to have initial conversations with 3 individuals from our network who closely fit our target persona. Below is a brief summary of our findings:

> **Specific Episodes of Problems and Emotional Pain**

- Person A did not express a strong sense of pain related to the problem.
- Person B shared a specific episode along with strong emotional pain.
- Person C also did not express a strong sense of pain related to the problem.

**Key Insights:**

- Teams building products before achieving PMF were more likely to resonate with the problem, while those after PMF felt less connected to the issue.
- None of the 3 individuals expressed a clearly strong awareness of the problem. They acknowledged it as a challenge, but with a "maybe, but not really" attitude.
- 2 of the individuals followed a "Build First" approach, while 1 followed a "Lean Startup" approach.
- When asked if they had certainty or confidence that their users truly wanted the features they were building, all 3 responded that they "release it to find out."

> **Evidence of Previous Attempts to Solve the Problem**

- All 3 individuals indicated that they were already taking action to address the problem and felt that their current approach was "working well."

**Key Concern:**

- Despite claiming that their approaches were working, they still admitted, "We don't know for sure, so we just release it to find out."

> **Impact on Decision-Making and Actions**

- All 3 individuals indicated that the problem primarily impacts decision-making at the team leader and engineer levels.
- However, they also suggested that it has at least some influence at the executive level as well.

{{</ collapse >}}

---