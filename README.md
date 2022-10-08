# Prediction-Of-Heart-Failure-Disease
## Problem Statement
The problem of heart disease we can be manage effectively with a combination of changes on our 
lifestyle, medicine. With the right treatment, the symptoms of heart disease can be reduced and the 
functioning of the heart improved. The predicted results can be used to prevent and thus reduce cost 
for surgical treatment and other expensive. The overall objective of my work will be to predict 
accurately with few tests and attributes the presence of heart disease. Attributes considered form the 
primary basis for tests and give accurate results more or less. Many more input attributes can be 
taken but our goal is to predict with few attributes and faster efficiency the risk of having heart 
disease. Decisions are often in the data set.

## Purpose of Project
The purpose of we are doing the project prediction of heart failure diseases because in accordance 
with the World Health Organization, India accounts for one-fifth of these deaths worldwide 
especially in younger population. The results of Global Burden of Disease study state age standardized cardiovascular disease (CVD) death rate of 272 per 100000 populations in India which 
is much higher than that of global average of 235. CVDs strike Indians a decade earlier than the 
western population. For us Indians, particular causes of concern in CVD are early age of onset, rapid 
progression and high mortality rate. Within India, the rates of CVD vary markedly with highest in 
states of Kerala, Punjab and Tamil Nadu.
In this project, the predictions on heart failure disease has been done and finally, the accuracy of the 
algorithm has been determined. Using this algorithms, we find the which variable is effect on heart 
disease

## Aim: 
The main Aim of the project is to study or predict whether patients have heart failure disease or not 
by given a number of variable from patients, and check the people have awareness about heart failure 
diseases using google form.
## Objective:
### Primary objectives
Predict whether patients have heart failure disease or not by given a number of variable from 
patients.
### secondary objectives:
1. To study and analyse impact of age and gender on heart failure disease.
2. Compare the which machine learning algorithm predict more accurate results.
3. To study and analyse which variable most impact on heart failure disease

## INTRODUCTION
The heart is one of the main organ of the human body. It pumps blood through the blood 
vessels of the circulatory system. The circulatory system is extremely important because it 
transports blood, oxygen and other materials to the different organs of the body. Heart plays 
the most crucial role in circulatory system. If the heart does not function properly then it will 
lead to serious health conditions including death.
Also the main cause of heart stroke is due to blockage in arteries. It has many other 
names such as cardiovascular disease and arterial hypertension. Approximately, there are 
almost 26 million people around the world affecting with heart diseases. The worry point is,
this ratio is expected to increase rapidly in coming years, if precautions are not taken 
efficiently. Apart from making life style healthy and diet control, the right time diagnosing 
and comprehensive analysis are other essential factors, which can ultimately save the lives.
Most of the time patients goes for several tests, which can overburden them with extra 
physical activities, time, and for sure additional financial charges. As previous studies 
suggested the common reasons behind heart disease can be unhealthy food, tobacco, 
excessive sugar, overweight or extra body fat. Whereas the common symptoms can be pain in 
arms and chest. Noticeably, these reasons are independent from each other; proper analysis 
on this kind of dataset can improve the process of diagnosing and can assist the heart 
surgeons as well. Different researches used number of techniques to improve the HF 
diagnosis process such as Extreme Learning Machine, heart disease classification, and 
machine learning classifiers.
Age, sex, smoking, family history, cholesterol, poor diet, high blood pressure, obesity,
physical inactivity, and alcohol intake are considered to be risk factors for heart disease, and 
hereditary risk factors such as high blood pressure and diabetes also lead to heart disease. 
Some risk factors are controllable. Apart from the above factors, lifestyle habits such as 
eating habits, physical inactivity, and obesity are also considered to be major risk factors.
There are different types of heart diseases such as coronary heart disease, angina pectoris, 
congestive heart failure, cardiomyopathy, congenital heart disease, arrhythmias, and 
myocarditis. It is difficult to manually determine the odds of getting heart disease based on 
risk factors. 
Therefore, this project has taken a small step towards saving the lives of HF patients and 
describes a way to improve the performance of diagnosing the patients on the bases of their 
medical history.
However, machine learning techniques are useful to predict the output from existing 
data. Hence, this project applies one such machine learning technique called classification for 
predicting heart disease risk from the risk factors. It also tries to improve the accuracy of 
predicting heart disease risk using a strategy termed ensemble.

## Sample Unit
Individuals who are heart disease failure people were chosen as samples.
## Sample Size:
Total Sample size was 299 people.
Total number of variable is 13.

## Data Information

#### Age: 
Age of the patient.

#### Anemia: 

Anemia is the number of healthy red blood cells in your body is to low. Red blood cells carry to the level of oxygen to all of the body’s tissue, so a low red blood cell count indicates that the amount of oxygen in your blood is lower than it should be

Creatinine phosphokinase: The level of the creatine phosphokinase in the blood in mcg/L. When the total CPK level is very high, it most often means there has been injury or stress to muscle tissue, the heart, or the brain. Muscle tissue injury is most likely. When a muscle is damaged, CPK leaks into the bloodstream. Finding which specific form of CPK is high helps determine which tissue has been damaged. (Range : Male = 21 to 232 IU/L , Female = 21 to 215 IU/L )

#### Diabetes: 

		Diabetes is the disease that occurs when your blood glucose, also called blood sugar, is too high. Glucose of blood is a main source of energy and its come from the eating of food.

#### Ejection fraction:

Ejection fraction is a measurement of how much blood the left ventricle pumps out with each contraction. A normal ejection fraction is more than 55%. This means that 55% of the total blood in the left ventricle is pumped out with each heartbeat. Heart failure with reduced ejection fraction happens when the muscle of the left ventricle is not pumping as well as normal. The ejection fraction is 40% or less.

(Ranges from 55% to 70%. )

High blood pressure: High blood pressure, or hypertension, occurs when your blood pressure increases to unhealthy level. Your blood pressure measurement considers how much blood is passing through your blood vessels and the amount of resistance the blood meets while the heart is pumping.

#### Platelets:

Platelet count of blood in kilo platelets/mL. Increased platelet activation and aggregation are involved in the pathogenesis of elevated blood pressure, which is also associated with hypertensive risk factors.

#### Serum creatinine:

	 The level of serum creatinine in the blood in mg/dL. Background and Purpose Elevated serum creatinine has been associated with increased mortality in hypertensive persons, the elderly, and patients with myocardial infarction or stroke in whom cardiovascular disease is the major cause of death.

(Range : Male = 0.74 to 1.35 mg/dL (65.4 to 119.3 micromoles/L)

Female = 0.59 to 1.04 mg/dL (52.2 to 91.9 micromoles/L) )


#### Serum sodium:

Sodium helps keep a normal balance of fluid in your body. Patients with heart failure need to follow a low-sodium diet because it helps control symptoms of heart failure and prevent other heart problems. Excessive sodium intake is linked to water retention, and it is also a risk factor for high blood pressure. Both excessive sodium intake and high blood pressure are major risk factors for developing heart failure, and for causing complications in those with existing heart failure. (Range : 135-147 mmol/L )

#### Gender:
 
The sex of the patient .

#### Smoking:

when you breathe in cigarette smoke, the blood that is distributed to the rest of the body becomes contaminated with the smoke's chemicals. These chemicals can damage to your heart and blood vessels

#### Time:

It is the time of the patient's follow-up visit for the disease in months

#### Death event:

If the patient deceased during the follow-up period
