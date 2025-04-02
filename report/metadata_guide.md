# 🧾 Metadaten-Kategorisierung – First Gen Project

Diese Datei dokumentiert die verwendeten Metadatenfelder und deren Bedeutung.

---

## 📍 Pflichtfelder

| Feld          | Beschreibung |
|---------------|--------------|
| `id`          | Eindeutige Kennung (z. B. post001, post002) |
| `title`       | Titel des Reddit-Posts |
| `text`        | Volltext (in JSON) |
| `subreddit`   | Herkunftsforum (z. B. r/college) |
| `date`        | Veröffentlichungsdatum |
| `link`        | Direktlink zum Post |

---

## 🧠 Kategorische Felder

### `stage` (Studienphase)
- `Pre-College` = Vorbereitung, Bewerbung
- `Undergraduate` = Bachelorstudierende
- `Graduate` = Masterstudierende
- `PhD` = Promovierende
- `Other` = Sonstiges / unklar

---

### `category` (Typ des Beitrags)
- `Experience` = Persönlicher Erfahrungsbericht
- `Question` = Beitrag enthält eine konkrete Frage oder Bitte um Rat
- `Achievement` = Erfolgserlebnis oder Meilenstein (z. B. Abschluss, Zulassung)
- `Rant` = Frustbeitrag / Beschwerde
- `Advice` = Beitrag gibt aktiv Rat oder Anleitung

---

### `user_role` (Selbstbeschreibung)
- z. B. `First Gen – Bachelor`, `First Gen – PhD`
- Freitextfeld, aber möglichst einheitlich schreiben

---

### `tone` (emotionale Tonalität)
→ Wird später ggf. maschinell ergänzt  
- `neutral`, `sadness`, `joy`, `anger`, `fear`, `pride` etc.

---

### `search_term`
- Suchbegriff, mit dem der Post gefunden wurde (z. B. `"first gen college"`)

---

### `gender`
- nur wenn erkennbar (z. B. „as a woman“, Pronomen etc.)
- `weiblich`, `männlich`, `unbekannt`

---

## 💡 Hinweis

Diese Kategorien sind bewusst einfach gehalten. Sie dienen nicht der psychologischen Klassifikation, sondern der explorativen Analyse und Storytelling-Unterstützung.
