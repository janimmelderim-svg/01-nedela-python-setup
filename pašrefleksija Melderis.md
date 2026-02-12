**1. nedēļa — Pašrefleksijas jautājumi**

Atbildi uz šiem jautājumiem saviem vārdiem. Mērķis nav “pareiza atbilde” — mērķis ir pārliecināties, ka tu saproti, ko esi iemācījies. Ja kādā punktā jūties nedrošs — tas ir signāls, ka jāpiestrādā.

Iesniedz šo dokumentu kopā ar pārējo mājasdarbu.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Koncepti

**1.	Kas ir programma? Kā tu to izskaidrotu cilvēkam, kurš nekad nav programmējis?**

Programma ir instrukciju kopa, kas nosaka operāciju secību, ko izpilda dators datu apstrādes procesā. Cilvēkam, kas nekad nav programmējis es to izskaidrotu, kā instrukciju. Lai izpildītu instrukciju, jāseko loģiskiem soļiem, kas norādīts, lai sasniegtu rezultātu.



**2.	Kas ir algoritms? Kā tas atšķiras no vienkāršas instrukcijas?**

Algoritms ir veicamo darbību priekšraksts kāda noteikta rezultāta sasniegšanai vai uzdevumu risināšanai. Tas atšķiras no instrukcijas sekojoši :

1\)	Algoritms ir vienmēr precīzs, bet instrukcija var būt neskaidra;

2\)	Instrukcijā var pārprast soļus un tos izlaist, bet algoritmā izlaižot soļus nevar nonākt pie rezultāta.

3)	Kādas trīs īpašības padara algoritmu derīgu (valid)? Pastāsti katru saviem vārdiem un dod piemēru, kas šo īpašību pārkāpj.



1\.	Precizitāte. Jābūt precīzam norādījumam. 

Parasti skaitliska vērtība vai noglabāta vērtība. Piemēram: Pievieno 100 gramus cukura (pareizi) pievieno sauju cukura (nenoteikta vērtība, var pārprast, katram sauja atšķiras)



2\.	Galīgums, jeb beidzamība. 

Algoritms nav īsts algoritms, ja tas nekad nebeidzas. Tas var atgriezties pie iepriekšēja nosacījuma, ja tas neizpildas un darīt līdz izpildas. Piemēram: pievieno 100 gramus cukura  atgriezties pie iepriekšējā soļa (šis nav algoritms, bet gan nebeidzams cikls). Pievieno 100 gramus cukura  pievieno 5 gramus sāls  apmaisi pievienoto (šis ir algoritms ar nodefinētiem soļiem uz rezultātu)

3\. Algoritmam jādod rezultāts

Tas atgriežas pie iepriekšējā soļa, ka algoritms navr būt bezgalīgs cikls, tam beigu beigās jādod rezultāts. Piemēram: Pievieno 100 gramus cukura  pievieno 5 gramus sāls  apmaisi pievienoto  gatavs maisījums (šis algoritms nonāk pie rezultāta)

&nbsp;

**3.	Ko nozīmē “secīga izpilde” (sequential execution)? Kāpēc datoram ir svarīgi, kādā secībā soļi tiek izpildīti?**

1\.	Šeit atkal nonākam pie iepriekš iztirzātā. Algoritmam nepieciešama secīga izpilde neizlaižot soļus, parasti secībā kā tas ir uzrakstīts no augšas uz leju. Šeiti r runa par konkrētību. Dators neizlaiž soļus, ja vien tas nav norādīts. Tas stingri seko algoritmam un secīgai izpildei. Tam nav brīva domāšana. Piemēram: kad lieku IKEA mēbeles es parasti tās mēģinu salikt bez instrukcijas. Kad nonāku strupceļā, tad sāku skatīties instrukciju un izpildīt sacīto bieži vien izlaižot soļus. Bet dators nespēj pats “uz savu galvu” izpildīt uzdevumu. Tam nepieciešama instrukcija, kuru tas secīgi pilda. Nebūs skaidri soļi un secīga instrukcija algoritms nesanāks un būs errors.



**4.	Izskaidro modeli “ievade → apstrāde → izvade” ar vienu konkrētu piemēru no ikdienas vai no sava mājasdarba.**

Mācoties python sākumā pie tutorial ir pavisam vienkārša saskaitīšanas ievade. Izrādās, ka python ir arī parasta kalkulatora funkcija. Devu viņam saskaitīt 1 un 2.

1\.	Ievade: “1+2”

2\.	Apstrāde: 1 saskaitīšana 2

3\.	Rezultāts: 3

**5.	Kas ir interpretators (interpreter) un ko tas dara ar tavu Python kodu?**

Varētu teikt, ka interpretators ir tulks. Rakstot python kodu un izpildot komandu print python interpretators tulko pa vienai rindiņai un pārbauda vai nav kļūdu. Ja ir kļūda, tad tas to uzreiz arī pasaka.



**6.	Kāda ir procesora (CPU) un atmiņas (memory) loma programmas izpildē? Izskaidro vienkāršoti, saviem vārdiem.**

Vienkāršoti – procesors ir smadzenes, kas kalkulē, domā, aprēķina, visualize, bet atmiņa ir kā glabātuve.



**7.	Kas notiek, ja tavā kodā ir sintakses kļūda? Kāpēc programma netiek izpildīta pat daļēji?**

Tas būtu līdzīgi kā nepabeigt, teikumu, neizskaidrot visu līdz galam vai runāt citā valodā. Ja nav skaidrs darāmais vai ta sir nesaprotams, tad programma nespēj to izpildīt.

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

**Praktiskie darbi**



**8.	Vai Python ir veiksmīgi uzstādīts tavā datorā? Kādu Python versiju parāda python --version?**

Jā, 3.14.3



**9.	Vai tu spēj palaist kodu no termināļa vai IDE? Apraksti, kā tu to dari — kādus soļus veic.**

Jā, terminālī ierakstu kodu uz mapi, kur atrodas fails, palaid python failu (.py)

IDE atver vai izveido .py failu, spiež “run”



**10.	Vai tu spēj izveidot .py failu un to izpildīt? Kas notiek, ja mēģini palaist failu, kura nav?**

Jā, ja nav fails, tad parādās kļūdas paziņojums



**11.	Vai tu uzrakstīji un palaidi savu “Hello, world!” programmu? Kas tieši parādījās ekrānā?**

Jā, ekrānā, nākošajā rindā, parādījās dotais teksts bez pēdiņām



**12.	Vai tu veiksmīgi nomainīji izvades tekstu? Ko tu mainīji un kāds bija rezultāts?**

Jā, nomainīju uz print("Vai esi gatavs?") un parādīja Vai esi gatavs?

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

**Refleksija**

**13.	Kāpēc programmētājam ir jābūt precīzam katrā instrukcijā? Ko dators nevar “uzminēt”?**

Dators nevar uzminēt, ko esmu vēlējies panākt. Jau iepriekš minēju, ka algoritmam jābūt precīzam, galīgam un jādod rezultāts. Ja nebūs precizitāte un galīgums, tad nebūs rezultāts.



**14.	Kāpēc precizitāte ir svarīga programmās? Apraksti vienu situāciju, kur neliela neprecizitāte varētu radīt lielu problēmu.**

Jebkura neprecizitāte izmaina rezultātu vai vispār nav rezultāts un ir errors. Teiksim, ja neieliek iekavu, nav pēdiņas nebūs vispār rezultāts. Vai, piemēram, \* vietā ieliek \*\*, tad rezultāts nebūs gaidāmais.



