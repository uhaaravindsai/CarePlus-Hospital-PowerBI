\# CarePlus Hospital — Power BI Analytics



\## 📊 Project Overview



CarePlus Hospital Analytics is an interactive Power BI project developed to analyze hospital appointments, patients, treatments, doctors, rooms, and operational performance.



The project transforms hospital operational data into interactive dashboards and KPIs to support data-driven analysis and business understanding.



\## 🎯 Project Objectives



\- Analyze appointment demand

\- Understand patient appointment behaviour

\- Evaluate treatment performance

\- Analyze doctor performance

\- Analyze room and equipment activity

\- Identify appointment and treatment problems

\- Present key findings through an executive summary



\## 🛠️ Tools \& Technologies



\- Power BI

\- Power Query

\- DAX

\- Data Cleaning \& Transformation

\- Data Modeling

\- Data Visualization

\- CSV



\## 📁 Dataset



The project uses six datasets:



\- Patients

\- Doctors

\- Rooms

\- Appointments

\- Treatments

\- Date Table



The data was cleaned and transformed using Power Query before creating the Power BI data model.



\## 🔗 Data Model



The Power BI model contains relationships between:



\- Patients and Appointments

\- Doctors and Appointments

\- Appointments and Treatments

\- Doctors and Treatments

\- Rooms and Treatments

\- Date Table and Appointments

\- Date Table and Treatments



The model uses an inactive treatment-date relationship for treatment-date analysis.



\## 📈 Dashboard Pages



\### 1. Appointment Demand Analysis



Analyzes:



\- Appointment volume

\- Appointment value

\- Average appointment value

\- City-wise demand

\- Service types

\- Priorities

\- Booking channels

\- Monthly appointment trends

\- Patient type and service type value



\### 2. Patient Appointment Behaviour



Analyzes:



\- Total patients

\- Appointments per patient

\- Patient distribution by city

\- Patient types

\- Patient appointment activity

\- Preferred time slots

\- Booking trends

\- Cumulative appointment value



\### 3. Treatment Performance Analysis



Analyzes:



\- Treatment outcomes

\- Treatment outcomes by city

\- Treatment outcomes by service type

\- Average waiting time

\- Average treatment duration

\- Treatment trends by actual treatment date



\### 4. Doctor \& Room Performance



Analyzes:



\- Active doctors

\- Treatments per doctor

\- Treatments by specialty

\- Doctor treatment workload

\- Doctor treatment outcomes

\- Treatment duration by doctor

\- Waiting time by doctor

\- Room activity

\- Room type activity

\- Equipment type activity



\### 5. Appointment \& Treatment Problems



Analyzes:



\- Multiple treatment attempts

\- Multiple attempt rate

\- Waiting time for multiple attempts

\- Problem treatments

\- Problem treatment rate

\- No-show rate

\- Cancellation rate

\- Rescheduled treatments

\- Problems by city

\- Waiting time by priority

\- Treatment outcomes by priority



\### 6. Executive Summary



Provides a high-level view of:



\- Total appointments

\- Total patients

\- Total treatments

\- Treatment completion rate

\- No-show rate

\- Average waiting time

\- Active doctors

\- Problem treatment rate



\## 📌 Key KPIs



\- Total Appointments

\- Total Patients

\- Total Treatments

\- Total Appointment Value

\- Average Appointment Value

\- Treatment Completion Rate

\- No-Show Rate

\- Average Waiting Time

\- Average Treatment Duration

\- Active Doctors

\- Multiple Attempt Rate

\- Problem Treatment Rate



\## 📂 Project Structure



```text

CarePlus-Hospital-PowerBI/

│

├── Dataset/

│   ├── patients.csv

│   ├── doctors.csv

│   ├── rooms.csv

│   ├── appointments.csv

│   ├── treatments.csv

│   └── date\_table.csv

│

├── PowerBI/

│   └── CarePlus\_Hospital\_Analytics.pbix

│

├── Screenshots/

│   ├── 01\_Appointment\_Demand.jpeg

│   ├── 02\_Patient\_Appointment\_Behaviour.jpeg

│   ├── 03\_Treatment\_Performance.jpeg

│   ├── 04\_Doctor\_Room\_Performance.jpeg

│   ├── 05\_Appointment\_Treatment\_Problems.jpeg

│   └── 06\_Executive\_Summary.jpeg

│

├── README.md

└── .gitattributes

