# ThePivi.github.io
Ez lesz a bemutatkozó oldalam

#Innen táplálkoztam:
https://www.youtube.com/watch?v=bB14uo0Tu5A
https://codepen.io/andornagy/pen/xhiJH
https://www.gamedev.tv/courses/enrolled
https://colorhunt.co/palettes/winter

#Localization:
Valamit ki kell rá találni hogy le lehessen könnyen cserélni a szövegeket a következő nyelvek között:
Angol
Magyar
Holland

#Menü struktúra:
Menü neve - Címsorban
-Magamról - Nevem
  - Tapasztalat - "karrierút"
    - Időrendbe szedve
    Itteni projektek
      (24 matematikai oktató játék)
    - Érdeklődés
    amit eddig
    - Játék tervezés
    - ötletelés
      - Megvalósult
        - RPG character editor
        - támad a mars Pascal
        - hacker C++ builder
        - Flash légvédelmi ágyús
      - Félbehagyott
        - Pascal
    - fejlesztés
  - Karrier célok - "dreams"
    amit ez után
    - Játék tervezés
    - ötletelés
    - fejlesztés
    - álom játék elkészítése
  - Nemzetiség
  - Amit még megosztanék
  Professzionalításos rész
-Irreleváns - OtherWorld
  - Fa égetésről
  - Hobby-k
    - amik kikapcsolnak
  - Célok az életben
    - farm
    - állatok
    Cicás projektek és az ananocszágok
    - család
  - Stabilítás
  - Peacefull

Menü működése Drag and Drop rendszerrel
 A menüpontok stabil működésének logikája:
  - Kell egy globális változó, amelyikben eltároljuk, hogy melyik Chip van benne a socket-ben (chip ereteti helye)
  - Amikor egy draggable elemet beteszünk a socket-be, akkor először továbbítjuk egy függvénynek, a jelenleg bennlevő helyét, és ami benne van, azt visszarakatjuk.
  - majd ami beletesszük és tároljuk azt amelyiket belehúztuk
 A másik verzió az:
  - hogy azt tárolom el, amelyik socket üres. csak abba lehet húzni chipet. Így vissza kell tenni mielőtt egy újat beletennénk a socket-ba.
  - Ezt talán úgy egyszerűbben lehet majd vezérelni, hogy láthatatlan felületet húzok minden draggable item fölé, ha bekerül egy chip, ami nem az, amit beletettem.
    - Ezután visszatételnél minden átlátszó felület eltűnik majd
    - Ehez viszont listába kell szedni az összes olyan objektumot, amiken módosítani kell.
