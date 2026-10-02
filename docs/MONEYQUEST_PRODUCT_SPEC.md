# MONEYQUEST

## 1. PRODUCT VISION

MoneyQuest is a game-based learning platform where children learn mathematics, financial literacy, decision-making, saving, spending, investing and entrepreneurship by managing a completely virtual economy.

The core loop is:

STUDY → EARN → DECIDE → EXPERIENCE CONSEQUENCES → LEARN → IMPROVE

The child should feel that they are playing a game.

The parent should feel that the child is learning useful real-world skills.

The product must NOT depend on paid generative-AI APIs.

All core intelligence must work through:

* deterministic rules
* structured educational content
* simulations
* formulas
* question banks
* local/open-source processing where necessary

---

# 2. TARGET USERS

## Primary

Children aged 10–14.

Initial MVP:

* Ages 10–12
* Classes approximately 5–7
* Mathematics + financial literacy

## Secondary

Parents of children aged 10–14.

Parents are the paying customer.

Children are the primary users.

---

# 3. CORE PRODUCT PHILOSOPHY

MoneyQuest should NOT lecture children about money.

It should allow children to EXPERIENCE money.

Example:

A child receives ₹1,000 virtual money.

They spend ₹900.

Later an unexpected ₹500 expense appears.

They cannot afford it.

The game explains:

"You didn't have enough emergency savings."

The child learns through consequences.

The system should never shame the child for making a decision.

There should be no "wrong financial personality."

Instead, the game should explain trade-offs.

---

# 4. VIRTUAL MONEY

All money inside the game is virtual.

It has NO real-world monetary value.

Initial balance:

₹1,000

The child can increase virtual wealth by:

* completing academic quizzes
* completing learning missions
* completing financial challenges
* completing business activities
* achieving learning streaks
* reaching educational milestones

The child cannot purchase virtual money using real money.

Parents cannot transfer real money into the child's wallet.

---

# 5. EARNING SYSTEM

Academic activities are the primary earning mechanism.

Example:

Math Quiz:

* Participation: ₹20
* 60–79%: ₹50
* 80–89%: ₹75
* 90–100%: ₹100

Science Quiz:
Same basic structure.

Weekly challenge:
₹100–₹300.

Chapter completion:
₹200.

Important:

Rewards should be calibrated so that children cannot become wealthy simply by repeatedly answering trivial questions.

The system should include diminishing rewards for repeated attempts.

---

# 6. XP SYSTEM

Money and XP are separate.

Money represents financial resources.

XP represents learning/game progression.

Example:

10-question quiz:

* 100 XP
* ₹75

Chapter mastery:

* 500 XP
* ₹250

XP determines:

* player level
* unlocked locations
* unlocked businesses
* new financial concepts
* new investment products
* cosmetic rewards

Money does NOT determine academic level.

---

# 7. PLAYER LEVELS

Example:

Level 1:
Money basics

Level 2:
Needs vs wants

Level 3:
Saving

Level 4:
Budgeting

Level 5:
Interest

Level 6:
Investing

Level 7:
Risk

Level 8:
Business

Level 9:
Loans

Level 10:
Insurance

Level 11:
Inflation

Level 12:
Portfolio management

More levels can be added later.

---

# 8. CHILD HOME SCREEN

The home screen should feel like a game dashboard.

Display:

* Avatar
* Name
* Level
* XP
* XP required for next level
* Wallet balance
* Savings
* Investments
* Net worth
* Current goal
* Daily mission
* Learning streak

Example:

MONEYQUEST

ADI
LEVEL 8

₹4,850 Wallet

₹2,500 Savings

₹3,200 Investments

Net Worth:
₹10,550

Today's Mission:
Complete a Maths Challenge

Reward:
+100 XP
+₹100

---

# 9. EARN SCREEN

The child sees available ways to earn.

Categories:

ACADEMIC

* Maths
* Science
* English

FINANCIAL

