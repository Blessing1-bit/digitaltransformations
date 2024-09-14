<h1>Project: Endra McVernan Global Services: Adjusting to emerging business trends and demands</h1>
This was my final presentation project for the IT Business Analysis (CPMN-014-009) course at SAIT (Southern Alberta Institute of Technology). Please find attached business case document for your review

<h2>1.Introduction</h2>

Endra McVernan Global Services, a key player in the medical services industry that specializes in the production and supply of hospital equipment. Since its founding in 2005, the company has grown steadily, now employing over 800 people across several locations in Western Canada. Despite its success, the company has relied on the same operational software for over 15 years. As this legacy system reaches the end of its useful life, the company is faced with severe challenges that has negatively impacted its business operations.

<h2>Problem Statement</h2> 

- **Limited functionalities**: The customer service team is unable to effectively manage customer's orders, 
- **Poor Integration**: The current system is unable to connect with other systems thereby leading to data inconsistency.
- **Slow Performance**: The sales team spends a significant amount of time generating reports reducing their performance and productivity. 
- **Lack of Mobile Access**: The on-site support field technicians are not able to access customer's critical information for effective installation.
- **High Maintenance Cost**: The asset sustenance department spends a significant amount maintaining the outdated system resulting in frequent crashes.
<br />

<h2>Business Impact</h2>

- 30% increase in order processing times
- b13% decline in sales number
- 28% inventory discrepancies and production delays
- < 75% CSAT score
- Employee stress: 16% - 75%
<br />

<h2>Objectives</h2> 
As a Business Analyst, your role is pivotal in the implementation of new system to achieve the following objectives:

- Replace outdated operational software with a modern, integrated system.
- Streamline business processes and automate manual workflows.
- Improve system integration to reduce data inconsistencies and re-work.
- Provide mobile access for On-Site Support teams to access critical information on-the-go.
- Reduce maintenance costs and minimize system crashes.
<br />

<h2>In-Scope</h2> 
The development of a new integrated system will perform a range of actions: 

- **Workflow Automation**: Automate the manual processes across sales and customer service departments to improve efficiency and reduce errors.
- **System Integration**: Ensure seamless integration between the new system and other systems to eliminate data inconsistencies.
- **Mobile Access**: Enable mobile access for On-Site Support teams to retrieve critical information remotely.
- **Employee Training and Data Migration**: Train employees on the new system and migrating all relevant data from the legacy system to manage change effectively.
  <br />

<h2>Stakeholer </h2> 

- Customer Service
- IT Department
- Sales Team
- On-site support field technicians
- Asset Sustenance Department
- Customer: Stakeholder that triggers the order process
   <br />

<h2>2. Project Tasks and Deliverables</h2>
As a Business Analyst, the following deliverables were created to ensure seamless project execution:
Please find attached files for detailed descriptions of the artifacts developed in the course of executing this project

<h2>2.1 Current State Process Map</h2>

The current state process map was created to baseline the organization's customer service process

![image](https://github.com/user-attachments/assets/56b9258d-94cc-4c6f-9250-2d3abc0c142f)

<h2>2.2 Future State Process Map</h2>
The future state process map was created to visualize the TO-BE state of the customer ordering process.

![image](https://github.com/user-attachments/assets/45bc1f52-e696-4dec-8dda-b20c06a88ce9)

<h2>2.3 Functional Requirement Document</h2>

Based on the insruction for this project one functional requirement was created for each stakeholder group

| ID           | Stakeholder           | Funtional Requirements |
| :---         |     :---              |          :---          |
| FR-01        | Customer Service Team | The customer service team should be<br> able to manage customers orders in the system   |
| FR-02        | IT Department         | The system should be able to communicate<br> with other systems |
| FR-03        | Sales Team            | Generate sales reports on the system |
| FR-04        | On-site support field<br>technicians| Remote access to customers <br> order details on installing medical equipment on client site|
| FR-05        | Asset Sustenance Department| Implement a modern software <br>(resistant to crashes and with little or no maintenance cost)|

<h2>2.4 Conflicting Requirement</h2>
  
The conflicting requirements in the case study was that the deployment of a new system violate the company policy that prohibibited replacement before current system end of life.

- The initiation taken to resolve this was to update or modify the company policy to align with new realities and challenges of the organization.

<h2>2.5 User Stories </h2>

The functional specifications were translated into user stories and acceptance criteria to capture the stakeholder requirements from their perspective.

| Uers Story ID| Funtional<BR> Requirements ID| User Story Description | Acceptance Criteria        
| :---         |     :---              |          :---          |  :---      |
| US-01        | FR-01                 | As a Customer Service Rep,<br>I want to be able to process orders online,<br>so that I can reduce time wastage.| Online interface is accessible via a secure link,<br> online interface allows processing of orders in real-time |
| US-02        | FR-02                 | As an IT Analyst,<br>I want to be able to pull data from a single source,<br>so that I can be sure of the data quality.| Data interface is accessible via a secure link,<br> data interface allows a data pull from a single source with no errors |
| US-03        | FR-03                 | As a sales rep,<b> I want to generate sales reports,<b>  so I can forecast more accurately and be more productive.| Report interface is accessible via a secure link,<br> report includes forecasting tools suitable for sales prediction |
| US-04        | FR-04                 | As an on-site rep,<b> I want remote access on field,<b> so that I can access client information to complete installations.|  remote access is provided via a secure link,<br> client information is visible via remote access link |
| US-05        | FR-05                 | As an asset sustenance rep,<br>I want a stable system,<br>so I can reduce crashes and maintenance costs.| System maintains at least 90% uptime,<br> system can handle peak loads without crashing |

<h2>2.6 Solution Options</h2>

- ****Outsourcing**:** For certain functions that the legacy system struggles with, the company could consider outsourcing to specialized service providers 
with more advanced technological capabilities.
- **Process optimization:** The company could focus on streamlining and optimizing their business processes to improve efficiency, even within the 
constraints of their current system
- **New Software Implementation:** A company wide implementation of a new technology tool that can help the different departments become more 
productive and efficient (after the existing policy has been modified or cancelled)

However, implementing a new modern integrated software solution was considered a more suitable option because it provides access to real time consistent data accross the systema, it has mobile compatilbility, as well as low cost of maintenance which solves Mc vernan currrent challenges.

<h2>2.7 Test Plan</h2>

- **Test ID:** TC-01
- **Module:** Online Order Processing by Customer Service Rep
- **User Story ID:** US-O1
- **Test Scenario:** Test that the Customer Service Rep is able to process order online
- **Test Case:**  Test that I am logged in with a valid url as a customer service rep in the online order processing when I
-  **Pre-Conditions:**  1. The customer service rep is logged into the online order processsing.<br>                    2. The system is up and running
-  **Test Steps:** 1. Login to the online order processing system as a Customer Service rep<br> 2.  Navigate to the "New Order" section<br> 3. Enter or select the customer information (e.g., name, contact details, shipping address)<br> 4.  Search for and select one or more products as required<br> 5. Enter the quantity for one or more products as required<br> 6. Add the products to the order<br> 7. Review the order summary, including products, quantities, and total price<br> 8. Select a shipping or delivery method<br> 9. Process the payment (using a test payment method)<br> 10. Submit the order (note the time taken to complete the entire process)<br> 11. Verify that an order confirmation is generated<br> 12. Check that the order appears in the "Recent Orders" list<br> 13. Logout of the system| customer information (e.g., name, contact details, shipping address).
-  **Expected Result:**
-  **Actual Result:**
  
  

























  




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
