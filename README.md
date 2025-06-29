LOC celog projekta je 170

Calculator.java – 134 loc -  rezultat statičke analize u IntelliJ okruženju: Kada sam pokrenula analizu dobila sam set nepravilnosti od koji su 3 kritična I 2 slabija (upozorenja). Reč je o sledećem: 
- Control flow issues (logičke nepravilnosti - if uslov u kom se deo koda ponavlja u više grana (if, else if, else). Taj zajednički deo može da se izvuče iz uslova, da se ne piše više puta.
- Data flow – promenljiva koja može biti null
- Java language level migration aids – znači da Java može da se unapredi
- Verbose or redundant code constructs – return na kraju metode koja ne vraća vrednost je suvišan


Start.java – 19 loc – analizu sam odradila u IntelliJ okruženju – Zapažanje: ispravno napisan, čist po stilskim i logičkim pravilima, ne sadrži sumnjive konstrukcije


LICENSE – 17 loc – kada sam pustila analizu u IntelliJ dobila sam odgovor “typo” za “dresevic” što konkretno znači da možda reč nije pravilna I da je treba ispraviti. Ja konkretno mislim da u ovom slucaju to treba ignorisati. 
