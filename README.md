# smsableV2
Android Java Project that turns your phone into an automatic SMS sender


Setting Up for Sending SMS
1. Install the app in your phone
2. Copy the Device ID 
3. Create a php file with the following "$_GET" method 
4. Use the following methods key,message,receiver
5. The data from that get methods should be saved in a table
6. Create a phpfile that will display the table where the key,message,receiver in JSON Format
7. Go to android app and find the file `Links` and change the link in the `smsReceiveAPI` with the link of your file


Setting Up for Receiving SMS
1. In incomming message put the keyword you want to be filtered and the PHP file you want to be called
2. Make sure that php file has a "$_POST" method with a parameter of number and message
3. Click Save Settings

For running the app
1. Click start SMS sending and choocse the SIM Card that has a load
2. Click Listen to Incoming SMS
