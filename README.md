## My Dashboard Project

# Motivation 


_This project was created to show a dataset in the forms of charts, allowing the user to select parts 
of the data to view different information such pokemon teams, gender of players, etc. I chose to use the 
dateset to find out if there is any correlation within the data in regards to age, gender, teams. Also,
to see if there is a pattern between new players and ones, who have played longer._ 

# Naming And inspiration

_I chose to use pokemon as a theme because I am aware of the game, and its popularity. The name I chose was down to the dashboard
was to do with the rest of my page, as I felt that it went well with my charts, border styling and finally._




### Select Dropdown
_I chose to give my page a dropdown to allow easy selection of date by pokemon teams. This way I felt I could
filter the data to show if there is any correlation between the teams players have chosen. I did this by using
a function called show_team_selector and picking team from my dataset. This was made easier by creating an id
in my index.html which later I could use in my (dc.selectMenu("#team-selector")._





## Credits

_As this is a project all the date was manually created and images have been used which all credits go niantic
so I do not take credit for any of the content. The content was just used as I am a player of the game pokemon
go and I wanted to see how I would that into a dashboard._

## Backgrounds

_For this project I trialled a number of backgrounds but I decided to go with a black background as I felt
it would show off the colours of my chart well. I did use a pokemon logo with an (image src=) to display a logo
but had some issues with pixelation. To resolve this I right clicked the image and used page inspect so I can
target the image width and height. On this occasion, I felt as it was the only real image others were charts 
created by my (graph.js) file, I adjusted my image so it would show clearly._



# Technologies

#### HTML

_This was used to create a structure for my page, which I could build on to later using css
to add colour and styling to the page (see below)._

#### CSS

_I used css style sheet which is a file that basically includes all my styles that add sytling, 
images, fonts etc. to the page. The css used on here gave my page styling as you see in the border style
I have used at start of my page._


# TESTING

#### Stacked Bar Chart

_I had some issues with changing the colour of my stacked bar charts as my legends were one colour but my bar charts
were totally another. This was resolved by using css and by right clicking the chart and inspecting I could see what 
was being using in to colour the charts. I used to (rect class=) but the problem I had with all three of my stack charts
would be same colour, so what I decided to do was use my id I had created and to use if statements as the three
teams in my chart we showing as layers so if one layer was equal to team name then it would use the colour. Also,
this was not easy as I had to research and find out that the colour cannot be changed with normal css eg (color: red;)
as I had to use fill to change colour of my chart within the function I created.This was very challenging so I chose to
use "chart.ordinalColors(["#f1c00f", "#a80e0e","#186CFF"])", which did help me to finally acheive the result I wanted,
allowing my colours to reflect when Hover over the legends._



#### HTML Validator 

The ("https://validator.w3.org/") was really helpful as it allowed me to work through my code and remove errors. 
This allowed me to have a code that ran smoothly because of no errors. I find this because sometimes I would have some issues
where I had fixed one part of my code then another error would show. The validator highlights the code with line number 
so I could easily dintinguish a typo or another code which was causing me problems._

#### CSS Validator 

_I used CSS Validator which is similar to the html validator above to make sure am using the correct code
which means it can help avoids errors down the line. This helped me a great deal as I had an issue with my
stacked charts and by checking the code was correct, this allowed me to work on my (graph.js) file because
I wanted to change the colour of the charts using that not and my css, made it easier to elimate what the issue
was_

#### GITHUB

_I found github to be of great use here as I could roll back data if I needed to. This was good to have this because I could see where I have gone wrong.
Using terminal on gitpod I checked which of my files were commited by using (git status).This allowed me to then add my files using (git add .) and then using 
(git status) again I could see they have been submitted. To complete this I would then use ("git push") which allowed my changes to be submitted so my site can 
be viewed online. I really found this to be much easier with gitpod intergration as I did not need to log on, which before could be difficult as your password your 
typing does not show up on screen. I did not need to manaully create a repository as this was already done as I created the workspace through github then selecting clone
which is plugin linking my github with my gitpod._

# DEPLOYMENT

_Using gitpod I pushed my project online, using the terminal I entered "git status", to see which files I had not commited, this showed me the files that were not pushed
in a red colour, I used "git commit -m "[commit message here]", After this I pushed the project online by using command "git push". This I found very easy to do as my gitpod is    
connected to my github, I had an issue with my workspace dissapearing, so I went online to github and using the gitpod plugin, It allow me to select the button and push
my github repository onto gitpod. After this had been done, now I can run my code " index.html" file, by simply entering into the terminal " python3 -m http.server, then clicking
in the bottom blue toolbar onto the ports section, expose the port 8000, then this will allow it to  be run in a browser to view " index.html"._

# CREDITS

#### MEDIA

_The images used in my index.html were taken online, the logo image on the right "https://www.futuregamereleases.com/wp-content/uploads/2019/08/niantic-banned-accounts-pokemon-go-ingress.png",
this was found by searching on "https://www.google.com/". The pokemon go logo that is seen on the site page was created by using "https://textcraft.net/style/Textcraft/pokemon",
this allowed me to enter text and create a logo, all credits go to the sites listed above._

#### CONTENT

_The data set is used which you will find in pokemon.csv was imspired from the site "https://www.kaggle.com/datasets", I chose a random data set and manual created the date
using as a template, so all the data was created for the purpose of the project and statistics are not based on real life events, credits go to site listed above for the
inspiration for my data._

#### ACKNOWLEDGEMENTS

_A big thank to all the tutors at code institute support, as I had many difficulty with what I was trying to accomplish, many times I did resolve the issue myself before support
got back to me. However, without the support I would not been able to complete this, so big thank you to them for the help they have provided._

# Created and Edited by Michael Singh






