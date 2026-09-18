# Privacybeleid

**Laatst bijgewerkt: 18 september 2026**

Dit privacybeleid beschrijft hoe de ontwikkelaar informatie verwerkt in Oh!Mijn Medicijnen (de “App”).

## 1. Medicijn- en innamedata

De App vereist geen registratie of account. Medicijnen, supplementen, innameschema’s en -historie, voorraadgegevens en notities blijven normaal op je apparaat. De App synchroniseert deze gegevens niet continu met onze cloud. Medicijnnamen, vrije notities, symptoomnotities en ruwe zoektermen worden niet als aangepaste velden naar Firebase Analytics of Crashlytics gestuurd.

## 2. Overzetten naar een nieuw apparaat

Alleen wanneer je de overdracht expliciet start in Instellingen, versleutelt de App je medicijn- en innamedata op het apparaat en stuurt de versleutelde gegevens naar een tijdelijke overdrachtsdienst.

- De gegevens worden versleuteld met een sleutel die lokaal uit de herstelcode wordt afgeleid. De normale serververwerking ontvangt geen medicijnnamen, innamelogboek, notities of symptomen in leesbare vorm.
- De versleutelde gegevens zijn maximaal **72 uur** beschikbaar. Na een geslaagde restore of intrekking worden ze zo snel mogelijk onbruikbaar gemaakt en verwijderd. De 72-uurs vervaldatum blijft de uiteindelijke bewaarbeveiliging bij tijdelijke storingen.
- We bewaren de herstelcode niet en kunnen een verloren code niet herstellen of opnieuw uitgeven.
- We gebruiken Firebase App Check en limieten tegen misbruik. Netwerkinformatie kan daarvoor worden verwerkt; operationele metadata bevat een eenrichtings-afgeleide identificatie in plaats van het ruwe IP-adres.
- Dit is een expliciete tijdelijke overdracht, geen accountback-up of continue cloudsynchronisatie.

## 3. Medicijnzoeken en suggesties

Voor ondersteunde landen kan een zoekterm naar een openbare of externe medicijninformatiedienst of naar een door ons beheerde proxy worden gestuurd. Innamehistorie, voorraad, notities en symptomen worden niet aan die aanvraag toegevoegd.

## 4. Gebruiksanalyse

We gebruiken **Google Firebase Analytics** voor kwaliteitsverbetering. Dit kan appversie, taal, functie-interacties, gegroepeerde aantallen en technische informatie omvatten. Aangepaste events bevatten geen medicijnnamen, notities, symptomen, ruwe zoektermen, herstelcodes, overdrachtsmogelijkheden of overdrachtspayloads. Analytics wordt niet gebruikt voor advertenties of gebruikers­tracking.

## 5. Crash- en foutdiagnostiek

We gebruiken **Google Firebase Crashlytics**. Door de App toegevoegde niet-fatale diagnostiek is beperkt tot vooraf gedefinieerde bewerkingen, fasen, foutcategorieën en numerieke codes en bevat geen medische inhoud of overdrachtsgeheimen. We stellen geen aangepaste Crashlytics-gebruikers-ID in. Je kunt verzameling uitschakelen in Instellingen; een wijziging kan pas na de volgende start volledig gelden.

## 6. Advertenties en tracking

De App toont geen advertenties, gebruikt geen Google AdMob en voert geen advertentietracking uit via ATT.

## 7. Externe diensten en cloudinfrastructuur

De App gebruikt Firebase en Google Cloud. Versleutelde overdrachtsgegevens en minimale operationele metadata worden tijdelijk verwerkt en opgeslagen op door ons beheerde Google Cloud-infrastructuur.

- [Privacybeleid van Google](https://policies.google.com/privacy)
- [Firebase Privacy en beveiliging](https://firebase.google.com/support/privacy)
- [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)

## 8. Wijzigingen

We kunnen dit beleid bijwerken wanneer functies of gebruikte diensten veranderen.

## 9. Contact

- **Email**: k.lifetime.app+ohkusuri-support@gmail.com

---
*De Japanse versie is de referentieversie.*
