# RFID failai
RFID technologijos failai

### Čia talpinama visa reikalinga info apie RFID technologijas.

#### Trumpas įvadas į RFID žymų pasaulį.

**RFID** yra bekontakčių radijo žymų technologija, naudojama domofonuose, mokėjimo kortelėse, kelionių kortelėse, biuro leidimuose, gyvūnuose, automobiliuose ir kt. Yra du pagrindiniai RFID žymų tipai, kuriuos naudojame kasdieniame gyvenime: (LF)Žemo dažnio ir (HF)Aukšto dažnio.

* (_Low Frequency:_ **125 kHz**) Žemo dažnio – turi ilgą skaitymo diapazoną. Nesaugu ir kvaila. Naudojamas primityviose prieigos kontrolės sistemose: domofonuose, biuro leidimuose, sporto salės abonementuose.
* (_High Frequency:_ **13,56 MHz**) Aukšto dažnio - turi trumpesnį diapazoną nei žemo dažnio ir gali turėti sudėtingus protokolus, šifravimą, autentifikavimą, kriptografiją. Naudojamas bekontaktėse banko kortelėse, kelionės bilietuose, saugiuose leidimuose.
* Yra daug **RFID** protokolų, kurie veikia kitais dažniais, pavyzdžiui, **UHF 840–960 MHz** Jie naudojami sekti krovinius, mokėti už mokamus kelius, sekti laukinius gyvūnus migracijos metu ir kt. Šios žymos gali turėti savo bateriją ir veikti nuo kelių metrų iki kelių kilometrų atstumu. Tuo pačiu metu jie yra gana reti ir beveik niekada nerandami kasdieniame gyvenime.

