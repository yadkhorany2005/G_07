## G_07 (Assigment 3)

## Role 1 (Requirements Elicitation Lead)
Role prepared by : Yad Sabah

Project overview
The mental health website aims to help people better understand their thier mental health by providing them with reliable information and tests on mental health disorders such as (depression, autism, bipolar, etc.

Elicitation techniques
To get all the necessary information needed for the website, three elicitation techniques were used.
1. Conducting a survey to get the opinion of the users of this app.
2. Interviews with stakeholders were done too by team members and experts on the subject.
3. Team brainstorming session was conducted to refine the ideas of users from the survey and interviews from stakeholders.

SURVEY

Aa survey was conducted to get the opinion of users to see their preferences on topics such as expectation preferences and functions.
The survey was done on a (42) people which included students graduates and young adults etc., most wanted short form so it's easier to understand, majority agreed upon prioritizing safety and privacy some people wanted external recourses available like hotlines or making accommodation with facilities and staff that can help such as doctors and specialists in their fields.

INERVIEW

An interview was conducted between two members of the group, one of which is a web developer, one general user, and one expert in the field providing helpful information regarding our website.

General user: shared his opinion on how the website should be safe, secure and easy to use, in addition it should include tips, maybe even adding some emergency contacts or resources available in a time of need.

Web developer: talked about simple and minimalist design that could be soothing to users will also being fast and secure, in addition to features that can help accessibility.

Expert: provided information on the content of the website, such as mental health issues, and some symptoms and how and where to look for them. The expert also emphasized using real medical information.

In conclusion, all the interviewees agreed that the website should be safe and secure and that it's reliable and easy to use. It gives accurate medical advice on the tests and informative parts as well.


## Role 2 (Requirements Classification Specialist)
Role prepared by: Nancy Louis

Introduction:
This document describes the functional and nonfunctional requirements for the Mental Disorder Website. This system is designed to help users understand mental health conditions, complete self-assessments and receive feedback in multiple languages (English, Arabic and Kurdish).

## Functional Requirements

| **ID** | **Functional Requirement**                           | **Description**                                                    |
|:-------|:---------------------------------------------------- |:-------------------------------------------------------------------|
| FR-01  | Allow users to select disorder category              | Enable users to choose which disorder they want to have a test on  |
| FR-02  | Display list of questions for each disorder          | Provides a set of questions for the user to answer.                |
| FR-03  | Collect and store user responses                     | Saves user responses temporarily and securely to calculate results |
| FR-04  | Calculate the result score based on the user's answer| Analyzes user answers to determine the seriousness of symptoms.    |
| FR-05  | Display disclaimer before starting the test          | Ensures users understand the test is not a medical diagnosis.      |



## Non-Functional Requirements

|**ID**  |  **Non-Functional Requirement**                    |**Description**                                                                  |
|:--- ---|:-------------------------------------------------- |:--------------------------------------------------------------------------------|
| NFR-01 | Easy to use and navigate.                          | User-friendly for all age groups.                                               |
| NFR-02 | Reliable and verified information.                 | Content is checked by professionals or based on research.                       |
| NFR-03 | Makes sure data is secured for the user’s privacy. | Protects user data from unauthorized access.                                    |
| NFR-04 | Accessible in 3 languages                          | Checks how serious the symptoms are.                                            |
| NFR-05 | Fast response time less than a second.             | Results and pages load without delay.                                           |
| NFR-06 | Clear and simple design                            | Makes sure that the system is easy to understand and use.                       |
| NFR-07 | Cross browser                                      | Supports Chrome, Firefox and mobile browsers.                                   |
| NFR-08 | Supports multiple languages.                       | Allows the user to choose their preferred language (English, Arabic or Kurdish) |
| NFR-09 | Provide separate pages for each disorder.          | Organizes website content.                                                      |

## User Requirements

| ID |  | User Requirement                            |   Description                                             |
|-------|---------------------------------------------|-----------------------------------------------------------|
| UR-01 | Learn about mental disorders                | Website provides educational reliable content.            |
| UR-02 | Check symptoms easily.                      | Short, and simple questionnaire format.                   |
| UR-03 | Get instant feedback                        | Results show instantly after the user completes the test. |
| UR-04 | View results in own language                | English Arabic or Kurdish.                                |
| UR-05 | Ensures privacy and safety                  | No personal information will be collected.                |
| UR-06 | Understand site purpose.                    | Disclaimer clarifies the website’s purpose.               |
| UR-07 | Users have to login inorder to do the test. | Email and password are required in order to start the test|

## System Requirements

| ID | System Requirement  |                                                       Description                                              |
|----|-------------------------------------------|------------------------------------------------------------------------------------------|
| SR-01 | Calculate and display results.         | Automates results and feedback display.                                                  |
| SR-02 | Maintain secure and reliable database. | Stores users’ responses temporarily and safely.                                          |
| SR-03 | Uses HTML, CSS and JavaScript.         | Developments technologies.                                                               |
| SR-04 | Provide page for each disorder type.   | Organizes content.                                                                       |
| SR-05 | Ensures accuracy and validation.       | Based on verified medical sources or doctor input makes sure all information is correct. |



## Role 4 (Structured Specification Developer)
Role prepared by : Shatu Bakhtiar

## Use Case: Disorder Assessment

| Field                   | Description                                                                                         
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Description             |  It gives the user a set of questions related to a chosen disorder.                                                                  |
| Such disorders include autism, anxiety, or depression. The system calculates a total score from the responses. Based on those responses, it also determines the| level of symptom severity.                                                                                                                                       |
| Inputs                  | The type of disorder the user has chosen and their responses to each question.                                                       |
| Source                  | Users enter their input by using the interface on the website.                                                                       |
| Outputs                 | A total score and a severity label (e.g., “Mild Depression”, “Severe Anxiety”).                                                      |
| Destination             | shown on the result page to the user.                                                                                                |
| Action                  | The system pulls up the questions related to whatever disorder gets picked It assigns a number for every answer the user enters. Then| the system sums up these numbers and compares them with set score levels to determine the severity. Immediately afterwards, it shows the results with some feedback.                                                                                                                                                        |
| Requires                | complete questionnaire answers and a valid disorder selection. Precondition: The user has selected a disorder and accessed its evaluation page.                                                                                                                                                 |
| Precondition            | The user has selected a disorder and accessed its evaluation page.                                                                   |
| Postcondition           | A message with advice and a severity result are shown.                                                                               |
| Side Effects            | None                                                                                                                                 |















## Role 5 (Requirements Prioritization Analyst)
Role prepared by : Shanel Sherzad
The prioritization of requirements is a crucial aspect of this project, it allows us to efficiently allocate our resources and time to the most important features first and slowly integrate extra features as the project progresses. Furthermore, since we chose the agile development method. It gives us flexibility and room for future evolution and newer feature additions.



We will divide the requirements into 3 categories; Mandatory(M), Nice to Have(N), Superfluous(S)



M requirements:
-The system should provide a consistent, reliable, accurate means of helping people get a better understanding of their mental conditions.
- The system’s questionnaire system should ask relevant questions created by experienced individuals who specialize in the field.
- The system should provide questionnaires, information, basic support for the most common type of mental disorders and issues such as autism, depression, BPD among other common conditions.
-The system should provide proper guidance to user according to their mental states.
-The website needs to have a safe method of access to protect users and their information.


N requirements:
-The system provides means of connecting with mental clinics and psychiatrists online.
- The system’s questionnaires can be used in tandem with a psychiatrist’s knowledge and an online session to give a final and concrete diagnosis.
- The system can provide tailored support for every different user.
-The system can have a nice, welcoming and good-looking user interface to make users feel at ease and comfortable.
-The system is able to use its questionnaires periodically to track progress and changes in users.
-The system features support for less common conditions.
-The system has a database which allows users to create accounts to store their information, history and track records.




S requirements:
-The system can use the user’s location and guide them to mental clinics in close proximity.
-The system allows users to have online sessions with psychiatrist in the website itself, where it has features that replicate a therapy session.
-The system has an optional AI model able to work as a supportive friend to make users feel comfortable and calm.





## Role 6 (Requirements Prioritization Analyst)
Role prepared by : Meron Thamer
There are two main concerns that we have found with the requirements

First of all is the accuracy of the assessments, most of the human traits can be linked to a certain mental disorder when they don’t even have the disorder themselves so by taking the test user might show some subtle signs of a disorder when they don’t actually have it making the test misleading and may cause discomfort for the user and may lead them to go down a rabbit hole that the website dug for them.

Secondly, Security and trust, the user data should be highly secured to prevent it from leaking, and strictly monitored by professionals or the web designers themselves. this process can boost the website’s popularity and gain the trust of users making it attract the attention of potential patients  and helping the vast majority of the human popularity giving the reassurance that they don’t have anything wrong with their mental status and if they do we will be guiding them towards the right path or at least help them begin their journey.

For our validation methods we will be using test cases, test case can help us set a  benchmark for the rest of the users  in order to see if the test actually works. Taking some samples and getting sample set of data to see if the test correlates with the results.
We'll get a person that has been diagnosed with a particular disorder that we have created a test for, then we will take their consent to take the test and see if they get our desired output, that will bring us confirmation that our test is successful therefore we can release for the public to benefit from it










