# SkillGemHud Properties


| SkillGemHud Properties |
| --- |


# SkillGemHud Properties

The LokiPoe InGameState SkillGemHud type exposes the following members.


| Name | Description |
| --- | --- |
| AreIconsDisplayed | Return true if at least 1 gem can be leveled. |
| IsOpened | Return true if at least 1 gem is visible. Please note: This return true even if the gem cant be leveled and only the experience level is displayed. To actually make sure you can level a gem, use `AreIconsDisplayed`. |
| ListOfPendingSkillElements |
| ListOfPendingSkillGems | Return the list of LevelingGem ready to be leveled. |
