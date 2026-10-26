# Data-binding types: S

Back to the [index](README.md).

## Savable

Save Dialog - Savable

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AbsoluteLocationText` |  | `CString` |  |
| `AccessSelf` |  |  |  |
| `AllowsFileDialog` |  | `bool` |  |
| `Error` |  | `CString` |  |
| `Filename` |  | `CString` |  |
| `FolderSelect` |  | `void` |  |
| `HasError` |  | `bool` |  |
| `HasWarning` |  | `bool` |  |
| `IsDeletable` |  | `bool` |  |
| `IsFilenameModifiable` |  | `bool` |  |
| `IsRevertible` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Location` |  | `CString` |  |
| `LocationTooltip` |  | `CString` |  |
| `RevertLocation` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilename` |  | `void` |  |
| `SetLocation` | `Arg0` | `void` |  |
| `SetSelected` | `Arg0` | `void` |  |
| `Warning` |  | `CString` |  |

## SavableGroup

Save Dialog - Savable Group

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HasError` |  | `bool` |  |
| `HasWarning` |  | `bool` |  |
| `IsExpanded` |  | `bool` |  |
| `IsRevertible` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsSelectedIndeterminable` |  | `bool` |  |
| `Location` |  | `CString` |  |
| `RevertLocation` |  | `void` |  |
| `Savables` |  |  |  |
| `Self` |  |  |  |
| `SetLocation` | `Arg0` | `void` |  |
| `SetSelected` | `Arg0` | `void` |  |
| `Title` |  | `CString` |  |
| `ToggleExpanded` |  | `void` |  |

## SaveDialog

Save Dialog

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `FindGroupLocation` | `Arg0, Arg1` | `void` |  |
| `FindLocation` | `Arg0, Arg1` | `void` |  |
| `Groups` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `IsSelectedIndeterminable` |  | `bool` |  |
| `SavableCount` |  | `int32` |  |
| `Self` |  |  |  |
| `SetSelected` | `Arg0` | `void` |  |

## SaveGame

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetLastModified` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## SaveGameAnalysisView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSaveGame` |  | `SaveGame` |  |
| `AccessSelf` |  |  |  |
| `GetNote` | `Arg0` | `CUTF8String` |  |
| `GetProgress` |  | `float` |  |
| `GetSaveGame` |  |  |  |
| `GetShowHidden` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsEmpty` |  | `bool` |  |
| `IsReading` |  | `bool` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |
| `ToggleShowHidden` |  | `void` |  |

## SaveGameAnalyzer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CancelLoad` |  | `void` |  |
| `CloseNotes` |  | `void` |  |
| `EditNotes` | `Arg0` | `void` |  |
| `ListSaves` |  | `void` |  |
| `LoadSelected` |  | `void` |  |
| `Self` |  |  |  |

## SaveGameBlockData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCharCount` |  | `int32` |  |
| `GetInstanceCount` |  | `int32` |  |
| `GetOtherPaths` |  | `CString` |  |
| `GetOtherPathsCount` |  | `int32` |  |
| `GetParentPercentage` |  | `float` |  |
| `GetPath` |  | `CString` |  |
| `GetPercentage` |  | `float` |  |
| `GetTitle` |  | `CString` |  |
| `GetTokenName` |  | `CString` |  |
| `GetWhitespaceCount` |  | `int32` |  |
| `GetWhitespaceRatio` |  | `float` |  |
| `Self` |  |  |  |

## SaveGameConfigView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTokenName` |  | `CString` |  |
| `IsActive` |  | `bool` |  |
| `IsDirty` |  | `bool` |  |
| `Save` |  | `void` |  |
| `Self` |  |  |  |

## SaveGameItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountryFlag` |  | `CoatOfArms` |  |
| `GetDate` |  | `Date` |  |
| `AccessSelf` |  |  |  |
| `CanGetAchievements` |  | `bool` |  |
| `CanLoad` |  | `bool` |  |
| `CanLoadDesc` |  | `CString` |  |
| `GetAchievementBlockingGameRulesInfo` |  | `CString` |  |
| `GetCountryFlag` |  |  |  |
| `GetCountryName` |  | `CString` |  |
| `GetCountryRank` |  | `CString` |  |
| `GetDate` |  |  |  |
| `GetIncompatibilityTooltip` |  | `CString` |  |
| `GetLastPlayed` |  | `CString` |  |
| `GetMissingDLCInfo` |  | `CString` |  |
| `GetMissingMods` |  | `CString` |  |
| `GetModifiedDate` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNumberOfPlayers` |  | `int32` |  |
| `GetVersionName` |  | `CString` |  |
| `HasAchievementBlockingGameRules` |  | `bool` |  |
| `HasMissingDLCs` |  | `bool` |  |
| `HasMissingMods` |  | `bool` |  |
| `IsCloudSave` |  | `bool` |  |
| `IsDifferentVersion` |  | `bool` |  |
| `IsIronmanSave` |  | `bool` |  |
| `IsMultiplayer` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `OnLoad` |  | `void` |  |
| `Select` |  | `void` |  |
| `SelectAndLoad` |  | `void` |  |
| `Self` |  |  |  |

## SaveGameListView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSaves` |  |  |  |
| `AccessSelf` |  |  |  |
| `HasSelection` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsReading` |  | `bool` |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetSelected` | `Arg0` | `void` |  |
| `Sort` | `Arg0` | `void` |  |

## SaveGameWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCloudData` |  | `CloudSaveData` |  |
| `AccessCloudData` |  |  |  |
| `AccessSelf` |  |  |  |
| `Cancel` |  | `void` |  |
| `GetDefaultSaveName` |  | `CUTF8String` |  |
| `GetSaveGames` |  |  |  |
| `IsIronman` |  | `bool` |  |
| `IsOverwrite` |  | `bool` |  |
| `IsSaveNameOk` |  | `bool` |  |
| `IsSaving` |  | `bool` |  |
| `IsShowInvalid` |  | `bool` |  |
| `Save` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleShowInvalid` |  | `void` |  |
| `UpdateSaveName` |  | `void` |  |

## Scope

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAmendment` |  | `Amendment` |  |
| `AccessAmendmentType` |  | `AmendmentType` |  |
| `AccessBattle` |  | `Battle` |  |
| `AccessBuilding` |  | `Building` |  |
| `AccessBuildingGroup` |  | `BuildingGroup` |  |
| `AccessBuildingType` |  | `BuildingType` |  |
| `AccessCharacter` |  | `Character` |  |
| `AccessCharacterRole` |  | `CharacterRole` |  |
| `AccessCivilWar` |  | `CivilWar` |  |
| `AccessCombatUnit` |  | `CombatUnit` |  |
| `AccessCombatUnitType` |  | `CombatUnitType` |  |
| `AccessCommanderOrderType` |  | `CommanderOrderType` |  |
| `AccessCompany` |  | `Company` |  |
| `AccessCompanyType` |  | `CompanyType` |  |
| `AccessCountry` |  | `Country` |  |
| `AccessCountryCreation` |  | `CountryCreation` |  |
| `AccessCountryDefinition` |  | `CountryDefinition` |  |
| `AccessCountryFormation` |  | `CountryFormation` |  |
| `AccessCulturalCommunity` |  | `CulturalCommunity` |  |
| `AccessCulture` |  | `Culture` |  |
| `AccessDecisionType` |  | `Decision` |  |
| `AccessDecree` |  | `Decree` |  |
| `AccessDiplomaticAction` |  | `DiplomaticAction` |  |
| `AccessDiplomaticCatalyst` |  | `DiplomaticCatalyst` |  |
| `AccessDiplomaticCatalystCategory` |  | `DiplomaticCatalystCategory` |  |
| `AccessDiplomaticCatalystType` |  | `DiplomaticCatalystType` |  |
| `AccessDiplomaticDemand` |  | `DiplomaticDemand` |  |
| `AccessDiplomaticPact` |  | `DiplomaticPact` |  |
| `AccessDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `AccessDiplomaticPlayType` |  | `DiplomaticPlayType` |  |
| `AccessDiplomaticRelations` |  | `DiplomaticRelations` |  |
| `AccessFront` |  | `Front` |  |
| `AccessGeographicRegion` |  | `GeographicRegion` |  |
| `AccessGoods` |  | `Goods` |  |
| `AccessHQ` |  | `Hq` |  |
| `AccessHarvestCondition` |  | `HarvestCondition` |  |
| `AccessHarvestConditionArea` |  | `HarvestConditionArea` |  |
| `AccessHarvestConditionType` |  | `HarvestConditionType` |  |
| `AccessIdeology` |  | `Ideology` |  |
| `AccessInstitution` |  | `Institution` |  |
| `AccessInstitutionType` |  | `InstitutionType` |  |
| `AccessInterest` |  | `Interest` |  |
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `AccessInterestGroupTrait` |  | `InterestGroupTrait` |  |
| `AccessInterestTierType` |  | `InterestTierType` |  |
| `AccessInvasion` |  | `Invasion` |  |
| `AccessJournalEntry` |  | `JournalEntry` |  |
| `AccessLaw` |  | `Law` |  |
| `AccessLawType` |  | `LawType` |  |
| `AccessMarket` |  | `Market` |  |
| `AccessMarketGoods` |  | `MarketGoods` |  |
| `AccessMilitaryFormation` |  | `MilitaryFormation` |  |
| `AccessMobilizationOption` |  | `MobilizationOption` |  |
| `AccessNavalBattle` |  | `NavalBattle` |  |
| `AccessNavalMission` |  | `NavalMission` |  |
| `AccessNavalMissionType` |  | `NavalMissionType` |  |
| `AccessObjective` |  | `Objective` |  |
| `AccessParty` |  | `Party` |  |
| `AccessPoliticalLobby` |  | `PoliticalLobby` |  |
| `AccessPoliticalLobbyAppeasementFactor` |  | `PoliticalLobbyAppeasementFactor` |  |
| `AccessPoliticalLobbyType` |  | `PoliticalLobbyType` |  |
| `AccessPoliticalMovement` |  | `PoliticalMovement` |  |
| `AccessPoliticalMovementCategory` |  | `PoliticalMovementCategory` |  |
| `AccessPoliticalMovementType` |  | `PoliticalMovementType` |  |
| `AccessPop` |  | `Pop` |  |
| `AccessPopType` |  | `PopType` |  |
| `AccessPowerBloc` |  | `PowerBloc` |  |
| `AccessPowerBlocIdentity` |  | `PowerBlocIdentity` |  |
| `AccessPowerBlocPrinciple` |  | `PowerBlocPrinciple` |  |
| `AccessPowerBlocPrincipleGroup` |  | `PowerBlocPrincipleGroup` |  |
| `AccessProvince` |  | `Province` |  |
| `AccessReligion` |  | `Religion` |  |
| `AccessScriptContainer` |  | `ScriptContainer` |  |
| `AccessShip` |  | `Ship` |  |
| `AccessShipGroup` |  | `ShipGroup` |  |
| `AccessShipModificationType` |  | `ShipModificationType` |  |
| `AccessShipType` |  | `ShipType` |  |
| `AccessShippingLane` |  | `ShippingLane` |  |
| `AccessState` |  | `State` |  |
| `AccessStateGoods` |  | `StateGoods` |  |
| `AccessStateRegion` |  | `StateRegion` |  |
| `AccessStateTrait` |  | `StateTrait` |  |
| `AccessStrait` |  | `Strait` |  |
| `AccessStraitDefinition` |  | `StraitDefinition` |  |
| `AccessStrategicRegion` |  | `StrategicRegion` |  |
| `AccessSway` |  | `Sway` |  |
| `AccessTechnology` |  | `Technology` |  |
| `AccessTheater` |  | `Theater` |  |
| `AccessTreaty` |  | `Treaty` |  |
| `AccessTreatyArticle` |  | `Article` |  |
| `AccessWar` |  | `War` |  |
| `AccessWarGoal` |  | `WarGoal` |  |
| `AccessWarGoalType` |  | `WarGoalType` |  |
| `GetAmendment` |  | `Amendment` |  |
| `GetAmendmentType` |  | `AmendmentType` |  |
| `GetBattle` |  | `Battle` |  |
| `GetBuilding` |  | `Building` |  |
| `GetBuildingGroup` |  | `BuildingGroup` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `GetCharacter` |  | `Character` |  |
| `GetCharacterRole` |  | `CharacterRole` |  |
| `GetCivilWar` |  | `CivilWar` |  |
| `GetCombatUnit` |  | `CombatUnit` |  |
| `GetCombatUnitType` |  | `CombatUnitType` |  |
| `GetCommanderOrderType` |  | `CommanderOrderType` |  |
| `GetCompany` |  | `Company` |  |
| `GetCompanyType` |  | `CompanyType` |  |
| `GetCountry` |  | `Country` |  |
| `GetCountryCreation` |  | `CountryCreation` |  |
| `GetCountryDefinition` |  | `CountryDefinition` |  |
| `GetCountryFormation` |  | `CountryFormation` |  |
| `GetCulturalCommunity` |  | `CulturalCommunity` |  |
| `GetCulture` |  | `Culture` |  |
| `GetDecisionType` |  | `Decision` |  |
| `GetDecree` |  | `Decree` |  |
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `GetDiplomaticCatalyst` |  | `DiplomaticCatalyst` |  |
| `GetDiplomaticCatalystCategory` |  | `DiplomaticCatalystCategory` |  |
| `GetDiplomaticCatalystType` |  | `DiplomaticCatalystType` |  |
| `GetDiplomaticDemand` |  | `DiplomaticDemand` |  |
| `GetDiplomaticPact` |  | `DiplomaticPact` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetDiplomaticPlayType` |  | `DiplomaticPlayType` |  |
| `GetDiplomaticRelations` |  | `DiplomaticRelations` |  |
| `GetFront` |  | `Front` |  |
| `GetGeographicRegion` |  | `GeographicRegion` |  |
| `GetGoods` |  | `Goods` |  |
| `GetHQ` |  | `Hq` |  |
| `GetHarvestCondition` |  | `HarvestCondition` |  |
| `GetHarvestConditionArea` |  | `HarvestConditionArea` |  |
| `GetHarvestConditionType` |  | `HarvestConditionType` |  |
| `GetIdeology` |  | `Ideology` |  |
| `GetInstitution` |  | `Institution` |  |
| `GetInstitutionType` |  | `InstitutionType` |  |
| `GetInterest` |  | `Interest` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `GetInterestGroupTrait` |  | `InterestGroupTrait` |  |
| `GetInterestTierType` |  | `InterestTierType` |  |
| `GetInvasion` |  | `Invasion` |  |
| `GetJournalEntry` |  | `JournalEntry` |  |
| `GetLaw` |  | `Law` |  |
| `GetLawType` |  | `LawType` |  |
| `GetMarket` |  | `Market` |  |
| `GetMarketGoods` |  | `MarketGoods` |  |
| `GetMilitaryFormation` |  | `MilitaryFormation` |  |
| `GetMobilizationOption` |  | `MobilizationOption` |  |
| `GetNavalBattle` |  | `NavalBattle` |  |
| `GetNavalMission` |  | `NavalMission` |  |
| `GetNavalMissionType` |  | `NavalMissionType` |  |
| `GetObjective` |  | `Objective` |  |
| `GetParty` |  | `Party` |  |
| `GetPoliticalLobby` |  | `PoliticalLobby` |  |
| `GetPoliticalLobbyAppeasementFactor` |  | `PoliticalLobbyAppeasementFactor` |  |
| `GetPoliticalLobbyType` |  | `PoliticalLobbyType` |  |
| `GetPoliticalMovement` |  | `PoliticalMovement` |  |
| `GetPoliticalMovementCategory` |  | `PoliticalMovementCategory` |  |
| `GetPoliticalMovementType` |  | `PoliticalMovementType` |  |
| `GetPop` |  | `Pop` |  |
| `GetPopType` |  | `PopType` |  |
| `GetPowerBloc` |  | `PowerBloc` |  |
| `GetPowerBlocIdentity` |  | `PowerBlocIdentity` |  |
| `GetPowerBlocPrinciple` |  | `PowerBlocPrinciple` |  |
| `GetPowerBlocPrincipleGroup` |  | `PowerBlocPrincipleGroup` |  |
| `GetProvince` |  | `Province` |  |
| `GetReligion` |  | `Religion` |  |
| `GetScriptContainer` |  | `ScriptContainer` |  |
| `GetShip` |  | `Ship` |  |
| `GetShipGroup` |  | `ShipGroup` |  |
| `GetShipModificationType` |  | `ShipModificationType` |  |
| `GetShipType` |  | `ShipType` |  |
| `GetShippingLane` |  | `ShippingLane` |  |
| `GetState` |  | `State` |  |
| `GetStateGoods` |  | `StateGoods` |  |
| `GetStateRegion` |  | `StateRegion` |  |
| `GetStateTrait` |  | `StateTrait` |  |
| `GetStrait` |  | `Strait` |  |
| `GetStraitDefinition` |  | `StraitDefinition` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `GetSway` |  | `Sway` |  |
| `GetTechnology` |  | `Technology` |  |
| `GetTheater` |  | `Theater` |  |
| `GetTreaty` |  | `Treaty` |  |
| `GetTreatyArticle` |  | `Article` |  |
| `GetVariable` | `Arg0` | `Scope` |  |
| `GetVariableFromVariableMap` | `Arg0, Arg1` | `Scope` |  |
| `GetWar` |  | `War` |  |
| `GetWarGoal` |  | `WarGoal` |  |
| `GetWarGoalType` |  | `WarGoalType` |  |
| `Var` | `Arg0` | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetFlagName` |  | `CString` |  |
| `GetList` | `Arg0` |  |  |
| `GetMapKeys` | `Arg0` |  |  |
| `GetScriptValueDesc` | `Arg0` | `CString` |  |
| `GetValue` |  | `CFixedPoint` |  |
| `GetValueWithDefault` | `Arg0` | `CFixedPoint` |  |
| `IsSet` |  | `bool` |  |
| `ScriptValue` | `Arg0` | `CFixedPoint` |  |
| `Self` |  |  |  |
| `VarRemaining` | `Arg0` | `int32` |  |
| `VariableMapContainsKey` | `Arg0, Arg1` | `bool` |  |
| `VariableMapContainsValue` | `Arg0, Arg1` | `bool` |  |
| `VariableMapExists` | `Arg0` |  |  |

## ScopeDebugData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDebugInformation` |  | `CString` |  |
| `GetRawID` |  | `CString` |  |
| `GetTypeData` |  | `CString` |  |
| `GetTypeID` |  | `CString` |  |
| `GetTypeName` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `SupportsVariables` |  | `bool` |  |

