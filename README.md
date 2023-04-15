# Zadaci

## Web aplikacija za evidenciju zadataka

Projekt Zadaci je nastao na faksu kao projekt za konstrukcijske vježbe iz predmeta **Web programiranje na strani poslužitelja** i **Skriptni programski jezici**.

Tema projekta je bila kreirati program za evidenciju zadataka sa autorizacijom korisnika i korištenjem hijerarhija gdje klasa Komentar sadrži objekte klasa Korisnik i Zadatak.

Stranica prikazuje sva naučena znanja o sljedećim web tehnologijama: **AngularJs v1.6.9** uz **jQuery 3.2.1**, **PHP 7** i korišten je **Bootstrap 4.4.1** za dizajn. A za bazu se koristio **MySQL**.

[![My Skills](https://skills.thijs.gg/icons?i=angular,jquery,php,bootstrap,mysql)](https://skills.thijs.gg)

---

### Kada se prijavi u aplikaciju, korisnik može:

- vidjeti svoj profil i ažuirati njegove podatke
- posjetiti profile drugih ljudi s kojima radi na zadacima
- pregledavati svoje dovršene i nedovršene zadatke koje može također sortirati i pretraživati po nazivu
- korisnik svoje zadatke(koje on izvršava) može komentirati i označiti kao dovršene, te uređivati i brisati svoje komentare na njima
- pregledavati kreirane zadatke koje može također sortirati i pretraživati po nazivu i kreirati nove
- kreirane zadatke uređivati, komentirati i obrisati te uređivati i brisati svoje komentare na njima
- u slučaju da se riješeni zadatak od strane korisnika koji ga je kreirao ne smatra zaista dovršenim on ga može vratiti u izvršavanje

---

### Pokretanje projekta

Potrebno je instalirati [XAMPP](https://www.apachefriends.org), te preko toga pokrenuti **Apache** i **MySQL**.

Potom zalijepiti mapu **Zadaci** u `C:\xampp\htdocs\`.

Link za pristup bazi: [http://localhost/phpmyadmin/index.php](http://localhost/phpmyadmin/index.php).

Zatim u **phpmyadmin** kreirati bazu koja se zove `zadaci`(Character Set neka bude **Collation**) te potom importati `zadaci.sql` koji se nalazi ovdje u root-u projekta.

Link za pristup aplikaciji: [http://localhost/zadaci/index.php#!/](http://localhost/zadaci/index.php#!/).
