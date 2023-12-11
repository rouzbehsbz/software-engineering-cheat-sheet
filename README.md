# Software Engineering

These are my personal notes and patterns on software architecture and system design, accumulated over years of experience, books and articles I have read.
I thought it might be good to start with explaining some concepts before diving into more detailed stuff.

## There is no one-size-fits-all solution
Keep in mind that there is no one perfect solution for all problems and challenges. Its an important one, always remember, as an engineer you must pick a design or solution with less trade-offs for your software or overall system.
You can't achieve high maintanability for your software without sacrficing performance, you can't scale your software without dealing with shared resource accessability from multiple concurrent consumers.
Practice and learn different designs and patterns, and choose most efficient one for your software or system.

## Software Architecture VS System Design
Software Architecture refers to high-level structure of a single software, its inner components and modules, their relationships and overall codebase organization.
On the other hand, System Design is a broader term for designing systems where multiple softwares comminucating with each other in a reliable way. Both cases involves
making decisions about data structures, algorithms and interfaces.

## Design Decision Principles
As a software architect or system designer,in making decisions and designs we should always seek to reach the following principles as much as possible:

- Performance
- Scalability
- Reliability
- Maintainability
- Deployment
- Security
