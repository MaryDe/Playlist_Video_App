** FINAL PROJECT **

Music Video App

Answer the following questions as you did in your Group Project:
This app allows user to sign-in to directly using their google account by by clicking the sign button because of passport google OAuth API and the youtube API that allows them to like a youtube video

Specfic goals, target audience to solve
This is to explore myself in using different API by following documentation and video learning. Also to enhancement further of knowledge and backend and frontend and databases model. Revesiting the our previous assigments bring more confident in me to enhance further on my skill level. The app is mean for beginners developers who still need broaded their knowledge in routing and database

In another block, answer the following:
-What is your business model? 
The business model of google and you tube is ecommerce 
Where is your revenue coming from?
From user who share and upload thiers, subscribe other user's chanel and make monetizing their videos.
-What are the costs of your business?
website maintenance and google paid advertisement to promote the app

Market research:
With the diversification and increased sophistication of the small business, the marketplace is expanding in the area of e­commerce.

Brief Specification and design:
The app has sign-in button the redirect the user to their personal gmail account. It has a profile page that allows the user to like a youtube video playlist 
Table Relations 
User.hasMany(Media)

Media.hasMany(Likes)
Likes.belongsTo(Media)

User.hasMany(Likes)
Likes.belongsTo(User) 


Technologies
Passport strategy for authenticating with Google using the OAuth 2.0 API.
Youtube Playlist Info is a library that fetches all the information for the songs within a playlist then returns them as one big array
JavaScript / Node / Express
Pug/JQuery/Bootstrap for frontend design
Node JS to build the app
Sequelize for table model setup 
Postgress to store the data

Timeline and Milestone of Project
(9-10-12)  watch and reads API documentation and learning tool videos
(11-12-12) plan the layout, pages and design of the playlist_ap
(13-14-12) write the actual program for backend functionalities
(15-16-12) test the functional for finalization 

