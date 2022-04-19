# School_District_Analysis
# PyCitySchools Analysis
## Overview
PyCitySchools district asked for an analysis on the district overall math and reading scores. This analysis is to see if there is any correlation with the budget per student by finding the overall passing percentages of all students. There was evidence finding that the Thomas High School ninth graders reading and math grades were not valid. The previous scores will be removed and reanalyze to retrieve the correct data.  
## Results
- How is the district summary affected?
  - There is no change as the null data was added for the ninth graders, but the total amount of students did not change.
#### Original and Updated District Summary Compared
<img width="921" alt="Original District summary" src="https://user-images.githubusercontent.com/101374716/163899438-6a3a6983-903b-4086-beed-8365edc43037.png">

<img width="971" alt="Updated District Summary" src="https://user-images.githubusercontent.com/101374716/163899532-480bdcec-6f64-47a7-8b94-6f9a68fd656d.png">

- How is the school summary affected?
  - Thomas High school in the orginal analysis overall passing was 90.94% while in the adjusted analysis it is 90.63%. The overall passing percentage decreased by 0.31%.
 #### Original and Updated School Summary Compared
 <img width="1001" alt="original_school_summary" src="https://user-images.githubusercontent.com/101374716/163902341-b86335b3-fb0c-4662-a033-46da354691f1.png">

<img width="978" alt="updated_school_summary" src="https://user-images.githubusercontent.com/101374716/163902358-215fe4ba-1c1c-463d-8ac3-099034eeb2f6.png">

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - NaN was replaced with the the ninth graders grades for reading and math. The updated analysis shows that Thomas High School Ranks in the top five in descending order. 
- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
- <img width="434" alt="All_math_scores" src="https://user-images.githubusercontent.com/101374716/163904574-fa5bb41f-2fdc-45ca-a041-1b5345cfdb37.png">

- Scores by school spending

- Scores by school size
<img width="755" alt="original_school-size" src="https://user-images.githubusercontent.com/101374716/163902476-9a1e8cb0-2738-4197-9d93-dae7ece1e855.png">

<img width="791" alt="adjusted_school_size" src="https://user-images.githubusercontent.com/101374716/163902485-5c263776-6b38-4986-b13d-43f2279be9d4.png">


- Scores by school type
<img width="745" alt="Original_school_type" src="https://user-images.githubusercontent.com/101374716/163902405-022b399b-dc3c-438e-8040-204c8c199028.png">

<img width="724" alt="adjusted_school_type" src="https://user-images.githubusercontent.com/101374716/163902418-254644ff-c97c-49b4-aa1a-826d2c912ea2.png">
