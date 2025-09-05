### The VidyaVerse Viral Challenge: From Clicks to Course Champions 🚀

---

### Project Overview 📈

[cite_start]This GitHub README outlines a data analytics mini-project for VidyaVerse, an Ed-Tech startup[cite: 7]. [cite_start]The project, "The VidyaVerse Viral Challenge," aimed to determine if a recent social media campaign, "#DataDreamer," successfully converted viral buzz into valuable, course-completing students[cite: 9, 17]. [cite_start]My role as a data analyst was to investigate this using a full data analytics workflow, from data cleaning to final analysis and a strategic recommendation[cite: 12, 14].

[cite_start]The central business question was whether the high ad spend was justified by the quality of students acquired[cite: 18]. [cite_start]The goal was to provide a data-backed verdict to the Head of Growth, Priya Sharma, on which platform brought in students who actually finish the course[cite: 17, 20].

---

### Data & Tools 🛠️

#### Datasets
[cite_start]The analysis was performed using two raw CSV files[cite: 24]:
* [cite_start]`campaign_performance.csv`: Raw data from ad platforms, including `campaign_id`, `ad_date`, `platform`, `ad_spend`, `clicks`, and `impressions`[cite: 25, 27].
* [cite_start]`student_enrollments.csv`: Data from the student information system, including `student_id`, `signup_date`, `course_name`, `completion_percentage`, and `source_campaign_id`[cite: 28, 29].

#### Tools
[cite_start]The project utilized a modern toolset to manage, analyze, and visualize findings[cite: 13]:
* [cite_start]**Notion AI**: For project management, creating a dynamic workspace, and summarizing key findings[cite: 22].
* [cite_start]**MindMup**: For brainstorming initial hypotheses and mapping out data points needed to validate them[cite: 22].
* [cite_start]**MySQL Workbench**: To ingest raw data, perform SQL `JOINs`, and create a unified master dataset[cite: 22].
* [cite_start]**Google Colab + Python (Pandas)**: For data cleaning, deep statistical analysis, and uncovering insights[cite: 22].
* [cite_start]**Google Slides**: To craft and present the final data story and strategic recommendation[cite: 78, 83].
* [cite_start]**Perplexity AI / ChatGPT / Gemini**: Used for code assistance, narrative crafting, and industry benchmarking[cite: 22, 84].

---

### Project Workflow ⚙️

[cite_start]The project followed a five-phase "Analytics Sprint" timeline[cite: 34]:

1.  **Phase 1: Mission Scoping & Hypothesis Mapping (30 minutes)** 🧭
    * [cite_start]Structured the investigation and defined the objectives[cite: 36].
    * [cite_start]Used Notion AI to create a project plan and MindMup to brainstorm initial hypotheses[cite: 37, 38, 42]. [cite_start]For example, a hypothesis might be that "YouTube delivers students with higher completion rates"[cite: 43].
2.  **Phase 2: The Data Laundromat (40 minutes)** 🧼
    * [cite_start]Cleaned and standardized the raw data using Python and Pandas in Google Colab[cite: 46, 47].
    * [cite_start]Fixed inconsistencies in the `platform` column (e.g., standardizing 'insta' and 'Instagram Ads' to 'Instagram') and removed duplicates[cite: 49, 50, 51].
    * [cite_start]The cleaned data was then exported to a new file, `campaigns_cleaned.csv`[cite: 53].
3.  **Phase 3: The Great Merge (40 minutes)** 🤝
    * [cite_start]Combined the marketing and student data to create a powerful master view[cite: 55].
    * [cite_start]Created a `vidyaverse_analytics` schema in MySQL Workbench and imported the datasets[cite: 57].
    * [cite_start]A SQL query using `JOIN` was crafted to link the two tables, creating the heart of the project[cite: 58, 59].
    * [cite_start]The final, merged data was exported to `master_analytics_data.csv`[cite: 61].
4.  **Phase 4: The Eureka Moment - Analysis (40 minutes)** 💡
    * [cite_start]Loaded the merged data into a new DataFrame in Google Colab[cite: 66].
    * [cite_start]Engineered key metrics, including **Cost Per Signup (CPS)** (`ad_spend` / total signups) and the "killer metric" **Cost Per Completed Student (CPCS)** (`ad_spend` / number of students with >90% completion)[cite: 67, 68, 69].
    * [cite_start]Used `groupby('platform')` to calculate and compare these metrics for each social media platform[cite: 71].
5.  **Phase 5: Crafting the Data Story (30 minutes)** ✍️
    * [cite_start]Translated the numerical findings into a persuasive business recommendation[cite: 76].
    * [cite_start]Created a Google Slides presentation with a punchline, evidence, and a clear recommendation[cite: 80, 82, 83]. [cite_start]For example, the recommendation could be to "Shift 30% of Instagram budget to YouTube for the next campaign"[cite: 83].
    * [cite_start]Used Perplexity AI to benchmark findings against industry standards[cite: 84, 85].

---

### Final Deliverables 🏆

* [cite_start]**Notion Project Page Link**: A publicly shared link to the project's workspace[cite: 88].
* [cite_start]**MindMup Hypothesis Map**: A shared link or screenshot of the hypothesis map[cite: 89].
* [cite_start]**Google Colab Notebook**: An `.ipynb` file with well-commented code for cleaning and analysis[cite: 90].
* [cite_start]**Google Slides Presentation**: The final presentation with the strategic recommendation[cite: 91].

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
