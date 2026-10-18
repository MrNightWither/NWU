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
