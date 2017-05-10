---
layout: post
title: BlocChat
thumbnail-path: "/assets/images/blocchat.png"
short-description: A real-time chat application.
---

{:.center}
![]({{ site.baseurl }}/assets/images/blocchat.png)

## Explanation
Bloc Chat is a minimal chat application that allows users to send messages in real time built with AngularJS.

## Problem
My main objective of this project was to create a chat application that allows the user to create rooms (that update in the view), send messages, and create a username to associate their messages with.

## Solution
By using UI Bootstrap, Firebase and Angular cookies I was able to accomplish all of the above. UI Bootstrap modals facilitates username and room creation while Firebase stores all the created rooms and sent messages.  Also, Angular cookies saves the username so the user only has to enter it once.

## Results
The result is a fully functioning chat application that provides the user with a timestamp of their the messages were sent.  Firebase also holds all memory of the messages sent and rooms created.

## Conclusion
I am pretty satisfied with how the project turned out.  The only thing I would have changed was the styling; although, I find it simple and charming I would've liked to clean it up a bit more.
