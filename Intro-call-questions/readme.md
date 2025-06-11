# 📚 Interview Preparation Notes – Nikitha Pulluri

## General Questions

### 👋 Tell Me About Yourself

Hi, I'm Nikitha Pulluri. I’m a Data Engineer with over four years of experience building scalable data pipelines and working with cloud platforms like AWS, GCP, and Azure. I recently completed my Master’s in Information Technology and Management from Florida Atlantic University, where I also led a real-time data lake project using AWS services.

Currently, I’m working at Medical Mutual, where I helped develop a resource onboarding platform using Snowflake and Matillion, improving onboarding efficiency by 25%. I’ve also built ETL pipelines using Python and Airflow, and worked on optimizing Snowflake queries for better performance.

Before that, I worked at HDFC Bank in India, where I designed Spark-based pipelines and automated data validation using Airflow and Python, which really strengthened my experience in big data processing and real-time analytics.

I enjoy solving data challenges and love working on cloud-native solutions. Outside of work, I mentor students in data engineering and recently analyzed IPL cricket data using Apache Spark as a side project.

---

### 🛠 Explain About Your Recent Project

Sure! In my most recent project at Medical Mutual, I worked on building a resource onboarding platform that helped automate and streamline how new team members are added to our systems. I developed data pipelines using Snowflake and Matillion, which made the whole process faster and more efficient—we saw about a 25% improvement in onboarding time.

I also collaborated with engineering teams to build a user-friendly onboarding website and worked on optimizing Snowflake SQL queries, which improved performance by 30%. Most of the data workflows were handled through Python scripts, scheduled using Airflow, and we deployed everything in the GCP environment using tools like Azure DevOps and Git.

This project helped me sharpen my cloud skills, especially in Snowflake, GCP, and Airflow, and gave me a great opportunity to work closely with cross-functional teams to build something impactful.

---

### 🎯 What Do You Find Most Challenging and Rewarding in Your Recent Role?

One of the most challenging parts of my recent role was building reliable data pipelines across different tools and cloud platforms—especially ensuring data quality while integrating systems like Snowflake, Matillion, and Airflow in a GCP environment. Managing dependencies and troubleshooting failures in production pipelines required a lot of attention to detail and problem-solving under pressure.

But that challenge also made the work really rewarding. I found it fulfilling to see how my efforts directly improved the onboarding process, reducing manual steps and saving time for both the engineering and HR teams. It was great to know that the tools I built were actually making people’s day-to-day work easier, and that gave me a real sense of impact.

---

### 🚀 Career Goals and How This Role Fits In

My career goal is to become a well-rounded data engineer with deep expertise in building scalable, cloud-native data solutions that support real-time analytics and decision-making. I’m especially interested in working with modern tools like Airflow, Spark, Snowflake, and cloud platforms like GCP and AWS to solve complex data challenges.

This role aligns perfectly with my goals because it gives me the opportunity to apply and deepen my technical skills while working on impactful projects. I’m also looking forward to collaborating with cross-functional teams, learning from experienced engineers, and growing into a position where I can eventually mentor others and contribute to high-level architecture decisions.

---

## 💻 Technical Questions

### What programming languages and tools are you most comfortable with?

I'm most comfortable with Python and SQL—I use them regularly for writing data pipelines, transformations, and queries. I’ve used Python with Airflow to automate workflows and schedule tasks, and SQL for building complex logic in Snowflake and Redshift.

I also have strong experience with cloud platforms like GCP, AWS, and Azure. In my recent project, I built ETL pipelines in GCP using Snowflake and Matillion, and managed deployments with Azure DevOps.

Apart from that, I’ve worked with Spark for big data processing, DBT for data modeling, and Power BI to create dashboards and reports that help teams make better decisions. I enjoy using the right tool for the problem, and I’m always open to learning new ones when the project needs it.

---

### What experience do you have with data warehousing or cloud platforms like AWS, Azure, or GCP?

I’ve had hands-on experience with all three major cloud platforms—AWS, Azure, and GCP—mostly through real-world projects.

In my recent role, I worked primarily with GCP, where I built data pipelines using Snowflake and Matillion, scheduled jobs with Airflow, and handled deployments using Azure DevOps. I also worked with AWS services like S3, Glue, Redshift, and Lambda in a previous project to build a custom data lake and automate ingestion.

I’m comfortable setting up cloud-based data workflows, managing permissions, and working with both batch and real-time processing. I really enjoy the flexibility these platforms offer and always try to follow best practices when it comes to scalability and cost-efficiency.

---

### Have you worked with large datasets? If so, how did you ensure accuracy and integrity?

Yes, I’ve worked with large datasets in both batch and real-time environments. For example, in one of my projects, I processed millions of records daily using Spark and Airflow pipelines, and stored the data in Snowflake and Redshift.

To ensure accuracy and integrity, I implemented data validation checks, such as row counts, schema matching, and null value checks, at each stage of the pipeline. I also used logging and alerting in Airflow to monitor data flows and catch issues early. In some projects, I used tools like DBT and Great Expectations for automated data testing and documentation.

Making sure the data is correct and trustworthy is really important to me—especially when teams are using it to make business decisions.

---

### Can you describe a time you had to troubleshoot a data-related issue?

Yes! In one of my recent projects at Medical Mutual, I noticed that a scheduled data pipeline in Airflow was completing successfully, but the final output in Snowflake had missing records. It was a bit tricky because there were no errors in the logs.

I started by checking upstream tasks and realized that a Python script responsible for filtering data had a logic issue, where it was unintentionally excluding valid records due to a mismatch in date formats. I fixed the logic, updated the date handling, and added a validation step to compare source and target counts.

After the fix, I also set up monitoring and alerting to catch any mismatches in the future. It was a good reminder that even when pipelines look healthy, it's important to have validation checks in place to ensure data accuracy.

---

## 👥 Behavioral Questions

### Tell me about a time you had to collaborate with a cross-functional team to complete a project.

In my recent project at Medical Mutual, I worked closely with engineering, HR, and business teams to build a resource onboarding dashboard. While I handled the backend data pipeline using Snowflake, Matillion, and Airflow, I also collaborated with frontend developers and business stakeholders to ensure the data was structured in a way that made sense for reporting and decision-making.

We held regular sync-ups to align on requirements and timelines. I found it rewarding to translate technical data issues into clear updates that non-technical teams could act on. That collaboration helped us launch the platform smoothly and cut onboarding time by 25%.

---

### How do you stay updated on the latest data engineering trends and technologies?

I stay updated by regularly following tech blogs, YouTube channels, and platforms like Medium and Towards Data Science. I also participate in online courses and recently completed certifications in AWS data engineering and Power BI. GitHub is another great source—I like exploring open-source projects to see how others solve similar problems. Whenever possible, I apply new learnings to side projects to gain hands-on experience.

---

### What are your preferred methods for communicating technical information to non-technical audiences?

I focus on keeping things simple and relevant. I avoid jargon and try to explain the “what,” “why,” and “how” behind any data insight or system change. Visual tools like Power BI dashboards or even simple charts help a lot in making the message clearer. I also make sure to connect the technical details to business outcomes, so it’s easier for non-technical stakeholders to see the value.

---

## ❓ Questions to Ask the Recruiter

- What tools and technologies does the data team currently use, and are there plans to adopt any new ones?
- What does the interview process look like for this role?
- Are there any assessments or technical interviews I should prepare for?
- What technologies and tools does the team primarily use?
- How closely does this role work with other teams, like product or business stakeholders?

---