## ScopeDebugInspectorPlugin

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetScopeData` |  | `ScopeDebugData` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## ScopedEditorSettingsCategory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCategory` |  | `EditorSettingCategory` |  |
| `GetCategory` |  | `EditorSettingCategory` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## ScopeObjectEditor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AsBool` |  | `bool` |  |
| `AsString` |  | `CString` |  |
| `GetID` |  | `uint64` |  |
| `GetSelectedType` |  | `CVector2i` |  |
| `GetTypeData` |  | `CString` |  |
| `GetValue` |  | `CString` |  |
| `GetVariableTypes` |  |  |  |
| `IsBool` |  | `bool` |  |
| `IsFlag` |  | `bool` |  |
| `IsNumber` |  | `bool` |  |
| `IsReference` |  | `bool` |  |
| `Self` |  |  |  |
| `SetFromString` |  | `void` |  |
| `SetIDFromString` |  | `void` |  |
| `SetSelectedType` |  | `void` |  |
| `SetTypeDataFromString` |  | `void` |  |
| `ToggleBool` |  | `void` |  |

## ScopeObjectProvider

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetError` |  | `CString` |  |
| `GetFilteredResultCount` |  | `int32` |  |
| `GetTotalResultCount` |  | `int32` |  |
| `GetTriggerString` |  | `CString` |  |
| `HasError` |  | `bool` |  |
| `Self` |  |  |  |
| `SetTriggerString` |  | `void` |  |
| `UpdateFilter` |  | `void` |  |

## ScopeObjectType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## ScriptContainer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetParent` |  | `Scope` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetParent` |  |  |  |
| `GetTagCount` |  | `int32` |  |
| `GetTagsString` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetVariableCount` |  | `int32` |  |
| `GetVariableListSize` | `Arg0` | `int32` |  |
| `GetVariableValue` | `Arg0` | `CFixedPoint` |  |
| `HasParent` |  | `bool` |  |
| `HasTag` | `Arg0` | `bool` |  |
| `HasVariable` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## ScriptedButton

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ExecuteEffect` |  | `Command` |  |
| `GetCooldownDesc` |  | `CString` |  |
| `GetCooldownDuration` |  | `CString` |  |
| `GetCooldownRemaining` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetPossibleDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasCooldown` |  | `bool` |  |
| `IsOnCooldown` |  | `bool` |  |
| `IsPossible` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## ScriptedGui

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `BuildTooltip` | `Arg0` | `CString` |  |
| `Execute` | `Arg0` | `void` |  |
| `ExecuteTooltip` | `Arg0` | `CString` |  |
| `IsShown` | `Arg0` | `bool` |  |
| `IsShownTooltip` | `Arg0` | `CString` |  |
| `IsValid` | `Arg0` | `bool` |  |
| `IsValidTooltip` | `Arg0` | `CString` |  |
| `Self` |  |  |  |

## ScriptedProgressBar

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetMaxValue` |  | `CFixedPoint` |  |
| `GetMinValue` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetPeriodicProgressBreakdown` |  | `CString` |  |
| `GetSecondDesc` |  | `CString` |  |
| `GetStartValue` |  | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsDefault` |  | `bool` |  |
| `IsDefaultBad` |  | `bool` |  |
| `IsDefaultGreen` |  | `bool` |  |
| `IsDoubleSidedBad` |  | `bool` |  |
| `IsDoubleSidedGold` |  | `bool` |  |
| `IsDoubleSidedRyukyu` |  | `bool` |  |
| `IsDoubleSidedSpain` |  | `bool` |  |
| `Self` |  |  |  |

## ScriptProfilerEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAverageTimeExclusive` |  | `double` |  |
| `GetAverageTimeInclusive` |  | `double` |  |
| `GetBottleneckTime` |  | `double` |  |
| `GetCallCount` |  | `uint64` |  |
| `GetFile` |  |  |  |
| `GetFileAndLine` |  | `CString` |  |
| `GetFileName` |  |  |  |
| `GetFileNameAndLine` |  | `CString` |  |
| `GetFormattedBottleneckTiming` |  | `CString` |  |
| `GetFormattedTiming` |  | `CString` |  |
| `GetLine` |  | `int32` |  |
| `GetMaxTimeInclusive` |  | `double` |  |
| `GetMinTimeInclusive` |  | `double` |  |
| `GetPerFrameTimeExclusive` |  | `double` |  |
| `GetPerFrameTimeInclusive` |  | `double` |  |
| `GetPerTickTimeExclusive` |  | `double` |  |
| `GetPerTickTimeInclusive` |  | `double` |  |
| `GetShortDescription` |  | `CString` |  |
| `GetTiming` |  | `double` |  |
| `GetTotalTimeExclusive` |  | `double` |  |
| `GetTotalTimeInclusive` |  | `double` |  |
| `GetType` |  | `CString` |  |
| `GetVariant` |  | `CString` |  |
| `HasFileLocation` |  | `bool` |  |
| `HasSamples` |  | `bool` |  |
| `OpenInCodeEditor` |  | `void` |  |
| `OpenInScriptEditor` |  | `void` |  |
| `Select` |  | `void` |  |
| `SelectFile` |  | `void` |  |
| `Self` |  |  |  |

## ScriptProfilerFileLine

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAverageTimeExclusive` |  | `double` |  |
| `GetAverageTimeInclusive` |  | `double` |  |
| `GetBottleneckTime` |  | `double` |  |
| `GetCallCount` |  | `uint64` |  |
| `GetFormattedBottleneckTiming` |  | `CString` |  |
| `GetFormattedTiming` |  | `CString` |  |
| `GetLine` |  | `int32` |  |
| `GetMaxTimeInclusive` |  | `double` |  |
| `GetMinTimeInclusive` |  | `double` |  |
| `GetPerFrameTimeExclusive` |  | `double` |  |
| `GetPerFrameTimeInclusive` |  | `double` |  |
| `GetPerTickTimeExclusive` |  | `double` |  |
| `GetPerTickTimeInclusive` |  | `double` |  |
| `GetText` |  |  |  |
| `GetTiming` |  | `double` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTotalTimeExclusive` |  | `double` |  |
| `GetTotalTimeInclusive` |  | `double` |  |
| `HasSamples` |  | `bool` |  |
| `OpenInCodeEditor` |  | `void` |  |
| `OpenInScriptEditor` |  | `void` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |

## ScriptProfilerGui

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentEntry` |  | `ScriptProfilerEntry` |  |
| `GetFileSearchList` |  | `ToolPropertySearchList` |  |
| `GetModeSearchList` |  | `ToolPropertySearchList` |  |
| `AccessSelf` |  |  |  |
| `GetCaptureTime` |  | `double` |  |
| `GetCapturedFrames` |  | `uint64` |  |
| `GetCapturedSamples` |  | `int32` |  |
| `GetCapturedTicks` |  | `uint64` |  |
| `GetCurrentEntry` |  |  |  |
| `GetCurrentEntryChildren` |  |  |  |
| `GetCurrentEntryParents` |  |  |  |
| `GetFileLines` |  |  |  |
| `GetFileSearchList` |  |  |  |
| `GetModeSearchList` |  |  |  |
| `GetNextFile` |  |  |  |
| `GetPreviousFile` |  |  |  |
| `HasNextFile` |  | `bool` |  |
| `HasPreviousFile` |  | `bool` |  |
| `IsCapturing` |  | `bool` |  |
| `OpenFileInCodeEditor` |  | `void` |  |
| `OpenFileInScriptEditor` |  | `void` |  |
| `OpenNextFile` |  | `void` |  |
| `OpenPreviousFile` |  | `void` |  |
| `ResetCaptureData` |  | `void` |  |
| `RestartCapture` |  | `void` |  |
| `SelectEdge` |  | `void` |  |
| `SelectRoot` |  | `void` |  |
| `Self` |  |  |  |
| `StartCapture` |  | `void` |  |
| `StopCapture` |  | `void` |  |

## ScriptRunnerInspector

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessEffectResult` |  | `ScriptRunnerResult` |  |
| `AccessEventTargets` |  | `EventTargetSetupContext` |  |
| `AccessTriggerResult` |  | `ScriptRunnerResult` |  |
| `AccessSelf` |  |  |  |
| `GetEffect` |  | `CString` |  |
| `GetTrigger` |  | `CString` |  |
| `ParseEffect` |  | `void` |  |
| `RunEffect` |  | `void` |  |
| `RunTrigger` |  | `void` |  |
| `Self` |  |  |  |
| `SetEffect` |  | `void` |  |
| `SetTrigger` |  | `void` |  |
| `ShouldModifyEventTargets` |  | `bool` |  |
| `ToggleModifyEventTargets` |  | `void` |  |

## ScriptRunnerResult

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetResult` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `HasResult` |  | `bool` |  |
| `IsMissingTooltip` |  | `bool` |  |
| `IsOutputVisible` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleOutputVisible` |  | `void` |  |

## SeaNodeMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetProvince` |  | `Province` |  |
| `AccessSelf` |  |  |  |
| `GetAIDebugInfo` |  | `CString` |  |
| `GetInteractionColor` |  | `CVector4f` |  |
| `GetInteractionTooltip` |  | `CString` |  |
| `GetProvince` |  |  |  |
| `GetSupplyNetworkTooltip` |  | `CString` |  |
| `HasAIDebugInfo` |  | `bool` |  |
| `HasActiveSupplyNetwork` |  | `bool` |  |
| `HasAnyShippingLaneDamaged` | `Arg0` | `bool` |  |
| `IsActiveInteractionNode` |  | `bool` |  |
| `IsClickableInteractionNode` |  | `bool` |  |
| `IsSeaNodeHighlighted` |  | `bool` |  |
| `IsSeaNodeHighlightedByEnemy` |  | `bool` |  |
| `IsSeaNodeHighlightedByFriendly` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsValidInteractionNode` |  | `bool` |  |
| `SelectClick` |  | `void` |  |
| `SelectInteractionClick` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldShowInteraction` |  | `bool` |  |

## SeaNodeMovementMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSeaNode` |  | `Province` |  |
| `AccessSelf` |  |  |  |
| `AreSelectedFleetsProtectingSupply` |  | `bool` |  |
| `AreSelectedFleetsRaidingSupply` |  | `bool` |  |
| `CanDeploySelectedFormationsToSeaNode` |  | `bool` |  |
| `GetActiveSupplyNetworkDesc` |  | `CString` |  |
| `GetConvoyRaidingDesc` |  | `CString` |  |
| `GetConvoyRaidingEnemyFleetsDesc` |  | `CString` |  |
| `GetInvasionDesc` |  | `CString` |  |
| `GetInvasionStatus` |  | `CString` |  |
| `GetMaxSupplyShipsDestroyablePerBattle` |  | `int32` |  |
| `GetMaxSupplyShipsProtectablePerBattle` |  | `int32` |  |
| `GetOwnSupplyShipsPassingThroughNode` |  | `int32` |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetPresentFormationsBreakdown` |  | `CString` |  |
| `GetSeaNode` |  |  |  |
| `GetSelectedFormationsInvolvementChangeDesc` |  | `CString` |  |
| `GetSupplyRaidTargetsBreakdown` |  | `CString` |  |
| `GetSupplyShipPredictionBreakdown` |  | `CString` |  |
| `GetSupplyShipPredictionTotalDelta` |  | `int32` |  |
| `GetSupplyShipsPassingThroughNode` |  | `int32` |  |
| `GetTravelTimeBreakdown` |  | `CString` |  |
| `HasActiveSupplyNetwork` |  | `bool` |  |
| `HasOwnSupplyShipsPassingThrough` |  | `bool` |  |
| `HasSupplyRaidTargets` |  | `bool` |  |
| `HasSupplyShipPrediction` |  | `bool` |  |
| `IsAllSelectedFormationsLocation` |  | `bool` |  |
| `IsAllSelectedFormationsTarget` |  | `bool` |  |
| `IsAnySelectedFormationsLocation` |  | `bool` |  |
| `IsAnySelectedFormationsTarget` |  | `bool` |  |
| `IsBeingConvoyRaidedByEnemies` |  | `bool` |  |
| `IsBeingNavallyInvadedByEnemies` |  | `bool` |  |
| `Self` |  |  |  |

## SearchBar

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearText` |  | `void` |  |
| `FocusEditBox` |  | `void` |  |
| `GetQuery` |  | `CString` |  |
| `GetResults` |  |  |  |
| `HasFocus` |  | `bool` |  |
| `IsMouseOverResults` |  | `bool` |  |
| `IsQueryEmpty` |  | `bool` |  |
| `OnResultsMouseEnter` |  | `void` |  |
| `OnResultsMouseLeave` |  | `void` |  |
| `Self` |  |  |  |

## SearchListNodeWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanEditEntry` |  | `bool` |  |
| `GetEntryTooltip` |  | `CString` |  |
| `IsEntryEditingSupported` |  | `bool` |  |
| `OnEntryEditClick` |  | `void` |  |
| `Self` |  |  |  |

## SearchResult

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCategory` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetMatchSnippet` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `IsHighlighted` |  | `bool` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |

## SeaRegionInfraMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStateRegion` |  | `StateRegion` |  |
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetStateRegion` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `Self` |  |  |  |

## SeaRegionPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessProvince` |  | `Province` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `GetProvince` |  | `Province` |  |
| `AccessActiveBattles` |  |  |  |
| `AccessCountriesWithShippingLanes` |  |  |  |
| `AccessEndedBattles` |  |  |  |
| `AccessProvince` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessShippingLanes` |  |  |  |
| `GetExporters` | `Arg0` |  |  |
| `GetImporters` | `Arg0` |  |  |
| `GetNumTradedInWorldMarket` | `Arg0` | `CFixedPoint` |  |
| `GetPlayerSeaRegionWars` |  |  |  |
| `GetPresentNeutralFleets` |  |  |  |
| `GetProvince` |  |  |  |
| `GetWorldMarketTradeBreakdown` | `Arg0` | `CString` |  |
| `GetWorldMarketTradedGoods` |  |  |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## SeaRegionWar

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetWar` |  | `War` |  |
| `AccessSelf` |  |  |  |
| `GetAlliedCountriesWithShippingLanes` |  |  |  |
| `GetAlliedFleets` |  |  |  |
| `GetEnemyCountriesWithShippingLanes` |  |  |  |
| `GetEnemyFleets` |  |  |  |
| `GetInvasions` |  |  |  |
| `GetWar` |  |  |  |
| `Self` |  |  |  |

## SelectFromInputNodeWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddPin` |  | `void` |  |
| `GetNumberOfPins` |  | `int32` |  |
| `RemovePin` |  | `void` |  |
| `Self` |  |  |  |
| `SetNumberOfPins` |  | `void` |  |

## SelectParticleUserDataDialog

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `DataModel` |  |  |  |
| `Self` |  |  |  |

## SelectTool

Map Editor - Map Object - Select Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsHideSelection` |  | `bool` |  |
| `Self` |  |  |  |
| `SetHideSelection` | `Arg0` | `void` |  |

## ServerInformation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMPMode` |  | `CString` |  |
| `GetServerID` |  | `CUTF8String` |  |
| `GetServerName` |  | `CUTF8String` |  |
| `HasServerID` |  | `bool` |  |
| `HasServerName` |  | `bool` |  |
| `IsInvite` |  | `bool` |  |
| `IsPublic` |  | `bool` |  |
| `IsSingleplayer` |  | `bool` |  |
| `Self` |  |  |  |

## SettingCategory

Jomini Settings - Category

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AccessSettingsOrder` |  |  |  |
| `GetName` |  | `CUTF8String` |  |
| `GetSettingsOrder` |  |  |  |
| `HasSettingsWidgets` |  | `bool` |  |
| `Self` |  |  |  |

## SettingsPage

Jomini Settings - Settings Page

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCategories` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CUTF8String` |  |
| `IsSelected` |  | `bool` |  |
| `OnClick` |  | `void` |  |
| `Self` |  |  |  |

## Ship

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetFleet` |  | `MilitaryFormation` |  |
| `GetGroup` |  | `ShipGroup` |  |
| `GetModificationTypeNew` | `Arg0` | `ShipModificationType` |  |
| `GetModificationTypeOld` | `Arg0` | `ShipModificationType` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetNavalBattle` |  | `NavalBattle` |  |
| `GetRepair` |  | `ShipConstruction` |  |
| `GetRetrofit` |  | `ShipConstruction` |  |
| `GetTargetFleet` |  | `MilitaryFormation` |  |
| `GetTemplate` |  | `ShipTemplate` |  |
| `GetType` |  | `ShipType` |  |
| `GetVeterancyLevel` |  | `ShipVeterancyLevel` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `AssignAsFlagship` |  | `Command` |  |
| `CanBeFlagship` |  | `bool` |  |
| `CancelRetrofit` |  | `Command` |  |
| `ChangeTemplate` | `Arg0` | `Command` |  |
| `Decommission` |  | `Command` |  |
| `GetAccuracy` |  | `CFixedPoint` |  |
| `GetAccuracyBreakdown` |  | `CString` |  |
| `GetArmor` |  | `CFixedPoint` |  |
| `GetArmorBreakdown` |  | `CString` |  |
| `GetAverageAttackDamage` |  | `CFixedPoint` |  |
| `GetAverageCriticalHitDamage` |  | `CFixedPoint` |  |
| `GetAverageCriticalHitDamageBreakdown` |  | `CString` |  |
| `GetBlockadeStrength` |  | `CFixedPoint` |  |
| `GetBlockadeStrengthBreakdown` |  | `CString` |  |
| `GetCarryingCapacity` |  | `CFixedPoint` |  |
| `GetCarryingCapacityBreakdown` |  | `CString` |  |
| `GetCrewBreakdown` |  | `CString` |  |
| `GetCrewDamage` |  | `CFixedPoint` |  |
| `GetCrewDamageBreakdown` |  | `CString` |  |
| `GetCrewMax` |  | `CFixedPoint` |  |
| `GetCrewMaxBreakdown` |  | `CString` |  |
| `GetCrewOriginStates` |  |  |  |
| `GetCriticalHitChance` |  | `CFixedPoint` |  |
| `GetCriticalHitChanceBreakdown` |  | `CString` |  |
| `GetCriticalHitMultiplier` |  | `CFixedPoint` |  |
| `GetCriticalHitMultiplierBreakdown` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDetection` |  | `CFixedPoint` |  |
| `GetDetectionBreakdown` |  | `CString` |  |
| `GetFlagshipOrnamentName` |  | `CString` |  |
| `GetHitPoints` |  | `CFixedPoint` |  |
| `GetHitPointsMax` |  | `CFixedPoint` |  |
| `GetHitPointsMaxBreakdown` |  | `CString` |  |
| `GetHitPointsPercentage` |  | `CFixedPoint` |  |
| `GetHullDamage` |  | `CFixedPoint` |  |
| `GetHullDamageBreakdown` |  | `CString` |  |
| `GetMarineCapacity` |  | `CFixedPoint` |  |
| `GetMarineCapacityBreakdown` |  | `CString` |  |
| `GetMaxDistanceToPort` |  | `int32` |  |
| `GetMaxDistanceToPortBreakdown` |  | `CString` |  |
| `GetModificationSlotsChanged` |  |  |  |
| `GetModifications` |  |  |  |
| `GetMovementSpeed` |  | `CFixedPoint` |  |
| `GetMovementSpeedBreakdown` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoFormattingLowercasePrefix` |  | `CString` |  |
| `GetNumCrewFromState` | `Arg0` | `int32` |  |
| `GetPowerProjection` |  | `CFixedPoint` |  |
| `GetReadinessGain` |  | `CFixedPoint` |  |
| `GetReadinessGainBreakdown` |  | `CString` |  |
| `GetRetrofitCost` |  | `CFixedPoint` |  |
| `GetRetrofitCostBreakdown` |  | `CString` |  |
| `GetRetrofitCostDesc` |  | `CString` |  |
| `GetRetrofitProgress` |  | `CFixedPoint` |  |
| `GetRetrofitWeeks` |  | `int32` |  |
| `GetRetrofitWeeksLeft` |  | `int32` |  |
| `GetScreening` |  | `CFixedPoint` |  |
| `GetScreeningBreakdown` |  | `CString` |  |
| `GetSpeedPerDay` |  | `CFixedPoint` |  |
| `GetSupplyCapacity` |  | `CFixedPoint` |  |
| `GetSupplyCapacityBreakdown` |  | `CString` |  |
| `GetSupplyEfficiency` |  | `CFixedPoint` |  |
| `GetSupplyEfficiencyBreakdown` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalCrew` |  | `int32` |  |
| `GetUpkeepCost` |  | `CFixedPoint` |  |
| `GetUpkeepCostBreakdown` |  | `CString` |  |
| `GetUtilityModifications` |  |  |  |
| `GetUtilityModificationsChanged` |  |  |  |
| `GetVeterancyExperience` |  | `CFixedPoint` |  |
| `GetVeterancyExperienceNeededForNextLevel` |  | `CFixedPoint` |  |
| `GetVeterancyExperienceRelativeToCurrentLevel` |  | `CFixedPoint` |  |
| `GetVeterancyExperienceWeeklyDecay` |  | `CFixedPoint` |  |
| `GetVeterancyExperienceWeeklyGain` |  | `CFixedPoint` |  |
| `GetVeterancyLevelUpProgress` |  | `CFixedPoint` |  |
| `GetVisibility` |  | `CFixedPoint` |  |
| `GetVisibilityBreakdown` |  | `CString` |  |
| `GetVulnerability` |  | `CFixedPoint` |  |
| `GetVulnerabilityBreakdown` |  | `CString` |  |
| `HasFlagshipSignalFlags` |  | `bool` |  |
| `IsAtMaxVeterancy` |  | `bool` |  |
| `IsDecayingVeterancyExperience` |  | `bool` |  |
| `IsDestroyed` |  | `bool` |  |
| `IsFlagship` |  | `bool` |  |
| `IsGainingVeterancyExperience` |  | `bool` |  |
| `IsInBattle` |  | `bool` |  |
| `IsOutdated` |  | `bool` |  |
| `IsToRetrofit` |  | `bool` |  |
| `IsUtilityModificationNew` | `Arg0` | `bool` |  |
| `IsUtilityModificationOld` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsVeterancyExperienceDecayPaused` |  | `bool` |  |
| `IsZoomingTo` |  | `bool` |  |
| `Retrofit` |  | `Command` |  |
| `Self` |  |  |  |
| `SetNextFlagshipOrnament` |  | `Command` |  |
| `SetPrevFlagshipOrnament` |  | `Command` |  |
| `SortCrewOriginStates` | `Arg0` | `void` |  |
| `ToggleFlagshipSignalFlags` |  | `Command` |  |
| `UnassignAsFlagship` |  | `Command` |  |
| `ZoomTo` |  | `void` |  |

## ShipChangeNamePopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetShip` |  | `Ship` |  |
| `AccessSelf` |  |  |  |
| `Confirm` |  | `Command` |  |
| `GetShip` |  |  |  |
| `OnEditName` |  | `void` |  |
| `Self` |  |  |  |

## ShipConstruction

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetFleet` |  | `MilitaryFormation` |  |
| `GetShip` |  | `Ship` |  |
| `GetShipTemplate` |  | `ShipTemplate` |  |
| `GetShipType` |  | `ShipType` |  |
| `GetSpawnRegion` |  | `StrategicRegion` |  |
| `AccessSelf` |  |  |  |
| `Cancel` |  | `Command` |  |
| `GetConstructionCost` |  | `CFixedPoint` |  |
| `GetConstructionSpeed` |  | `CFixedPoint` |  |
| `GetConstructionUsage` |  | `CFixedPoint` |  |
| `GetEfficiency` |  | `CFixedPoint` |  |
| `GetIndex` |  | `int32` |  |
| `GetPlaceInQueue` |  | `int32` |  |
| `GetProgress` |  | `CFixedPoint` |  |
| `GetProgressPercent` |  | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetWeeksLeft` |  | `int32` |  |
| `IsInProgress` |  | `bool` |  |
| `IsRepair` |  | `bool` |  |
| `IsRetrofit` |  | `bool` |  |
| `MoveDown` |  | `Command` |  |
| `MoveToBottom` |  | `Command` |  |
| `MoveToIndex` | `Arg0` | `Command` |  |
| `MoveToTop` |  | `Command` |  |
| `MoveUp` |  | `Command` |  |
| `Self` |  |  |  |

