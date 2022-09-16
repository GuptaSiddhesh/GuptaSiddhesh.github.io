<h1 align="center"> 
  CMSC320 Final Project 
  Univeristy of Maryland Computer Science Course Grade Predictor 
</h1>
<h2 align="center"> Team: Siddhesh Gupta, Tanmay Prakash, Shanil Kothari </h1>

<p> 
Have you ever wondered what grades you can get in a Computer Science course ? Have you ever thought how much work I need to put into this class to get a particular grade. If not we are sure that you must have thought about this while taking CMSC 351 with the great Cldye Kruskal or some similar/comparable course. At University of Maryland, every comp-sci student can either be seen banging their head with a wall or thinking about dropping computer science as a major.

  With student's grade data we will like to determine what grade a particular student can get in a Computer Science course given the student's performance in past Computer Science Courses (Pre-Requisites or Gateway Courses). We want to answer the question that are grades and performance in a course correlated to the performance in the pre-requisite courses for that course ? 
  
  If our model is reasonabaly successful, we can provide insights to students which can prove very helpful when taking some important decisions. For E.g. A student can know that historically other students who have a similar performance to them have ended with a X grade in the class. So student can think and decide ok, I will have to put in more work than usual to earn a better grade than this. Or currentlly I am at this standing, should I drop the class ? And sometimes its just peace of mind and anxiety buster to know where you stand and where you can end-up at the end of the semester.
  
  These decisions have a significant impact on your college plan, graduation, and even your GPA. 
</p>


<h2> Data Collection</h2>
<p>
A student's acadmic records are goverened by many privacy laws, including FERPA. FERPA is a Federal law that protects a student's education records. It may only disclose a student's educational record if he or she has given written consent to do so. We requested for anonymized data from the school, but due to these laws we couldn't get access to such data. We had to do it the harder way - survey people for their data. Then we made a google form to collect grades for each course they took. We made it anonymous so that no personal information is collected and can be linked to a specific student. We relied on the honesty of students to fill out the form. 
 
Important things about the data -
1. We generally saw a trend that students who performed well in classes shared their data. For most of the classes the average grade from the survey was heigher than the overall general average grade. (Tanmay insert teh graph and explain the results)
2. Student's are allowed to skip certain classes through the help of AP's, high school credits, and Computer Science Exemption exams. We encountered such data and we had no way to determine which grade to assign the student. We made a general assumption to take these as B+ grades, which according to university policy means Good Mastery of the subject. This was done for the following courses - CMSC 131, CMSC 132, CMSC 216, CMSC 250, MATH 140, and MATH 141. 
3. There were cases where students didn't want to share the results/grades on a particular course. To deal with this, we averaged the grades in other courses that the student took and entered that value instead of "Don't want to share".
4. There were some students who didn't attempt certain courses. We ignored such student enteries entirely for certain models depending on the subject.
5. There were certain edge cases also, which we handled on case to case basis.
</p>

<p> Shanil Data Cleaning Details Code + Steps </p>
<p> Tanmay Data Visualizations with explanantions of the insights </p>
<p> Siddhesh Model Building with explanations and results </p>
