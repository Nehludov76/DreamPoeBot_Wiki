# LokiPoe.InGameState.CurrencyExchangeUi Class


| LokiPoe InGameState CurrencyExchangeUi Class |
| --- |


# LokiPoe InGameState CurrencyExchangeUi Class


```csharp
public static class CurrencyExchangeUi
```


```csharp
public static class CurrencyExchangeUi
```


```csharp
public ref class CurrencyExchangeUi abstract sealed
```


```csharp
public ref class CurrencyExchangeUi abstract sealed
```

The LokiPoe InGameState CurrencyExchangeUi type exposes the following members.


| Name | Description |
| --- | --- |
| CurrencyEntryList |
| IsCurrencySelectionPanelOpen | Return true if the Currency selection panel is open. |
| IsOpened | Return true if the Currency Exchange pannel is open. |
| MarketRatios | Return the actual list of market ratios, or empty if no ration are available. |
| Orders | Retrieve the list of placed orders, Pls Note that the Order class contain members and methods to operate over orders. |
| SelectedCurrencyIHave | Return a string containing the name of the actually selected currency IHave. |
| SelectedCurrencyIWant | Return a string containing the name of the actually selected currency IWant. |
| SelectedQuantityIHave | Return the actual quantity IHave. |
| SelectedQuantityIWant | Return the actual quantity IWant. |


| Name | Description |
| --- | --- |
| ClearQuantityIHave | Clear the Quantity IHave field and press enter. |
| ClearQuantityIWant | Clear the Quantity IWant field and press enter. |
| LockAndPlaceOrder | Ensure the 2 numbers are locked as requested by the interface, and then click the Place Order button. |
| LockOrder | Ensure the 2 numbers are locked as requested by the interface. |
| ResetQuantity |
| SelectCurrency |
| SelectCurrencyIHave | Select the IHave currency. |
| SelectCurrencyIWant | Select the IWant currency. |
| SetCurrencySelectionCategory |
| SetQuantity |
| SetQuantityIHave | Set the quantity of IHave currency to exchange. |
| SetQuantityIWant | Set the quantity of IWant currency to exchange. |
| SetSearchFilterText |
| SwapCurrencies | Ctrl click on the current selected IWant to swap the currency, useful to check the ratio for opposite match. |
