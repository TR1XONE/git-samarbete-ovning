# Inlämning: Samarbete med Git och GitHub

## Medverkande

- Anna Andersson
- Erik Eriksson

## Länk till GitHub-repository

[https://github.com/TR1XONE/git-samarbete-ovning](https://github.com/TR1XONE/git-samarbete-ovning)

## Reflektion över arbetet

### Hur gick arbetet?

Arbetet gick överlag mycket bra. Vi lyckades följa instruktionerna och genomföra alla steg i uppgiften, från att skapa ett gemensamt repository till att lösa en merge-konflikt. Samarbetet flöt på smidigt och vi hade en bra dialog under hela processen, vilket var avgörande när vi stötte på problem.

### Vad fungerade bra?

- **Branching-strategin:** Att arbeta i separata branches (`anna-redigering` och `erik-redigering`) var väldigt effektivt. Det gjorde att vi kunde arbeta parallellt utan att vara rädda för att skriva över varandras ändringar. Vi kunde fokusera på våra egna delar av texten i lugn och ro.
- **Pull Requests:** Användningen av pull requests gav oss en bra möjlighet att granska varandras arbete innan det slogs samman med huvudbranchen (`main`). Kommentarfunktionen var särskilt användbar för att ge feedback och ställa frågor.
- **Commit-meddelanden:** Vi försökte skriva tydliga och beskrivande commit-meddelanden. Detta gjorde det enkelt att följa historiken och förstå vilka ändringar som gjorts i varje commit.

### Vad var utmanande?

Den största utmaningen var att hantera den merge-konflikt som uppstod. När vi skulle slå samman den andra pull requesten hade vi båda redigerat samma del av filen `artikel.md`. Först kändes det lite läskigt med alla konfliktmarkörer (`<<<<<<<`, `=======`, `>>>>>>>`) som dök upp i filen. Det krävde att vi satte oss ner tillsammans, kommunicerade och kom överens om hur vi skulle kombinera våra ändringar på bästa sätt. Dokumentationen av denna process i `konfliktlogg.md` var också en bra övning i sig.

### Vilka delar känner ni att ni behöver öva mer på?

Även om vi lyckades lösa merge-konflikten, är det definitivt ett område vi behöver öva mer på. Vi kan tänka oss att konflikter kan bli betydligt mer komplexa i större projekt med fler filer och fler utvecklare. Vi skulle också vilja bli snabbare på att använda Git-kommandon i terminalen utan att behöva slå upp dem lika ofta. Att arbeta mer med `rebase` istället för bara `merge` kan också vara ett intressant nästa steg för att hålla historiken renare.
