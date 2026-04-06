# LokiPoe.InGameState.SkillGemHud Class

**Вложено элементов:** 8  

| LokiPoe InGameState SkillGemHud Class |
| --- |


# LokiPoe InGameState SkillGemHud Class


```csharp
public static class SkillGemHud
```


```csharp
public static class SkillGemHud
```


```csharp
public ref class SkillGemHud abstract sealed
```


```csharp
public ref class SkillGemHud abstract sealed
```

The LokiPoe InGameState SkillGemHud type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | AreIconsDisplayed | Return true if at least 1 gem can be leveled. |
|  | IsOpened | Return true if at least 1 gem is visible. Please note: This return true even if the gem cant be leveled and only the experience level is displayed. To actually make sure you can level a gem, use `AreIconsDisplayed`. |
|  | ListOfPendingSkillElements |  |
|  | ListOfPendingSkillGems | Return the list of LevelingGem ready to be leveled. |


|  | Name | Description |
| --- | --- | --- |
|  | HandlePendingLevelUps |  |
|  | LevelAll | Click the All button to level all skill gem. |

## Дочерние разделы
- [**SkillGemHud Properties**](./SkillGemHud Properties/README.md)
- [**SkillGemHud Methods**](./SkillGemHud Methods/README.md)
