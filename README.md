# From analysis to action

In a world where access to clean water is a precious commodity, a team of dedicated researchers embarked on a mission to uncover the hidden truths of water quality in Maji Ndogo. Armed with data, they delved into the depths of information, seeking insights that could make a profound impact on the lives of countless individuals. In this 4 part project we, emphasize the importance of accurate information in addressing water challenges. By uncovering hidden truths and empowering individuals to make informed choices about their water sources, the team aimed to ensure equal access to clean and safe water for all in Maji Ndogo.

# Part 1: Beginning Your Data-Driven Journey in Maji Ndogo
We will be working with a database of 60,000 records, meticulously collected by our devoted team of engineers, field workers, scientists, and analysts.
We need to make sense of this immense data trove and extract meaningful insights breathe life into these records and listen to the story they are telling us.

#### 1. Get to know our data:
Before we do anything else, let's take a good look at our data. We'll load up the database and pull up the first few records from each table. It's like getting to know a new city- we need to explore the lay of the land before we can start our journey.

#### 2. Dive into the water sources: 
We've got a whole table dedicated to the types of water sources in our database. Let's dig into it and figure out all the unique types of water sources we're dealing with.

#### 3. Unpack the visits to water sources: 
The 'visits' table in our database is like a logbook of all the trips made to different water sources. We need to unravel this logbook to understand the frequency and distribution of these visits. Let's identify which locations have been visited more than a certain number of times.

#### 4. Assess the quality of water sources: 
The quality of water sources is a pretty big deal. We'll turn to the water_quality table to find records where the subjective_quality_score is within a certain range and the visit_count is above a certain threshold. This should help us spot the water sources that are frequently visited and have a decent quality score.

#### 5. Investigate any pollution issues: 
We can't overlook the pollution status of our water sources. Let's find those water sources where the pollution_tests result came back as 'dirty' or 'biologically contaminated'. This will help us flag the areas that need immediate attention.

### Key insights:
- Not all visits were created equal.
- Some lucky individuals experienced short queue times, while others faced long waits. These disparities in efficiency shed light on the need for improvements in water collection systems, ensuring that everyone has equal access to this vital resource.
- Water sources that were labelled as "Clean" were not always what they seemed. Deep within the data, I discovered instances of biological contamination lurking in these supposedly pristine sources. It was a shocking revelation, exposing errors in the classification of water sources and raising concerns about the accuracy of the data.
- meticulously crafted a step-by-step approach to rectify the errors, ensuring that each contaminated source was accurately labeled. By removing the misleading "Clean" label, I aimed to provide a more accurate representation of water quality, empowering individuals to make informed choices about their water sources.
- I understood the importance of thorough testing and verification. I painstakingly analyzed the data, running extensive checks to ensure the accuracy of my findings.

# Part 2: Clustering Data to Unveil Maji Ndogo's Water Crisis

In this next step, we will cluster our data, stepping back from the individual figures to gain a panoramic understanding. This bird's eye view will allow us to unearth broader narratives and hidden correlations concealed within our rich dataset. Next, we must pay heed to the different forms of data in our possession. They are not mere numbers or dates; they are stories waiting to be deciphered. Their unique structure, though challenging, brims with valuable insights. As we process these, we unlock deeper layers of understanding.

We conduct a comprehensive survey to gather data on water sources, queue times, and infrastructure conditions. The purpose of this data-driven project is to shed light on the key insights, trends, and findings from the survey, exploring their significance and potential real-world implications for the community of Maji Ndogo.

#### Overview:
1. Cleaning our data:
Updating our employee data

2. Honouring the workers:
Finding our best

3. Analysing Locations:
Understanding where the water sources are

4. Diving into the sources:
Seeing the scope of the problem

5. Start of a solution:
Thinking about how we can repair

6. Analysing queues:
Uncovering when citizens collect water

7. Reporting insights:
Assembling our sights into a story

