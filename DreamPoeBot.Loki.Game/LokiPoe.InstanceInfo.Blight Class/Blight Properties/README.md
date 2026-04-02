# Blight Properties


| Blight Properties |
| --- |


# Blight Properties

The LokiPoe InstanceInfo Blight type exposes the following members.


| Name | Description |
| --- | --- |
| ActualPumpDurability | Return the actual pump durability. |
| EncounterStage | This is a number that go from 0 to 5 (from a first observation), and describe the actual Blight encounter State: 0 = No encounter, 1 = the encounter is running, 2 = The encounter success and some chest loot are still unopened, 3 = The encounter success , the pumb is been destroied, and some chest loot are still unopened, 4 = The encounter success and all chests are been open, 5 = The encounter failed. |
| IsEncounterCompletedAllChestLooted | The Blight encounter is over, all chests are been opened. |
| IsEncounterCompletedPumpDestroied | The Blight encounter is over, the pump is been destroied and there are some chests still unopened. |
| IsEncounterFailed | The Blight encounter failed, the pump is been destroyed, there are no chest to open. |
| IsEncounterFinishedLootAvailable | The Blight encounter is over, all monster are been killed and there are some chests still unopened. |
| IsEncounterRunning | The Blight encounter is running, not all monster are been killed. |
| MaxPumpDurability | Return the max pump durability. |
| Resources | Return the actual Resources availables. |
| SpawnersInfo | Return a list of BlightSpawnerData that describe the various lane spawners types. |
