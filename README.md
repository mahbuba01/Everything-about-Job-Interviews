# Product-Based Company
These companies create their own products. Examples include Google, Apple, and Amazon etc.

Interview Preparation Tips:

1. Proficiency in at least one programming language: Such as C++, Java, or Python. These languages are versatile and used in web development, game development, desktop applications, Android, iOS, AI, data science, system design, virtual reality, and cybersecurity etc.
2. Data Structures and Algorithms (DSA): Essential for any company interview, especially product-based ones. Key topics include, like BFS & DFS, sliding window, top K elements, linked lists, stacks, queues, dynamic programming, arrays, strings, searching, sorting, backtracking, tries, bit manipulation, graphs, and BSTs.
3. Practice problem-solving, on platforms like LeetCode. Focus on frequently asked questions and patterns.
4. Additional knowledge in computer networks, system design, database management, operating systems, and testing etc.

# Service-Based Company
These companies do not have their own specific products. Examples include IBM and Accenture.

Interview Preparation Tips:

1. Proficiency in at least one programming language: Such as C++, Java, or Python.
2. Basic knowledge of DSA.
3. Object-Oriented Programming (OOP)
4. Database management
5. Computer fundamentals

# Preparation Plan Before Interviews at Top-Tier Companies

The following plan should give you an idea of how to tackle the interview preparation process.

★ 1+ Year Before Interview:

1. Learn multiple (like 2 or 3) programming languages.

2. Expand your network.

3. Build projects, website/portfolio showcasing your experience.

4. Students: Find internship and take classes with large projects.
Professionals: Focus on working on "meaty" projects.

★ 3-12 Months Before Interview:

5. Continue working on projects. Try to add one more project.

6. Create a draft of resume and send it out for review.

7. Make a target list of preferred companies.

8. Learn and master Big O. Then Implement DSA from scratch.

★ 1-3 Months Before Interview:

9. Do several mock interviews & Continue practicing interview questions.

10. Create a list to track mistakes you've made while solving problems.

★ 4 Weeks Before Interview:

11. Create an interview prep grid.

12. Update Resume & Begin applying to companies.

13. Continue practicing questions, writing code on paper. Do another mock interview.

★ 1 Week Before Interview:

14. Continue practicing interview questions. Do a final mock interview.

15. Rehearse your stories from the interview prep grid.

16. Re-read Big O section & Algorithm Approaches (optimize & solve techniques).

★ Day Before Interview: 

17. Rehearse each story from interview prep grid once.

18. Continue practicing questions & review your list of mistakes.

19. Review the Powers of 2 table. Print it for a phone screen.

★ Day of Interview:

20. Wake up in plenty of time to eat good breakfast & be on time. Be Confident but Not Cocky!

21. Remember to talk out loud. Show how you think.

★ After Interview:

22. Write "Thank You" note to the recruiter.

23. If you haven't heard from recruiter, check in after one week.

24. If there's no offer, ask when you can re-apply. Don't give up hope!

25. But got an offer? Celebrate! Your hard work has paid off!


Reference Book: 
Cracking the Coding Interview

# Technical Interview Preparation

Online Resources:

1. Pramp – Practice online mock interviews
2. LeetCode – Standard problems & solutions
3. Codewars – Explore others’ smart solutions

Books:

1. Cracking the Coding Interview
2. Elements of Programming Interviews (Not necessary for beginners)

# System Design Interview Preparation

System design questions are common in interviews (especially at big tech companies like Google, Amazon, Facebook).

The goal is to evaluate how you think about and design large-scale systems.

Important Terminologies:

Replication: Keeping copies of data from one machine on other machines for fault tolerance.

Consistency: Ensuring all machines have the same data.

Eventual Consistency: All machines will eventually have the same data over time.

Availability: The system can always respond to requests, even if some nodes fail.

Partition Tolerance: The system continues to operate despite network failures or communication issues between nodes.

Vertical Scaling: Increasing the resources (CPU, RAM, etc.) of a single machine.

Horizontal Scaling: Adding more machines to handle increased load.

Sharding: Splitting large datasets across multiple machines.

Load Balancer: Distributes incoming traffic across multiple servers.

Caching: Storing frequently accessed data (e.g., Redis, CDN) to reduce latency and database load.

CAP Theorem:

In a distributed system, you cannot simultaneously guarantee all three:

1. Consistency (C)
2. Availability (A)
3. Partition Tolerance (P)

At most, you can fully achieve two of them.

"In distributed systems, when a network partition occurs, you must choose between Consistency(C) and Availability(A)"

Example:

Banking system → prefers Consistency

Social media feed → prefers Availability

Common Interview Questions:

• Design a scalable search system like Google Search.

• Design a URL shortener like Bitly.

• Design a messaging system like WhatsApp.

Interviewers typically focus on:

• Scalability

• Traffic estimation

• Storage planning

Example:

Designing a URL Shortener

Step 1: Requirements

• Short URL generation

• Redirection service

• High availability

Step 2: Scale Estimation

• 100 million URLs

• 10,000 QPS

Step 3: High-Level Design

• Load Balancer → API Servers → Database (Sharded) → Cache (Redis)

Step 4: Deep Dive

• Use hashing to generate short codes.

• Store mappings in a NoSQL database for fast reads.

