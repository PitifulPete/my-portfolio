# My Portfolio Website

Welcome to the repository of my personal portfolio website! This project showcases my works and provides means to contact me. It's created with HTML and CSS, and it's designed to be simple, clean, and responsive. 

## Project components

### 1. Header section
The header section displays a picture of me and provides links to my LinkedIn and GitHub profiles.

### 2. About section
The about section introduces me and provides details about my capabilities and motivations.

### 3. Projects section
The project section highlights some of the key projects i've worked on. Each project includes a title, description, and a relevant link.

### 4. Content section
The content section features some of the blog contents i've written or co-written, and a link to my personal substack page.

### 5. Footer section
The footer section contains a copyright notice.

## How to use

1. Clone the repository to your local machine.
2. Customize the content in each section of the HTML files.
3. Modify the CSS files to match your preferred styling.
4. Add more sections if you want.

## How to deploy on Netlify

1. Sign up for a Netlify account if you don't have one.
2. Create a new site on Netlify.
3. Set the build command to your preferred static site generator or leave it blank if it's just HTML/CSS --- that is, if you are maintaining the current structure.
4. Specify the publish directory as the folder containing your HTML files.
5. Deploy your site!

## Caveat

In the projects section, both the project title (h3) and the associated link icon possess typical link capabilities. However, due to the specific implementation using JavaScript to enable clicking on them, they do not inherit the ability to open links in a new tab when right-clicked. 

What am i saying here? If you click on any part of the project title, you can open the link it's associated with. But if you right-click on any part other than the <a> tag, you wil not get the option to open in a new tab. And the reason why is because i had to manipulate other parts to become clickable with JS while the <a> tag is just typical link implementation. 

Why didn't i just do it the normal way? I wanted to maintain a structure i already implemented and simultaneously make the entire project title clickable. Hence, the result. Nothing major, just thought you should know. 

## AOB
Feel free to reach out if you have any questions or need further assistance. Enjoy
