+++
date = '2026-09-30'
draft = false
title = 'Blog'
+++

## Steps used to make this project

- Install Hugo on windows using "winget install Hugo.Hugo.Extended"

- Verify Hugo version to see it was installed correctly "winget list Hugo"

- set "cd C:\Users\M2604113\OneDrive - QMMC\Escritorio\Leo\practice\Hugo" as the location where I will create my project

- create a project using "hugo new site mywebsite_sap"

- Go inside "mywebsite_sap" with cd

- Go inside .toml File and change the title

- Created the about page using "hugo new content about.md", customized it, learned what "#", "-" and "draft" means in Hugo context

- Create the Hugo server using "hugo server"

- Get the localhost URL that appears on powershell, and enter it on a web browser in order to be abble to see it

-  Create the layout "single.html", here I learned that you kind of define the Hugo structure into the template by using "{{.}}", this basically works as a place holder for your content folder page. single.html is the html structure

- Adding the CSS into static / css / style.css

- Create the rest of the webpages

- Create the index, in order to have navigation tab