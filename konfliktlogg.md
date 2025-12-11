# Konfliktlogg

## Datum och tid
2025-12-11

## Konflikt
När vi försökte merga Erik's branch (erik-redigering) till main uppstod en merge-konflikt i filen `artikel.md`.

## Orsak
Både Anna och Erik hade lagt till nya sektioner efter introduktionen, men på olika platser i filen:
- Anna hade lagt till "Samarbetsfördelar" och "Versionshantering"
- Erik hade lagt till "Säkerhet och backup" och "Sammanfattning"

Eftersom båda hade utgått från samma ursprungliga version av main-branchen visste inte Git vilken ordning sektionerna skulle ha.

## Lösning
Vi löste konflikten genom att:
1. Öppna filen `artikel.md` och identifiera konfliktmarkörerna (`<<<<<<<`, `=======`, `>>>>>>>`)
2. Diskutera vilken ordning som var mest logisk för artikelns struktur
3. Kombinera båda ändringarna i följande ordning:
   - Introduktion
   - Samarbetsfördelar (Anna)
   - Versionshantering (Anna)
   - Säkerhet och backup (Erik)
   - Sammanfattning (Erik)
4. Ta bort konfliktmarkörerna
5. Spara filen och göra en commit med meddelandet "Lös merge-konflikt mellan Anna och Eriks ändringar"

## Resultat
Konflikten löstes framgångsrikt och alla sektioner från båda bidragsgivare finns nu med i artikeln i en logisk ordning.

## Lärdomar
- Kommunikation är viktigt när man arbetar i samma fil
- Merge-konflikter är normala och inget att vara rädd för
- Git ger oss verktygen att lösa konflikter på ett kontrollerat sätt
