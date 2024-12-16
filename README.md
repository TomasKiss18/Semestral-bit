# Semestral-bit

Analýza bezpečnosti RFID/NFC

Tento repozitár sa venuje semestrálnemu projektu z predmetu BIT

Nakoľko je repozitár verejný, a pracujem v ňom s niektorými mojími osobnými kartami ktoré sú stále aktívne(niektoré nie) a je možné ich stále použíť v plnej prevádzke nachádzajú sa tu z týchto kariet výlučne fotografie so zamazanými dátami aby nebolo možné kartu zneužívať a replikovať. V samotnej dokumentácii sú dáta zobrazené v plnej miere.

Tento repozitár obsahuje rôzne súbory týkajúce sa bezpečnosti kariet, testovania NFC technológií a analýzy kariet ako Mifare Classic, Mifare Desfire a NTAG či v dokumentácii spomenuté bankové karty. Súbory zahŕňajú technickú dokumentáciu, obrázky a videá súvisiace s rôznymi analýzami a testovaním NFC kariet(emuláciou mifare desfire ako aj prelamovaním sektorov Mifare Classic karty).

Súbory:
BIT - Analýza bezpečnosti kariet dokumentácia Kiss.pdf
Samotná dokumentácia semestrálneho projektu zameraná na bezpečnostnú analýzu rôznych typov NFC kariet.

Dual_line_datasheet_COMINFO_24_0.pdf
Technická špecifikácia pre produkt COMINFO, súvisiaci s NFC technológiou. Obsahujúca čítačku Dual line ktorá bola použítá pri testovaní vhodnej emulácie ISIC karty.

LICENSE
Licenčná dohoda určujúca podmienky používania tohto repozitára a kódu.

MIFARE_DESFIRE_ISIC_data.jpg
Obrázok s informáciami o MIFARE DESFire ISIC karte so zamazanými dátami "UID".

Mifare_desfire_funkcny_isic_zamazana.jpg
Fotografia Flipper zariadenia s obrázokom dát Mifare DESFire, ktorý obsahuje zamazané informácie nakoľko je karta stále funkčná.

Popis_ISIC_karty_MIFARE_CLASSIC.png
Obrázok ilustrujúci rozdelenie sektorov a blokov vrámci ISIC karty, technológia MIFARE CLASSIC.

README.md
Tento súbor - obsahuje informácie o projekte, inštrukcie a popis repozitára.

bank_card_unreadable.jpg
Obrázok nečitateľnej Visa Debit bankovej platobnej karty ktorá je stále aktívna, avšak vypíše správu: "Can't parse data from app"

bitifli.jpg
bitifli_flipper_upravená.jpg
Tieto dva súbory sme v dokumentácii nespomenuli, avšak táto karta slúži na overenie [OBYČAJNÝM UID] transakcii z aplikácie bitlifi od firmy AnyCoin. Táto firma sa zaoberá zjednodušovaním **User Experience** a platbami cez Lightning Network (druhá vrstva BTC). Je však možné túto kartu oskenovať a zaplatiť ňou v ich internom POS terminály avšak kvôli tomu, že sa v karte nachádza iba ISO tag, karta nemá žiadne špeciálne overenie čo považujeme za zraniteľnosť nakoľko už sa jedná o istú "alternatívnu formu" platenia a častokrát sú peňažné prostriedky veľmi citlivou oblasťou pre ľudí. Predsa si povedzme, kto by chcel prísť o peniaze? Aj keď len alternatívne...  

Je to teda upravený obrázok zariadenia Flipper Zero, s naskenovanou bitlifi alternativnou platobnou kartou spojenou s aplikáciou klienta.

diamond_karta_naskenovana.jpg
Skenovaná verzia Diamond karty - do posilňovne. Jedná sa o EM4100 kartu ktorá je ľahko čitateľná.

old_bank_card.jpg
Obrázok starej neplatnej bankovej karty Master card, ktorá zobrazuje finančnú menu ako aj štát v ktorom bola vidaná spolu s číslom karty a validačným dátumom. CVV číslo sa tu nenachádza.

prelomene_Mifare_classic.mp4
Video ukazujúce proces prelomenia Mifare Classic karty.

presvietená_NTAG_karta.jpg
Fotografia NTAG karty

testovanie_emulácie.mp4
Video ukazujúce testovanie emulácie NFC karty Mifare desfire - ISIC karty.

white_card_NTAG215.jpg
Obrázok bielej NTAG215 karty, používaný na testovanie.

white_card_NTAG215_presvietená.jpg
Fotografia NTAG215 karty s dodatočným presvietením na zobrazenie detailov vnútra karty (čip, obvod ktorý zachytáva radio frekvenčné vlny).
