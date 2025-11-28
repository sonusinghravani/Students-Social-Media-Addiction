# 📱 Students Social Media Addiction Dashboard

**Made by:** Sonu Kumar  
**Trained at:** Career247 
**Date:** November 28, 2025

---

## 🎯 Business Problem

Social media addiction among students is growing fast — and it’s affecting their studies, sleep, mental health, and relationships. Schools, parents, and policymakers need to understand:

- Which age group uses social media the most?  
- Do males or females spend more time online?  
- Which platforms are most addictive?  
- How does usage affect grades and sleep?  
- Is there a link between addiction score and mental health?

This dashboard was built to answer these questions using real student survey data — provided by **Career247 Institute** as part of our training program.

---

## 📊 Dashboard Goal

The goal is to help educators, counselors, and researchers:

- See how much time students spend on social media (avg: 4.92 hours/day)  
- Compare usage by gender, academic level, and age  
- Find which platforms cause the most academic damage  
- Spot trends between addiction, sleep, and mental health  
- Make data-backed decisions to guide students toward healthier habits

---

## 🔍 Interactive Feature: Drill-Through to Student ID

I added a **Drill-Through** feature that lets users click on any student’s ID to see their full profile — including:

- Country  
- Avg Sleep Hours  
- Avg Usage Hours  
- Addicted Score  
- Most Used Platform  
- Conflict Level  
- Mental Health Score  

> ✅ *Why this matters?*  
It helps counselors or teachers identify high-risk students quickly. For example, if a student has high “Addicted_Score” + low “Mental_Health_Score”, they can get immediate support.

This feature was built using Power BI’s native **Drill-Through functionality**, linked to the main `Student` table.

---

## 🖼️ Key Visuals — Why They Were Chosen

*(Same as before — but now with Drill-Through added)*

### 1. **KPI Summary (Avg Usage Hours, Student Count, % Affected Academically, Avg Sleep Hours)**  
> *Why?*  
These 4 numbers give an instant snapshot of the problem. Example: 705 students surveyed, average usage = 4.92 hours, 64% affected academically, avg sleep = 6.87 hours. Perfect for quick decision-making.

### 2. **Avg Usage Hours by Gender (Bar Chart)**  
> *Why?*  
Females use social media slightly more (5.0 hrs) than males (4.8 hrs). Helps target awareness programs based on gender.

### 3. **Sum of Avg Daily Usage by Academic Level (Bar Chart)**  
> *Why?*  
Undergraduates use the most (1766 total hours), followed by Graduates (1553). High School students use the least (150). Shows where intervention is most needed.

### 4. **Count of Most Used Platform by Gender & Academic Level (Donut Charts)**  
> *Why?*  
Shows which apps students prefer. TikTok, Instagram, WhatsApp top the list. Also shows if preferences differ by gender or study level — useful for platform-specific campaigns.

### 5. **% Affected Academically by Platform (Bar Chart)**  
> *Why?*  
KakaoTalk & WhatsApp have 100% academic impact — meaning every user of these apps reports being affected. Facebook & YouTube have lowest impact (30%). Helps schools focus on high-risk apps.

### 6. **Addicted Score vs Mental Health Score (Scatter Plot)**  
> *Why?*  
Higher addiction score = lower mental health score. Clear negative correlation. Proves that social media addiction harms mental well-being.

### 7. **Avg Sleep Hours vs Age (Line Chart)**  
> *Why?*  
Sleep dips at age 23 (avg 4.51 hrs), then rises again. Shows peak stress/usage years — useful for counseling support timing.

### 8. **Relationship Status Distribution (Pie + Bar Chart)**  
> *Why?*  
Most students are single (54.47%), followed by “In Relationship” (40.99%). Single students report higher conflict levels — maybe due to more screen time or less emotional support.

---

## 💡 Key Business Insights

- **Undergraduates** are the most active users — target them with digital wellness workshops.
- **Females** spend slightly more time on social media — tailor content for them.
- **KakaoTalk & WhatsApp** have 100% academic impact — warn students about overuse.
- **High addiction score = low mental health** — school counselors should check this link.
- **Age 23** has lowest sleep — offer stress management sessions during final year.
- **Single students** face more conflict — maybe add peer support groups.
- **Drill-Through feature** allows deep-dive into individual student data — critical for personalized support.

---

## 🛠️ Tools Used

- **Power BI** – For building the dashboard and visuals
- **Power Query** – To clean and structure the raw student survey data
- **DAX** – For creating calculated columns like “% Affected Academically”, “Addicted Score”
- **Data Modeling** – Created relationships between tables (Student, Country, Platform, etc.)
- **Custom Visuals** – Used scatter plots, donuts, and line charts for better storytelling
- **Drill-Through** – Built to allow users to explore individual student records

---

## 📄 Purpose and Description

This dashboard was created as part of my training at **Career247 Institute**, where I’m learning **Generative AI + Data Analytics** together.

The dataset was provided by Career247 — it includes 705 students from 40+ countries, with details on usage hours, platforms, mental health, academic performance, and more.

I cleaned and prepared the data using **Power Query**, created calculated metrics in DAX, and built interactive features like **Drill-Through to Student ID** — so educators can see exactly which students need help.

The dashboard tells a powerful story: **social media is not just entertainment — it’s impacting students’ lives deeply**. And with the right tools, we can help them find balance.

This project reflects my skills in:

✔️ Data Cleaning & Preparation  
✔️ Power BI Dashboard Design  
✔️ Interactive Features (Drill-Through)  
✔️ Storytelling with Data  
✔️ Working with Real-World Datasets

All under the guidance of **Career247 Institute** — where I’m learning to combine AI and analytics for real-world impact.

---

## 👤 About Me

**Name:** Sonu Kumar  
**Skills:** Power BI, Power Query, DAX, Data Visualization, Drill-Through, Generative AI Basics  
**Goal:** To build smart, human-centered dashboards that help people make better decisions — especially in education and mental health.

1.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/1.%20Overview.png
2.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/2.%20Mental%20health.png
3.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/3.Academic%20impact.png
4.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/4.%20Relationship%20and%20conflict.png
5.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/5.Interactive%20Story.png
6.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/6.Drill%20Through.png
7.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/7.Student%20Id.png
8.	https://github.com/sonusinghravani/Students-Social-Media-Addiction/blob/main/8.%20Interactivity%20and%20storytelling.png


