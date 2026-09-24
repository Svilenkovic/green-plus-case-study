<a href="https://greenplus.rs/"><img src="media/cover.jpg" alt="Green Plus, naslovna strana na laptopu i telefonu" width="100%"></a>

# Green Plus

Sajt na jednoj strani za firmu za kompenzaciju reaktivne energije, koji kupca iz industrije vodi od računa za struju do merenja, opreme i ponude.

**[greenplus.rs](https://greenplus.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/green-plus) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Green Plus</td></tr>
  <tr><td><b>Delatnost</b></td><td>Kompenzacija reaktivne energije za industriju: merenje, projekat i ugradnja</td></tr>
  <tr><td><b>Lokacija</b></td><td>Beograd</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt na jednoj strani</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, GSAP, Lenis, JSON-LD</td></tr>
</table>

## O projektu

Green Plus meri, projektuje i ugrađuje kompenzaciju reaktivne energije sa EPCOS/TDK opremom, na niskom i srednjem naponu. Ono što prodaju mora prvo da se objasni, pa strana ide redom kojim kupac odlučuje: stavka za prekomerno preuzetu reaktivnu energiju na računu, merenje na licu mesta, proračun i ponuda, pa ugradnja.

Najveći deo posla radi forma. Traži firmu, kontakt osobu i, ako je poznat, mesečni iznos te stavke. Prima i sam račun kao PDF, JPG ili PNG do 10 MB, pa prvi razgovor počinje od brojeva umesto od opšteg pitanja o ceni. Zaštita od spama se ne vidi: pregledač u Web Workeru rešava mali zadatak sa servera dok posetilac kuca, a provera jednim klikom se pojavljuje samo ako to ne uspe.

## Šta sam uradio

- Celine o opremi za niski i srednji napon, postupku rada, vrstama kompenzacije, isplativosti i ESCO finansiranju, izvedenim radovima i referencama
- Grupe opreme povezane sa stranicama proizvođača i dva kataloga za preuzimanje u PDF-u
- Forma za ponudu sa poljem u koje se račun prevlači, CSRF tokenom, poljem-mamcem i nevidljivom proof-of-work proverom
- GSAP sa ScrollTrigger i DrawSVG dodacima i Lenis, sve sa istog servera, kao i fontovi
- Traka za poziv i slanje računa koja na telefonu stoji pri dnu ekrana
- Strukturisani podaci za firmu, usluge, galeriju i česta pitanja, i mapa sajta u kojoj su i katalozi

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 98 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `FAQPage`, `ImageGallery`, `Organization`, `ProfessionalService`, `Service`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Green Plus, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Green Plus, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Oprema i tehnički podaci predstavljeni po grupama proizvoda">
<sub>Oprema i tehnički podaci predstavljeni po grupama proizvoda</sub>

<img src="media/inner-2.webp" alt="Izvedeni radovi sa fotografijama opreme na lokaciji">
<sub>Izvedeni radovi sa fotografijama opreme na lokaciji</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
