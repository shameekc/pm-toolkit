# Template: Press Releases for Product Companies

This file contains two distinct press release formats used by leading product companies. They serve different purposes and are used at different stages.

| | Amazon Style (PR/FAQ) | Google Style (Product Blog) |
|---|---|---|
| **When** | Before you build | When you ship |
| **Audience** | Internal stakeholders | External (customers, press, public) |
| **Purpose** | Validate the idea, align the org | Announce the launch, drive adoption |
| **Tone** | Formal, structured, problem-first | Narrative, conversational, vision-led |
| **Key feature** | FAQ section (internal + external) | Storytelling with feature deep-dives |
| **Length** | PR = 1 page; FAQ = 1-5 pages | 800-1500 words |

---

# Style 1: Amazon PR/FAQ ("Working Backwards")

## What It Is

An **internal** document written **before a single line of code**. You write a press release as if the product already launched, then work backwards through FAQs to clarify execution details. If the PR isn't compelling, don't build it.

> "Done correctly, the Working Backwards process is a huge amount of work, but it saves you even more work later. It's not designed to be easy — it's designed to save huge amounts of work on the back end, and to make sure we're actually building the right thing." — Jeff Bezos

## How It's Used

1. PM writes the PR/FAQ (1-2 days of deep thinking)
2. Team reads it silently in a "Narrative" meeting (first 20 min)
3. Group discussion follows — poking holes, raising concerns
4. PM iterates until the document is crisp and the idea is validated
5. Only then does development begin

## Template

```markdown
# [COMPANY] ANNOUNCES [PRODUCT/FEATURE] TO ENABLE [TARGET CUSTOMER] TO [KEY BENEFIT]

**[One-sentence subtitle that reframes the headline, adding specifics
about what's different or why now.]**

---

**[City, State] — [Intended Launch Date]**

[INTRO PARAGRAPH: 3-4 sentences. Expand on the solution. Name the target
customer. State the primary benefit. Describe what is launching at a high
level. This is the "elevator pitch" paragraph.]

[PROBLEM PARAGRAPH: Describe the top 2-3 customer problems in descending
order of pain. Write from the customer's perspective. Be specific about
the negative impact — time wasted, money lost, frustration caused. Do NOT
mention your solution here. Keep this paragraph 100% about the problem.]

[SOLUTION PARAGRAPH: Describe how the product solves each problem listed
above. Write a brief overview of how it works, then walk through each
problem and explain the fix. For existing products, clarify how this new
capability fits into the existing workflow.]

**[COMPANY LEADER QUOTE]**

"[A quote from a senior leader — ideally your manager's manager — explaining
why the company decided to tackle this problem and how the solution addresses
it. This builds organizational alignment because the quoted leader is now
implicitly sponsoring the idea.]"

— [Name], [Title], [Company]

**How It Works**

[Describe the step-by-step experience from the customer's perspective.
How do they discover it? How do they start using it? What happens next?
Write enough detail to convince readers it actually solves the problem.
Use numbered steps or bullets.]

1. [Step 1 — discovery / entry point]
2. [Step 2 — core experience]
3. [Step 3 — outcome / value delivered]

**[CUSTOMER QUOTE]**

"[A quote from a hypothetical but realistic customer. Choose a name and
company that represent your target persona. The quote should describe
their pain BEFORE the product, then the outcome AFTER. This implicitly
communicates your target market and total addressable market.]"

— [Name], [Title], [Company] ([size/type that signals TAM])

**Getting Started**

[One sentence on how customers can start using this today. Include a URL
or equivalent. This forces you to think about the actual onboarding path.]

Visit [URL] to get started.
```

### FAQ Section

The FAQ follows the PR on subsequent pages. Split into two categories:

```markdown
---

# Frequently Asked Questions

## Customer FAQs

**Q: How is this different from [competitor/alternative]?**
A: [Honest differentiation — what you do better, what trade-offs exist.]

**Q: How much does it cost?**
A: [Pricing model. If free, explain how. If paid, justify the value.]

**Q: Does this work with [existing tool/workflow]?**
A: [Integration and compatibility details.]

**Q: What happens to my data?**
A: [Privacy, security, and data handling.]

**Q: Can I try it before committing?**
A: [Free trial, freemium, demo — whatever the path to first experience is.]

[Add 3-5 more questions a real customer would ask.]

---

## Internal FAQs

**Q: What is the total addressable market (TAM)?**
A: [Market size with data sources. Who are the customers? How many?]

**Q: What are the unit economics / P&L projections?**
A: [Revenue model, margins, estimated CAC and LTV. Even rough estimates
force financial thinking early.]

**Q: What are the key dependencies?**
A: [Technical dependencies, team dependencies, partner dependencies.
What needs to be true for this to work?]

**Q: What is the estimated engineering effort?**
A: [Team size, timeline, key technical risks.]

**Q: What are the biggest risks?**
A: [Top 3-5 risks and how you'd mitigate each.]

**Q: How will we measure success?**
A: [Primary metric, secondary metrics, timeline to evaluate.]

**Q: What are we NOT doing?**
A: [Explicit scope boundaries. What's out of v1?]

**Q: Why now? Why not 6 months ago or 6 months from now?**
A: [Market timing, competitive pressure, technical readiness, team capacity.]

[Add questions stakeholders are likely to raise in review.]
```

