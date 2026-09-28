# Week 1 and Day 1 Plan – Senior Java Developer

Based on the 6-month roadmap and the 8-hour/day schedule, the first week focuses on 3 main goals:

1. Establish a Senior identity: responsibility, design thinking, and disciplined learning.
2. Set up the learning environment and workflow: Git, Java, Maven/Gradle, Docker, and a sample project.
3. Begin building foundational knowledge and a personal project: Java Core, System Design, and basic microservices.

---

## 1) Week 1 Goals

### Learning Goals
- Read and recite the Senior identity statement once each day.
- Set up the learning environment: Git, JDK 17+, IntelliJ IDEA, Maven/Gradle, Docker Desktop.
- Master Java Core fundamentals: OOP, collections, exceptions, streams, and generics.
- Understand basic System Design concepts: scalability, latency, throughput, load balancers, databases, and caching.
- Begin building a basic Product Service as part of the microservices project.

### Week Deliverables
- Have one clean, well-structured Git repository.
- Complete 3–5 basic Java exercises.
- Write one short technical note or first blog post.
- Build a preliminary Product Service model with a simple REST API.

---

## 2) Daily Study Schedule (8 Hours/Day)

| Time | Activity | Notes |
|---|---|---|
| 5:30–6:00 | Read the identity statement and restate daily goals | Don't use your phone |
| 6:00–7:30 | Block 1: Deep theory | System Design / Java Core |
| 7:30–8:00 | Breakfast, short break | |
| 8:00–12:00 | Work at the company | Apply the mindset at work |
| 12:00–13:00 | Lunch and rest | No studying |
| 13:00–14:30 | Block 2: Java practice / coding | LeetCode / mini lab |
| 14:30–14:45 | Short break | Walk, drink water |
| 14:45–16:15 | Block 3: Personal project | Product Service |
| 16:15–16:30 | Short break | |
| 16:30–18:00 | Block 4: In-depth study | Docker / Git / Java Boot |
| 18:00–19:00 | Dinner and rest | |
| 19:00–20:30 | Block 5: Documentation / blog / review | Teach back what you learned |
| 20:30–21:00 | Journal and review | Record XP and what you learned |
| 21:00–21:30 | Technical reading / light reading | |
| 21:30–22:00 | Unwind and get ready for bed | |

---

## 3) Week 1 Study Schedule

### Monday – Set Up the Fundamentals and Senior Identity
- 6:00–7:30: Reread the Senior Java Developer identity statement. Write down 3 behaviors to practice this week.
- 13:00–14:30: Java Core: OOP, classes, objects, inheritance, abstraction, encapsulation, polymorphism.
- 14:45–16:15: Initialize the Product Service project with Spring Boot and prepare the package structure.
- 16:30–18:00: Set up Git, GitHub, JDK 17, Maven/Gradle, IntelliJ IDEA, and Docker Desktop.
- 19:00–20:30: Write a note: “What does being a Senior Java Developer look like in practice?”
- 20:30–21:00: Journal and record XP.

### Tuesday – Java Fundamentals and Design Thinking
- 6:00–7:30: Basic System Design: scalability, availability, latency, throughput, and database selection.
- 13:00–14:30: Java Collections, Map/List/Set, equals/hashCode, streams, and lambda.
- 14:45–16:15: Create the Product entity, repository, and first REST API controller.
- 16:30–18:00: Basic Docker: containers, images, Dockerfile, Docker Compose, and running local PostgreSQL.
- 19:00–20:30: Write a short blog post: “How are Java Streams used in practice?”
- 20:30–21:00: Journal.

### Wednesday – Practical Java and the First API
- 6:00–7:30: Basic Clean Architecture: entities, use cases, adapters, and service layer.
- 13:00–14:30: Exception handling, validation, DTOs, and mappers.
- 14:45–16:15: Complete Product CRUD API: getAll, getById, create, update, delete.
- 16:30–18:00: Basic PostgreSQL + Spring Data JPA configuration and schema migration.
- 19:00–20:30: Review your code; check naming conventions and architecture boundaries.
- 20:30–21:00: Journal.

### Thursday – Testing and Code Quality
- 6:00–7:30: Testing fundamentals: unit tests, integration tests, TDD.
- 13:00–14:30: JUnit 5 + Mockito; write tests for Product Service.
- 14:45–16:15: Add validation and test the controller and service.
- 16:30–18:00: Set up Lombok, MapStruct, or a manual mapper; review code smells.
- 19:00–20:30: Write an ADR or design note: “Why should Product Service have a separate service layer?”
- 20:30–21:00: Journal.

### Friday – System Design & First Project
- 6:00–7:30: System Design: API Gateway, database, cache, load balancer, message queue.
- 13:00–14:30: Solve 2 LeetCode problems: array/string or hashmap.
- 14:45–16:15: Add pagination, sorting, and API queries for Product.
- 16:30–18:00: Create Docker Compose to run the app and database; test locally end-to-end.
- 19:00–20:30: Write a short blog post: “Where do microservices begin in practice?”
- 20:30–21:00: Journal.

