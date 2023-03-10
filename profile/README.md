# ArtNotiser - hjälper dig kryssa fåglar i Sverige

ArtNotiser hjälper dig hitta nya års- och livskryss för de landskap, kommuner eller lokaler som du vill bevaka. Du slipper gå in på Artportalen hela tiden för att söka fram det du vill ha, istället får du information om nya kryss pushade till dig via epost eller i appen. Läs mer om ArtNotiser i vår [Användarmanual](https://github.com/ArtNotiser/artnotiser-docs).

Vill du ställa frågor eller diskutera så gör du det på [ArtNotiser Diskussioner](https://github.com/orgs/ArtNotiser/discussions). Du kan läsa utan att vara inloggad, men för att skriva inlägg behöver du [skapa ett konto på GitHub](https://github.com/signup?return_to=https%3A%2F%2Fgithub.com%2Forgs%2FArtNotiser).

## För utvecklare

ArtNotiser är uppdelad i fyra repositories:
* [artnotiser-backend](https://github.com/ArtNotiser/artnotiser-backend)
* [artnotiser-mobile](https://github.com/ArtNotiser/artnotiser-mobile)
* [artnotiser-IaC](https://github.com/ArtNotiser/artnotiser-IaC)
* [artnotiser-docs](https://github.com/ArtNotiser/artnotiser-docs)

`artnotiser-backend` är motorn bakom ArtNotiser, den läser obsar från Artportalen, jämför med användarnas kryss och skickar notiser till användarna.

`artnotiser-mobile` är en app för iOS och Android, den anropar API:er i `artnotiser-backend`.

`artnotiser-IaC` skapar de komponent i Azure som behövs för att driftsätta `artnotiser-backend`.

`artnotiser-doc` är en användarmanual med slutanvändare som målgrupp, den är skriven på svenska. Teknisk dokumentation finns som wiki i respektive repository.
