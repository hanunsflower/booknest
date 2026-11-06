# BookNest – Development Roadmap & Task Tracker

## Project Overview

**Project:** BookNest – Personal Library & Social Reading Platform

**Goal:** Build a full-stack platform where readers can manage their personal libraries, track reading progress, save reviews and quotes, discover books, and connect with other readers.

**Technology Stack:**
- Frontend: React
- Backend: Node.js + Express
- Database: MySQL
- Authentication: JWT + bcrypt
- Book Data: Google Books API
- Image Storage: Cloudinary
- Charts: Chart.js

---

# Development Progress

- [x] Milestone 0: Foundation
- [ ] Milestone 1: Database & Architecture
- [ ] Milestone 2: UI/UX Design
- [ ] Milestone 3: Authentication & Profiles
- [ ] Milestone 4: Personal Library
- [ ] Milestone 5: Reading Tracker
- [ ] Milestone 6: Reviews, Quotes & Notes
- [ ] Milestone 7: Insights Dashboard
- [ ] Milestone 8: Social Community
- [ ] Milestone 9: Testing, Polish & Deployment

---

# Milestone 0: Foundation

**Goal:** Prepare the project repository and documentation before development.

### Tasks

- [x] Create GitHub repository named `booknest`.
- [x] Create `client/`, `server/`, and `docs/` folders.
- [x] Create the project README.
- [x] Correct the SRS visibility definition to private or public.
- [x] Export the SRS as `BookNest_SRS.pdf`.
- [x] Save the SRS inside `docs/`.
- [x] Create `.gitignore`.
- [x] Create `.env.example`.
- [x] Commit and push the initial project structure to GitHub.

**Deliverable:** A clean GitHub repository containing the project structure and documentation.

---

# Milestone 1: Database & Architecture

**Goal:** Design the database and backend architecture before implementing features.

### Tasks

- [ ] Identify all database entities.
- [ ] Draw the Entity Relationship Diagram (ERD).
- [ ] Define relationships between database tables.
- [ ] Write the MySQL database schema in `server/db/schema.sql`.
- [ ] Create the system architecture diagram.
- [ ] Document API endpoints grouped by feature.
- [ ] Decide the Express folder structure:
  - Routes
  - Controllers
  - Services
  - Middleware
  - Database
- [ ] Document important technical decisions.

**Deliverable:** Database schema, ER diagram, architecture diagram, and API documentation.

---

# Milestone 2: UI/UX Design

**Goal:** Design the visual appearance and user experience before frontend implementation.

### Tasks

- [ ] Choose the color palette.
- [ ] Select typography and fonts.
- [ ] Define the overall visual style and mood.
- [ ] Create wireframes for:
  - Landing page
  - Login and registration
  - Dashboard
  - Personal library / bookshelf
  - Book detail page
  - User profile
- [ ] Create high-fidelity Figma designs for the dashboard and bookshelf.
- [ ] Define reusable design tokens.
- [ ] Plan responsive layouts for mobile and desktop.

**Deliverable:** Figma designs, wireframes, and a UI style guide.

---

# Milestone 3: Authentication & Profiles

**Goal:** Build secure user registration, login, email verification, and profile management.

### Tasks

- [ ] Initialize the Express server.
- [ ] Configure the MySQL database connection.
- [ ] Set up database migrations.
- [ ] Implement user registration.
- [ ] Hash passwords using bcrypt.
- [ ] Implement email verification using verification tokens.
- [ ] Configure email sending using Nodemailer.
- [ ] Implement login and logout.
- [ ] Generate and validate JWT tokens.
- [ ] Create authentication middleware.
- [ ] Build React login and registration pages.
- [ ] Create an authentication context.
- [ ] Implement protected routes.
- [ ] Build the user profile page.
- [ ] Implement profile editing.
- [ ] Implement avatar uploads using Cloudinary.

**Deliverable:** Users can register, verify their email, log in, and manage their profiles.

---

# Milestone 4: Personal Library

**Goal:** Allow users to build and manage their personal digital libraries.

### Tasks

- [ ] Create book-related database tables and relationships.
- [ ] Implement book endpoints.
- [ ] Implement user-library endpoints.
- [ ] Integrate Google Books API for book searches.
- [ ] Build the Add Book form.
- [ ] Implement manual book entry.
- [ ] Implement cover image uploads using Cloudinary.
- [ ] Allow users to organize books into collections.
- [ ] Implement reading status:
  - Want to Read
  - Currently Reading
  - Completed
- [ ] Implement library search.
- [ ] Implement filtering and pagination.
- [ ] Build the book detail page.
- [ ] Create the visual bookshelf.
- [ ] Implement drag-and-drop bookshelf organization.

**Deliverable:** Users can add, organize, search, and manage books in their personal libraries.

