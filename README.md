# perma_id experiment
[Permanent ID](https://wiki.openstreetmap.org/wiki/Permanent_ID) experiment in curatorship of "OSM watchers" of a country.

## The perma_id counter and lookup control
... see [SemanticBridge](https://github.com/OSMBrasil/semantic-bridge)'s lookup model. The counter have no implementation, is controled by `max(x)` SQL clause, and registered (here at git) as [`perma_id_nextValue`](data/perma_id_nextValue) file.

## Grouping by themes and curating by watchers
The lookup table must be checked and, mainly, the `perma_id` number must be attributed only for OSM itens that have one or more watchers, as responsible for the perma_id.

See [collaborative spreadsheets](https://docs.google.com/spreadsheets/d/1Qj9j9n7LpLoXn_DpTJHUqdsjVuCmOmF3n5aY69Dxfg0/)


## Data input alternatives

* Friendly: [Spreadsheet for themes and watchers](https://docs.google.com/spreadsheets/d/1Qj9j9n7LpLoXn_DpTJHUqdsjVuCmOmF3n5aY69Dxfg0/edit)

* Direct: [`data` folder](data) with main CSVs, and `data/_themeName_` folder with CSV controled by the watchers of each theme.

------

[&#160; Contents and data of this project are dedicated to<br/> ![](assets/CC0-logo-200px.png) ](LICENSE.md)
