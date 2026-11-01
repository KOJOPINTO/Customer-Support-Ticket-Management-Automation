# Workflow Overview – Customer Support Ticket Management Automation

## Project Overview

This project automates customer support ticket registration, assignment, notifications, and resolution tracking using Make.com.

It helps businesses manage customer complaints more efficiently while reducing manual administrative work.

## Tools Used

- **Google Forms:** Collects customer support requests.
- **Google Sheets:** Stores tickets and tracks their progress.
- **Make.com:** Automates ticket creation, routing, and notifications.
- **Gmail:** Sends customer confirmations, business notifications, and resolution emails.

## Workflow 1: Ticket Registration and Assignment

1. A customer submits the Google Form.
2. Make.com detects the new spreadsheet row.
3. A unique Ticket ID is generated.
4. The ticket status is initialized as Open.
5. A Router checks the issue category.
6. The ticket is assigned to the appropriate department and technician.
7. The customer receives a confirmation email.
8. The business receives a ticket notification.

## Workflow 2: Ticket Resolution Notification

1. Make.com searches for tickets marked Resolved.
2. It checks that the Customer Notification Status is Pending.
3. Gmail sends a resolution email to the customer.
4. Google Sheets updates the notification status to Sent.

## Ticket Categories and Assignment

| Category | Department | Technician |
|---|---|---|
| Technical Support | IT Support | Technician 1 |
| Billing & Payments | Finance | Technician 2 |
| Account Access | Account Management | Technician 3 |
| Product or Service | Customer Service | Technician 4 |
| Other | General Support | Technician 5 |

## Expected Business Impact

- Faster handling of customer complaints.
- Automatic assignment of support responsibilities.
- Consistent customer communication.
- Improved ticket tracking and accountability.
- Reduced repetitive administrative tasks.
