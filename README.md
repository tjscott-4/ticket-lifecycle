<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
## 🧠 osTicket: Ticket Lifecycle Management

This project demonstrates the complete lifecycle of a help desk ticket using **osTicket**, hosted on a **Windows 10 VM in Microsoft Azure**.  
It showcases how IT professionals handle service requests from **initial intake** to **final resolution**, following structured, real-world support workflows.

---

## 🧠 Technologies Used

- **osTicket** – Open-source Help Desk and Ticketing System  
- **Microsoft Azure** – Cloud Infrastructure Hosting  
- **Remote Desktop Protocol (RDP)** – Remote Management Access  
- **Windows 10 Professional x64 (22H2)** – Operating System Environment  

---

## 📝 Ticket Lifecycle Stages

1. **Intake** – User submits a support request  
2. **Assignment & Communication** – Admin triages and assigns tickets  
3. **Working the Issue** – Agent investigates and resolves the issue  
4. **Resolution** – Issue is closed and user is notified  

---

## ♻️ Ticket Lifecycle Example: From Intake to Resolution

---

### 📩 **Intake**

**Steps:**
1. Navigate to `http://localhost/osTicket/index.php`
2. Click **“Open a New Ticket”**
3. Complete the required fields:
   - **Email Address:** Contact email of the requester  
   - **Full Name:** End user’s full name  
   - **Help Topic:** Select from the dropdown (e.g., Password Reset, Hardware Issue)  
   - **Issue Summary:** Short title and an optional detailed description  

**Example:**  
Jane Doe (`jane.doe1999@gmail.com`, 999-999-9999) submits a ticket reporting issues accessing **online mobile banking**.

📘 **Why this matters:**  
Accurate and detailed ticket submissions help technicians respond efficiently and prevent miscommunication.

🧠 **Skills demonstrated:**  
- End-user intake and ticket documentation  
- Categorization and communication clarity  

![End User Ticket Screenshot](images/ticket_intake.png)

---

### 💬 **Assignment & Communication**

**Steps:**
1. Log in as an **Administrator** at `http://localhost/osTicket/scp/login.php`  
2. Navigate to **Tickets → Open** and select the new ticket  
3. Configure the following fields:
   - **Priority:** High  
   - **Department:** Support or SysAdmins  
   - **Assigned To:** Choose the appropriate agent  
   - **SLA Plan:** SEV-A  

4. Add internal notes or updates in the ticket thread  
5. Click **Post Reply** to assign and notify the user  

📘 **Why this matters:**  
Proper triage and communication ensure tickets are routed efficiently and within SLA expectations.

🧠 **Skills demonstrated:**  
- Ticket prioritization and workflow management  
- SLA application  
- Clear internal and external communication  

![Admin Assign Ticket Screenshot](images/ticket_assignment.png)

---

### 🛠️ **Working the Issue**

**Steps:**
1. Log in as the **Assigned Agent** at `http://localhost/osTicket/scp/login.php`  
2. View the **Tickets** dashboard showing ticket number, priority, subject, submitter, and assigned agent  
3. Open the ticket to:
   - Review ticket history and updates  
   - Communicate with the end user through **Post Reply**  
   - Leave internal notes for other technicians or supervisors  

**Example:**  
The assigned agent reviews Jane Doe’s ticket, identifies the issue, and provides a detailed, professional response explaining the resolution.

📘 **Why this matters:**  
Simulates real-world troubleshooting workflows and professional communication with end users.

🧠 **Skills demonstrated:**  
- Troubleshooting and problem documentation  
- Agent collaboration  
- End-user communication and resolution reporting  

![Agent Working Ticket Screenshot](images/ticket_working.png)

---

### ❤️‍🩹 **Resolution**

**Steps:**
1. Before posting the final reply, set **Ticket Status → Closed**  
2. Click **Post Reply** to finalize the resolution  
3. osTicket displays confirmation:
   - The ticket no longer appears under **Open Tickets**  
   - A success banner confirms: “Reply posted successfully.”  

4. To view closed tickets:  
   - Navigate to **Tickets → Closed**  
   - Filter by the relevant date or time period  

📘 **Why this matters:**  
Closing tickets ensures proper documentation, helps track resolution metrics, and maintains service accountability.

🧠 **Skills demonstrated:**  
- Ticket lifecycle completion  
- SLA closure documentation  
- Post-resolution verification  

![Ticket Closed Confirmation Screenshot](images/ticket_closed.png)

---

## 🧩 Real-World Application

In enterprise environments, support tickets may originate through **email, chat, web forms, or in-person requests**.  
Even minor issues should be logged to maintain visibility, performance metrics, and consistent service quality.

📘 **Why this matters:**  
Documenting every interaction creates transparency, tracks workloads, and improves customer satisfaction.

🧠 **Skills reinforced:**  
- ITIL-aligned service management  
- Process standardization  
- Accountability and operational efficiency  

![Real World Workflow Screenshot](images/ticket_realworld.png)
