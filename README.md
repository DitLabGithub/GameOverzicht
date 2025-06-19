# GameOverzicht
Overzicht van alle games die we hosten met een korte beschrijving.

## Exam day disaster:

-Sean's versie met inventory
https://ditlabgithub.github.io/ExamDayDisasterWEBGL/

-Amber's versie zonder inventory
https://ditlabgithub.github.io/ExamDayDisasterAmberFinal/

## Retro Computer Sim:

-Laatste versie door Constantin 
https://ditlabgithub.github.io/RetroComputerSim/

## SSI Game door Raul:

-Laatste versie (wel development versie)
https://ditlabgithub.github.io/SSIGame/

## SSI serious game Project Kiosk:

-Laatste versie (wel development versie)
https://ditlabgithub.github.io/Projekt-Kiosk/

# Working method

Throughout the internship/graduation period we will have multiple demos where we want to see the progress of the games. We want the prototype to be showcased through a WebGL build updated to your progress. This working method showcases how you should set this up.
First make sure that in Unity you have downloaded and installed the option to build to WebGL. the platform should be active like showed in this picture.
 
![image](https://github.com/user-attachments/assets/0041a607-0f52-4184-9118-44619d331300)

To be able to build and host on GitHub pages you should use the correct player settings. To make sure you are able to host your WebGL build through GitHub pages you will have to change the following settings. 
- Set the Compression format to disabled
- Set the Decompression Fallback to true
- Set Debug Symbols to off
Your player settings for the WebGL build should look something like this. We dont use Brotli or Gzip because these compression formats are not supported by GitHub pages hosting of a WebGL build. So make sure you put the compression method on Disabled.

![image](https://github.com/user-attachments/assets/7f367be3-3a8c-498c-a878-0e25c333a97d)

Once you have this setup you are ready to build. 
For the re-occuring demos where you will be showcasing the progress of the game we will first need to setup the GitHub repository. First start off going to the GitHub website and make a new repository on the provided DIT-Lab organisation. Once you clicked on make a new repository you put your repository name (NameOfGameWEBGL) and set the repository to public (nessecary for free hosting) optionally add a README file and then click on create repository. 

Once your repository is created clone the repository to your desktop(local). When you have this setup you will have a empty github folder setup on your desktop and you are ready to build. Continue in Unity and make sure you copied the settings given previously. When you click on build it will give you the option to select a destination for the build folders. Choose the repository that you cloned for the WebGL page. After you build you will see all of the changes in GitHub desktop but dont push yet. Navigate to the github folder then left click to add a .txt document and name it .nojekyll and save it (makes sure that GitHub reads the folders correctly). Now on GitHub desktop you can push everything. Then on GitHub desktop(locally) create a branch from main and call it gh-pages and commit and push this branch. Once you have created this branch you publish and push this and then you are onto the next step and your folder should look something like this.

![image](https://github.com/user-attachments/assets/79675d44-b37b-4636-8948-526ea80e32e0)

Now go to the Github page and navigate to the settings of your respository and go to Pages on the left sidebar. Set the branch to your gh-pages branch and set the folder to root and then save this. After a minute or so you will see a link which indicates that your page is live. 

![image](https://github.com/user-attachments/assets/a18a9b3a-639c-46a9-842c-0bb30189aaf6)

Because you have all of the files setup your game will be played in the browser.
Note: When you are ready to demo build to the same folder and overwrite the files. This will ensure that it showcases the most recent build/progress.  

## Concepten

- ParadiSSIo (credits: Christobal Joven Lee)

![image](https://github.com/user-attachments/assets/ef09b13a-25d8-4f97-a33a-fbae61e7fa3f)

- Project Kiosk (credits: Christobal Joven Lee)

![image](https://github.com/user-attachments/assets/ce14b9e2-7321-45d4-a045-3959b29ddac2)

- Digital Dimploma Disaster (credits: Christobal Joven Lee)

![image](https://github.com/user-attachments/assets/70967eeb-6e43-4f84-ae1d-161a57fcae19)

- Diploma Day Disaster (credits: Christobal Joven Lee)
  
![image](https://github.com/user-attachments/assets/7ea254e5-a9ef-45ef-bf48-b47c46b2155e)

- Nation of One (credits: Razvan Andrei Petcu)
  
![image](https://github.com/user-attachments/assets/50cc6365-1684-4e71-a05c-a5a84a84fa9f)

- Data detective (credits: Razvan Andrei Petcu)
  
![image](https://github.com/user-attachments/assets/fd958f07-52bc-42bd-bd86-25f3340b1c16)

- Cocktail Master (credits: Razvan Andrei Petcu)
  
![One pager Cocktail masters](https://github.com/user-attachments/assets/982c8351-5392-4497-8ef8-b38963e10f76)

- Kernel (credits: Razvan Andrei Petcu)
  
![One pager Kernel](https://github.com/user-attachments/assets/144b660a-ba49-4e9e-8693-8a14c32ac9b6)
  
- Honorbound (credits: Razvan Andrei Petcu)
  
![One pager Honorbound](https://github.com/user-attachments/assets/06b9983d-c815-4457-80e8-5c7aafe54827)
 
- Reclaiming me (credits: Garon Bos)
  
![image](https://github.com/user-attachments/assets/276cb5b0-6c0b-42d9-8263-4a561b66a4e8)