### Key insights
1. Most water sources are rural.
2. 43% of our people are using shared taps. 2000 people often share one tap.
3. 31% of our population has water infrastructure in their homes, but within that group, 45% face non-functional systems due to issues with pipes,
pumps, and reservoirs.
4. 18% of our people are using wells of which, but within that, only 28% are clean.
5. Our citizens often face long wait times for water, averaging more than 120 minutes.
6. In terms of queues:
   - Queues are very long on Saturdays.
   - Queues are longer in the mornings and evenings.
   - Wednesdays and Sundays have the shortest queues.

![graph](https://github.com/NelisiweBezana/SQL/assets/140618126/48375587-2c30-4b88-94fd-144e5f9bb3fe)


# Part 3: Weaving the Data Threads of Maji Ndogo's Narrative
In this stage, we will be integrating the auditor's report into the database, which will add valuable insights and recommendations for further improvement. This integration will enhance the overall functionality and effectiveness of the database.

We embarked on a data-driven investigation to uncover any signs of corruption within our organization. The findings that emerged from this analysis are both eye-opening and concerning. By analyzing various sources of information, we can identify key insights and patterns that shed light on potential corrupt practices.

Overview:
1. Generating an ERD:
Understanding the database structure

2. Integrating the report:
Adding the auditor report to our database

3. Linking records:
Joining employee data to the report

4. Gathering evidence:
Building a complex query seeking truth

### Key Insights:
- Unusual Mistakes: Through meticulous analysis, we discovered that certain employees consistently made a significantly higher number of mistakes compared to their peers. This raised suspicions of possible corruption, as these individuals seemed to be involved in activities that deviated from standard procedures.

- Alarming Statements: Further investigation revealed that these same employees were associated with records containing incriminating statements. These statements hinted at irregularities and unethical behaviour, with mentions of bribery and questionable financial transactions. The correlation between the employees' suspicious activities and these statements intensified our concerns.

- Real-World Implications: The implications of these findings go beyond our organization. Corruption, in any form, has detrimental effects on society, eroding trust and hindering progress. By addressing and combating corruption within our own ranks, we are taking a stand against this pervasive issue and contributing to a better future for all.

# Part 4: Charting the Course for Maji Ndogo's Water Future
As we step into this next phase, you will be shaping our raw data into meaningful views- providing essential information to decision-makers. This will enable us to discern the materials we need, plan our budgets, and identify the areas requiring immediate attention. We're not just analysing data; we're making it speak in a language that everyone involved in this mission can understand and act upon. Lastly, we'll be creating job lists for our engineers. Their expertise will be invaluable in tackling the challenges we face, but they can only do their job effectively when they have clear, data-driven directions.

### Key Insights: 
Based on the data analysis, we have discovered the following insights:
1. Water Sources in Maji Ndogo: Most water sources in Maji Ndogo are located in rural areas.
2. Shared Taps: Approximately 43% of the population relies on shared taps, with an average of 2000 people sharing one tap.
3. Water Infrastructure in Homes: Around 31% of the population has water infrastructure in their homes. However, within this group:
   - 45% face non-functional systems due to issues with pipes, pumps, and reservoirs.
   - Broken infrastructure is observed in towns like Amina, the rural parts of Amanzi, and some towns across Akatsi and Hawassa.
4. Wells: About 18% of the population uses wells. However, only 28% of these wells are clean. This issue is prevalent in Hawassa, Kilimani, and Akatsi.

5. Wait Times for Water: Citizens often face long wait times for water, with an average wait time of more than 120 minutes. We observed the following patterns:
   - Long queues are experienced on Saturdays.
   - Morning and evening periods have longer queues.
   - Wednesdays and Sundays have shorter queues.
  
## Conclusion
In Maji Ndogo, the journey towards sustainable water access begins with acknowledging the existing disparities and taking targeted actions to address them. By focusing on repairing broken infrastructure, installing filters in contaminated wells, expanding shared tap systems, and drilling new wells near rivers, we can pave the way for a future where every individual has the right to clean and accessible water.
