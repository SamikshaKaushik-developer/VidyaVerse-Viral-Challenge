### The VidyaVerse Viral Challenge: From Clicks to Course Champions 🚀

---

### Project Overview 📈

This GitHub README outlines a data analytics mini-project for VidyaVerse, an Ed-Tech startup. The project, "The VidyaVerse Viral Challenge," aimed to determine if a recent social media campaign, "#DataDreamer," successfully converted viral buzz into valuable, course-completing students.My role as a data analyst was to investigate this using a full data analytics workflow, from data cleaning to final analysis and a strategic recommendation.

The central business question was whether the high ad spend was justified by the quality of students acquired. The goal was to provide a data-backed verdict to the Head of Growth, Priya Sharma, on which platform brought in students who actually finish the course.

---

### Data & Tools 🛠️

#### Datasets
The analysis was performed using two raw CSV files:
* `campaign_performance.csv`: Raw data from ad platforms, including `campaign_id`, `ad_date`, `platform`, `ad_spend`, `clicks`, and `impressions`.
* `student_enrollments.csv`: Data from the student information system, including `student_id`, `signup_date`, `course_name`, `completion_percentage`, and `source_campaign_id`.

#### Tools
The project utilized a modern toolset to manage, analyze, and visualize findings
* **Notion AI**: For project management, creating a dynamic workspace, and summarizing key findings
* **MindMup**: For brainstorming initial hypotheses and mapping out data points needed to validate them.
* **MySQL Workbench**: To ingest raw data, perform SQL `JOINs`, and create a unified master dataset
* **Google Colab + Python (Pandas)**: For data cleaning, deep statistical analysis, and uncovering insights
* **Google Slides**: To craft and present the final data story and strategic recommendation
* **Perplexity AI / ChatGPT / Gemini**: Used for code assistance, narrative crafting, and industry benchmarking

---

### Project Workflow ⚙️

The project followed a five-phase "Analytics Sprint" timeline:

1.  **Phase 1: Mission Scoping & Hypothesis Mapping ** 🧭
    * Structured the investigation and defined the objectives
    * Used Notion AI to create a project plan and MindMup to brainstorm initial hypotheses
    * For example, a hypothesis might be that "YouTube delivers students with higher completion rates".

2.  **Phase 2: The Data Laundromat ** 🧼
    * Cleaned and standardized the raw data using Python and Pandas in Google Colab
    * Fixed inconsistencies in the `platform` column (e.g., standardizing 'insta' and 'Instagram Ads' to 'Instagram') and removed duplicates
    * The cleaned data was then exported to a new file, `campaigns_cleaned.csv`
      
3.  **Phase 3: The Great Merge ** 🤝
    * Combined the marketing and student data to create a powerful master view
    * Created a `vidyaverse_analytics` schema in MySQL Workbench and imported the datasets.
    * A SQL query using `JOIN` was crafted to link the two tables, creating the heart of the project
    * The final, merged data was exported to `master_analytics_data.csv`
      
4.  **Phase 4: The Eureka Moment - Analysis ** 💡
    * Loaded the merged data into a new DataFrame in Google Colab.
    * Engineered key metrics, including **Cost Per Signup (CPS)** (`ad_spend` / total signups) and the "killer metric" **Cost Per Completed Student (CPCS)** (`ad_spend` / number of students with >90% completion)
    * Used `groupby('platform')` to calculate and compare these metrics for each social media platform.
  
5.  **Phase 5: Crafting the Data Story ** ✍️
    * Translated the numerical findings into a persuasive business recommendation
    * Created a Google Slides presentation with a punchline, evidence, and a clear recommendation[cite: 80, 82, 83]. [cite_start]For example, the recommendation could be to "Shift 30% of Instagram budget to YouTube for the next campaign"
    * Used Perplexity AI to benchmark findings against industry standards.

---

### Final Deliverables 🏆

* **Notion Project Page Link**: A publicly shared link to the project's workspace
* **MindMup Hypothesis Map**: A shared link or screenshot of the hypothesis map
* **Google Colab Notebook**: An `.ipynb` file with well-commented code for cleaning and analysis
* **Google Slides Presentation**: The final presentation with the strategic recommendation

### Contributors 💻:
**[Suresh jangid]**

* LinkedIn: http://www.linkedin.com/in/suresh-jangid-b06a47280
* GitHub: https://github.com/Sureshjangid99
  

**[Samiksha Kaushik]**

* LinkedIn: https://www.linkedin.com/in/samiksha-kaushik-b8a6702a5
* GitHub: https://github.com/SamikshaKaushik-developer


**[Krishna Pratap Singh Chauhan]**

* LinkedIn: https://www.linkedin.com/in/kpsingh20
* GitHub: https://github.com/kpsingh-26


**[Ishita Chaudhary]**

LinkedIn:
GitHub: https://github.com/Ishita-tech-hub
