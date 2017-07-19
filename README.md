# memorygame-parent

A program 7-es és 8-as Javával egyaránt futtatható Wildfly 9 ás 10 szerveren.

In the Wildfly server, in the standalone/configuration/standalone.xml file change the servlet-container XML element so that it has the attribute allow-non-standard-wrappers="true"!

Adatbázis:
Oracle 10 XE
Először hozzuk létre a táblákat a usersResultCreate.sql futtatásával.
Ez pl. SQLDeveloperben egyben lefuttatható,
de pl. az Oracle 10 Xe böngészős adatbáziskezelőjében a "/" jelekkel elválasztott részeket egyenként kell futtatni.
Utána az alapadatokat a csv (először a users, majd a result) file-okból importáljuk,
vagy a usereket regisztráció útján is létre lehet hozni.

Jó játékot!
