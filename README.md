# DriverPass System Design

# Project Summary

DriverPass is a system design project completed for CS 255 at SNHU. The client, DriverPass, wanted a web-based platform that helps student drivers prepare for and pass their DMV test. The system gives students access to practice exams, study materials, and the ability to schedule on-the-road driving lessons with instructors. It also supports different user roles — students, instructors, secretaries, management, and IT — each with their own set of permissions and tools within the system. The project involved gathering business requirements, creating UML diagrams (use case, activity, sequence, and class), defining technical requirements, and presenting the design back to the client in nontechnical language.


# Reflections

Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client was DriverPass, a company that wanted to improve student driver pass rates at the DMV. They wanted a cloud-hosted web application where students could study DMV material, take practice tests, and schedule on-the-road driving lessons with instructors. The system also needed to support secretaries handling scheduling and account issues, management generating reports and managing accounts, and IT maintaining the system and keeping DMV content up to date. The whole thing needed to be accessible from any modern browser on desktop or mobile, with role-based access so every user only sees what they are supposed to see.

What did you do particularly well?

I think the business requirements document was my strongest piece. I was thorough in breaking down what each user role needed, and I made sure every requirement could be traced back to something the client actually said in the interview. I also think I did a good job with the technical requirements section — it covered hardware, software, security, and infrastructure without being vague or just restating the functional requirements in different words. The security design in particular felt well thought out because it addressed real concerns like password policy, account lockout, encryption, and logging rather than just saying the system would be secure.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?


I would go back and improve the UML class diagram. While it covers the main classes and attributes the system needs, I could have included methods to show what each class actually does rather than just what data it holds. Adding methods would have made the diagram more useful for a developer picking up the design, because they would be able to see not just the structure but also the behavior of each class. I also would have spent more time on the relationships between classes to make the multiplicity and direction of each association clearer.

How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?


The user needs came from an interview transcript with the DriverPass client. I went through what they said they wanted and broke it down into functional and nonfunctional requirements — what the system needs to do versus how well it needs to do it. For example, the client said students needed to be able to schedule lessons and take practice tests, so those became core use cases that showed up in every diagram. The client also stressed that DMV content needed to stay current, so I built that into the technical requirements as either an automatic feed or a manual update process handled by IT. Considering the user's needs is the whole point of designing a system. If the design does not reflect what the users actually need, then it does not matter how technically sound it is — it will not get used, or worse, it will actively get in the way of the people it was built for.

How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?


I start with the requirements. Before drawing any diagrams or thinking about how the system works, I need to know what it is supposed to do and who is going to use it. From there I work outward — identify the users and their roles, figure out what each one needs access to, and then model those interactions. I used UML diagrams to map that out visually: use case diagrams for the big picture, activity diagrams to walk through specific processes step by step, sequence diagrams to show how different parts of the system communicate, and a class diagram to define the data structure. In the future I would lean more into iterative design — getting a rough version in front of stakeholders early and refining based on their feedback rather than trying to get everything perfect in one pass. I would also want to use prototyping tools to mock up the user interface earlier in the process, because a lot of misunderstandings between a client and a designer come from the client not being able to visualize what they are getting until it is too late to change it easily.