* Budget challenge
* Saving challenge
* Investment challenge

LIFE

* Decision challenge
* Business challenge

Each activity shows:

Difficulty
Expected time
XP reward
Money reward

---

# 10. EDUCATIONAL QUIZ ENGINE

The MVP should start with Mathematics.

Each question must contain:

* subject
* chapter
* topic
* difficulty
* question
* options
* correct answer
* explanation
* XP reward
* money reward

The system records:

* attempts
* score
* time taken
* mistakes
* topic
* difficulty

---

# 11. MISTAKE ENGINE

MoneyQuest should remember academic mistakes.

Example:

Child answers 5 percentage questions:

3 incorrect.

System records:

Topic:
Percentages

Accuracy:
40%

Status:
Needs Practice

The system can then recommend:

"Practice Percentages"

The recommendation engine must initially use deterministic rules.

Example:

IF topic accuracy < 60%
AND attempts >= 5

THEN:
weak_topic = true

IF topic accuracy > 85%
AND attempts >= 10

THEN:
topic_mastered = true

---

# 12. SPENDING SYSTEM

The child has a virtual marketplace.

Categories:

## Wants

Chocolate
Games
Toys
Movies
Entertainment

## Needs

School supplies
Books
Transport
Basic necessities

## Growth

Books
Courses
Educational tools
Skill activities

The purpose is NOT to classify wants as bad.

The game should teach:

"Every purchase has an opportunity cost."

---

# 13. PURCHASE CONSEQUENCES

Example:

Chocolate:
Cost ₹100

Immediate:
Enjoyment +10

Long-term:
No financial asset created.

Book:
Cost ₹100

Immediate:
Knowledge +5

Potential:
Unlock reading challenge.

Investment:
Cost ₹100

Potential future value:
Variable.

The game should make the consequences visible.

---

# 14. GOALS

Children can create virtual goals.

Examples:

Bicycle:
₹5,000

Headphones:
₹3,000

Gaming setup:
₹10,000

Book collection:
₹2,000

Trip:
₹8,000

The system shows:

Current:
₹1,850

Goal:
₹5,000

Progress:
37%

The child can choose how to reach the goal:

* save
* earn
* complete missions
* start a business
* invest

---

# 15. SAVINGS

Introduce a savings account.

Example:

Wallet:
₹2,000

Savings:
₹5,000

Savings should have a small simulated interest rate.

The game should explain:

"Your money earned ₹X because you kept it saved."

The rate must be configurable by the game administrator.

---

# 16. INVESTMENT SYSTEM

All investments are virtual.

MVP investment categories:

1. Savings
2. Fixed-income product
3. Mutual-fund-style diversified fund
4. Stocks

Later:

* bonds
* gold
* index funds
* business investments

Do not use real-money investment functionality.

---

# 17. STOCK MARKET

The first market should use fictional companies.

Examples:

SolarSpark
TechNova
ChocoMax
Move Motors
HealthPlus
FinBank

Each company has:

* price
* sector
* risk level
* historical price
* company description
* events

Prices are controlled by the simulation engine.

Do NOT initially depend on real stock APIs.

---

# 18. MARKET EVENTS

The market periodically generates predefined events.

Example:

SolarSpark:

"SolarSpark opened a new factory."

Price:
₹100 → ₹112

Another event:

"SolarSpark's project was delayed."

Price:
₹112 → ₹96

The child can click:

WHY?

The system explains the event using predefined content.

No LLM required.

---

# 19. RISK SYSTEM

Each investment has:

* expected volatility
* risk rating
* potential reward
* historical performance

Do not display:

"This investment is good."

Instead display:

"Historically more volatile."

The objective is to teach trade-offs.

---

# 20. BUSINESS SIMULATION

At a higher level, the child can start a virtual business.

Initial business:

Lemonade Stand.

Inputs:

Inventory
Price
Marketing
Sales
Expenses

Example:

50 units × ₹20

