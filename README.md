# Wedding Website
A beautiful, feature rich, device friendly wedding website.  
_See [wedding.rampatra.com](http://wedding.rampatra.com/) for a demo. Use invite code `271117` to RSVP._

# Highlights
1. Slick and fully __responsive__ design.
2. __RSVP feature__ which directly uploads data to a Google sheet.
3. __Receive email alerts__ when someone RSVPs.
4. __Add to Calendar__ feature which supports four different calendars.
5. __Book Uber__ button lets guests book a cab to the venue with just a single tap.
6. A nice __Youtube video__ showing your venue.
7. __Google Map__ showing your venue's location.
8. Start and run the website __completely free__. No hosting, backend server, or database required as you can use
   [GitHub Pages](https://pages.github.com/) to host and Google sheets (with the help of Google scripts) to store RSVP
   data.

# Getting Started
1. LINUX - Install NVM (Node Version Manager) from [here](https://github.com/nvm-sh/nvm)
2. WINDOWS - Install NVM (Node Version Manager) from [here](https://github.com/coreybutler/nvm-windows/releases)
3. `$ git clone https://github.com/joaobortotcadore/wedding-ll.git` - clone this project to your computer
4. `$ cd wedding-ll` - go inside the project directory
5. `$ nvm install lts` - install the latest LTS version of Node.js
6. `$ nvm use lts` - use the latest LTS version of Node.js
   - For WINDOWS, you may need to run the following commands in PowerShell as an Administrator:
      - `$ Get-ExecutionPolicy -List`
      - `$ Set-ExecutionPolicy Unrestricted -Scope CurrentUser`
      - `$ Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`
      - `$ Get-ExecutionPolicy`
7. `$ npm install -g gulp-cli` - install gulp globally
8. `$ npm install` - install dependencies
9. `$ gulp` - compile sass to css, min
10. That's it, open `index.html` file on your browser by just double-clicking on it.

# Documentation
I have written a 
[blog post describing all the features of this wedding website](https://blog.rampatra.com/wedding-website) and how to
customize each of them according to your needs.

# Usefull online tools
[Photopea](https://www.photopea.com/) - Online Photoshop editor.
[Flat Icon](https://www.flaticon.com/br/) - Free icons for website.