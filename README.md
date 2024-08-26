# GameOverzicht
Overzicht van alle games die we hosten met een korte beschrijving.

Exam day disaster:

-Sean's versie met inventory
https://ditlabgithub.github.io/ExamDayDisasterWEBGL/

-Amber's versie zonder inventory
https://ditlabgithub.github.io/ExamDayDisasterAmberFinal/

Retro Computer Sim:

https://ditlabgithub.github.io/RetroComputerSim/

SSI Game door Raul:

https://ditlabgithub.github.io/SSIGame/


# Werkwijze

Maak een nieuw project aan op github met readme, clone de repo via git clone <repo-naam>. Maak in unity een WebGL build en vink compressie aan als disabled. Zie hieronder de documentatie en omschrijving. Geen compressie is makkelijker te hosten dan b.v. Brotli of gzip, al zijn die wat kleiner. 

In het plaatje hieronder is gzip aangevinkt. Dit moet voor ons disabled zijn:

![image](https://github.com/user-attachments/assets/237bf3e2-dea1-4537-990f-1b52f8f24025)

 
Unity - Manual: Deploy WebGL application
 

https://docs.unity3d.com/Manual/webgl-deploying.html
	
Description:


gzip
	
This is the default option. Gzip files are bigger than Brotli files, but faster to build, and natively supported by all browsers over both HTTP and HTTPS.


Brotli
	
Brotli compression offers the best compression ratios. Brotli compressed files are smaller than gzip, but take a longer time to compress, which increases your iteration times on release builds. Chrome and Firefox only natively support
 Brotli compression over HTTPS.


Disabled
	
Disables compression. Use this option if you want to implement your own compression in post-processing scripts. You should also use it if you plan to use static compression on the hosting server.
 
Als deze build geslaagd is de folders Build, TemplateData en de index.html overzetten naar de projectmap. Commit en push deze. Maak nu een branch aan die gh-pages heet vanaf main en update de readme. Commit en push. Stel in Github als default branch nu de gh-pages in. Het project wordt nu via githubpages gehost op https://ditlabgithub.github.io/ met je projectnaam. Bijvoorbeeld https://ditlabgithub.github.io/ExamDayDisasterWEBGL/

Bij een nieuwere versie, vervang de files weer vanuit de uitgepakte WebGL zip, commit en push. Dit is de standaard manier waarop we ook demo's willen zien van studenten en meteen kunnen hosten.
