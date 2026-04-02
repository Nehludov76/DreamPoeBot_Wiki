# DelveSubterrainChartUi Properties


| DelveSubterrainChartUi Properties |
| --- |


# DelveSubterrainChartUi Properties

The LokiPoe InGameState DelveSubterrainChartUi type exposes the following members.


| Name | Description |
| --- | --- |
| IsChartLoaded | Return true if the chart finished loading the next sector of the map. Please note, when you move the map, the new sector next to the one focused might be loaded. Most of the time the load uppen in few ms, but in Slow pc it might require more time. |
| IsOpened | Return true if the Delve Interface is open. |
| VisibleDelveNodes | Return a List of DelveCell That rapresent a square in the Subterrain chart usually containing a icon. For informations about the property of a DelveCell, refer to the documentation about it. Please note: the whole Subterrain chart is a big grid formed by small square, where the icon of each node is usually placed. Some square dont have a icon, that mean that they are simple continuous route. So to calculate the lenght of a route, you need to consider all the square between start and end, the more sqare with no icons, the longer is the path. |
