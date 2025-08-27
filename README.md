Situation:
The UNSW Student Accommodation team faced significant challenges in managing the application process:
1.	High application volume – without a centralized monitoring platform, staff could not efficiently track and process thousands of student applications.
2.	Complex applicant categories – it was difficult to properly allocate and prioritize groups such as scholarship holders, partner program students, and applicants with disabilities, leading to inefficiencies and potential misallocations.

Project Goal: Deliver a data-driven platform that shortens processing times, improves allocation fairness for priority groups (e.g. scholarship recipients, partners) and provides staff with a transparent, real-time monitoring dashboard. 

My Responsibility
- Led a five-member team to execute full ETL on over 39 000 UNSW accommodation records (2022–2025).  
- Cleansed and standardised data using Python & pandas.  
- Created new DAX measures to calculate processing time, reply time and availability.  
- Built interactive visuals and pages in Power BI covering processing time, room‐type preferences, applicant segmentation and real-time availability. 

 Outcomes
1. Correlation Insight: Faster staff processing leads to quicker student replies.  
2. Peak Load Analysis: November has the highest application volume (2,761) but also the slowest average reply (2.9 days), prompting a recommendation for automated reminders.  
3. Preference Discovery: Universal demand for private single rooms and two-bed units across all student groups, suggesting an adjustment in room supply.  
4. Real-Time Monitoring: A dashboard showing available rooms within the next 130 days and 1 year, enabling proactive waitlist offers and higher utilisation.  
5. Academic Recognition: Project awarded Distinction (80/100) and led to an internship interview with UNSW Student Accommodation. 


Analysis Steps

In Processing Time Analysis
   - Measure: days between application date and offer-sent date (DAX).  
   - Visuals: line charts of average processing & reply to times by month.  
   - Insight: 116 offers processed same-day; 900 replies within one day.  
   - ![Processing time ](https://github.com/user-attachments/assets/0dd539b9-1f9c-4235-b928-29334eb6fabf)


In Applicants Analysis
   - Ranking of 1st–3rd popular room types overall.  
   - Filters by applicant group: scholarships, partners, families, Aboriginal students.  
   - Insight:  
     - Scholarship → Studio & Single rooms  
     - With partner → One-bed & Two-bed units  
     - With children → Two-bed units  
     - Aboriginal → Private smaller rooms  
   ![Applicants Analysis](https://github.com/user-attachments/assets/b4b5640b-a05b-4247-9439-6b3d8c98f9c6)


Real-Time Monitoring Dashboard
   - New DAX measures for “Available within 130 days” and “Available within 1 year.”  
   - Top table: short-term availability (next 130 days)  
   - Bottom chart: long-term availability (1 year horizon)  
   - Enables staff to identify vacancies and proactively offer waitlist spots
 ![Real time monitoring](https://github.com/user-attachments/assets/0c5638b5-d4f8-4cd2-9639-67c74ecc70f3)
