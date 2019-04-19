# *SQUARE WHO? Let's Build a Portfolio Site with HTML/SCSS*
#### Hosted by the [Computer Science Education Club](https://my3.my.umbc.edu/groups/cs-ed) and [UMBC](https://www.umbc.edu/)
##### Date: April 19, 2019
##### Time: 12pm to 2pm
##### Location: ITE 231
##### What to Bring: Your Personal Laptop
#
#
---
# WORKSHOP AGENDA
#
## __Hour 1__ 
### Part 1a: Setting Up  
1. [Download Node.js](https://nodejs.org/en/download/).
2. [Download Git](https://git-scm.com/downloads).
3. [Download Atom IDE](https://flight-manual.atom.io/getting-started/sections/installing-atom/).
4. [Create a GitHub account](https://github.com/) and make sure you are logged in. 
5. Now navigate to the [workshop's Git repository](https://github.com/zleckron/cseduclub) where the starter files exist.
6. _Fork_ the repository to your account by pressing the "Fork" button in the upper right-hand corner.
7. *__IMPORTANT:__* Rename the newly forked repository to `username.github.io`, where `username` is your username on GitHub. No exceptions.
8. Copy to clipboard the url to your renamed Git repo i.e. `https://github.com/username/username.github.io` 
9. Now from an easily accessible place on your computer (i.e. "My Documents"), create a new folder and name it "Websites" (you can name it whatever you want but we'll use "Websites" for consistency). 
*__Protip:__ avoid having spaces in your folder names; instead use a dash or underscore.*
10. Open up a terminal. On MacOS, open the pre-installed app called Terminal. On Windows, open the pre-installed app Command Prompt.
11. In the terminal, execute each command below, line by line. Replace `username` with your GitHub username.
#
```sh
$ cd into/your/Websites/folder
$ git clone https://github.com/username/username.github.io
$ cd username.github.io
$ npm install
$ npm rebuild node-sass
$ npm start
```
11. Open the Atom IDE that you downloaded in step 2. From your Atom IDE, open `username.github.io`.
12. [Add the atom-live-server package] by visiting this link (https://atom.io/packages/atom-live-server) and clicking the green "Install" button.
13. In Atom, enter `ctrl-alt-l` with your keyboard (`ctrl-option-l` on MacOS).
14. go to `locahost://3000` in a browser of your choice (if one doesn't open up for you after step 13) and marvel at what is being rendered from your starter code. __DON'T WORRY -__ you will get a chance to customize the site later on in the workshop. But first ...
#
### Part 1b: Brief Overview of HTML & SCSS
**_Zoee, I will let you do this part to start and I can add/modify it afterwards. Obviously we can revise it again accordingly after a few dry runs._**
#
#
## __Hour 2__ 
### Part 2: Customize with [Bulma](http://bulma.io)
1. Now return to your Atom IDE and follow along with the instructor in this __*live coding*__ session. The goal here is to get you familiar with Bulma's file structure as well as Bulma's syntax for using its various components.

Once you are more or less happy with how your site looks in `localhost://3000`, it is now time to "push" these new changes up to your newly created GitHub account. 
2. Open up a __second__ terminal and run the following commands.
#
```sh
$ cd into/your/Websites/folder
$ git status
$ git add --all
$ git commit -m "Initial commit"
$ git push -u origin master
```
3. … and you're done! Fire up a browser and go to `https://username.github.io`. Do a little dance to celebrate your very first website!
#
_Refer to [GitHub Pages](https://pages.github.com/) if you want to change the url to a custom domain name of yours, among other things._
_And don't forget to check out all the other cool links for your benefit. They can be found in the workshop slides that will be emailed to you. **You're Welcome :)**_