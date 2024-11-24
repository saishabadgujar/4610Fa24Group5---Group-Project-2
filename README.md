# 4610Fa24Group5---Group-Project-2

<h1>Team 5 Mist 4610 Group Project 2</h1>

<h2>Team Name:</h2>
<p>4610Fa24Group5</p>

<h2>Team Members:</h2>
<ul>
  <li><a href="https://github.com/maadhavan23">Maadhavan Muthuselvan</a></li>
  <li><a href="https://github.com/kendallbabbs">Kendall Babbs</a></li>
  <li><a href="https://github.com/LoskiJin">Loski Jin</a></li>
  <li><a href="https://github.com/saishabadgujar">Saisha Badgujar</a></li>
  <li><a href="https://github.com/loganmatson">Logan Matson</a></li>
</ul>

<h2>Data Set Description:</h2>
<p>The dataset contains detailed records of traffic crashes within the city limits of Chicago under the jurisdiction of the Chicago Police Department(CPD). This dataset covers crash data from select police districts starting in 2015, expanded citywide through 2017 and on. This is a large dataset, including both minor and major crashes recorded by CPD. There are numerous columns within the dataset, but we selected a few key columns to focus on. This includes crash type (categorical), primary contributory cause (categorical), injuries total (numerical), report type (categorical), weather (categorical), crash hour (numerical).</p>


<h2>Our 2 Questions:</h2>

<h3>1. Which specific type of crashes provokes the most injuries, both in total and on a per crash basis?</h3>
<p>This question is important in identifying what kinds of crashes have a high possibility of injury and more specifically which crashes have the most injuries, aka crashes that are the most dangerous. Knowing these crash types can help policy makers and authorities to make informed decisions on traffic safety and focus on mitigating these specific crashes. Additionally, identifying these collisions can enable educational campaigns and technological innovations aimed at reducing the particular risks associated with these crashes. Overall, this question highlights areas where action is needed, and encourages the city of Chicago to take the preventative measures against crashes.</p>


<h3>2. What external factors contribute to a higher injury rating for pedestrian injuries?</h3>
<p>This question is helpful in explaining why pedestrian crashes are more injury-prone, shedding light on contributing factors such as lack of driver wellness or pedestrian visibility. Analyzing external factors (e.g. weather conditions, lighting, vehicle speed, or road design) can help us understand what preventative measures to take, like improving the safety of crosswalks, more speed regulation, and even better monitoring the state of drivers. This understanding can lead to awareness campaigns targeting both drivers and pedestrians, promoting behaviors that reduce injury risks and improve the safety of driving. All in all, visualizing this question can contribute to safer roads, informed policymaking, and ultimately save lives by reducing the severity of traffic incidents.</p>


<h2>Manipulations Applied:</h2>
<p>Instead of analyzing the overall number of injuries, which is biased due to more frequent crash types such as Rear Endings versus Pedestrian Crashes, we calculated the average number of injuries per crash for each crash type. This was achieved by dividing the total number of injuries (SUM [Injuries Total]) by the total number of crashes ([Crash Count]) for each category. This manipulation allowed us to normalize the data, ensuring that crash types with higher frequencies did not disproportionately affect our analysis. As a result, we can accurately see which crash types have the highest impact on injuries, regardless of how often they occur.</p>


<h3>Question #1</h3>


<img width="465" alt="Screenshot 2024-11-20 at 12 35 49 PM" src="https://github.com/user-attachments/assets/44175179-28a8-4d6b-8d34-a4c908380f47">


<h3>Question #2</h3>
<h4>All Crashes</h4>

<img width="746" alt="Screenshot 2024-11-20 at 12 35 59 PM" src="https://github.com/user-attachments/assets/1387b291-704e-44d7-b9b2-d94cecb9a430">

<h4>Pedestrian Crashes</h4>

<img width="738" alt="Screenshot 2024-11-20 at 12 33 46 PM" src="https://github.com/user-attachments/assets/d88e5404-82ca-4fd0-91a1-b39024da9041">

<h2>Analysis & Results:</h2>
<p>The analysis of crash data in the City of Chicago reveals distinct patterns in total injuries and injuries per crash across various crash types, providing important insights into traffic safety. While certain crash types, such as rear-end collisions, contribute to a significant portion of total injuries due to their high frequency, other crash types, including pedestrian-involved crashes, exhibit disproportionately higher injuries per crash. This disparity highlights the severity and danger associated with specific types of accidents. By normalizing the data to account for crash frequency, it becomes evident that crashes involving pedestrians or head-on collisions result in more severe outcomes, even if they occur less frequently. These findings underscore the importance of implementing targeted safety measures, such as improving pedestrian crosswalk designs, enforcing stricter speed regulations, and enhancing driver education. The results call for a deeper understanding of contributing factors to develop more effective interventions and prevent future harm.</p>


<h2>Citations:</h2>



<h2>Tableau Packaged Workbook:</h2>






