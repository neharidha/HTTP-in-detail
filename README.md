# HTTP-in-detail
HTTP in detail | TryHackMe | Solution

Module — How The Web Works

HTTP in detail

Learn about how you request content from a web server using the HTTP protocol

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task1:

1.1 What does HTTP stand for?

Correct Answer: HyperText Transfer Protocol

1.2 What does the S in HTTPS stand for?

Correct Answer: secure

1.3 On the mock webpage on the right there is an issue, once you’ve found it, click on it. What is the challenge flag?

Correct Answer: THM{INVALID_HTTP_CERT}

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task2:

2.1 What HTTP protocol is being used in the above example?

Correct Answer: HTTP/1.1

2.2 What response header tells the browser how much data to expect?

Correct Answer: Content-Length

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task3:

3.1 What method would be used to create a new user account?

Correct Answer: post

3.2 What method would be used to update your email address?

Correct Answer: put

3.3 What method would be used to remove a picture you’ve uploaded to your account?

Correct Answer: delete

3.4 What method would be used to view a news article?

Correct Answer: get

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task4:

4.1 What response code might you receive if you’ve created a new user or blog post article?

Correct Answer: 201

4.2 What response code might you receive if you’ve tried to access a page that doesn’t exist?

Correct Answer: 404

4.3 What response code might you receive if the web server cannot access its database and the application crashes?

Correct Answer: 503

4.4 What response code might you receive if you try to edit your profile without logging in first?

Correct Answer: 401

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task5:

5.1 What header tells the web server what browser is being used?

Correct Answer: User-Agent

5.2 What header tells the browser what type of data is being returned?

Correct Answer: Content-Type

5.3 What header tells the web server which website is being requested?

Correct Answer: Host

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task6:

6.1 Which header is used to save cookies to your computer?

Correct Answer: Set-Cookie

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Task7:

7.1 Make a GET request to /room

Correct Answer: THM{YOU’RE_IN_THE_ROOM}

7.2 Make a GET request to /blog and using the gear icon set the id parameter to 1 in the URL field

Correct Answer: THM{YOU_FOUND_THE_BLOG}

7.3 Make a DELETE request to /user/1

Correct Answer: THM{USER_IS_DELETED}

7.4 Make a PUT request to /user/2 with the username parameter set to admin

Correct Answer: THM{USER_HAS_UPDATED}

7.5 POST the username of thm and a password of letmein to /login

Correct Answer: THM{HTTP_REQUEST_MASTER}

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —

Happy Learning — Hope this helps you out :)

For in-depth solutions, check this out — https://github.com/neharidha?tab=repositories

-Neharidha Murali

— — — — — — — — — — — — — — — — — — — — — — — — — — — — — — — —