#### RFID žymų tipai (_iliustracija, šaltinis: Tagprint.com.my_)
![RFID tipai](http://www.tagprint.com.my/wp-content/uploads/rfid-inlay-sample-1.jpg)

### Skirtumai tarp RFID 125 kHz ir 13,56 MHz

 Lengviausias būdas suprasti, kokiame diapazone veikia **RFID** žyma, yra pagal antenos tipą. Žemo dažnio žymose (**125 kHz**) antena pagaminta iš labai plonos vielos, tiesiog plonesnės už plauką, ir daugybė apsisukimų. Todėl tokia antena atrodo kaip vientisas metalo gabalas. Aukšto dažnio plokštės (**13,56 MHz**) turi daug mažiau posūkių ir storesnį laidą ar pėdsakus. Taigi tarp posūkių matomi tarpai. 
pamatyti **RFID** kortelės viduje esančią anteną, galite ją apšviesti galinga lempa. Jei antena turi tik kelis didelius posūkius, greičiausiai tai yra **HF** aukšto dažnio plokštė. Jei antena atrodo kaip tvirtas metalo gabalas be tarpų, tai **LF** žemo dažnio plokštė.
 **LF** Žemo dažnio žymos dažniausiai naudojamos sistemose, kurioms nereikia ypatingo saugumo: domofono raktai, sporto salės abonementai ir kt. Dėl didesnio diapazono juos patogu naudoti kaip parkavimo bilietus: vairuotojui nereikia priglausti kortelės prie skaitytuvo, ji veikia iš toli. Tuo pačiu metu žemo dažnio žymos yra labai primityvios, jos turi mažą duomenų perdavimo spartą, todėl jos negali įgyvendinti sudėtingų dvipusių duomenų mainų, tokių kaip balanso patikrinimai ir kriptografija. Žemo dažnio žymos perduoda tik savo trumpąjį **ID** be jokių autentifikavimo priemonių.
Aukšto dažnio žymos naudojamos sudėtingesnei sąveikai tarp kortelės ir skaitytuvo, kai reikia kriptografijos, ilgo abipusio ryšio, autentifikavimo ir pan., pavyzdžiui, banko kortelėms, patikimiems leidimams. 

#### RFID žymų skirtumai pagal dažnį (_iliustracija, šaltinis: RFpage.com_)

![RFID skirtumai](https://www.rfpage.com/wp-content/uploads/2021/09/RFID-Antennas.jpg)

#### Dažnių diapazonas RFID kortelėse

     Dažnių diapazonas | Atstumas  | Duomenų sparta
     LF: 120–150 kHz   |   10 cm   | Žema
     HF: 13.56 MHz     |  0.1–1 m  | Nuo žemos iki vidutinės 
     UHF: 433 MHz      |  1–100 m  | Vidutinė
     UHF: 865–868 MHz  |  1–12 m   | Nuo vidutinės iki aukštos
          902–928 MHz
     MW: 2.4–5.8 GHz   | 1–2 m     |  Aukšta
     MW: 3.1–10 GHz    | iki-200 m |  Aukšta

#### Kaip veikia RFID žymos (_iliustracija, šaltinis: Youtube/RFpage.com_)

![Kaip veikia RFID](https://www.rfpage.com/wp-content/uploads/2021/09/RFID-Working.jpg)

**LF 125 kHz** žemo dažnio žymės.

* _Didelis diapazonas_ – šių žymų diapazonas pasiekiamas dėl žemo dažnio. Yra **EM-Marin** ir **HID** kortelių skaitytuvai, kurie veikia maždaug metro atstumu. Jie dažnai naudojami automobilių stovėjimo aikštelėse.
* _Primityvus protokolas_ – dėl mažo duomenų perdavimo spartos tokios žymos gali perduoti tik savo trumpąjį **ID**. Daugeliu atvejų nenaudojama jokio autentifikavimo ir duomenų apsaugos priemonių. Kai tik kortelė patenka į skaitytuvo veikimo lauką, ji pradeda perduoti savo identifikatorių.
* _Žemas saugumo lygis_ – dėl protokolo primityvumo tokias žymas lengva nukopijuoti ar nuskaityti iš savininko kišenės.


**HF 13,56 MHz** aukšto dažnio žymės.

* _Trumpas diapazonas_ – aukšto dažnio žymės yra specialiai sukurtos taip, kad jas būtų galima naudoti arti skaitytuvo. Tai daroma, be kita ko, siekiant apsisaugoti nuo neteisėto skaitymo. Didžiausias skaitymo diapazonas, naudojant tokias pasyvias korteles, yra apie 15 cm specialiuose tolimojo nuotolio skaitytuvuose.
* _Išplėstiniai protokolai_ – duomenų perdavimo sparta iki **424 kbps** leidžia įgyvendinti sudėtingus duomenų mainų protokolus su visišku dviejų krypčių apsikeitimu: kriptografija, failų perdavimu ir pn.
* _Aukštas saugumo lygis_ – aukšto dažnio bekontaktės kortelės nenusileidžia kontaktinėms lustinėms kortelėms. Yra kortelių, kurios palaiko sudetingus šifravimo algoritmus, tokius kaip **AES**, ir įgyvendina asimetrinę viešojo rakto kriptografiją.

### Panagrinėkime **LF 125 kHz** žemo dažnio protokolus

Žemo dažnio žymose saugomi trumpi kelių baitų ilgio kortelių **ID**. Šie **ID** registruojami valdiklio arba domofono duomenų bazėje. Tokiu atveju kortelė tiesiog perduoda savo **ID** visiems norintiems, kai tik jai generuojamas magnetinis laukas. Dažnai kortelės **ID** užrašomas ant pačios kortelės ir gali būti nufotografuotas bei rankiniu būdu įvestas į klonavimo įrenginį. 
Populiarūs 125 kHz protokolų tipai:

* **EM-Marin** - **_EM4100_**, **_EM4102_**. Vienas iš populiariausių protokolų. Labai paprastai ir stabiliai veikia, galima nuskaityti iš metro atstumo.
* **HID Prox II** - yra žemo dažnio protokolas iš **HID Global**. Labiau paplitusi vakaruose, bet taip pat aptinkama azijos šalyse. Sudėtingesnis algoiritmas, skaitytuvai ir kortelės yra gan brangūs.
* **Indala** yra labai senas žemo dažnio protokolas, kurį išrado **Motorola**, bet vėliau išpirko **HID**. Beveik nebenaudojamas, bet vis tiek retkarčiais pasitaiko.

Realiame gyvenime yra daug daugiau žemo dažnio protokolų, tačiau jie visi vienaip ar kitaip yra šių trijų pagrindinių protokolų variantai, kurie naudoja tą pačią moduliaciją fiziniame lygmenyje.

#### EM Marin

Labiausiai paplitęs **RFID** formatas yra **EM-Marin**. Tai paprastas ir neapsaugotas nuo kopijavimo protokolas, paprastai yra naudojams **EM4100** lustas. Yra ir kitų lustų, kurie veikia tuo pačiu principu, pvz: **EM4305** – skirtingai nei **EM4100**, jį galima perrašyti.
Unikalus **EM4100** kodas susideda iš 5 baitų. Kartais tai parašyta ant **RFID** kortelės. Unikalus kodas vienu metu gali būti parašytas keliais formatais: dešimtainiu arba tekstiniu. **EM-Marin** kortelėse paprastai įrašomi ne visi 5 baitai, o tik apatiniai 3 baitai. Likę 2 baitai turės būti sutvarkyti, jei kortelės nuskaityti nepavyks.
Kai kurie domofonai bando apsisaugoti nuo pasikartojančių raktų ir bando tai patikrinti. Domofonas prieš skaitydamas siunčia rašymo komandą, o jei įrašymas sėkmingas, tokį raktą laiko netikru.

#### HID Prox

**HID Global** yra didžiausias **RFID** įrangos gamintojas pasaulyje. Jie turi kelis patentuotus žemo ir aukšto dažnio **RFID** protokolus. Populiariausias žemo dažnio **HID** protokolas yra **26 bitų H10301** (**HID26**, dar žinomas kaip **HID PROX II**). Jame esantis unikalus kodas susideda iš 3 baitų (24 bitai), dar 2 bitai naudojami palyginimui (vientisumo patikrinimui).
Kai kuriose **HID26** kortelėse yra užrašyti numeriai, nurodantys partijos numerį ir kortelės **ID**. Iš šių skaičių neįmanoma visiškai atpažinti 3 baitų unikalaus kodo, tik 2 baitai užrašomi ant kortelės dešimtaine forma: **Kortelės ID**.

#### Indala

**Indala RFID** protokolą sukūrė **Motorola**, o vėliau įsigijo **HID**. Tai labai senas protokolas, o šiuolaikiniai prieigos kontrolės gamintojai jo nenaudoja. Tačiau realiame gyvenime **Indala** yra reta.
Kaip ir **HID26**, **Indala** kortelės unikalus kodas **I40134** susideda iš 3 baitų. Deja, **Indala** kortelių duomenų struktūra nėra vieša informacija, ir kiekvienas, kuris yra priverstas palaikyti šį protokolą, pats sugalvoja, kurią baitų tvarką pasirinkti ir kaip interpretuoti signalą žemu lygiu.

#### LF Kortelių klonavimas

Yra keli specialių tuščių kortelių tipai kuriuose galite įrašyti bet kurį iš trijų aukščiau aprašytų protokolų (**EM-Marin, HID Prox, Indala**). Populiariausias ruošinių tipas yra **T5577**. 
Žemo dažnio **T5577 RFID** kortelės irgi būna įvairių tipų. Pavyzdžiui kad skaitytuvai su patikra nesuprastu ar šios kortelės yra klonai, ar ne, jos būna užmaskuotos ir apgauna tokius skaitytuvus.

### Panagrinėkime HF Aukšto dažnio protokolus **13,56 MHz**

**13,56 MHz** aukšto dažnio žymas sudaro daugybė standartų ir protokolų – ir jie paprastai vadinami **NFC** technologija , o tai ne visada tiesa. Pagrindinė protokolų dalis yra paremta **ISO 14443** standartu – tai pagrindinis fizinių ir loginių sluoksnių protokolų rinkinys, kuriuo grindžiami aukšto lygio protokolai ir kuriais remiantis buvo sukurti alternatyvūs žemo lygio standartai, pavyzdžiui, **ISO 18092**. Dažniausias diegimas yra **ISO 14443-A**, jį labai dažnai naudoja kelionių kortelės, leidimai ir banko kortelės.
Supaprastinta **NFC** architektūra atrodo taip: žemo lygio **ISO 14443** bazėje įdiegtas transportavimo protokolas, jį parenka gamintojas. Pavyzdžiui, **NXP** sukūrė savo aukšto lygio **Mifare** kortelių perdavimo protokolą, nors nuorodos lygiu **Mifare** kortelės yra pagrįstos **ISO 14443-A** standartu.

#### NFC architektūra plačiau (_iliustracija, šaltinis: habr.org_)

![NFC architektūra](https://habrastorage.org/r/w1560/webt/t5/_9/pf/t5_9pf6yy48b9qcck2pztbfio5u.jpeg)

#### Grynas UID ISO 14443-A

Visos **HF** kortelės, pagrįstos **ISO 14443-A**, turi unikalų lusto identifikatorių – **UID**. Tai yra kortelės serijos numeris, panašus į tinklo plokštės **MAC** adresą. **UID** yra 4, 7 ir labai retai 10 baitų ilgio. **UID** neapsaugotas nuo skaitymo ir nėra slaptas, kartais net užrašomas ant kortelės.
Tiesą sakant, yra gan daug skaitytuvų sistemų kurie naudoja tik **UID** kad suteiktų prieigą. Taip nutinka net ir tada, kai **RFID** žymos yra kriptografiškai apsaugotos. Ir saugumo prasme tai mažai kuo skiriasi nuo paprastų žemo dažnio **125 kHz** kortelių. Virtualiose kortelėse _(pvz., **Apple Pay**)_ tyčia naudojamas dinaminis **UID**, kad telefonų savininkai negalėtų naudoti mokėjimo programos kaip durų rakto.

* Žemas lygis – skaitomas **UID**, **SAK** ir **ATQA**.
* Aukštas lygis - duomenų skaitymas kortelės atmintyje naudojant konkretų aukšto lygio protokolą. Pavyzdžiui, duomenų skaitymas **Mifare Ultralight** kortelėse.

#### Mifare Ultralight

**Mifare** yra bekontakčių intelektualiųjų kortelių, turinčių skirtingus aukšto lygio protokolus, šeima. **Mifare Ultralight** yra paprasčiausias kortelės tipas šeimoje. Pagrindinėje versijoje ji nenaudoja kriptografinės apsaugos ir turi tik 64 baitus vidinės atminties. Tokios žymos kartais naudojamos kaip domofono raktų pakabukai, leidimai ir kelionių kortelės. Pavyzdžiui, _Vilniečio kortelė_ iki 2023 metų buvo gaminama **Mifare** kortelės pagrindu.

#### EMV banko kortelės (_PayPass, Apple Pay_)

**EMV** (**Europay**, **Mastercard** ir **Visa**) yra tarptautinis banko kortelių standartų rinkinys. 
Banko kortelės yra visavertės lustinės kortelės su sudėtingais duomenų mainų protokolais ir palaikančios asimetrinį šifravimą. Be **UID** nuskaitymo, banko kortelė gali keistis sudėtingais duomenimis, įskaitant pilno kortelės numerio ištraukimą (16 skaitmenų kortelės priekyje), kortelės galiojimo datą, kartais savininko vardą ir pavardę ir net naujausią pirkinių istoriją.
EMV standarto kortelės turi skirtingas aukšto lygio revizijas, todėl duomenys kuriuos galima nuskaityti iš kortelių gali skirtis. Bet pavizdžiui **CVV** (3 skaitmenys kortelės gale) niekaip negali būti nuskaityti.
Banko kortelės yra apsaugotos nuo pakartotinių atakų, todėl negalėsite jų nukopijuoti naudodami paprastus klonavimo aparatus, o tada emuliuoti ir sumokėti už pirkinį parduotuvėje.

#### ApplePay virtuali kortelė VS fizinė banko kortelė

Palyginti su plastikine banko kortele, telefone esanti virtuali kortelė suteikia mažiau informacijos ir yra saugesnė atsiskaitant neprisijungus.

#### ApplePay ir fizinės banko kortelės skirtumai (_iliustracija, šaltinis: habr.org_)
![Apple vs Bank](https://habrastorage.org/r/w1560/webt/u_/2k/by/u_2kby7anzdserrxznhdsszsiy0.jpeg)

#### Apple Pay, Google Pay virtualios kortelės privalumai:

* Neleidžia naudoti perimtų duomenų atsiskaitant internetu – įprastą kortelę galima naudoti **CNP** _(kortelės nėra)_ operacijoms, tai yra atsiskaitant internetu ar telefonu ir pan. Tokio metodo neišeina naudoti su **Apple Pay** virtualia kortele. Taip yra dėl to, kad elektroninė kortelė registruojantis išduoda naują kortelę, kurios operacijos turi turėti kriptografinį parašą. Nuskaitant **Apple Pay** pateikiamas naujos išduotos elektroninės kortelės **PAN** ir galiojimo laikas, o ne registruojama fiziniu būdu. Todėl jei atsiskaitymui internetu nurodysite perimtus virtualios kortelės duomenis, mokėjimas bus atmestas nes šioms operacijoms reikalingas specialus parašas.
* Neatskleidžia kortelės savininko duomenų – kai kurios fizinės bekontaktės kortelės gali atskleisti kortelės turėtojo vardą ir naujausią pirkinių istoriją. Virtuali kortelė to nedaro.

#### ApplePay ir GPay kortelių skirtumai (_iliustracija, šaltinis: bytebytego.com_)
![Apple vs GPay](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fb32cb5f4-92c6-4859-b825-92b04b6daf1e_1357x1536.jpeg)

### Panagrinėsime ar galima pasisavinti svetimus pinigus iš Apple pay ir banko kortelių?

Pagrinėsime populiarius mitus susijusius su sukčiavimu bekontakčio mokėjimo sistemomis, naudojant **POS** terminalą ir **PayPass** / **PayWave** / **Google Pay** / **Apple Pay**.

![Vagystes POS](https://i.ytimg.com/vi/mhsbS2Y2RD0/maxresdefault.jpg)
_(šaltinis: ytimg.com)_

#### Aptariamos temos:

1. Ar tikrai gali pavogti pinigus atsiremdamas **POS** terminalą į kišenę? — bandysime pilnai atkartoti šį sukčiavimo scenarijų nuo pradžios iki pabaigos, naudodami tikrą **POS** terminalą ir mokėjimo korteles realiomis sąlygomis.
2. Kuo skiriasi fizinės ir virtualios **Apple Pay** kortelės? – kaip susiejama fizinė kortelė ir **Apple Pay** prieigos raktas ir kodėl **Apple Pay** yra daug kartų saugesnis nei įprasta kortelė.
3. Naudojame aparatinę **NFC** sniferį (**ISO 14443A**) – naudosime **Proxmark3 Pro** įrenginį duomenims tarp **POS** terminalo ir kortelės perimti. Pasvarstykime, kokius konfidencialius duomenis galima išgauti iš perimto srauto.
4. Analizuojame **EMV** protokolą – kokiais duomenimis keičiasi kortelė ir **POS** terminalas, naudojamas užklausos formatas, apsaugos nuo sukčiavimo ir pakartojimo atakų mechanizmai.
5. Ištirkime operacijas be kortelės (**CNP, MO/TO**) — kokiais atvejais tikrai galima pavogti pinigus iš kortelės, turint tik bekontakčius duomenis, o kada tai neįmanoma.

#### Kaip tai veikia?

Pirmiausia apsvarstykime pagrindines sąvokas: bet kokie pinigų judėjimai naudojant mokėjimo korteles galimi tik per tarpininkus, prijungtus prie mokėjimo sistemos, pavyzdžiui, **VISA** ar **MasterCard**. Skirtingai nei pavedimai tarp fizinių asmenų, nurašyti pinigus iš kortelės gali tik juridinis asmuo (prekybininkas), turintis priėmimo sutartį su banku.

![POS pavedimu kelias](https://miro.medium.com/max/1400/1*K9bp4Kbg_HWik1wOxQw9jw.jpeg)
_(šaltinis: miro.medium.com)_

#### Operacijų etapai atsiskaitant per POS terminalą

Aukščiau pateiktame paveikslėlyje parodyta klasikinė mokėjimo per **POS** terminalą schema. Būtent tokia veiksmų seka atsiranda tada, kai sumokėję kasoje laukiate patvirtinimo terminale. 

1. Pirkėjas uždeda/perbraukia/įdeda kortelę į **POS terminalą**;
2. **POS terminalas** perduoda duomenis internetu priimančiam bankui;
3. Įgyjantis bankas per tarptautinę mokėjimo sistemą (**IPS**) susisiekia su kortelę išdavusiu banku ir pasiteirauja ar kortelės turėtojas gali sumokėti už pirkinį;
4. Išdavęs bankas patvirtina arba atmeta pirkimą, po to atspausdinamas lapelis (_antras čekis_).

Yra šios schemos išimčių, pvz. operacijos neprisijungus, jas apsvarstysime toliau. Be to jei įsigyjantis bankas ir emitentas yra tas pats bankas, 2 ir 4 veiksmai atliekami tame pačiame banke.

**Prekybininkas** - asmuo ar organizacija, teikiantis prekes ar teikiantis paslaugas.

**Priimantis bankas** - bankas, teikiantis pardavėjui mokėjimų banko kortelėmis priėmimo paslaugas. Šiame banke, kaip taisyklė, yra pardavėjo atsiskaitomoji sąskaita, į kurią įskaitomi nuo kortelės nuskaičiuoti pinigai.

**Išduodantis bankas** - kortelę išdavęs bankas. Jame yra kortelės turėtojo, iš kurio nurašomi pinigai, sąskaita.

**Tarptautinė mokėjimo sistema(_IPS_)** - tarptautinė tarpininkavimo sistema tarp bankų visame pasaulyje, leidžianti bankams tarpusavyje atsiskaityti nesudarius sutarties su kiekvienu banku atskirai. Visi prie **IPS** prisijungę bankai sutinka dirbti pagal tas pačias taisykles, o tai labai supaprastina tarpusavio sąveiką. Pavyzdžiui, **Visa**, **MasterCard**, **UnionPay**, **American Express** ir t.t.

**Kortelės turėtojas** – asmuo, sudaręs kortelių aptarnavimo sutartį su ją išdavusiu banku. 

#### Mitai apie **Apple Pay**

* **Kortelė nukopijuojama į telefoną** - Taip nėra, intelektualiojoje kortelėje yra saugoma atminties sritis su kriptografine informacija, kurios negalima pašalinti išdavus kortelę. Dėl šios priežasties lustinės kortelės jokiu būdu negalima kopijuoti. Tiesą sakant, reikia pasakyti, kad tokie išpuoliai yra įmanomi, tačiau jų kaina viršija bendrą pinigų sumą, kurią dauguma šio straipsnio skaitytojų išleis visą gyvenimą.
* **Telefonas prie interneto prisijungia kiekvieną kartą mokėjimo metu** - **Google Pay** / **Apple Pay** neprisijungia prie interneto **POS** mokėjimo metu. Visa reikalinga informacija yra saugoma lokaliai telefone.
* **Kiekvienam mokėjimui sugeneruojamas naujas kortelės numeris (PAN)** - Taip gali atrodyti, jei perskaitysite **Apple** pranešimus spaudai apie **Apple Pay** technologiją. Tačiau tai yra klaidingas _tokeno_ sąvokos aiškinimas. Tiesą sakant, virtualios kortelės rekvizitai išlieka nepakitę ilgą laiką, tai galite patikrinti pagal paskutinius kortelės numerio skaitmenis, esančias kvite (_banko čekis_) atsiskaitydami už pirkinius.
* **Atsiskaitant per Apple Pay / Google Pay, imamas papildomas mokestis** - Taip nėra, mokėsite tiksliai tiek, kiek nurodyta ant kainų etiketės ir pagal sutarties su išdavusiu banku, kurio kortelę susiejote sąlygas.
* **Pinigai gali būti nurašyti du kartus** - Šis mitas galioja ne tik **Google Pay** / **Apple Pay**, bet ir paprastoms banko kortelėms. Manau, kad tai atsirado dėl viešojo transporto atsiskaitymo sistemų, kuriose terminalas kaskart pateikus bilietą nurašo pinigus. Dėl netiksliai perbrauktos kortelės galimi du ar daugiau kartų lėšų nuskaičiavimai. Bet **POS** terminalų atveju ši rizika neegzistuoja, nes terminalas nustoja keistis informacija su kortele, kai tik gauna reikiamus duomenis.

Sistemos kaip **Apple Pay** veikia pagal **EMV** mokėjimo prieigos rakto specifikaciją. Fizinės kortelės ir telefono susiejimo su **Apple Pay** procedūra nėra viešai aprašyta, todėl procesą analizuosime pagal žinomus duomenis.

![Apple Pay EMV systema](https://miro.medium.com/v2/resize:fit:2400/format:webp/1*U5yCNkePH0kGvTjRrUu6kQ.png)
_(šaltinis: miro.medium.com)_


* Teikėjas (**Google**, **Apple**, **Samsung**) gauna informaciją apie kortelę;
* Per **IPU** tiekėjas klausia, ar ši kortelė (_išduodantis bankas_) palaiko **EMV** Tokenizaciją;
* **MPS** pusėje sugeneruojama virtuali kortelė (_token_), kuri įkeliama į saugią saugyklą telefone. Poto generuojamas privatus raktas iš virtualios kortelės.
* Telefone pasirodo sugeneruota virtuali _tokeno_ kortelė, kurią išduodantis bankas interpretuoja kaip operacijas su fizine kortele. Jei fizinė kortelė užblokuota, blokuojamas ir tokenas.

Atsiskaitant telefonu **POS** terminalas mato įprastą **VISA** arba **MasterCard** kortelę ir su ja bendrauja taip pat, kaip su fizine kortele. Virtualioje _tokeno_ kortelėje yra visi įprastos kortelės atributai: **PAN** numeris, galiojimo data ir pan. Tuo pačiu metu virtualios kortelės numeris ir galiojimo laikas skiriasi nuo susietos originalios kortelės.


### Eksperimentas pasisavinti pinigus per POS terminalą, jo kąštai ir galimybės.

![POS steal](https://www.investsmall.co/wp-content/uploads/2020/12/pos-machines-1024x797.jpg)
_(šaltinis: investsmall.co)_

Darysime prielaidą, kad **UAB** plius einamoji sąskaita - 300 eurų. Tada **POS** terminalas sukčiui kainuos 100 eurų. Supaprastinau savo hipotetinio sukčiaus gyvenimą, sumažinau atakos kainą. Juk kuo mažesnė atakos kaina, tuo lengviau ją įgyvendinti. Taigi, aferistas gavo **POS** terminalą ir eina į sausakimšą vietą, kad pavogtų pinigus iš jų kišenės.

#### Problema Nr.1: Operacijų be PIN kodo apribojimas

Maksimalios operacijos sumos limitą nepatvirtinus **PIN** kodu galima nustatyti tiek pačiame **POS** terminale (_CVM Required Limit_), tiek banko pusėje. Ši riba šiai dienai yra 30 eurų. _**UPD** Kortelės nustatymuose gali būti nustatytas autorizavimo tipas Kortelės turėtojo tikrinimo metodai (**CVM**) – parašas ant čekio. Tokiu atveju bekontaktė operacija bus atlikta bet kokia suma be PIN kodo._
Sakysim aferistas nusprendžia vienu metu nurašyti 29 eurus. Jei bus prašoma pakartotinai per trumpą laiką nurašyti sumą, mažesnę nei limitas, taip pat bus prašoma įvesti **PIN** kodą ir daugeliu atvejų kelis kartus iš eilės nepavyks nurašyti 29 eurų. Todėl optimaliausia strategija būtų ne daugiau kaip vienas nurašymas iš vienos kortelės. Tiesą sakant, daugybė nurašymų, kurių suma siekia 29 eurų per trumpą laiką, gali suaktyvinti kovos su sukčiavimu sistemą įsigyjančiojo banko pusėje, todėl ši strategija nėra optimali sukčiui. Taigi realiame gyvenime jam tektų rinktis įvairesnes sumas ir taip sumažinti galimas pajamas.

#### Problema Nr.2: Piniginėje kelios kortelės

Tai svarbus momentas šiame vagystės scenarijuje, nes iš tikrųjų beveik niekas kišenėje nesinešioja vienos kortelės. Daugeliu atvejų kortelė yra saugoma piniginėje kartu su kitomis bekontaktėmis kortelėmis, tokiomis kaip kelionės bilietai ar kitos banko kortelės. Dalis terminalų, kai skaitytuvo lauke randama daugiau nei viena kortelė su **SAK**, žyminčia protokolo palaikymą **14443-4**, indikuoja klaidą: _Pateikti vieną kortelę_. Tačiau ne visi terminalai tai daro. Pavyzdžiui, **VeriFone POS** terminalai pasirenka atsitiktinę kortelę iš kelių. Kai kurie terminalai tiesiog ignoruoja visas korteles jei yra daugiau nei viena kortelė. Ir nerodo jokių klaidų pranešimų.

#### Antikolizija ISO 14443-3

Perskaityti vieną konkrečią kortelę iš kelių nėra lengva užduotis fiziniu lygmeniu. Norėdami išspręsti šią problemą galime naudoti antikolizijos mechanizmą. Šis metodas leidžia pasirinkti vieną kortelę, jei atsakymas buvo gautas iš kelių kortelių vienu metu. Tai pats pirmas žingsnis užmezgant ryšį su bekontakte kortele pagal **ISO-14443A** protokolą. Šiame etape skaitytojas negali sužinoti, kuri iš pateiktų kortelių yra banko kortelė. Vienintelė galimybė – pagal **SAK** (_Select Acknowledge_) atsakymą pasirinkti vieną daugiau ar mažiau panašią į banko kortelę.
Taigi, pavyzdžiui, Vilniaus viešajame transporte naudojama _Vilniečio kortelė_ (**Mifare** standartas) turi reikšmę **SAK=0x08** (**b00001000**), kurioje šeštas bitas lygus nuliui. Nors visos banko kortelės **SAK** atsakymuose turi šeštąjį bitą, lygų 1, o tai reiškia **ISO 14443-4** protokolo palaikymą. Todėl viskas, ką terminalas gali padaryti aptikęs kelias korteles vienu metu, tai išskirti korteles, kurios nepalaiko **ISO 14443-4**, ir pasirinkti vieną iš panašių į banko kortelę. Protokolo **ISO 14443-4** palaikymas negarantuoja kad ši kortelė bus banko kortelė, tačiau greičiausiai paprasto žmogaus piniginėje nebus kitos rūšies kortelės, palaikančios **ISO 14443-4**. 

![SAK kodų lentelė](https://e2e.ti.com/cfs-file.ashx/__key/communityserver-discussions-components-files/667/8831.SAK.png)
_(šaltinis: e2e.ti.com)_

Nepaisant to kad yra apsaugos protokolas nuo susidūrimų bet jei piniginėje yra bent trys bekontaktės kortelės, ypač sunku sėkmingai nuskaityti norimą kortelę. Dauguma bandymų baigsis skaitymo klaidomis. Lauko sąlygomis tai padaryti dar sunkiau.

#### Operacijos neprisijungus ir internetu

**EMV** specifikacijos leidžia atlikti operacijas neprisijungus. Šiuo režimu nurašymas atliekamas be internetinio banko išduodančiojo patvirtinimo. Dienos pabaigoje, kai **POS** terminale atsiranda internetas, pasirašytos operacijos siunčiamos į išduodantį banką.

#### Pelno skaičiavimas

Pagal mūsų scenarijų atakos kaina buvo 400 eurų. Tai reiškia, kad norint bent jau susigrąžinti investicijas, mūsų herojus turi atlikti bent jau kokių 20 operacijų po 20 eurų. Įsivaizduokite, kad jis buvo gana vikrus ir visą dieną lakstė po miestą, prilipęs prie visų iš eilės, todėl dienos pabaigoje buvo padaręs 30 sėkmingų nurašymų. Į įsigijimo komisinius (vidutiniškai 2%), išgryninimo komisinius (4-10%) ir kitus komisinius neatsižvelgsime.

#### Ar jis gali sėkmingai atsiimti pinigus naudodamas kortelę, susietą su einamąją sąskaitą?

Iš tikrųjų ne viskas taip paprasta. Pinigai į sukčiaus sąskaitą bus įskaityti tik po kelių dienų!Per šį laiką mūsų aferistas turi tikėtis, kad nė vienas iš trisdešimt aukų neužginčys sandorio, o tai labai mažai tikėtina. Todėl realiai sukčiaus sąskaita bus užblokuota dar prieš tai, kai į ją bus įskaityti pinigai. Jei asmuo pastebėjo, kad jo kortelėje buvo atliktas pirkinys, kurio jis neatliko, jis turėtų kreiptis į jį išdavusį banką ir pateikti pretenziją. Ginčintiniems sandoriams svarstymas užtrunka iki 60 dienų. Per šį laiką išduodantis bankas išsiunčia užklausą priimančiam bankui, o jei priimantis bankas patvirtina įtartinų operacijų faktą, terminalas ir terminalo savininko atsiskaitomojoje sąskaitoje esančios lėšos blokuojami.

Išpuolio kaina mūsų scenarijuje yra 400 eurų. Realiai ji bus kelis kartus didesnė, tad norint pasipelnyti sukčiui prireiks kur kas daugiau pastangų. Pagal mūsų scenarijų sukčius visada nurašo 29 eurus, o tai greičiausiai suaktyvins kovos su sukčiavimu sistemą įsigyjančio banko pusėje. Realiai sukčiai turės nurašyti mažesnes sumas. Norint bent jau susigrąžinti investicijas, sukčiui reikės apšvarinti kelis šimtus aukų. Net jei keliolika jų susisieks su išdavusiu banku ir užginčys operaciją, sukčiaus sąskaita greičiausiai bus užblokuota. Scenarijus, kad įsigyjantis bankas susitartu su sukčiumi mažai tikėtinas, nes licencija eksploatuoti **IMS** kainuoja daug daugiau nei bet koks galimas pelnas iš tokio sukčiavimo.
Realiai sėkmingų nurašymų procentas vargu ar viršys 10%. Taigi, nepaisant to kad teoriškai tokia ataka yra įmanoma, praktiškai ji pasirodo nepalanki ir itin sunkiai įgyvendinama. Galimybė gauti bent šiek tiek pelno yra tokia maža, kad dėl to visa idėja netenka prasmės.

#### Kitas vagystės scenarijus – Piktasis POS terminalas

Tarkime, mūsų aferistas dirba prie kasos parduotuvėje arba kurjeris su mobiliuoju **POS** terminalu. Tokiu atveju jis turi galimybę pagauti kortelės duomenis, kurių kai kuriais atvejais gali pakakti atsiskaityti internetu.
Pirmiausia išsiaiškinkime, kaip tiksliai atrodo bekontaktė operacija ir kokiais duomenimis keičiasi kortelė su **POS** terminalu. Kadangi esame per tingūs skaityti tūkstančius puslapių dokumentacijos, tiesiog perimsime keitimąsi fiziniu lygiu naudodami **Proxmark3 Pro**.
Yra tam tikrų skirtumų tarp **MasterCard** **PayPass** ir **Visa** **payWave EMV** specifikacijos. Tai yra parašo formato ir kai kurių duomenų skirtumas. Bet mums tai neaktualu. **Proxmark3 Pro** yra visiškai atviro kodo _sniferiu_, kuris išsaugo užfiksuotas **APDU** komandas SD kortelėje. _Sniferio_ antena yra tarp terminalo ir kortelės ir pasyviai fiksuoja visą perduodamą informaciją. Žvelgiant į ateitį reiktų pasakyti kad šiuo lygiu mokėjimas telefonu ir įprasta plastikine kortele nesiskiria. **POS** terminalui tai yra įprasta **VISA** kortelė. Tačiau atsiskaityti telefonu daug saugiau nei fizine kortele, kodėl vėliau pamatysime.

#### EMV protokolo analizė

Štai kaip atrodo įrašytas sąvartynas mokant už saldainį ir vandens butelį, kurių bendra kaina yra 3,50 euro. Naudojant **Apple Pay**:

**R>>** — **POS** terminalo siunčiami duomenys
**T<<** — Banko kortelės siunčiami duomenys (mūsų atveju telefonas su **Apple Pay**)

     R>> 52
     R>> 52
     R>> 52
     R>> 52
     R>> 52
     R>> 52
     R>> 52
     T<< 04 00
     R>> 93 20
     T<< 08 fe e4 ec fe
     R>> 93 70 08 fe e4 ec fe dd 6e
     T<< 20 fc 70
     R>> 50 00 57 cd
     R>> 26
     R>> 52
     T<< 04 00
     R>> 93 70 08 fe e4 ec fe dd 6e
     T<< 20 fc 70
     R>> e0 80 31 73
     T<< 05 78 80 70 02 a5 46
     R>> 02 00 a4 04 00 0e 32 50 41 59 2e 53 59 53 2e 44 44 46 30 31 00 e0 42
     T<< 02 6f 23 84 0e 32 50 41 59 2e 53 59 53 2e 44 44 46 30 31 a5 11 bf 0c 
         0e 61 0c 4f 07 a0 00 00 00 03 10 10 87 01 01 90 00 4b b3

#### Išanalizuokime kiekvieną liniją atskirai.

Keitimo pradžioje terminalas užmezga ryšį su kortele nuorodos lygiu. Tiems, kurie yra susipažinę su tinklais ir **OSI** modeliu, bus patogu galvoti apie tai kaip apie **L2** lygį, o kortelės **UID** (_unikalus identifikatorius_) - kaip pagrindinio kompiuterio **MAC** adresą.

* Pagal **ISO-14443** standarto terminologiją:
* **PCD** (proximity coupling device) yra skaitytuvo pavadinimas, mūsų atveju tai yra **POS** terminalas.
* **PICC** (proximity integrinio grandyno kortelė) yra kortelė, mūsų atveju šį vaidmenį atlieka telefonas.

Svarbus skirtumas tarp įprastos mokėjimo kortelės ir **Apple Pay** yra tas, kad kortelė visada yra prieinama skaitymui ir niekaip neleidžia kontroliuoti skaitymo proceso. Ją galima nekontroliuojamai perskaityti per drabužius, o telefonas, patekęs į skaitytuvo veikimo lauką, ragina vartotoją aktyvuoti virtualią kortelę. Kol vartotojas nepatvirtina, telefonas neperduoda jokių duomenų, o skaitytuvas net nežino, kad šalia yra virtuali kortelė. 

#### **Rezultate:**

     R>> 52 // WUPA (wake up)
     R>> 52 // WUPA
     R>> 52 // WUPA
     R>> 52 // WUPA
     R>> 52 // WUPA
     R>> 52 // WUPA
     R>> 52 // WUPA
     T<< 04 00 // ATQA (Answer To Request type A) 
     R>> 93 20 // Select cascade 1 (Anti Collision CL1 SEL)
     T<< 08 fe e4 ec fe // UID (4 bytes) + BCC (Bit Count Check)
     R>> 93 70 08 fe e4 ec fe dd 6e // SEL (select tag 0x9370) + UID + CRC16
     T<< 20 fc 70  // SAK (Select Acknowledge 0x20) + CRC16 
     R>> 50 00 57 cd // HALT (Disable communocaion 0x5000) + CRC16
     R>> 26 // REQA
     R>> 52 // WUPA
     T<< 04 00 // ATQA
     R>> 93 70 08 fe e4 ec fe dd 6e // SELECT
     T<< 20 fc 70 // SAK
     R>> e0 80 31 73 // RATS (Request Answer to Select 0xE080) + CRC16
     T<< 05 78 80 70 02 a5 46 // ATS (Answer to select response)

Terminalas nuolat siunčia komandą **0x52 Wake-up** (**WUPA**), o kai tik kortelė atsiranda veiksmų laukelyje, jis atsako komanda _Answer To Request type A_ (**ATQA**), mūsų atveju tai yra **0x04 0x00** . **ATQA** atsakas gali skirtis priklausomai nuo lusto gamintojų.
Gavęs **ATQA** atsakymą, terminalas pradeda susidūrimo aptikimo procedūrą, kad nustatytų, ar veiksmų lauke yra daugiau nei viena kortelė. Komanda **0x93 0x20** _Select cascade level 1_ (**SEL CL1**) ragina visas išorines korteles pranešti apie pirmąją savo **UID** dalį.
Kortelė atsako **0x08 0xFE 0xE4 0xEC 0xFE** , pirmieji keturi baitai yra **Apple Pay** virtualios kortelės **UID** ir kontrolinė suma 0xFE _Bit Count Check_ (**BCC**) pabaigoje. Gavęs kortelių identifikatorius, skaitytuvas prieina prie konkrečios kortelės su komanda **0x93 0x70** (**SELECT**). Po komandos nurodomas kortelės **UID** -> **0x08 0xfe 0xe4 0xec** + **0xfe** _BCC_ + **0xdd 0x6e** _CRC16_. Kortelė atsako **0x20** _Select Acknowledge_ (**SAK**) + **0xfc 0x70** _CRC16_.

Jei atliekant šį veiksmą gaunami keli **SAK** atsakymai, skaitytuvas gali sumažinti **UID** ilgį komandoje **SELECT**, kol atsakys viena kortelė. Tačiau kaip buvo minėta aukščiau, kai kurie **POS** terminalai atsisako tęsti, jei šiame etape aptinkami susidūrimai, ty kelių kortelių buvimas vienu metu. **UID** ilgis gali būti 4, 7 arba 10 baitų. Visų mano sutiktų banko kortelių, įskaitant **Apple Pay**, **UID** buvo 4 baitai. Įdomu tai, kad **Apple Pay** generuoja skirtingą **UID** per braukimą, skirtingai nei fizinėse kortelėse, kur **UID** paprastai yra pastovus. Esu tikras, kad tai daroma tam, kad **iPhone** nebūtų naudojami kaip primityvios prieigos kortelės, nes **UID** pagrįstos prieigos kontrolės sistemos vis dar yra labai populiarios.

Terminalas siunčia komandą **0x50 0x00** _HALT_ + **0x57 0xcd** _CRC16_. Tai yra pabaigos komanda.
Tada procedūra kartojama dar kartą, terminalas vėl pažadina kortelę (**WUPA**), tačiau nepatikrinus ar nėra konfliktų, iš karto atliekamas **SELECT**. Kodėl tai daroma - nežinau, galbūt tai yra patikimesnis būdas nustatyti konfliktus tarp kelių kortelių. Antrą kartą terminalas jau siunčia komandą **0xE0 0x80** _Request Answer to Select_ (**RATS**) + **0x31 0x73** _CRC16_. Kortelė atsako **0x05 0x78 0x80 0x70 0x02** Atsakymas pasirenkant atsakymą (**ATS**) + **0xA5 0x46** _CRC16_.

**Answer_to_Select** - atsakymas panašus į **Answer To Reset** (_ATR_). Jame pateikiama informacija apie maksimalų kadro dydį ir nuorodos lygio parametrus. Šiame etape baigiamas žemo lygio komunikacija, tada keitimasis pradedamas aukštesnio lygio protokolu, priklausomai nuo kortelėje esančios programos. **SELECT** operacija yra vienoda visoms **ISO 14443A** bekontaktėms kortelėms, įskaitant **NFC** žymas, viešojo transporto bilietus ir kt.

#### Galimų programų užklausa – SELECT PPSE

Ryšiui su **EMV** kortele visada prasideda nuskaitant **PPSE** (mokėjimo sistemos aplinka). Terminalas klausia kortelės, kokias mokėjimo programas ji turi. Dažniausiai tai yra viena programa, kaip ir mūsų pavyzdyje - **VISA**. Tačiau yra kortelių su keliomis mokėjimo programomis. Tai gali būti **JCB** arba **UnionPay** mokėjimo sistemos programa. Tokios kortelės vadinamos **Co-Badged**.

#### SELECT PPSE APDU komanda

     00 A4 04 00 0E 32 50 41 59 2E 53 59 53 2E 44 44 46 30 31 00
     00 A4 04 00 // komanda _SELECT_ 
     0E // ilgis _command data_ (14 baitų)
     32 50 41 59 2E 53 59 53 2E 44 44 46 30 31 // _command data_ 2PAY.SYS.DDF01
     00 // pabaigos markeris

#### Atsakymas į SELECT PPSE

     6F 23 84 0E 32 50 41 59 2E 53 59 53 2E 44 44 46 30 31 A5 11 BF 0C 
     0E 61 0C 4F 07 A0 00 00 00 03 10 10 87 01 01 90 00

Patogumui paanalizuokime atsakymą naudodami internetinį **TVL** analizatorių. 
Nuoroda į reikšmes: [TVL reikšmės](https://iso8583.info/lib/EMV/TLVs)

     X6F: # ISO 7816 Template, File Control Parameters and File Management Data (FCI)
      tag: 6F
      len: 23 #[35]
      val:
     x84: # EMV, Dedicated File (DF) Name
      tag: 84
      len: 0E #[14]
      val: # "325041592E5359532E4444463031" # Dedicatet File (DF) Name
     xA5: # EMV, Template, FCI A5
      tag: A5
      len: 11 #[17]
      val:
     xBF0C: # EMV, FCI Issuer Discretionary Data
      tag: BF0C
      len: 0E #[14]
      val: # FCI Issuer Discretionary Data
     x61: # ISO 7816, Template, Application
      tag: 61
      len: 0C #[12]
      val: # Template, Application
     x4F: # ISO 7816, Application Identifier (AID), Card
      tag: 4F
      len: 07 #[7]
      val: # AID, Card (VISA debit or credit)
     RID: "A000000003" # Registered Application Provider Identifier  (RID) Visa international
     PIX: "1010" # Propietary Application Identifier Extension (PIX)
     x87: # EMV, Application Priority Indicator
      tag: 87
      len: 01 #[1]
      val: # Application Priority Indicator
     S01: 0 # Application may be selected without confirmation of cardholder
     S02: 1 # No priority assigned

Iš viso to mus domina tik mokėjimo paraiškos identifikatorius (AID). Šiuo atveju vertė yra A0000000031010 , ty Visa International.
AID pažymėtas 4F žymekliu . Antrasis bitas po žymeklio yra jame esančių duomenų ilgis. Nors AID ilgis gali svyruoti nuo 5 iki 16 baitų, daugeliu atvejų jis yra 7 baitai.

#### Vieni iš populiaresnių AID reikšmių

     A0000000031010 Visa International
     A0000000032020 Visa International
     A0000000041010 Mastercard International
     A0000000043060 Mastercard International United States Maestro (Debit)

Paraiškos prioriteto indikatorius – nurodo mokėjimo paraiškų prioritetą. 

#### Mokėjimo programos paleidimas – SELECT AID

     '00 A4 04 00 07 A0 00 00 00 03 10 10'
     00 A4 04 00 // komanda "Select" 
     07 // command data reikšmė (7 baitai)
     A0 00 00 00 03 10 10 // AID Visa International

Pasirinkus norimą mokėjimo programą, terminalas ją paleidžia. 

#### PDOL (Processing Options Data Object List)

     6f 31 84 07 a0 00 00 00 03 10 10 a5 26 9f 38 18 9f 66 04 9f 02 06 9f 03 06 9f 1a 02 
     95 05 5f 2a 02 9a 03 9c 01 9f 37 04 bf 0c 08 9f 5a 05 60 08 40 06 43 90 00

#### Išanalizuokime atsakymą analizatoriumi.

     x6F: # ISO 7816, Template, File Control Parameters and File Management Data (FCI)
      tag: "6F"
      len: "31" #[49]
      val:
     x84: # EMV, Dedicated File (DF) Name
      tag: "84"
      len: "07" #[7]
      val: # Dedicated File (DF) Name. [Visa debit or credit]
     RID: "A000000003" # Registered Application Provider Identifier (RID) [Visa International] 
     PIX: "1010" # Proprietary Application Identifier Extension (PIX)
     xA5: # EMV, Template, FCI A5
      tag: "A5" 
      len: "26" #[38]
      val:
     x9F38: # EMV, Processing Options DOL (PDOL) 
      tag: "9F38" 
      len: "18" #[24]
     val: # Processing Options DOL (PDOL).
      x9F66: "9F6604"
      x9F02: "9F0206" # EMV, Authorised Amount (Numeric)
      x9F03: "9F0306" # EMV, Amount, Other (Numeric)
      X9F1A: "9F1A02" # EMV, Country Code, Terminal
      x95: "9505" # EMV, Terminal Verification Results (TVR)
      x5F2A: "5F2A02" # ISO 7816, Currency Code, Transaction
      x9A: "9A03" # EMV, Date, Transaction
      x9C: "9C01" # EMV, Transaction Type
      x9F37: "9F3704" # EMV, Unpredictable Number
     xBFOC: # EMV, FCI Issuer Discretionary Data tag: "BFOC" len: "08" #[8]
     val: # FCI Issuer Discretionary Data.
     x9F5A:
      tag: "9F5A"
      len: "05" #[5]
      val: "6008400643"

Reaguodama į mokėjimo programos paleidimą, kortelė siunčia parametrų rinkinį, kurį tikisi gauti iš terminalo – **PDOL** (_Processing Options Data Object List_). Terminalas turi atsakyti griežtai pagal šią seką.

**PDOL** gali skirtis priklausomai nuo kortelės. Bendras **PDOL** parametrų skaičius yra kelios dešimtys. 
Pažvelkime į **PDOL** atidžiau. Po žymeklio nurodytas ilgis yra griežtai nustatomas atsakymo iš terminalo į šią užklausą. Tuščias atsakymas užpildomas nuliais iki norimo ilgio.

#### PDOL užklausos analizė:

     9F 38 18 // Pradžios markeris **PDOL**. ilgis 18 (24 baitai) 
     9F 66 (ilgis 04) // Terminal Transaction Qualifiers (TTQ). Terminalo palaikomų protokolų rinkinys. 
     9F 02 (ilgis 06) // Nurašymo suma
     9F 03 (ilgis 06) // sekanti suma
     9F 1A (ilgis 02) // Šalies kodas pagal ISO3166-1 standartą.
     95 (ilgis 05) // Terminal Verification Results
     5F 2A (ilgis 02) // Valiutos kodas, kuria dirba terminalas, ISO4217 standartas
     9A (ilgis 03) // Data YYMMDD formate
     9C (ilgis 01) // Transakcijos tipas 
     9F 37 (ilgis 04) // Atsitiktinis skaičius 

Iki šiol visi perduoti duomenys yra identiški visoms šios kortelės operacijoms.

#### Įšėmimo užklausa – GET PROCESSING OPTIONS

     '80A8000023832136A0400000000000290000000000000004400000000000044023032300E011010300'

     80 A8 00 00 // Komanda GET PROCESSING OPTIONS (GPO)
     23 // Visas užklausos ilgis (35 baitų)
     83 // PDOL atsakymo markeris
     21 // PDOL atsakymo ilgis (33 baitų)
     36 A0 40 00 // Terminal Transaction Qualifiers (TTQ)
     00 00 00 00 29 00 // nurašymo suma (29,00 eurai)
     00 00 00 00 00 00 // sekanti suma 
     04 40 // Šalies kodas (440 - Lietuva)
     00 00 00 00 00 // Terminal Verification Results (TVR)
     04 40 // Valiuta (440 - euras) 
     23 03 23 // Data (23 kovo 2023)
     00 // Transakcijos tipas
     E0 11 01 03 // Atsitiktinis skaičius

Šis atsakymas aiškiai parodo, kaip terminalas, esantis Lietuvoje, prašo nurašyti nuo kortelės 29,00 eurus. Atkreipkite dėmesį į atsitiktinį skaičių pabaigoje (_E0110103_) tai yra [9F37 Unpredictable Number](https://www.emvlab.org/emvtags/show/t9F37/) parametras. Tai pirmasis kriptografijos ženklas. Ateityje šį skaičių kartu su transakcijos duomenimis kortelė turės pasirašyti kriptografiniu parašu. Tai suteikia terminalui galimybę kontroliuoti parašo iš kortelės tinkamumą ir apsaugo nuo pakartotinių atakų.

#### Kortelės atsakymas į - GET PROCESSING OPTIONS

     7762820200409404180101009F360202069F2608D6F56B8ABED78F239F10201F4AFF32A
     00000000010030273000000004000000000000000000000000000009F6C020080571348
     00997250511756D23122010000052099995F9F6E04238800009F2701809000

Šiame atsakyme yra **VISA** specifinių duomenų laukų, todėl naudojau analizatorių, kuris palaiko [VISA kortelių bekontakčio mokėjimo specifikaciją (VCSP)](https://iso8583.info/lib/VISA/VCPS/).

     x77: # EMV, Template, Response Message Format 2 
      tag: "77” 
      len: ”62” #[98]
      val: # Template, Response Message Format 2.
     x82: # VCPS, Application Interchange Profile (AIP) 
      tag: ”82” 
      len: ”02” #[2]
      val: # Application Interchange Profile (AIP).
     BOI: "00” B02: "40" # _1 - bit 7, Mobile handset - 
     x94: # EMV, Application File Locator (AFL) 
      tag: "94" 
      len: "04" #[4]
      val: # Application File Locator (AFL).
     SI: # AFL Record 
     B01: "18" # SFI [xxxxx] [3]
     B02: "01" # From record [1] 
     B03: "01" # To record [1] 
     B04: "00" # First hashed
     x9F36: # EMV, Application Transaction Counter (ATC) 
      tag: "9F36" 
      len: "02" #[2]
      val: "0206" # Application Transaction Counter (ATC).[518]
     x9F26: # EMV, Cryptogram, Application 
      tag: "9F26" 
      len: "08" #[8]
      val: "D6F56B8ABED78F23" # Cryptogram, Application.
     x9F10: # VCPS, Issuer Application Data (IAD) 
      tag: "9F10" 
      len: "20" #[32]
      val: # Issuer Application Data (IAD). 
     len: "IF" #[31]
     CVN: "4A" # Cryptogram Version Number (CVN) [74] 
     DKIv2: "FF" # Derivation Key Index (DKI) [255]
     CVRv2: # Card Verification Results 
      len: "3332************3030" # RFU 
     IDDv2: '0010****************************************0000" # Issuer Discretionary data
     x9F6C: # VCPS, Card Transaction Qualifiers (CTQ) 
      tag: "9F6C" 
      len: "02" #[2]
      val: # Card Transaction Qualifiers (CTQ).
     BO1: "00"
      0 - bit 1, Valid for contactless ATM transactions 
     B02: "80"
      1 - bit 8, CDCVM Performed
     x57: # ISO 7816, Track 2, Equivalent Data 
      tag: "57" 
      len: "13" #[19]
      val: '’4800********1756D********************F'' # Track 2, Equivalent Data.
     x9F6E: # VCPS, Form Factor Indicator (FFI) 
      tag: "9F6E" 
      len: "04" #[4]
      val: # Form Factor Indicator (FFI).
     BO1: "23" # Consumer Payment Device Form Factor 
     # ___00011 - bits 5-1, Consumer mobile phone 
     B02: "88" 
     # 1______ - bit 8, Passcode Capable 
     # ___1___ - bit 4, Two-way Messaging
     B03: "00" 
     B04: "00"
     x9F27: # EMV, Cryptogram Information Data (CID) 
      tag: "9F27" 
      len: "01" #[1]
      val: "80" # Cryptogram Information Data (CID)
      # 10____ - bits 8-7, ARQC
      # ___000 - bits 3-1 (Reason/Advice/Referral Code), No information given

_Application Interchange Profile_ (**AIP**) – yra informacija apie mokėjimo programos parametrus. Mūsų atveju **AIP** yra **00 40** . Apsvarstykime šio parametro reikšmes iš [EMV 4.3 3 knygos](https://www.emvco.com/wp-content/uploads/2017/05/EMV_v4.3_Book_3_Application_Specification_20120607062110791.pdf).

      -Pirmas baitas-
      |B8|B7|B6|B5|B4|B3|B2|B1|Meaning                                        |
      -------------------------------------------------------------------------
      |0 |- |- |- |- |- |- |- |RFU                                            |
      |- |0 |- |- |- |- |- |- |SDA supported                                  |
      |- |- |0 |- |- |- |- |- |DDA supported                                  |
      |- |- |- |0 |- |- |- |- |Cardholder verification is supported           |
      |- |- |- |- |0 |- |- |- |Therminal risk managment is to be performed    |
      |- |- |- |- |- |0 |- |- |Issuer Authentication is supported             |
      |- |- |- |- |- |- |0 |- |On device cardholder verification is supported |
      |- |- |- |- |- |- |- |0 |CDA supported                                  |
      -------------------------------------------------------------------------

      -Antras baitas-
      |B8|B7|B6|B5|B4|B3|B2|B1|Meaning                                        |
      -------------------------------------------------------------------------
      |0 |- |- |- |- |- |- |- |EMV mode is supported                          |
      |- |0 |- |- |- |- |- |- |RFU                                            |
      |- |- |0 |- |- |- |- |- |RFU                                            |
      |- |- |- |0 |- |- |- |- |RFU                                            |
      |- |- |- |- |0 |- |- |- |RFU                                            |
      |- |- |- |- |- |0 |- |- |RFU                                            |
      |- |- |- |- |- |- |0 |- |RFU                                            |
      |- |- |- |- |- |- |- |0 |Relay resistance protocol is supported C2      |
      -------------------------------------------------------------------------
