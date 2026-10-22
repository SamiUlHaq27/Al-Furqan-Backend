# Project Plan

**Al-Furqan** addresses this by establishing a reality-synthesis platform governed by formal logic and evidence-based verification.

By enforcing hierarchical stance partitioning (Pro, Con, and Context), automated pre-ingestion triage (link validation, toxicity filtering, and semantic relevance scoring), and dynamic, trust-weighted voting algorithms, Al-Furqan replaces chaotic comment threads with structured, auditable knowledge trees that surface objective truth for public matters and private enterprise decision-making alike.

### Challenge 1: Safe speech

- **Problem:** Some users may post hateful and abusive comments. It will cause bad user experience.
- **Solution:** Use AI and word matching techniques to identify speech violation and block such posts.
  - Allow users to report as abusive also. It will be then manually reviewed by a person and handled.
- **Status:** Pending for implementation

### Challenge 2: Personal targeting

- **Problem:** Some users may try to target non-public entities which may result in bad reputation of the system. As the data is going to be public such records for any private individual could cause issues.
- **Solution:** Use well established knowledge platform like Google Knowledge Graph to ensure if targeted personality is public.
- **Status:** Under consideration because many popular social media platforms also do not restrict posting against non public personalities.

### Challenge 3: Maintaining clean knowledge base

- **Problem:** For discussing a topic whether something is good or bad, something was real or not there might be internal sub topics which could define the final result. There could also be other discussion linked to it. It is crucial to maintain a clean structure for getting the final result about something.
- **Solution:** The core of the system is discussion.
  - Take it as a general no matter an event or personality or a statement. 
  - Make sure to include a clear question and possible options if available. 
  - Allow users to tag or link other discussions while discussing something. It will highlight if discussions are related and their results could be used to get final answer for current discussion.
- **Status:** Under progress

### Challenge 4: Spamming

- **Problem:** Some users might try to exploit system by adding unnecessary comments/discussions or too many comments.
- **Solution:** Allow only limited comments/discussions per hour or per day so users seriously write and comment. Provide comment edit feature but record the history as well.
  - Warn and block users on repeated attempts.
  - Allow Other users to report as spam
- **Status:** Under progress

### Challenge 5: Irrelevant comments/discussions

- **Problem:** Some users might try to exploit system by posting irrelevant data that would be bad for decision making and user experience.
- **Solution:** Use semantic analysis to check if comment or discussion is on the topic and sensible and not just random text.
  - Warn and block users on repeated attempts.
  - Allow Other users to report as spam
- **Status:** Under progress

### Challenge 6: Providing clean interface

- **Problem:** Too much comments and data will make the system look alike traditional social media platforms and forums. User will see distributed detail in comments
- **Solution:** Instead of regular comments allow users to select for possible options or custom option if provided.
  - Group the comments, arguments and evidences with respect to those options. Show the list of arguments with people who posted. If an argument is posted by multiple people combine using AI.
  - Show evidences and up votes or down votes.
  - Instead of repeating something allow users to up vote or down vote something.
  - Show counter arguments and arguments for other options like the same way beneath it.
  - If there are matching arguments only count unique users up vote
  - Allow users to show or hide themselves in up votes or down votes
  - Finally provide a summary of what arguments were given under which evidences and what are counter arguments and how many people are supporting that argument.
- **Status:** Under progress

### Challenge 7: Waiting time for content quality checking

- **Problem:** As the comments and discussions have to be checked before going live there would be waiting time.
- **Solution:** Use queue based approaches to check data quality and taking heavy loads. Use approval and quality statuses to ensure only top quality data is going to the users.
- **Status:** Under progress

### Challenge 8: Know your user
- **Problem:** Some people might try creating multiple accounts using temporary or fake credentials causing invalid voting results and overall public analysis.
- **Solution:** Use device fingerprinting and frequent account verifications to ensure one user one person.
- **Status:** Under progress