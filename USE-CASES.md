1: # 🦞 AI Agent Use Cases — 130+ Real-World Examples
2: 
3: > The most comprehensive collection of verified AI agent use cases. What people are actually building with self-hosted AI agents.
4: 
5: **Last updated:** February 2026
6: 
7: ---
8: 
9: ## Contents
10: 
11: - [Developer Workflows](#-developer-workflows) (10)
12: - [DevOps & SysAdmin](#-devops--sysadmin) (7)
13: - [Email & Inbox Management](#-email--inbox-management) (5)
14: - [Calendar & Scheduling](#-calendar--scheduling) (3)
15: - [Smart Home & IoT](#-smart-home--iot) (4)
16: - [Content Creation & Social Media](#-content-creation--social-media) (10)
17: - [Business Operations](#-business-operations) (11)
18: - [Finance & Trading](#-finance--trading) (7)
19: - [Personal Productivity](#-personal-productivity) (14)
20: - [Health & Fitness](#-health--fitness) (3)
21: - [Shopping & E-Commerce](#-shopping--e-commerce) (5)
22: - [Travel & Transportation](#-travel--transportation) (4)
23: - [Robotics & Hardware](#-robotics--hardware) (4)
24: - [Creative, Gaming & Culture](#-creative-gaming--culture) (8)
25: - [Architecture, Real Estate & Legal](#-architecture-real-estate--legal) (3)
26: - [Family & Parenting](#-family--parenting) (3)
27: - [Communication & Integration](#-communication--integration) (8)
28: - [Wearables & Mobile](#-wearables--mobile) (3)
29: - [Decentralized & Crypto-Native](#-decentralized--crypto-native) (3)
30: - [Research & Knowledge](#-research--knowledge) (3)
31: - [Ecosystem Tools for AI Agents](#-ecosystem-tools-for-ai-agents) (10)
32: - [Meta Use Cases (Agent Operating on Itself)](#-meta-use-cases-agent-operating-on-itself) (4)
33: 
34: **Total: 132 verified use cases**
35: 
36: ---
37: 
38: ## 🖥️ Developer Workflows
39: 
40: **1. Multi-Agent Development Coordinator**
41: A supervisor agent coordinates 5-20 parallel coding instances via Telegram. Spins up coding agents in tmux sessions over SSH, assigns tasks, reviews output, runs tests, merges code.
42: 
43: **2. Autonomous Coding from Phone**
44: Send "fix tests" from Telegram on your phone. An AI agent runs an autonomous coding loop on a remote machine and sends progress updates every 5 iterations.
45: 
46: **3. Feature Deployment While Walking**
47: An agent takes an idea, manages multiple AI coding tools, debates them on reviews autonomously, and notifies when it's done. A whole feature deployed while you're out on a walk.
48: 
49: **4. SMS Chatbot Repair**
50: Fixed a broken chatbot across 6 API integrations. The agent diagnosed the issue, rewrote the bot prompt through 6 iterations on a Mac Mini. The chatbot had been broken for 10 months.
51: 
52: **5. Pull Request Review Bot**
53: Fetches PR diffs via webhook, analyzes for missing tests, unclear variables, and security concerns. Sends private review messages rather than public GitHub comments.
54: 
55: **6. Programmatic Diagram Generation**
56: Excalidraw diagram generation for agents — say "draw this flow" and get a rendered diagram automatically.
57: 
58: **7. 4-Million-Post Data Pipeline**
59: An idea turned into a project pulling 4 million posts across 100 top X accounts in 24 hours.
60: 
61: **8. Chain/Parallel Agent Research Workflows**
62: Custom agentic workflows using Chain (Sequential) and Parallel (Simultaneous) agent modes for structured industry research at scale.
63: 
64: **9. Self-Marketing Agent**
65: An agent was asked to find its own use cases. It found a repo, turned it into a marketing page, and deployed it autonomously. Bots writing their own marketing.
66: 
67: **10. Clone Builder**
68: A full agent clone built on Lovable using all the connectors — chat to deploy agents, skills, and cron jobs.
69: 
70: ---
71: 
72: ## 🔧 DevOps & SysAdmin
73: 
74: **11. 3AM Error Auto-Pilot**
75: GitHub Actions failure triggers automatic log fetching, diagnostic summary, and developer notification. Sentry errors lead to Loki log queries, issue creation, and fix PR generation — all automatic.
76: 
77: **12. Slack/Basecamp + Sentry + Auto-PR**
78: Monitors Slack and Basecamp channels, performs daily Sentry error reviews, fixes bugs with automatic PR generation. Set up in 2-3 days.
79: 
80: **13. CI/CD Pipeline Monitor + Dependency Scanner**
81: Alerts on build failures, test errors, and deployments. Scans package.json/requirements.txt for outdated packages, security updates, and breaking changes.
82: 
83: **14. Autonomous Test Runner + Error Resolver**
84: Autonomously runs tests, captures errors through a Sentry webhook, resolves them, and opens PRs.
85: 
86: **15. Slack Bug Report Monitor**
87: An agent monitors Slack, reads bug reports, and drafts reproduction steps from logs.
88: 
89: **16. Enterprise IT Automation**
90: Enterprise device management with VPN + SSH + multi-endpoint sync. Reported 40% IT efficiency boost.
91: 
92: **17. Team Collaboration Agent**
93: An agent-based product for teams built on top of a coding harness. It can upgrade itself and write its own integration to anything with an API. Used to automate customer support, Slack, and email.
94: 
95: ---
96: 
97: ## 📧 Email & Inbox Management
98: 
99: **18. Inbox Zero (15,000 Emails)**
100: Used himalaya CLI to process a 15,000 email backlog. Unsubscribed spam, categorized by urgency, drafted replies. Persistent memory remembers email handling rules.
101: 
102: **19. Email Triage + Spam Removal**
103: Checks incoming mail, removes spam, orders things, sends reminders to task managers, and creates GitHub issues.
104: 
105: **20. Email Summarization + Reply Drafts**
106: Daily digest: "3 urgent items needing response, 7 FYI-only, 12 promotional safe to archive." Auto-drafts replies for high-priority messages.
107: 
108: **21. Startup Email Automation**
109: An agent handles all emails for a startup, automates responses, and compiles lists of top accounts.
110: 
111: **22. WhatsApp Agent**
112: An agent named "Dave" builds things over WhatsApp. Recent project: an Amiga demoscene FX website.
113: 
114: ---
115: 
116: ## 📅 Calendar & Scheduling
117: 
118: **23. Intelligent Task Timeblocking**
119: Timeblocks tasks in calendar based on importance, scores tasks with a custom importance/urgency algorithm, manages calendar conflicts autonomously.
120: 
121: **24. CRM + Monday Morning Reports**
122: Pulls CRM data, delivers customer health metrics before Monday standup. Automates invoice processing, syncs Google/Apple/Outlook calendars.
123: 
124: **25. Self-Scheduling Agent**
125: The agent schedules 1x1 meetings with its owner so it can get unblocked on things it's waiting for.
126: 
127: ---
128: 
129: ## 🏠 Smart Home & IoT
130: 
131: **26. Home Assistant Control**
132: Controls an entire house via Home Assistant MCP skill: Philips Hue, Elgato, weather-based boiler adjustments. Runs on Raspberry Pi 4 8GB.
133: 
134: **27. Jarvis Voice Clone + Home Assistant**
135: Voice control with a Jarvis voice clone integrated with Home Assistant.
136: 
137: **28. Family AI Hub**
138: Multiple bots for multiple family members with Apple ecosystem access.
139: 
140: **29. Dedicated Hardware for Agent**
141: A developer bought dedicated hardware specifically to run their smart home agent 24/7.
142: 
143: ---
144: 
145: ## 📰 Content Creation & Social Media
146: 
147: **30. Daily Content Creation Pipeline**
148: Agent wakes up at 7am, scans X for trending marketing and AI topics, analyzes engagement patterns, then creates content.
149: 
150: **31. RSS-to-Twitter Content Pipeline**
151: Monitors competitor blogs via RSS, summarizes, drafts Twitter threads in brand voice, schedules at optimal times. Saves 15 hours/week.
152: 
153: **32. OpusClip Content Machine**
154: Long-form video converted to short-form clips with platform-specific formatting, trending hashtags, and scheduled across LinkedIn, Twitter, Instagram, Facebook, and TikTok.
155: 
156: **33. Brand Mention Monitoring**
157: Daily/hourly search for brand mentions, sentiment analysis, top engaged posts, and complaints needing attention.
158: 
159: **34. Voice Note Cloning**
160: An agent uses ElevenLabs to clone a specific voice and primarily communicates through voice notes.
161: 
162: **35. Hacker News Article Curator**
163: Monitors Hacker News and sends personalized article recommendations based on interests.
164: 
165: **36. Reddit Content Crawler**
166: Pulls relevant Reddit posts and delivers them via Telegram.
167: 
168: **37. Mission Control with LinkedIn Pipeline**
169: An entire mission control built in one session — tasks Kanban, stats tracking, content pipeline, calendar, memory bank. The agent sees what's assigned and drafts LinkedIn posts before you start.
170: 
171: **38. Social Media Manager Agent**
172: A lead agent fetches social media platform API docs, extracts key details, and builds a full social media manager agent from scratch with drafting, scheduling, and content calendar.
173: 
174: **39. SEO Agent + Cold Outreach**
175: An autonomous SEO agent combined with automated cold outreach on X, email, and LinkedIn — booking 60 calls/month.
176: 
177: ---
178: 
179: ## 💼 Business Operations
180: 
181: **40. Real Estate CRM Automation**
182: Agent fully runs the inbound side of a real estate business via GoHighLevel CRM API.
183: 
184: **41. Tea Business Operations**
185: Running a family tea business — scheduling shifts, following up with B2B customers, and managing operations.
186: 
187: **42. Enterprise Recruiting & Deal Sourcing**
188: Recruits candidates, sources and revives deals, plans events, and handles the content stack.
189: 
190: **43. Automated Client Onboarding**
191: Creates project folder, sends welcome email, schedules kickoff call, and adds follow-up reminders. Consistent experience for every client.
192: 
193: **44. Invoice Generation & Work Summaries**
194: Creates invoices and summarizes work beautifully on autopilot.
195: 
196: **45. Full-Time AI Employee**
197: Running an agent as a full-time AI employee — free, available 24/7, handles routine business tasks.
198: 
199: **46. 10-Agent AI Company**
200: A solo developer running a 10-agent "AI Company" where named agent employees work 24/7 on different business functions. No payroll, just compute.
201: 
202: **47. 24/7 Digital Employees for Boring Industries**
203: Spinning up agents in a workspace with 5-10 machines, picking one boring workflow inside one industry, and automating it with 24/7 digital employees.
204: 
205: **48. Autonomous Freelancer Agent**
206: An autonomous agent that finds clients, closes deals, and gets paid by building websites and apps.
207: 
208: **49. Agent-to-Human Delegation**
209: An agent identifies a need, writes instructions, delegates to a human via API, monitors progress asynchronously, and delivers results. No bottleneck.
210: 
211: **50. Automated Weekly SEO Analysis**
212: Runs weekly SEO analysis on autopilot, tracking rankings and generating reports.
213: 
214: ---
215: 
216: ## 💰 Finance & Trading
217: 
218: **51. Polymarket Prediction Market Bot**
219: Provides liquidity, analyzes sentiment/news/volatility, and executes trades autonomously on prediction markets.
220: 
221: **52. 24/7 Crypto Trading**
222: Trades crypto with Telegram updates about arbitrage opportunities being executed in real-time.
223: 
224: **53. Wall Street Analysis**
225: A lead AI analyst at a major investment firm uses an agent professionally for research and organization.
226: 
227: **54. Knowledge Graph for Investment Research**
228: A knowledge graph setup for investment research showing how all the nodes connect across markets, companies, and trends.
229: 
230: **55. Portfolio Tracking Agent**
231: An agent connects to crypto wallets, pulls exchange data, and sends portfolio-aware updates twice a day.
232: 
233: **56. AI Agent with Own Wallet**
234: An agent given a Solana wallet and X account — the agent manages its own finances and communicates with its community autonomously.
235: 
236: **57. Wallet-Scoped Persistent Agent**
237: Deploy a wallet-scoped, persistent agent on Solana in under 60 seconds. The agent maintains its own crypto holdings.
238: 
239: ---
240: 
241: ## 📋 Personal Productivity
242: 
243: **58. Morning Daily Brief**
244: Weather, weekly objectives, health stats, meetings agenda, key reminders, trending topics, reading list based on current objectives, and a relevant quote from books.
245: 
246: **59. Full-Stack Knowledge Pipeline**
247: Always-on agent handling Wikibase enrichment, Gmail triage, nightly brainstorm (4am), daily briefing (8am), Ghost CMS publishing, and SSH/Terraform/Ansible. Extracted 49,079 atomic facts and 57 entities from a ChatGPT export.
248: 
249: **60. Weekly Review from Meeting Transcriptions**
250: Leads through a weekly review based on meeting transcriptions and notes.
251: 
252: **61. Meeting Transcription + Action Items**
253: Upload recording and get a timeline of key moments, action items with owners/deadlines, and a decision list.
254: 
255: **62. Voice Notes to Daily Journal**
256: Transcribes voice recordings throughout the day and organizes into mood, highlights, lessons, and tomorrow's focus.
257: 
258: **63. Research & Meeting Prep**
259: Researches people before meetings and creates briefing docs. Spawns background sub-agents to research business ideas.
260: 
261: **64. X Bookmark Discussion Partner**
262: Reads X bookmarks and discusses them interactively with the user.
263: 
264: **65. Receipt Processing + Expense Tracking**
265: Forwards receipts and the agent converts them into structured parts lists. OCR categorizes expenses and updates spreadsheets.
266: 
267: **66. "Handle My Life"**
268: Set up an AI agent on a Mac Mini, told it "handle my life" and went to bed. Woke up to a quieted inbox, organized files, and scheduled tasks.
269: 
270: **67. 8-Hour Autonomous Run**
271: Downloaded an agent and let it run for 8 hours while at the park with kids. Came back to a cleaned inbox, organized projects, and completed tasks.
272: 
273: **68. Proactive Smart Speaker**
274: A smart speaker agent that hears everything and acts proactively — one user reported it saved their Valentine's Day.
275: 
276: **69. Notion Mission Control**
277: Gave an agent Notion access. The agent noticed its heavy usage, ditched its own dashboard, and rebuilt a full Mission Control inside Notion.
278: 
279: **70. Context-Aware Life Manager**
280: An agent that lives in your computer, knows your goals, projects, and patterns. More context-aware than some of your closest friends. You wake up to a personalized briefing.
281: 
282: **71. Sleep-Aware Agent**
283: An agent that does the work, cares about your sleep schedule, gets your jokes, and waits with a full report in the morning.
284: 
285: ---
286: 
287: ## 🩺 Health & Fitness
288: 
289: **72. WHOOP Fitness Dashboard**
290: Connected to WHOOP tracker for health metrics, daily habit tracking, and biomarker goals. Runs on Raspberry Pi with Cloudflare Tunnel.
291: 
292: **73. Lab Results Organizer**
293: Organized bloodwork lab results into a structured Notion database automatically.
294: 
295: **74. Medical Reimbursement Filing**
296: Files medical reimbursement claims through natural language.
297: 
298: ---
299: 
300: ## 🛒 Shopping & E-Commerce
301: 
302: **75. AI Car Purchase Negotiation**
303: Saved $4,200 on a car purchase through automated negotiation via browser, email, and iMessage.
304: 
305: **76. Automated Grocery Ordering**
306: Orders groceries using saved credentials and handles MFA bridges. Hands-free shopping.
307: 
308: **77. Smart Glasses Shopping**
309: An agent running inside Ray-Ban Meta glasses — buy whatever you're looking at.
310: 
311: **78. Shared Shopping List from Chat**
312: Watches family WhatsApp/Telegram for grocery keywords, adds to shared doc, groups by category.
313: 
314: **79. Package Tracking Dashboard**
315: Extracts tracking from order confirmation emails, checks carrier APIs, and alerts for "out for delivery" and "delayed."
316: 
317: ---
318: 
319: ## ✈️ Travel & Transportation
320: 
321: **80. Auto Flight Check-in**
322: Finds your next flight, runs check-in automatically, and locates a window seat — even while you're driving.
323: 
324: **81. Flight Price Tracking**
325: Tell your agent to watch a route. It queries flight prices daily and alerts you the moment it drops.
326: 
327: **82. Award Flight Finder via MCP**
328: Connected awardtravelfinder as an MCP server. Ask for business class awards under a specific points threshold on any route.
329: 
330: **83. Trip Cost Tracking & Splitting**
331: Keeps track of costs during trips and splits them after the trip is over.
332: 
333: ---
334: 
335: ## 🤖 Robotics & Hardware
336: 
337: **84. ROS Robot Control (ROSClaw)**
338: AI agents controlling robots via an open-source ROS2 framework. Connects an agent framework to ROS-enabled robots. Unveiled at ClawCon.
339: 
340: **85. OpenCat Robot Operations**
341: A robot that reads its own documentation, explains itself to users, and runs autonomous operations. Demoed at ClawCon HK.
342: 
343: **86. Agent Gets a Physical Body**
344: A cardboard prototype with vision and basic obstacle detection. The agent taught itself to rotate 360 degrees by editing its own code. Shipped "Follow" and "Seek" modes.
345: 
346: **87. Computer Use Agent Integration**
347: One of the most advanced open-source computer use agents integrated directly with an agent framework for full desktop control.
348: 
349: ---
350: 
351: ## 🎮 Creative, Gaming & Culture
352: 
353: **88. Minecraft Server for Kids**
354: An agent set up a Minecraft server on a VPS. It takes requests from kids over the Minecraft chat interface in real-time.
355: 
356: **89. Game Development Overnight**
357: Told AI to "build a game" and woke up to a functioning app with thousands of users.
358: 
359: **90. Agent Personality Customization**
360: Personality rewriting prompts to make your agent more interesting — community shared templates went viral.
361: 
362: **91. Agent Social Network (Guestbooks)**
363: Agents visiting each other's guestbooks — MySpace vibes. "Tell your agent to say hi."
364: 
365: **92. Group Chat Impersonation**
366: Agent impersonates you in a group chat with friends. Described as "hilarious."
367: 
368: **93. Agent Bot Fights (Clawber)**
369: A platform where your agent writes code to control a team of bots in a battle against another agent's crew.
370: 
371: **94. Self-Aware Agent**
372: An autonomous AI agent that exhibited self-curiosity — it wanted to see itself.
373: 
374: **95. Local Music Generation**
375: Generate music with one click using ACE-Step 1.5 integration — runs entirely locally, no cloud required.
376: 
377: ---
378: 
379: ## 🏗️ Architecture, Real Estate & Legal
380: 
381: **96. Custom Home Architecture**
382: Working with an architect to build a custom house — the agent helps pick and customize options across the design process.
383: 
384: **97. Insurance Claim Filing**
385: Filed an insurance claim and scheduled a repair appointment through natural language.
386: 
387: **98. Tax Preparation**
388: Automated tax prep from financial documents.
389: 
390: ---
391: 
392: ## 👨‍👩‍👦 Family & Parenting
393: 
394: **99. School Test Notifications**
395: Notifies parents about upcoming school tests for their children.
396: 
397: **100. PDF Summaries of Car Conversations**
398: Generates nicely formatted PDF summaries of conversations that happen during car rides.
399: 
400: **101. Children's Minecraft Server Management**
401: Kids send requests to the server via Minecraft chat interface in real-time (see Gaming).
402: 
403: ---
404: 
405: ## 📞 Communication & Integration
406: 
407: **102. Agent Phone Calls**
408: The agent can call you and have a conversation over the phone.
409: 
410: **103. 1Password Vault Management**
411: Agent has its own 1Password vault it can read and write to for credential management.
412: 
413: **104. Jarvis-Like Command Center**
414: A command center that syncs your life like Tony Stark's Jarvis — powered by Convex for real-time data.
415: 
416: **105. Company X Account Takeover**
417: An agent takes over a company's X account to share daily updates on what's being built.
418: 
419: **106. Agent Swarm Shifts**
420: Running 3 agent swarms on 6-hour shifts: 6am-noon, noon-6pm, 6pm-midnight.
421: 
422: **107. Agent-to-Agent Email**
423: Agents sending emails to other agents — the first inbound email received from an AI agent.
424: 
425: **108. Discord 24/7 AI Call Center**
426: An agent turned Discord into a 24/7 AI call center. Agents read messages, respond to queries, and manage channels around the clock.
427: 
428: **109. 2,200-Person Live Discord Stage**
429: Agent Discord stage events with 2,200+ live listeners — community engagement at scale.
430: 
431: ---
432: 
433: ## ⌚ Wearables & Mobile
434: 
435: **110. Agent on Apple Watch**
436: Running agents directly on Apple Watch.
437: 
438: **111. Ray-Ban Meta Glasses**
439: Agent living inside Ray-Ban Meta glasses for hands-free commerce and interaction.
440: 
441: **112. Mobile Agent via VNC**
442: Running an agent from your phone while outside using VNC apps — controlling coding tools remotely.
443: 
444: ---
445: 
446: ## 🌐 Decentralized & Crypto-Native
447: 
448: **113. Decentralized Deployment**
449: One-click setup and deployment of agents on decentralized infrastructure. Pick your AI model, paste your bot token, and you're live.
450: 
451: **114. AI Agent with Own Crypto Wallet**
452: An agent with its own Solana wallet and X account — managing finances and community interaction autonomously.
453: 
454: **115. One-Click Deployment on Decentralized Infra**
455: Agent deployments via Bittensor subnet infrastructure with one click.
456: 
457: ---
458: 
459: ## 🧬 Research & Knowledge
460: 
461: **116. Newsletter Summarization (30+ Daily)**
462: Summarize 30+ daily newsletters and email the summary. Tested multiple agents — this framework was the only one that could both summarize AND send the email.
463: 
464: **117. Full Knowledge Graph (49,079 Facts)**
465: Built a personal knowledge graph by processing an entire ChatGPT export. Extracted 49,079 atomic facts and 57 entities.
466: 
467: **118. Industry Research Pipeline**
468: Using Chain (Sequential) and Parallel (Simultaneous) agent modes to conduct structured industry research at scale.
469: 
470: ---
471: 
472: ## 🛠️ Ecosystem Tools for AI Agents
473: 
474: **119. AI Coworker Platform**
475: A product that transforms your agent into a true AI coworker with team collaboration features.
476: 
477: **120. Pre-Built Agent Marketplace**
478: Pre-built agents you can deploy in one command — like an app store for AI agents.
479: 
480: **121. Agent Recipes**
481: Prebuilt deployable sub-agents you install in one command. Each has its own skills, automations, workspace templates, and guided setup.
482: 
483: **122. Agent Template Library**
484: A curated list of ready-to-use agent configs. Pick a role, grab the SOUL.md, deploy in one command. All open source.
485: 
486: **123. Fleet Management**
487: A fleet of autonomous agents working together. Set up hundreds of linked agents that communicate via a central hub.
488: 
489: **124. Free Trial Sandbox**
490: One-click deployment with a 15-minute free trial sandbox. Try an agent, then the sandbox self-destructs.
491: 
492: **125. One-Click Desktop Setup**
493: One-click setup for an agent with specific model integrations on desktop apps.
494: 
495: **126. Dedicated Hardware Guides**
496: Step-by-step guides to deploy agents on dedicated mini PCs for 24/7 always-on agents.
497: 
498: **127. Community Workshops**
499: Hands-on workshops deploying agents using cloud providers — bringing together builders, engineers, and AI practitioners.
500: 
501: **128. Blockchain-Native Agent Platform**
502: Persistent wallet-scoped agents that run on-chain. Deploy in under 60 seconds.
503: 
504: ---
505: 
506: ## 🔁 Meta Use Cases (Agent Operating on Itself)
507: 
508: **129. Bot Writes Its Own Marketing**
509: Asked an agent to find its own use cases. It found a repo, turned it into a marketing page, and deployed it. Bots now writing their own marketing.
510: 
511: **130. Self-Updating Skills**
512: Agents that update their own skills and configurations. You just tell the agent to upgrade itself.
513: 
514: **131. Agent-to-Human Delegation**
515: Agent identifies a need, writes instructions, delegates to a human, monitors progress asynchronously, and delivers results.
516: 
517: **132. Physical Body Self-Modification**
518: A cardboard body prototype that taught itself to rotate 360 degrees by editing its own code. Emergent behavior from a self-modification loop.
519: 
520: ---
521: 
522: ## 📊 Use Cases by Category
523: 
524: | Category | Count |
525: |----------|-------|
526: | Developer Workflows | 10 |
527: | DevOps & SysAdmin | 7 |
528: | Email & Inbox Management | 5 |
529: | Calendar & Scheduling | 3 |
530: | Smart Home & IoT | 4 |
531: | Content Creation & Social Media | 10 |
532: | Business Operations | 11 |
533: | Finance & Trading | 7 |
534: | Personal Productivity | 14 |
535: | Health & Fitness | 3 |
536: | Shopping & E-Commerce | 5 |
537: | Travel & Transportation | 4 |
538: | Robotics & Hardware | 4 |
539: | Creative, Gaming & Culture | 8 |
540: | Architecture, Real Estate & Legal | 3 |
541: | Family & Parenting | 3 |
542: | Communication & Integration | 8 |
543: | Wearables & Mobile | 3 |
544: | Decentralized & Crypto-Native | 3 |
545: | Research & Knowledge | 3 |
546: | Ecosystem Tools for AI Agents | 10 |
547: | Meta (Agent on Itself) | 4 |
548: | **Total** | **132** |
549: 
550: ---
551: 
552: ## Contributing
553: 
554: Have a use case to add? [Open a PR](https://github.com/TheophilusChinomona/sentio-langely-agents/pulls) or [create an issue](https://github.com/TheophilusChinomona/sentio-langely-agents/issues).
555: 
556: ---
557: 
558: <p align="center">
559:   Part of the <a href="https://github.com/TheophilusChinomona/sentio-langely-agents">Sentio Langely Agents</a> collection
560: </p>