## ShipConstructionQueue

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## ShipCostPoint

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetModificationLevel` |  | `int32` |  |
| `GetPosition` |  | `CVector2f` |  |
| `IsCurrent` |  | `bool` |  |
| `IsIncluded` |  | `bool` |  |
| `Self` |  |  |  |

## ShipDesignerModSlot

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedModification` |  | `ShipModificationType` |  |
| `GetSlot` |  | `ShipModificationSlotType` |  |
| `AccessSelf` |  |  |  |
| `GetModifications` |  |  |  |
| `GetSelectedModification` |  |  |  |
| `GetSlot` |  |  |  |
| `GetSlotButtonName` | `Arg0` | `CString` |  |
| `HasSelection` |  | `bool` |  |
| `IsModificationBlocked` | `Arg0` | `bool` |  |
| `IsModificationSelectedInOtherSlot` | `Arg0` | `bool` |  |
| `IsModificationSelectedInSlot` | `Arg0` | `bool` |  |
| `IsUtility` |  | `bool` |  |
| `OnDeselectModification` |  | `void` |  |
| `OnSelectModificationForSlot` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## ShipDesignerPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentShipType` |  | `ShipType` |  |
| `GetShipViewer` |  | `ShipViewer` |  |
| `GetTemplate` |  | `ShipTemplate` |  |
| `GetTemplateEdited` |  | `ShipTemplate` |  |
| `AccessSelf` |  |  |  |
| `CreateTemplate` |  | `Command` |  |
| `EditTemplate` |  | `Command` |  |
| `GetChosenName` |  | `CString` |  |
| `GetConstructionCostDifference` |  | `CFixedPoint` |  |
| `GetConstructionWeeksForLevel` | `Arg0` | `int32` |  |
| `GetCostCurve` |  |  |  |
| `GetCostDescForLevel` | `Arg0` | `CString` |  |
| `GetCostForLevel` | `Arg0` | `CFixedPoint` |  |
| `GetCostPoints` |  |  |  |
| `GetCurrentShipType` |  |  |  |
| `GetGraphicsTypeSelected` |  |  |  |
| `GetGraphicsTypesAvailable` |  |  |  |
| `GetMaintenanceCostDifference` |  | `CFixedPoint` |  |
| `GetModificationSlots` |  |  |  |
| `GetNumGraphicsTypesAvailable` |  | `int32` |  |
| `GetRetrofitAllCost` |  | `CFixedPoint` |  |
| `GetRetrofitAllCostDesc` |  | `CString` |  |
| `GetRetrofitCost` |  | `CFixedPoint` |  |
| `GetRetrofitCostDesc` |  | `CString` |  |
| `GetShipTypes` |  |  |  |
| `GetShipViewer` |  |  |  |
| `GetTemplate` |  |  |  |
| `GetTemplateEdited` |  |  |  |
| `GetUtilityModificationSlots` |  |  |  |
| `HasCurrentShipType` |  | `bool` |  |
| `IsCreating` |  | `bool` |  |
| `IsEditing` |  | `bool` |  |
| `OnEditName` |  | `void` |  |
| `SelectGraphicsType` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetShipTemplate` | `Arg0` | `void` |  |
| `SetShipType` | `Arg0` | `void` |  |
| `ToggleRetrofit` |  | `void` |  |
| `WillRetrofit` |  | `bool` |  |

## ShipFilter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetShipsFiltered` |  |  |  |
| `IsFilterSelected` | `Arg0` | `bool` |  |
| `IsUnfiltered` |  | `bool` |  |
| `ResetFilters` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleFilter` | `Arg0` | `void` |  |

## ShipGraphicsType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `Self` |  |  |  |

## ShipGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetShipTypes` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUIColor` |  | `CVector4f` |  |
| `Self` |  |  |  |

## ShipList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetActiveSelection` |  | `ShipSelection` |  |
| `GetFilterOfGroup` | `Arg0` | `ShipFilter` |  |
| `GetFleet` |  | `MilitaryFormation` |  |
| `GetMostCommonShipTypeOfGroup` | `Arg0` | `ShipType` |  |
| `AccessSelf` |  |  |  |
| `DeactivateEditMode` |  | `void` |  |
| `GetArmorAverage` |  | `CFixedPoint` |  |
| `GetBlockadeStrength` |  | `CFixedPoint` |  |
| `GetBlockadeStrengthMax` |  | `CFixedPoint` |  |
| `GetCrew` |  | `int32` |  |
| `GetCrewDamageAverage` |  | `CFixedPoint` |  |
| `GetCrewMax` |  | `int32` |  |
| `GetCrewOriginStates` |  |  |  |
| `GetCrewPercentage` |  | `CFixedPoint` |  |
| `GetDamageAverage` |  | `CFixedPoint` |  |
| `GetHitPoints` |  | `CFixedPoint` |  |
| `GetHitPointsMax` |  | `CFixedPoint` |  |
| `GetHitPointsPercentage` |  | `CFixedPoint` |  |
| `GetHullDamageAverage` |  | `CFixedPoint` |  |
| `GetNumCrewFromState` | `Arg0` | `int32` |  |
| `GetNumNewShipsUnderConstruction` |  | `int32` |  |
| `GetNumNewShipsUnderConstructionOfGroup` | `Arg0` | `int32` |  |
| `GetNumNewShipsUnderConstructionOfTemplate` | `Arg0` | `int32` |  |
| `GetNumNewShipsUnderConstructionOfType` | `Arg0` | `int32` |  |
| `GetNumShips` |  | `int32` |  |
| `GetNumShipsCanRetrofit` |  | `int32` |  |
| `GetNumShipsCannotRetrofit` |  | `int32` |  |
| `GetNumShipsFromState` | `Arg0` | `int32` |  |
| `GetNumShipsOfGroup` | `Arg0` | `int32` |  |
| `GetNumShipsOfTemplate` | `Arg0` | `int32` |  |
| `GetNumShipsOfType` | `Arg0` | `int32` |  |
| `GetNumShipsOutdated` |  | `int32` |  |
| `GetNumShipsOutdatedOfGroup` | `Arg0` | `int32` |  |
| `GetNumShipsToRetrofit` |  | `int32` |  |
| `GetNumShipsUnderConstruction` |  | `int32` |  |
| `GetNumShipsUnderConstructionOfGroup` | `Arg0` | `int32` |  |
| `GetNumShipsUnderConstructionOfType` | `Arg0` | `int32` |  |
| `GetShipConstructions` |  |  |  |
| `GetShipConstructionsOfGroup` | `Arg0` |  |  |
| `GetShipConstructionsOfType` | `Arg0` |  |  |
| `GetShipCrewBreakdown` | `Arg0` | `CString` |  |
| `GetShipGroups` |  |  |  |
| `GetShipGroupsBreakdown` |  | `CString` |  |
| `GetShipTemplates` |  |  |  |
| `GetShipTemplatesOfGroup` | `Arg0` |  |  |
| `GetShipTemplatesOfType` | `Arg0` |  |  |
| `GetShipTypes` |  |  |  |
| `GetShipTypesOfGroup` | `Arg0` |  |  |
| `GetShipTypesOfGroupBreakdown` | `Arg0` | `CString` |  |
| `GetShips` |  |  |  |
| `GetShipsOfGroup` | `Arg0` |  |  |
| `GetShipsOfTemplate` | `Arg0` |  |  |
| `GetShipsOfType` | `Arg0` |  |  |
| `GetShipsOfTypeBreakdown` | `Arg0` | `CString` |  |
| `GetSupplyExpenses` |  | `CFixedPoint` |  |
| `GetSupplyExpensesDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasAnyShipOutdated` |  | `bool` |  |
| `HasAnyShipOutdatedOfGroup` | `Arg0` | `bool` |  |
| `HasNewShipConstructionQueued` |  | `bool` |  |
| `HasNewShipConstructionQueuedOfGroup` | `Arg0` | `bool` |  |
| `HasNewShipConstructionQueuedOfTemplate` | `Arg0` | `bool` |  |
| `HasNewShipConstructionQueuedOfType` | `Arg0` | `bool` |  |
| `HasShipConstructionQueued` |  | `bool` |  |
| `HasShipConstructionQueuedOfGroup` | `Arg0` | `bool` |  |
| `HasShipConstructionQueuedOfType` | `Arg0` | `bool` |  |
| `IsEditModeActive` |  | `bool` |  |
| `IsEditModeActiveForGroup` | `Arg0` | `bool` |  |
| `IsToRetrofit` |  | `bool` |  |
| `Self` |  |  |  |
| `SortCrewOriginStates` | `Arg0` | `void` |  |
| `ToggleEditMode` | `Arg0` | `void` |  |

## ShipModificationSlotType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsUtility` |  | `bool` |  |
| `Self` |  |  |  |

## ShipModificationType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetConstructionGoodsModifier` |  | `Modifier` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetSlotType` |  | `ShipModificationSlotType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetApplicableShipTypes` |  |  |  |
| `GetApplicableShipTypesString` |  | `CString` |  |
| `GetClickSound` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetID` |  | `int32` |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTechRequirements` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasRequiredTech` |  | `bool` |  |
| `IsUtility` |  | `bool` |  |
| `Self` |  |  |  |

## ShipPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetShip` |  | `Ship` |  |
| `GetShipViewer` |  | `ShipViewer` |  |
| `AccessSelf` |  |  |  |
| `GetShip` |  |  |  |
| `GetShipViewer` |  |  |  |
| `Self` |  |  |  |

## ShippingLane

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBeginState` |  | `State` |  |
| `GetCountry` |  | `Country` |  |
| `GetEndState` |  | `State` |  |
| `GetProvince` |  | `Province` |  |
| `GetTreaty` |  | `Treaty` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBeginState` |  |  |  |
| `GetConvoyCostFormatted` |  | `CString` |  |
| `GetConvoyCostFormattedShort` |  | `CString` |  |
| `GetConvoyCostRaw` |  | `int32` |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectivenessFormatted` |  | `CString` |  |
| `GetEffectivenessRaw` |  | `CFixedPoint` |  |
| `GetEndState` |  |  |  |
| `GetGoodsListDesc` |  | `CString` |  |
| `GetMerchantMarineDemandFormatted` |  | `CString` |  |
| `GetMerchantMarineDemandRaw` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsGoodsTransfer` |  | `bool` |  |
| `IsPortConnection` |  | `bool` |  |
| `Self` |  |  |  |

## ShipSelection

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTypeOfShipsSelected` |  | `ShipType` |  |
| `AccessSelf` |  |  |  |
| `CanChangeTemplate` |  | `bool` |  |
| `ChangeTemplate` | `Arg0` | `Command` |  |
| `Decommission` |  | `Command` |  |
| `GetChangeTemplateDesc` |  | `CString` |  |
| `GetNumShipsSelected` |  | `int32` |  |
| `GetNumShipsSelectedOfTemplate` | `Arg0` | `int32` |  |
| `GetNumTemplatesAvailable` |  | `int32` |  |
| `GetRetrofitCost` |  | `CFixedPoint` |  |
| `GetRetrofitCostDesc` |  | `CString` |  |
| `GetShipsFiltered` |  |  |  |
| `GetTemplatesAvailable` |  |  |  |
| `GetTemplatesSelected` |  |  |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `ResetSelection` |  | `void` |  |
| `Retrofit` |  | `Command` |  |
| `SelectFiltered` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleSelection` | `Arg0` | `void` |  |

## ShipTemplate

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetType` |  | `ShipType` |  |
| `AccessSelf` |  |  |  |
| `CancelConstruction` |  | `Command` |  |
| `CancelConstructionForFleet` | `Arg0` | `Command` |  |
| `DeleteTemplate` |  | `Command` |  |
| `GetAccuracy` |  | `CFixedPoint` |  |
| `GetAccuracyBreakdown` |  | `CString` |  |
| `GetArmor` |  | `CFixedPoint` |  |
| `GetArmorBreakdown` |  | `CString` |  |
| `GetBlockadeStrength` |  | `CFixedPoint` |  |
| `GetBlockadeStrengthBreakdown` |  | `CString` |  |
| `GetCarryingCapacity` |  | `CFixedPoint` |  |
| `GetCarryingCapacityBreakdown` |  | `CString` |  |
| `GetConstructionCost` |  | `CFixedPoint` |  |
| `GetConstructionCostDesc` |  | `CString` |  |
| `GetConstructionGoodsCost` |  | `CFixedPoint` |  |
| `GetConstructionGoodsCostDesc` |  | `CString` |  |
| `GetConstructionGoodsDesc` |  | `CString` |  |
| `GetConstructionProgressMax` |  | `CFixedPoint` |  |
| `GetConstructionWeeks` |  | `int32` |  |
| `GetCrewDamage` |  | `CFixedPoint` |  |
| `GetCrewDamageBreakdown` |  | `CString` |  |
| `GetCrewMax` |  | `CFixedPoint` |  |
| `GetCrewMaxBreakdown` |  | `CString` |  |
| `GetCriticalHitChance` |  | `CFixedPoint` |  |
| `GetCriticalHitChanceBreakdown` |  | `CString` |  |
| `GetCriticalHitMultiplier` |  | `CFixedPoint` |  |
| `GetCriticalHitMultiplierBreakdown` |  | `CString` |  |
| `GetDetection` |  | `CFixedPoint` |  |
| `GetDetectionBreakdown` |  | `CString` |  |
| `GetHitPointsMax` |  | `CFixedPoint` |  |
| `GetHitPointsMaxBreakdown` |  | `CString` |  |
| `GetHullDamage` |  | `CFixedPoint` |  |
| `GetHullDamageBreakdown` |  | `CString` |  |
| `GetMarineCapacity` |  | `CFixedPoint` |  |
| `GetMarineCapacityBreakdown` |  | `CString` |  |
| `GetMaterielGoodsDesc` |  | `CString` |  |
| `GetMaxDistanceToPort` |  | `int32` |  |
| `GetMaxDistanceToPortDesc` |  | `CString` |  |
| `GetModifications` |  |  |  |
| `GetMovementSpeed` |  | `CFixedPoint` |  |
| `GetMovementSpeedBreakdown` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetReadinessGain` |  | `CFixedPoint` |  |
| `GetReadinessGainBreakdown` |  | `CString` |  |
| `GetScreening` |  | `CFixedPoint` |  |
| `GetScreeningBreakdown` |  | `CString` |  |
| `GetSupplyCapacity` |  | `CFixedPoint` |  |
| `GetSupplyCapacityBreakdown` |  | `CString` |  |
| `GetSupplyEfficiency` |  | `CFixedPoint` |  |
| `GetSupplyEfficiencyBreakdown` |  | `CString` |  |
| `GetSupplyGoodsCost` |  | `CFixedPoint` |  |
| `GetSupplyGoodsCostDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalMaintenanceCost` |  | `CFixedPoint` |  |
| `GetTotalMaintenanceCostDesc` |  | `CString` |  |
| `GetUtilityModifications` |  |  |  |
| `GetVisibility` |  | `CFixedPoint` |  |
| `GetVisibilityBreakdown` |  | `CString` |  |
| `GetVulnerability` |  | `CFixedPoint` |  |
| `GetVulnerabilityBreakdown` |  | `CString` |  |
| `HasFlagshipSignalFlagsEntity` |  | `bool` |  |
| `IsBase` |  | `bool` |  |
| `IsCustom` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `QueueConstruction` |  | `Command` |  |
| `QueueConstructionForFleet` | `Arg0` | `Command` |  |
| `Self` |  |  |  |
| `SetAsDefaultForCountry` |  | `Command` |  |
| `SetAsDefaultForFleet` | `Arg0` | `Command` |  |

## ShipTemplateList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDefaultTemplateForFleetOfType` | `Arg0, Arg1` | `ShipTemplate` |  |
| `GetDefaultTemplateOfType` | `Arg0` | `ShipTemplate` |  |
| `AccessSelf` |  |  |  |
| `GetTemplatesOfType` | `Arg0` |  |  |
| `GetTypesAvailableOfGroup` | `Arg0` |  |  |
| `GetTypesObsoleteOfGroup` | `Arg0` |  |  |
| `GetTypesUnavailableOfGroup` | `Arg0` |  |  |
| `Self` |  |  |  |

## ShipTemplateVersion

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## ShipType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetConstructionGoodsModifier` |  | `Modifier` |  |
| `GetDistanceToPortModifier` |  | `Modifier` |  |
| `GetGroup` |  | `ShipGroup` |  |
| `GetMaterielGoodsModifier` |  | `Modifier` |  |
| `GetModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetID` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetMaxDistanceToPort` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetProfileTexture` |  |  |  |
| `GetTechRequirements` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasRequiredTech` |  | `bool` |  |
| `IsObsolete` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## ShipVeterancyLevel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetNextLevel` |  | `ShipVeterancyLevel` |  |
| `AccessSelf` |  |  |  |
| `GetCurrentLevel` |  | `int32` |  |
| `GetExperienceThreshold` |  | `CFixedPoint` |  |
| `GetModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNextLevelRelativeExperienceThreshold` |  | `CFixedPoint` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsMaxLevel` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## ShipViewer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCameraLookAt` |  | `CVector3f` |  |
| `GetCameraPosition` |  | `CVector3f` |  |
| `GetEntity` |  |  |  |
| `ResetCamera` |  | `void` |  |
| `Self` |  |  |  |
| `StartEntityState` | `Arg0` | `void` |  |

## SkinEditor

GFX Skin Editor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## SmartBrushHeightRange

Map Editor - Smart Material Painter - Brush Height

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPattern` |  | `SmartBrushPattern` |  |
| `AccessPattern` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CUTF8String` |  |
| `GetOpacityMaskTexturePath` |  | `CString` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## SmartBrushPattern

Map Editor - Smart Material Painter - Brush Patter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMaterialMix` |  | `MaterialMix` |  |
| `AccessMaterialMix` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetAngleL` |  | `float` |  |
| `GetAngleR` |  | `float` |  |
| `GetBleeding` |  | `uint32` |  |
| `GetDensity` |  | `int32` |  |
| `GetInterpolationIndex` |  | `CVector2i` |  |
| `GetModeIndex` |  | `int32` |  |
| `GetPatternIndex` |  | `CVector2i` |  |
| `GetSharpness` |  | `uint32` |  |
| `Self` |  |  |  |

## SmartBrushPresetManager

Map Editor - Smart Material Painter - Brush Preset Manager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPresets` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetPresets` |  |  |  |
| `Self` |  |  |  |

## SmartMaterialPaintingMode