### Saturday – Review and Weekly Recap
- 6:00–7:30: Review and organize the week's knowledge; assess which goals were achieved.
- 13:00–14:30: Review Java labs, fix errors, and note their solutions.
- 14:45–16:15: Check the Product Service project and prepare the week's commits.
- 16:30–18:00: Improve project structure, create the first README, and document how to run the project.
- 19:00–20:30: Write a weekly recap: 3 new things learned, 3 bugs fixed, and 3 improvements for next week.
- 20:30–21:00: Journal and assess weekly trust.

### Sunday – Rest / Light Recovery
- Take at least one full session off during the week.
- If you have energy, spend 1–2 hours on light reading; don't overload yourself.
- While resting, reset your mind, get enough sleep, and prepare for Week 2.

---

## 4) Day 1 Plan (Detailed Execution)

### Day 1 Goals
- Read and understand the Senior Java Developer identity.
- Set up the basic learning environment.
- Begin studying Java Core and System Design.
- Initialize the first Product Service project.

### Day 1 Schedule

#### 5:30–6:00 – Identity Statement
- Read the main version of `../../senior-java-developer-identity-statement.md` aloud.
- Choose 3 behaviors to practice today.
- Write: “What will I do today to live up to my Senior identity?”

#### 6:00–7:30 – Block 1: System Design + Java Core
- Study the basic concepts:
  - Scalability
  - Availability
  - Latency vs throughput
  - Database vs cache
  - Load balancer
- Java Core:
  - OOP: class, object, encapsulation, inheritance, polymorphism.
  - Collections: ArrayList, HashMap, LinkedList, Set.
  - Exception handling.

#### 7:30–8:00 – Break and Breakfast
- Have breakfast, take a short walk, and don't spend too long scrolling on your phone.

#### 8:00–12:00 – Work at the Company
- Observe how the team designs, reviews code, and resolves issues.
- Note one technique or design decision that you find valuable.

#### 12:00–13:00 – Lunch Break
- Don't overload yourself with studying; prioritize recovery.

#### 13:00–14:30 – Block 2: Java Practice
- Write a mini Java exercise:
  - A `Product` class with fields and methods.
  - An `ArrayList` + `HashMap` example.
  - An exception handling example.
- Create `notes/java-core-day1.md` or `lessons-learned.md` if you want to save your notes.

#### 14:45–16:15 – Personal Project: Product Service
- Create the first Spring Boot project.
- Structure:
  - `controller`
  - `service`
  - `entity`
  - `repository`
  - `dto`
- Create the first `Product` entity.
- Create a `GET /products` API that returns an empty list or sample data.

#### 16:30–18:00 – Docker + Git + Environment
- Install/check:
  - Java 17
  - Maven or Gradle
  - IntelliJ IDEA
  - Docker
  - GitHub account
- Create a GitHub repository for the project.
- Add a preliminary `.gitignore`, `README.md`, and `docker-compose.yml`.

#### 19:00–20:30 – Write Documentation / Teach Back
- Write a short blog post:
  - “What did I learn today about Java Core and System Design?”
- Goal: write so others can understand, not just to save it for yourself.

#### 20:30–21:00 – Journal and Review
- Answer these 5 questions:
  1. What did I learn today?
  2. Where did I act like a Senior today?
  3. Where did I still think like a Mid-level developer?
  4. What will I improve tomorrow?
  5. How much XP did I earn today?

---

## 5) Day 1 Completion Checklist

- [ ] Read the Senior Java Developer identity statement.
- [ ] Choose 3 Senior behaviors to practice today.
- [ ] Set up the Java/Git/Docker environment.
- [ ] Write one Java Core mini exercise.
- [ ] Initialize the Spring Boot Product Service project.
- [ ] Design the basic package structure and Product entity.
- [ ] Write an end-of-day journal.
- [ ] Make the first GitHub commit.

---

## 6) Week 1 Success Criteria

- Make at least 1 commit per day or 5 commits during the week.
- Have 1 Product Service project that runs locally.
- Write 3 short notes/blog posts.
- Complete 2 Java exercises or tutorials.
- Keep a weekly learning journal and review your identity every day.

---

## 7) Suggestions for Avoiding Burnout

- Use Pomodoro 50/10: focus for 50 minutes, take a 10-minute break.
- Don't study through more than 3 consecutive blocks without a break.
- If you're tired, reduce the amount of theory, prioritize practice, and get enough sleep.
- Each evening, review 3 things: what you learned, where you went wrong, and what to improve tomorrow.

---

## 8) Week 2 Goals

- Increase your focus on Java Web and Spring Boot.
- Complete Product Service CRUD.
- Add JPA, DTOs, validation, and tests.
- Start getting familiar with Docker Compose and PostgreSQL.

Start here: Day 1 doesn't need to be perfect; it only needs real progress and the beginning of good habits. A Senior's foundation is built through steady days, not one burst of effort.