---

# Milestone 5: Reading Tracker

**Goal:** Help users track their reading progress and build consistent reading habits.

### Tasks

- [ ] Create reading log database tables.
- [ ] Implement reading log endpoints.
- [ ] Allow users to record pages read and reading dates.
- [ ] Calculate reading progress percentages.
- [ ] Build progress bars.
- [ ] Create a reading log form.
- [ ] Allow users to set annual reading goals.
- [ ] Calculate current reading streaks.
- [ ] Calculate longest reading streaks.
- [ ] Write unit tests for streak calculations.
- [ ] Implement the book completion flow.
- [ ] Record book completion dates.

**Deliverable:** Users can track pages, reading progress, streaks, and annual reading goals.

---

# Milestone 6: Reviews, Quotes & Notes

**Goal:** Allow users to record their thoughts and personal experiences with books.

### Tasks

- [ ] Create review database tables.
- [ ] Implement ratings from 1 to 5 stars.
- [ ] Allow users to write reviews.
- [ ] Allow users to edit and delete their reviews.
- [ ] Implement private/public visibility settings.
- [ ] Allow users to save favorite quotes.
- [ ] Support optional page numbers for quotes.
- [ ] Allow users to create private notes.
- [ ] Display reviews, quotes, and notes on relevant book pages.
- [ ] Enforce privacy rules on the backend.
- [ ] Test access restrictions for private content.

**Deliverable:** Users can manage reviews, ratings, quotes, and private notes securely.

---

# Milestone 7: Insights Dashboard

**Goal:** Provide users with meaningful insights into their reading habits.

### Tasks

- [ ] Create statistics API endpoints.
- [ ] Calculate total books read.
- [ ] Calculate currently reading books.
- [ ] Calculate total pages read.
- [ ] Calculate current reading streak.
- [ ] Display annual reading goal progress.
- [ ] Calculate monthly reading statistics.
- [ ] Create monthly pages-read charts.
- [ ] Create monthly books-completed charts.
- [ ] Calculate favorite genres.
- [ ] Create genre distribution charts.
- [ ] Build dashboard statistic cards.
- [ ] Integrate Chart.js.
- [ ] Polish the dashboard UI.

**Deliverable:** A functional dashboard with reading statistics, goals, and visual analytics.

---

# Milestone 8: Social Community

**Goal:** Connect readers and allow them to share their reading experiences.

### Tasks

- [ ] Implement follow functionality.
- [ ] Implement unfollow functionality.
- [ ] Build public user profiles.
- [ ] Display public reviews and favorite books.
- [ ] Display currently reading books where visibility permits.
- [ ] Create public book pages.
- [ ] Display public reviews on book pages.
- [ ] Implement review likes and unlikes.
- [ ] Implement flat comments.
- [ ] Build a home activity feed.
- [ ] Display activity from followed users.
- [ ] Implement book recommendations to followers.
- [ ] Build the Discover page.
- [ ] Browse books by genre and category.
- [ ] Display popular books.
- [ ] Implement simple rule-based book recommendations.
- [ ] Implement content reporting.
- [ ] Add basic moderation functionality.

**Deliverable:** A working social reading community with profiles, following, reviews, and book discovery.

---

# Milestone 9: Testing, Polish & Deployment

**Goal:** Make BookNest reliable, responsive, secure, and publicly accessible.

### Tasks

- [ ] Implement loading states.
- [ ] Implement empty states.
- [ ] Implement error handling and error messages.
- [ ] Improve mobile responsiveness.
- [ ] Check accessibility.
- [ ] Test authentication functionality.
- [ ] Test private-content access restrictions.
- [ ] Test important API endpoints.
- [ ] Fix identified bugs.
- [ ] Prepare production environment variables.
- [ ] Deploy the frontend using Vercel or Netlify.
- [ ] Deploy the backend using Render or Railway.
- [ ] Configure managed MySQL hosting.
- [ ] Configure production Cloudinary and Google Books API settings.
- [ ] Test the deployed application.
- [ ] Record a project demonstration video.
- [ ] Update the README with screenshots and the live URL.

**Deliverable:** A deployed, tested, portfolio-ready BookNest application.

---

# Development Guidelines

1. Complete tasks in milestone order unless a dependency requires otherwise.
2. Understand the code before implementing it.
3. Follow the SRS as the main reference for requirements.
4. Test every feature after implementation.
5. Protect private user information on the backend.
6. Use Git commits to track completed work.
7. Update this checklist after completing each task.
8. Avoid implementing advanced features before the core functionality works.

---

# Current Development Status

**Current Milestone:** Milestone 0 – Foundation

**Current Task:** Create the GitHub repository and initial project structure.

**Last Completed Task:** None yet.

**Next Task:** Create the `booknest` repository and its folders.