# Datenschutzerklärung

**Zuletzt aktualisiert: 18. September 2026**

Diese Datenschutzerklärung erläutert, wie der Entwickler Informationen in Oh!Meine Medis (der „App“) verarbeitet.

## 1. Medikamenten- und Einnahmedaten

Die App erfordert keine Registrierung und kein Konto. Eingetragene Medikamente oder Nahrungsergänzungsmittel, Einnahmepläne und -historie, Bestandsinformationen und Notizen bleiben normalerweise auf deinem Gerät. Die App synchronisiert diese Daten nicht fortlaufend mit unserer Cloud. Medikamentennamen, Freitextnotizen, Symptomnotizen und rohe Suchbegriffe werden nicht als benutzerdefinierte Firebase-Analytics- oder Crashlytics-Felder gesendet.

## 2. Gerätewechsel

Nur wenn du den Gerätewechsel in den Einstellungen ausdrücklich startest, verschlüsselt die App Medikamenten- und Einnahmedaten auf deinem Gerät und sendet die verschlüsselten Daten an einen temporären Übertragungsdienst.

- Die Daten werden mit einem Schlüssel verschlüsselt, der lokal aus dem Wiederherstellungscode abgeleitet wird. Die normale Serververarbeitung erhält Medikamentennamen, Einnahmehistorie, Notizen oder Symptome nicht im Klartext.
- Verschlüsselte Übertragungsdaten sind höchstens **72 Stunden** verfügbar. Nach erfolgreicher Wiederherstellung oder Widerruf werden sie möglichst sofort unbrauchbar gemacht und gelöscht. Bei vorübergehenden Kommunikations- oder Bereinigungsfehlern bleibt die 72-Stunden-Frist die endgültige Aufbewahrungsgrenze.
- Wir speichern den Wiederherstellungscode nicht und können einen verlorenen Code weder wiederherstellen noch neu ausgeben.
- Zum Schutz vor Missbrauch verwenden wir Firebase App Check und Ratenbegrenzungen. Netzwerkinformationen können dafür verarbeitet werden; in operativen Metadaten wird statt der rohen IP-Adresse eine unumkehrbar abgeleitete Kennung gespeichert.
- Der Gerätewechsel ist eine ausdrückliche, temporäre Übertragung und keine kontobasierte Sicherung oder fortlaufende Cloud-Synchronisierung.

## 3. Medikamentensuche und Vorschläge

In unterstützten Ländern kann ein Suchbegriff an öffentliche oder externe Medikamentendienste oder an einen von uns betriebenen Suchproxy gesendet werden. Einnahmehistorie, Bestandsinformationen, Notizen und Symptome werden diesen Anfragen nicht hinzugefügt.

## 4. Nutzungsanalyse

Wir verwenden **Google Firebase Analytics** zur Qualitätsverbesserung. Übermittelt werden können App-Version, Sprache, Funktionsinteraktionen, gruppierte Zählwerte und technische Informationen. Benutzerdefinierte Events enthalten keine Medikamentennamen, Notizen, Symptome, rohen Suchbegriffe, Wiederherstellungscodes, Übertragungsberechtigungen oder Übertragungsdaten. Analytics wird nicht für Werbung oder Nutzertracking verwendet.

## 5. Absturz- und Fehlerdiagnose

Wir verwenden **Google Firebase Crashlytics**. Von der App ergänzte nicht schwerwiegende Diagnosen sind auf vordefinierte Vorgänge, Phasen, Fehlerklassen und Zahlencodes beschränkt und enthalten keine medizinischen Inhalte oder Übertragungsgeheimnisse. Wir setzen keine benutzerdefinierte Crashlytics-Nutzer-ID. Die Erfassung kann in den Einstellungen deaktiviert werden; eine Änderung kann erst nach dem nächsten Start vollständig wirksam sein.

## 6. Werbung und Tracking

Die App zeigt keine Werbung, verwendet kein Google AdMob und führt kein Werbetracking über ATT durch.

## 7. Drittanbieter und Cloud-Infrastruktur

Die App verwendet Firebase und Google Cloud. Verschlüsselte Übertragungsdaten und minimale operative Metadaten werden vorübergehend auf von uns verwalteter Google-Cloud-Infrastruktur verarbeitet und gespeichert.

- [Google Datenschutzerklärung](https://policies.google.com/privacy)
- [Firebase Datenschutz und Sicherheit](https://firebase.google.com/support/privacy)
- [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)

## 8. Änderungen

Wir können diese Erklärung aktualisieren, wenn sich Funktionen oder verwendete Dienste ändern.

## 9. Kontakt

- **Email**: k.lifetime.app+ohkusuri-support@gmail.com

---
*Die japanische Version ist die maßgebliche Referenzfassung.*
