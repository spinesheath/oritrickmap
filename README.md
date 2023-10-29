# Ori trick map
Browse tricks in Ori and the Blind Forest on the map of Nibel\
https://oristorage.blob.core.windows.net/other/oriTrickMap.html

# Verify changes to trick definitions
## local definitions file
To verify your edits, open the html file locally. It will attempt to load the local trickDefinitions.json. This will likely be blocked by CORS, so you have to enable it in your browser.
## host definitions on github
Push the adjusted trick definitions to your fork and change the url in oriTrickMap.html to point to your fork. The variable you need to change is called "trickDefinitionsSource". Then just open the html locally.

# Guidelines for trick definitions
## General
All relevant voice or text should be in English.
## Name
Should be short and informative. The user will know the rough location of the trick on the map, so information about that does not have to be complete. Try to write the name in a way that is most useful for someone trying to figure out how to reach a place or achieve some other goal.
## Position
If you skip the x/y coordinates in a trick definition, it will be considered location independent. It will only be displayed when no other tricks can be found near the location where the user clicked on the map.\
Coordinates should be at the place where the user is most likely to look on the map. For a pickup that will usually be the pickup itself, not where you start from.
## Variants
A trick can have many variants with different skill sets or approaches that all achieve the same goal. Each variant should have tags, requirements, description and video. Differences that are irrelevant to the core of the trick can be grouped into a single variant, for example if you need wall jump of climb to scale wall somewhere in the middle of a trick. Try to sort variants by increasing difficulty.
## Requirements
A concise list of skills, resources and other things the player needs to execute a trick. Should usually start with skills, and skills should be listed in clockwise order on the skill wheel. There are no strict rules on the format, choose whatever is most informative for the user.
## Tags
A comma separated list of tags categorizing the variant. Tags are used for filtering tricks, so make sure you write them exactly the same as existing tags. New tags should be useful for filtering.
## Description
A detailed description of the execution of the trick. Should be detailed enough for an experienced player to figure out the trick without video, and help a less experienced player understand how to execute what they see in the video.
## Video
Make sure you have the approval of the creator of the video if you didn't create it yourself. Try to adhere to as many of the following guidelines as possible.
- Keep videos short.
- In game music or no music.
- Game sounds can be heard.
- Input display for difficult tricks.
We might be able to jump into a longer video at a specific time stamp, haven't tried it yet. Not sure how convenient that would be.
