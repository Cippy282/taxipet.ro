# taxipet.ro – site TAXI PET&GO

Site static (HTML/CSS), găzduit gratuit pe GitHub Pages, domeniu **www.taxipet.ro** (înregistrat la Hostico).

## Plan SEO integrat

### 1. Cuvinte-cheie țintă (integrate în titluri, descrieri, H1/H2, texte, nume și `alt` ale pozelor)

| Prioritate | Cuvânt-cheie | Pagina țintă |
| --- | --- | --- |
| 1 | închiriere dubă Bacău / închiriere autoutilitară Bacău | `/inchiriere-duba-animale-bacau` |
| 1 | închiriere dubă pentru câini / mașină cu cuști pentru câini | `/inchiriere-duba-animale-bacau` |
| 1 | rent a car pet friendly Bacău / închiriere mașină cu animale de companie | `/` |
| 2 | închiriere mașină fără șofer Bacău | `/`, `/tarife-si-conditii` |
| 2 | tarif / preț închiriere dubă Bacău | `/tarife-si-conditii` |
| 2 | transport câine mare mașină, drum la veterinar cu câinele | `/blog...` |
| 3 | expoziții canine Bacău / Nord-Est | `/blog-expozitii-canine-nord-est-ce-iei-cu-tine` |
| 3 | ajutor veterinar gratuit Bacău, întreprindere socială Bacău | `/ajutor-pe-patru-roti`, `/despre-noi` |
| Local | Bacău, Onești, Moinești, Comănești, Buhuși, Roman, Piatra Neamț | `areaServed` + texte |

### 2. SEO tehnic (implementat)
- Titlu unic + meta description unică pe fiecare pagină, URL-uri curate cu cuvinte-cheie, `canonical` pe `https://www.taxipet.ro`.
- Date structurate schema.org: `AutoRental` (firmă locală, telefon, e-mail, zonă deservită, program), `FAQPage`, `BreadcrumbList`, `Service`, `BlogPosting`.
- `sitemap.xml`, `robots.txt`, `llms.txt`, Open Graph (Facebook/WhatsApp preview), favicon, manifest.
- Imagini WebP comprimate, cu nume de fișier și `alt` descriptive, `width/height` și lazy-loading.
- Mobil-first, meta geo Bacău, `lang="ro"`, diacritice corecte.
- Bara fixă de contact (e-mail, WhatsApp, telefon 0758 420 574) pe toate paginile.

### 3. Pași după publicare (necesită conturile beneficiarului)
1. **Google Search Console**: adăugare proprietate `taxipet.ro` (verificare prin înregistrare TXT în DNS la Hostico), trimitere `https://www.taxipet.ro/sitemap.xml`.
2. **Google Business Profile**: categorie „Agenție de închirieri auto”, zonă de serviciu Bacău, telefon 0758 420 574, site www.taxipet.ro, poze cu duba. Cel mai important pas pentru căutările „lângă mine” și Google Maps.
3. **Recenzii**: link de recenzie Google trimis pe WhatsApp după fiecare închiriere.
4. **Backlink-uri locale**: profil pe pagina Facebook/Instagram, linkuri de la clinicile veterinare partenere (ex. Amon Vet Care), asociații de protecție, directoare locale de firme.
5. **Conținut**: un articol nou pe lună în `/blog` (subiecte: vara și câinele în mașină, pensiuni pentru câini în Bacău, târguri de adopție, mutarea cu animalele).
6. **Bing Webmaster Tools**: import din Search Console.
7. Revizuire la 3 luni: interogări din Search Console → ajustare titluri și texte.

## Structura
`/` · `/inchiriere-duba-animale-bacau` · `/tarife-si-conditii` · `/ajutor-pe-patru-roti` · `/intrebari-frecvente` · `/contact` · `/despre-noi` · `/blog` (+3 articole) · `404.html`

Proiect cofinanțat de Uniunea Europeană – GO SES URBAN, cod SMIS 311122.
