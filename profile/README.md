## ArtNotiser - hjälper dig kryssa fåglar i Sverige

ArtNotiser informerar dig om nya års- och livskryss för de landskap, kommuner eller lokaler som du vill bevaka. Du slipper gå in på Artportalen varje timme, istället får du information om nya kryss via epost eller i appen. 

Koden för ArtNotiser är uppdelade i tre delar:
* [artnotiser-backend](https://github.com/ArtNotiser/artnotiser-backend)
* [artnotiser-mobile](https://github.com/ArtNotiser/artnotiser-mobile)
* [artnotiser-IaC](https://github.com/ArtNotiser/artnotiser-IaC)

`artnotiser-backend` är motorn bakom ArtNotiser, den läser obsar från Artportalen, jämför med användarnas kryss och skickar notiser till användarna.

`artnotiser-mobile` är en app för iOS och Android, den anropar API:er i `artnotiser-backend`.

`artnotiser-IaC` skapar de komponent i Azure som behövs för att driftsätta `artnotiser-backend`.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
