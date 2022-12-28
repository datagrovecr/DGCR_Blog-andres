# Creating a Perosnal website
## Developer: Andrés Villalobos Carballo

### Project Name: Personal site
Link to repo:
- https://github.com/AndresV20/vite-personal-site
- https://github.com/AndresV20/astro-site


### Project Function
The purpose of this project is to have an example of a personal site for new developers joining the team, as this will be one of their first projects.


### Specific Task
My task on this project was to create two sites, one that uses only HTML & CSS and a second one that uses Astro and Tailwind to build and style the site.

![Start of personal site](https://raw.githubusercontent.com/AndresV20/Work/f5afbd94592a881f3e9e77dab3d73a5fef7c3065/progress1.png)

### Challenges
The challenges faced during the creation of the first web site were few, however they were mostly related to the styling aspect, for example when adding an image of myself, I struggled with the positioning of the image, I solved this by setting the positioning to absolute and moved to where I wanted it to be on the home page, another challenfe was creating the button that downloads my c.v., because it was the first time that I'd done this, fortunately there's a sufficient amount of documentation that explains well the proper syntax for HTML when you want to add a button that downloads a file, then another challenge came when I decided to style this button, in CSS you can link serveral elements to the same set of rules by adding comas between the elements you'd like to style (header, h1 {style rules}) this helps you have less lines of code because it reuses the style rules already set for several elements the developer would like to look the same, I tried to use the same styling for the c.v. button as the buttons containing my social media links, the result, it didn't style the c.v. button properly, what this did was add the button styling (a small black recatangle) but ignored the styling instruction that removes the link text and makes appear as normal text. The solution, have a separate block of instructions in the CSS file for this button. Another important aspect of this project is that adding vitepress from the start makes it easier to publish to surge later on when the site is done.
Link style text can be seen in the first progress image just above my name.
The challenges for the Astro & TailwindCSS version of the site were interesting in their own way, I believe these were mostly due to the learning curve when using new tools. One of these new challenges was setting up astro, even though the setup in the terminal is more modern than using vitepress, in the setup astro asks you what you want to call the project, if you want to install dependencies, initialize a GitHub repository, what kind of typescript you'd like to implement strict, strictest or relaxed and finally which template you'd like to use, first I chose the one for a personal blog site, but that caused some issues when adding a navigation bar as it would not find the other pages in the dev site, I solved by selecting a template that had a few good practices, is how I believe was called by astro in the set-up process. Another challenge was setting up tailwind in the astro site, tailwind as oposed to raw CSS, needs a config file and a terminal command to be able to run also an input.css file because terminal command creates an output.css from this, where CSS just needs a .css file and the link tag in the html pages you want to be affected by the styles set in the file by the developer. Another challenge that at the time of writting this I'm currently fixing is that when publishing to surge, the browser thinks the output.css file is one of the pages and returns an error 404 not found, also when I ran the npm run build command it got rid of the output.css file for reasons I cannot quite comprehend yet.
### Final Versions
Inspite of these challenges, there is a surge website for the HTML & CSS version of the project. These are some images of the begining of the styling.
![Version 1 of styling]{https://raw.githubusercontent.com/AndresV20/Work/main/progress2.png}
![Final version of styling]{https://raw.githubusercontent.com/AndresV20/Work/main/progress3.png}
![Style Error]{https://raw.githubusercontent.com/AndresV20/Work/main/progress4.png}