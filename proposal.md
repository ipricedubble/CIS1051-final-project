# Proposal

## What will (likely) be the title of your project?

I'll probably end up naming it something boringly descriptive like 'Plant Medicine'. 

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

An app that reminds the user to take their medication. Each day that they successfully take their medication, the user's virtual plant grows.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The software will ask the user to input one or more times to receive a notification to remind them to take their medication. The software will store this value, and when the system's time is equal to the stored value, a push notification will be sent to the user. A boolean value ("notification_sent") will be stored to indicate whether or not this notification has been sent. While "notification_sent" is equal to 'true', the interface will have a button which prompts the user confirm whether or not they took their medication. The software will store a boolean value ("medication_taken"). If all "medication_taken" values for a day are equal to 'true', the sprite for the plant will change and gradually 'grow'. If one or more values are equal to 'false', the plant will not grow. Once the plant reaches its maximum growth, the sprite will remain the same unless the values for "medication_taken" are false for three days or more. Every two days after that, the plants sprite will change to indicate withering. There will be five stages of withering until the plant is "dead" and does not grow. 

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N/A

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

- The user will be able to set one notification time for their medication.
- The user will be able to confirm that they succeeded in taking their medication.
- The plant will grow (sprite will change) if the user confirms that they took their medication.
- The application will store the number of days that the user takes their medication so that the plant grows consistently and does not reset.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

- The user will be able to set multiple notification times (i.e. AM and PM) for their medication.
- The user will be able to confirm that they failed to take their medication.
- The plant's growth will reverse if the user does not take their medication.
- The interface will NOT use placeholder images to illustrate the plant stages.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

- The plant will wither (using different sprites rather than reversed) if the user does not take their medication.
- The growth stages and withering stages will correlate to one another (ex. if the plant is at stage 6 growth when it begins to wither, the withering will begin at stage 3).
- The plant will grow at midnight instead of immediately upon taking the medication (not sure about this one though, I'll have to think about which time is better).
- The application will have some sort of sound effects (no idea what for yet, I just like sound effects)
- The interface will be customizable with different backgrounds and plant pots.
- The app will be usable on both Android and IOS devices.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I need to install Kivy (a module for app development). I need to research how to use that module and I will presumably have to install an Android emulator (when I'm home for Easter I'll also see if I can't find someone's old phone as well, since that would be more help with creating the interface). I believe I have the skills on the programming side, I just need to get familiar with Kivy so I can apply them. I also need to learn how to create the interface, as I don't exactly know how that works yet (I was never good at CSS). As less of an immediate priority, I need to make placeholder images because I'll need them pretty immediately as I write the code. One of my friends said she could create sprites for me (not for free!), which takes some of the load off because I'm a terrible artist. I want to do some sort of informal poll 

