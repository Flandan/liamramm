---
title: "A test post"
description: "This post is for testing testing testing testing testin testing testing"
publishDate: "22 Feb 2023"
updatedDate: 22 Jan 2024
tags: ["test", "markdown"]
---

# Building an Interactive Learning Tool for Law Students: A Journey from Unreal Engine to Web Application

## Introduction to the Project

In the evolving landscape of legal education, integrating technology into the learning process has become imperative. One such innovation is the creation of a multiple-choice game designed to reinforce good interviewing techniques for law students. This interactive tool puts students in the role of a junior solicitor interviewing a potential client involved in a vehicle accident. Through a series of carefully structured questions and scenarios, the game aims to enhance students' interviewing skills, making the learning process both engaging and practical.

## Game Concept and Ruleset

The game begins with a brief introduction to the scenario: the player, a junior solicitor, is scheduled to meet a new client, Mr. Tron, who has been injured in a road traffic accident. The player’s task is to conduct an effective interview by selecting appropriate questions at each stage. The game employs three distinct types of questions to simulate the complexity and dynamics of real-life client interviews:

1. **Multiple Choice**: Players choose the correct question to gather pertinent information. Incorrect choices prompt feedback and another attempt.
2. **Sequence**: All questions are valid but must be asked in a specific order. Players receive feedback if questions are asked out of sequence.
3. **Quiver**: Players select 15 questions from a set of 25. The quality of the questions determines the relevance of the information obtained.

At the end of the interview, players can review their draft client statement, with any missed information redacted. This feature allows them to see what they could have asked differently and learn from their mistakes.

## Development Journey

### Initial Development in Unreal Engine

The project was initially developed using Unreal Engine, leveraging C++ and Blueprints. Unreal Engine’s robust capabilities in creating immersive 3D environments and interactive experiences made it an attractive choice for this educational tool. The engine's "Widget" framework facilitated the creation of the user interface, allowing for dynamic interaction and feedback mechanisms critical to the game’s design.

### Transition to Web Application with React and CSS

Despite the powerful features of Unreal Engine, the team faced challenges with text-based inline styling and the flexibility needed for a predominantly text-driven application. To address these issues, the project transitioned to a web-based application using React and CSS. This shift offered several advantages:

- **Enhanced Text Handling**: React provides superior handling of text-based content, which is essential for an application focused on dialogue and question-based interactions.
- **Flexibility in UI Design**: CSS allows for precise and flexible styling, enabling the team to create a clean, user-friendly interface that can easily be adapted and scaled.
- **Cross-Platform Accessibility**: A web application ensures that the game is accessible from various devices, including laptops, tablets, and smartphones, broadening its reach and usability.

## Technical Implementation

The technical implementation of the game involved several key steps:

1. **Backend Development**: The backend was built to handle the logic of the game, including the sequencing of questions, tracking player choices, and generating feedback. This was achieved using a combination of Node.js for server-side scripting and a database to store question sets and user progress.
2. **Frontend Development**: React was used to create a dynamic and responsive user interface. Components were designed to manage different types of questions (Multiple Choice, Sequence, Quiver) and provide immediate feedback based on user input.
3. **Integration with CSS**: Custom CSS was employed to style the application, ensuring that the interface was both visually appealing and easy to navigate. This included the creation of interactive elements such as buttons, feedback messages, and the client statement review section.
4. **User Experience (UX) Design**: Special attention was given to UX design to ensure that the game was intuitive and engaging. This involved user testing and iterations based on feedback to refine the flow of the interview and the clarity of instructions and feedback.

## Educational Impact and Future Directions

The transition from Unreal Engine to a web-based platform not only enhanced the technical capabilities of the game but also significantly improved its educational impact. By simulating real-world interview scenarios, the game provides law students with practical experience in a controlled environment. The immediate feedback and the ability to review and reflect on their performance help reinforce learning and build confidence in their interviewing skills.

Looking ahead, the project aims to incorporate more advanced features such as:

- **Adaptive Learning**: Implementing AI to adapt the difficulty and complexity of questions based on the player’s performance.
- **Expanded Scenarios**: Adding more diverse scenarios and case studies to cover a wider range of legal situations and interviewing techniques.
- **Collaborative Features**: Introducing multiplayer options where students can collaborate or compete in simulated interviews, enhancing peer learning and engagement.

## Conclusion

The development of this multiple-choice game represents a significant step forward in the use of technology for legal education. By combining interactive gameplay with practical learning objectives, the project offers a novel and effective way for law students to hone their interviewing skills. The journey from Unreal Engine to a web-based application demonstrates the importance of flexibility and adaptability in educational technology development, ensuring that the final product is both technically robust and pedagogically sound.