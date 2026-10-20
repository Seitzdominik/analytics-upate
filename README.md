# AnalyticsWP – Updates

Update-Quelle für den AnalyticsWP-Fork. Hier liegen nur die Release-ZIPs
(`releases/`) und `update.json`. WordPress-Seiten mit dem Plugin fragen
`update.json` ab und installieren ein Update nur, wenn SHA-256 und
ed25519-Signatur zum öffentlichen Schlüssel im Plugin passen.

Veröffentlicht wird mit `dev-tools/publish-release.sh` im Quell-Repository.
Nichts hier von Hand ändern: Ein unsigniertes oder verändertes ZIP lehnen
die Seiten ab.
