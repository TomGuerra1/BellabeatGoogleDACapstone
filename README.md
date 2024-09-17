# Bellabeat Case Study
#### By: Tomas Guerra

#### Date: September 11, 2024

## Scenario
#### Since its foundation in 2013, Bellabeat has been able to grow rapidly and steadily within its industry, being a high-tech company that focuses on the manufacturing of healt-focused smart products for women. Through their growth, they've been able to create 5 products: the Bellabeat app, Leaf, Time, Spring, and the Bellabeat membership. Being a small company with much potential for growth within their industry, this team has been called upon to assist on the analysis of data from the products, further understand how their clientele is utilizing their products, and utilizing the discovery as accurate and approprate insights to enhance the marketing strategy for Bellabeat.

## Business Task
#### Business Task: To help drive the marketing strategy of Bellabeat into more data-driven decisions, allowing for the company to hold a more global position within its industry.
#### Key Stakeholders: Urška Sršen, Sando Mur, the Bellabeat Marketing Analytics team.

## Dataset
#### The data set was retrieved from Kaggle: https://www.kaggle.com/datasets/arashnic/fitbit?resource=download

#### It's composed of 18 CSV files, gathering data of over 30 selected users of the FitBit brand, and its associated products.

#### The data set (somehow) follows ROCCC standards, which means it is Reliable, Original, Comprehensive, Current, and Cited data.
#### However, the dataset only possesses data of 30 users, which is a limited sample size. As well, some data of certain users has been manually entered, instead of measured by a device connected via WiFi.
#### Also, the data was collected within the first semester from 2016, which doesn't reflect the user's current lifestyle.

## Finds and insights
### Overview of Data

<img width="785" alt="Screenshot 2024-09-16 at 12 41 37 PM" src="https://github.com/user-attachments/assets/356b197c-ce8d-41ff-96cc-9abc03e6463f">

#### After cleaning and overviewing the data, we could make some immediate assumptions, as to the fact that we'll be working with some incomplete data. Of the 35 selected users that submitted their personal data, only 34 of them had a total step count for the period of time in consideraton, 23 had measurements of time taken during their sleep, and only 8 had weight measurements, from which 5 were manually entered, not recorded.
####

<img width="420" alt="Screenshot 2024-09-16 at 12 52 37 PM" src="https://github.com/user-attachments/assets/928507f9-613a-42e8-9b47-75a419b5321e">

#### In order to better grasp how the users are utilizing their time, we focus on the intensity levels of their daily activities. On average, users are spending almost 85% of their time on sedentary activities, with only a little over 2% on fairly or very intense activities. It is important to note that, almost 15% of their day is spent on lightly intense activities, which could be considered a short brisk walk, or warm-up activities. 
####

<img width="709" alt="Screenshot 2024-09-16 at 3 17 24 PM" src="https://github.com/user-attachments/assets/a38f9163-7769-42e1-94b0-3c8efe2d70cc">

#### On a daily basis, the time spent sedentary is reflected as 995.3 minutes, which translates to a total of a little over 16 hours of the day, with just a little under 30 minutes of time dedicated to fairly or very intense activities daily.

<img width="498" alt="Screenshot 2024-09-16 at 3 12 55 PM" src="https://github.com/user-attachments/assets/fb9a8a84-31c1-4047-85ab-3a812ff3addd">

#### Across the week, users are also utilizing their time differently. On average, users tend to take more steps on Wednesdays, followed by Saturdays. However, Tuesdays and Sundays are the days with the least step count from our users. 

<img width="817" alt="Screenshot 2024-09-16 at 8 46 34 PM" src="https://github.com/user-attachments/assets/c78fbecf-362b-48fc-aca5-615a3d543241">

#### More specifically, after drilling down the step count a little more, we're able make more specific assumptions. On a daily basis, users tend to have the highest count of steps at noon. However, it is also important to note how this same users have a continous build-up of step-count during the late afternoon into the early evening, from the hours of 4 pm in the afternoon, until 7pm in the early evening. Then, a drastic drop occurs at 8pm into the evening.

## Recommendations
#### 1. A greater volume of data is essential in order to formulate more concrete, precise, and up-to-date assumptions. The data overview highlights the need for additional information to improve accuracy and reliability when drawing conclusions, ensuring that insights are based on a comprehensive and robust dataset.
#### 2. It's recommended to develop targeted campaigns that promote short bursts of high-intensity fitness activities throughout the weekdays. Analysis reveals that three out of the four days with the lowest average steps per day are Tuesdays, Thursdays, and Fridays, suggesting that these days present an opportunity to encourage increased activity through focused fitness initiatives.
#### 3. To foster greater user engagement, create incentives within the Bellabeat app that could motivate users to engage in more moderate to high-intensity physical activities. Gamification elements, such as earning points or collecting medals after reaching specific activity thresholds could significantly encourage users to stay active.
#### 4. Leverage the current product offerings to effectively communicate with customers about their activity intensity levels. For example, the app could alert users after prolonged periods of inactivity or extended durations without adequate sleep, encouraging them to take action and improve their wellness by providing timely and personalized feedback.

## Dashboard
#### [Tableau Storyboard](https://public.tableau.com/views/BellaBeatCaseStudy_17265362458020/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
