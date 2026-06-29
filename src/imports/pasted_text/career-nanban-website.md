Career Nanban | Complete Website

Project Overview
Build a complete, fully functional, professional website called Career Nanban — a gamified AI-powered career learning platform. Tagline: "Guiding you today, empowering you tomorrow."
The website must have zero confusion for users. Every button works. Every navigation link goes somewhere. Every page has a clear purpose. Clean, modern dark UI with amber and teal accents.

GLOBAL DESIGN RULES
Color palette:

Background: #0A0F2C
Card surface: #131929
Border: #1E2A45
Primary amber: #F5A623
Teal accent: #00A8CC
Success green: #2ECC8A
Error red: #EF4444
White text: #FFFFFF
Muted text: #94A3B8

Typography:

Headings: Poppins Bold
Body: Inter Regular
Badges/Labels: Space Grotesk Medium

Global animations (apply everywhere):

Page load: content fades up from 20px, opacity 0→1, 400ms ease
All buttons: scale 1.04 on hover, scale 0.97 on click
All cards: lift -4px on hover, border glows in accent color
Progress bars: animate width 0→value on page enter, 600ms ease-out
Smooth scroll between all sections
Navbar shrinks on scroll down, expands on scroll up

Logo placement:

Logo image placeholder (team will replace later)
Show "CN" amber text as temporary logo everywhere


SPLASH SCREEN (First thing user sees)
Full screen dark background #0A0F2C
Center content:

Logo placeholder circle (80px, amber border glow pulse animation)
"CN" initials inside in amber, Poppins Bold 32px
Below logo: "Career Nanban" text fades in, H1 white
Below name: tagline fades in with 300ms delay: "Guiding you today, empowering you tomorrow." teal color
Loading bar at bottom: thin amber line animates left to right over 2.5 seconds

After 2.5 seconds:

Entire splash screen slides up and disappears
Landing page appears underneath with fade in

Logo animation detail:

Logo circle starts at scale 0.3, opacity 0
Scales to 1.1 then settles to 1.0 (spring bounce effect)
Amber glow pulses outward like ripple, 2 rings expanding and fading
Text appears letter by letter after logo settles


PAGE 1 — LANDING PAGE (Home)
Section 1 — Navbar
Fixed top, full width, height 68px

Background: #0A0F2C 85% opacity + backdrop blur

Border bottom: 1px solid #1E2A45
Left: Logo placeholder + "Career Nanban" in amber

Center links: Home | Features | How It Works | Testimonials | Contact

Right: "Login" ghost button + "Get Started Free" amber filled button
Mobile: hamburger menu icon, clicking opens full screen nav overlay
Section 2 — Hero
Full viewport height

Left side (55%):

Small pill badge top: "🚀 AI-Powered Career Platform" — teal border, teal text, dark bg
H1 headline (3 lines):

Line 1: "Learn Smart."

Line 2: "Level Up Fast."

Line 3: "Get Placed." — this line in amber color
Body text below: "Career Nanban guides you from zero to your dream job with AI-generated roadmaps, gamified learning levels, and real placement preparation — all in one platform."
Two buttons: "Start My Journey →" (amber filled, large) + "Watch Demo" (outline teal)
Stats row below buttons (3 items with dividers):

"12,000+ Learners"
"500+ Career Paths"
"92% Placement Rate"
Numbers in amber, labels in muted white



Right side (45%):

Dashboard preview card (mock UI screenshot style)
Shows: student name, XP bar, level progress, 3 task checkboxes
Floating mini cards around it:

Top right: "+120 XP Earned!" green popup card, bounces gently
Bottom left: "🔥 7 Day Streak!" amber card, pulses
Top left: "Level 5 Unlocked! 🎉" teal card, slides in


All floating cards have continuous subtle float animation (up-down loop)

Section 3 — How It Works
Title: "Your Journey in 4 Simple Steps" centered H2

Subtitle: "No confusion. No overwhelm. Just a clear path." muted text
4 step cards in a row with animated connecting dotted line between them:
Step 1 — "Tell Us Your Goal"

