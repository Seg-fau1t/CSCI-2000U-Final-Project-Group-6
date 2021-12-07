# Quality of housing in Toronto

## About us

> Hamza Hassan (HamzaHassan02)

> Shriraam Murugathas (raamify)

> Imran Mustafa (Seg-fau1t)

> Raj Shukla (Raj-Shukla2002)

## Introduction

This is a summary of a technical report that studyes the quality of Toronto's rentable housing. In particular realting to data collected by Toronto's RentSafe program, which inspects many hoousing complexes and rates them basesd on a standardized score. this data (avalibale at https://open.toronto.ca/dataset/apartment-building-evaluation/) will hopefully help in understanding the state of the city housing.

## Discussion

while many questions were asked and answered, with the variety of data points. Not all produced any meaning full trends and strong relationships. So this discussion will be limited to the most successful analysis preformed on the data set.

To start on of the data points that seemed interseting was the house age, and in particular how the affected the resulting score of the building. This was done to see if the city had an issue with older houses not being mantained and upgraded. and after analysis we did see a negative of -0.2624 trend, with higher ages corralating with a lower score. this does seem to issue but when comapring this number which is made up of the most recent reports in the city and compared them to the older reports we see that the corraltion seems to have gone down in recent years as the older reports show a correlation of -0.3297. thus implying that the city's ageing infrastructure seems to be getting the attention that it needs to improve and keep up with more modern buildings.

the next piece of analysis was by far the best and most successful and produceing some intresting insight into the state of the city. in this analysis we looked into the differences between Toronto's wards, to see if their were any high/low preformers and to see if their were any trends between them. and after breaking down scoreing by ward, and trend appeared to emerge where the wards with the most complexes seemed to score lower then wards with fewer. and after analysis of the relationships prodiced a whoping -0.4879 corealtion between ward size and average score. this seems to show that larger wards are performing poorly compared to their smaller counter parts. and while this is not the very strong trend it still seems strong enough for the city to investagate.

their were other things in the dataset that were looked into, but the rest of the trends were much weaker and not all that noteworthy. please read the full technical report if you are intrested in more detail to the above analysis and what other thing that were looked into.

## Conclusion

In Conclusion the project some trend in the rentable housing in Toronto, some like the increasing quality of housing built in the Toronto area, good. Some like the corelation between larger world and lower scores bad. But on the whole the quality of Toronto housing seems to be on a rise, and one that seems likely to persist into the near future.

and in reflection we have learned many things when it comes to data analysis, form its open-ended nature. to practice using real data sets and tools, to hoe to write reports on one's findings and what they mean. much of what this project has taught us will no doubt be invaluable in our future careers

and lessons for the next time that we preform data analysis can include asking more open question that really on multiple data points. So that more and better insight can be made from the same data. this will help refine the process of data science in any future analysis we preform.

## Acknowledgements

This project was submitted as the final course project for CSCI 2000U “Scientific 
Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cite

-------------------------------------------------------------------------------

# CSCI2000U Jupyter Notebook Image - Fall 2021

This repository contains a Jupyter Notebook environment with all the required packages for the **Scientific Data Analysis** course.

## Getting Started

On Ubuntu

1.	Install **Docker** on Ubuntu: https://docs.docker.com/engine/install/ubuntu/ 
  - 	Make sure you can run: `$ sudo docker run hello-world`
    - 	You might need to start docker first with: `$ sudo dockerd`
    - 	And then use another Ubuntu terminal to run the hello-world
2.	Install Docker compose: https://docs.docker.com/compose/install/ 
3.	Download, clone, or start a repository from the jupyter course repo template (recommended)
    - https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template.
5.	Go into your local repo of this project
6.	Start the container with your jupyter environment: `$ sudo docker-compose up`
7.	Access the jupyter notebook from your browser using any of the given URLs from the previous Step.


**Note:** You should **not** make changes to the `Dockerfile` or the `docker-compose.yml` file.

If you are using a different OS, you would still need to install docker from Step 1 and 2 for your platform. 
You should be responsible for searching the equivalent OS commands for your setup.