Revenue:
₹1,000

Costs:
₹400

Profit:
₹600

The child learns:

Revenue ≠ Profit.

Later businesses can include:

* stationery shop
* gaming store
* bakery
* online store
* farm
* technology company

---

# 21. LIFE EVENTS

The game occasionally introduces events.

Examples:

Bicycle repair:
₹500

Laptop repair:
₹1,500

Birthday gift:
₹300

Educational course:
₹2,000

Unexpected expense:
₹800

Opportunity:
"Buy a used bicycle for ₹2,000."

The events should teach:

* emergency funds
* planning
* opportunity cost
* insurance
* budgeting

Events should not be excessively negative.

The purpose is learning, not punishment.

---

# 22. SKILL → INCOME SYSTEM

Later levels introduce virtual jobs.

Example:

Math skill level 5:
Junior Calculator

Math skill level 10:
Junior Analyst

English skill level 10:
Content Creator

Coding skill level 10:
Junior Developer

Each job has:

* skill requirement
* virtual income
* time requirement

This teaches:

Skills → opportunities → earning potential.

---

# 23. FUTURE SIMULATION

The child should eventually be able to simulate:

"What happens if I continue making these decisions?"

Example:

AGE 10
Net worth:
₹5,000

AGE 12
₹18,000

AGE 15
₹48,000

AGE 18
₹110,000

The simulation should allow:

"What if I saved more?"

"What if I spent more?"

"What if I invested?"

"What if I started a business?"

This demonstrates long-term consequences and opportunity cost.

---

# 24. PARENT DASHBOARD

Parents should NOT need to watch the game.

Dashboard should show:

## Academic

Math:
82%

Science:
76%

English:
89%

## Learning

Questions answered:
187

Learning time:
3h 42m

Current streak:
6 days

## Weak areas

Fractions
Percentages

## Financial learning

Saving:
Strong

Budgeting:
Developing

Risk understanding:
Needs practice

Goal planning:
Strong

## Virtual economy

Wallet:
₹2,400

Savings:
₹4,000

Investments:
₹3,200

Net worth:
₹9,600

---

# 25. PARENT INSIGHTS

The system should produce rule-based insights.

Examples:

"Your child improved Mathematics accuracy from 68% to 81% this week."

"Your child is repeatedly making mistakes with percentages."

"Your child completed 4 learning missions this week."

"Your child has been consistently saving toward a goal."

"Your child has taken several high-risk virtual investments."

These are observations, not psychological assessments.

---

# 26. PARENT-CHILD CHALLENGES

Parents can create challenges.

Example:

Challenge:
Earn ₹1,000 this week.

Requirements:
Complete 5 academic missions.

Reward:
Special avatar item.

Parent can see progress.

---

# 27. ACHIEVEMENTS

Examples:

First ₹1,000 saved

First investment

First business

First ₹10,000 net worth

7-day learning streak

100 maths questions

First profitable business

First diversified portfolio

Completed first financial challenge

Achievements should reward learning and exploration.

---

# 28. GAME ECONOMY PRINCIPLES

Avoid:

* gambling mechanics
* loot boxes
* paid random rewards
* real-money trading
* real-money investment
* manipulative notifications
* excessive streak pressure

The game must teach healthy financial behaviour.

Virtual investing must never become gambling.

---

# 29. NO PAID AI API REQUIREMENT

The product must function without:

OpenAI API
Claude API
Gemini API
Any paid LLM API

AI can be considered later as an optional feature.

Core product must never depend on it.

---

# 30. TECHNOLOGY

Frontend:
Next.js
TypeScript
React

Backend:
Python
FastAPI

Database:
PostgreSQL

Charts:
Recharts

Authentication:
Email/password initially

Deployment:
Docker

Architecture:
Frontend → API → PostgreSQL

Game calculations must be performed server-side for important values.

The browser must not be trusted to calculate wallet balances or investment values.

---