Icon: target/bullseye in amber
Description: "Answer a few quick questions about your background and dream career. Takes 2 minutes."

Step 2 — "Get Your AI Roadmap"

Icon: map/route in teal
Description: "Our AI builds a personalized step-by-step learning path just for you."

Step 3 — "Learn & Level Up"

Icon: trophy in amber
Description: "Complete levels, earn XP, unlock badges. Learning feels like a game."

Step 4 — "Get Placed"

Icon: briefcase in green
Description: "Practice mock interviews, build your resume, apply with confidence."

Connecting line animates on scroll: draws from left to right as user scrolls into view
Section 4 — Features
Title: "Everything You Need. Nothing You Don't." H2 centered
6 feature cards in 2×3 grid:
Card 1: 🗺️ AI Roadmap Creator

"Tell us your goal and experience. Get a complete learning path in seconds."
Card 2: 🎮 Gamified Levels

"Learn through structured levels. Earn XP and credits on every completion."
Card 3: 📋 Daily Tasks

"Wake up to a focused daily task list. Never wonder what to study next."
Card 4: 🤖 AI Chatbot

"Ask anything career-related. Get instant answers, resources, and guidance."
Card 5: 🎤 Mock Interview

"Practice real interview questions with AI feedback. Be ready before day one."
Card 6: 🏆 Leaderboard

"Compete with peers, climb rankings, stay motivated."
Each card:

Dark card bg, amber icon top left
Title H4 white, description body muted
Hover: border glows amber, card lifts, icon scales 1.1

Section 5 — Testimonials
Title: "Real Students. Real Results." H2 centered
Horizontal auto-scrolling strip (infinite loop, pauses on hover):

4 testimonial cards:
Card 1: "I got placed at TCS in 3 months using Career Nanban. The roadmap was exactly what I needed." — Priya S., B.Tech CSE, Chennai
Card 2: "The mock interview feature helped me crack 3 rounds confidently. Best platform for freshers." — Karthik M., MCA Graduate
Card 3: "Daily tasks kept me consistent. I never missed a day of learning for 45 days straight!" — Divya R., Data Science fresher
Card 4: "The AI chatbot answered every doubt I had. It was like having a mentor 24/7." — Arun K., B.Tech IT
Each card: avatar placeholder circle, quote in italic, name + college below, 5 star rating amber
Section 6 — CTA Banner
Full width dark amber gradient band

Left: "Ready to start your career journey?"

Right: "Get Started Free →" white filled button

Subtle particle/sparkle animation in background
Section 7 — Footer
4 column layout:

Col 1: Logo + tagline + social icons (LinkedIn, GitHub, Instagram, YouTube)

Col 2: Platform links — Home, Features, Roadmap, Levels, Leaderboard

Col 3: Support — Contact, FAQ, Privacy Policy, Terms

Col 4: Contact — email placeholder, Instagram handle placeholder
Bottom bar: "© 2026 Career Nanban. Built with ❤️ for students."

PAGE 2 — ONBOARDING FLOW (After clicking "Get Started Free")
This is the most important page. Multi-step form. No page reload between steps. Progress bar at top shows which step user is on.
Header: Logo top left, "Step X of 6" top right, progress bar below header
Step 1 — Welcome
Full center layout:

Heading: "Let's build your career path! 👋"
Subtext: "Answer 6 quick questions. We'll create a roadmap just for you."
Single large button: "Let's Go →" amber

Step 2 — Education Background
Heading: "What is your education background?"

Subtext: "This helps us suggest the right career paths for you."
Option cards (large clickable cards, not dropdowns):

🎓 Currently Studying (UG/PG)
📚 Completed Degree — Fresher (0-1 year)
💼 Working Professional (1+ years experience)
🔄 Career Switcher (Changing domain)

Clicking a card: highlights it in amber border + amber bg tint, shows checkmark
If "Currently Studying" or "Completed Degree":

Follow-up appears below (smooth slide down):

