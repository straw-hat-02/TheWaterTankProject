# The Water Tank Project

This is the web application for the dashboard of the water tank project. Written in HTML, CSS and Javascript. This can only work using flask or django.

## Installation

Using GIT Bash:

- git remote add origin 'https://github.com/straw-hat-02/TheWaterTankProject'
- git pull origin master

## Usage 
- Change line 57 using the external ip your server
- index.html must be rendered with argument 'data'
- 'data' format:
-- Type: list
-- [volume1,volume2,volume3,volume4,volume5,volume6,
    lastUsed1,lastUsed2,lastUsed3,lastUsed4,lastUsed5,lastUsed6,
    [day1,count1],[day2,count2],[day3,count3],[day4,count4],[day5,count5],[day6,count6],
    [month1,count1],[month2,count2],[month3,count3],[month4,count4],[month5,count5],
    [month,count6],[year1,count1],[year2,count2],[year3,count3],[year4,count4],
    [year5,count5],[year6,count6]]

## License
[MIT](https://choosealicense.com/licenses/mit/)




