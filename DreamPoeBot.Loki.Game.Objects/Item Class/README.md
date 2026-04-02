# Item Class


| Item Class |
| --- |


# Item Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Game.Objects.Item"]


```csharp
public class Item : RemoteMemoryObject
```


```csharp
public class Item : RemoteMemoryObject
```


```csharp
public ref class Item : public RemoteMemoryObject
```


```csharp
public ref class Item : public RemoteMemoryObject
```

The Item type exposes the following members.


| Name | Description |
| --- | --- |
| Item | Initializes a new instance of the Item class |
| Item(Int64, Int32) | Initializes a new instance of the Item class |
| Item(Int64, Int32, Int32) | Initializes a new instance of the Item class |
| Item(Int64, Boolean, Vector2i, Vector2i) | Initializes a new instance of the Item class |
| Item(Item, Boolean, Vector2i, Vector2i) | Initializes a new instance of the Item class |
| Item(Int64, Boolean, Vector2i, Vector2i, Int32) | Initializes a new instance of the Item class |


| Name | Description |
| --- | --- |
| AbsorbedCorruption |
| Address | (Inherited from RemoteMemoryObject .) |
| Affixes |
| AlternateQualityType |
| AlternateQualityTypeValue |
| AppliesToCurrentAreaByLevel |
| ArmorValue |
| AttacksPerSecond |
| BaseArmor |
| BaseAttacksPerSecond |
| BaseCritialStrikeChance |
| BaseEnergyShield |
| BaseEvasion |
| BaseItemType |
| BaseMaxPhysicalDamage |
| BaseMinPhysicalDamage |
| BaseRequiredLevel |
| BaseWeaponType |
| CanUse |
| ChargesPerUse |
| ChargesPerUseBase |
| Class |
| Components |
| CompositeType |
| CritialStrikeChance |
| CurrentAction |
| CurrentCharges |
| DisplayNote |
| DroneCurrentCharges |
| DroneMaxCharges |
| EnergyShieldValue |
| EvasionValue |
| Expeditions |
| ExplicitAffixes |
| ExplicitStats |
| FitsEquipRequirements |
| Flags |
| FullName |
| Game | (Inherited from RemoteMemoryObject .) |
| GemTypes |
| HasCurrentAction |
| HasFullStack |
| HasIncubator |
| HasInventoryLocation |
| HasMicrotransitionAttachment |
| HasSkillGemsEquipped |
| HealthRecover |
| HealthRecoveredPerSecond |
| HighestImplicitValue |
| Id |
| ImplicitAffixes |
| ImplicitStats |
| InventoryId |
| IsChromatic |
| IsContraband |
| IsCorrupted |
| IsCrusaderItem |
| IsDead |
| IsElderItem |
| IsFractured |
| IsHostile |
| IsHunterItem |
| IsIdentified |
| IsInstantRecovery |
| IsMirrored |
| IsRedeemerItem |
| IsRelic |
| IsShaperItem |
| IsSpecialMapKey | Return true if this is a specia key map. Refer to keys for:Valdo Map, Vaal Temple Map, Shaper Guardian Map, Nightmare Map. |
| IsStackable |
| IsSynthesized |
| IsUsable |
| IsValid | 0x65004D = "Me"(4 bytes) from word Metadata |
| IsVeiled |
| IsWarlordItem |
| ItemLevel |
| ItemType |
| LinkedSocketColors |
| LocalId |
| LocalStats |
| LocationBottomRight |
| LocationTopLeft |
| M | (Inherited from RemoteMemoryObject .) |
| ManaRecover |
| ManaRecoveredPerSecond |
| MapArea |
| MapItemQuantity |
| MapItemRarity |
| MapLevel |
| MapMonsterPackSize |
| MapRawItemQuantity |
| MapRawItemRarity |
| MapRegion |
| MapSeries |
| MapTier |
| MaxChaosDamage |
| MaxCharges |
| MaxChargesModifier |
| MaxColdDamage |
| MaxCurrencyTabStackCount |
| MaxDamage |
| MaxDps |
| MaxElementalDamage |
| MaxFireDamage |
| MaxLightningDamage |
| MaxLinkCount |
| MaxMonsterLevel |
| MaxPhysicalDamage |
| MaxQuality |
| MaxStackCount |
| Metadata |
| MinChaosDamage |
| MinColdDamage |
| MinDamage |
| MinDps |
| MinElementalDamage |
| MinFireDamage |
| MinLightningDamage |
| MinMonsterLevel |
| MinMonsterLevelPrefix |
| MinMonsterLevelSuffix |
| MinPhysicalDamage |
| Name |
| Offsets | (Inherited from RemoteMemoryObject .) |
| PositionedComp |
| Quality |
| Rarity |
| RecoveryTime |
| RenderArt |
| RequiredDex |
| RequiredDexForNextLevel |
| RequiredInt |
| RequiredIntForNextLevel |
| RequiredLevel |
| RequiredLevelForNextLevel |
| RequiredStr |
| RequiredStrForNextLevel |
| ScourgedTier |
| SentinelDroneEmpowerments |
| SentinelDroneEmpowers |
| SentinelDroneMaxDuration |
| Size |
| Skill |
| SkillGemLevel |
| SkillGemQualityType |
| SkillSocketIndex | Return the Socket Index where this skill gem is socketed in the Item sockets. PLS NOTE! This only work for Skill Gems, it do not work for Support gems. Go get the Index of a support gem, or in general to get a more satisfaing result, use public int GetSocketIndexOfGem(Item gem). |
| SocketColor |
| SocketColors |
| SocketCount |
| SocketedDisplayString |
| SocketedGems |
| SocketedSkillGemsByLinks |
| SocketLinks |
| StackCount |
| Stats |
| Tags |
| UiElement |
| WorldItemId |
| WorldItemPosition |


| Name | Description |
| --- | --- |
| AnyMetadataFlags |
| AsObject T | (Inherited from RemoteMemoryObject .) |
| CalcGemStatReq |
| CreateObject T | (Inherited from RemoteMemoryObject .) |
| Dump |
| Equals(Object) | (Inherited from RemoteMemoryObject .) |
| Equals(RemoteMemoryObject) | (Inherited from RemoteMemoryObject .) |
| Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
| GetGemInSocket |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetObject T | (Inherited from RemoteMemoryObject .) |
| GetObjectAt T (Int32) | (Inherited from RemoteMemoryObject .) |
| GetObjectAt T (Int64) | (Inherited from RemoteMemoryObject .) |
| GetSocketIndexForSkilGem |
| GetSocketIndexOfGem |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| HasMetadataFlags |
| MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
| OnPointerChanged | (Inherited from RemoteMemoryObject .) |
| ReadObject T | (Inherited from RemoteMemoryObject .) |
| ReadObjectAt T | (Inherited from RemoteMemoryObject .) |
| ReadObjectSkill | (Inherited from RemoteMemoryObject .) |
| RequiredDexForLevel |
| RequiredIntForLevel |
| RequiredLevelForLevel |
| RequiredStrForLevel |
| ToString | (Overrides Object ToString .) |
| UpdatePointer | (Inherited from RemoteMemoryObject .) |


| Name | Description |
| --- | --- |
| NeedUpdate | (Inherited from RemoteMemoryObject .) |