Map Editor - Smart Material Painter Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCurrentPreset` |  |  |  |
| `AccessCurrentPresetRanges` |  |  |  |
| `AccessOpacityMaskTexturePreview` | `Arg0` |  |  |
| `AccessPatternCurveTexture` | `Arg0` |  |  |
| `AccessPatternTypeTexture` | `Arg0` |  |  |
| `AccessSelf` |  |  |  |
| `AddAngle` | `Arg0, Arg1, Arg2` | `void` |  |
| `AddBleeding` | `Arg0, Arg1` | `void` |  |
| `AddDensity` | `Arg0, Arg1` | `void` |  |
| `AddOpacityMaskOffset` | `Arg0, Arg1, Arg2` | `void` |  |
| `AddOpacityMaskRotation` | `Arg0, Arg1` | `void` |  |
| `AddOpacityMaskScale` | `Arg0, Arg1, Arg2` | `void` |  |
| `AddSharpness` | `Arg0, Arg1` | `void` |  |
| `ApplyChanges` |  | `void` |  |
| `CanApplyChanges` |  | `bool` |  |
| `CanReorderRangeToNext` | `Arg0` | `bool` |  |
| `CanReorderRangeToPrev` | `Arg0` | `bool` |  |
| `ChangeSampleEntryComposition` | `Arg0, Arg1, Arg2, Arg3` | `void` |  |
| `ClearOpacityMaskTexture` | `Arg0` | `void` |  |
| `ClonePreset` |  | `void` |  |
| `CopyCurveToClipboard` | `Arg0` | `void` |  |
| `CreateNewPreset` |  | `void` |  |
| `CreateNewRange` |  | `void` |  |
| `DeletePreset` |  | `void` |  |
| `DeleteRange` | `Arg0` | `void` |  |
| `DiscardChanges` |  | `void` |  |
| `EndSampleCompositionEdit` | `Arg0, Arg1, Arg2` | `void` |  |
| `GetBackgroundProcessingDesc` |  | `CString` |  |
| `GetCurrentPreset` |  |  |  |
| `GetCurveFromClipboard` |  |  |  |
| `GetDebugDesc` |  | `CString` |  |
| `GetDebugUIHint` |  | `CString` |  |
| `GetOpacityMaskOffset` | `Arg0, Arg1` | `float` |  |
| `GetOpacityMaskRotation` | `Arg0` | `float` |  |
| `GetOpacityMaskScale` | `Arg0, Arg1` | `float` |  |
| `GetPaintingForbiddenDesc` |  | `CString` |  |
| `GetPresetIndex` |  | `CVector2i` |  |
| `GetRangeName` | `Arg0` | `CUTF8String` |  |
| `GetTopologyPickerDesc` |  | `CString` |  |
| `HasAnyPresets` |  | `bool` |  |
| `HasDoneAnyChangesToPresets` |  | `bool` |  |
| `HasOpacityMaskTexture` | `Arg0` | `bool` |  |
| `IsAutosave` |  | `bool` |  |
| `IsBackgroundProcessing` |  | `bool` |  |
| `IsCurrentPresetValid` |  | `bool` |  |
| `IsCurveClipboardEmpty` |  | `bool` |  |
| `IsDebugActive` |  | `bool` |  |
| `IsDebugActiveFor` | `Arg0` | `bool` |  |
| `IsDebugTooltipVisible` |  | `bool` |  |
| `IsDebuggingSinglePoint` |  | `bool` |  |
| `IsEraserSelected` |  | `bool` |  |
| `IsEyeDropperSelected` |  | `bool` |  |
| `IsHeightRangeVisible` | `Arg0` | `bool` |  |
| `IsOpacityMaskTextureLoading` | `Arg0` | `bool` |  |
| `IsPainterSelected` |  | `bool` |  |
| `IsPaintingForbidden` |  | `bool` |  |
| `IsPaintingForbiddenTooltipActive` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsTopologyPickerEnabled` |  | `bool` |  |
| `IsTopologyPickerTooltipActive` |  | `bool` |  |
| `IsVisualDebuggingTooltipActive` |  | `bool` |  |
| `ReloadPresets` |  | `void` |  |
| `RemoveMaterialEntry` | `Arg0, Arg1` | `void` |  |
| `RenamePreset` |  | `void` |  |
| `ReorderRangeToNext` | `Arg0` | `void` |  |
| `ReorderRangeToPrev` | `Arg0` | `void` |  |
| `SavePresets` |  | `void` |  |
| `Self` |  |  |  |
| `SetAngleAsString` | `Arg0, Arg1` | `void` |  |
| `SetBleedingAsString` | `Arg0` | `void` |  |
| `SetDensityAsString` | `Arg0` | `void` |  |
| `SetEraserSelected` |  | `void` |  |
| `SetEyeDropperSelected` |  | `void` |  |
| `SetHeightRangeName` | `Arg0` | `void` |  |
| `SetInterpolationIndex` | `Arg0` | `void` |  |
| `SetOpacityMaskOffsetAsString` | `Arg0, Arg1` | `void` |  |
| `SetOpacityMaskRotationAsString` | `Arg0` | `void` |  |
| `SetOpacityMaskScaleAsString` | `Arg0, Arg1` | `void` |  |
| `SetPainterSelected` |  | `void` |  |
| `SetPatternIndex` | `Arg0, Arg1` | `void` |  |
| `SetPatternMode` | `Arg0, Arg1` | `void` |  |
| `SetPresetIndex` |  | `void` |  |
| `SetSharpnessAsString` | `Arg0` | `void` |  |
| `ShowMaterialBrowserAndAddToCurrentPattern` | `Arg0` | `void` |  |
| `ShowMaterialBrowserAndSetEntryInCurrentPattern` | `Arg0, Arg1` | `void` |  |
| `StartSampleCompositionEdit` | `Arg0` | `void` |  |
| `ToggleAutosave` |  | `void` |  |
| `ToggleDebugActiveFor` | `Arg0` | `void` |  |
| `ToggleHeightRangeVisible` | `Arg0` | `void` |  |
| `ToggleMaterialLock` | `Arg0` | `void` |  |
| `ToggleSampleEntryLock` | `Arg0, Arg1, Arg2, Arg3` | `void` |  |
| `ToggleTopologyPicker` |  | `void` |  |

## Social

Jomini Social Manager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTotalUnreadChatMessages` |  | `int32` |  |
| `Self` |  |  |  |

## SocialClass

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMaxAllowedStatusIn` | `Arg0` | `AcceptanceStatus` |  |
| `GetMinAllowedStatusIn` | `Arg0` | `AcceptanceStatus` |  |
| `GetSocialHierarchy` |  | `SocialHierarchy` |  |
| `AccessSelf` |  |  |  |
| `GetAllowedProfessions` |  |  |  |
| `GetAllowedStatusesIn` | `Arg0` |  |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectsDescIn` | `Arg0` | `CString` |  |
| `GetMaxAcceptanceIn` | `Arg0` | `int32` |  |
| `GetMaxAllowedStatusIn` | `Arg0` |  |  |
| `GetMinAcceptanceIn` | `Arg0` | `int32` |  |
| `GetMinAllowedStatusIn` | `Arg0` |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetPopTriggerDesc` |  | `CString` |  |
| `GetSocialHierarchy` |  |  |  |
| `GetStrataConcept` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalPopulationIn` | `Arg0` | `int64` |  |
| `HasBoundedAcceptanceIn` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## SocialHierarchy

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAllSocialClassesDesc` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetLowerStrataPopTypesDesc` |  | `CString` |  |
| `GetLowerStrataSocialClasses` |  |  |  |
| `GetLowerStrataSocialClassesDesc` |  | `CString` |  |
| `GetMaxSocialClassesInAnyStrata` |  | `int32` |  |
| `GetMiddleStrataPopTypesDesc` |  | `CString` |  |
| `GetMiddleStrataSocialClasses` |  |  |  |
| `GetMiddleStrataSocialClassesDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetPopTriggerDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalPopulationIn` | `Arg0` | `int64` |  |
| `GetUpperStrataPopTypesDesc` |  | `CString` |  |
| `GetUpperStrataSocialClasses` |  |  |  |
| `GetUpperStrataSocialClassesDesc` |  | `CString` |  |
| `IsDefault` |  | `bool` |  |
| `Self` |  |  |  |

## SocialNotificationWindow

Jomini Friend List - Notification window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessChatMessages` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetNotificationsLayoutAnchor` |  |  |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldBeShown` |  | `bool` |  |
| `Show` |  | `void` |  |

## SocialUI

Jomini Friend List - Social UI

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Hide` |  | `void` |  |
| `IsAllowedToBeShown` |  | `bool` |  |
| `Self` |  |  |  |
| `Show` |  | `void` |  |
| `ToggleShow` |  | `void` |  |
| `WantsToBeShown` |  | `bool` |  |

## SocialWidget

Jomini Social Widget

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## SocietyPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMapModeList` |  | `MapModeList` |  |
| `GetPopList` |  | `PopList` |  |
| `GetSelectedAcceptanceStatus` |  | `AcceptanceStatus` |  |
| `GetSelectedAcceptanceStatusSegment` |  | `AcceptanceStatusSegment` |  |
| `AccessRepresentativePops` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetPopList` |  |  |  |
| `GetSelectedAcceptanceStatus` |  |  |  |
| `GetSelectedAcceptanceStatusSegment` |  |  |  |
| `IsAcceptanceStatusSelected` | `Arg0` | `bool` |  |
| `SelectAcceptanceStatus` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## SplineAdjustmentTool

Map Editor - Spline Network Adjustment Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddAnchorsToAdjacentSelectedPairs` |  | `void` |  |
| `CanAddAnchorsInSelection` |  | `bool` |  |
| `CanDeleteSelection` |  | `bool` |  |
| `DeleteSelected` |  | `void` |  |
| `HasMapContent` |  | `bool` |  |
| `HasMergeNotes` |  | `bool` |  |
| `IsAnchorCreationSelected` |  | `bool` |  |
| `IsAnchorSelectionSelected` |  | `bool` |  |
| `IsMapContentSelectionSelected` |  | `bool` |  |
| `IsNavMeshVisible` |  | `bool` |  |
| `IsShowingAllMergeNotes` |  | `bool` |  |
| `IsShowingConflictsMergeNotes` |  | `bool` |  |
| `SelectAnchorCreation` |  | `void` |  |
| `SelectAnchorSelection` |  | `void` |  |
| `SelectMapContentSelection` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleNavMeshVisibility` |  | `void` |  |
| `ToggleShowingAllMergeNotes` |  | `void` |  |
| `ToggleShowingConflictsMergeNotes` |  | `void` |  |

## SplineAdjustmentToolMode

Map Editor - Spline Network Adjustment Tool - Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## SplineRiverInteractionMode

Map Editor - Spline Ruler Interaction Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## SplineRiverTool

Map Editor - Spline River Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetWidth` |  | `float` |  |
| `ModifyWidth` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetWidth` |  | `void` |  |
| `SetWidthStr` |  | `void` |  |

## SplineStripTool

Map Editor - Spline Strip Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanDeleteSelection` |  | `bool` |  |
| `CheckAllStripsForErrors` |  | `void` |  |
| `DeleteSelected` |  | `void` |  |
| `FocusCameraOnSelection` |  | `void` |  |
| `FocusCameraOnStripError` |  | `void` |  |
| `GetStripErrorCount` |  | `int32` |  |
| `HasMapContent` |  | `bool` |  |
| `HasMergeNotes` |  | `bool` |  |
| `HasSelectedStrips` |  | `bool` |  |
| `IsAnchorCreationSelected` |  | `bool` |  |
| `IsAnchorSelectionSelected` |  | `bool` |  |
| `IsMapContentSelectionSelected` |  | `bool` |  |
| `IsNavMeshVisible` |  | `bool` |  |
| `IsShowingAllMergeNotes` |  | `bool` |  |
| `IsShowingConflictsMergeNotes` |  | `bool` |  |
| `IsStripCreationSelected` |  | `bool` |  |
| `IsStripSelectionSelected` |  | `bool` |  |
| `SelectAnchorCreation` |  | `void` |  |
| `SelectAnchorSelection` |  | `void` |  |
| `SelectMapContentSelection` |  | `void` |  |
| `SelectStripCreation` |  | `void` |  |
| `SelectStripSelection` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleNavMeshVisibility` |  | `void` |  |
| `ToggleShowingAllMergeNotes` |  | `void` |  |
| `ToggleShowingConflictsMergeNotes` |  | `void` |  |

## SplineStripToolMode

Map Editor - Spline Strip Tool - Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## SplineToolsMapContentPanel

Map Editor - Spline Strip Tool - Map Content Panel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AutoPlaceHubAnchors` |  | `void` |  |
| `HasMapContent` |  | `bool` |  |
| `Self` |  |  |  |

## SplineTypeCreateSelectionDropdown

Map Editor - Spline Strip Tool - Create Dropdown

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSplineTypeSelected` | `Arg0` | `bool` |  |
| `SelectSplineType` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SplineTypes` |  |  |  |
| `Toggle` |  | `void` |  |

## SplineTypeItem

Map Editor - Spline Strip Tool - Spline Type

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetId` |  | `uint8` |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## SplineTypeSwitchSelectionDropdown

Map Editor - Spline Strip Tool - Type switch dropdown

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ChangeSelectedStripsType` | `Arg0` | `void` |  |
| `IsSplineTypeSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SplineTypes` |  |  |  |
| `Toggle` |  | `void` |  |

## SplineVisibilityDropdown

Map Editor - Spline Visibility Dropdown

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsVisibilityModeAll` |  | `bool` |  |
| `IsVisibilityModeFirst` |  | `bool` |  |
| `IsVisibilityModeLast` |  | `bool` |  |
| `Self` |  |  |  |
| `SetVisibilityModeToAll` |  | `void` |  |
| `SetVisibilityModeToFirst` |  | `void` |  |
| `SetVisibilityModeToLast` |  | `void` |  |
| `Toggle` |  | `void` |  |

## StagedFormation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMilitaryFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `GetCommandLimit` |  | `CString` |  |
| `GetCommandLimitRaw` |  | `int32` |  |
| `GetFormationResultBreakdown` |  | `CString` |  |
| `GetHQs` |  |  |  |
| `GetIDString` |  | `CString` |  |
| `GetIDStringForUnitType` | `Arg0` | `CString` |  |
| `GetMilitaryFormation` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumCombatUnits` |  | `int32` |  |
| `GetNumCombatUnitsIfTransferred` |  | `int32` |  |
| `GetNumConscriptsFromHQ` | `Arg0` | `int32` |  |
| `GetNumConscriptsFromState` | `Arg0` | `int32` |  |
| `GetNumRegularsFromHQ` | `Arg0` | `int32` |  |
| `GetNumRegularsFromState` | `Arg0` | `int32` |  |
| `GetNumShips` |  | `int32` |  |
| `GetNumShipsIfTransferred` |  | `int32` |  |
| `GetResultingNumbersDesc` |  | `CString` |  |
| `GetShipTypes` |  |  |  |
| `GetStates` |  |  |  |
| `GetUnitTypes` |  |  |  |
| `HasValidFormation` |  | `bool` |  |
| `IsAllSelectedFromHQ` | `Arg0` | `bool` |  |
| `IsAllSelectedFromState` | `Arg0` | `bool` |  |
| `IsFormationSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `ToggleSelectionOnAllFromHQ` | `Arg0` | `void` |  |
| `ToggleSelectionOnAllFromState` | `Arg0` | `void` |  |

## StagedShipsWithType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetShipType` |  | `ShipType` |  |
| `AccessSelf` |  |  |  |
| `GetNumShips` |  | `int32` |  |
| `GetNumShipsSelected` |  | `int32` |  |
| `GetShipType` |  |  |  |
| `GetShips` |  |  |  |
| `HasMoved` |  | `bool` |  |
| `IsShipSelected` | `Arg0` | `bool` |  |
| `OnEditboxValueChanged` |  | `void` |  |
| `OnSliderValueChanged` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleShipSelected` | `Arg0` | `void` |  |

## StagedUnitsWithType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStateFilter` |  | `State` |  |
| `GetUnitType` |  | `CombatUnitType` |  |
| `AccessSelf` |  |  |  |
| `CanMoveConscriptsToStaged` |  | `bool` |  |
| `CanMoveRegularsToStaged` |  | `bool` |  |
| `ClearStateFilter` |  | `void` |  |
| `GetInvalidConscriptTransferDesc` |  | `CString` |  |
| `GetInvalidRegularTransferDesc` |  | `CString` |  |
| `GetNumCombatUnits` |  | `int32` |  |
| `GetNumConscripts` |  | `int32` |  |
| `GetNumConscriptsInState` | `Arg0` | `int32` |  |
| `GetNumFilteredConscripts` |  | `int32` |  |
| `GetNumFilteredRegulars` |  | `int32` |  |
| `GetNumRegulars` |  | `int32` |  |
| `GetNumRegularsInState` | `Arg0` | `int32` |  |
| `GetNumSelectedConscripts` |  | `int32` |  |
| `GetNumSelectedRegulars` |  | `int32` |  |
| `GetStagedCombatUnitStates` |  |  |  |
| `GetStagedCombatUnits` |  |  |  |
| `GetStagedCombatUnitsInState` | `Arg0` |  |  |
| `GetStateFilter` |  |  |  |
| `GetUnitType` |  |  |  |
| `HasMoved` |  | `bool` |  |
| `HasStateFilter` |  | `bool` |  |
| `IsUnitSelected` | `Arg0` | `bool` |  |
| `OnConscriptsEditboxValueChanged` |  | `void` |  |
| `OnConscriptsSliderValueChanged` |  | `void` |  |
| `OnRegularsEditboxValueChanged` |  | `void` |  |
| `OnRegularsSliderValueChanged` |  | `void` |  |
| `Self` |  |  |  |
| `SetStateFilter` | `Arg0` | `void` |  |
| `ToggleUnitSelected` | `Arg0` | `void` |  |

