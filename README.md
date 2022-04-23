# School_District_Analysis

## Overview
The purpose of this analysis is to remove values that are not a number (NaN) so that the analysis is as accurate as possible for school district reading and math scores. 

## Results

### District Summary

<img width="907" alt="1" src="https://user-images.githubusercontent.com/91761393/164911795-9a174aaa-acf9-4026-a481-4ef9eff372c8.png">

The overall average math and reading percentages dropped by no more than 1%.


### School Summary

<img width="983" alt="2" src="https://user-images.githubusercontent.com/91761393/164911813-ea9c9c7f-d11b-47e3-96b1-98d12e4b2b85.png">

The top 5 performing schools are Cabrera, Griffin, Wilson, Pena, and Wright High School while the bottom 5 performing are Rodriguez, Figueroa, Huang, Hernandez, and Johnson High School. 


### Thomas High School

<img width="983" alt="3" src="https://user-images.githubusercontent.com/91761393/164911835-cb98d52b-9c61-43d1-b683-83ee78b5df76.png">

<img width="978" alt="4" src="https://user-images.githubusercontent.com/91761393/164911842-1bf514f7-541b-4aa5-823f-7a6454b79cad.png">

After replacing reading and math scores, THS dropped out of the top 5 schools. The overall passing rate also dropped from 91% to 65%. It now ranks 8 out of 15 schools

<img width="286" alt="5" src="https://user-images.githubusercontent.com/91761393/164911868-b5fe7329-825f-4f0e-a668-22413e4b829b.png">

<img width="286" alt="6" src="https://user-images.githubusercontent.com/91761393/164911874-7bf8cc23-da4d-44c4-b8d7-7d3d34513e1a.png">


### After Replacing 9th Grade Scores...

* Math and Reading Scores by Grade

Scores were largely unnafected by removing the 9th grade scores.

* Scores by School Spending

<img width="814" alt="7" src="https://user-images.githubusercontent.com/91761393/164911904-c6ea0b77-52bb-43de-8c68-86ccff5df7ab.png">

Percent passing as it pertains to passing reading and math did drop in the $630-$644 range after removing NaN's.

* Scores by School Size

<img width="750" alt="8" src="https://user-images.githubusercontent.com/91761393/164911911-15b7538a-1228-400d-bf61-23c0ca4a5748.png">

Overall, math, and reading passing percentages did drop after removing NaN values but only for schools with 1000-2000 students enrolled. 

* Scores by School Type

<img width="704" alt="9" src="https://user-images.githubusercontent.com/91761393/164911930-82f0f37c-8445-4e72-a580-f1d2f64b8c64.png">

Scores for district vs. charter schools were unnaffected by the removal of NaN values. 

## Summary 
Overall, after replacing NaN values, school spending passing % and school size passing % dropped for the district while passing % and scores by grade were unnaffected. 
