# .Net-Core-3.1-Web-API-and-NLog
There are several popular logging framework available for c#, but 
[Nlog](https://nlog-project.org/) is my favorite. It's versatility and ease of configuration 
make it my number one choice for logging.

#### Why use a logging framework
Logging frameworks are written so that they never interfere with the 
normal operation of the app. Another way to put this is that while the
logging framework may not work correctly, it won't crash your app.
Logs should follow the standard

| Level | Typical Use |
| ------- | ------------ |
| Fatal	| Something bad happened; application is going down |
Error	Something failed; application may or may not continue
Warn	Something unexpected; application will continue
Info	Normal behavior like mail sent, user updated profile etc.
Debug	For debugging; executed query, user authenticated, session expired
Trace	For trace debugging; begin method X, end method X


#### Where to send log data
The first and most obvious answer is to a file, but there are 
other choices.
