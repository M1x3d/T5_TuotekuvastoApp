# T5_TuotekuvastoApp

products.json sisältää kaikkien tuotteiden tiedot.
HomeController.cs lukee products.json:ista tuotteet ja palauttaa ne Product -luokkana.
Product.cshtml käyttää Product -luokkana palautettuja tuotteita ja näyttää tuotteiden kuvat, nimet, kuvaukset ja hinnat käyttäjälle.
Se. miten tuotteet on sivulle aseteltu, perustuu site.css -tiedostossa määriteltyihin tyyliasetuksiin .product-grid ja .product-card div:eille.
