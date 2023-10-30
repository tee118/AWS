## BOOKSTORE DATABASE LAB


## What sort of information will you need to get from the project stakeholders before you can begin modeling the database?

- Inventory Information: product ID, name, description, quantity, cost, price, etc.
- Sales Reports & Sales Data: Date, product ID, quantity sold, revenue, etc.
- Schedules for Author and Performer Appearances: date, start/end times, author/performer name, book/act details, etc.
- Event details
- User Roles and Access Rights
- Data Volume and Performance Requirements
- Data Security and Compliance
- Integration Needs
- Future Scalability and Growth


# To interact effectively with your customers and project stakeholders during the database design process:
---
Hold Regular Meetings: 
Prototyping
Documentation
Feedback Loop
User Acceptance Testing (UAT)
Training

## Gathering Resources - Exercise 2
 
## For the inventory spreadsheet:
- What are the specific columns/fields? Product ID, name, quantity, cost, price, etc.?
- How often is it updated? Is inventory continually tracked or periodic snapshots?
## For the monthly sales report:
- What are the exact data fields included? Sale ID, date, product, quantity, revenue?
- How is the data for this generated? Querying the inventory spreadsheet or some other source?
## For customer receipts:
- Do receipts capture customer info like name or contact details?
- Is sales data from receipts integrated with inventory and reporting or separate?
## What is the workflow for:
- Adding new inventory? Is the form the source or just for reference?
- Updating inventory when items are sold?
- Generating sales reports?
- How are author/performer events and schedules currently tracked? Details needed on this process.
- Approximately how many products, transactions, events are there on a weekly/monthly basis?
- How long does inventory, sales, and schedule data need to be retained?
- Who on the staff needs to access which parts of the data? Any role-based permissions?
- What are the pain points or limitations with the current tracking methods?
- Do they have a budget or desired timeline for the new system?
- Any preferences on platforms, databases, or languages for the new system?

## What additional questions might you have based on the inventory spreadsheet?
- What is the unique identifier for each product (SKU, product ID, etc)? I don't see a clear unique field.
- For book titles, is ISBN captured? This would be helpful to accurately identify and look up book metadata.
- How is quantity tracked as books are sold? Is this spreadsheet updated regularly?
- Are there any additional attributes that would be useful to capture like publish date, genre, vendor?
- I see a supplier column - do you need to track multiple suppliers per title?
- Is location/shelf important to track for inventory purposes?

## What additional questions might you have based on the customer receipt?
we would ask about the customer receipt:
- Is there a unique identifier for each transaction, like a sales ID or invoice number? I don't see one on the receipt.
- Is customer information like name, email address, or phone number captured on the receipt or in your system?
- Do you need to track payment information like payment method, card details, or check number?
- How are items on the receipt linked back to inventory? Is an internal product ID or SKU used?
- Are sales tax and total amount paid needed in the system for reporting?

## What additional questions might you have based on the monthly sales report? we would ask about the monthly sales report:
- What is the exact source of data used to generate this report? Inventory spreadsheet, POS system reports, other sources?
- How much manual effort is required to aggregate the sales data and produce this report?
- What date range does the monthly period cover? Calendar month, last 30 days?
- How are total sales and average sales per day calculated?
- Are any sales excluded from the report, like refunded items?

## [Desk calendar] 
## What additional questions might you ask based on the calendar or the schedule of book signings, appearances by musicians, and other events?
- we would ask about scheduling author/musician events based on reviewing the calendar:
- Do you need to track details like the type of event (book signing, concert, reading etc.), duration, location details?
- Will there be multiple authors/musicians booked for some events?
- How far in advance are events booked? Do you need to track tentative vs confirmed events?
- Is there a way to link inventory to events to get stock reminders? ISBN or product IDs?
- Will sales/revenue from events be tracked?
- Do you want to track attendee capacity and reservations/RSVPs?
- Are there any costs associated with events that need tracking? Fees, travel reimbursement etc.