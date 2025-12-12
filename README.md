### Varsion A (quick)

1. Download the project from GitHub:<br> https://github.com/marysia-tanska/p5-local-deploy <br><br>
2. Install VSCode and open the project folder:<br>https://code.visualstudio.com/ <br><br>

3. Install the Live Server extension and run it in the project folder.<br><br>

4. Now, replace the ```star_sketch.js``` and ```star.js``` files with your JS files, and adapt paths in ```index.htm```. Upload any additional files if needed. Adapt ```index.js``` and ```styles.css``` as you like. Use relative paths. For example for ```{YOUR_PROJECT_PATH}\images\image01.jpg```, a relative path would be ```.\images\image01.jpg```.<br><br>
 
5. If you want to, you can connect your project to GitHub, and/or deploy it using Netlify. Netlify provides clear instructions for GitHub integration.<br>https://www.netlify.com/<br><br>
**NOTE: To publish on Netlify from GitHub, your project should be on GitHub.com, NOT git.arts.ac.uk!**<br><br>


### Version B (more industry-standard, good for complex projects):
1. Download the project from GitHub:<br> https://github.com/marysia-tanska/p5-local-deploy <br><br>
2. Install VSCode and open the project folder:<br>https://code.visualstudio.com/ <br><br>

3. Install nvm: <br>
https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/<br><br>
4. GInstall Node.js and npm through a desktop installer or via terminal:<br><br>
https://nodejs.org/en/download<br><br>
5. In the terminal, go to {YOUR_PROJECT_PATH}, for example:<br>
```cd C:\coding_projects\personal_website```<br><br>
6. Install Browser Sync (a package that watches changes in your file and ```npm install -g browser-sync ```<br><br>
7. Copy the ```watcher.js``` file to ```{YOUR_PROJECT_PATH}/dev_files```<br><br>
8. From the terminal, run:<br>
```node ./dev-files/watcher.js```<br><br>

9. Now, replace the ```star_sketch.js``` and ```star.js``` files with your JS files, and adapt paths in ```index.htm```. Upload any additional files if needed. Adapt ```index.js``` and ```styles.css``` as you like. Use relative paths. For example for ```{YOUR_PROJECT_PATH}\images\image01.jpg```, a relative path would be ```.\images\image01.jpg```.<br><br>
 
10. If you want to, you can connect your project to GitHub, and/or deploy it using Netlify. Netlify provides clear instructions for GitHub integration.<br>https://www.netlify.com/<br><br>
**NOTE: To publish on Netlify from GitHub, your project should be on GitHub.com, NOT git.arts.ac.uk!**
