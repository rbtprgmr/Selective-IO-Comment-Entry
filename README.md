# Selective IO Comment Entry
This webpage will allow a user to manually enter IO Comments into a Fanuc Robot. 
This is the same as going to the robot comment tool, the exception is it allows you to input the IO port that you are commenting.

This was created to solve timeout errors that may occur and also to allow the user to specify a quick comment without having to navigate an entire array on a page.

Instructions:
  * Upload ioentry.htm file to the robot using preferred method (FTP,UT1,UD1, etc.) - Robot will place file on /fr/.
  * Navigate to http://robot-ip-here/ioentry.htm in your preferred browser.
  * Enter in IO Port Number that you wish to comment.
  * Enter your desired comment.
  * Click the submit button and the data will parse to the robot. The input fields will become disabled.
  * You can confirm entry by checking the IO screen on the robot.
  * Select "Clear DI/DO Information" to enable the input fields so another comment can be entered.
