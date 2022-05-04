TO EDIT: 
1. open index_backup.html 
2. edit the file
3. use an online tool (eg. https://html-to-pug.com/) to convert html to pug
4. copy the pug code to src/pug/index.pug replacing the old content
5. (opitional) use npm start to see the change
6. use npm build
7. use node scripts/pages.js damorosodaragona master to deploy the change 


TO EDITO COLOR:
1. go to src/scss/variables
2. open \_colors.scss
3. edit the section "// Override Bootstrap color system" adding or modifyng the color
4. change the line $primary: $blue4; inserting the new color as value of $primary

MULTIPAGE SYSTEM:
1. when you create a new page copy all the code from a previuos page inserting <head> and <body> from the start at least to the end of <Navigation bar>. Suggestion is to copy all the page and modify the section after the end ot the navigation bar. 
2. create a new .pug file with the same name of the .html file, insert the pug code (see step 3 of the section "TO EDIT")
3. start and deploy following step 6 and 7 of the "TO EDIT SECTION"