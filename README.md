# Heart Disease Data Analysis
## by Rodrigo Tiscareno


Heart Disease is the leading cause of death in the world. According to the CDC, heart disease is responsible for about 1 in 4 deaths in the United States and over $1 billion in daily government and organization expenditure. <sup>1, 2</sup> Despite advocacy for heart health and billions of dollars spent each year in heart disease awareness campaigns, diagnoses are expected to rise by a staggering 46% by 2046. <sup>2</sup>

The good news? Almost 80% of premature heart disease and stroke can be prevented through healthy behaviours.<sup>2</sup>  Personal health habits such as regular exercise, ample sleep time, and diet can all work towards preventing health-related diseases. 

Through this data analysis exercise, I want to explore the correlation of a handful of personal health factors towards a patient's heart condition and their body mass index and arrive at conclusions to how individuals' personal choices affect their health. 

My objectives are to:

- Visually explain the characteristics' contribution to heart health
- Create and deploy a classification algorithm to determine heart condition based on the given dataset's factors
- Understand which features hold the most significance when computing a predicted diagnosis.

## Dataset

The dataset I will be working with a Kaggle [dataset](https://link-url-here.org) with over 319, 795 patient records acquired from the CDC Government website. The Kaggle dataset was created by Kamil Pytlak. 

### Feature Description

- HeartDisease: Binary variable of whether a patient has reported a case of heart disease or mydocardial infarction.
- BMI: Body Mass Index of patient.
- Smoking: Binary variable of whether a patient has smoked at least 100 cigarettes throughout their entire life.
- AlcoholDrinking: Binary Variable of whether a male patient is drinking more than 14 drinks per week or a female patient drinking more than 7 drinks per week.
- Stroke: Binary variable as to whether a patient has ever had a stroke.
- PhysicalHealth: How many days a patient has reported feeling unwell physically in the last 30 days.
- MentalHealth: How many days a patient has reported feeling unwell mentally in the last 30 days.
- DiffWalking: Binary variable of whether a patient has faced difficulty walking or climbing stairs.
- Sex: Gender of patient.
- AgeCategory: Categorical variable describing the age of the patient.
- Race: The patient's ethnicity.
- Diabetic: Binary variable of whether a patient is a diabetic.
- PhysicalActivity: Binary variable of whether a patient has reported doing physical activity in the last 30 days.
- GenHealth: Categorical variable describing the general health of a patient.
- SleepTime: How many average hours of sleep the patient receives in a 24-hour period.
- Asthma: Binary variable of whether a patient has been diagnosed with asthma. 
- KidneyDisease: Binary variable of whether a patient has been diagnosed with kidney disease. 
- SkinCancer: Binary variable of whether a patient has been diagnosed with skin cancer. 


## Summary of Findings

Following the objectives outlined in the investigation, we wanted to first find the correlation of BMI with the risk of heart disease. We found that they were positively correlated with each other, that is, the higher a patient's BMI, the higher their risk of heart disease. We moved onto exploring features related to patient information such as age, ethnicity, and gender. While specific ethnicities did not prove to have a pattern regarding heart disease, ethnicities exhibiting low BMI values tended to also have a low risk of heart disease. There were no notable differences in terms of gender, with the sample having an equal number of affected males and females. In terms of patient age, we found that as patients age their risk of heart disease also increases. While their probability isn't directly affected, their physical activity and general health drops affecting BMI, in turn affecting their risk of heart disease. 

General health and physical activity were huge factors in determining heart disease. What we found is that most patients with a low BMI described their health as "very good" or "excellent" which prompted members of these classes to exhibit lower probabilities of heart disease. A patient's perceived general health was an important feature tied to heart disease. The more poor physical or mental health days a patient suffered, the higher their BMI. Perception of health was later to be discovered once again by the general health and physical activity of the patient. 

Sleep time was another impactful feature that we took a look at. We found that the amount of sleep that a patient receives is directly connected to both BMI and heart disease risk. We found that the amount of sleep a patient receives is cyclical and based on their stage of life. Teens, young adults, and seniors generally observed a higher amount of sleep compared to adults. There was a higher variation with a patient's general health rating as we transcended into the adult ages, particuarily due to the sleep time they have recieved. Lastly, we explored a patient's pre-existing conditions and how they correlate with heart disease. We found that previous experiences with stroke in particular increase the chance of future heart disease diagnosis.

Finally, as a highlight to our analysis, we examined the significance of each feature through a random forest classification algorithm. The algorithm affirmed our conclusions on the strong ties of BMI, sleep time, and physical health in regards to heart disease - these features were the most significant as per our algorithm.



## Key Insights for Presentation

The intent for the presentation is to display the significance of sleep-time, physical activity, and a lowered BMI to reduce heart disease. By representing key patterns tying these variables to the risk of heart disease and BMI, the goal is to raise awareness of the fact that heart disease is preventable and possible to minimize the risk of. 

The specific insights we want to touch on are:

- BMI's correlation with the probability of heart disease.
- Sleep time's effect on patient BMI.
- Age Category trend analysis with sleep-time and general health considerations.
- Age Category trend analysis with BMI and physical activity considerations.
- Feature Significance 

Changes will mostly revolve around changes to graph design and visual enhancements. 