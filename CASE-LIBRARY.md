# Case library

Each case is one page in plain HTML, CSS and JavaScript with fictional data in a file in data/, and needs no library. To use one, rewrite CASE.md with its details.

| Case | What the page does | Rule to test | Human check |
|---|---|---|---|
| Expense report checker | Lists expense lines. Flags lines over the limit or with no receipt. | Flag lines over the limit or without a receipt. | A manager approves each flagged line. |
| Meeting cost calculator | Computes the cost of a meeting. Attendees times hourly rate times duration, with a warning above a set amount. | Check the total and warning threshold. | The organizer decides whether the meeting goes ahead. |
| Complaint SLA tracker | Lists customer complaints. Computes the reply deadline from the category and the customer tier. | Check the deadline for each category and tier. | A team lead reviews every late complaint. |
| Leave request tracker | Lists leave requests. Counts working days and the remaining balance. | Check working-day counts and balances. | A manager approves each request. |
| Invoice due-date tracker | Lists invoices. Shows days overdue and a late fee. | Check days overdue and fee calculations. | Finance approves any late fee before it is sent. |
| Event budget planner | Lists event costs. Adds up costs and warns before the budget is exceeded. | Check totals and the budget warning. | The event owner approves any overrun. |
| Onboarding checklist | Tracks tasks for a new hire. Groups tasks by week with a progress bar. | Check task grouping and progress. | The manager signs off each week. |
| Stock reorder alerts | Lists products. Shows products under their reorder point and the quantity to order. | Check which products need reordering and quantities. | A buyer approves large orders. |
| Lead scoring calculator | Scores sales leads. Adds points per criterion and gives an A, B or C priority. | Check points and priority bands. | A sales lead reviews every A lead before contact. |
| Supplier quote comparison | Compares three quotes. Ranks them on price, delay and quality with weights. | Check the weighted ranking. | The purchasing manager approves the choice. |
