# Zooey Discord Bot
Zooey is a Discord chat bot that adds useful commands for Granblue Fantasy.

## Commands
Below is a selection of commands that the bot supports, along with examples on how to use them.

#### !time
Returns the current time in JST (Japan Standard Time)

##### Example Usage

    !time

***

#### !striketime or !st
Returns the time remaining until the next striketime.

##### Example Usage

    !striketime
    !st

***

#### !events or !schedule
This will show a list of all currenly running, recently finished and upcoming events for Granblue Fantasy. The bot will calculate the time remaining and display it as well.

##### Example Usage

    !events 
    !schedule

***
        
#### !news
Shows the 3 most recent news items posted on the official GBF News page. This is only available in Japanese, as the news page is never translated to English. 

##### Example Usage

    !news

***

#### !zoi or !zooey
This will return a random Zooey fanart image from danbooru. Only SFW images are included in the results, although the definition of SFW might vary based on personal opinion.

##### Example Usage

    !zoi
    !zooey

***
    
#### !booru <tag> or !danbooru <tag>
This will return a random fanart image from danbooru based on the tag supplied. Only SFW images are included in the results, although the definition of SFW might vary based on personal opinion. 

For a list of tags refer to [danbooru](http://danbooru.donmai.us/tags)

##### Example Usage

    !booru clarisse_(granblue_fantasy) 
    !danbooru catalina_(granblue_fantasy) _(granblue_fantasy) 

***

#### !cc <source currency> <target currency> <amount>
This will convert a given amoun from one currency to another. Data is based on Google's currency conversion and might not always exactly match the currency conversion rate on mobage or Google Play.

##### Example Usage

    !cc JPY USD 3080

