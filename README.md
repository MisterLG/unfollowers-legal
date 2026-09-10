# unfollowers-legal

Rechtliche Seiten und Hilfeseite zur iOS-App **Unfollowers** — sieh, wer dir auf
Instagram nicht mehr folgt, ohne Login und ohne Passwort.

Veröffentlicht über GitHub Pages:

| Seite | Zweck |
|---|---|
| `index.html` | Startseite, kurze Beschreibung der App |
| `support.html` | Export anfordern, einlesen, Fehlerbehebung — die Support-URL für den App Store |
| `privacy.html` | Datenschutzerklärung — die Privacy-URL für App Store Connect |
| `impressum.html` | Impressum nach § 5 DDG |

`style.css` enthält die gemeinsame Gestaltung; die Seiten passen sich hellem und
dunklem Erscheinungsbild an, weil sie meist vom iPhone aus geöffnet werden. Das
Motiv im Kopf jeder Seite ist dasselbe wie das App-Symbol.

Live unter <https://misterlg.github.io/unfollowers-legal/>.

## Stand

Die App ist **nicht kommerziell**: keine Werbung, keine In-App-Käufe, kein
Tracking. Deshalb reichen Impressum und Datenschutzerklärung — und deshalb
steht dort **keine Anschrift**, sondern Name, E-Mail und der Hinweis, dass eine
ladungsfähige Anschrift auf Anfrage mitgeteilt wird.

> Die Unterzeile lautet „Anbieterkennzeichnung“ und nicht „Angaben gemäß
> § 5 DDG“ — die Vorschrift verlangt eine Anschrift, und auf sie wird sich hier
> bewusst nicht berufen. § 5 DDG knüpft an geschäftsmäßige, in der Regel gegen
> Entgelt angebotene Telemedien an; für ein kostenloses Angebot ohne Werbung
> und Käufe greift die Pflicht nach vertretbarer Auslegung nicht. Risikofrei
> ist das nicht: „geschäftsmäßig“ wird weit ausgelegt.
>
> **Wird die App monetarisiert, muss die Anschrift zurück** — zusammen mit AGB
> und Widerrufsbelehrung.

> **Vor dem Einschalten der Monetarisierung** (`Store/MonetizationConfig.swift`)
> müssen **AGB und Widerrufsbelehrung** ergänzt und die Datenschutzerklärung um
> den Kaufvorgang erweitert werden. Ohne das nicht scharf schalten.

## Zwei Punkte, die diese App von den anderen unterscheidet

1. **Der Export enthält Daten über Dritte.** Followerlisten sind Benutzernamen
   anderer Menschen. Die Datenschutzerklärung spricht das ausdrücklich an und
   ordnet es der Haushaltsausnahme zu (Art. 2 Abs. 2 lit. c DSGVO), statt es zu
   übergehen.
2. **Markenrecht.** Metas Richtlinien verbieten „Insta“, „Gram“ und „IG“ im
   App-Namen. „Unfollowers“ ist frei davon. Instagram darf beschreibend in Text
   vorkommen, nicht aber im Namen, im Symbol oder so, dass eine Partnerschaft
   nahegelegt würde. Der Markenhinweis steht im Impressum und im Fuß der
   Startseite.

## Änderungen

Bei inhaltlichen Änderungen an der Datenschutzerklärung das Stand-Datum in
`privacy.html` mitziehen.
