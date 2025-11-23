]Awning Works Inc (AWI)
https://www.awningworksinc.com/

Awning Works Inc (AWI) is a custom shade construction/manufacturing company that also has several sister companies under eCentral Stores (ECS) which deals with the fabric/home décor side of outdoor living.  D365 is used primarily for AWI customers but there are some sister company customers added for tracking. There will be a fundamental change under Rebranding 2026.

We are rebranding and will be putting all residential under Patio Lane Outdoor Living (brand of ECS), Hospitality Commercial soft goods under Patio Lane Contract, commercial custom manufacture under AWI with the option to have HYBRID projects that start off under one but use the other brand as a SUB-CONTRACTOR BRAND with the funding to go through the INITIAL BRAND.

We are also expanding our Satellite office in Orlando with potential for other Satellite offices.

We originally began using Dynamics 365 Sales in 2017 to track AWI ONLY customers with QuickBooks as our ERP and Quote creation tool. D365 was originally set up as a RapidStart in 2016 but it wasn’t until June 2017 that Christine came in and began customizing. We now have several new custom fields and layouts (especially reflecting the growing diversity of the business). In 2020, we switched (as directed) to the Unified Interface – unfortunately some of the old system settings were melded into it. 

It may be better to create a new, cleaner app to remove any conflicts and to improve functionality – hopefully increasing user use and positive experience. There is one Workflow on Appts that definitely need help to delete.

Challenges have been primarily on automation, integration of software, and accurate, easy-to-see sales reporting. Plus having different sales tracks with pipelines for new branding project types and needs.

We have looked into many options for modifications or software alternatives but have only gotten through the conversation portion with a variety of Software professionals.

There must be a balance for skills provided, cost outlaid, vision for future goals, and awareness of current needs with minimal interruptions to our increasingly busy workday.





 


SOFTWARE USED DAILY FOR PROJECTS: 

 