• Cache popular URLs.

Step 5: Trade-offs

• Hash collisions → Use longer hashes.

• Consistency vs Availability → Use eventual consistency for caching.

Important Concepts to Study:

• Horizontal Scaling & Vertical Scaling

• Load Balancing & Caching

• Session Management

• Database Replication & Partitioning

• Data Center Redundancy

• Database Indexing

• Rate Limiting

• Security & Monitoring

• Latency vs Throughput

• Hashing & Consistent Hashing (Must-Know) → Essential for sharding and load distribution.

Preparation & Resources:

1. Real System Design Case Studies

Designing Data-Intensive Applications

• Provides deep understanding of databases, scalability and consistency.

2. Modern Interview-Focused Resource

System Design Primer (GitHub)

• The most popular interview-focused resource.

• Covers real interview questions and detailed solutions.

3. Practice Platform

Excalidraw (or any whiteboard tool)

• System design interviews require drawing and explaining architectures.

• Without practice, it is difficult to perform well in interviews.

# Live Coding Practice Platforms

1. Pramp
2. Gainlo
3. Interviewing.io

# CS News Sites

1. Hacker News [https://news.ycombinator.com/]
2. Lobsters [https://lobste.rs/]

# Why Some Engineers Earn More Than Others Despite Having the Same Experience? So How to Increase Your Earnings?

1. Depth Matters More Than General Knowledge: Having surface-level knowledge of many things is really good but being a specialist in one area.

2. Prioritize Problem-Solving Over Plain Coding: Companies pay for Real Solutions, not just Code! Without expertise in System Design, Long-term Scalability, Performance Tuning, Business Logic, Security, Database Indexing, API Rate Limiting; Growth is limited. Always understand a feature’s purpose first. Like if an API underperforms; Identify the root cause, improve queries & add caching.

3. Get Strong at System Design & Performance Tuning (differentiators for high-paying engineers): Like can your system scale to millions of users while optimizing performance through database indexing, caching, and faster API response times?

4. Keep Learning Beyond Work Hours: Read technical books, Stay updated with new technologies & frameworks, Work on side projects that showcase your skills in solving real-world problems.  

5. Build a Network & Strengthen Your Personal Brand: Share knowledge online to boost visibility with recruiters & hiring managers.  

6. Master Negotiation Skills to Maximize Your Worth: Engineers who negotiate well earn more. Research market rates (e.g., Levels.fyi), quantify your impact (e.g., “I optimized a system to save $100K”) & ask confidently for what you deserve. Don’t just take the first offer; Push for better salary, equity or bonuses.
For example: Thanks for the $180K offer! Based on my experience & market data, Am targeting $200K; How can we align on that?


# Laws of Software Engineering

1. Murphy’s Law (Edward A. Murphy Jr.)

If something can go wrong, it will go wrong.

Example:

• Server might crash → keep backups

• Users may give wrong input → add validation

2. Brooks’s Law (Fred Brooks)

Adding manpower to a late project makes it later.

When new people are added to a late project:

• Training is required

• Communication increases

• Confusion increases

3. Postel’s Law (Jon Postel)

Be conservative in what you send (send clean & correct data), and liberal in what you accept (be flexible, tolerate small errors).

4. Pareto Principle (Vilfredo Pareto)

80% of the results come from 20% of the work.

Not all tasks are equally important, a small portion (20%) creates the biggest impact (80%).

5. Kerckhoffs’s Principle (Auguste Kerckhoffs)

A system should remain secure even if everything about it is public (except the key).

Security depends on the secrecy of the key, not on hiding the system (algorithm or code).

6. Moore’s Law (Gordon Moore)

Computing power roughly doubles every ~2 years.

Example:

Earlier, training an AI model took 1 month.

Now, the same task can be done in a few days.

7. Ninety-Ninety Rule (Tom Cargill)

First 90% of the work takes 10% of the time.

Remaining 10% of the work takes 90% of the time.

The initial progress feels fast, but the final part (debugging, polishing, handling edge cases) takes much longer.

8. Premature Optimization Principle (Donald Knuth)

Premature optimization is the root of all evil.

Avoid excessive optimization at the beginning — focus on making it work first, then optimize later.

9. Metcalfe’s Law (Robert Metcalfe)

The value of a network grows with the square of the number of connected users.

As users increase, value doesn’t grow linearly, it grows quadratically (n²).

10. OODA Loop (John Boyd)

A model for fast decision-making and iteration:

Observe → Orient → Decide → Act

Example:

1. Launch an app
2. See user feedback (Observe)
3. Understand the problem (Orient)
4. Decide on changes (Decide)
5. Release updates (Act)


# Software Development Mistakes 

1. Missed the deadline? Add more developers.
2. Someone isn’t working properly? Say nothing.
3. One person will do everything; no need to involve others.
4. The project is difficult? Hard work alone will make it succeed.
5. Work loudly in an open space.
6. Risk management? Not needed (Agile/Rapid methods will handle it).
7. Missed a milestone? Complete it before the next one.
8. Testing/environment setup takes time? No problem.
9. No need for version control in small projects.
10. Documentation? Not required; code is enough.
11. Client/stakeholder feedback? A waste of time.
12. Branching strategy? Just push to main.
13. CI/CD pipeline? Overkill for small teams.



