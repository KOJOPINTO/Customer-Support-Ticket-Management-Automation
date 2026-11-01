# Business Rules – Customer Support Ticket Management Automation

## 1. Ticket Creation
- Every new customer support request creates a ticket.
- Each ticket receives a unique Ticket ID using the format `TKT-` followed by the spreadsheet row number.
- New tickets are assigned the status **Open**.

## 2. Department and Technician Assignment

Tickets are automatically routed based on the selected issue category.

| Issue Category | Assigned Department | Assigned Staff |
|---|---|---|
| Technical Support | IT Support Team | Technician 1 |
| Billing & Payments | Finance Team | Technician 2 |
| Account Access | Account Management Team | Technician 3 |
| Product or Service | Customer Service Team | Technician 4 |
| Other | General Support Team | Technician 5 |

## 3. Email Notifications
- Customers receive an email confirming that their ticket was received.
- The business receives a notification containing the ticket details and assignment.
- Notifications include the Ticket ID, issue category, priority, and issue description.

## 4. Ticket Management
- Support staff can update the assigned technician and ticket status.
- Available ticket statuses are Open, In Progress, and Resolved.
- Resolution notes are entered by support staff.
- The date resolved is recorded when the ticket is completed.

## 5. Resolution Notifications
- A customer receives a resolution email when the ticket status is Resolved and the Customer Notification Status is Pending.
- After the email is sent, the notification status changes to Sent.
- This prevents the same resolution notification from being sent repeatedly.

## 6. Business Benefits
- Faster ticket assignment.
- Better visibility into customer complaints.
- Reduced manual administrative work.
- Improved customer communication.
- Clearer accountability for support teams.
