# Rešene naloge za predmet "Varnost in Zaščita"
Pred vami so rešene naloge za predmet varnost in zaščita na FERI.
Naloge so rešene v programskem jeziku Ruby.

Avtor: [Oto Brglez](https://github.com/otobrglez/)

## 1. Naloga

Na vajah boste prejeli datoteko s šifriranim besedilom, ki ga morate dešifrirati s pomočjo tehnike frekvenčne analize. Vaša naloga je izdelava programa za frekvenčno analizo, ki omogoča (delno) razkritje besedila in ročno zamenjavo posameznih črk ključa. Ker bo vaš program omogočil samo delno razkritje besedila, boste s pomočjo ročne zamenjave črk ključa prišli do popolnoma dešifriranega besedila.

V okviru naloge izdelajte program, ki vključuje naslednje funkcionalnosti:

* frekvenčno analizo šifriranega besedila,
* frekvenčno analizo referenčnega besedila,
* s pomočjo frekvenčne analize uporabniku omogoča (delno) razkriti šifrirano besedilo,
* predogled delno razkritega besedila,
* ročno zamenjavo posameznih črk ključa (POZOR: če, na primer, zamenjate "a" s "t" mora program tudi avtomatično menjati "t" z "a", saj se v nasprotnem primeru izgubi sledljivost za črkami), odpiranje (šifriranega besedila in referenčnega besedila) in shranjevanje besedila (dešifriranega) v tekstovno datoteko.

Nalogo lahko izvedete s poljubnim programskim orodjem in programskim jezikom. 
Če uporabljate dodatne knjižnice, jih vključite v projekt. Program naj ima okenski uporabniški vmesnik, preko katerega lahko vnesemo parametre in pridobimo rezultate.

Za preverjanje pravilnosti delovanja programa, uporabite testni datoteki.

Pri zagovoru naloge je potrebno poznati izvorno kodo programa in princip delovanja tehnike frekvenčne analize.