"What degree?" — pill options: B.Tech/BE | BCA | MCA | BSc | MBA | Other
"Which stream/branch?" — pill options: CSE | IT | ECE | Mechanical | Civil | Commerce | Arts | Other
"Which year?" (if studying) — pill options: 1st | 2nd | 3rd | 4th | Final Year



If "Working Professional":

"Years of experience?" — pill options: 1-2 yrs | 2-4 yrs | 4+ yrs
"Current domain?" — text input

Next button appears after selection. Disabled until option chosen.
Step 3 — Career Goal
Heading: "What is your career goal?"

Subtext: "Choose the domain you want to work in. You can change this later."
Domain cards in 3×3 grid (large, icon + title):

💻 Software Development
📊 Data Science & Analytics
🤖 AI & Machine Learning
🎨 UI/UX Design
☁️ Cloud & DevOps
🔐 Cybersecurity
📱 Mobile Development
🧪 QA & Testing
📢 Digital Marketing

Clicking: selects card, amber border glow

Below grid: "Don't see your goal?" text link → opens text input to type custom goal
Step 4 — Skills You Already Know
Heading: "What skills do you already have?"

Subtext: "Be honest — this helps us skip what you already know."
Skill chips grid (multi-select, click to toggle):

Programming: Python | Java | C | C++ | JavaScript | TypeScript | R

Web: HTML | CSS | React | Node.js | Django | Flask | Next.js

Data: SQL | Excel | Tableau | Power BI | Pandas | NumPy

Tools: Git | Docker | Figma | VS Code | Linux

Other: "Add your own skill +" input chip
Selected chips: amber fill, white text, checkmark icon

Unselected chips: dark border, muted text
Below: "No skills yet? That's okay! →" link skips to next step
Step 5 — Experience Level
Heading: "How would you rate yourself?"

Subtext: "Be honest — we'll start you at the right level."
3 large option cards:
🌱 Complete Beginner

"I'm starting from scratch. I need basics first."
📈 Some Knowledge

"I know the basics but want to go deeper."
🚀 Intermediate

"I have decent skills but want to reach expert level."
Clicking selects with amber highlight
Below: "Available time per day?"

Pill options: 30 mins | 1 hour | 2 hours | 3+ hours
Step 6 — Goal & Timeline
Heading: "What's your placement goal?"
Two inputs:

"Target company type" — pill options: Product Company | Service Company | Startup | MNC | Government | Any
"When do you want to get placed?" — pill options: 1 Month | 3 Months | 6 Months | 1 Year

Final section:

Summary card showing all their answers:

"Here's what we know about you:"

Education: [their answer]
Goal: [their answer]
Skills: [chip list]
Level: [their answer]
Timeline: [their answer]


Edit button beside each line

Big amber button at bottom: "Generate My Roadmap 🚀"
On click:

Button shows loading spinner
Progress animation: "🤖 AI is building your personalized roadmap..."
3 animated steps appear one by one:

"✓ Analyzing your background..."
"✓ Mapping career requirements..."
"✓ Building your learning path..."


After 2 seconds → redirects to Dashboard


PAGE 3 — DASHBOARD
Navbar: same global navbar + XP counter + streak + avatar right side
Welcome Banner (full width)

"Good morning, [Name]! 👋"

Subtitle: "You're on Day 3 of your journey. Keep going!"

Right side: overall progress ring (circular, teal, percentage inside)

Background: subtle amber to teal gradient left border only
4 Metric Cards Row

Levels Completed: 3 — teal icon
Current Streak: 7 Days — amber flame icon
Total XP: 480 — gold star icon
Badges Unlocked: 2 — purple badge icon

Each card: dark surface, large number in accent color, label muted, icon top right

Two Column Layout below:
Left (60%) — Today's Mission:

Title: "Today's Tasks 📋" + "3 of 5 done" pill

Progress bar below title: amber fill, shows 60%

Task list (5 items):

✅ Watch: Introduction to Python (30 min) | +50 XP — completed, strikethrough
✅ Read: Variables & Data Types article | +30 XP — completed
⬜ Practice: 5 LeetCode Easy problems | +80 XP — pending
⬜ Watch: Functions in Python video | +50 XP — pending
⬜ Quiz: Python Basics (10 questions) | +100 XP — pending

