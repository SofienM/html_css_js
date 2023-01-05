```
const data = [
  {
    city: "Brest",
    name: "Malcom",
    url: "https://france3-regions.francetvinfo.fr/image/2RLWh_MZj-kCn4Kr8o3cq7gjNHs/600x400/regions/2021/08/06/610d665a0d50a_herwann-asseh-5419253.jpg",
  },
  {
    city: "Londres",
    name: "Ibrahima",
    url: "https://france3-regions.francetvinfo.fr/image/2RLWh_MZj-kCn4Kr8o3cq7gjNHs/600x400/regions/2021/08/06/610d665a0d50a_herwann-asseh-5419253.jpg",
  },
  {
    city: "Paris",
    name: "Sofiane",
    url: "https://france3-regions.francetvinfo.fr/image/2RLWh_MZj-kCn4Kr8o3cq7gjNHs/600x400/regions/2021/08/06/610d665a0d50a_herwann-asseh-5419253.jpg",
  },
];
```

Etape 1
Avec `data = {city: "Londres", name: "Laurent"}`
mettre les données dans deux spans qui ont déjà un id

Etape 2
Mettre les données dans une div

```
for (personne of data) {
    vide.innerHTML = vide.innerHTML + personne.city + personne.name
}
```

Etape 3
Créer les h2

```
for (personne of data) {
    nvx = document.createElement("h2")
    nvx.innerHTML = personne.city
    vide.appendChild(nvx)
}
```

Variante

<h2 class="toto">Malcom</h2><span>lala</span>

Etape4
des cards
