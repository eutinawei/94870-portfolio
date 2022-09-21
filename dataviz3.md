# Assignment 3 & 4: Critique by Design

[Home Page](/README.md)

## Step three: sketch out a solution

![IMG_0269](https://user-images.githubusercontent.com/46619191/191154956-2278fde0-a8b2-4f47-ae7e-dccc53de1e82.jpg)

I basically took the numbers and turned it into a line graph. I figured it would be useful to visualize the numbers for readers to view the trend. Also, I made different countries to different colors, and I simplify both x-axis and y-axis to a range of number to simplify the graph.

## Step four: Test the solution

1. Student, early 20's
  - Q: Can you tell me what you think this is?
  - A: This is the number of Taiwanese students receiving student visa from some countries from 2012 to 2021 (basically repeating the title)
  - Q: Can you describe to me what this is telling you?
  - A: US used to take a lot more of the Taiwanese students, but there was a sharp decline. Other counties are relatively segmented.
  - Q: Is there anything you find surprising or confusing?
  - A: Except for US, other countries are a bit too small and hard to read.
  - Q: Who do you think is the intended audience for this?
  - A: Potential voters in the US? (Why?) Cause the sharp decline seemed to be because of Trump. (Oh I did a poor job wireframing. That line should decline during 2020.) Oh so it's because of covid! Then the audience might be Taiwanese that are looking for visa.
  - Q: Is there anything you would change or do differently?
  - A: I would make the scale of x-axis bigger. Cause currently except the US, all the other countries are gathered together.

2. Student, mid 20's
  - Q: Can you tell me what you think this is?
  - A: A graph about the number of Taiwanese students receiving student visa from major countries from 2012 to 2021 (repeating the title as well)
  - Q: Can you describe to me what this is telling you?
  - A: The majority of Taiwanese throughout the years have been getting student visa from the US, and it plunged during 2019. (Oh sorry I messed up the wireframe it should be 2020.) Oh okay. It makes sense now.
  - Q: Is there anything you find surprising or confusing?
  - A: It is confusing that the line for Japan is longer than others, and how only Canada acted differently during 2020 is pretty surprising.
  - Q: Who do you think is the intended audience for this?
  - A: Probably Taiwanese who are deciding what countries they would like to go study.
  - Q: Is there anything you would change or do differently?
  - A: I would like to learn more about the data before 2012. Also, I would want to zoom in the graph and set the max value of y-axis to 15k to have a clearer comparison of different countries.

## Step five: Build your solution

### Data Source

* [Taiwanese Ministry of Education](https://depart.moe.edu.tw/ed2500/News_Content.aspx?n=2D25F01E87D6EE17&sms=4061A6357922F45A&s=EBACDD1821598B54)
* [Graph PDF File](https://ws.moe.edu.tw/Download.ashx?u=C099358C81D4876CC7586B178A6BD6D5062C39FB76BDE7EC66666DAAF3C3A25A1A6A5CF96175B24B5A53B76DF0C038A11A21C9E5F85354419AE072D6F25F637CEE2A91C1A6023013336083EB22FC9603&n=5AFD75A083F3B9F893E3B2F745DF5E553480784997A7BC0106B92954E0A2BF48&icon=..pdf)

I chose this data because it is meaningful and important to me. This is the number of Taiwanese receiving student visa from various countries within the last 10 years, by our Ministry of Education. It is special to me because my friends and I used to take this as reference when we considering what places we wanted to do our masters before applying for masters programs and coming to the states. I can remember even back then we joked about how poor it did in terms of visualization. Therefore, although I was hesistant on choosing this as my assignment data source (since this is a table chart, and it's obvious that there's great room of improvement), I still wanted to give it a shot because I've always wanted to try to make it more understandable.

### Data Visualization

After conducting some quick survey, at first, I tried to create a graph with Tableau with all countries having different colors in it. However, I soon realized it would be complicated to put all countries in the same graph, so I separated the data into three groups: North America, Europe, and East Asia and Oceania. Also, to make the groups clearer, I made the countries in the same group having gradient colors for indication. As for zooming in and decreasing the range for the y-axis, which was mentioned by the second tester, originally I was considering taking the US line away when doing graphs for other two groups; however, I still think it is important to show how they relatively perform, and that is also what I want to convey, so I still keep it that way in the end. Overall, I think this is a interesting experience for me: by staring at the original table chart, I understood that there was a plunge and immediately followed by a sharp increase for the US after covid happened. However, it was not until I put it together with other counties and compared them that I realized other countries did not perform that severe. Also, it's cool to see how Japan dropped to almost the bottom after covid happened, and I believe it has something to do with the Japanese government locking down the country.

<img width="1040" alt="North America" src="https://user-images.githubusercontent.com/46619191/191399074-9ecc9f7e-f273-4b94-a153-f7d9165d4841.png">

<img width="1040" alt="Europe" src="https://user-images.githubusercontent.com/46619191/191399087-eb55d1f0-834c-4875-8847-094e5b0e47bb.png">

<img width="1040" alt="East Asia and Oceania" src="https://user-images.githubusercontent.com/46619191/191399103-f089d3b4-f4e8-4ce6-9985-e463e17860e1.png">