Clicking checkbox: task crosses out, XP popup flies up from checkbox, green checkmark appears

Right (40%) — Your Progress:

Current Level card:

"Level 3 — Functions & Scope"
Progress bar 65% amber
"Continue Learning →" amber button

Recent Achievement:

Badge card: "Quick Learner 🏆"
"Earned today!" green label
Sparkle animation on badge

Upcoming milestone:

"5 more XP to Level 4!" teal text
Mini progress bar

Roadmap Preview Strip (below two columns)

Title: "Your Roadmap Progress"

Horizontal scrolling nodes:

Node 1: Python Basics ✅ green
Node 2: Functions & Scope 🔄 amber (active, pulsing)
Node 3: OOP Concepts 🔒 grey
Node 4: Data Structures 🔒 grey
Node 5: Projects 🔒 grey

"View Full Roadmap →" link right side


PAGE 4 — MY ROADMAP
Page title: "Your Career Roadmap"

Subtitle: "Goal: Data Science & Analytics | Target: 3 Months | Est. Placement: Sept 2026"
Top bar: goal title left, "Edit Goal" outline button, progress ring right (overall %)
Phase tabs below top bar:

All | Phase 1: Foundations | Phase 2: Core Skills | Phase 3: Projects | Phase 4: Placement
Vertical roadmap (center of page, max width 700px centered):
Connecting animated dashed line runs through all nodes
Each node row (full width):

Left side: connector line + circle node

Right side: content card
Node states:

Completed ✅: green filled circle, checkmark, green card border

Active 🔄: amber circle with pulse glow animation, "IN PROGRESS" amber badge

Locked 🔒: grey circle, lock icon, grey card, no hover effect
Content card (for each node):

Phase label top: "PHASE 1 — FOUNDATIONS" teal small caps
Topic title H4 white
Subtopics list: 3-4 bullet points, muted text, small
Meta row: "8 lessons · 3 days · ⭐ 240 XP"
Status badge right
Active node only: "Continue →" amber button right side

Hover on any unlocked node:

Card border glows
Tooltip appears: subtopics preview list

Sample nodes:

Phase 1 — Foundations:

Python Basics ✅
Data Types & Variables ✅
Functions & Scope 🔄 (active)
OOP in Python 🔒
Libraries: NumPy & Pandas 🔒

Phase 2 — Core Skills:

SQL Fundamentals 🔒
Data Visualization 🔒
Statistics for DS 🔒
Machine Learning Basics 🔒

Phase 3 — Projects:

EDA Project 🔒
ML Classification Project 🔒
Dashboard Project 🔒

Phase 4 — Placement Prep:

Resume Building 🔒
Mock Interviews 🔒
Company Research 🔒
Apply & Track 🔒


PAGE 5 — LEVELS / COURSE PAGE
Left sidebar (280px fixed):

Title: "Python → Data Science Path"

List of all levels with status icons

Active level highlighted amber bg tint

Each level shows: level number, title, XP, status icon

Clicking any unlocked level loads it in main area
Main content area:

Breadcrumb top: Home > Roadmap > Python Basics > Level 3
Level header:

"Level 3 — Functions & Scope" H2
XP badge: "⭐ 240 XP" amber
Estimated time: "⏱ 2 hours"
Progress: "2 of 6 lessons done" + mini progress bar

Video section:

Dark video player (16:9 ratio)

Custom amber play button center

Video title below: "3.1 — Introduction to Functions"

Playlist sidebar right of video: 6 lesson items, checkmarks on done ones
Tab bar below video:

Notes | Resources | Quiz | Discussion
Notes tab (default):

Clean readable content

Code blocks in dark mono font with syntax highlight colors

Key concept callout boxes: amber left border, dark bg
Resources tab:

List of resource cards:

Each card: type badge (Article/Video/Docs) + title + source name + "Open →" button

Teal badge = video, amber badge = article, green badge = documentation
Quiz tab:

"Test Your Knowledge — Level 3 Quiz"

5 MCQ questions one at a time

