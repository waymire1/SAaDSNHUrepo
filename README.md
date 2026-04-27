
# DriverPass System Design

Project Summary
DriverPass is a system design project completed for CS 255 at SNHU. The client, DriverPass, wanted a web-based platform that helps student drivers prepare for and pass their DMV test. The system gives students access to practice exams, study materials, and the ability to schedule on-the-road driving lessons with instructors. It also supports different user roles — students, instructors, secretaries, management, and IT — each with their own set of permissions and tools within the system. The project involved gathering business requirements, creating UML diagrams (use case, activity, sequence, and class), defining technical requirements, and presenting the design back to the client in nontechnical language.
Reflections

How did you interpret user needs and implement them into your design?

The user needs came from an interview transcript with the DriverPass client. I went through what they said they wanted and broke it down into functional and nonfunctional requirements — what the system needs to do versus how well it needs to do it. For example, the client said students needed to be able to schedule lessons and take practice tests, so those became core use cases that showed up in every diagram. The client also stressed that DMV content needed to stay current, so I built that into the technical requirements as either an automatic feed or a manual update process handled by IT. The key was making sure that every piece of the design traced back to something the client actually asked for rather than just adding features for the sake of it.

How do you approach designing software?

I start with the requirements. Before drawing any diagrams or thinking about how the system works, I need to know what it is supposed to do and who is going to use it. From there I work outward — identify the users and their roles, figure out what each one needs access to, and then model those interactions. I used UML diagrams to map that out visually: use case diagrams for the big picture, activity diagrams to walk through specific processes step by step, sequence diagrams to show how different parts of the system communicate, and a class diagram to define the data structure. I also try to keep the client's perspective in mind the whole time. A design is only good if the people paying for it can understand what they are getting, so I put effort into being able to explain the system without hiding behind jargon.
