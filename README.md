[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15148018&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?

Software engineering is a comprehensive discipline that combines application engineering principles and techniques to create high-quality software systems and products. It encompasses the entire process of software development, from initial planning, designing, implementing, testing, deploying to maintenance and evolution. It involves a systematic, disciplined, and quantifiable approach to the development, operation, and maintenance of software. Software engineering applies engineering principles to software creation, ensuring that the final product is reliable, efficient, and meets user requirements.

Traditional Programming, on the other hand, is a more general term that refers to the process of writing code to solve a specific problem or create a software application. It focuses on writing code, debugging, and testing, but may not necessarily follow a structured approach or consider the entire software development life cycle.

The key differences between software engineering and traditional programming are:

Traditional programming refers to the process of writing code to solve specific problems or implement specific functionalities. It often focuses on the immediate task at hand without considering the broader context of software development. On the other hand, software engineering takes a more holistic approach to software development. It involves the use of systematic methodologies, best practices, and standardized processes to ensure the quality, reliability, and maintainability of software systems.

Software engineering goes beyond just writing code. It involves activities such as requirements analysis, system design, software testing, project management, and maintenance. It emphasizes the use of modular and reusable code, documentation, and collaboration among team members. Software engineers also consider factors such as scalability, performance, security, and user experience when developing software systems.


1. Scope: Software engineering encompasses the entire software development life cycle, including requirements gathering, design, development, testing, deployment,  maintenance and evolution. Traditional programming, on the other hand, focuses primarily on writing code.
2. Approach: Software engineering follows a systematic and structured approach, whereas traditional programming may be more ad-hoc and focused on solving a specific problem, leading to less organized and less efficient development processes.
3. Quality: Software engineering emphasizes quality, reliability, and maintainability. It includes rigorous testing, debugging, and maintenance processes to ensure that software meets user requirements and is free from defects. Whereas traditional programming may prioritize getting the code working quickly.
4. User-Centered: Software engineering is user-centered, meaning that it involves understanding user needs and requirements to develop software that meets those needs. Traditional programming often focuses more on technical aspects and less on user needs.
5. Collaboration: Software engineering involves collaboration among developers, designers, and other stakeholders to ensure that software meets user requirements and is developed efficiently. Traditional programming often involves individual developers working in isolation.
6. Continuous Improvement: Software engineering involves continuous improvement through testing, debugging, and maintenance. Traditional programming often lacks this focus on continuous improvement, leading to less efficient and less effective software development processes.

Here's a simple example to illustrate the difference:

Traditional programming example;

def calculate_sum(a, b):
    result = a + b
    print("The sum is:", result)

calculate_sum(3, 5)

(In this traditional programming example, we have a function called calculate_sum that takes two arguments, a and b. It calculates the sum of a and b and then prints the result.)

Software Engineering example;

class Calculator:
    def calculate_sum(self, a, b):
        result = a + b
        return result

calculator = Calculator()
sum_result = calculator.calculate_sum(3, 5)
print("The sum is:", sum_result)

(In this software engineering example, we have a class called Calculator that encapsulates the functionality of calculating the sum. The calculate_sum method takes two arguments, a and b, and returns the result. We create an instance of the Calculator class and call the calculate_sum method on it. The result is assigned to a variable sum_result and then printed.
The software engineering example demonstrates a more structured and reusable approach. By encapsulating the functionality within a class, we can create multiple instances of the Calculator class and perform calculations independently. The code is organized, modular, and follows best practices of software engineering.)

In summary, while traditional programming focuses on writing code to solve immediate problems, software engineering is a structured and user-centered approach to software development that emphasizes quality, collaboration, and continuous improvement. Software engineering takes a broader and more systematic approach to software development, considering the entire software development life cycle and the long-term goals of the software system.It differs significantly from traditional programming in these key aspects.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:

The Software Development Life Cycle (SDLC) is a structured process used to develop, maintain, and replace software systems. The SDLC framework provides a step-by-step methodology for planning, creating, testing, deploying, and maintaining software systems. The various phases of the SDLC are:

1. Planning Phase
In this phase, the project's scope, goals, timelines, budget, and resources are defined. The project's feasibility is assessed, and a detailed project plan is created.

2. Requirements Gathering Phase
In this phase, the project's requirements are gathered from stakeholders, customers, and users. The requirements are documented, and a detailed analysis is performed to understand the project's needs.

3. Design Phase
In this phase, the project's design is created, including the system architecture, user interface, and system components. The design is reviewed, and any changes are incorporated.

4. Implementation or Coding Phase
In this phase, the project's design is implemented, and the code is written. The development team starts building the software system.

5. Testing Phase
In this phase, the developed software system is tested to ensure it meets the project's requirements. Various types of testing, such as unit testing, integration testing, and system testing, are performed.

6. Deployment Phase
In this phase, the tested software system is deployed to the production environment. The system is installed, configured, and made available to users.

7. Maintenance Phase
In this phase, the deployed software system is maintained, and any issues or defects are fixed. The system is updated, and new features are added as needed.

Agile vs. Waterfall Models

There are two popular SDLC models: Agile and Waterfall.

Agile Model
The Agile model is an iterative and incremental approach to software development. It emphasizes flexibility, customer satisfaction, and team collaboration. The Agile model is suitable for projects with changing requirements and involves continuous iteration and improvement.

Waterfall Model
The Waterfall model is a linear and sequential approach to software development. It follows a phased approach, where each phase is completed before moving on to the next one. The Waterfall model is suitable for projects with well-defined requirements and a fixed scope.

In summary, the SDLC phases provide a structured approach to software development, while the Agile and Waterfall models offer different approaches to managing the SDLC process.



Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Requirements Engineering:

Agile vs. Waterfall Models: Comparison and Contrast

The Agile and Waterfall models are two popular software development methodologies that differ in their approach to managing the software development life cycle (SDLC). Here's a comparison of the two models:

Agile Model

Key Characteristics:

Iterative and Incremental: Agile involves breaking down the development process into smaller, manageable chunks, with each iteration building upon the previous one.
Flexible and Adaptive: Agile is designed to accommodate changing requirements and priorities.
Customer Involvement: Agile emphasizes close collaboration with customers and stakeholders to ensure that the developed software meets their needs.
Team Collaboration: Agile encourages cross-functional teams to work together to achieve common goals.
Continuous Improvement: Agile involves continuous iteration, testing, and refinement to ensure that the software meets the desired quality standards.
Waterfall Model

Key Characteristics:

Linear and Sequential: Waterfall follows a phased approach, where each phase is completed before moving on to the next one.
Predictive and Plan-Driven: Waterfall is based on a detailed plan, with a clear understanding of the project's scope, timeline, and budget.
Phase-Gate Approach: Waterfall involves a phase-gate approach, where each phase is reviewed and approved before proceeding to the next one.
Less Customer Involvement: Waterfall typically involves less customer involvement during the development process.
Fixed Scope: Waterfall is designed for projects with a fixed scope and well-defined requirements.
Key Differences:

Flexibility: Agile is more flexible and adaptable to changing requirements, while Waterfall is more rigid and plan-driven.
Customer Involvement: Agile involves more customer involvement during the development process, while Waterfall has less customer involvement.
Risk Management: Agile is better suited for managing risks and uncertainties, while Waterfall is more suitable for projects with well-defined requirements.
Time-to-Market: Agile allows for faster time-to-market, as it involves iterative development and continuous delivery, while Waterfall follows a more traditional, sequential approach.
Scenarios for Each Model:

Agile:

Complex or Uncertain Projects: Agile is suitable for projects with complex or uncertain requirements, where flexibility and adaptability are essential.
Rapid Prototyping: Agile is ideal for rapid prototyping and proof-of-concept development.
Customer-Facing Applications: Agile is well-suited for customer-facing applications, where customer feedback and involvement are crucial.
Waterfall:

Well-Defined Requirements: Waterfall is suitable for projects with well-defined requirements and a fixed scope.
Regulated Industries: Waterfall is often used in regulated industries, such as aerospace, defense, or healthcare, where strict compliance and auditing are required.
Predictable Projects: Waterfall is ideal for projects with a predictable outcome, where the scope, timeline, and budget are well-defined.
Requirements Engineering:

Requirements engineering is a critical aspect of software development that involves eliciting, analyzing, documenting, and maintaining software requirements. Both Agile and Waterfall models have their own approaches to requirements engineering:

Agile Requirements Engineering:

Iterative Requirements Gathering: Agile involves iterative requirements gathering, where requirements are refined and updated throughout the development process.
User Stories: Agile uses user stories to capture requirements, which are prioritized and refined during the development process.
Continuous Refinement: Agile involves continuous refinement of requirements, based on customer feedback and changing priorities.
Waterfall Requirements Engineering:

Upfront Requirements Gathering: Waterfall involves upfront requirements gathering, where all requirements are gathered and documented before development begins.
Detailed Requirements Specification: Waterfall uses a detailed requirements specification document, which outlines all the project's requirements.
Change Management: Waterfall has a formal change management process, which ensures that any changes to requirements are properly documented and approved.
In summary, Agile and Waterfall are two distinct software development methodologies that cater to different project needs and requirements. Agile is suitable for projects with complex or uncertain requirements, while Waterfall is ideal for projects with well-defined requirements and a fixed scope.



What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:

Requirements Engineering:

Requirements engineering is the process of defining, analyzing, documenting, and maintaining the requirements of a software system. It involves understanding the needs and constraints of the stakeholders, users, and the business, and translating them into a clear, concise, and unambiguous set of requirements that can be used as a basis for software development.

Requirements Engineering Process:

The requirements engineering process typically involves the following activities:

1. Requirements Elicitation: Gathering requirements from stakeholders, users, and business through various techniques such as interviews, surveys, focus groups, and observation.
2. Requirements Analysis: Analyzing the gathered requirements to identify conflicts, ambiguities, and inconsistencies, and to define the functional and non-functional requirements of the system.
3. Requirements Specification: Documenting the requirements in a clear, concise, and unambiguous manner, using techniques such as use cases, user stories, and requirements specification documents.
4. Requirements Validation: Verifying that the requirements are correct, complete, and unambiguous, and that they meet the needs and expectations of the stakeholders and users.
5. Requirements Management: Managing changes to the requirements, tracking and documenting changes, and ensuring that the requirements are up-to-date and consistent throughout the software development lifecycle.
Importance of Requirements Engineering:

Requirements engineering is a critical phase of the software development lifecycle, as it sets the foundation for the entire project. The importance of requirements engineering can be summarized as follows:

1. Ensures Correctness: Requirements engineering ensures that the software system meets the needs and expectations of the stakeholders and users, reducing the risk of developing a system that does not meet the requirements.
2. Reduces Errors: Requirements engineering helps to identify and resolve errors and ambiguities early in the development process, reducing the cost and effort required to fix them later.
3. Improves Communication: Requirements engineering facilitates communication among stakeholders, users, and developers, ensuring that everyone has a common understanding of the system's requirements.
4. Increases Customer Satisfaction: Requirements engineering ensures that the software system meets the needs and expectations of the customers, leading to increased customer satisfaction and loyalty.
5. Reduces Costs: Requirements engineering helps to reduce costs by identifying and prioritizing the most important requirements, and by reducing the need for rework and changes later in the development process.

Software Design Principles:

Software design principles are guidelines and best practices that guide the design of software systems. Some of the key software design principles include:

1. Separation of Concerns: Divide the system into smaller, independent components, each responsible for a specific concern or functionality.
2. Abstraction: Represent complex systems in a simplified way, focusing on essential features and hiding irrelevant details.
3. Modularity: Break down the system into smaller, independent modules, each with a specific function or responsibility.
4. Reusability: Design components and modules to be reusable in other parts of the system or in other systems.
5. Flexibility: Design the system to be flexible and adaptable to changing requirements and technologies.
6. Scalability: Design the system to scale up or down as needed, to handle increased load or traffic.
7. Maintainability: Design the system to be easy to maintain, update, and modify, with minimal impact on the overall system.
8. Testability: Design the system to be easy to test, with clear and concise interfaces and APIs.

By following these software design principles, developers can create software systems that are robust, scalable, maintainable, and easy to use, and that meet the needs and expectations of the stakeholders and users.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:

Modularity in Software Design:

Modularity is a software design principle that involves breaking down a large software system into smaller, independent, and self-contained modules or components. Each module is designed to perform a specific function or set of functions, and is typically responsible for a specific aspect of the system's overall functionality.

Characteristics of Modular Design:

1. Separation of Concerns: Each module is responsible for a specific concern or functionality, making it easier to understand, modify, and maintain.
2. Independence: Modules are designed to be independent of each other, with minimal dependencies and interactions.
3. Self-Containment: Each module is self-contained, with its own data and functionality, making it easier to modify or replace without affecting other modules.
4. Interface-Based: Modules communicate with each other through well-defined interfaces, making it easier to swap out or replace modules without affecting the overall system.

Benefits of Modularity:

1. Improved Maintainability: Modularity makes it easier to maintain and update individual modules without affecting the entire system.
2. Scalability: Modularity allows for easier scaling of individual modules or components, making it easier to add new functionality or improve performance.
3. Reusability: Modular design enables reusability of individual modules or components across different systems or applications.
4. Flexibility: Modularity provides flexibility in terms of technology choices, allowing for easier integration of new technologies or frameworks.
5.Easier Testing: Modularity makes it easier to test individual modules or components, reducing the complexity and scope of testing.

How Modularity Improves Maintainability and Scalability:

1. Easier Bug Fixing: With modularity, bugs can be isolated to individual modules, making it easier to identify and fix issues without affecting the entire system.
2. Faster Updates: Modular design enables faster updates and deployments, as individual modules can be updated independently without affecting the entire system.
3. Improved Code Organization: Modularity promotes better code organization, making it easier to understand and navigate the codebase.
4. Reduced Coupling: Modularity reduces coupling between modules, making it easier to modify or replace individual modules without affecting other parts of the system.
5. Improved Performance: Modularity can improve performance by allowing for more efficient use of system resources and reducing the overhead of unnecessary functionality.

Testing in Software Engineering:

Testing is an essential phase of the software development lifecycle that involves evaluating the software system to ensure it meets the required specifications, functionality, and quality standards. Testing involves various activities, including:

1. Unit Testing: Testing individual modules or components to ensure they function correctly.
2. Integration Testing: Testing how individual modules or components interact with each other.
3. System Testing: Testing the entire software system to ensure it meets the required specifications and functionality.
4. Acceptance Testing: Testing the software system to ensure it meets the customer's or user's requirements.

Types of Testing:

1. Black Box Testing: Testing the software system without knowledge of the internal workings.
2. White Box Testing: Testing the software system with knowledge of the internal workings.
3. Gray Box Testing: Testing the software system with partial knowledge of the internal workings.

Importance of Testing:

1. Ensures Quality: Testing ensures the software system meets the required quality standards.
2. Reduces Defects: Testing helps identify and fix defects early in the development process.
3. Improves Reliability: Testing improves the reliability of the software system.
4. Increases Customer Satisfaction: Testing ensures the software system meets the customer's or user's requirements, leading to increased satisfaction.


Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?



Levels of Software Testing:

1. Software testing is a crucial phase of the software development lifecycle that involves evaluating the software system to ensure it meets the required specifications, functionality, and quality standards. There are several levels of software testing, each with its own objectives and scope:

2. Unit Testing: Testing individual modules or components of the software system to ensure they function correctly. Unit testing is typically performed by the developer who wrote the code.

3. Integration Testing: Testing how individual modules or components interact with each other to ensure they work together seamlessly. Integration testing is typically performed after unit testing.

4. System Testing: Testing the entire software system to ensure it meets the required specifications and functionality. System testing is typically performed after integration testing.

5. Acceptance Testing: Testing the software system to ensure it meets the customer's or user's requirements. Acceptance testing is typically performed after system testing.
Why Testing is Crucial in Software Development:

Testing is crucial in software development for several reasons:

1. Ensures Quality: Testing ensures the software system meets the required quality standards, reducing the risk of defects and errors.
2. Reduces Defects: Testing helps identify and fix defects early in the development process, reducing the cost and effort required to fix them later.
3. Improves Reliability: Testing improves the reliability of the software system, ensuring it performs consistently and accurately.
4. Increases Customer Satisfaction: Testing ensures the software system meets the customer's or user's requirements, leading to increased satisfaction and loyalty.
5. Reduces Maintenance Costs: Testing reduces the maintenance costs associated with fixing defects and errors, allowing developers to focus on new features and functionality.


Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

A version control system (VCS) is a software tool that helps developers manage changes to code, collaborate with others, and maintain a record of changes. 

VCSs are essential in software development for several reasons:

1. Track Changes: VCSs allow developers to track changes to code, making it easier to identify and fix errors.
2. Collaboration: VCSs enable multiple developers to collaborate on the same codebase, reducing conflicts and errors.
3. Version History: VCSs maintain a version history of changes, allowing developers to revert to previous versions if needed.
4. Branching and Merging: VCSs allow developers to create branches for new features or bug fixes, and merge them into the main codebase when complete.

Popular VCSs include:

1. Git: A distributed VCS that allows developers to work on local copies of the codebase.
2. Subversion (SVN): A centralized VCS that stores code in a single repository.
3. Mercurial: A distributed VCS that allows developers to work on local copies of the codebase.

By using a VCS, developers can ensure that changes to code are tracked, collaborated on, and maintained in a consistent and reliable manner.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

Role of a Software Project Manager

A software project manager is the most important person in a team who takes overall responsibility to manage software projects and plays a crucial role in the successful completion of projects. The job responsibilities of a project manager range from invisible activities like building up team morale to highly visible customer presentations.

Key Responsibilities:

1. Project Planning: Project planning involves estimating several characteristics of a project and then planning the project activities based on these estimations.
2. Project Monitoring and Control: Project monitoring and control involve tracking the project's progress, identifying and correcting deviations from the plan, and taking corrective action to ensure the project is completed on time and within budget.
3. Project Estimation: Project estimation involves estimating the project's size, cost, duration, and effort required to complete the project.
4. Scheduling: Scheduling involves creating a project schedule that outlines the tasks to be performed, the resources required, and the timelines for completion.
5. Staffing: Staffing involves identifying the resources required for the project and assigning them to specific tasks and activities.
6. Risk Management: Risk management involves identifying, analyzing, and mitigating risks that could impact the project's success.
7. Miscellaneous Plans: This includes making several other plans such as quality assurance plans, configuration management plans, and communication plans.

Challenges Faced:

1. Scope Creep: Managing changes to the project scope and ensuring that they do not impact the project's timeline and budget.
2. Resource Constraints: Managing resources such as team members, equipment, and budget to ensure that they are utilized efficiently and effectively.
3. Communication: Ensuring that all stakeholders are informed and aligned with the project's progress and changes.
4. Risk Management: Identifying and mitigating risks that could impact the project's success.
5. Team Management: Managing a team of diverse individuals with different skills, expertise, and personalities to ensure that they work together effectively to achieve the project's goals.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software Maintenance:

Software maintenance is the process of modifying, updating, and improving existing software applications to ensure they continue to meet the changing needs of users and remain relevant in a rapidly evolving technology landscape. It involves a series of activities aimed at ensuring the software remains stable, efficient, and effective throughout its lifespan.

Types of Maintenance Activities:

1. Corrective Maintenance: Identifying and fixing errors, bugs, and defects in the software to ensure it functions as intended.
2. Adaptive Maintenance: Modifying the software to adapt to changes in the operating environment, such as updates to the operating system or hardware.
3. Perfective Maintenance: Improving the software's performance, functionality, or usability to meet changing user needs or to take advantage of new technologies.
4. Preventive Maintenance: Performing routine tasks to prevent problems from occurring, such as backups, updates, and security patches.

Why Maintenance is Essential:

Maintenance is an essential part of the software lifecycle because it:

1. Ensures Software Quality: Maintenance helps to identify and fix defects, ensuring the software meets the required quality standards.
2. Improves User Experience: Maintenance activities, such as perfective maintenance, can improve the software's performance, functionality, and usability, leading to a better user experience.
3. Reduces Downtime: Regular maintenance can help prevent software failures, reducing downtime and minimizing the impact on business operations.
4. Enhances Security: Maintenance activities, such as security patches and updates, help to protect the software and data from security threats.
5. Supports Business Growth: Maintenance enables the software to adapt to changing business needs, supporting growth and evolution.
6. Extends Software Lifespan: Regular maintenance can extend the lifespan of the software, delaying the need for replacement or redevelopment.

In summary, software maintenance is a critical phase of the software lifecycle that ensures the software remains relevant, efficient, and effective throughout its lifespan. By performing regular maintenance activities, organizations can improve software quality, reduce downtime, enhance security, and support business growth.

Ethical Considerations in Software Engineering:¹

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?¹

Ethical Considerations in Software Engineering

As software engineers, we have a significant impact on people's lives through the systems we design and develop. It is essential to consider the ethical implications of our work to ensure that we are creating systems that benefit society as a whole.

Ethical Issues in Software Engineering

Some common ethical issues that software engineers might face include:

1. Addictive Design: Creating systems that are intentionally designed to be addictive, manipulating users into spending more time or money than they intend to.
2. Corporate Ownership of Personal Data: Collecting and using personal data without users' knowledge or consent, or selling it to third parties without their permission.
3. Algorithmic Bias: Developing systems that perpetuate biases and discrimination, either intentionally or unintentionally.
4. Weak Cyber Security and PII Protection: Failing to protect users' personal identifiable information (PII) and sensitive data, putting them at risk of identity theft, financial loss, or other harm.
5.Overemphasis on Features: Prioritizing the addition of new features over the well-being and safety of users, potentially leading to negative consequences.

Ensuring Ethical Standards

To ensure that they adhere to ethical standards, software engineers can:

1. Be Transparent: Clearly communicate how personal data is collected, used, and protected.
2. Design with User Well-being in Mind: Consider the potential impact of their designs on users' mental and physical health.
3. Test for Bias: Regularly test systems for biases and take steps to mitigate them.
4. Prioritize Security: Implement robust security measures to protect users' PII and sensitive data.
5. Engage in Ethical Discussions: Participate in open and honest discussions about the ethical implications of their work, and be willing to make changes when necessary.

By considering the ethical implications of their work, software engineers can create systems that benefit society as a whole, while also maintaining the trust and respect of their users.

Here is an example of how a software engineer might implement ethical considerations in their code:

# Example of transparent data collection

def collect_user_data(user_input):
    print("We are collecting your data to improve our services. Your data will be used anonymously.")
    # Collect data with user's consent
    return user_input

# Example of designing with user well-being in mind

def limit_screen_time(user_activity):
    if user_activity > 2 hours:
        print("You have reached your daily screen time limit. Take a break!")
        # Implement features to encourage healthy screen use
    return user_activity

Note: These examples are simplified and not intended to be production-ready code. They are meant to illustrate the concept of ethical considerations in software engineering.


citations:

¹Ethics in Software Engineering: A Key Component of Professional ... pdh-pro

¹The Essential Software Engineering Code of Ethics... institutedata

¹5 examples of ethical issues in software development - TechTarget


¹How can software engineers ensure that their work align with ethical ...
quora


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
