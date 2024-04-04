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
