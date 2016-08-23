## ADP Website Guide
You're the webmaster, congrats! Here's the key info you'll use to maintain this site:
### File Structure
The navigation pane on the lefthand side of the website has options for the about, members, rush, contact pages, etc. Each of these nav buttons is linked to a corresponding html file with the same name. The exception is `index.html`, which is the file for the homepage.

### Updating Site Content
Thanks to github, all of these files can be edited in the browser. You can click on a file above and navigate to the edit button to open up a file in the github text editor. Once you're done, click "commit changes" to save, and optionally, write a short description of the changes you made.
To update contact info, edit 'contact.html', etc.

### Adding New Content
To add photos or other media to the homepage, you'll first need to upload the files. Using the 'upload files' button is the easiest way to add files to the repository. To add them to one of the webpages, look how it's done in `index.html` and try to copy that. If the image / content isn't displaying properly, you'll need to change the file permissions to be publically viewable.

### Deleting Content
Simple! But be careful when deleting markup (`<stuff in brackets/>`) because this can change the way the webpage displays.

### Updating email aliases
head over to namecheap.com and login.

####*advanced info* for the curious:
This very simple site is hosted on github.com for free. ADP has registered the domain name at namecheap.com, where we also have a login. The settings for the domain name "adpscolumbia.org" point to github.com servers, which is why the html code you see here loads when you type in `http://adpscolumbia.org`. The `CNAME` file in this repository tells github that the domain name "adpscolumbia.org" is pointing to this code repository.