## StarvationType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsMild` |  | `bool` |  |
| `IsSevere` |  | `bool` |  |
| `Self` |  |  |  |

## State

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` | `Arg0` | `Building` |  |
| `AccessMarket` |  | `Market` |  |
| `AccessModifier` |  | `Modifier` |  |
| `AccessOwner` |  | `Country` |  |
| `AccessPopsList` |  | `PopList` |  |
| `AccessStateRegion` |  | `StateRegion` |  |
| `AccessSubsistenceBuilding` |  | `Building` |  |
| `GetBuilding` | `Arg0` | `Building` |  |
| `GetColonyCompany` |  | `Company` |  |
| `GetController` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `GetEnemyWithHighestOccupation` |  | `Country` |  |
| `GetFoodSecurity` |  | `FoodSecurity` |  |
| `GetMarket` |  | `Market` |  |
| `GetMassMigrationCulture` |  | `Culture` |  |
| `GetMassMigrationOriginCountry` |  | `Country` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetNextColonyProvince` |  | `Province` |  |
| `GetOccupant` |  | `Country` |  |
| `GetOwner` |  | `Country` |  |
| `GetStateRegion` |  | `StateRegion` |  |
| `GetSubsistenceBuilding` |  | `Building` |  |
| `GetTheater` | `Arg0` | `Theater` |  |
| `MakeScope` |  | `Scope` |  |
| `AbandonColony` |  | `Command` |  |
| `AccessAllBuiltRuralBuildings` |  |  |  |
| `AccessBuilding` | `Arg0` |  |  |
| `AccessBuildings` |  |  |  |
| `AccessCappedRuralBuildings` |  |  |  |
| `AccessCoastalBuildings` |  |  |  |
| `AccessDecrees` |  |  |  |
| `AccessDevelopmentBuildings` |  |  |  |
| `AccessMarket` |  |  |  |
| `AccessMilitaryFormationsSuppliedFromThisState` | `Arg0` |  |  |
| `AccessModifier` |  |  |  |
| `AccessOwner` |  |  |  |
| `AccessPopCultures` |  |  |  |
| `AccessPopInterestGroups` |  |  |  |
| `AccessPopReligions` |  |  |  |
| `AccessPopTypes` |  |  |  |
| `AccessPopsList` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessShippingLanesFromThisState` | `Arg0` |  |  |
| `AccessShippingLanesOnlyGoodsTransferFromThisState` | `Arg0` |  |  |
| `AccessShippingLanesOnlyPortConnectionsFromThisState` | `Arg0` |  |  |
| `AccessSubsistenceBuilding` |  |  |  |
| `AccessUncappedRuralBuildings` |  |  |  |
| `AccessUrbanBuildings` |  |  |  |
| `CalcPopInstitutionBureaucracyCost` |  | `CFixedPoint` |  |
| `CalcSupplyToDemandRatio` | `Arg0` | `CFixedPoint` |  |
| `CalcTaxCapacity` |  | `CFixedPoint` |  |
| `CalcTaxCapacityBalance` |  | `CFixedPoint` |  |
| `CalcTaxCapacityUsage` |  | `CFixedPoint` |  |
| `CalcTurmoil` |  | `CFixedPoint` |  |
| `GetAdditionalSOLFactorsDescAll` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescMiddle` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescPoor` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescRich` |  | `CString` |  |
| `GetAnnualPopNetMigration` |  | `int64` |  |
| `GetArableLandCapacity` |  | `int32` |  |
| `GetAtRiskCoastalBuildingsList` |  | `CString` |  |
| `GetAverageAnnualWage` |  | `CFixedPoint` |  |
| `GetAverageAnnualWageDesc` |  | `CString` |  |
| `GetAverageStandardOfLivingAll` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingMiddle` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingPoor` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingRich` |  | `CFixedPoint` |  |
| `GetBaseBureaucracyCostRaw` |  | `CFixedPoint` |  |
| `GetBasePopBureaucracyCostRaw` |  | `CFixedPoint` |  |
| `GetBestTexture` |  |  |  |
| `GetBestTextureEffect` |  | `CString` |  |
| `GetBlockadeEffectsDesc` |  | `CString` |  |
| `GetBlockadeLevel` |  | `CFixedPoint` |  |
| `GetBuilding` | `Arg0` |  |  |
| `GetBuildingsWithGovernmentExpenses` |  |  |  |
| `GetBuildingsWithTaxationRevenue` |  |  |  |
| `GetBureaucracyCost` |  | `CFixedPoint` |  |
| `GetBureaucracyCostDesc` |  | `CString` |  |
| `GetCapitalEffectsDesc` |  | `CString` |  |
| `GetCityHubName` |  | `CString` |  |
| `GetClaimsDesc` |  | `CString` |  |
| `GetColonizers` | `Arg0` | `CString` |  |
| `GetColonyCompany` |  |  |  |
| `GetColonyGrowthDateDesc` |  | `CString` |  |
| `GetColonyGrowthModifierDesc` |  | `CString` |  |
| `GetColonyProgress` |  | `CFixedPoint` |  |
| `GetColonyProgressAsDays` |  | `int32` |  |
| `GetColonyProgressAsFloat` |  | `float` |  |
| `GetColonyProvinceProgressDesc` |  | `CString` |  |
| `GetColonyTransferName` |  | `CString` |  |
| `GetColor` |  | `CVector4f` |  |
| `GetConscriptionLimit` |  | `int32` |  |
| `GetConscriptionLimitDesc` |  | `CString` |  |
| `GetConstructionEfficiency` |  | `CFixedPoint` |  |
| `GetConstructionEfficiencyForBuildingType` | `Arg0` | `CFixedPoint` |  |
| `GetConstructionEfficiencyForBuildingTypeTooltip` | `Arg0` | `CString` |  |
| `GetConstructionEfficiencyTooltip` |  | `CString` |  |
| `GetController` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCulturalCommunities` |  |  |  |
| `GetCurrentBlockadeStrength` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDailyColonyProgress` |  | `CFixedPoint` |  |
| `GetDailyDevastationIncreaseFromBombardment` |  | `CFixedPoint` |  |
| `GetDailyDevastationIncreaseFromBombardmentBreakdown` |  | `CString` |  |
| `GetDevastationDailyChange` |  | `CFixedPoint` |  |
| `GetDevastationDailyChangeBreakdown` |  | `CString` |  |
| `GetDevastationEffects` |  | `CString` |  |
| `GetDevastationLevel` |  | `CFixedPoint` |  |
| `GetEnemyWithHighestOccupation` |  |  |  |
| `GetExpectedSOLFactorsDescAll` |  | `CString` |  |
| `GetExpectedSOLFactorsDescMiddle` |  | `CString` |  |
| `GetExpectedSOLFactorsDescPoor` |  | `CString` |  |
| `GetExpectedSOLFactorsDescRich` |  | `CString` |  |
| `GetExpectedStandardOfLivingAll` |  | `CFixedPoint` |  |
| `GetExpectedStandardOfLivingMiddle` |  | `CFixedPoint` |  |
| `GetExpectedStandardOfLivingPoor` |  | `CFixedPoint` |  |
| `GetExpectedStandardOfLivingRich` |  | `CFixedPoint` |  |
| `GetExportRevenue` | `Arg0` | `CFixedPoint` |  |
| `GetExportedAmount` | `Arg0` | `CFixedPoint` |  |
| `GetExports` |  |  |  |
| `GetFamineDesc` |  | `CString` |  |
| `GetFarmHubName` |  | `CString` |  |
| `GetForestryHubName` |  | `CString` |  |
| `GetFormattedStandardOfLivingAll` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelAll` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelMiddle` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelPoor` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelRich` |  | `CString` |  |
| `GetFormattedStandardOfLivingMiddle` |  | `CString` |  |
| `GetFormattedStandardOfLivingPoor` |  | `CString` |  |
| `GetFormattedStandardOfLivingRich` |  | `CString` |  |
| `GetFreeArableLandAfterInactiveQueuedEntry` |  | `CString` |  |
| `GetGDPContribution` |  | `CFixedPoint` |  |
| `GetGDPContributionPercentage` |  | `CFixedPoint` |  |
| `GetGDPGoodsContribution` | `Arg0` | `CFixedPoint` |  |
| `GetGDPGoodsContributionBreakdown` |  | `CString` |  |
| `GetGDPGoodsContributionPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetGdpRatioOwnedBy` | `Arg0` | `CFixedPoint` |  |
| `GetGdpRatioOwnedByDesc` | `Arg0` | `CString` |  |
| `GetGoodsSortedByGDP` |  |  |  |
| `GetGovernmentExpenses` |  | `CFixedPoint` |  |
| `GetHarvestConditions` |  |  |  |
| `GetHomelandsDesc` |  | `CString` |  |
| `GetID` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetImportRevenue` | `Arg0` | `CFixedPoint` |  |
| `GetImportedAmount` | `Arg0` | `CFixedPoint` |  |
| `GetImports` |  |  |  |
| `GetIncorporationPartialEffectsDesc` |  | `CString` |  |
| `GetIncorporationProgress` |  | `CFixedPoint` |  |
| `GetIncorporationTimeDesc` |  | `CString` |  |
| `GetIncorporationTimeLeft` |  | `CString` |  |
| `GetInfrastructure` |  | `CFixedPoint` |  |
| `GetInfrastructureBalance` |  | `CFixedPoint` |  |
| `GetInfrastructureDesc` |  | `CString` |  |
| `GetInfrastructureUsage` |  | `CFixedPoint` |  |
| `GetInfrastructureUsageDesc` |  | `CString` |  |
| `GetInsufficientQualificationsForAvailablePositionsDesc` |  | `CString` |  |
| `GetInvasions` |  |  |  |
| `GetJobseekersDesc` |  | `CString` |  |
| `GetLiteracy` |  | `CFixedPoint` |  |
| `GetLocality` |  | `CFixedPoint` |  |
| `GetLocalityDesc` |  | `CString` |  |
| `GetMarket` |  |  |  |
| `GetMarketAccess` |  | `CFixedPoint` |  |
| `GetMarketAccessDesc` |  | `CString` |  |
| `GetMarketAccessStatus` |  | `CString` |  |
| `GetMarketCapitalEffectsDesc` |  | `CString` |  |
| `GetMassMigrationCulture` |  |  |  |
| `GetMassMigrationEndDate` |  | `CString` |  |
| `GetMassMigrationOriginCountry` |  |  |  |
| `GetMaxBattalions` |  | `int32` |  |
| `GetMaxImbalance` |  | `CFixedPoint` |  |
| `GetMaxImbalanceScaledByBasePrice` |  | `CFixedPoint` |  |
| `GetMaxPotentialFor` | `Arg0` | `int32` |  |
| `GetMigrationAndSlaveTradeDetailsDesc` |  | `CString` |  |
| `GetMigrationDesc` |  | `CString` |  |
| `GetMigrationDetailsDesc` |  | `CString` |  |
| `GetMigrationLabel` |  | `CString` |  |
| `GetMigrationPull` |  | `CFixedPoint` |  |
| `GetMigrationPullDesc` |  | `CString` |  |
| `GetMineHubName` |  | `CString` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameWithCountryFlag` |  | `CString` |  |
| `GetNextColonyProvince` |  |  |  |
| `GetNonPotentialDiploPlays` |  |  |  |
| `GetNumArableLandReservedForSubsistence` |  | `int32` |  |
| `GetNumBaseFreeArableLand` |  | `int32` |  |
| `GetNumBuildingsAffectedByGoodsShortage` |  | `int32` |  |
| `GetNumColonizers` |  | `int32` |  |
| `GetNumConstructableUrbanBuildings` |  | `int32` |  |
| `GetNumConsumed` | `Arg0` | `CFixedPoint` |  |
| `GetNumFreeArableLand` |  | `int32` |  |
| `GetNumInactiveQueuedArableLandEntry` |  | `CString` |  |
| `GetNumJobseekers` |  | `int64` |  |
| `GetNumLoyalists` |  | `int64` |  |
| `GetNumObstinanceSupporters` |  | `int64` |  |
| `GetNumOfObstinatePopsFromMovement` | `Arg0` | `int64` |  |
| `GetNumProduced` | `Arg0` | `CFixedPoint` |  |
| `GetNumProvinces` |  | `int32` |  |
| `GetNumRadicals` |  | `int64` |  |
| `GetNumSubsistenceWorkingAdults` |  | `int64` |  |
| `GetNumUnemployedWorkingAdults` |  | `int64` |  |
| `GetNumUsedArableLand` |  | `int32` |  |
| `GetNumUsedArableLandFullyBuilt` |  | `int32` |  |
| `GetNumUsedArableLandFullyBuiltEntry` |  | `CString` |  |
| `GetNumUsedArableLandUnderConstruction` |  | `int32` |  |
| `GetNumUsedArableLandUnderConstructionEntry` |  | `CString` |  |
| `GetNumberOfPopsMiddle` |  | `int64` |  |
| `GetNumberOfPopsPoor` |  | `int64` |  |
| `GetNumberOfPopsRich` |  | `int64` |  |
| `GetObstinance` |  | `CFixedPoint` |  |
| `GetObstinanceDesc` |  | `CString` |  |
| `GetObstinanceEffectScale` |  | `CFixedPoint` |  |
| `GetObstinanceEffectsDesc` |  | `CString` |  |
| `GetObstinanceFromMovement` | `Arg0` | `CFixedPoint` |  |
| `GetOccupant` |  |  |  |
| `GetOccupantsTooltip` |  | `CString` |  |
| `GetOccupationPiechartData` |  |  |  |
| `GetOwner` |  |  |  |
| `GetPlanInvasionDesc` |  | `CString` |  |
| `GetPolStrForCulture` | `Arg0` | `int64` |  |
| `GetPolStrForReligion` | `Arg0` | `int64` |  |
| `GetPollutionGeneration` |  | `CFixedPoint` |  |
| `GetPollutionGenerationDesc` |  | `CString` |  |
| `GetPollutionHealthEffectsReduction` |  | `CFixedPoint` |  |
| `GetPollutionHealthEffectsReductionDesc` |  | `CString` |  |
| `GetPopBirthrate` |  | `CFixedPoint` |  |
| `GetPopCultureDesc` |  | `CString` |  |
| `GetPopCultureDescByIndex` | `Arg0` | `CString` |  |
| `GetPopGrowthDesc` |  | `CString` |  |
| `GetPopMortality` |  | `CFixedPoint` |  |
| `GetPopNetGrowth` |  | `int64` |  |
| `GetPopReligionDesc` |  | `CString` |  |
| `GetPopReligionDescByIndex` | `Arg0` | `CString` |  |
| `GetPopTotalChange` |  | `int64` |  |
| `GetPops` |  |  |  |
| `GetPopulationForCulture` | `Arg0` | `int64` |  |
| `GetPopulationForReligion` | `Arg0` | `int64` |  |
| `GetPopulationRatioBelowExpectedStandardOfLiving` |  | `CFixedPoint` |  |
| `GetPopulationSize` |  | `int64` |  |
| `GetPortHubName` |  | `CString` |  |
| `GetPotentialDecrees` |  |  |  |
| `GetPotentialDiploPlays` |  |  |  |
| `GetPotentialLabor` |  | `int64` |  |
| `GetPotentialPopTypeQualificationsDesc` |  | `CString` |  |
| `GetPotentialProductionForCountry` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetPotentialProductionForCountryDesc` | `Arg0, Arg1` | `CString` |  |
| `GetPotentialQualifications` | `Arg0` | `int64` |  |
| `GetPotentialQualificationsBreakdown` | `Arg0` | `CString` |  |
| `GetPotentialQualificationsDesc` |  | `CString` |  |
| `GetPotentialUrbanBuildings` |  |  |  |
| `GetProductionInfo` |  |  |  |
| `GetRequiredBlockadeStrength` |  | `CFixedPoint` |  |
| `GetSamplePops` |  |  |  |
| `GetSlaveExportMarkersDesc` |  | `CString` |  |
| `GetSlaveImportMarkerDesc` |  | `CString` |  |
| `GetSlaveTradeDetailsDesc` |  | `CString` |  |
| `GetStateRegion` |  |  |  |
| `GetStationSelectedFormationsCommand` |  | `Command` |  |
| `GetSubsistenceBuilding` |  |  |  |
| `GetTaxCapacityDesc` |  | `CString` |  |
| `GetTaxCapacityEffectsDesc` |  | `CString` |  |
| `GetTaxCapacityUsageDesc` |  | `CString` |  |
| `GetTaxationRevenue` |  | `CFixedPoint` |  |
| `GetTheater` | `Arg0` |  |  |
| `GetTimedModifiers` |  |  |  |
| `GetTimedModifiersBreakdown` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalConsumption` |  | `CFixedPoint` |  |
| `GetTotalConvoysFromShippingLanesViaState` | `Arg0` | `int32` |  |
| `GetTotalExportRevenue` |  | `CFixedPoint` |  |
| `GetTotalExportedAmount` |  | `CFixedPoint` |  |
| `GetTotalImportRevenue` |  | `CFixedPoint` |  |
| `GetTotalImportedAmount` |  | `CFixedPoint` |  |
| `GetTotalLabor` |  | `int64` |  |
| `GetTotalMerchantMarineDemandViaState` | `Arg0` | `CFixedPoint` |  |
| `GetTotalPolStr` |  | `int64` |  |
| `GetTotalPortConnectionsViaState` | `Arg0` | `int32` |  |
| `GetTotalProduction` |  | `CFixedPoint` |  |
| `GetTradeCapacity` |  | `int32` |  |
| `GetTradeCapacityBalance` |  | `int32` |  |
| `GetTradeCapacityDesc` |  | `CString` |  |
| `GetTradeCapacityUsage` |  | `int32` |  |
| `GetTradeCapacityUsageDesc` |  | `CString` |  |
| `GetTradePotential` |  | `CFixedPoint` |  |
| `GetTradePotentialDesc` |  | `CString` |  |
| `GetTurmoilEffects` |  | `CString` |  |
| `GetUrbanization` |  | `int32` |  |
| `GetUrbanizationBuildingsMaxLevelDesc` |  | `CString` |  |
| `GetUrbanizationDesc` |  | `CString` |  |
| `GetUrbanizationNeededPerLevelFormatted` |  | `CString` |  |
| `GetUrbanizationNeededPerLevelRaw` |  | `int32` |  |
| `GetWeeklyEmigration` |  | `int64` |  |
| `GetWeeklyImmigration` |  | `int64` |  |
| `GetWeeklyPopNetMigration` |  | `int64` |  |
| `GetWeeklySlaveExport` |  | `int64` |  |
| `GetWeeklySlaveImport` |  | `int64` |  |
| `GetWorldMarketAccess` |  | `CFixedPoint` |  |
| `GetWorldMarketAccessDesc` |  | `CString` |  |
| `GetWorldMarketAccessFormatted` |  | `CString` |  |
| `GetYearlyGDP` |  | `CFixedPoint` |  |
| `GetYearsToIncorporate` |  | `CFixedPoint` |  |
| `HasAnyGoodsShortage` |  | `bool` |  |
| `HasAtRiskCoastalBuildings` |  | `bool` |  |
| `HasBuilding` | `Arg0` | `bool` |  |
| `HasBuildingGoodsShortage` | `Arg0` | `bool` |  |
| `HasClaims` |  | `bool` |  |
| `HasConstructionQueued` |  | `bool` |  |
| `HasDevastation` |  | `bool` |  |
| `HasDiscoverableResources` |  | `bool` |  |
| `HasFamine` |  | `bool` |  |
| `HasGoodsShortage` | `Arg0` | `bool` |  |
| `HasHomelands` |  | `bool` |  |
| `HasInsufficientQualificationsForAvailablePositions` |  | `bool` |  |
| `HasOccupation` |  | `bool` |  |
| `HasPopGoodsShortage` | `Arg0` | `bool` |  |
| `HasSlaveExportMarkers` |  | `bool` |  |
| `HasTimedModifiers` |  | `bool` |  |
| `HasTurmoilEffects` |  | `bool` |  |
| `IncorporateState` |  | `Command` |  |
| `IsBeingBombarded` |  | `bool` |  |
| `IsBeingColonized` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsCapitalState` |  | `bool` |  |
| `IsCoastal` |  | `bool` |  |
| `IsColonizationPaused` |  | `bool` |  |
| `IsColonyProgressBlockedByInactiveInterest` |  | `bool` |  |
| `IsCompanyColony` |  | `bool` |  |
| `IsContested` |  | `bool` |  |
| `IsEligibleForMassMigration` |  | `bool` |  |
| `IsFullyOccupied` |  | `bool` |  |
| `IsGrowingColony` |  | `bool` |  |
| `IsImportingSlaves` |  | `bool` |  |
| `IsIncorporated` |  | `bool` |  |
| `IsIncorporating` |  | `bool` |  |
| `IsIsolatedFromMarket` |  | `bool` |  |
| `IsMarketCapital` |  | `bool` |  |
| `IsMassMigrationTarget` |  | `bool` |  |
| `IsOwner` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsSlaveState` |  | `bool` |  |
| `IsSplitState` |  | `bool` |  |
| `IsStrategicObjective` | `Arg0` | `bool` | Returns 'true' if this State is a Strategic Objective of 'pCountry' |
| `IsTreatyPort` |  | `bool` |  |
| `IsUnincorporated` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsValidInvasionTarget` |  | `bool` |  |
| `IsWorldMarketHub` |  | `bool` |  |
| `IsZoomingToCapital` |  | `bool` |  |
| `PanCamera` |  | `void` |  |
| `PredictBureaucracyCost` |  | `CFixedPoint` |  |
| `RequiresNavalTransportForSelectedFormations` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowTransportPlannerForSelectedFormation` |  | `void` |  |
| `SortBuildings` | `Arg0` | `void` |  |
| `SortBuildingsWithOrder` | `Arg0, Arg1` | `void` |  |
| `SortExports` | `Arg0` | `void` |  |
| `SortImports` | `Arg0` | `void` |  |
| `TogglePauseColonization` |  | `Command` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `UnincorporateState` |  | `Command` |  |
| `ZoomExtraCloseToCapital` |  | `void` |  |
| `ZoomToCapital` |  | `void` |  |

## StateGoods

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `GetState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBreakdownOfBuildingsAffectedByShortage` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetGoods` |  |  |  |
| `GetIDString` |  | `CString` |  |
| `GetNumBuildingsAffectedByShortage` |  | `int32` |  |
| `GetState` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## StateInfraMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetState` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `IsConnectedMarker` |  | `bool` |  |
| `Self` |  |  |  |

## StateMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetGoods` |  |  |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## StateNameChangePopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `Confirm` |  | `Command` |  |
| `GetState` |  |  |  |
| `OnEditCityName` |  | `void` |  |
| `OnEditFarmName` |  | `void` |  |
| `OnEditMineName` |  | `void` |  |
| `OnEditName` |  | `void` |  |
| `OnEditPortName` |  | `void` |  |
| `OnEditWoodName` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldHaveCityHub` |  | `bool` |  |
| `ShouldHaveFarmHub` |  | `bool` |  |
| `ShouldHaveMineHub` |  | `bool` |  |
| `ShouldHavePortHub` |  | `bool` |  |
| `ShouldHaveWoodHub` |  | `bool` |  |

## StatePopulationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessState` |  | `State` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## StateRegion

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessLargestStateOwner` |  | `Country` |  |
| `AccessStrategicRegion` |  | `StrategicRegion` |  |
| `GetLargestStateInRegion` |  | `State` |  |
| `GetLargestStateOwner` |  | `Country` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessLargestStateOwner` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessStrategicRegion` |  |  |  |
| `AccessTraits` |  |  |  |
| `Colonize` |  | `Command` |  |
| `GetAdjacentLandStateRegionsDesc` |  | `CString` |  |
| `GetAdjacentSeaStateRegionsDesc` |  | `CString` |  |
| `GetCityHubName` |  | `CString` |  |
| `GetColonizeTooltip` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFarmHubName` |  | `CString` |  |
| `GetForestryHubName` |  | `CString` |  |
| `GetID` |  | `int32` |  |
| `GetLargestStateInRegion` |  |  |  |
| `GetLargestStateOwner` |  |  |  |
| `GetMineHubName` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNavalExitStateRegionDesc` |  | `CString` |  |
| `GetPollutionEffects` |  | `CString` |  |
| `GetPollutionImpact` |  | `CFixedPoint` |  |
| `GetPollutionImpactDailyChange` |  | `CFixedPoint` |  |
| `GetPollutionImpactTargetLevel` |  | `CFixedPoint` |  |
| `GetPollutionLevel` |  | `CFixedPoint` |  |
| `GetPortHubName` |  | `CString` |  |
| `GetSeaInfrastructure` | `Arg0` | `CFixedPoint` |  |
| `GetSeaInfrastructureDesc` | `Arg0` | `CString` |  |
| `GetStatesDesc` |  | `CString` |  |
| `GetStrategicRegion` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsSplitState` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `PanCamera` |  | `void` |  |
| `Self` |  |  |  |

## StatesPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` | `Arg0` | `Building` |  |
| `AccessState` |  | `State` |  |
| `AccessSubsistenceBuilding` |  | `Building` |  |
| `GetCharacterFilter` |  | `CharacterFilter` |  |
| `GetState` |  | `State` |  |
| `AccessBuilding` | `Arg0` |  |  |
| `AccessLocalGoods` |  |  |  |
| `AccessNonLocalGoods` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `AccessSubsistenceBuilding` |  |  |  |
| `CalcBuildUrbanBuildingsButtonPosition` |  | `CVector2f` |  |
| `GetNumAgricultureLevels` |  | `int32` |  |
| `GetNumAgricultureLevelsDesc` |  | `CString` |  |
| `GetNumAgricultureLevelsInQueue` |  | `int32` |  |
| `GetNumDevelopmentLevels` |  | `int32` |  |
| `GetNumDevelopmentLevelsDesc` |  | `CString` |  |
| `GetNumDevelopmentLevelsInQueue` |  | `int32` |  |
| `GetNumResourceLevels` |  | `int32` |  |
| `GetNumResourceLevelsDesc` |  | `CString` |  |
| `GetNumResourceLevelsInQueue` |  | `int32` |  |
| `GetNumUrbanLevels` |  | `int32` |  |
| `GetNumUrbanLevelsDesc` |  | `CString` |  |
| `GetNumUrbanLevelsInQueue` |  | `int32` |  |
| `GetState` |  |  |  |
| `IsBuildUrbanBuildingsMenuOpen` |  | `bool` |  |
| `IsExpanded` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |
| `ToggleBuildUrbanBuildingsMenu` | `Arg0` | `void` |  |
| `ToggleSection` | `Arg0` | `void` |  |

## StateTrait

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetModifiersDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUnlocks` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `Self` |  |  |  |

## StatusWidget

Status Widget

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ConnectAccount` |  | `void` |  |
| `DisconnectAccount` |  | `void` |  |
| `Hide` |  | `void` |  |
| `IsAccountConnected` |  | `bool` |  |
| `IsBusy` |  | `bool` |  |
| `Logout` |  | `void` |  |
| `Self` |  |  |  |
| `Show` |  | `void` |  |
| `SupportsConnectAccount` |  | `bool` |  |
| `ToggleCreateAccountWindow` |  | `void` |  |
| `ToggleCreateProfileWindow` |  | `void` |  |
| `ToggleLoginWindow` |  | `void` |  |

