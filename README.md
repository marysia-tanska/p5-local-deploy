1. Install nvm: <br>
https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/<br><br>
2. Go to the terminal and use nvm to install Node.js:<br><br>
https://www.linode.com/docs/guides/how-to-install-use-node-version-manager-nvm/#use-nvm-to-install-node<br><br>
3. In the terminal, go to {YOUR_PROJECT_PATH}, for example:<br>
```cd C:\coding_projects\personal_website```<br><br>
4. Install Browser Sync (a package that watches changes in your file and ```npm install -g browser-sync ```<br><br>
5. Copy the ```watcher.js``` file to ```{YOUR_PROJECT_PATH}/dev_files```<br><br>

6. From the terminal, run:<br>
```node ./dev-files/watcher.js```<br><br>

7. Now, copy the ```index.html``` into {YOUR_PROJECT_PATH}. Put your ```sketch.js``` and any other files into the same folder and make sure the file paths are correct. Use relative paths. For example for ```{YOUR_PROJECT_PATH}\images\image01.jpg```, a relative path would be ```.\images\image01.jpg```.<br><br>

8. If you want to, you can connect your project to GitHub, and/or deploy it using Netlify. Netlify provides clear instructions for GitHub integration.<br>https://www.netlify.com/