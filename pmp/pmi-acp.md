---
layout: page
title: "PMI-ACP 筆記"
---

# PMI-ACP 筆記

## Domain 1：Agile Principles and Mindset (敏捷原則及心態)
### SM角色的責任
Scrum Master要扮演牧羊犬的角色，避免羊群（developers）受到「大野狼」的騷擾

1. Coach：ScrumMaster對團隊與Product Owner（PO）具有教練的責任，協助這兩個角色扮演好他們各自的責任。所謂教練的責任，並不是說ScrumMaster要直接接手團隊與PO的問題，而是從旁觀察團隊與PO如何運用Scrum與敏捷開發方法，並且協助他們解決自己的問題，養成持續改善的文化。
2. Servant Leader：有人翻成「僕人式領導」、「僕人領袖」或「服務領導」，簡單的說，ScrumMaster不是團隊的管理者，所以他的心態不是「團隊今天要幫我做什麼」，而是反過來問「我今天可以做什麼協助團隊變得更有效率？」
3. Process Authority：對於團隊而言，ScrumMaster是流程的權威，也就是說ScrumMaster要對於Scrum流程、敏捷開發精神都很了解。
4. Interference Shield：ScrumMaster是牧羊犬，要保護團隊（羊）不被大野狼干擾。
5. Impediment Remover：雖然ScrumMaster扮演顧問角色且不應直接接手解決團隊與PO本身的問題，但如果他們所遭遇的問題本身無力加以排解，而且對生產力形成阻礙，此時ScrumMaster就應該接手加以排除這些阻礙。在公司中常見的阻礙有跨部門協調工作與公司既有規範過於僵化。例如，公司統一規定員工使用的筆電等級只能用i5的CPU與4G的記憶體。對於開發人員而言，這種等級的電腦速度太慢，但團隊成員無法自行申請更高等級的電腦。
6. Change Agent：ScrumMaster的終極責任就是扮演組織的變革媒介，讓改變與持續改善不只發生在團隊內部，也可以逐漸影響整個組織。與前五點相比，要做好這一點更加困難。

