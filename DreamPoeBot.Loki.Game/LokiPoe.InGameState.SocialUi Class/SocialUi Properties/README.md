# SocialUi Properties

**Вложено элементов:** 8  

| SocialUi Properties |
| --- |


# SocialUi Properties

The LokiPoe InGameState SocialUi type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | IsFriendsTabSelected | Return true if the Friend Tab is selected. |
|  | IsGuildTabSelected | Return true if the Guild Tab is selected. |
|  | IsOpened | Return true if the social screen in open. |
|  | IsPartyTabSelected | Return true if the Party Tab is selected. |
|  | IsPublicPartiesTabSelected | Return true if the Public Parties Tab is selected. |
|  | OnlineFriends | Return a list of OnlineFriend class, containing account name and char name of the actually online friends. PLS NOTE: the function require the Social Pannel to be open, so it require the ProcessHookManager.IsEnabled state to work. The function will open and close the social pannel, or, if the pannel is already open, leave it open. |
|  | TabControl | Return a TabControlWrapper class describing the actual Tab selected. |
|  | WindowControl | Return a DockedWindowControlWrapper describing the Social screen window control. |

## Дочерние разделы
- [**IsFriendsTabSelected Property **](./IsFriendsTabSelected Property/README.md)
- [**IsGuildTabSelected Property **](./IsGuildTabSelected Property/README.md)
- [**IsOpened Property **](./IsOpened Property/README.md)
- [**IsPartyTabSelected Property **](./IsPartyTabSelected Property/README.md)
- [**IsPublicPartiesTabSelected Property **](./IsPublicPartiesTabSelected Property/README.md)
- [**OnlineFriends Property **](./OnlineFriends Property/README.md)
- [**TabControl Property **](./TabControl Property/README.md)
- [**WindowControl Property **](./WindowControl Property/README.md)
