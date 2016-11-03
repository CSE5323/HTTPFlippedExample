###For Thought
Group: Jenn Le, Ashley Isles, Preston Tighe
1. Yes it is blocking the IOLoop because while a function is servicing a post request, the IOLoop is not looking for any other connections.
2. No because the iOS app just tries to connect to the server and does nothing else if a connection can't be made.
