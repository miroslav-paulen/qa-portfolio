1, TC001 Registrácia
kroky: Registrácia -> odhlásenie -> Login s platnými údajmi
očakávanie : Zobrazené používaťelské meno, prihlásený stav

2, TC002 Zadanie nesprávneho hesla
kroky : zadanie platneho login a neplatného hesla
Oč : chybová hláška nesprávne heslo, zostanem neprihlásený

TC003 Neexistujúci užívatel
kroky : zadanie nesprávneho login a nesprávneho hesla
Oč : chybová hláška o neexistujúcom používatelovy. zostanem neprihlásený

4, TC004 prihlásenie s práznimi polami
kroky : pokus o prihlásenie sa s nevyplnením login a heslom
Oč : chybová hláška zadajte login/heslo, zostanem odhlásený

5, TC005 rôznorodé prihlasovanie
kroky : prihlasovanie pomocou správneho login s velkými písmenami
oč : prihlásenie úspené -> stav prihlásený

6, TC006 refresh stránky
kroky : prihlásenie -> F5/ refresh stránky
oč : zostať prihlásený aj po obnovení stránky

7, TC007 Zatvorenie stránky, automatický login
kroky : byť prihlásený -> zavrieť stránku -> otvoriť stránku
oč : po otvorení stránky byť odhlásený na domovskej stránke

8, TC008 Valídna registrácia
kroky : vyplniť všetky povinné a nepovinné polia platnými hodnotami
oč : úspech keď -> možnosť registrovať sa novým účtom

9, TC009 Duplikátne prihlasovacie meno
kroky : pokus registrovať sa už použitím prihlasovacím menom
oč : chybová hláška (username already exist ) alebo ekvivalent, žiaden účet nevznikne

10, TC010 minimálna dĺžka hesla
kroky : pri registráci skúsiť použiť heslo o 1 menej ako je minimum
oč : chybová hláška o minimálnej dĺžke hesla. účet nevznikne

11, TC011 formát mailu
kroky : pri registrácii použiť nesprávny mail bez @ (napr efg.123.com)
oč : chybová hláška nesprávny formát mailu (alebo ekvivalent ), účet nevznikne

12, TC012 obnovenie hesla
kroky : pri prihlasovaný uviesť možnosť zabudnuté heslo -> zadať mailovú adresu priradenú k účtu -> potvrdiť
oč : nové heslo bolo odoslané na túto mailovú adresu
