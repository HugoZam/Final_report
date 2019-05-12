# Final Report

## ITMT 430 2019 - Your Name

### Sprint 4

1. Each team member should comment on their own accomplishments (Taken word for word from the sprint reports) and describe what they did and explain any decisions referencing any lectures or material from the text book or web.

Accomplishments sprint 4: "As Lead developer again the main goal after the purge of the cloudinary api was getting back functionality of things like searching for multiple pictures with tags which was done by splitting input from the tagline on a space, inserting them into the search array and then locating the picture among all the pictures tagged located on mongo DB. It was also to add more sleek functionality like making it so the 3 radio buttons only showed once “Get Started” was selected."

During this sprint being told we could no longer use the Cloudinary API, despite explaining our use of it
throughout the semester, we wanted to prove we could function without it. It was less work than anticipated,
the majority of the work was migrating our use of pulling meta data from mongo DB instead of the cloudinary storage in order to get the sear for tag function to work. It required extensive research on how we could replace Cloudinary in which I spent majority of lab time with my team mates discussing it. The other goal was to have a deployable system this time around which we had gotten a build script that was up and running mostly due to Jinwen who really took the time to understand how the scripts worked and brought that information back to the group, we managed to hit our goals this sprint.

1. Correlate the personal sprint report with completed goals stated in the sprint report
1. Trello Card(s) that shows the completed artifact (screen shot of card)  

![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_1.PNG)
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_2.PNG)
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_3.PNG)

1. Github code commits
    1) Under the History tab in GitHub you will see the repo commit history and each commit has a SHA-1 hash, supply this URL


    2) https://github.com/illinoistech-itm/2019-team-08f/commit/23f6215a336d66d3663776162ce9e6421dbdee10

    3) https://github.com/illinoistech-itm/2019-team-08f/commit/b70da3181e018d018823b95f35ed30c8dc1d1690
    4) https://github.com/illinoistech-itm/2019-team-08f/commit/26168cf452a164560b10291a3dfe4336ee04ccbe
    5)https://github.com/illinoistech-itm/2019-team-08f/commit/962979e5fe89c6e17bc4975fcff8cc27737fda8f
    6)https://github.com/illinoistech-itm/2019-team-08f/commit/785d07299adc49c8362969b622d2500ec5b35a31
### Sprint 5

1. Each team member should comment on their own accomplishments (Taken word for word from the sprint reports) and describe what they did and explain any decisions referencing any lectures or material from the text book or web.

As a junior developer two of my main tasks to get working where editing the metadata in the pictures to change the tag function, and to add multiple images while retaining a dynamic way for adding a tag to each image being added. I was unable to figure out the changing the meta data because it would not remove the old tag but add a new one alongside the old one. I hope to figure out how to fix this problem in the future.

For majority of this sprint I spent doing research with Tom on the best way to do multiples of both tag and image upload. In the end we did a quick work around our problem by letting the user choose Up to 5 images by adding 5 individual buttons to add an image instead having one and being able to select multiple images through the file selection. This ended up being a limitation from mongoDB rather than our logic. By the end of the sprint we did end up having what we wanted to accomplish done but not in the exact sleekest way possible UI wise.

1. Correlate the personal sprint report with completed goals stated in the sprint report

1. Trello Card(s) that shows the completed artifact (screen shot of card)  
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_4.PNG)
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_5.PNG)
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_6.PNG)

1. Github code commits
    1) Under the History tab in GitHub you will see the repo commit history and each commit has a SHA-1 hash, supply this URL
    2) https://github.com/illinoistech-itm/2019-team-08f/commit/cd72af37fab4a18305128963ea3fa57c4959cb4e
    3) https://github.com/illinoistech-itm/2019-team-08f/commit/b8826ba83e09ae129cb78b90dd968decea70862c

### Sprint 6

1. Each team member should comment on their own accomplishments (Taken word for word from the sprint reports) and describe what they did and explain any decisions referencing any lectures or material from the text book or web.

As IT Operations part of my main task was troubleshooting why building the machine didn't work on a machine and what could be improved on within the script so that everyone could successfully build. Especially with the added build step for the database we had constant stand stills on machines for almost no apparent reason.

During this phase I spent a lot of the time with Wenzhao trying to debug everyone's machines when they would get stuck during the running of our build script. Tom, Akshay, and Jingwen being the most troubling for there own reasons. We did some modifications to the instructions based on certain errors that would come up and work arounds for them. I believe it fell in line with what we wanted to accomplish which is have everyone have a successful build on a work machine they own

1. Correlate the personal sprint report with completed goals stated in the sprint report
1. Trello Card(s) that shows the completed artifact (screen shot of card)  
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_7.PNG)
![Screenshot](https://github.com/HugoZam/Final_report/blob/master/final_template/trello_card_8.PNG)

1. Github code commits
    1) Under the History tab in GitHub you will see the repo commit history and each commit has a SHA-1 hash, supply this URL
