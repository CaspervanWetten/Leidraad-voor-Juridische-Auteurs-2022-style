# Leidraad voor Juridische Auteurs 2022 style

 Een Citation Style Language (CSL) specificatie wat de leidraad voor Juridische auteurs volgt

Heeft nu direct support voor:

* Jurisprudentie verwijzingen
  * [Gerechtshof] [datum], [ECLI nummer] *(roepnaam arrest)*
  * Let (voorlopig?) nog niet op het publicatie tijdschrift (e.g. *NJ*) of A-G conclusies.
  * Door in Zotero een 'pagina' te specificeren, wordt het automatisch as r.o. toegevoegd
  * De Zotero connector kan de correcte informatie 'out of the box' uit rechtspraak.nl trekken, alleen de roepnaam van het arrest kan, indien gewenst, toegevoegd worden als "Short Title"
  * Werkt grotendeels met eur-lex, alleen de ECLI moet handmatig toegevoegd worden aan het "docket number" veld. Ook pakt hij altijd het woord "zaak" mee, dit is niet deel van de voetnoot volgens de leidraad.
* Artikelen
* Boeken
  * Noch boeken noch artikelen kunnen direct door de connector uit InView Essentials ge-exporteerd worden, 'internationalere' bronnen (scholar etc.) werken wel gewoon
* correcte volgens de leidraad citatie voor:
  * kamerstukken
  * parlementaire documenten
  * (Europese) regelgeving
  * handboeken en
  * bijdragen in boeken
* kan niet gegarandeerd worden, maar hij doet zijn best.
