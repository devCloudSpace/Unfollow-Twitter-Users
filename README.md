# Automattically Unfollow Twitter Users who are not following you back
This script is to be run in your web console.  
  
Make sure you are on your profile under "following".  
Scroll down as far as you wish, then copy/paste this script into the web console.  
  
It will pause for a random amount of seconds (greater than 2) between each action.  
This is in order to not be spammy on the Twitter network.  
Random time varies between 1 and a number of seconds set by the user.  
  
### Warning:
#### Do not unfollow more than 200 people in a 24 hour period.
Twitter does not like mass unfollowing (or following) and will lock your account.  
To many lock outs and you could get your account banned.  
  
### How to do the thing:
#### (In 9 Easy Steps!)
0. Right Click 'unfollow.js' above and select open in new tab
1. Open [https://twitter/following](https://twitter.com/following)
2. Open the dev console (**ctrl + shift + J** or **cmd + shift + J** on Mac)
3. Highlight and copy the code from 'unfollow.js'
4. Paste the copied code into your dev console from step 3
5. Enter any usernames of non-followers you'd like to keep following
7. Press 'Enter'
8. Profit!  
  
  **Notice:**  
  * Make sure to type the usernames of the non-followers you wish to keep following **exacly** as is showin in their handle.
  * "jrswab" is not the same as "Jrswab", "JRswab", "jrSwab", ect.
  * no need to prefix with '@'
  
**To Do:**
1. Allow users to load usernames from a text file.

**Done:**
1. ~~Send alert message when finished.~~
2. ~~Execute unfollow actions at random intervals to seem more human~~
3. ~~Make the script unable to refollow previously unfollowed users if the page is not refreshed before consecutive reruns.~~
4. ~~Allow user to input usernames of non-followers that they wish to keep following.~~
5. ~~Allow users to specifiy maximum wait time between actions.~~

  
### If you found this usefull please give it a star. I'll :heart: you forever.
