# VistaValue: Expense Tracking At its Finest
[![forthebadge](http://forthebadge.com/images/badges/made-with-swift.svg)](http://forthebadge.com)	
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

## Your favorite app developers are back at it again!
Me and [@kshriv](https://github.com/kshriv) both finished up another year at GT and realized we had around a week before our internships started. With a time crunch of a week and a dream to change the world we decided to grind out an expense tracking app.
Why an expense tracking app you may ask? With only a week we didn't want to set the bar too high but also not too low. With an expense tracking app we realized that it could be as detailed and comprehensive as we wanted it to be, and save features to future iterations of the app. 

## The Goal
At a high level we set a plan:
• Implement data persistence in Swift

• Integrate cocoapods into our project

• Practice flat UI/UX design

• Transition away from storyboarding designs and move towards a programmatic approach

• Create amazing graphs generated from user data


## Demo

## Data Persistence
After discussing different options to persist data, we decided the most logical as well as the the easiest would be to implement Apple's native User Defaults. This way the data is stored locally on your device and you don't have to have Wi-Fi or data to use the app. Since user defaults is essentially just a backend dictionary where data is stored by keys we made a key for every category we allotted as an expense option. Putting this in a struct allowed us to access the keys easily throughout any swift file. 
<img src="https://github.com/thearijain/OfficialVistaValue/blob/master/Pictures/Keys.png" width="500" height="280" img align="right">
