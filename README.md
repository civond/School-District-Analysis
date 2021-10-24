<h1>School District Analysis</h1>
<h2>Overview</h2>
<br/> The purpose of performing this activity was to first remove the scores of all 9th graders at Thomas High School, and then determine whether school budget, type, or size has an effect on the overall passing rate in reading and math subjects.
<h2>Results</h2>
Replacing the scores of 9th graders (due to fears of academic dishonesty) had the following effects (THS is a medium-sized, medium-budget school):
  <ul>
    <li>District summary was slightly shifted downwards (see images below for numbers).</li>
      <br/>Original: <img src = Resources/District_Original.PNG>
      <br/>Adjusted: <img src = Resources/District_Update.PNG><br/>
    <li>The overall passing percentage in both math and reading subjects for THS dropped slightly from 90.94% -> 90.63%.</li>
      <br/>Original: <img src = Resources/THS_Original.PNG>
      <br/>Adjusted: <img src = Resources/THS_update.PNG><br/><br/>
  
  <li>Relative to other schools, THS's passing percentages are similar to another medium-budget/medium-size charter school (Griffin HS)</li>
    <br/>Adjusted: <img src = Resources/GriffinHS.PNG><br/><br/>
  <li>The average math and reading scores for 9th graders at THS were 83.6% and 83.7% respectively (before changing values to NaN)</li>
  Math: <img src = Resources/MathScores_Original.PNG>
  Reading: <img src = Resources/ReadingScores_Original.PNG><br/><br/>
  
  <li>Average math score for medium-spending schools (per student) decreased (79.42% -> 79.41%) and average reading score increased (82.04% -> 82.05%)</li>
   <br/>Original: <img src = Resources/SchoolSpending_Original.PNG>
   <br/>Adjusted: <img src = Resources/SchoolSpending_Updated.PNG><br/><br/>
  
  <li>Scores by school size saw no changes.</li>
  <img src = Resources/SchoolSize_Updated.PNG><br/><br/>
  <li>Scores by school type saw no changes.</li>
  <img src = Resources/SchoolType_Updated.PNG><br/><br/>
  </ul>
<h2>Summary</h2>
After the scores of ninth graders at THS was replaced with NaN's, there were the following changes:
<ol>
  <li>Average math scores for medium-spending schools saw a slight decrease while average reading scores for medium-spending schools saw a slight increase.</li>
  <li>Average math and reading scores decreased slightly across the whole district.</li>
  <li>The percentage of students who passed both reading and math at THS dropped by a third of a percent.</li>
  <li>The percentage of students who passed both reading math in the district as a whole also saw a slight decrease.</li>
</ol>

