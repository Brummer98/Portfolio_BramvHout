# Software design FitOne

## Table of contents
* [User stories](#user-stories)
* * [Requirements](#requirements)
* * [Wireframes](#wireframes)
* * [Architecture](#architecture)
* * [API](#api)

## User stories
Several user stories have been written to express the functionality of the FitOne project:
* As a user i want to be able to have an easy overview of my daily caloriës intake in a dashboard like platform
* As a user i want the functionality to add food products to my personal list, to in that way have the overview of my caloriës intake every day.
* As a user i want the possibilty to select a goal, in order to generate a personal plan on which the daily calorie intake will be estimated.
* As a user i want to be able to choose from and select a range of fitness exirceses, in order to generate a personal plan on which the daily calorie intake will be estimated.
* As a user i want to be able to create an account, so i can easily login to the FitOne app to make use of all the functionalities that FitOne has to offer.
* As an admin i want that on every click on the page/action happening on the page that triggers content to show, that this would be achieved within 2 seconds of time. 

## Requirements
As for every project, requirements need to be setup so the proper functionalities that really need to be in the application, can be prioritized. For this i used the MoSCoW method and splitted the requirements into functional and non-functional.
#### functional requirements
* Users must be able to create an account ( Must )
* Users must be able to login on their created account ( Must )
* Users must be able to insert personal information to save to their account, like: Length, weigth, age, sex and name. ( Must )
* Users must be able to add food products to their personal list, to create an overview of their daily calorie intake. ( Must )
* Users must be able to edit their personal information, aswell as their goals and already added foods. ( Must )
* Users should be able to choose from a goal, for example: Losing weight or gaining muscle. ( Should )
* Users could be able to add another user on the platform to their 'friends' list ( Could )
* Users could be able to send a message to one of their 'friends' on the platform ( Could )
* Users could be able to schedule a training moment in their agenda and add friends to join them ( Could )

#### Non-functional requirements
* The process of loging in should not take any longer than 3 seconds after the button 'Login' has been pressed. ( Should )
* When a button is being pressed, the function that belongs to that button click event should not take any longer than 2 seconds ( Should ) 

## Wireframes
For designing the FitOne pages, i used a piece of software called ***Draw.io***. Since the wireframes are only an estimate of what i should look like, and not what it directly needs to look like, Draw.io is a perfectly fine program to use.

###### Creating account page
![alt text][logo]

[logo]: https://github.com/Brummer98/Portfolio_BramvHout/blob/2b5a1e26542064af7816b015cde29bbbd6644d34/img/FitOne%20-%20CreateAccount.png "Create account page FitOne"

###### Login page
![alt text1][logo1]

[logo1]: https://github.com/Brummer98/Portfolio_BramvHout/blob/2b5a1e26542064af7816b015cde29bbbd6644d34/img/FitOne%20-%20LoginUser.png "Login account page FitOne"

###### Dashboard home page
![alt text2][logo2]

[logo2]: https://github.com/Brummer98/Portfolio_BramvHout/blob/2b5a1e26542064af7816b015cde29bbbd6644d34/img/FitOne%20-%20Dashboard.png "Dashboard page FitOne"

###### Personal page
![alt text3][logo3]

[logo3]: https://github.com/Brummer98/Portfolio_BramvHout/blob/2b5a1e26542064af7816b015cde29bbbd6644d34/img/FitOne%20-%20Personal%20page.png "Personal page FitOne"

## Architecture
###### Context diagram
![alt text4][logo4]

[logo4]: https://github.com/Brummer98/Portfolio_BramvHout/blob/4818492d09fd2a9fadbbc278ea149ff1c577891c/img/Context%20diagram%20-%20FitOne.png "Context diagram FitOne"
###### Container diagramm
![alt text5][logo5]

[logo5]: https://github.com/Brummer98/Portfolio_BramvHout/blob/4818492d09fd2a9fadbbc278ea149ff1c577891c/img/Container%20diagram%20-%20FitOne.png "Container diagram FitOne"
###### Component diagram
![alt text6][logo6]

[logo6]: https://github.com/Brummer98/Portfolio_BramvHout/blob/4818492d09fd2a9fadbbc278ea149ff1c577891c/img/Component%20diagram%20-%20FitOne.png "Component diagram FitOne"
## Source
https://c4model.com/img/bigbankplc-SystemContext.png\
https://c4model.com/img/bigbankplc-Containers.png\
https://c4model.com/img/bigbankplc-Components.png\
https://c4model.com/img/bigbankplc-Classes.png
