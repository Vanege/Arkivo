Elsendaj platformoj kiel Youtube ofte havas butonon kiu permesas ŝanĝi la rapidecon laŭ kiu video estas montrata. Tiu funkcio estas tre utila kiam la enhavo mem estas iom malrapida aŭ enuiga. Tiel oni ricevas pli da informoj pli rapide.

Sed okazas tre ofte ke elsendaj platformoj ne disponigas tian butonon. Tiam oni povas perdi multe da tempo kaj entute ne plu voli spekti. Estas domaĝe por ĉiuj.

Sed bonŝance, ekzistas solvo kiu funkcias por la plimulto de retejoj:

La elementoj en retejo estas difinitaj per lingvo kiun oni nomas "HTML" (HyperText Markup Language), per la programistaj iloj ("Developer tools") de onia retumilo, oni povas vidi la HTML. La maniero malfermi la programistajn ilojn dependas de la retumiloj, sed ĉiuj komunaj retumiloj posedas ilin je.

Per la inspektilo ("Inspector") ene de la programistaj iloj, oni povas scii kiuj elementoj produktas kiuj partoj de la retejo.

Plejofte, video estas montrita en <video>-elemento. Se tio estas la okazo, tio signifas ke oni povas plirapidigi la videon (eĉ se la retejo ne defaŭlte proponas la eblon).

Malfermu la komandlinion de la retumilo ("Console") kaj tajpu tiun komandon:
```
document.querySelector("video").playbackRate=1.5
```
Tio altigos la rapidecon de montrado de la video per 50%. Se vi volas altigi nur de 25%, skribu 1.25 anstataŭ 1.5. Se vi volas malrapidigi de 25%, skribu 0.75. Oni tiel povas atingi rapidecojn kiuj ne eblas defaŭlte.

Mi uzas tiun teknikon ekzemple por NLZiet (la "Netflix" de televidaj programoj en la Nederlanda kaj Belg-nederlanda televido).

Se vi ne volas ĉiam tajpi la komandon kiam vi volas plirapidigi, vi povas uzi la teknikon de paĝoskripto ("Bookmarklet"). Pri tio mi jam skribis artikolon: https://vanege-esperanto.blogspot.com/2023/11/0070-pagoskriptoj-por-rapide-fari-ion.html