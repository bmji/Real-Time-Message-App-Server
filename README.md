# Project #4: Messaging App

## Project Idea - Base plan
I have decided to use React for the front-end and Express for the back-end for this project. The main idea was to allow people to communicate with each other within an exclusive room. There would be a main location of some sort which would have several other private rooms that a user can enter by clicking into that room. Upon entering the room, the user would see a massaging box along with other icons that would enable video and voice chat. It would also display the members that are currently in the selected room as well as the room that they had chosen.

## Project After Review
In order to allow users to communicate online, I was required to utilise Socket.io, an event-driven library for real-time web application. I was not able to implement a main room that consisted of multiple other rooms, although I was able to allow multiple users to make a room by creating an ID. My idea of allowing video chat was also scrapped due to the time-limitation. The project ended up being a lot more simple that I was hoping, but I am very happy that I managed to get the main function working; allowing multiple users to chat to one another.

## Biggest Struggle
The biggest struggle I faced was having to learn Socket.io. Because Socket.io was so new to me, it was hard for me to connect that and what I had already knew. I was required to watch multiple videos and read the documentation, which took a lot longer than I was hoping. I kept running into issues where the connection between the client side and server side wasn't recognising each other and being able to get my project working took a lot of trial and error.

## Unsolved Issues
One thing I have noticed and was not able to fix was that if two users joined with the same name, they would be recognised as the same person in the chat.

## Cool Tech
There is not much to my project as it is a very simple messaging app, but from my own opinion, I believe that Socket.io is one of the coolest (and only) tech that I have implemented into my project.

## Project Link
Feel free to use my React app to communicate with other members that use the same network!

Link to my app: <a href="https://messenger-app-alicia.herokuapp.com/">Here</a>