## Původ dat

Data pochází z projektu [OpenStreetMap](https://www.openstreetmap.org), exportována byla prostřednictvím mapy [OSM Admin Boundaries](https://wambachers-osm.website/boundaries/) pomocí následujícího příkazu:

```bash
curl -f -o hranice.zip --url 'https://wambachers-osm.website/boundaries/exportBoundaries?cliVersion=1.0&cliKey=XXX&exportFormat=json&exportLayout=levels&exportAreas=water&union=false&selected=441793&from_AL=7&to_AL=8'
```

Kde `XXX` je autentizační klíč (vygeneruje se zdarma registrací v projektu OSM), `441793` je identifikátor Blanska a parametry `from_AL` a `toAL` určují rozsah administrativních úrovní, které se mají exportovat.

## Licenční podmínky

Data jsou licencována tak, jak projekt OSM vyžaduje, tedy pod licencí *Open Data Commons Open Database Licence*. Stručně řečeno s nimi můžete dělat, co chcete, ale musíte uvádět jejich původ a případná odvozená autorská díla šířit pod stejnou licencí.

## Použití

Pro jednoduché zobrazení lze použít web [geojson.net](https://geojson.net/), případně soubor s daty otevřít přímo ve webovém rozhraní GitHubu. Interaktivní mapy ([jako je například tato](https://www.datawrapper.de/_/r7cK6/)) lze vytvářet pomocí nástroje [Datawrapper](https://www.datawrapper.de/).