Each question: question text + 4 option buttons

Option buttons: dark border default, green fill on correct, red fill on incorrect

After answering: explanation text slides down

Score shown at end: "4/5 Correct! +180 XP Earned 🎉"

Retry button if score below 3
Right floating sticky panel (240px):

"Level Progress" card:

Circular progress ring
XP earned this session
"Mark Level Complete" amber button — on click: confetti burst + XP popup + modal


PAGE 6 — MOCK INTERVIEW PAGE
Page title: "Mock Interview Center 🎤"

Subtitle: "Practice makes placement. Get AI feedback on every answer."
Top filter bar:

Domain tabs: All | Technical | HR | Aptitude | Group Discussion

Difficulty pills: Easy | Medium | Hard

Round type pills: Round 1 — Aptitude | Round 2 — Technical | Round 3 — HR | Round 4 — Managerial
Interview Mode Cards (3 column grid):
Card 1 — Quick Practice

"Answer one question at a time. Get instant AI feedback."

"Start Practice →" teal button
Card 2 — Full Mock Interview

"Simulate a complete interview: Aptitude → Technical → HR. 45 minutes."

"Start Full Mock →" amber button
Card 3 — Topic-Wise Practice

"Pick a specific topic like Arrays, DBMS, or HR questions."

"Choose Topic →" outline button
Interview Rounds Explained section:

Title: "What to Expect in Each Round"

4 horizontal cards:
Round 1 — Online Aptitude Test:

Quantitative Aptitude
Logical Reasoning
Verbal Ability
Time: 60-90 minutes
Tips: "Practice speed. Use elimination method."

Round 2 — Technical Interview:

DSA & Problem Solving
Core CS Subjects (DBMS, OS, CN, OOP)
Project Discussion
Tips: "Explain your thought process. Draw diagrams."

Round 3 — HR Interview:

Tell me about yourself
Strengths & Weaknesses
Why this company?
Tips: "Be genuine. Use STAR method for answers."

Round 4 — Managerial Round:

Situational questions
Leadership & teamwork
Salary discussion
Tips: "Show confidence. Research the company well."

Each card: color coded border (blue/teal/amber/green), round number badge top right, tips section in italic muted text
Practice Question Section (below cards):
Filter selected: Round 2 Technical | Medium
Question card:

Dark surface card, full width

Top bar: "Question 12 of 50" left, difficulty badge "Medium" amber right

Question text H4: "Explain the difference between stack and queue with a real-world example."

Below question:

Your answer textarea (min 120px, full width, dark themed)
Placeholder: "Type your answer here... Be as detailed as you can."
"Get AI Feedback 🤖" amber button below textarea

After clicking Get AI Feedback:

Loading state: "🤖 Analyzing your answer..."

Then AI feedback card slides in below:
Feedback card:

Score: "7/10" large amber number
"Good Answer" green badge OR "Needs Improvement" amber badge
Section 1: "✅ What you got right:" — green bullet points
Section 2: "⚠️ What you missed:" — amber bullet points
Section 3: "💡 Model Answer:" — teal border left, clean text
"Next Question →" button bottom right

Interview History (bottom of page):

Title: "Your Practice History"

Table: Date | Topic | Round | Score | Time Taken

Sample rows pre-filled with dummy data

PAGE 7 — LEADERBOARD
Page title: "Top Learners 🏆"

Subtitle: "Compete, stay motivated, climb the ranks."
Filter tabs: This Week | This Month | All Time | My College
Top 3 Podium section:
Rank 2 (left, slightly lower): silver bg, avatar, name, XP count, silver badge

Rank 1 (center, tallest): gold glow border + animated crown above avatar, name, XP, gold badge, confetti static decoration around

Rank 3 (right, lowest): bronze bg, avatar, name, XP, bronze badge
Full leaderboard table below:

Columns: Rank | Name + Avatar | Career Goal | XP This Week | Badges | Streak | Change
Rank 1-3: gold/silver/bronze badge beside rank number

Current user row: amber tint background, "You" pill beside name

