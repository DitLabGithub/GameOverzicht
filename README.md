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
https://ditlabgithub.github.io/SSIProjectKiosk/



# Werkwijze

Maak een nieuw project aan op github met readme, clone de repo via git clone -repo-naam-. Maak in unity een WebGL build en vink compressie aan als disabled. Zie hieronder de documentatie en omschrijving. Geen compressie is makkelijker te hosten dan b.v. Brotli of Gzip, al zijn die wat kleiner. 

In het plaatje hieronder is Gzip aangevinkt. Dit moet voor ons disabled zijn:

![image](https://github.com/user-attachments/assets/237bf3e2-dea1-4537-990f-1b52f8f24025)

 
Unity - Manual: Deploy WebGL application
 

https://docs.unity3d.com/Manual/webgl-deploying.html


 
## Description:


Gzip
	
This is the default option. Gzip files are bigger than Brotli files, but faster to build, and natively supported by all browsers over both HTTP and HTTPS.


Brotli
	
Brotli compression offers the best compression ratios. Brotli compressed files are smaller than gzip, but take a longer time to compress, which increases your iteration times on release builds. Chrome and Firefox only natively support
 Brotli compression over HTTPS.


Disabled
	
Disables compression. Use this option if you want to implement your own compression in post-processing scripts. You should also use it if you plan to use static compression on the hosting server.


## Vervolg

Als deze build geslaagd is de folders Build, TemplateData en de index.html overzetten naar de projectmap. Commit en push deze. Maak nu een branch aan die gh-pages heet vanaf main en update de readme. Commit en push. Stel in Github als default branch nu de gh-pages in. Dit is een speciale branchnaam die Github laat weten dat het project gehost moet worden. Het project wordt nu via githubpages gehost op https://ditlabgithub.github.io/ met je projectnaam. Bijvoorbeeld https://ditlabgithub.github.io/ExamDayDisasterWEBGL/

Bij een nieuwere versie vervang je wederom de files vanuit de uitgepakte WebGL zip, commit en push. Dit is de standaard manier waarop we ook demo's willen zien van studenten en meteen kunnen hosten.

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