### Scrum
- Scrum is an iterative, incremental framework for project management often seen in agile software development, a type of software engineering.（Scrum是一種迭代式增量軟體開發過程，通常用於敏捷軟體開發。）-Wikipedia
- Scrum is a management and control process that cuts through complexity to focus on building software that meets business needs.-Ken Schwaber 與 Mike Beedle 在 Agile Software Development with Scrum, p 2.
### Definition of Timeboxing(時間箱)
- source [Definition of Timeboxing](https://www.scruminc.com/what-is-timeboxing/)
- Timeboxing is allotting a fixed, maximum unit of time for an activity. That unit of time is called a time box. The goal of timeboxing is to define and limit the amount of time dedicated to an activity.

- In Scrum, timeboxing is a critical component of all five events. Some Scrum teams also use timeboxing during a Sprint to concretely define open-ended tasks. An example of an open-ended task might be conducting research that is necessary for the team to reach a decision or to estimate the size and complexity of an upcoming story.
![What is Timeboxing?](https://tinyurl.com/yaqq79er)

- Timeboxing is a common feature of many project management methodologies because timeboxing keeps teams focused on accomplishing the task at hand by providing a clear definition of done.

- Timeboxing also encourages teams to start getting work done immediately. Temporal Motivation Theory shows that time constraints are a critical component of getting work done efficiently.  In Scrum, the sooner you can inspect a deliverable, the sooner you can adapt it.

### Sprint:(衝刺) 
- Timeboxing is used to define the length of the Sprint. The Sprint is a timebox of one month or less in which the scrum team will deliver the Sprint goals. At Scrum Inc., our Sprint timebox is one week and this is what we recommend to teams that we coach.

### Sprint Planning: 
- When a team launches, they establish the timebox for the Sprint Planning meeting. As noted in the Scrum Guide, a Sprint planning meeting should be timeboxed at 8 hours or less for a one-month Sprint. The shorter the Sprint, the shorter the timebox should be for Sprint Planning. At Scrum Inc., *** we recommend one-week Sprints and a two-hour timebox for Sprint Planning. ***

### Daily Scrum:(衝刺規劃) 
- The Daily Scrum is a timebox of *** 15 minutes for each 24-hour period *** that helps the Scrum Team synchronize activities and make visible any impediments to achieving the Sprint Goal.

### Sprint Review: (衝刺)-檢視回饋到『輸入的需求端』
- The Sprint Review is a *** timebox of four hours or less for one-month Sprints.***  During the Sprint Review, Sprint Backlog items delivered during the sprint are demonstrated and inspected. It is also a time to adapt the backlog based on feedback.

### Sprint Retrospectives: (回顧/lesson learned)-『回顧或是反省會議』回饋到『開發流程』
- The Sprint Retrospective is a *** timebox of three hours or less for a one month sprint *** . This is an event in which the team inspects itself and identifies a process improvement that the team will implement in the following sprint.

### What is the difference between the Sprint Review and the Sprint Retrospective?
- source Agile Software Development: What is the difference between the Sprint Review and the Sprint Retrospective? - Quora http://bit.ly/2p5ssUp
- The Sprint Review is equivalent to *** a user acceptance test***. It is where the project team demonstrates the results of the work that they have done in the sprint and the Product Owner and any required stakeholders accept the work or not.

- A Sprint Retrospective is equivalent to a project post-mortem except that it is *** done at the end of a sprint***. The purpose of the meeting is to reflect on what went well and what didn't go well in the previous sprint and determine how it can be improved in the next sprint.

- In simple terms, the ***Sprint Review is focused on the "product" and maximizing the business value of the results of the work of the previous sprint*** and the *** Sprint Retrospective is focused on the process and continuous process improvement.***
- Scrum 有如下圖所示的『雙重回饋機制』。在軟體開發中，下圖左邊的『輸入』是『軟體需求』，中間『流程』那一塊表示軟體開發活動，最後的『輸出』表示軟體本身（也可以包含設計與使用文件等）。從輸入經過開發流程到產品輸出，在 Scrum 的術語中這一段時間稱之為『sprint（短跑或衝刺）』，另一個與 sprint 相同意思但卻更一般化的說法叫做『iteration』。廣義的來說，敏捷方法（agile methods）將一個軟體專案的開發時程（假設 6 個月）切割成若干個『時間長度固定（time-boxing）』，例如兩個禮拜的開發活動，這種時間長度固定的週期就稱之為一個 sprint 或是一個 iteration。如果一個專案是 6 個月後要釋出產品，開發團隊採用為期兩週的 sprint，那麼這個專案就一共有 12 個 sprints（先不要管每一個 sprint 要做什麼，以及如何將需求分配到每個sprint 這些問題）。
![scrum 雙重回饋](https://tinyurl.com/ycftt4l9/)
- 採用 Scrum 的團隊就是要在每一個 sprint 結束之前（每兩週）完成上圖從輸入端丟入軟體需求，然後經過開發流程，最後產生產品。圖中從輸出那端拉了『兩條回饋線』，一條透過『demo meeting（sprint demo or sprint review meeting）』回饋到『輸入的需求端』，另一條透過『retrospective meeting，回顧或是反省會議』回饋到『開發流程』。

### Five scrum activities(events/ceremonies)
- Product backlog refinement(產品工作清單)
- Sprint planning meetings(衝刺規劃會議)
- Daily scrum（每日站立會議)
- Sprint reviews(衝刺展示會議)
- Sprint retrospective(衝刺回顧檢討會議)


### Done
- When a Product Backlog item(產品待辦事項日誌) or an Increment is described as “Done”

### 4 Manifesto for Agile Software Development
1. Individuals and interactions over processes and tools
2. Working software over comprehensive documentation
3. Customer collaboration over contract negotiation
4. Responding to change over following a plan

### TheThree Pillars of scrum
1. Transparency
 This means presenting the facts as is. All people involved—the customer, the CEO, individual contributors—are transparent in their day-to-day dealings with others. They all trust each other, and they have the courage to keep each other abreast of good news as well as bad news. Everyone strives and collectively collaborates for the common organizational objective, and no one has any hidden agenda.
 透明度：這意味著按現狀呈現事實。所有涉及的人員 - 客戶，首席執行官和個人貢獻者 - 在與其他人的日常交易中透明。他們都相互信任，他們有勇氣相互傳達好消息和壞消息。每個人都為共同的組織目標而努力和共同合作，沒有人有任何隱藏的議程。

2. Inspection
Inspection in this context is not an inspection by an inspector or an auditor but an inspection by every- one on the Scrum Team. The inspection can be done for the product, processes, people aspects, practices, and continuous improvements. For example, the team openly and transparently shows the product at the end of each Sprint to the customer in order to gather valuable feedback. If the customer changes the requirements during inspection, the team does not complain but rather adapts by using this as an opportunity to collaborate with the customer to clarify the requirements and test out the new hypothesis.
檢查：在這種情況下的檢查不是由檢查員或審計員進行檢查，而是由Scrum團隊中的每個人進行檢查。可以對產品，流程，人員方面，實踐和持續改進進行檢查。例如，團隊在每次Sprint結束時公開並透明地向客戶展示產品，以收集有價值的反饋。如果客戶在檢查過程中改變了要求，團隊不會抱怨，而是通過使用這個機會與客戶合作來澄清要求並測試新的假設。
3. Adaptation
Adaptation in this context is about continuous improvement, the ability to adapt based on the results of the inspection. Everyone in the organization must ask this question regularly: Are we better off than yesterday? For profit-based organizations, the value is represented in terms of profit. The adaptation should eventually relay back to one of the reasons for adapting Agile—for example, faster time to market, increased return on investment through value- based delivery, reduced total cost of ownership through enhanced software quality, and improved customer and employee satisfaction.
適應性：在這方面的適應是關於持續改進，根據檢查結果進行適應的能力。組織中的每個人都必須定期提出這個問題：我們比昨天更好嗎？對於基於利潤的組織，價值以利潤來表示。最終的調整應該回到適應敏捷的原因之一 - 例如，加快上市時間，通過基於價值的交付提高投資回報，通過提高軟件質量降低總體擁有成本，並提高客戶和員工的滿意度。

### Agile Leadership practices(敏捷領導作法)
1. Honesty(誠實)
2. Forward looking(往前看)
3. Competent(能力)
4. Inspiring(激勵)


## Domain 2：Value-Driven Delivery(價值導向)
### Mary and Tom Poppendieck : The Seven Wastes of Software Development:

1. Partially Done Work(部份完成工作)
2. Extra Features(額外功能)
3. Relearning(重新學習)
4. Handoffs(交換)
5. Delays(延遲)
6. Task Switching(任務切換)
7. Defects(缺陷)

#### Udemy_PMI-ACP Agile Certified Exam Prep-Workbook

1. Partially Done Work(部份完成工作)
2. Extra Features(額外功能)
3. Extra Process(額外流程
4. Motion(運動)
5. Waiting(等待)
6. Task Switching(任務切換)
7. Defects(缺陷)


The Seven Wastes of Software Development - DZone Agile http://bit.ly/2GXPAvZ

## Domain 3：Adaptive Planning(適應性與漸進式規劃)
### Seven lean core concepts
1. Eliminate waste(消除浪費)
2. Empower the team(賦予團隊權力)
3. Deliever fast(快速交付)
4. Optimate the whole(優化整體)
5. Build qualty in(建立質量)
6. Defer decisions(推遲做出決定)
7. Amplify learning(放大學習)

### 開發新產品，4種收入類別

1. New revenue:
2. Incremental revenue:
3. retained reveune:
4. Operational Efficiencies:

###  The Kano model classifies customer requirements into five categories:
狩野模式(KANO Model)受行為科學家赫茲伯格的雙因素理論的啟發，東京理工大學教授狩野紀昭(Noriaki Kano)和他的同事Fumio Takahashi於1979年10月發表了《質量的保健因素和激勵因素》(Motivator and Hygiene Factor in Quality)一文，第一次將滿意與不滿意標準引人質量管理領域

1. Basic/threshold attributes
2. Performance/linear/one-dimensional attributes
3. Excite/delight attributes
3. Indifferent attributes
5. Reverse attributes
Excite and Delight Your Customers by Using the Kano Model | AgileConnection http://bit.ly/2uwXgTg


### Last Responsible Moment (LRM)
- A strategy of not making a premature decision but instead delaying commitment and keeping important and irreversible decisions open until the cost of not making a decision becomes greater than the cost of making a decision.
- 這是一種不作出過早決定的策略，而是延遲承諾並保持重要且不可逆轉的決策，直至不作出決定的成本高於做出決策的成本。



## Domain 4：Stakeholder Engagement(利害關係人分析與參與)

## Domain 5：Team Performance(團隊績效)

## Domain 6：Problem Detection and Resolution(問題偵測與解決)
### The Goldratt theory of constraints(限制理論)
1. Identify the system's constraint(s).(定義系統限制)
2. Decide how to exploit the system's constraint(s).(決定如何去應用系統限制)
3. Subordinate everything else to the above decision(s).(將所有事歸屬至以上決定)
4. Elevate the system's constraint(s).(提升系統限制)
5. Warning! If in the previous steps a constraint has been broken, go back to step 1, 
but do not allow inertia to cause a system's constraint.
(警告！ 如果在前面的步驟中約束已被破壞，請返回步驟1，
但不要讓慣性造成系統的限制)

## Domain 7：Continuous Improvement (Product, Process, People) (持續改善)