Change column: ▲ green (moved up) / ▼ red (moved down) / — grey (no change)
Row hover: slight lighter bg tint
Your Stats sidebar (right 280px):

"Your Ranking" card:

Current rank: "#47"
XP to next rank: "Need 240 more XP to reach #46"
Progress bar: amber
"Study Today →" amber button


PAGE 8 — AI CHATBOT
Page title: "Career Nanban AI 🤖"

Subtitle: "Your personal career mentor. Ask anything."
Full page split layout:
Left panel (320px) — Suggested Topics:

Section headers with topic chips:
🗺️ Roadmap Help:

"Build my roadmap for Data Science"

"What should I learn for full stack?"

"I'm a fresher, where do I start?"
💼 Interview Prep:

"Give me 10 HR interview questions"

"How do I answer 'Tell me about yourself'?"

"Explain DBMS concepts for interview"
📚 Learning Help:

"Explain recursion simply"

"What is the difference between SQL joins?"

"Suggest resources for machine learning"
🎯 Career Advice:

"Which companies hire data science freshers?"

"How to write a fresher resume?"

"What skills does TCS look for?"
Each chip: clickable, clicking fills chat input and auto-sends
Right panel (chat area):

Chat messages area (scrollable, no fixed height)
AI welcome message (first message):

Avatar: small CN amber circle

"Hi! I'm Career Nanban AI 👋 I'm here to help with your career journey. Ask me anything about learning paths, interview prep, skills, or job search!"
User message (right aligned):

Amber bg tint, white text, avatar right side
AI message (left aligned):

Dark card surface, teal left border, CN avatar left, white text
AI response can contain:

Plain text answer
Bullet point list (styled cleanly)
Code block (dark mono font, syntax colors)
Resource suggestion card (title + link chip)
"Practice Question" CTA card

Typing indicator (while AI responds):

3 dots bouncing in sequence, teal color, inside AI bubble
Chat input bar (fixed bottom):

Dark input field full width

Placeholder: "Ask anything about your career..."

Right side: Send button (amber, arrow icon)

Left side: topic suggestion icon button (opens left panel on mobile)

PAGE 9 — ACHIEVEMENTS & BADGES
Page title: "Achievement Wall 🏅"
XP Summary banner:

3 stat items in a row:

Total XP: 1,240 — amber star icon
Current Level: 12 — teal icon
Rank: Gold Learner — purple crown icon

Progress bar below: "240 XP to reach Platinum Rank" — teal fill

Badge categories tabs:

All | Learning | Streaks | Speed | Interview | Placement
Badge grid (4 columns):

Earned badges: full color, hexagon shape, glow border, hover shows tooltip

Locked badges: grey, blurred, lock overlay, hover shows "Complete X to unlock this"
Sample badges:

🌟 First Step — Complete your first lesson (earned)
🔥 Week Warrior — 7 day streak (earned)
⚡ Speed Learner — Complete level in under 1 hour (locked)
💯 Quiz Master — Score 100% on any quiz (locked)
🎤 Interview Ready — Complete first mock interview (locked)
🏢 Placement Bound — Apply to first company (locked)

Milestones Timeline (below grid):

Horizontal scroll

Each milestone: date circle + event name + XP earned

Connected by amber dashed line

Earned milestones: amber, future milestones: grey

IMPORTANT INSTRUCTIONS FOR DORA AI:

Every navbar link must navigate to its correct page — no dead links
All buttons must have working hover and click states
Onboarding steps must flow sequentially — Next button disabled until option selected
All form inputs must be interactive
Mobile responsive — all pages must work on 375px width
Dark mode only
Logo is a placeholder — leave a clearly labeled image slot everywhere
Use smooth transitions between all pages (fade or slide, 300ms)
All animations must be subtle — nothing flashy or distracting
XP popups must appear on task completion actions
Mock interview feedback section must show/hide on button click
Chatbot typing indicator must show while response loads


Nandhu paste this full prompt into dora.run and it will generate the complete Career Nanban website! 🚀
Want me to also write the GitHub README and Next.js folder structure so your team is ready for the coding phase too?