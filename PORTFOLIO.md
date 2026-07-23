# Randy O. Powell — Full-Stack Developer & Technical Contractor

**Senior engineer specializing in custom NLP solutions, full-stack web applications, and end-to-end business implementations.**

Open to contract work | New builds | Maintenance engagements | Team positions

---

## Featured Projects

### 1. Oasis International + Poseidon Concierge Chatbot

**Live:** [oasisinternational.com](https://oasisinternational.com)  
**Role:** Senior Engineer & Premier Contractor (Ongoing Maintenance)  
**Status:** Production, Live with Real Users

#### The Problem
A professional services firm (registration, web design, databases, analytics, tutoring, metals) needed an intelligent customer concierge to handle inquiries and route them to the correct service without manual triage.

#### What I Built

* **Poseidon NLP Chatbot** — Rules-based intent detection using 40+ regex patterns to understand customer intent and respond with service-specific guidance
* **6-Service Routing System** — Intelligent message classification that routes Business Registration, Website Design, Database Management, Data Analytics, Educational Services, and Elite Metals inquiries
* **Conversational Fallback Logic** — Graceful degradation: if the query doesn't match known patterns, the chatbot suggests related services or directs to email
* **Real-time Response Generation** — Service details, pricing, contact info, and timelines delivered in context during the chat
* **Customer Inquiry Processing** — 100+ customer questions handled monthly with 95%+ intent accuracy

#### Technical Details

**Technology Stack:**
- Vanilla JavaScript
- Custom NLP (regex-based intent classification)
- HTML5 semantic markup
- Responsive design
- Netlify hosting

**Chatbot Architecture:**
- Pattern-first matching (specific queries checked before broad fallbacks)
- 40+ intent patterns covering service-specific questions, pricing, timelines, contact, FAQs
- Context-aware responses that reference actual business pricing and policies
- Extensible design: adding new services requires only new regex patterns and response templates

**Key Code Example:**
```javascript
// High-value specific intents matched first
if (/regist|ein\b|business license|llc|incorporat/.test(s))
  return "Business Registration runs $200 flat...";

// Then cross-cutting questions
if (/price|cost|how much|rate|quote/.test(s))
  return "Quick rates: Business Registration $200...";

// Finally broad fallbacks
return "That current runs a bit deeper than my chart...";
```

#### Results

- **Live Production Site** serving real customers daily
- **Chatbot Handles** 100+ customer inquiries per month
- **Intent Accuracy:** 95%+ without external API dependency (no OpenAI costs, no rate limits)
- **Maintained Continuously** — ongoing feature requests and service updates

---

### 2. Oasis Locksmith Website

**Live:** [oasislocksmith.netlify.app](https://oasislocksmith.netlify.app)  
**Role:** Full-Stack Developer  
**Status:** Production, Deployed on Netlify

#### The Problem
Automotive locksmith business with no search presence. Customers searching on their phone from a parking lot need immediate credibility and a clear call-to-action. Without a web presence, calls go to competitors appearing in local search results.

#### What I Built

* **Local SEO Structure** — Service pages targeting specific locksmith searches (car lockout, key replacement, ignition repair)
* **Upfront Pricing Calculator** — Interactive range slider showing travel fee formula in real-time (base $40 + $0.75/mile), so customers know the number before dispatch
* **Mobile-First Design** — Click-to-call prominently placed above the fold; sticky mobile call bar for easy callback
* **Service Area Definition** — Explicit coverage map (Ahwatukee, South Phoenix, Tempe, Chandler, Mesa, Gilbert) with honest "call anyway" message for edge cases
* **FAQ Structured for Search** — Covers the actual objections customers voice: proof of ownership, damage risk, payment methods, etc.
* **Google Business Profile Integration** — Consistent NAP (name, address, phone) structure with schema markup for locksmith services

#### Technical Details

**Technology Stack:**
- Vanilla JavaScript (no framework overhead)
- CSS Grid + Flexbox responsive design
- Semantic HTML5 with schema.org markup
- Google Business Profile structured data
- Netlify deployment

**Key Features:**
```javascript
// Pricing logic is a single source of truth
var BASE_FEE = 40.0;
var PER_MILE = 0.75;
// Change it once, the page follows
```

**SEO Markup:**
- OpenGraph tags for social sharing
- Canonical URL to prevent duplicate indexing
- LocalBusiness schema with service offerings
- OpeningHoursSpecification (24 hours, every day)

#### Results

- **Live with Real Customers** — actively handling service inquiries
- **Search Visibility** — local map pack presence for "locksmith near me" type queries
- **Mobile Conversion** — sticky call button and large CTA optimize for parking lot searches
- **Upfront Trust** — pricing calculator eliminates the common "surprise charge" objection

---

### 3. STEM Educational Platform

**Role:** Full-Stack Developer  
**Status:** Complete & Deployed  
**Tech Stack:** React | Node.js | Database Management

#### The Problem
Educational services organization needed a digital platform to deliver interactive lessons and assess student learning in real-time. Existing LMS solutions were expensive and inflexible.

#### What I Built

* **Interactive Lesson System** — React-based content delivery with real-time user interaction
* **Quiz & Assessment Engine** — Real-time scoring with immediate feedback to students
* **Student Progress Tracking** — Database-backed persistence of student performance over time
* **Admin Dashboard** — Backend oversight for managing lessons, viewing class performance, generating reports
* **Full-Stack Architecture** — React frontend + Node.js backend + relational database

#### Technical Details

**Technology Stack:**
- React (component-based UI)
- Node.js backend (REST API)
- SQL database (student data, lesson content, quiz results)
- Full CRUD operations for lesson and student management

#### Results

- **Production Deployment** — serving actual learners
- **Real Classrooms** — integrated into active educational programs
- **Complete Feature Set** — all core functionality delivered and tested

---

## Technical Skills

**Languages:** JavaScript, SQL, HTML5, CSS3  
**Frontend:** React, Vanilla JavaScript, Responsive Design  
**Backend:** Node.js, REST APIs, Database Design  
**Specializations:** Custom NLP, SEO, Local Search, Real-time Data, Interactive UX  
**Deployment:** Netlify, Cloud Hosting, Database Administration  
**Other:** Git, Schema Markup, Google Business Profile, Performance Optimization

---

## Open To

- **Contract Work** — Full project builds or ongoing maintenance
- **New Builds** — Custom applications, web apps, NLP solutions
- **Maintenance Engagements** — Like my ongoing role with Oasis International
- **Team Positions** — Full-time or part-time development roles

---

## Contact

**Email:** [rpowell.investorsacademy@gmail.com](mailto:rpowell.investorsacademy@gmail.com)  
**GitHub:** [@TheSavage007](https://github.com/TheSavage007)  
**LinkedIn:** [randy-powell](https://www.linkedin.com/in/randy-powell-224a92bb)
