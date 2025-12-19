# Sam Nie
Incoming DevOps Intern @ Wolters Kluwer | Incoming Tech Lead @ Code4Community | RTC member | AWS Certified Developer and Professional Scrum Master | CS and Cognitive Psych at Northeastern University

Undergraduate Junior pursuing a B.S. in Computer Science and Cognitive Psychology @ Northeastern University 

Former Quality Assurance Tester Co-Op at the Massachusetts Medical Society (New England Journal of Medicine)

Zealous for knowledge to evolve leadership and technical skills.

**Programming Languages**: Java, HTML, CSS, Typescript, JavaScript, SQL, Python, PHP 

**Technologies**:  ReactJS, React Native, ExpressJS, NodeJS, DynamoDB, JEST, JUnit, Postman, Linux, Selenium, Cypress, AWS, Azure, Github Actions CICD, Jenkins, Docker, Docker Compose, Linux, Windows

**Certifications**: AWS Developer Associate (Amazon Web Services), AWS Cloud Practitioner (Amazon Web Services), Professional Scrum Master I (Scrum.org), Lead 360 Blueprint (Northeastern University) 

[LinkedIn](https://www.linkedin.com/in/sam-nie-460a02293/)

## 🏆 Featured Projects

### Fenway Community Center Donation System - Code4Community (Sept 2025 - Dec 2025)

[https://github.com/Code-4-Community/fcc](https://github.com/Code-4-Community/fcc)

A new donation technical system and admin portal for Fenway Community Center to improve donor retention and reuptake.

Technologies: ReactJS, ExpressJS, NestJS, NodeJS, PostgreSQL, JEST, TypeORM, Stripe API

<ins>My contributions so far as a backend developer:</ins>

* Stripe Payments: Implemented end-to-end Stripe flows in NestJS with 2 REST endpoints (intent, webhook) in payments.controller.ts, service logic in payments.service.ts, 3+ DTOs in dtos, and mapping utilities in mappers.ts; authored documentation in STRIPE.MD and added unit tests.
* Donations Domain: Modeled the Donation entity donation.entity.ts, wired TypeORM in data-source.ts, and shipped 3+ migrations for users/donations in migrations; exposed 4 API endpoints in donations.controller.ts with service logic in donations.service.ts.
* Testing & Quality: Expanded test coverage with unit/integration/e2e suites, including donations.e2e-spec.ts, donations.controller.spec.ts, payments.service.spec.ts, and mappers.spec.ts; updated jest.config.ts.
* API Surface & Validation: Delivered 6 REST endpoints total (4 donations + 2 payments), 3+ migrations, 3+ DTOs, and mapper utilities; tightened input validation for payment intents/subscriptions and improved error handling to harden the API.

### Agentic Northeastern University Course Search (Oct 2025 - Dec 2025)

[https://github.com/SamNie2027/Search_NEU_agentic](https://github.com/SamNie2027/Search_NEU_agentic)

An AI-powered course search tool for Northeastern University undergrad students that uses TF-IDF, semantic embeddings, and ReAct agents to help students find relevant courses.

Technologies: Python, PyTorch, FastAPI, Semantic Embeddings, Sentence Transformers, Agent Workflows (ReAct)

<ins>My contributions as a model developer:</ins>

* Built hybrid course search blending keyword and semantic matching to surface top 3 results from 5.5k courses
* Implemented agent-guided assistant with automatic search strategy selection using deterministic decoding and 6-step max for consistent, fast responses
* Generated 768-dim vector embeddings for all courses using sentence-transformers in precompute pipeline to improve search responsiveness under load
* Added verification tests and scripts to validate embeddings and data integrity, increasing demo stability
* Designed prompt routing logic to direct code-like queries to keyword search and conversational queries to semantic search

### Shelter Link - Code4Community (Jan 2025 - June 2025)

[https://github.com/Code-4-Community/shelter-link](https://github.com/Code-4-Community/shelter-link)

The goal of Project ShelterLink is to develop a user-friendly, map-based application to help LGBTQ+ youth locate winter shelters in Boston.

Technologies: React Native, ExpressJS, AWS DynamoDB, NodeJS, JEST

<ins>My contributions as a full-stack developer:</ins>

* Added documentation for front-end types and discussed further type iterations
* Implemented and applied custom fonts
* Changed components to match high fidelity design
* Collaborating to create a mobile application to help homeless LGBTQ+ youth locate winter shelters
* Developed full-stack on React-Native components and Express endpoints, including code reviews
* Working with AWS cloud and DynamoDB database
* Utilized **Postman** to cover 100% of backend endpoints, created Github Actions CI/CD to incorporate tests
* Tested backend using **JEST** with 98% Stryker coverage, incorporated into Github Actions CI/CD
* Created **Cypress** tests for end-to-end user flows, enabling automated UI checks in CI/CD

<img width="250" height="450" alt="image" src="https://github.com/user-attachments/assets/fffb68dc-f9b3-46df-8eba-87d68e3266a3" />

### Study Buddy Networking Web App (Jan 2024 - Sept 2024)

[https://github.com/Oasis-NEU/s24-group16](https://github.com/Oasis-NEU/s24-group16)

Demo: [https://youtu.be/jW2umXdV-qs](https://youtu.be/jW2umXdV-qs)
Code Overview: [https://youtu.be/UOTxTe2UXdA](https://youtu.be/UOTxTe2UXdA)

A better alternative to Canvas for connecting with other people in the same class as you!

Technologies: HTML, CSS, Javascript, Bootstrap 5, SQL (mySQL), PHP

<ins>My contributions as project manager and full-stack developer:</ins>

* Led ideation meetings to draft concept and user flow

* Designed front-end using Figma, implemented designs with HTML, CSS, and Bootstrap

* Developed back-end with user login and sessions and database editing using PHP and SQL

* Dynamic web pages and user feedback using PHP in creative ways

* Thorough documentation

<img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/d189f341-c2b1-4072-99e4-08539dc49935" />

<img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/1e4cfec9-1545-4450-80bf-a92ff82918c9" />

## 🚀 Hackathon, Experimental, and Learning Projects

### Scholarly Mail (Oct 2025 - Present)

[https://github.com/SamNie2027/ScholarlyMail2](https://github.com/SamNie2027/ScholarlyMail2)

A Spring Boot service for managing scholarly articles built mainly to explore Java and DevOps practices

Technologies: Java, Maven, Spring Boot, Couchbase, MongoDB, JUnit 5, Docker, Docker Compose, Jenkins

<ins>My contributions as a solo backend developer:</ins>

* Built Spring Boot RESTful API for scholarly article management with CRUD operations and read-state toggle
* Migrated persistence layer from MongoDB to Couchbase using Spring Data Couchbase and dynamic properties
* Wrote JUnit 5 integration tests with MockMvc and Testcontainers for real Couchbase instances with CI-safe guards
* Dockerized application and services with Compose orchestration and Couchbase init scripts for reproducible environments
* Implemented Jenkins CI/CD pipeline with Docker-based Maven agents and Maven Wrapper for automated builds

### Ray - GNEC Hackathon (Oct 2025)

[https://github.com/SamNie2027/Ray](https://github.com/SamNie2027/Ray)

A hackathon project that gamified the process of donating to make charitable giving more engaging and rewarding.

Technologies: TypeScript, MySQL, Docker, Github Copilot

<ins>My contributions as an AI-accelerated backend developer:</ins>

* Applied prompt engineering using the RACE framework (Role, Action, Context, Expectation) to guide AI-generated code effectively.
* Used GitHub Copilot to create and run Jest tests, ensuring reliability and functionality of core features.
* Leveraged Copilot to write mocks and endpoints with documentation, accelerating backend development.
* Strengthened skills in reviewing and refining AI-generated code, providing feedback to improve software architecture and align with best development practices.

### TattleTell - InnovAIte Finalist (Feb 2025)

[https://github.com/SamNie2027/InnovAIte2025](https://github.com/SamNie2027/InnovAIte2025)

TattleTell is an app and API where the local community can report maintenance issues with a click of a button, reducing response time of maintenance issues and enabling instant recognition using Machine Learning.

Technologies: React Native, ExpressJS, Python Flask

<ins>My contributions as a full-stack app and API developer:</ins>

* Developed responsive app to take pictures and convert into files to send up application infrastructure
* Created and tested all endpoints, including the frontend, backend, and AI API
* Quickly explained concepts to team members unfamiliar with the tech stack

## 💻 Team-Based Academic Projects

### Husky Overflow (Oct 2024 - Dec 2024)

(no link as this repository is private)

A stack overflow copy to add features to for Fundamentals of Software Engineering

Technologies: ReactJS, ExpressJS, NodeJS, JEST, MongoDB, Bootstrap

<ins>My contributions as a full-stack developer and tester:</ins>

* Manually tested functionality and UI on Windows, MacOS, Chrome, Edge, Firefox, and Safari
* Added React components for user profiles, integrated Auth0 with login and signup pages
* Added routes with Express, manipulated user information with MongoDB, unit tested with JEST


<!--
**SamNie2027/SamNie2027** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

random change

- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
