# School_District_Analysis_Challenge
# How is the district summary affected?
 The total count of students did not change as that was run on the count of the student ids, which was not turned into null data. When comparing them, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set.
# How is the school summary affected?
![6e767defd7944ec7de2a2c90e38a867](https://user-images.githubusercontent.com/108849308/193166678-ab7c582a-5bc4-442a-bf07-5c53ebab95b2.jpg)
![ebfff982b6d9e878f646b46dae00ebf](https://user-images.githubusercontent.com/108849308/193166722-5c45ff46-b792-43d0-bdc1-016e4931e7cc.jpg)
Removing the 9th grade students from the data set had a huge impact by dropping from 91% to 65% for the overall passing rate.
# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
![b86db578ba6d238d5618e8175a919fb](https://user-images.githubusercontent.com/108849308/193166909-cd88b3d4-b67e-4a23-b2da-b04c3c953980.jpg)
![0ca7911ceb32af276c8828c74ebaa76](https://user-images.githubusercontent.com/108849308/193166945-1daaa0ba-c3fc-4da9-a5a5-d41bd605b99f.jpg)
After adjusting the 9th grade data, Thomas High School ranked in the exact middle of 15 campuses at 8th from the bottom.
# How does replacing the ninth-grade scores affect the following:
![fb8dbe1ce8a136136e363b68f593025](https://user-images.githubusercontent.com/108849308/193167057-484d0d33-519c-4354-8f15-710afbebce6d.jpg)
![5458f9f4546f3af17f4d684a8d87301](https://user-images.githubusercontent.com/108849308/193167083-f3f3a859-f78b-433d-89df-8b393b9d3298.jpg)
Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts.
# Scores by school spending
There was very little spending impact by changing the 9th grade scores.
![819c73805fa320adc9f05a26375744f](https://user-images.githubusercontent.com/108849308/193167326-9887cb91-cabd-4a88-a70e-b30a981509eb.jpg)
![2f6864d59f0d1ccd456de01012c5216](https://user-images.githubusercontent.com/108849308/193167338-dd6edb4b-014e-4231-a44f-23e6e2857d43.jpg)

# Scores by school size
![9d3397306393eea5dd6157f53c97055](https://user-images.githubusercontent.com/108849308/193167405-8aef1fcd-6780-491d-8826-3ce26f42b663.jpg)
![bbae4fcd1837dcba80e2e689539255a](https://user-images.githubusercontent.com/108849308/193167421-56f6d830-7788-4c1d-8a08-7e2eb6881fba.jpg)
There was very little impact by campus size due to changing the 9th grade scores.
# Scores by school type
![5515d0768ce27a56a8d89a81ba03064](https://user-images.githubusercontent.com/108849308/193167480-fab92e58-165a-40f1-9c89-7194c7a9ac0e.jpg)
![6e2d5591287d097993336fbd9cfa4a2](https://user-images.githubusercontent.com/108849308/193167482-f65b4b9d-9001-4c4f-95bc-47a3d1b2b6b8.jpg)
There was very little impact by school type by changing the 9th grade scores.
# Summary
1.The overall passing rate for Thomas High School changed from 91% to 65%.

2.Thomas High School's ranking dropped from 2nd to 8th.

3.Data at the grade level will now show as "NaN" in reports for the 9th grade students.

4.The campus math and reading averages and passing percentages all saw shifts.


