# Problem Statement
**The Problem** is a lack of inventory management from field, to crate, to storage, to market thus increasing waste of produce and lack of produce being sent to market.

**It affects** the company itself due to mismanagement of inventory, the managers, as it is more difficult to keep track of what is and is not needed, the employees, who may feel their work is inadequate due to waste, and the customers, who are not receiving the appropriate produce at markets.

**The impact** is loss of sales, dissatisfied customers, and limiting growth and expansion.

**A successful solution** would be to set up a database containing information about what space is available, what and when crops are being sown, estimated yield, estimated produce to be sent to markets, actual produce sent to markets, return produce from markets and finally, waste.

---
---
<br />

# Thriving Food Farm as a System
**What is its purpose: i.e. what is it trying to achieve?**  <br />
Providing good-quality, organic produce to the homes of local families while maintaining the health of the soil in a sustainable and regenerative way.

**What does it produce?** <br />
Organic, chemical-free, seasonal vegetables

**What is its deemed boundary?** <br />
Farmland Expansion, Farm Inventory Management, Produce Storage, Distribution Network, Staff and Working Capital.

**What does it consist of physically and conceptually?**<br />
- *Physically*: Farmland, Vehicles and Machinery, Warehouse and Coolrooms, Distribution Vehicles, Working Capital
- *Conceptually*: Intellectual Property, Customer Relationships, Perceived value, Perceived quality, Organisational Structure, Brand Reputation.

**What does it process?** <br />
Orders, sales, payments, complaints, produce

**What does it receive and produce for other systems or its users/customers?** <br />
Produce, orders, sales, payments, complaints.

**What does it keep or store?** <br />
Produce, raw materials, customer data.

---
---
<br />

