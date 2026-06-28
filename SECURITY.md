🔐 SECURITY POLICY – WorldBooksFoods
🟢 Supported Versions

Diese App wird aktiv gewartet und erhält Sicherheitsupdates für die aktuelle Version.

Version	Supported
1.1.x (aktuell)	✅ Ja
1.0.x	❌ Nein
< 1.0	❌ Nein
🔐 Sicherheitsmodell der App

WorldBooksFoods nutzt folgende Technologien:

Firebase Authentication (E-Mail Login)
Firestore Database (Cloud Speicherung)
DataStore (lokaler Cache)
Jetpack Compose (UI Layer)
📊 Gespeicherte Daten

Die App speichert nur folgende Daten:

👤 Benutzerkonto
E-Mail-Adresse (Firebase Auth)
User ID (UID)
❤️ Favoriten
Food Item IDs
Speicherung unter:
users/{userId}/favorites/{foodId}
🔒 Datenschutz & Sicherheit
Jeder Benutzer kann nur seine eigenen Daten lesen und schreiben
Zugriff wird durch Firebase Security Rules geschützt
Keine sensiblen Daten wie:
Passwörter (werden von Firebase verwaltet)
Zahlungsdaten
Standortdaten

werden gespeichert.

🌐 Datenübertragung
Alle Daten werden über HTTPS verschlüsselt übertragen
Firebase sorgt für sichere Cloud-Kommunikation
⚠️ Bekannte Risiken

Die App ist sicher, aber folgende Risiken können theoretisch auftreten:

Kein Internet → temporäre Synchronisationsverzögerung
Falsche Firebase Rules → Zugriff verweigert (PERMISSION_DENIED)
Gerätewechsel ohne Login → lokale Favoriten nicht verfügbar
🛡️ Sicherheitsmaßnahmen

Die App schützt Daten durch:

Firebase Authentication (User Isolation)
Firestore Rules (UID-based access control)
DataStore nur als Cache (kein Hauptspeicher)
Try/Catch Error Handling in allen Firebase Calls
Optimistic UI mit Revert bei Fehlern
🚨 Vulnerability Reporting

Wenn du eine Sicherheitslücke findest, melde sie bitte direkt an:

📧 Email: support@worldbooksfoods.app
🌍 Website: https://wadtaktok-dev.github.io/WorldBooksFoods/

⏱️ Response Time
Bestätigung innerhalb von: 48 Stunden
Analyse: 3–7 Tage
Fix (falls nötig): so schnell wie möglich in einem Update
🔄 Update Policy
Sicherheitsupdates werden sofort veröffentlicht
Kritische Bugs → Hotfix Release
Normale Updates → Version Upgrade im Play Store
📌 Hinweis

Diese App ist ein persönliches Projekt und nutzt Firebase als Backend-Service. Alle Daten werden nach Google Firebase Standards geschützt.