•	Dynamics 365 (18+ licenses) + File Data (4) + App Data (1
o	FULL LICENSE Module app – rarely used
o	TEAM LICENSE Module app – DEFAULT
o	D365 for Outlook Module app – infrequently used
o	MOBILE Module app – infrequently used
•	Microsoft 365 (Outlook/Calendar/Word/Excel/SharePoint/Teams primarily)
o	Multiple Servers for Explorer
o	Excel for Estimating
o	Server-based File Management for projects
•	3CX VoiP ---- phones system integrated but challenge
•	QuickBooks (non-integrated) for Quote generation and invoicing/PO -- AWI & ECS
•	GoHighLevel (CRM Lead generation) -- AWI & ECS (PLOL)
•	Magento for quote generation and invoicing ---ECS
•	Shopify – ECS
•	Klaviyo (email) - ECS
•	Gorgias (chat/tickets) - ECS
•	External Lead sources – like HomeForce – ECS & AWI
•	SmartSheets – Project tracking ---AWI+some ECS
•	Mondays – Project tracking ---ECS
•	Nitro and PDFxchange for Quotes and Job Work Orders
•	SignNow  (a Docusign  type program) - AWI
•	https://calendly.com/



 
EXPLANATION OF OPPORTUNITIES
Use Qualified Leads for New Customer to generate Contact and Opportunity (possibly Account).
Add Opportunity to an existing customer on Accounts = Commercial, Contacts = Residential.

Creation of opportunities is based on expectations. 
If customer has several needs or may break into multiple purchases, then MULTIPLE OPPS are created for them to pick and choose as many as they like.

If the customer only has one need/project or single purchase but wants multiple choices, we create multiple estimates but only ONE OPP [updating the PRIMARY estimate fields & putting alternate estimates in Notes or tasks – FUTURE plan to create estimates inside D365 – challenge on current method if using note is not having a list of non-primary field estimates.

Also, construction may have multiple General Contractors bidding on the SAME PROJECT. We call those Multi-bids. So we create ONE OPP for the ONE PROJECT, usually putting the FIRST requestor as the Account/contact and the additional requestors as CONNECTIONS and a note with a list of all GCs and info provided.

Use Connections on all Entities/tables to show complexity of relationships [not just stakeholder]

CURRENT REVENUE FIELD TYPES
Budget Range = dropdown range per customer
Proj. Est. Value = Guestimate by sales rep for expected ballpark cost for project
Est. Revenue = FINAL TOTAL on the estimate (with tax)  [default most views-need to change to SO]
SO Rev [subtotal $] = subtotal without tax [QBO subtotal so it may have county tax] base for commission
Commission = pre-calculated out on estimate worksheet
Actual revenue = CLOSED AS revenue

CURRENT FIELD TYPES TO DIFFERENTIATE SALES TRACKS
FOR AWI/ECS? = single choice for either AWI, PL, PLOL, PLOL-RP, PLOL-SP, PLOL-other vendor, PLC, Hybrid (AWI + vendor), Hybrid (AWI +PLOL)
Vendor List = multi-choice for Different Manufacturers of the products sold (some are partner vendors)

Lead Source = single choice dropdown
Source Detail = text field to clarify Lead Source with specific brief detail

EST TYPE? = single selection dropdown to indicate where estimate was generated, for what purpose, etc

ECS/PL Status = single dropdown menu to indicate if Account & contacts were confirmed for either AWI &/or ECS 
ECS Status Date = date last confirmed 
Comments (A) = text field for above on the Account Details tab

 


COMPANY CURRENT WORKFLOW
Our customer leads/projects are generated from new or existing customers via walk-in, phone, email, website inquiries, BID SITE platforms used by contractors, cold calls, referrals from vendors, and leads generated through a paid service. 

LEAD (for new customers) - QUALIFIED IMMEDIATELY if able.

PIPELINE - STAGE 1  >>>> [support advances through stages – AUTOMATION WOULD BE NICE]
1.	Request comes in – usually to Sales Support first (unless directly to Sales Rep who forward to Support for data entry)
a.	FUTURE: Homeforce  GoHighLevel will send new leads to direct add into CONTACTS
i.	Assigned to specific Rep
ii.	He will confirm valid – if it it is
iii.	Request Support to add opportunity [WISH BUTTON to AUTO ADD]

2.	Search to see if they are existing customer – [may search QuickBooks also]
a.	EXISTING if they are – create opportunity on ACCOUNT for commercial or on CONTACT for residential customer. Assign to rep 
(is there a way for opportunities to default ownership of opportunity to the owner of the account or contact – with option to change – instead of creator?)

b.	NEW CUSTOMER --- create a Lead and qualify immediately

PIPELINE – STAGE 2  >>>> Define Scope
3.	Sales Rep gets new opp assignment  [via email with URL link]
a.	Sales Rep contact customer	
b.	Confirm info [ask support to update any new info]
c.	Create folder in file management 
d.	Add file path to Opp
e.	Set appointment &/or confirm scope
f.	Add comments

PIPELINE – STAGE 3  >>> Estimating (Rep)
4.	REGULAR ESTIMATES - Sales Rep goes through the estimating process [using word, excel]
a.	Rep puts guestimate value in Proj est revenue
b.	Using filters based on custom dropdown & calendar fields to work through dashboard views for Assignments to different department action
c.	Estimators update fields
d.	Price approval dept updates fields
e.	Sales Rep finalizes EST

5.	FIELD ESTIMATES – Sales Rep DURING APPT – creates estimate
a.	Gets quote from vendor
b.	Finalizes estimate
c.	Shows to customer – gets signature if sold [SignNow]

PIPELINE – STAGE 4 >>> sent to EST Creation
same email group   [FUTURE – want to CREATE IN D365]
6.	REGULAR: Sales Rep sends email File Path to Finance so they can create entry into QBO

7.	FIELD: sends email with quote (with or without signature) to support to ENTER into D365

PIPELINE – STAGE 5 >>> Has Estimate (need Follow-up // awaiting customer decision)
use Email/QuickBooks & reports & File Explorer by Support
8.	REGULAR: Using either email &/or QuickBooks entries, support finds correct opportunity in D365 and adds Estimate info 
9.	FIELD: uses Email to update Opportunity with Estimate information
10.	Rejected – Close as Lost

PIPELINE – STAGE 6 >>> PendingWON / WON
per Finance – QBO --- do not close out as won until confirmed AWARDED
11.	Support updates based on Finance status – using report emails or Teams Chat directives
a.	Enter into SmartSheets [would be nice if we could push]
BASIC Data to PDF Worksheet and to SmartSheets
b.	Create a Digital Folder Work Order PDF [would be nice if we could push]
c.	Change File Path/Updated name/location
12.	Support close as Won




DYNAMICS CHALLENGES
•	Conflicts with old version and UI version (some of the workflows) (KD of RG)
•	Tasks not staying completed (KD of RG)

•	Old workflow button trigger obsolete (SAME AS in Lead Acct address & Project address)
o	Appointments pulling old formatting and cannot remove
•	Not accounting for ALL estimates (because multiple estimates are on notes)
•	Management level reporting
•	Compiling information from multiple platforms
•	Repetitive entry [need duplication option]
•	Sales level reporting
•	Consistency/accuracy with data entry & proper use
•	Notifications for action
•	Data memory
•	Automation
•	Not set up for Quoting
•	Majority of users are view only or updating a few fields only
•	Excessive Opportunity views because users not comfortable filtering as needed, hard to update all 
•	Blocked Email out because of concerns of unintended use (failure to remove customer)
•	Marketing
o	Showing Applications/products of interest on Account, Contact for marketing purposes. Primarily only shown on opportunity which limits how pull marketing lists to a Single specific product or application.
•	Queues – we have never used
•	Goal set-up (is this being discontinued)
•	Creating new Processes for Field, Level A, service (different pipeline steps & requirements) 
•	Too much info on one tab / navigation / need to be user friendly
•	Ability to track project info once Opp is closed [within d365]
•	Need form for Customer Direct Entry on a tablet to a Lead (to be qualified by staff)
•	Contacts added under Account Primary Contact not later updated with Account on the Contact
•	Multiple fields needed to reflect all the variations options/pathways for company which may seem like duplication but it provides complexity representation
•	Account Rating not being updated to show the highest level in sales process the customer has reached [need trigger if doesn’t show PAYING or CORE customer and has WON OPPS]
•	WHY DOES THE DASHBOARD NOT SAVE CONSISTENTLY IN POWER APPS SINCE 2025 – 
only way to tell that it has saved is to change the name of the dashboard each time to make sure saved before exiting. 
CRM WISHLIST  
SALES / REPORTING / ANALYTICS
•	PowerBI dashboard set up to pull info from different data sources // Power Bi [for collaborative info from other platforms and data analysis sharable to reps]
•	Custom dashboards – put the ones we want below
A.	Sales goal for month quarter etc. they will be in the red until they meet their goal then the dashboard will turn green. Will give the dollar amount
B.	Commission calculation – be able to go by date – They fluctuated from 6% to 10%
C.	Closing ratio per salesperson and team
D.	Lead generation sales metrics
E.	Top opportunities
F.	Sales leadership
G.	Year over year performance and quarter over quarter
H.	Daily leaderboard
I.	Marketing ROI
J.	Average acquisition cost for leads
K.	Lead conversation rate for purchased leads
L.	Live monitoring dashboards
M.	Opportunities won and lost per customer


SALES REPORTS
•	Closing Rate
•	Closing Rate Last Yr
•	Estimates Value Inc/Dec Over Last Yr
•	Estimate Qty Inc/Dec Over Last Year
•	Grade to Sales Goal 2022
•	Sales Rev Inc/Dec Over Last Year
•	Compensation Inc/Dec Over Last Year
•	Add commission and bonus reporting dashboard
•	Product Sold and Location

•	Report on money owed vs Commission since we do a commission draw system 

•	YTD Conversion Data - Walk-in Converts to a Sale and total Dollar amount by Month. Along same line- Creating above for all Opp sources on a monthly trend chart

•	Update Active Account View to show Rep Follow-up & Type Follow-up field

•	VIEW - Accounts not been contacted within 6 months per newly created field in Accounts and Contacts [have created ACTION DATE, TYPE ACTION dropdown]

•	Sales Order Revenue Data - Awarded (AWI & ECS)

•	Create KPI's - need to figure out targets on timing & quantities - Creation date, within # assigned to Owner or closed as Lost, 
What would you need to create a dashboard with the below KPIs?
•	Ad Spend ($6k Renaissance program)
•	Total Leads Provided
•	Avg. Cost Per Lead if above or below 60
•	Qualified Leads
•	Weekly/Monthly Sales bookings/estimates
•	Won Leads/Lost Leads
•	Conversion Rate
•	Revenue
•	Avg. Deal Size
•	Hot/Very Hot Leads weekly/monthly 

•	Set-up Sales Goals (or new method if obsolete)
•	GOAL for AWI Revenue (based on SO total ????) by Month? Quarter? Year?
•	Goal for individual rep revenue by Month? Quarter? Year?
•	Goal for total estimates created per Month? Quarter? Year?
•	Count of Estimates created vs Estimates sold for CLOSING RATE
•	Compare previous Years
•	Percentage beyond or below goals set
•	Bonus tracking per salesperson 
•	Commission tracking

•	Sales Performance Basics
•	Know your Estimate Street Value- you can only hit sales goals if you hit total estimate values based upon your closing rate
•	How do I get opportunities that fit my sales goal expectation- Effectively evaluate customer, budget and scope and make good decisions for yourself and company that produces a Sale.
•	Proactively seek your sweet spot projects/products/clients – GC plan rooms, phone calls, online plan rooms
•	PL opps from AWI Opps that we receive.

•	Thinking CRM of course, dashboard report and vetting AWI Opps at onset, or post with Rep (and could also be after AWI awarded) with some new vetting inquiries that Janice can define as well as products and budgets.


AUTOMATION / CONVENIENCE
•	STRIP ATTACHMENTS FROM ALL TRACKED EMAILS – other data saving 

•	HINTS/REMINDERS based on certain fields

•	Lead Address Triggers – copy address from company to Project address OR from Project to company address (manual) - had before UI change

•	Opportunity Duplicate Trigger (manual) – what about MERGE opps option?

•	Add button to automatically create an opportunity from Account (commercial) or Contact (residential) with option to pull project address from selection 
o	Is there a way to set up a Trigger to Add opp with certain fields responses and connections auto added or maybe just add connection and couple of fields - specific to which chosen

•	Other buttons to trigger automation or pull of info to make it easier for our salespeople  

•	Workflows based on responses [throughout]

•	Fix phone numbers so that they integrate with VoiP system but DISPLAY in a user-friendly format. VoiP uses no dividers. User friendly is with dashes.

•	Suggestions for Counties based on City &/or Zip Code

•	Integration with WEB INQUIRIES to Lead and then Support validates before Qualifiying

•	Automatically update ACCT/Contact? Rep Follow-up & Type Follow-up (like sales pipeline is) field based on Opp creation, Estimate entry, SO entry, Last Follow-up or manually (maybe a trigger [last activity type trigger – updates date and workflow selects type based on trigger]
•	add customers business card image/info to contact information [added capture but…]

•	Action Cards - note main details (Due date countdown, Todays, Follow-up dates, etc)

•	Auto emails for 5-star reviews with follow up from salesperson to customer – this is more POST-SALE action after project is completed per SmartSheets & paid per Finance. Might have to be a button?
•	Notify Customer of Sales Rep Appt // Texting customers with name of salesperson and time/date of arrival // Emailing customers same information as text // Auto texts/email to customers [with option to block, as needed]
•	Auto generated reminder(email-text) to follow up with an opp with estimate every 30/60/120 days. Each representative will likely want to specify their required follow up reminder. 

o	Text/email for salesperson follow up reminder // Reminders for follow-up via Text (auto-Trigger date Next or Last) - autocreate task? or post? IF THEN

o	Reminder via email/text to Keep Open/Close - set stage of project by (auto-trigger based on creation, due date, email EST, ????) 

o	Auto generated reminder email-text that a bid due date is approaching. Accurate input of due date will be needed. We would have to formulate this as some bids require longer time for RFQ ( we would need to establish some norms/standards with our sales team).

o	AUTO REMINDER - Use Task and text for RFQ? should we have an activity for RFQ specifically? Should we have an Activity specifically for post-Sale dates? Started creating an SDR activity but never implemented
•	House Value Field or click action for new residential Contacts Address (manual) // Bring up house on app and online with value and median income for that area  ---- We have BING MAPS already – want to add maps integration with home values [pulling from other website]
o	Map of lead (location?) that will show them the median income of the neighborhood and pictures of the house

•	SEE INTEGRATION for EST Creation push from D365 to Finance for QBO entry request.


FUNCTION / PROCESS
•	IMPROVE USER EXPERIENCE BUT STILL REFLECT THE COMPLEXITY OF THE COMPANY’S NEEDS 

•	Maintain enough Data Storage 
•	What type of licenses do we need?
•	Marketing: E-Campaigns – Mail Chimp etc. – by product type – dollar amount – residential – commercial
•	Set up Territories or another business unit for ECS vs AWI (make sure hierarchy is accurate for reps) [best practice]

•	Possible switch from Server to SharePoint for job folders? [best practice] 

•	Create Knowledge Articles for Sales Reps to use - clean up storage method for D365

•	Clear up focus of revenue for reporting - Base on Estimated revenue (TOTAL with taxes), SO Revenue (without tax except county$ like QBO but if use from crm instead of QBO then maybe a not issue), Actual Revenue (pulled from Estimate revenue)

•	Redesign Mobile App for Sales Rep use

•	Schedule sales call thru D365 and auto populate on outlook calendar as well – without conflict

•	replace existing Lead Import template with chosen fields and order [done mostly – need to improve mapping]

•	INFORMATION ON OTHER D365 APPS – Business Central, Customer Engagement, etc
INTEGRATION: QuickBooks, SmartSheet, Magento, etc
•	Minimal Project Management post-sale date tracking information - maybe using Activities since it is accessible even after closure? and can use with reports

•	Sales Orders / Purchases Business Central?????

•	Get history of QB/QBO Estimates (especially SO) imported into Sales Hub - currently only $, date, JID in Primary or task/notes FOR REPORTS

•	Quoting EST created in Sales Hub - Customer Set-up (lines pushed to Template in our Format, download PDF to proj folder & emailed with attachments to customer)  - Push to PDF

•	Update Permissions for individual Reps (privacy field on certain fields

•	Explain how to use Queues - found on User form [best practice]
•	Smartsheet integration – PM integration – Job Costing
•	Custom Estimate templates – We want all estimates to be made in the CRM software
o	How would it show as a list of estimate PDFs instead of a list of details
•	Send created Estimate to Finance to add to QBO when customer approves OR if only created in QBO then ready to create (move the opportunity to finance they get alerted its ready to type up and send to the customer) - we already have a sent to EST Creation date field
•	QB online integration 2 ways
•	Integration invoice and payment management thru QB.
•	Calculating tax per county on the estimates
•	Integration with SignNow
•	Integration with Calendly or MS Bookings

