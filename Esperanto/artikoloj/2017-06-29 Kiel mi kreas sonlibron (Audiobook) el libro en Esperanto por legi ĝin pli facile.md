Tiu metodo validas por Linux. La metodo por aliaj operaciumoj estas simila.


Ekzemplo de sonlibro kreita.

Libroj ofte estas maloportunaj. Ili estas kostaj, pezaj, kaj postulas uzadon de oniaj manoj. Elektronikaj libroj estas iom pli bonaj, tamen oni devas daŭre teni sian poŝtelefonon, ĝis kiam ne plu restas baterio.

Mi preferas sonlibrojn. Mi povas aŭskulti ilin kiam mi provas dormi, kiam mi manĝas, kiam mi estas en veturiloj (legi en veturiloj naŭzigas min). Mi povas simple fermi miajn okulojn kaj koncentriĝi pri la situacio rakontita.

Bedaŭrinde, ekzistas preskaŭ neniu sonlibro en Esperanto. Estus bone se iu kreus ilin per sia propra voĉo. Tamen ekzistas eblo: uzi Texto-Al-Voĉan (Text To Speech) programon. La plej populara kiu estas senpaga estas eSpeak, kaj mi montros al vi kiel mi uzis ĝin por krei sonlibron.
## Trovi libron (aŭ gazeton) en Esperanto

Ekzistas pluraj retejoj kie oni povas trovi senpage tekstojn en Esperanto. Tamen la plej rekta solvo estas unue trovi la nomon de la libro, kaj poste uzi serĉilon kiel Google, kiu povas rekte trovi la dosieron.

    Claude Piron
    Bitarkivo
    Bitoteko
    Scienca kaj Teknika Esperanto-Biblioteko
    Librejo en Facebook
    Librejo de Esperantofre
    Librejo de Cindy McKee
    Librejo de i-esperanto
    Project Gutenberg
    Esperanto.us

## Prepari la tekston

Mi provas trovi version en .html de la libro. Se nur versio en .pdf troveblas, mi verŝajne bezonos prepari la tekston, por ke ĝi estos bone legita de la programo. Kiel ekzemplon, mi prenos la verkon “La Bona Lingvo” en .pdf (eĉ se versio en .html ekzistas) por montri al vi kiel mi preparas tekston. La .pdf estas trovebla ĉi tie: http://esperanto.org.uk/eldonoj/piron/tekstoj/La_bona_lingvo.pdf

Unue, mi kopias la tekston al Sublime Text. Sublime Text estas io kiel Notepad de Microsoft, kiu estas simpla ilo por krei kaj redakti tekston. La teksto de la libro devas unue esti en la formato .txt.

Ĉu vi vidas la nombrojn 1 2 3? Ĉiu nova nombro estas nova linio. Por ke la teksto estu pli facile legebla, mi volas ke ĉiu alineo estu sur unu linio, kaj ke estu malplena linio inter alineoj. Bedaŭrinde, la formato .pdf “kreas” novan linion kiam la linio havas pli ol 78 karakteroj.

Por atingi tion, mi uzas plurajn regulajn esprimojn. Vi ne bezonas kompreni ilin kadre de tiu artikolo, sed estas tre utila scii povi fari tian aferon, kiam oni bezonas trakti tekstojn. Sublime Text ebligas uzi regulajn esprimojn post premo de Ctrl-H.

Bone. Post kelkaj permanaj kontroloj (ĉiu teksto havas siajn strangaĵojn), la teksto estas preta por esti legita. Mi registras ĝin en aparta dosierujo sub la nomo La_Bona_Lingvo.txt.

## Uzi eSpeak

Instali eSpeak en Linux Ubuntu estas ege simpla. Mi simple bezonas malfermi komandlinion, kaj tajpi tiun komandon: sudo apt install espeak

En la retejo de eSpeak troviĝas paĝo pri kiel uzi ĝin.

Jen la tuta komando, kiun mi devas tajpi:
espeak -veo -f La_Bona_Lingvo.txt -s 125 -g 7 -w La_Bona_Lingvo125vm.wav

    -veo : elektas la voĉon en Esperanto de eSpeak
    -f La_Bona_Lingvo.txt : uzas tiun dosieron kiel fonton
    -s 125 : uzas rapidecon de 125 vortoj minute (175 normale)
    -g 7 : aldonas iom da tempo inter la vortoj (nesufiĉa normale)
    -w La_Bona_Lingvo125vm.wav : kreas kiel rezulton la dosieron La_Bona_Lingvo125vm.wav

(Vi povas ŝanĝi la komandon laŭ viaj propraj preferoj.)

La dosiero La_Bona_Lingvo125vm.wav nun troviĝas en la dosierujo. Mi tuj povas aŭskulti ĝin. Tamen, ĝi estas tre peza (917 MB por 5 horoj kaj 46 minutoj) ĉar la formato estas kruda. Do, antaŭ ol meti la dosieron al en mia MP3-ludigilo/lanĉilo, mi ŝanĝas ĝian formaton al .mp3 per Audacity.

Bone. Mi povas aŭskulti 30 minutojn da ĝi ĉiuvespere, en mia lito, kun miaj manoj disponeblaj. Rimarku ke tiel, oni povas “legi” multajn librojn en Esperanto tre rapide. Oni simple bezonas sekvi la ritmon de la voĉo, kaj tio estas pli kuraĝiga ol mane turni paĝojn.

Notu, ke la ĉefa problemo nun estas la Teksto-Al-Voĉa programo eSpeak. Se la voĉo estus pli klara kaj natura, oni povus aŭskulti librojn multe pli rapide. (Tamen, oni jam povas kutimiĝi al la nuna voĉo.) Ankaŭ notu ke kelkaj libroj en Esperanto havas tre malnormalan (kelkfoje evitindan) stilon, kaj malfacilas kompreni ilin laŭ la imponita direkto de voĉlegado.

Mi ofte demandas min kial ne ekzistas pli bona Teksto-Al-Voĉo en Esperanto. Laŭ mi, krei tian programon devus esti prioritato, ĉar ĝi helpos ĝui la Esperantan kulturon, kaj ankaŭ helpos kurs-kreantojn. Bedaŭrinde, mi havas nek la teknikajn sciojn por fari tion, nek la monon de UEA.