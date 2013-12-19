#Testfall [1.3 Boka båtplats.](AF/1.3 Boka båtplats.md)

I detta testfall är målet att undersöka så att en klubbmedlem enkelt kan boka en båtplats som passar sin båt.

##Förkrav

Logga in som klubbmedlem: Användare: testMember, Lösenord: password.

##Efterkrav

Kontrollera så att en rad har skapats i databasen med korrekt id, namn, båtreg och båtplats.

##Testfall

### TF 1.1 Boka båtplats åt båt1

1. Gå till sidan för lediga båtplatser (www.dengladepiraten.se/batplatser)
2. En lista med lediga båtplatser visas och alternativ att filtrera efter någon av dina båtar: båt1, båt2, båt3
3. Välj båt1.
4. En lista presenteras med lediga båtplatser som passar för vald båt: 2, 4, 5, 29, 44.
5. Välj båtplats 2.
6. Pris och information om båtplatsen presenteras och får val boka eller avbryt.
7. Klicka på boka.
8. Ett meddelande presenterar att båtplatsen nu är bokad.

### TF 1.2 Boka båtplats åt båt2

1. Gå till sidan för lediga båtplatser (www.dengladepiraten.se/batplatser)
2. En lista med lediga båtplatser visas och alternativ att filtrera efter någon av dina båtar: båt1, båt2, båt3
3. Välj båt2.
4. En lista presenteras med lediga båtplatser som passar för vald båt: 4, 18, 51.
5. Välj båtplats 18.
6. Pris och information om båtplatsen presenteras och får val boka eller avbryt.
7. Klicka på boka.
8. Ett meddelande presenterar att båtplatsen nu är bokad.

### TF 1.3 Boka båtplats åt båt3

1. Gå till sidan för lediga båtplatser (www.dengladepiraten.se/batplatser)
2. En lista med lediga båtplatser visas och alternativ att filtrera efter någon av dina båtar: båt1, båt2, båt3
3. Välj båt3.
4. En lista presenteras med lediga båtplatser som passar för vald båt: 4, 55.
5. Välj båtplats 55.
6. Pris och information om båtplatsen presenteras och får val boka eller avbryt.
7. Klicka på boka.
8. Ett meddelande presenterar att båtplatsen nu är bokad.

##Alternativa testfall

### TF 1.4 3A: Båtplatsen passar ej någon båt.

1. Gå till sidan för lediga båtplatser (www.dengladepiraten.se/batplatser)
2. En lista med lediga båtplatser visas: 2, 4, 5, 18, 29, 44, 51, 55, 60.
3. Välj båtplats 60.
4. Pris och information om båtplatsen presenteras och ett meddelande skrivs ut att det ej finns någon båt som passar på båtplats.

### TF 1.5 3B: Båtplatsen passar flera båtar.

1. 1. Gå till sidan för lediga båtplatser (www.dengladepiraten.se/batplatser)
2. En lista med lediga båtplatser visas: 2, 4, 5, 18, 29, 44, 51, 55, 60.
3. Välj båtplats 4.
4. Pris och information om båtplatsen presenteras och får val boka eller avbryt.
5. Klicka på boka.
6. En lista presenteras av vilka båtar som passar på denna platsen: båt1, båt2, båt3.
7. Välj båt1 och klicka på boka.
8. Ett meddelande presenterar att båtplatsen nu är bokad.

### TF 1.6 8: Användaren vill ej ha båtplatsen.

1. Gå till sidan för lediga båtplatser (www.dengladepiraten.se/batplatser)
2. En lista med lediga båtplatser visas och alternativ att filtrera efter någon av dina båtar: båt1, båt2, båt3
3. Välj båt1.
4. En lista presenteras med lediga båtplatser som passar för vald båt: 2, 4, 5, 29, 44.
5. Välj båtplats 2.
6. Pris och information om båtplatsen presenteras och får val boka eller avbryt.
7. Klickar på avbryt.
8. Lediga båtplatser presenteras igen.

