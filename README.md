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
Karen submits a ticket reporting issues accessing **online mobile banking**.

📘 **Why this matters:**  
Accurate and detailed ticket submissions help technicians respond efficiently and prevent miscommunication.

🧠 **Skills demonstrated:**  
- End-user intake and ticket documentation  
- Categorization and communication clarity  

<img width="1303" height="565" alt="image" src="https://github.com/user-attachments/assets/b4749ec3-1465-465c-b5dc-22ce7cf85971" />
<img width="1119" height="1387" alt="image" src="https://github.com/user-attachments/assets/e44e1387-b1d3-4f9c-9645-2814703830dc" />


---

### 💬 **Assignment & Communication**

**Steps:**
1. Log in as an **Administrator** at `http://localhost/osTicket/scp/login.php`  
2. Navigate to **Tickets → Open** and select the new ticket
   <img width="629" height="226" alt="image" src="https://github.com/user-attachments/assets/47c3a913-8323-4f51-897d-1612757eb109" />

4. Configure the following fields:
   - **Priority:** High  
   - **Department:** Online Banking
   - **Assigned To:** Choose the appropriate agent  
   - **SLA Plan:** SEV-A
 <img width="626" height="322" alt="image" src="https://github.com/user-attachments/assets/415edb2c-d2a8-4150-ac2c-549ba13939cb" />


5. Add internal notes or updates in the ticket thread  
6. Click **Post Reply** to assign and notify the user  

📘 **Why this matters:**  
Proper triage and communication ensure tickets are routed efficiently and within SLA expectations.

🧠 **Skills demonstrated:**  
- Ticket prioritization and workflow management  
- SLA application  
- Clear internal and external communication  




---

### 🛠️ **Working the Issue**

**Steps:**
1. Log in as the **Assigned Agent** at `http://localhost/osTicket/scp/login.php`
<img width="370" height="255" alt="image" src="https://github.com/user-attachments/assets/7b218ff4-24b7-4397-b260-bb47eae75433" />

2. View the **Tickets** dashboard showing ticket number, priority, subject, submitter, and assigned agent
<img width="653" height="244" alt="image" src="https://github.com/user-attachments/assets/e2e45336-834a-4491-80b7-211f03beeb7c" />
 
3. Open the ticket to:
   - Review ticket history and updates  
   - Communicate with the end user through **Post Reply**  
   - Leave internal notes for other technicians or supervisors
<img width="631" height="632" alt="image" src="https://github.com/user-attachments/assets/1e3ca3d2-a538-465a-a171-eda1f1555cd2" />


**Example:**  
The assigned agent reviews Jane Doe’s ticket, identifies the issue, and provides a detailed, professional response explaining the resolution.

📘 **Why this matters:**  
Simulates real-world troubleshooting workflows and professional communication with end users.

🧠 **Skills demonstrated:**  
- Troubleshooting and problem documentation  
- Agent collaboration  
- End-user communication and resolution reporting  


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