# 31. DATABASE CORE ENTITIES

Users

Parents

Children

ParentChildRelationships

Subjects

Chapters

Topics

Questions

QuestionAttempts

LearningProgress

Wallets

Transactions

Goals

SavingsAccounts

Investments

InvestmentHoldings

Companies

MarketPrices

MarketEvents

Businesses

BusinessTransactions

LifeEvents

Achievements

XPTransactions

Notifications

---

# 32. SECURITY PRINCIPLES

Parent accounts and child accounts must be separated.

Children must not be able to:

* access parent data
* modify their wallet directly
* modify quiz rewards
* modify investment prices
* access another child's data

All important game calculations must happen server-side.

---

# 33. MVP SCOPE

DO NOT build everything initially.

MVP should contain:

1. Parent registration
2. Child profile
3. Child dashboard
4. Virtual wallet
5. XP
6. Mathematics quiz system
7. Rewards
8. Spending
9. Savings
10. Goals
11. Basic fictional investments
12. Basic parent dashboard

Do NOT build initially:

* real stocks
* business simulation
* loans
* insurance
* multiplayer
* school accounts
* mobile apps
* AI tutor
* complex avatars
* real payments

---

# 34. MVP SUCCESS CRITERIA

The MVP is successful if:

1. A child understands the game without an adult explaining it extensively.

2. A child voluntarily returns to play.

3. A child completes academic challenges to earn virtual money.

4. A child understands that spending reduces available money.

5. A child understands that saving delays spending for future goals.

6. A child understands that investing involves risk.

7. A parent can see meaningful academic and financial-learning progress.

The most important metric:

RETENTION.

If children do not voluntarily return, adding more features will not solve the fundamental problem.

---

# 35. DEVELOPMENT PRINCIPLE

Build in small milestones.

Never ask an agent to build the entire application at once.

Every milestone must:

1. Build
2. Run
3. Test
4. Commit to Git
5. Review
6. Continue

Git commits should represent working milestones.

---

# 36. FIRST DEVELOPMENT MILESTONE

Build ONLY:

* project structure
* Next.js frontend
* FastAPI backend
* PostgreSQL connection
* Docker setup
* authentication foundation
* parent account
* child profile
* basic dashboard
* wallet
* transaction ledger
* XP system

Do NOT build the stock market yet.

Do NOT build the full quiz system yet.

Do NOT build the business simulation yet.

First establish a reliable foundation.

---

# 37. DEFINITION OF DONE FOR MILESTONE 1

A developer should be able to:

1. Start the project locally with one documented command.

2. Open the web application.

3. Create a parent account.

4. Create a child profile.

5. Log into the child account.

6. See the child dashboard.

7. See virtual money balance.

8. Earn virtual money through a test reward.

9. Spend virtual money through a test transaction.

10. See transaction history.

11. Earn XP.

12. See current level.

13. Restart the application without losing data.

14. Run automated tests successfully.

15. Run the application in Docker.

No placeholder functionality should silently pretend to work.

---

# 38. PRODUCT DESIGN DIRECTION

Visual style:

Modern
Playful
Clean
Premium
Not childish

Avoid excessive cartoon styling.

Target visual feeling:

"Game + finance + education"

rather than:

"School website."

The child interface should be colourful and exciting.

The parent interface should be calm, clean and analytical.

---

# 39. PRODUCT RULE

Every feature must answer at least one question:

"What does the child learn?"

"What decision does the child make?"

"What consequence does the child experience?"

"What useful information does the parent receive?"

If a feature does none of these, do not add it to the MVP.

---

# 40. LONG-TERM VISION

MoneyQuest can eventually become a complete virtual life simulator where children learn:

Education
Money
Saving
Investing
Business
Risk
Decision-making
Planning
Entrepreneurship
Consumer awareness
Career decisions

The ultimate goal is:

A child should finish using MoneyQuest with a better understanding of how decisions today affect opportunities tomorrow.
