# Simple Turbo / Hotwire App

- This application basically has one model with very few peices of data. 
- It requires Redis, Turbo, and Hotwire.  
- This allows it to work within frames and only replace paritals of the frame when working with data.  Also all changes to the database are broadcast instantly.  

# To Run 
- Clone this repo. 
- Make sure you have docker and docker-compose.  
- In the command line `docker-compose up -d`
- Travel to Port 3002 
- You may have to exec into the container and run `rails db:create && rails db:migrate` to get the database setup. 
- Go to the posts path and play around. 
