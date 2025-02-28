# CS-320-Porftolio
# Software Testing and Automation Portfolio Submission

This repository contains my work from **Project One** and **Project Two**, demonstrating my skills in software testing, automation, and quality assurance. The files included showcase my ability to create unit tests to uncover errors, analyze testing approaches based on requirements, and apply the right testing strategies to ensure software reliability.

## **How can I ensure that my code, program, or software is functional and secure?**
To ensure my code is functional, I write unit tests that validate the expected behavior of key components. For example, in the Contact Service, I implemented structured assertions using `assertEquals`, `assertThrows`, and `assertNull` to confirm that contacts were added, retrieved, and deleted correctly while preventing invalid data. 

To ensure security, I followed best practices like data validation and error handling to prevent issues like duplicate entries, invalid inputs, or unexpected crashes.

## **How do I interpret user needs and incorporate them into a program?**
Understanding user needs involves analyzing requirements and translating them into functional constraints and test cases. In my project, I made sure that appointment IDs were unique and that dates were validated to prevent past entries—features that align with real-world scheduling needs. 

By testing valid and invalid inputs, I ensured that the system behaved as expected in different scenarios, reflecting a user-focused design approach.

## **How do I approach designing software?**
I approach software design with a focus on clarity, maintainability, and testing from the start. Instead of just implementing features, I also write unit tests to catch errors early and prevent technical debt. 

In my Contact Service, I designed my classes to follow a clear structure, ensuring that modifications in the future wouldn’t break functionality. Additionally, I use automated testing where possible to make sure that even small updates don’t introduce new bugs.
