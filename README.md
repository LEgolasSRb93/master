# Master rad

## Tema: Implentacija sinhronizacije vremena u namenskim racunarskim sistemima

Uvod ili Synopsis za master rad. Nesto smisleno moze ovde da ide.
**Takodje dodati kod na ovaj repo, ogoljen freeRTOS lwIP sa PTP-om**

Potrebno opisati:

* APstrakt
* Uvod
    - Zasto je bitno da se to radi? [doen, some parts, recheck]
    - Kako se radi? [done, recheck]
    - Sta se postize ovim nacinom rada? [done, reheck]
    - U cemu je poboljsanje u odnosu na prethodne nacine rada? [done, recheck]
* Opis PTP-a
    - Uvod o tome sta je PTP, i nakon opis sta je sve potrebno da bi se skontao i odredio PTP.
    - Opis PTP-a (Precision_Time_Protocol)
        - Opsti opis [done]
        - Opis poruka [done]
        - Opis sinhronizacije [done]
        - hardverski TSU -> Zasto je bitno da i hardver podrzava sve? []
        - Slike []
    - Opis OSI modela [done] -> mora malo da se doradi, ubaci slike
    - Opis TCP/IP modela [done] -> proveri greske, ubaci slike
* Opis operativnog sistema
    - FreeRTOS opis [done, basics]
    - lwIP opis [done, check for more detail]
* Hardverska implementacija
    - Zasto je odabran ovaj hardver? [done]
    - Koje su dobre strane koriscenja? [done]
    - Hadverska ubrzanja? [done]
    > [DONE] -> proveren tekst, primecene sitne greske koje treba ispraviti.
    > [HINT] -> pogledati jos jednom datasheet i dodati delove o brojanju sekundi, i primerima za podesavanje vremena.
* Softverska implementacija
    - Nacin na koji je odradjeno sve []
* Zakljucak



### Linkovi koji su korisceni pri pisanju:
- https://www.wikiwand.com/en/Precision_Time_Protocol
- https://standards.ieee.org/findstds/standard/1588-2008.html
- https://www.rtaautomation.com/technologies/ieee-1588/
- https://www.webcitation.org/5qaJpYqCH
- https://www.freertos.org/Documentation/161204_Mastering_the_FreeRTOS_Real_Time_Kernel-A_Hands-On_Tutorial_Guide.pdf
- https://www.wikiwand.com/en/FreeRTOS
- http://lwip.wikia.com/wiki/LwIP_Wiki
- https://savannah.nongnu.org/projects/lwip/
- http://ww1.microchip.com/downloads/en/DeviceDoc/SAMA5D27-SOM1-Kit1-User-Guide-DS50002667B.PDF
- https://www.rtaautomation.com/technologies/ieee-1588/

Bookmark folder **Master** also!
