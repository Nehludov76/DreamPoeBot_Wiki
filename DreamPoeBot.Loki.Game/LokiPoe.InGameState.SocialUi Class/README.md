# LokiPoe.InGameState.SocialUi Class

**Вложено элементов:** 18  

| LokiPoe InGameState SocialUi Class |
| --- |


# LokiPoe InGameState SocialUi Class


```csharp
public static class SocialUi
```


```csharp
public static class SocialUi
```


```csharp
public ref class SocialUi abstract sealed
```


```csharp
public ref class SocialUi abstract sealed
```

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


|  | Name | Description |
| --- | --- | --- |
|  | HandlePendingPartyInvite | Obsolete. This method is currently under review and in not usable, you are advised to check the NotificationUi class to handle party invite, trade invite or guild invite. |
|  | HandlePendingPartyInviteNew | This method will accept a specific char name invitation, and decline all other. NOTE: this only handle party invite.. |
|  | InviteToParty | Invite a specific character to the party. |
|  | LeaveCurrentParty | Leave the current party. |
|  | SwitchToFriendsTab | Switch to the Friend Tab. |
|  | SwitchToGuildTab | Switch to the Guild Tab. |
|  | SwitchToPartyTab | Switch to the Party Tab. |
|  | SwitchToPublicPartiesTab | Switch to the Public Parties Tab. |

## Дочерние разделы
- [**SocialUi Properties**](./SocialUi Properties/README.md)
- [**SocialUi Methods**](./SocialUi Methods/README.md)