# Vision/Elevator Pitch
## For Produce and Inventory (Phase 1)
**For** Thriving Food Farm executive management <br />
**Who** would like to keep records of produce planted, harvested, sold and discarded <br />
**The Farm Inventory Management** system will keep a record of produce from field to market to waste  <br />
**Unlike** our current manual records and estimations  <br />
**It will be different** by having a digital database to reduce estimations of what produce is available or required`
## For Customer Sales (Phase 2)
**For** Thriving Food customers <br />
**Who** would like to have a greater likelihood of receiving seasonal produce <br />
**The Farm Inventory Management** system will better estimate what produce is available or required<br />
**Unlike** our current manual records and estimations  <br />
**It will be different** by having a digital database to better estimate what produce is purchasable

---
---
<br />

# Scope - In/Out List
| Topic | In  | Out |
| ----- | --- | --- |
| Purchase history | :heavy_check_mark: |
| Harvest Calendar | | :x:
| Produce harvested | :heavy_check_mark: |
| Produce stored | :heavy_check_mark: |
| Produce allocated | :heavy_check_mark: |
| Record sales | :heavy_check_mark: |
| Record deliveries | :heavy_check_mark: |
| Record waste | :heavy_check_mark: |
| Customer notifications of upcoming produce | | :x:
| Alerts on low produce | | :x:
| Automated Reorder Stock based on data | | :x:
| Mobile Accessibility | | :x:
| Produce Perishable Tracker for produce in storage  | | :x:
| Coolroom & Vehicle capacity indicator | | :x:

---
---
<br />

# Business Rules
- The total purchase of all seedlings must not exceed the total planting space available.
- The total harvest should not exceed the available storage.
- The total harvested should be accounted for during allocation.
- The produce allocation should equal produce sent to market, plus delivery orders, plus produce stored.
- The total harvested should equal the total sales, plus produce stored plus total waste combined.
- Each crop will be self-contained with its data to track its lifecycle

---
---
<br />

# RAIDS - Risk, Assumptions, Issues, Dependencies, System Constraints
| Category | Description | Impacts | Owner | Priority |
| -------- | ----------- | ------- | ----- | -------- |
| **R**isk | Produce is mismanaged and not accounted for | Entire system's reliability | |High | | 
| **A**ssumption | Database is regularly updated when produce is moved from harvested, to allocated, to stored, to market, to waste etc. | Future purchase orders | | High
| **A**ssumption | Weather and produce loss margin are accounted for when orders are being made | Future purchase orders | | Low
| **A**ssumption | Remote device to update allocation of produce as allocations are taking place | Accuracy of produce sent to market and sales | | Medium
| **I**ssues | Newly implemented system will not be as reliable in initial stages but will improve as time continues due to more data from sales | Initial system's reliability | | Medium
| **I**ssues | Unsold produce consolidated prior to updating system | Accuracy of produce sold and estimations for future markets | | Medium
| **D**ependency | Each stage of the crop cycle is dependent on the previous, from purchasing seedlings to planting to managing growth, to harvesting, to storing, to allocating, to sales, to excess waste | Entire system's reliability | | High

---
---
<br />

# Personas
## Name and Descriptor: *Farmer Frank, the small farm owner*
| *WHO* | *HOW* | *WHAT* | *WHY* |
| ----- | ----- | ------ | ----- |
| Farmer Frank grew up in the city. His father was a businessman and encouraged Frank to follow in his corporate ways. After growing tired of the corporate world, Frank started his own business. He found an escape from office life by starting a small vegetable garden in his backyard. Soon this turned into his true passion and abandoned his small business to start a new one: an organic vegetable farm. Operating solely from his backyard, he fed his family, friends and neighbours until he had enough courage to buy a plot of land and start making a name for himself. | The life of a farmer is a busy one. Frank is always working on the next project to grow his farm. His skills like his hard work ethic and, knowledge of cultivation and agriculture. However, worrying about the crops and staying on top of orders does not give Frank the time to keep a record of how many seeds need to be sown, how many crops need to be harvested and what markets would be best suited for his produce. Being able to systemically track which crops he needs more of and which he needs less of would greatly streamline his farming venture. | Franks needs somewhere to track what he is planting, what needs to be planted, when it needs to be planted, how much needs harvesting, how much produce he yields, what is being sold and what is getting wasted. | Frank is very much about efficiency. As he is always busy maintaining the farm and running a business, he wants a system to track his input/output so that he can optimise his time spent farming, rather than sitting at a desk searching for past orders and sales receipts. He is also mindful of his sustainability keen on waste prevention, so knowing how much is needed will reduce waste and costs.

## Name and Descriptor: *Healthy Helen, the eco-friendly mother*
| *WHO* | *HOW* | *WHAT* | *WHY* |
| ----- | ----- | ------ | ----- |
| Helen grew up in the countryside surrounded by nature. She studied environmental law at university and after her studies travelled across the world meeting many different people, from many different backgrounds. She saw the damage that exporting non-native food crops to other parts of the world was doing to the ecosystem and the livelihoods of the local farmers. She vowed to shop locally and support locally grown produce. She has since settled in a beautiful suburb where she raises her four wonderful children. She is very conscious of the chemicals that go into the mass growing of produce and does her weekly food shop at farmers' markets. These foods also help her children maintain a busy active lifestyle between school and after-school sports. | Helen likes to meal plan as her busy lifestyle with work, her children and her hobbies, means she does not have the time to walk around a grocery store wondering what to eat that evening. She found a local farmer who consistently sells his produce at the farmers' market she attends. The farmer always has plenty of fresh produce that she likes to enjoy and also some seasonal produce that she tries to change up her meal plans. | Helen keeps track of the upcoming specials through the farmer's newsletters, where she finds out what will be in stock for the upcoming markets. This allows her to plan her meals and avoids her having to stop at the grocery store for the items that she missed at the market. | Helen likes to ensure she knows what food she is feeding her children. The farmer's market is certified and trustworthy. She knows that her family are eating fresh, locally grown produce. Her children also love coming to the market with her to help pick out the vegetables and meet the farmer who is behind it all face-to-face.

---
---
<br />

# Requirements
## Business Requirements
- BR001 : Reduce overstock by 10%.
- BR002 : Sales increase by 10%.
- BR003 : Inventory Manager upkeep costs no more than 5 % of total revenue.

## Functional Requirements (Management)
- FR001 : Management are able to update ordered and sold produce.
- FR002 : Management are able to add the amount and date for the crop planted.
- FR003 : Management are required to update each crop individually.
- FR004 : Management are able to track the statistics of each crop based on previous data.
- FR005 : Management are required to update the allocation of produce post-harvest.
- FR006 : The system should provide accurate and real-time tracking across the supply chain.
- FR007 : Management should be able to know the location of produce after allocation and easily move

## Non-Functional Requirements
- NFR001 : The system should be easy to use and update
- NFR002 : System should be scalable
- NFR003 : The system should be fast to respond to requests and updates

---
---
<br />

# Sample User Stories
| As  | I need | So that |
| --- | ------ | ------- |
| Farm Manager | to be able to track previous orders | I know whether or not to update current order |
| Farm Manager | to be able to see how produce is in-demand | I can plan future orders appropriately |
| Farm Manager | to be able to track what is harvested vs sold | I can reduce waste |
| Harvest Manager | to know how many of each crop should be harvested | I can accurately prepare and plan the harvest |
| Stock Manager | to know how much space is available in storage | I can inform Harvest Manager how many of each crop should be harvested |
| Stock Manager | to know how much space is available in vehicles | I can allocate enough produce to each market |
| Stock Manager | to know how many produce returns from markets | I can track what is kept in storage |
| Stock Manager | to know how many produce returns from markets | I can adjust the amount of produce sent to markets |
| Sales Manager | to know how much produce I have at markets | I can adjust any deals or offers |
| Sales Manager | to know old sales records | I can recalculate the value of produce |

---
---
<br />

# Sample Product Context Diagram
![Context Diagram of High-Level view of Farm Inventory Manager System.](/diagrams/FIM_Context_Diagram.png)

---
---
<br />

# Use Case Diagram
![High-Level Use Case Diagram of Farm Inventory Manager System.](/diagrams/FIM_Use_case_diagram.png)
