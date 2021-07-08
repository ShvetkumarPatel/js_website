## Server Configuration

1. Edit ```server/app/config/env.js``` file with database configuration.
2. Install Node.js
3. Go to server folder
4. Install dependencies ```npm install```
5. Run server ```node server.js```
6. Edit client url in ```client/upload.html```

****************************
REQUIREMENTS
****************************
Create a website about the touristic attractions of the country of your choice. That country must be approved
by me; talk to me on Zoom or send me a Mio to get it approved. The website:

(1)
Must have at least 6 pages. Each page must contain at least one picture related to your country and
one paragraph discussing that country. At least one page must contain a video, or a link to a video,
which discusses that country

(2)
Must be “stylish”. Nothing too fancy; at least go for matching colors and avoid having plain black text
on a white background. In other words, make your website look like a professional website that you would find on the Internet. This includes having a consistent look and disposition of elements from one page to another.

(3)
Must allow the user to add their own pictures, one at a time, onto a dedicated section of the website.
Whatever picture is uploaded by the user will be checked to see if its resolution is too large. If the picture is too large, it will not be added onto the website, or to the database (see below). 
If there are too many pictures for a page, the user should be able to scroll down to look through the pictures.

(4)
Must save its pictures (uploaded by the user or not) into an SQL database by using Node.js (with or without Express.js).