---

## Amazon Style Example

# ACME ANNOUNCES SMART TEMPLATES TO HELP NEW TEAMS GET PRODUCTIVE IN 5 MINUTES

**Pre-built project structures eliminate the blank-screen problem, reducing time-to-value from 45 minutes to under 5 minutes for new users.**

---

**San Francisco, CA — March 2026**

Acme, the project management platform for growing teams, today announced Smart Templates, a library of pre-built project structures that get new teams productive in minutes instead of hours. Smart Templates are available to all Acme Pro and Enterprise customers at no additional cost, with an initial library of 12 templates spanning engineering, product, design, marketing, and operations workflows.

When a new team signs up for a project management tool, they face an empty workspace — no projects, no tasks, no structure. Research shows that 60% of new users who encounter this blank screen abandon the product within their first session. The average new user takes 45 minutes to manually set up their first project, and by that point, many have already given up and returned to spreadsheets or email. The problem isn't product quality — it's the cold start. Teams know they need better project management, but translating messy real-world workflows into a digital structure is surprisingly difficult.

Smart Templates solve the cold-start problem by offering pre-built project structures based on how real teams actually work. Instead of staring at a blank screen, new users choose from templates like "Sprint Planning," "Product Launch," or "Content Calendar" — each pre-populated with realistic tasks, smart defaults, and inline tips that explain the workflow. Unlike static templates that provide empty columns, Smart Templates include sample content that teaches the tool through doing.

"Our activation rate has been our biggest growth bottleneck. We've watched thousands of users sign up, stare at an empty workspace, and leave. Smart Templates attack this problem directly by giving every new team a running start."

— Sarah Chen, VP Product, Acme

**How It Works**

1. After signing up, users see a template picker: "Choose a template to get started" (or skip to create a blank project)
2. Select a template — the system creates a fully-structured project in under 60 seconds
3. Each task includes descriptions, tips, and suggested custom fields that teach the workflow
4. Users customize freely — rename, add, delete, rearrange. It's a starting point, not a constraint
5. Teams can save their customized projects as team templates for future use

"We used to lose half our new hires during onboarding because setting up their workspace took forever. With Smart Templates, they pick 'Engineering Sprint' and they're productive in 5 minutes. Our onboarding completion rate went from 45% to 85%."

— Jamie Torres, VP Engineering, GrowthLabs (180 employees)

**Getting Started**

Visit acme.com/templates to browse the template library and create your first project.

---

# Frequently Asked Questions

## Customer FAQs

**Q: How many templates are available?**
A: 12 at launch, covering sprint planning, product launch, hiring pipeline, content calendar, bug tracking, design sprint, OKR tracking, customer feedback, event planning, sales pipeline, marketing campaign, and team onboarding. We'll add more based on usage data and requests.

**Q: Can I create my own templates?**
A: Yes. Any project can be saved as a team template on Enterprise plans. Pro plan users can use the built-in library.

**Q: Will templates overwrite my existing projects?**
A: No. Templates create new projects. Your existing workspace is untouched.

## Internal FAQs

**Q: What is the TAM?**
A: 8,500 monthly signups × 60% who currently abandon = 5,100 users/month who would benefit. At $50/user/month average, recovering even 20% = $51K additional MRR.

**Q: Engineering effort?**
A: 3 sprints (6 weeks), 3 engineers. Template storage system, rendering logic, browsing UI, creation flow. Versioning deferred to v2.

**Q: Biggest risk?**
A: Paradox of choice — too many templates may overwhelm users. Mitigation: start with 5-7 in the picker, show full library only on demand. A/B test template count.

**Q: How will we measure success?**
A: Primary: Activation rate (45% → 60%). Secondary: Time to first task completion (45 min → 5 min). Evaluate at 30 days post-launch.

---

---

# Style 2: Google Product Blog Announcement

## What It Is

An **external-facing** narrative blog post published on launch day. Written in first person (by a product leader), it tells the story of why the product exists, demonstrates the features through real-world scenarios, and connects the launch to the company's broader vision. Less structured than Amazon's format — more storytelling, more "show don't tell."

## How It's Used

1. Published on the company blog on launch day
2. Sent to press alongside an embargo briefing
3. Syndicated to social media, newsletters, and partner channels
4. Serves as the canonical reference for what shipped and why

