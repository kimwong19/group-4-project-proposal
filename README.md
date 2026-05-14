# Group project proposal

Directions:

- Use your work plan from class to fill in the information below.
- Practice pulling, making changes, staging/committing/pulling/pushing to the same repo.
- Communicate about who is doing what throughout the entire process.

What you will submit on Friday the 15th:

- proposal: a link to your forked repository with the completed proposal in the README
- work plan: your paper plan that you completed in class on Monday the 4th

Use your project proposal to:

- refer back to the original plan while you are working
- keep track of high-level changes in structure (e.g. role switching, elective modifications)

Note:

- your project proposal is subject to change after you learn more about your datasets and what is possible - allow yourselves the flexibility to make adjustments as needed
- the more detail you can provide in your proposal, the more thorough your feedback will be


## Group members
Stella Freedberg, Kimberly Wong, Sami Gibson

## Group name:
Invertebrates & Dissolved oxygen

## Topic information and question
**Topic:** Aquatic invertebrates

**Question(s):** 

- What is the strength of the relationship between DO and invertebrate abundance?

**Response variable(s)**

- Invertebrate Abundance (log + 1 transformed average abundance/L)

- Dissolved Oxygen (Median DO (mg/L))

## Datasets
**Datasets used:**

- Aquatic Sampling Data-2026-03-10.xlsx
  - Sheets: Water Quality, Aquatic Insects, sites
- taxon_list.csv

## Figures
**Potential figure 1:**

Abundance vs. DO
<img width="706" height="467" alt="abundance-vs-do" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/abundance-vs-do.png" />

**Potential figure 2:**

Invertebrate abundance vs. Site
<img width="738" height="465" alt="abundance-across-sites" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/abundance-across-sites.png" />

**Potential figure 3:**

DO vs. Site
<img width="703" height="473" alt="site-vs-do" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/site-vs-DO.png" />

**Potential figure 4:**

DO Distribution Across Sites
<img width="703" height="473" alt="do-distribution" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/do-distribution.png" />

**Potential figure 5:**

Invertebrate Abundance vs. DO Bins
<img width="703" height="473" alt="abundance-vs-do-bins" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/abundance-vs-do-bins.png" />

**Potential figure 6:**

DO and Abundance Correlation
<img width="1474" height="1604" alt="abundance-vs-DO-correlation" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/abundance-vs-DO-correlation.png" />

**Potential figure 7:**

DO and Abundance Correlation 2
<img width="1474" height="1604" alt="abundance-vs-do-correlation-2" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/abundance-vs-do-correlation-2.png" />

**Potential figure 8:**

Community composition plot
<img width="1474" height="1604" alt="composition-plot" src="https://github.com/kimwong19/group-4-project-proposal/blob/main/code/composition-plot.png" />

## Data cleaning/wrangling/summarizing plan

To clean the data, we will filter to only include quarterly surveys at NCOS and filtered beaker samples, select columns of interest, clean column names, remove outliers, and join data frames. Our data summarizing steps will include calculating median dissolved oxygen levels and average abundance per liter.  

## Project roles

**Natural history/framing director:** Stella Freedberg

**Stats and visualization director:** Sami Gibson

***GitHub/code director:** Kimberly Wong

## Elective

**Group members completing elective:** Stella Freedberg, Kimberly Wong, Sami Gibson

**Elective idea:**

We are planning to make a collage using water color and microscope images of invertebrates to visualize our data.
- add microscopic images of each of the 5 main inverts 
- Water color bubbles/ blow colored bubbles with watercolor around each to demonstrate how much dissolved oxygen each likes 
    - More bubbles = likes more DO
    - Less bubbles = likes less DO
<img width="703" height="287" alt="Screenshot 2026-05-06 at 6 59 23 PM" src="https://github.com/user-attachments/assets/842d70d9-9b74-4e5f-b167-0787fa86b987" />

**Elective timeline**:

Week 7: have set plan of what we want to visualize

Week 8 (timeline check in): begin assembling project 

Week 9: assemble the project + practice presentation

Week 10: finishing touches + present

Finals week: n/a
