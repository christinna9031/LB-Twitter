# LB Twitter
 LioranBoard extension for Twitter.      
**Features** : Tweet, Retweet, Like a Tweet, Reply to a Tweet, Get Recent Tweets, Monitor New Tweets (and trigger actions in your LB), rename your Twitter name.       

**IMPORTANT:**
Once you install the extension, go to your Transmitter - Twitter Tab. Click on Check status and select Open or Copy Twitter URL. Copy your provided PIN.
Fill out "Enter PIN" input field and click on Authenticate. If it says Success, you're all good to go.  
You can Tweet, Retweet, Like and Retrieve Tweets from your Transmitter as well directly from the Receiver. 

**The extension comes with premade buttons to make it easier to understand how it works:**

`Tweet it`
* value 1 = text you want to Tweet (can contain links as well)      


**Get Recent Tweets**      
* incl_retweets = whether to include retweets, incl_replies = whether to include replies      
* value1 = variable/stack to save the tweet(s) in
* value2 = twitter screen name  (no spaces and no @)        
* value3 = how many tweets to get (retweets and replies are still counted even when you select false)        
* you can put "timeline" in value2 to retreat all tweets in your timeline       
* your tweets will be saved in your variable and tweet IDs in variable_id               
			
			
**Like a Tweet** 
* value1 = Tweet ID (can be retrieved from variable_id after you use "Recent Tweet")      

**Retweet** 
* value1 = Tweet ID (can be retrieved from variable_id after you use "Recent Tweet")       


**Reply to a Tweet** 
* value1 = Tweet ID (can be retrieved from variable_id after you use "Recent Tweet")
* value2 = empty
* value 3 = text to reply with       

**Monitor Tweets ON**      
Monitors any new tweets from the specified account and sends an extension trigger.      
* value2 = twitter screen name (no spaces and no @)       
* value3 = interval to check for new tweets (in seconds).    
It will first retrieve 10 recent tweets. After that it will remember which one it has already retrieved and will only trigger with any new tweets. It will remember it even after you close Transmitter. the extension trigger name will be the same as the screen name (all lower case characters)       

**Monitor Tweets OFF**      
Turns off new tweets monitoring.
* value2 = screen name you used in your Monitor Tweets ON command         

**Tweet Trigger**         
Fires whenever there is a new tweet. The trigger is the same as the screen name you used in your Monitor Tweets ON button. Twitter API is delayed by a few minutes when retrieving any new tweets, so be aware of that.    

**Rename**     
Lets you rename your Twitter name
* value1 = your new name


**How to install an extension:**
1. Download the .lbe extension file
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)