## Template

```markdown
# [Benefit-Driven Headline — What This Means for Users]

**Author:** [Name], [Title — e.g., VP Product, Chief Product Officer]
**Date:** [Publication date]

---

[OPENING PARAGRAPH: 2-3 sentences. Announce what's launching and
immediately frame the user benefit. Connect to a broader trend or
mission. Set the tone — conversational, confident, forward-looking.]

## [The Problem, Framed as a Story]

[1-2 paragraphs. Tell the story of the problem from the user's perspective.
Use a specific scenario — "Imagine you're a PM who just joined a new team..."
Include data if you have it, but lead with narrative. Make the reader nod
and think "yes, that's me."]

## [The Solution — Benefit-Led Subheading, Not Feature Name]

[1-2 paragraphs introducing the solution. Explain what it does through
the lens of the scenario you just described. Show the before/after.
Keep it conversational — "Now, instead of X, you can Y."]

## [Feature Deep-Dive Section 1 — Benefit-Led Subheading]

[Describe the first key capability. Lead with what it enables, then
explain how it works. Include a specific example or scenario.
Placeholder for screenshot or demo GIF.]

*[Screenshot/GIF placeholder: show the feature in action]*

## [Feature Deep-Dive Section 2 — Benefit-Led Subheading]

[Second capability. Same pattern — benefit first, then mechanism.
Different scenario to show breadth.]

*[Screenshot/GIF placeholder]*

## [Feature Deep-Dive Section 3 — Benefit-Led Subheading]

[Third capability. If relevant, include a data point or benchmark
— "In beta, teams using X completed projects 40% faster."]

## What Our Customers Are Saying

[1-2 real customer quotes from beta or early access. Include name,
title, company. The quotes should describe a specific before/after,
not generic praise.]

> "[Specific quote about their experience — the problem they had
> and how the product solved it.]"
>
> — [Name], [Title], [Company]

## What's Next

[1-2 paragraphs on the roadmap and vision. What are you building next?
How does this launch fit into the bigger picture? This signals ambition
and gives readers a reason to stay engaged.]

## Get Started

[Product/Feature] is available [today / starting date] for [audience].
[Pricing details — free, included, new plan, etc.]

[CTA button text: "Try it now" / "Learn more" / "Get started free"]

→ [URL]

---

*[Author bio: 1-2 sentences about the author and their role.]*
```

---

## Google Style Example

# Smart Templates: Get Your Team Productive in 5 Minutes, Not 45

**Author:** Sarah Chen, VP Product
**Date:** March 15, 2026

---

Today we're launching Smart Templates — a library of pre-built project structures that eliminate the dreaded blank-screen problem for new teams. It's the fastest way to go from "we just signed up" to "we're actually getting work done."

## The Blank Screen Problem

Here's a scenario every PM knows: your team decides to adopt a new project management tool. Everyone's excited. You sign up, invite the team, and then... you're staring at an empty workspace. No projects. No tasks. No structure. Just a blinking cursor and a vague sense of "now what?"

We've watched this play out thousands of times. Our data shows that 60% of new users who hit this blank screen never come back. The average first-project setup takes 45 minutes — longer than most people's patience for a tool they haven't committed to yet. The problem was never our product. It was the cold start.

## Start with Structure, Make It Yours

Smart Templates flip the onboarding experience. Instead of building from scratch, you pick a template — "Sprint Planning," "Product Launch," "Content Calendar" — and get a fully-structured project in under 60 seconds. But these aren't empty shells. Every template comes pre-populated with realistic tasks, descriptions, and inline tips that teach you the workflow as you use it.

The key insight: people learn tools by *doing*, not by reading documentation. So we built templates that double as interactive guides.

## Real Tasks, Not Placeholder Text

Most template libraries give you column headers and empty cards. Ours include actual sample tasks — with descriptions that explain *why* the template is structured this way.

Pick "Sprint Planning" and you'll see tasks like "Write sprint goals" (with a description explaining what good sprint goals look like), "Groom backlog" (with tips on estimation), and "Schedule retro" (with a suggested agenda). You're learning best practices while setting up your project.

*[Screenshot: Sprint Planning template with sample tasks and inline tips]*

## Your Team's Workflows, Saved and Shared

Once you've customized a template to fit your team's actual process, save it. Your "Engineering Sprint — Our Way" template becomes available to everyone on your team. New hires pick it up on day one and they're set up exactly the way your team works.

Enterprise customers are already using this to standardize workflows across departments — one team perfects a process, saves it as a template, and rolls it out to 50 others.

*[Screenshot: Saving a custom team template]*

## The Numbers from Beta

We've been testing Smart Templates with 200 teams over the past 6 weeks. The results:

