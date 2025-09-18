SkillSwap SA 🌟
Learn. Teach. Earn. Together.

SkillSwap SA is a web-based platform designed to bridge educational gaps in under-resourced communities across South Africa. We connect tutors, learners, and peer mentors in a sustainable ecosystem where knowledge sharing is rewarded. Students can earn valuable credits for participating in sessions, which can be redeemed for essential rewards like mobile data, airtime, and school supplies.

✨ Key Features
Dual Role System: Be both a Learner and a Peer Mentor. Share knowledge in subjects you excel at and receive help in others.

Credit-Based Economy: Earn credits for teaching and attending sessions. Spend them on real-world rewards.

Gamified Learning: Stay motivated with badges, achievements, and leaderboards.

Community Hub: A shared space for users to post study tips, participate in eco-challenges, and share success stories.


Frontend: Vanilla HTML, CSS, and JavaScript (Focus on responsive, mobile-first design)

Backend & Database: Supabase (Authentication, Database, Real-time Functionality)

Hosting: Netlify

Notifications: Email via Web3Forms

Rewards API: Placeholder integration for airtime/data vendors (Simulated in prototype) "Future feature"

📋 Project Roadmap
Phase 1: MVP

User Authentication (Email/Phone)

Basic Profiles & Session Booking

Core Credits System

Phase 2: Community & Gamification

User Ratings & Reviews

Badges & Leaderboards

Community Forum Feed

Phase 3: Automation & Scale

Integrated Email Notifications

Automated Reward Fulfillment API

Admin Dashboard

Phase 4: Partnerships

NGO/Sponsor Integration

Enhanced Impact Reporting

🗃️ Database Schema (Supabase)
The project uses a PostgreSQL database powered by Supabase. Core tables include:

profiles: Extends auth.users with user data (role, subjects, bio).

sessions: Manages booked tutoring sessions between users.

credit_transactions: Ledger for all credit earnings and spending.

rewards: Catalog of available rewards and their credit cost.

posts: Powers the community hub feed.
