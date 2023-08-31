# Sleep Health Analysis

1. [TL;DR](#tldr)
2. [Dataset Overview](#dataset-overview)
3. [Key Features of the Dataset](#key-features-of-the-dataset)
4. [Dataset Columns](#dataset-columns)

![pexels-andrea-piacquadio-3771115](https://github.com/Hamza-149/sleep-health-analysis/assets/69048367/4a83f9c0-5f07-4451-8216-721489b7b353)

## TL;DR
The dataset we are going to be analysing contains data and several metrics of working-class people who suffer from Sleep Disorders such as 'Sleep Apnea' or 'Insomnia' and people who are healthy and don't have any such disorders. The objective of this analysis is to identify any correlation in their between the data in dataset and the sleep disorders that they suffer from.

![sd_vs_age](https://github.com/Hamza-149/sleep-health-analysis/assets/69048367/7d4143e4-447a-4b7d-b3db-7db9f652012b)
![sd vs other features](https://github.com/Hamza-149/sleep-health-analysis/assets/69048367/416a8f44-e4bc-4daa-bfa3-f17105ac769b)
![sd vs other features_violinplot](https://github.com/Hamza-149/sleep-health-analysis/assets/69048367/026be9ff-2a66-4d13-9949-297deb47e27f)

These are the infernces we have made from the above charts that we plotted:

**Sleep Apnea**
- They do not really have any issues when it comes to the amount of sleep they get hence why their sleep quality is also decent
- They also happen to be the most physically active of the bunch. This doesn't mean that one causes the other but it is just a trend that we notice
- Their stress levels happen to be pretty
- Their BP (systolic and diastolic) is also the highest 

**Insomnia**
- This disorder results in people not getting enough sleep hence why we can see that the sleep duration and the quality of sleep happens to be the lowest for them
- Once again when it comes to the physical activity we cannot infer much but they definitely are lower compared to those suffering from sleep apnea
- Their stress levels happen to be pretty
- Their BP (systolic and diastolic) isn't as high someone who is suffering from sleep apnea but is still higher than someone who doesn;t suffer from these disorders

![stresslvl-qos heatmap](https://github.com/Hamza-149/sleep-health-analysis/assets/69048367/5cd1d4dd-a258-4d48-a91d-fbe827b8ae0d)

It follows a downward trend and we can also see notice that there are quite a few stressed out people who are suffering from these sleep disorders. It could be due to their profession, their personal affairs or even something else but it definitely has been taking a toll on them

## Dataset Overview:
The Sleep Health and Lifestyle [Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset) comprises 400 rows and 13 columns, covering a wide range of variables related to sleep and daily habits. It includes details such as gender, age, occupation, sleep duration, quality of sleep, physical activity level, stress levels, BMI category, blood pressure, heart rate, daily steps, and the presence or absence of sleep disorders.

## Key Features of the Dataset:
- Comprehensive Sleep Metrics: Explore sleep duration, quality, and factors influencing sleep patterns.
- Lifestyle Factors: Analyze physical activity levels, stress levels, and BMI categories.
- Cardiovascular Health: Examine blood pressure and heart rate measurements.
- Sleep Disorder Analysis: Identify the occurrence of sleep disorders such as Insomnia and Sleep Apnea.

## Dataset Columns:
- Person ID: An identifier for each individual.
- Gender: The gender of the person (Male/Female).
- Age: The age of the person in years.
- Occupation: The occupation or profession of the person.
- Sleep Duration (hours): The number of hours the person sleeps per day.
- Quality of Sleep (scale: 1-10): A subjective rating of the quality of sleep, ranging from 1 to 10.
- Physical Activity Level (minutes/day): The number of minutes the person engages in physical activity daily.
- Stress Level (scale: 1-10): A subjective rating of the stress level experienced by the person, ranging from 1 to 10.
- BMI Category: The BMI category of the person (e.g., Underweight, Normal, Overweight).
- Blood Pressure (systolic/diastolic): The blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure.
- Heart Rate (bpm): The resting heart rate of the person in beats per minute.
- Daily Steps: The number of steps the person takes per day.
- Sleep Disorder: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).

## Details about Sleep Disorder Column:

- None: The individual does not exhibit any specific sleep disorder.
- Insomnia: The individual experiences difficulty falling asleep or staying asleep, leading to inadequate or poor-quality sleep.
- Sleep Apnea: The individual suffers from pauses in breathing during sleep, resulting in disrupted sleep patterns and potential health risks.