- **Time to first task completion:** 45 minutes → 4.5 minutes (90% reduction)
- **Activation rate:** 45% → 78% (33 percentage point lift)
- **Week-1 retention:** 52% → 71% for teams that started with a template

## What Our Customers Are Saying

> "We onboard 10-15 new engineers a quarter. Before Smart Templates, each one needed a 30-minute walkthrough just to set up their workspace. Now they pick 'Engineering Sprint,' and they're contributing on day one. It's saved our team leads hours every month."
>
> — Jamie Torres, VP Engineering, GrowthLabs

> "I tried three different PM tools last year and abandoned all of them because setup was too painful. Smart Templates is the reason I actually stuck with Acme. I picked 'Content Calendar,' tweaked a few things, and I was running my editorial process in 10 minutes."
>
> — Priya Sharma, Content Lead, NovaBrand

## What's Next

Smart Templates is just the beginning of our investment in time-to-value. Over the coming months, we'll be adding AI-powered template suggestions (based on your team size, industry, and workflow patterns), community-contributed templates, and cross-project template dependencies for teams managing complex programs.

Our goal: zero time between "I signed up" and "I'm getting value."

## Get Started

Smart Templates are available today for all Acme Pro and Enterprise customers at no additional cost. The initial library includes 12 templates across engineering, product, design, marketing, and operations.

→ Browse templates at acme.com/templates

---

*Sarah Chen is VP Product at Acme, where she leads product strategy and the platform team. Previously, she was a PM at Stripe and Notion.*

---

---

# Instructions & Best Practices

## General Principles (Both Styles)

1. **Start with the customer, not the product.** The problem section should make readers nod before you ever mention your solution.

2. **Write at an 8th-grade reading level.** If your grandmother can't understand it, it's too jargony.

3. **One announcement per press release.** Don't bundle multiple features.

4. **The headline is a benefit, not a feature.** "Smart Templates Help Teams Get Productive in 5 Minutes" — not "Acme Launches Template Library v2.0."

5. **Customer quotes > executive quotes.** The customer quote is the most important part. It should describe a specific before/after.

6. **Include real numbers.** Specifics are persuasive; generalities are forgettable.

## When to Use Which Style

| Situation | Use |
|-----------|-----|
| Evaluating whether to build a feature | Amazon PR/FAQ |
| Aligning stakeholders on a product idea | Amazon PR/FAQ |
| Getting executive buy-in for resourcing | Amazon PR/FAQ |
| Announcing a shipped feature externally | Google Product Blog |
| Briefing press or analysts | Google Product Blog |
| Creating launch content for marketing | Google Product Blog |
| Writing both (ideal) | Amazon PR/FAQ first → Google Blog at launch |

## The Ideal Flow

```
Amazon PR/FAQ (before build)
    → validates idea, aligns org, surfaces risks
    → product gets built
    → beta feedback refines the story
Google Product Blog (at launch)
    → reuses the problem/solution framing from the PR/FAQ
    → adds real customer quotes from beta
    → includes screenshots, data, and "what's next"
```

---

# Using AI to Generate Press Releases

### Amazon PR/FAQ (before building)

```
Using @press-release.md Style 1 (Amazon PR/FAQ), write an internal
press release for [feature/product] as if it already launched.

Here's what I know:
- Target user: [who]
- Problem: [pain point with evidence]
- Proposed solution: [high-level approach]
- Key differentiator: [why ours is different]
- Expected impact: [metric we want to move]

Include the full FAQ section with both customer FAQs and internal FAQs
(TAM, engineering effort, risks, success metrics, scope boundaries).
```

### Google Product Blog (at launch)

```
Using @press-release.md Style 2 (Google Product Blog), write an external
launch announcement for [feature].

Use data from @[experiment-readout].md and these beta customer quotes:
- "[Quote 1]" — [Name, Title, Company]
- "[Quote 2]" — [Name, Title, Company]

Write it in first person as [author name, title]. Include benefit-led
subheadings, a "What's Next" section, and a clear CTA.
```

### Convert Amazon PR/FAQ → Google Blog Post

```
I have an internal Amazon-style PR/FAQ: @[prfaq-doc].md

Convert it into a Google-style product blog announcement. Keep the
problem/solution framing but shift to narrative storytelling. Replace
hypothetical customer quotes with these real ones from beta:
- "[Quote]" — [Name, Title, Company]

Add a "What's Next" section and a CTA.
```

### Stress-test a PR/FAQ

```
Review my Amazon PR/FAQ: @[prfaq-doc].md

Evaluate it on these criteria:
1. Is the problem compelling enough that someone would stop reading
   and share it?
2. Is the solution clearly differentiated from alternatives?
3. Does the customer quote feel real?
4. Are the internal FAQs honest about risks?
5. Would you greenlight this for development? Why or why not?

Be brutally honest. Suggest a stronger headline if mine is weak.
```
