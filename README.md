# streamlining-ticket-assignment-for-efficient-support-operations
This initiative aims to automate ticket routing at ABC Corporation, improving efficiency by assigning tickets to the right teams. It reduces resolution delays, enhances customer satisfaction, and optimizes resource use in the support department.

## 📌 Objective
Implement an automated system in ServiceNow to intelligently route support tickets to the correct team, reducing response times and improving operational efficiency.

## 🛠 Tools Used
- ServiceNow Flow Designer
- ServiceNow Tables (`u_operations_related`, `sys_user_group`)
- ACL and Business Rules (minor tweaks)
- GitHub for version control

## ⚙️ Workflow Summary
- Trigger: When a new ticket is created with `Issue = Regarding Certificates`
- Action: Automatically assigns the ticket to the **Certificates** group

## ✅ Output
- Reduced manual triage time
- Automatic group assignment
- Improved SLA compliance

## 📸 Screenshots
- Flow Design
- Test Ticket Creation
- Execution Logs
- Result Ticket with Group Assigned
