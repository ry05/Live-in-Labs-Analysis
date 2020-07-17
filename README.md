# Live-in-Labs Analysis

Data Analysis undertaken during the Live in Labs program at ASE-B.

**Link to Medium Blog :** <http://bit.ly/village-data-analysis>

## What is Live in Labs

Live-in-Labs® is a multidisciplinary experiential learning program that breaks classroom and lab barriers by applying learned theory in real-world settings. This credit-based academic program draws on principles of lean research for the development and deployment of sustainable solutions for current challenges faced by rural communities in India. By directly living in rural communities (labs) and co-designing solutions to development challenges, program participants gain first-hand knowledge and know-how of identifying and assessing community needs and subsequently developing and implementing viable solutions through various participatory methods.

**Source:** <https://www.amrita.edu/international/live-in-labs>

## Acknowledgement

Being a part of Live in Labs Amrita (LiLA) was an amazing experience for me. It was wonderful working with the Live in Labs Amrita team.

Also, none of this would have been possible without the equal efforts of my team members Nithika Suresh, Bhanuvardhan CH, Venkata Ramana and Lalith Shubhankar. The role of Mr Vignesh V as our team mentor was also extremely important and resourceful in helping us survey the village conditions effectively.

![The Purpose of LiLA](https://github.com/ry05/Live-in-Labs-Analysis/blob/master/Purpose%20of%20LiLA.JPG)

**Fig 1.** Infographic depicting the purpose of LiLA

## Some Preliminary Information about the village we visited

### Name of the Village

**Official Name :** New Thariyal

**Also called as :** Dodeneer

### Location

Northern Punjab, India

### About the People

-   **Number of People in the village:** 300+
-   **Number of Houses:** 58
-   **Major Occupation:** Unskilled, seasonal labour

### Resource Map of the Village

![Resource Map of Dodeneer](https://github.com/ry05/Live-in-Labs-Analysis/blob/master/Resource%20Map.jpeg)

**Fig 2.** A resource map helps mark the key resources available in a village and is also the basis for dividing the village into sectors at a later stage.

**Credits for the drawing:** Venkata Ramana

## State of water in the village (Before our study)

-   According to several villagers, the dearth of water is a problem that cripples their daily routines.
-   The main people who are affected by the above problem statement include the labourers as they are often delayed for work if the water is late or does not arrive as they are the ones who go to nearby villages to collect water.
-   The women of the house are also affected as the household chores are at a standstill when water is not there.
-   Teenage girls also find the water issues to be extremely uncomfortable, especially during the times of their menstrual cycles.
-   The village has a debt of over 1,50,000 INR on the borewell that belongs to the Government of Punjab, India. All current usage of the borewell is unauthorized and can be shut down at any time.
-   Some houses use underground motors to pump up water from the Thariyal source which is not legal according to the rules set by the Govt. of Punjab, India.

## The Water Consumption Survey at Dodeneer

Information about the **Water Consumption Survey** that was conducted at Dodeneer by Team Analytica

### Why did we conduct this survey

In the first 4 days of our brief 7-day visit to the village, we spent our time observing the lifestyle of the villagers. We used strategies such as Participatory Rural Appraisal(PRA) to identify the most prevalent issues in the village. Through the use of PRA related tools such as venn diagrams, resource maps and problem trees, we
were able to draw a detailed picture of the needs of the village and **Water was shaping up as an area of concern**.<br>

Furthermore, through the interviews of the villagers and their personas, we realized that water was a significant area of concern and that the villagers had a lot to complain about when the thematic area in consideration was water.<br>

Next, **we needed to come up with a means to corroborate our finds through the PRA framework and the village interviews. Also, it was important for us to identify the main causes of the water shortage(if there was any)**. In order to achieve these two purposes, the data scientist in me decided to conduct a survey where we would collect data from each household in the village and use it to validate and quantify the amount of water-related stress in the village.

### The Survey Methodology

#### Main Research Question

Are the people of Dodeneer suffering from acute water shortage?

#### How was the survey conducted

-   The survey was conducted as in-person interviews where a pre-prepared questionnaire was used as a reference
-   The data was first collected by the team on paper and then it was entered into a spreadsheet

#### The Questionnaire

The following questions were asked to each household as a part of our survey :

-   What is the medium of water storage in the house?(Tank or Sump or buckets or cans)
-   What is a rough estimate of the capacity of the water used by the house per day?
-   Does the house have an underground motor(to pump up water)?
-   Does the household receive water from the Thariyal water supply, from the in-village borewell source or both?
-   If a household receives water from both sources, which source provides a larger amount of water?
-   How many members live in the house?

**Language of Interview:** These questions were asked in the regional languages(Punjabi and Hindi) to the people.<br>
**Extra Help:** The team was also helped by a local guide to help us with the interactions with the villagers

#### Key Considerations that were taken care of while creating the questionnaire

-   **Relevance** - Are the questions relevant w.r.t our goals of conducting the survey?
-   **Structure** - Are the questions structured in a way so that they can be masked as a natural conversation? This was very important to consider as a normal conversation would cause people to open up more frankly than a definite set of questions being shot at them.
-   **Length** - We abstained from making a lengthy questionnaire so that we would not be consuming too much time of a person.
-   **Comfort** - In a backward Indian village, not every question will be taken up in the right spirit. So, we decided to refrain from asking questions such as family income as not every household will be willing to give an accurate answer.

## Performing Data Analysis

How did I analyze the survey data?

### Analysis Workflow

![LiLA Survey Workflow](https://github.com/ry05/Live-in-Labs-Analysis/blob/master/LiLA%20Survey%20Workflow.png)

**Fig 3.** LiLA Survey Analysis Workflow

### Tools Used

-   MS Excel
-   Jupyter Notebook(Python)
