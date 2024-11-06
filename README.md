# T5_TuotekuvastoApp
Tehtävä 5. Luo ASP.NET Core Web Application

## products.json
products.json sisältää kaikkien tuotteiden tiedot.

## Homecontroller.cs
HomeController.cs lukee products.json:ista tuotteet ja palauttaa ne Product -luokkana.

## Product.cshtml
Product.cshtml käyttää Product -luokkana palautettuja tuotteita ja näyttää tuotteiden kuvat, nimet, kuvaukset ja hinnat käyttäjälle.
Se. miten tuotteet on sivulle aseteltu, perustuu site.css -tiedostossa määriteltyihin tyyliasetuksiin .product-grid ja .product-card div:eille.
