Pozdrav svima!

Hvala što ste došli i pokazali interes za predavanje "JavaScript od null-e"! Posjećenost je bila puno veća nego što sam očekivao! Nadam se da ste se dobro proveli.

Podsjetili su me poslije predavanja da sam zaboravio postaviti i odgovoriti na obećano pitanje:

"Što je i gdje je source kôd JavaScripta?"

To pitanje sam si postavio puno puta kada sam počeo raditi s JavaScriptom. Volim proučavati kako nešto radi pa sam htio pogledati kako su stvari posložene, zašto se jezik ponaša baš tako kako se ponaša.

Znao sam da je Ruby realiziran kroz C, da Haxe pogoni OCaml, ali što je temelj JavaScriptu?

Jednostavno - ECMAScript standard. Ili točnije, JavaScript engine koji implementira dani standard.

Mozilla koristi Spidermonkey. Safari koristi Nitro. Edge koristi Chakru. Chrome, Node, i mnogi drugi koriste V8. Svaki engine - a ima ih više nego što sam nabrojao - implementira (ili možda interpretira) standard na svoj način, u jeziku po njegovom izboru.

Zbog toga i postoje razlike u izvođenju skripti među preglednicima, jer se enginei razlikuju u detaljima implementacije. To ne uključuje samo memory management, recimo, ili neke optimizacije u procesu kompilacije kôda. Tu je ponekad riječ i o nekakvoj "kreativnoj slobodi" u izboru toga što će se točno implementirati. Ne mora svaki engine implementirait cijeli standard. Iako bi bilo poželjno :)

No dobro, da se vratim na pitanje. Ako me zapravo zanima jezik i zašto je takav kakav je, proučit ću ECMAScript standard prema kojem radim. Ako me zanimaju implementacijski detalji, ili možda želim i sam implementirati standard jednog dana, proučit ću izvorni kôd popularnih enginea.

I ako vas zanima koliko se točno enginei razlikuju, možete provjeriti sljedeću tablicu:

http://kangax.github.io/compat-table/es6/

Hvala još jednom što ste došli i nadam se da ćemo se vidjeti i na nekom sljedećem predavanju!

- Domagoj