## Strait

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDefinition` |  | `StraitDefinition` |  |
| `GetFirstController` |  | `Country` |  |
| `GetFirstSeaNode` |  | `Province` |  |
| `GetFirstState` |  | `State` |  |
| `GetOtherController` | `Arg0` | `Country` |  |
| `GetOtherState` | `Arg0` | `State` |  |
| `GetSecondController` |  | `Country` |  |
| `GetSecondSeaNode` |  | `Province` |  |
| `GetSecondState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `ControllerHasAccessPermissionsAll` | `Arg0` | `bool` |  |
| `ControllerHasAccessPermissionsNoEnemies` | `Arg0` | `bool` |  |
| `ControllerHasAccessPermissionsOnlyAllies` | `Arg0` | `bool` |  |
| `ControllerHasAccessPermissionsOnlyController` | `Arg0` | `bool` |  |
| `ControllerHasAccessStatusClosed` | `Arg0` | `bool` |  |
| `ControllerHasAccessStatusNoMilitary` | `Arg0` | `bool` |  |
| `ControllerHasAccessStatusOpen` | `Arg0` | `bool` |  |
| `ControllerHasTollRateHighTolls` | `Arg0` | `bool` |  |
| `ControllerHasTollRateLowTolls` | `Arg0` | `bool` |  |
| `ControllerHasTollRateMediumTolls` | `Arg0` | `bool` |  |
| `ControllerHasTollRateNoTolls` | `Arg0` | `bool` |  |
| `GetAccessClosedIcon` |  |  |  |
| `GetAccessNoMilitaryIcon` |  |  |  |
| `GetAccessOpenIcon` |  |  |  |
| `GetAccessPermissionsDescAll` |  | `CString` |  |
| `GetAccessPermissionsDescNoEnemies` |  | `CString` |  |
| `GetAccessPermissionsDescOnlyAllies` |  | `CString` |  |
| `GetAccessPermissionsDescOnlyController` |  | `CString` |  |
| `GetAccessStatusDescClosed` |  | `CString` |  |
| `GetAccessStatusDescNoMilitary` |  | `CString` |  |
| `GetAccessStatusDescOpen` |  | `CString` |  |
| `GetAccessStatusFor` | `Arg0` | `CString` |  |
| `GetActiveStraitAccessStatus` |  | `CString` |  |
| `GetAllowedAllIcon` |  |  |  |
| `GetAllowedNoEnemiesIcon` |  |  |  |
| `GetAllowedOnlyAlliesIcon` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDefinition` |  |  |  |
| `GetFirstController` |  |  |  |
| `GetFirstSeaNode` |  |  |  |
| `GetFirstState` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetOtherController` | `Arg0` |  |  |
| `GetOtherState` | `Arg0` |  |  |
| `GetSecondController` |  |  |  |
| `GetSecondSeaNode` |  |  |  |
| `GetSecondState` |  |  |  |
| `GetStateAllowedCountriesIcon` | `Arg0` |  |  |
| `GetStateAllowedCountriesStatus` | `Arg0` | `CString` |  |
| `GetStateAllowedCountriesStatusDesc` | `Arg0` | `CString` |  |
| `GetStateAllowedCountriesTextIcon` | `Arg0` | `CString` |  |
| `GetStatePredictedTollProfitHigh` | `Arg0` | `CFixedPoint` |  |
| `GetStatePredictedTollProfitLow` | `Arg0` | `CFixedPoint` |  |
| `GetStatePredictedTollProfitMedium` | `Arg0` | `CFixedPoint` |  |
| `GetStateStraitAccessIcon` | `Arg0` |  |  |
| `GetStateStraitAccessStatus` | `Arg0` | `CString` |  |
| `GetStateStraitAccessStatusDesc` | `Arg0` | `CString` |  |
| `GetStateStraitAccessTextIcon` | `Arg0` | `CString` |  |
| `GetStateTollIcon` | `Arg0` |  |  |
| `GetStateTollProfit` | `Arg0` | `CFixedPoint` |  |
| `GetStateTollProfitChangeHigh` | `Arg0` | `CFixedPoint` |  |
| `GetStateTollProfitChangeLow` | `Arg0` | `CFixedPoint` |  |
| `GetStateTollProfitChangeMedium` | `Arg0` | `CFixedPoint` |  |
| `GetStateTollProfitChangeNoTolls` | `Arg0` | `CFixedPoint` |  |
| `GetStateTollRevenue` | `Arg0` | `CFixedPoint` |  |
| `GetStateTollStatus` | `Arg0` | `CString` |  |
| `GetStateTollTextIcon` | `Arg0` | `CString` |  |
| `GetTollHighIcon` |  |  |  |
| `GetTollLowIcon` |  |  |  |
| `GetTollMediumIcon` |  |  |  |
| `GetTollNoTollsIcon` |  |  |  |
| `GetTollRateDescHighTolls` |  | `CString` |  |
| `GetTollRateDescLowTolls` |  | `CString` |  |
| `GetTollRateDescMediumTolls` |  | `CString` |  |
| `GetTollRateDescNoTolls` |  | `CString` |  |
| `GetTollRateValueForController` | `Arg0` | `CFixedPoint` |  |
| `GetTollsFor` | `Arg0` | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasAccessPermissionsFirstAll` |  | `bool` |  |
| `HasAccessPermissionsFirstNoEnemies` |  | `bool` |  |
| `HasAccessPermissionsFirstOnlyAllies` |  | `bool` |  |
| `HasAccessPermissionsFirstOnlyController` |  | `bool` |  |
| `HasAccessPermissionsSecondAll` |  | `bool` |  |
| `HasAccessPermissionsSecondNoEnemies` |  | `bool` |  |
| `HasAccessPermissionsSecondOnlyAllies` |  | `bool` |  |
| `HasAccessPermissionsSecondOnlyController` |  | `bool` |  |
| `HasAccessStatusFirstClosed` |  | `bool` |  |
| `HasAccessStatusFirstNoMilitary` |  | `bool` |  |
| `HasAccessStatusFirstOpen` |  | `bool` |  |
| `HasAccessStatusSecondClosed` |  | `bool` |  |
| `HasAccessStatusSecondNoMilitary` |  | `bool` |  |
| `HasAccessStatusSecondOpen` |  | `bool` |  |
| `HasEconomicalAccess` | `Arg0` | `bool` |  |
| `HasMilitaryAccess` | `Arg0` | `bool` |  |
| `HasNoAccess` | `Arg0` | `bool` |  |
| `HasNoMilitaryAccess` | `Arg0` | `bool` |  |
| `HasOpenAccess` | `Arg0` | `bool` |  |
| `HasTollRateFirstHighTolls` |  | `bool` |  |
| `HasTollRateFirstLowTolls` |  | `bool` |  |
| `HasTollRateFirstMediumTolls` |  | `bool` |  |
| `HasTollRateFirstNoTolls` |  | `bool` |  |
| `HasTollRateSecondHighTolls` |  | `bool` |  |
| `HasTollRateSecondLowTolls` |  | `bool` |  |
| `HasTollRateSecondMediumTolls` |  | `bool` |  |
| `HasTollRateSecondNoTolls` |  | `bool` |  |
| `IsAllowedCountriesOnlyController` | `Arg0` | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsFirstFortified` |  | `bool` |  |
| `IsFullController` | `Arg0` | `bool` |  |
| `IsOpen` |  | `bool` |  |
| `IsSecondFortified` |  | `bool` |  |
| `IsZoomingToMapMarkerPosition` |  | `bool` |  |
| `Self` |  |  |  |
| `SetControllerAccessPermissionsAll` | `Arg0` | `Command` |  |
| `SetControllerAccessPermissionsNoEnemies` | `Arg0` | `Command` |  |
| `SetControllerAccessPermissionsOnlyAllies` | `Arg0` | `Command` |  |
| `SetControllerAccessPermissionsOnlyController` | `Arg0` | `Command` |  |
| `SetControllerAccessStatusClosed` | `Arg0` | `Command` |  |
| `SetControllerAccessStatusNoMilitary` | `Arg0` | `Command` |  |
| `SetControllerAccessStatusOpen` | `Arg0` | `Command` |  |
| `SetControllerTollRateHighTolls` | `Arg0` | `Command` |  |
| `SetControllerTollRateLowTolls` | `Arg0` | `Command` |  |
| `SetControllerTollRateMediumTolls` | `Arg0` | `Command` |  |
| `SetControllerTollRateNoTolls` | `Arg0` | `Command` |  |
| `SetStateAccessClosed` | `Arg0` | `Command` |  |
| `SetStateAccessNoMilitary` | `Arg0` | `Command` |  |
| `SetStateAccessOpen` | `Arg0` | `Command` |  |
| `SetStateAllowedCountriesNoEnemies` | `Arg0` | `Command` |  |
| `SetStateAllowedCountriesOnlyAllies` | `Arg0` | `Command` |  |
| `SetStateAllowedCountriesOnlyController` | `Arg0` | `Command` |  |
| `StateHasAccessClosed` | `Arg0` | `bool` |  |
| `StateHasAccessNoMilitary` | `Arg0` | `bool` |  |
| `StateHasAccessOpen` | `Arg0` | `bool` |  |
| `StateHasAllowedCountriesNoEnemies` | `Arg0` | `bool` |  |
| `StateHasAllowedCountriesOnlyAllies` | `Arg0` | `bool` |  |
| `StateHasAllowedCountriesOnlyController` | `Arg0` | `bool` |  |
| `StateHasHighTolls` | `Arg0` | `bool` |  |
| `StateHasLowTolls` | `Arg0` | `bool` |  |
| `StateHasMediumTolls` | `Arg0` | `bool` |  |
| `StateHasMostSevereAllowedCountries` | `Arg0` | `bool` |  |
| `StateHasMostSevereStraitAccess` | `Arg0` | `bool` |  |
| `StateHasNoTolls` | `Arg0` | `bool` |  |
| `StateStraitAccessIsOverruled` | `Arg0` | `bool` |  |
| `ZoomToMapMarkerPosition` |  | `void` |  |

## StraitDefinition

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstLandEndpoint` |  | `Province` |  |
| `GetFirstSeaEndpoint` |  | `Province` |  |
| `GetSecondLandEndpoint` |  | `Province` |  |
| `GetSecondSeaEndpoint` |  | `Province` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFirstLandEndpoint` |  |  |  |
| `GetFirstSeaEndpoint` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetSecondLandEndpoint` |  |  |  |
| `GetSecondSeaEndpoint` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  | `CString` |  |
| `MilitaryBlockRequiresFullControl` |  | `bool` |  |
| `Self` |  |  |  |
| `TollsRequireFullControl` |  | `bool` |  |
| `TotalBlockRequiresFullControl` |  | `bool` |  |

## StraitMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStrait` |  | `Strait` |  |
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetStrait` |  |  |  |
| `Self` |  |  |  |

## StraitPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStrait` |  | `Strait` |  |
| `AccessSelf` |  |  |  |
| `GetExporters` | `Arg0` |  |  |
| `GetImporters` | `Arg0` |  |  |
| `GetNumTraded` | `Arg0` | `CFixedPoint` |  |
| `GetStrait` |  |  |  |
| `GetTradeBreakdown` | `Arg0` | `CString` |  |
| `GetTradedGoods` |  |  |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## StrategicRegion

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFirstDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetFirstDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetInterest` | `Arg0` | `Interest` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessFirstDiplomaticPlay` |  |  |  |
| `AccessIncorporatedStates` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessStates` |  |  |  |
| `AccessStatesOwnedBy` | `Arg0` |  |  |
| `AccessUnincorporatedStates` |  |  |  |
| `GetBestTexture` |  |  |  |
| `GetCountriesWithInterest` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFirstDiplomaticPlay` |  |  |  |
| `GetIndex` |  | `uint32` |  |
| `GetInterest` | `Arg0` |  |  |
| `GetInterests` |  |  |  |
| `GetLocalCountriesLocalityPercentage` |  | `CFixedPoint` |  |
| `GetLocalCountriesLocalityPercentageDisplay` |  | `CFixedPoint` |  |
| `GetLocalCountriesWithOwnedStates` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNonLocalCountriesLocalityPercentage` |  | `CFixedPoint` |  |
| `GetNonLocalCountriesLocalityPercentageDisplay` |  | `CFixedPoint` |  |
| `GetNonLocalCountriesWithOwnedStates` |  |  |  |
| `GetNonPlayerCountriesWithInterest` |  |  |  |
| `GetNonPlayerCountriesWithInterestTier` | `Arg0` |  |  |
| `GetPercentStatesOwnedBy` | `Arg0` | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalGDP` |  | `CFixedPoint` |  |
| `HasDiplomaticPlay` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsLand` |  | `bool` |  |
| `IsNonPlayerCountriesSorted` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsZoomingTo` |  | `bool` |  |
| `Self` |  |  |  |
| `SortNonPlayerCountries` | `Arg0` | `void` |  |
| `SortNonPlayerCountriesWithInterestTiers` | `Arg0, Arg1` | `void` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `ZoomToExtraFar` |  | `void` |  |
| `ZoomToFar` |  | `void` |  |

## StrategicRegionMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessStrategicRegion` |  | `StrategicRegion` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `AccessSelf` |  |  |  |
| `AccessStrategicRegion` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetStrategicRegion` |  |  |  |
| `Self` |  |  |  |

## StrategicRegionPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMapModeList` |  | `MapModeList` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `AccessSelf` |  |  |  |
| `GetStrategicRegion` |  |  |  |
| `Self` |  |  |  |

## SubjectType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDiplomaticActionType` |  | `DiplomaticActionType` |  |
| `GetHigherAutonomySubjectType` | `Arg0` | `SubjectType` |  |
| `GetLowerAutonomySubjectType` | `Arg0` | `SubjectType` |  |
| `AcceptsAnyOverlordType` |  | `bool` |  |
| `AcceptsOnlyRecognizedOverlordType` |  | `bool` |  |
| `AccessSelf` |  |  |  |
| `CanStartOwnDiplomaticPlays` |  | `bool` |  |
| `GetDesc` |  | `CString` |  |
| `GetDiplomaticActionType` |  |  |  |
| `GetHigherAutonomySubjectType` | `Arg0` |  |  |
| `GetIncomeTransfer` |  | `CFixedPoint` |  |
| `GetKey` |  | `CString` |  |
| `GetLowerAutonomySubjectType` | `Arg0` |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNameNoIconNoFormatting` |  | `CString` |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasCategory` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `JoinOverlordWars` |  | `bool` |  |
| `Self` |  |  |  |
| `ShouldAnnexOnCountryFormation` |  | `bool` |  |

## SupplyNetworkEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetValue` |  | `CFixedPoint` |  |
| `RouteGetName` |  | `CString` |  |
| `Self` |  |  |  |

## SupplyShipConstruction

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetShipType` |  | `ShipType` |  |
| `AccessSelf` |  |  |  |
| `GetConstructionCost` |  | `CFixedPoint` |  |
| `GetConstructionSpeed` |  | `CFixedPoint` |  |
| `GetConstructionUsage` |  | `CFixedPoint` |  |
| `GetEfficiency` |  | `CFixedPoint` |  |
| `GetPlaceInQueue` |  | `int32` |  |
| `GetProgress` |  | `CFixedPoint` |  |
| `GetProgressPercent` |  | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetWeeksLeft` |  | `int32` |  |
| `IsInProgress` |  | `bool` |  |
| `Self` |  |  |  |

## Sway

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSwayOffer` |  | `SwayOffer` |  |
| `MakeScope` |  | `Scope` |  |
| `AcceptSway` |  | `Command` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetProposalDesc` |  | `CString` |  |
| `GetSwayOffer` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsCallingInObligation` |  | `bool` |  |
| `IsReverseSway` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `RejectSway` |  | `Command` |  |
| `Self` |  |  |  |
| `WouldRepudiateObligationIfRejected` |  | `bool` |  |

## SwayCountryPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `AccessDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `AccessOtherCountry` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetOtherCountry` |  | `Country` |  |
| `AccessCountry` |  |  |  |
| `AccessDiplomaticPlay` |  |  |  |
| `AccessOtherCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessShownSwayOffers` |  |  |  |
| `AccessSwayOfferTypes` |  |  |  |
| `AccessSwayOfferWarGoalTypes` |  |  |  |
| `DecreaseFilterLevel` |  | `void` |  |
| `GetCountry` |  |  |  |
| `GetDiplomaticPlay` |  |  |  |
| `GetOtherCountry` |  |  |  |
| `IsReverseSway` |  | `bool` |  |
| `IsShowingSwayOfferTypes` |  | `bool` |  |
| `IsShowingSwayOfferWarGoalTypes` |  | `bool` |  |
| `IsShowingSwayOffers` |  | `bool` |  |
| `Self` |  |  |  |
| `SetSwayOfferType` | `Arg0` | `void` |  |
| `SetSwayOfferWarGoalType` | `Arg0` | `void` |  |

## SwayOffer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountryForFlag` | `Arg0` | `Country` |  |
| `GetDiplomaticActionType` |  | `DiplomaticActionType` |  |
| `GetOfferedWarGoal` |  | `WarGoalDraft` |  |
| `GetState` |  | `State` |  |
| `GetSwayOfferType` |  | `SwayOfferType` |  |
| `GetThirdPartyCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `CalcManeuversCost` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetAcceptSwayScore` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetAcceptSwayScoreWithArticle` | `Arg0, Arg1, Arg2, Arg3` | `int32` |  |
| `GetCountryForFlag` | `Arg0` |  |  |
| `GetDiplomaticActionType` |  |  |  |
| `GetManeuversCostDesc` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetName` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetOfferedWarGoal` |  |  |  |
| `GetState` |  |  |  |
| `GetSwayOfferType` |  |  |  |
| `GetTexture` |  |  |  |
| `GetThirdPartyCountry` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetWouldAcceptSwayDesc` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetWouldAcceptSwayDescWithArticle` | `Arg0, Arg1, Arg2, Arg3` | `CString` |  |
| `RequiresAnyInput` |  | `bool` |  |
| `Self` |  |  |  |
| `SetArticleInputsFromDraft` | `Arg0` | `void` |  |
| `TakesEffectImmediately` |  | `bool` |  |
| `WouldAcceptSway` | `Arg0, Arg1, Arg2` | `bool` |  |
| `WouldAcceptSwayWithArticle` | `Arg0, Arg1, Arg2, Arg3` | `bool` |  |

## SwayOfferType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |
