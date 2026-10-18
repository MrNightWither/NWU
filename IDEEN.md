# Ideen für NightWither Unity

Stand: 18.10.2026. Gesammelt nach einem Blick über alle Repos
(`Socials-nwu`, `discord`, `events`, `kooperation`, `shop`, `donation`,
`spotifypage`, `spotifystreamer.bot`, `Impressum-nwu`, `Datenschutz-nwu`,
`nightwither-admin`, `NWU-Avatars`). Das private Repo `Code` ist nicht berücksichtigt.

## Für dieses Repo (`NWU`)

- [ ] **Gemeinsames Fundament** (Empfehlung): eine zentrale Quelle für Schriften
      (Inter, Rajdhani), Favicon, Krone, Farben, 404-Seite und Fußzeile, z. B. unter
      `assets.nightwither.de`. Heute hat fast jedes Repo eigene Kopien, teils doppelt
      (Schriften im Hauptordner und in `fonts/`). Einmal ändern, überall gleich.
- [ ] **Gemeinsamer Header und Footer als Skript**: gleiche Navigation auf allen Seiten,
      Live-Anzeige (roter Schimmer, wenn gestreamt wird), Links zu Impressum und Datenschutz.
- [ ] **NWU-Worker als zentrale API**: Live-Status, Follower-Zahlen und Streamplan an einem
      Ort; Seiten, Overlays und Admin lesen alle von dort. Anschluss an den bestehenden
      Worker `nwu-avatare` aus `NWU-Avatars` prüfen.

## Für bestehende Repos

- [ ] **Admin** (`nightwither-admin`): Reiter für Avatare (Häuser, Level, Ruhm,
      `!levelup` per Knopf), Shop-Bestellungen und Spendenziele.
- [ ] **Hauptseite** (`Socials-nwu`): kleiner Teaser für Haus-Pokal und Reise-Karte
      („Haus des Mondes führt“). Die Avatar-Seite selbst bleibt nur über Twitch verlinkt.
- [ ] **Shop** (`shop`): Haus-Merch für Mond, Blut, Nebel und Flamme mit Wappen.
- [ ] **Events** (`events`): Haus-Turniere und Morrígans Prüfung als feste Events,
      Gewinner automatisch in der Chronik.
- [ ] **Donation** (`donation`): Spendenziel, das auf der Reise-Karte Essenz bringt.
- [ ] **Avatare** (`NWU-Avatars`), schon in `docs/UEBERGABE.md` vorgemerkt:
      Kanalpunkte und Verabschiedung am Stream-Ende (am schnellsten umsetzbar),
      später Kreaturen-Kämpfe und „Das Erwachen“.

## Fürs Streamen

### Story & Häuser
- [ ] **Haus-Abstimmung über das Spiel**: jedes Haus stimmt ab, was gespielt wird oder welche Challenge kommt.
- [ ] **Morrígans Fluch**: per Kanalpunkte eine Strafe auslösen (z. B. nur Pistole, invertierte Maus, kein HUD), Fluch-Karte mit Countdown im Overlay.
- [ ] **Haus-Kopfgeld**: Ziel im Spiel setzen, das Haus, das vorher richtig tippt, bekommt Ruhm.
- [ ] **Verräter-Event**: ein zufälliger Zuschauer sabotiert heimlich sein Haus per Flüster-Aufgabe und wird am Ende enthüllt.

### Interaktion
- [ ] **Boss-Fight aus dem Chat**: bei Raid oder Hype Train greifen alle Figuren eine Kreatur an, jede Nachricht ist ein Treffer.
- [ ] **Vorhersage mit Ruhm**: Twitch-Vorhersagen geben dem Haus der Gewinner zusätzlich Ruhm.
- [ ] **Thron der Zitadelle**: der aktivste Chatter sitzt am Ende auf dem Thron, Abzeichen bis zum nächsten Stream.
- [ ] **Chat baut mit**: gemeinsames Ziel pro Stream (z. B. 1.000 Nachrichten), dann weicht Nebel auf der Reise-Karte.

### Formate
- [ ] **Haus-Turnier am Wochenende**: Zuschauer spielen für ihr Haus, Ergebnisse in die Chronik.
- [ ] **„Ungefiltert“-Talk**: feste Talk-Runde mit Fragen aus dem Discord, Ausschnitte für TikTok und Spotify.
- [ ] **Gäste aus der Kooperation**: Partner-Streamer als Botschafter eines Hauses mit eigener Figur.
- [ ] **Monatsfinale**: Pokal-Verleihung mit Prolog-Stimme, Krone und Rückblick.

### Technik & Wachstum
- [ ] **`!clip`-Markierung**: Chat setzt Markierungen, daraus Clips für TikTok und Shorts.
- [ ] **Multistream-Rangliste**: Twitch, Kick, TikTok und YouTube im Wettstreit um Essenz.
- [ ] **Merch-Drop live**: Haus-Hoodie im Stream enthüllen, 24 Stunden Rabattcode.

## Minispiele

### Mit den Figuren im Overlay
- [ ] **Wettrennen der Häuser** (`!rennen`): Chat-Nachrichten geben der eigenen Hausfigur Schub. *(Favorit)*
- [ ] **Tauziehen**: zwei Häuser, 60 Sekunden `!zieh`. *(Favorit, wenig Aufwand)*
- [ ] **Letzter steht**: Nebel zieht sich zusammen, Blitze, wer übrig bleibt, holt Ruhm.
- [ ] **Schatzsuche**: Truhe am Rahmen versteckt, raten mit `!grab oben/links/…`.
- [ ] **Fang den Raben**: Rabe fliegt durchs Bild, wer zuerst `!fang` schreibt, sammelt ihn. *(Favorit, wenig Aufwand)*

### Rate- und Reaktionsspiele
- [ ] **Wer bin ich?**: verschwommene Figur oder Wappen wird langsam schärfer.
- [ ] **Rune tippen**: Wort in Runenschrift, erste richtige Übersetzung gewinnt.
- [ ] **Höher oder tiefer**: Serie mit `!hoch`/`!tief`, wer falsch liegt, fliegt raus.
- [ ] **Emote-Kette**: vorgegebene Emote-Reihenfolge nachbauen, Fehler setzt zurück.

### Glück & Risiko
- [ ] **Würfel der Morrígan** (`!wurf`): einmal pro Stream, 6 = doppelter Ruhm, 1 = 5 Minuten Silhouette.
- [ ] **Haus-Lotterie**: Ruhm einsetzen, Ziehung am Stream-Ende, Siegerhaus teilt den Pott.
- [ ] **Truhe oder Falle**: Chat wählt eine von drei Truhen, Belohnung für alle oder Strafe für den Streamer.

### Mit dem Streamer
- [ ] **Chat steuert dich**: 30 Sekunden Mehrheitsbefehle (`!links`, `!springen`, `!schießen`).
- [ ] **Aufgaben-Rad**: bei Subs/Bits dreht sich ein Rad mit Challenges.
- [ ] **Duell gegen den Streamer**: Mini-Quiz oder Reaktionstest, Gewinner bestimmt die nächste Runde.
