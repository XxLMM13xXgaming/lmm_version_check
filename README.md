PLEASE FOLLOW INSTRUCTIONS!!!

PLACE THIS FILE IN gmod/addons/youraddon/lua/autorun/

First you will need a github account.. (it can be free... mine is)
Next go to your Gist's page (https://gist.github.com)
Enter in a file name.. can be anything does not matter! (first we will be doing the version.. so name it just the addon name)
Then enter the version (1.0 most likly)
Your screen should look like this: https://gyazo.com/58d2efdfe994fe8ef6b58821a46d8c4d
MAKE SURE TO CLICK CREATE PUBLIC GIST
Then click on the "Raw" button (screen should look like this: https://gyazo.com/a2d105000bf11e2aaecd91dc3835893c)
Your page will then go to a blank page with just the text.. now your link should look like this:

https://gist.githubusercontent.com/XxLMM13xXgaming/697ebb4f92d669012cfa130b75498dfd/raw/1f5443bc0e6fece435b53a55d6e1d3430c0852b0/test

Now you do need to edit this link...
remove the random numbers inbetween /rar/ and /test so my link up there will look like this

https://gist.githubusercontent.com/XxLMM13xXgaming/697ebb4f92d669012cfa130b75498dfd/raw/test

go to that link and it should look the same as the first link
Screen should look like this: https://gyazo.com/ec6e42bc9cdfd3998e9e0403d28d60f5

Place that new shorter link in the config "version_url" and set "version" to 1.0 or your version...

Next is the "update_ur".. repeat this whole config but name the file your addon name and add UR to the end (ex. test UR)
instead of putting 1.0 you can put the update reason meaning whats new.. I would put "Most up-to-date Release" for the first version
make the link short (follow directions above) and place the link in the config "update_ur" 

You should also put the link to the github download in the "update_url" config option

Also.. the "addon_id" config option should be a special word/id.. In my addons i use LMM then the addon initials like for my bail npc i would do LMMBNPC however you can use whatever you want
in the "addon_name" config option you can put your addons name that will show to the user like.. "Bail NPC" in my case for the bail npc addon!

Your all done!

HOW TO UPDATE:

Go to your gists page and click on the addon name (NOT THE UR YET) then click edit and change the version! (also change the version in the config file of the version check!)
Then click save and upload the change to github (your addons new version)
Then go to your gists page and click on the addons UR file and change it to whats new in the addon!
Save that to gist and thats it!

Thanks for using and PLEASE make sure to credit me in your addon! Thanks!
