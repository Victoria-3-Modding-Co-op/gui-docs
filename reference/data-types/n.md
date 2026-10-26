# Data-binding types: N

Back to the [index](README.md).

## NationalAwakeningMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCulture` |  | `Culture` |  |
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## NationalizeBuildingGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetInvestor` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetErrors` |  | `CString` |  |
| `GetFilterMaxLevels` | `Arg0` | `int32` |  |
| `GetFilterNumSelectedLevels` | `Arg0` | `int32` |  |
| `GetInvestor` |  |  |  |
| `GetMaxLevels` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetNumSelectedLevels` |  | `int32` |  |
| `GetSelectedLevelsDesc` |  | `CString` |  |
| `HasFilter` | `Arg0` | `bool` |  |
| `IsGovernment` |  | `bool` |  |
| `IsNationalizable` |  | `bool` |  |
| `IsPrivate` |  | `bool` |  |
| `OnSelectedLevelsEditboxValueChanged` |  | `void` |  |
| `OnSelectedLevelsSliderValueChanged` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilter` | `Arg0` | `void` |  |

## NationalizeBuildingTypeGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuildingType` |  | `BuildingType` |  |
| `AccessSelf` |  |  |  |
| `GetBuildingType` |  |  |  |
| `GetCurrentLevels` |  | `int32` |  |
| `GetMaxLevels` |  | `int32` |  |
| `GetSelectedBuildingsBreakdown` |  | `CString` |  |
| `Self` |  |  |  |

## NationalizeBuildingWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanToggleCompensation` |  | `bool` |  |
| `GetBuildingGroups` |  |  |  |
| `GetBuildingTypeGroups` |  |  |  |
| `GetBuildings` |  |  |  |
| `GetCanToggleCompensationTooltip` |  | `CString` |  |
| `GetCompensationBreakdown` |  | `CString` |  |
| `GetCompensationShareToInvestmentPool` |  | `CFixedPoint` |  |
| `GetCompensationShareToPlayerInvestmentPool` |  | `CFixedPoint` |  |
| `GetCompensationTotal` |  | `CFixedPoint` |  |
| `GetDamagedRelationsListDesc` |  | `CString` |  |
| `GetNumLevelsToNationalize` |  | `int32` |  |
| `GetPopRadicalizationListDesc` |  | `CString` |  |
| `HasNationalizableGroup` |  | `bool` |  |
| `IsNationalizingAll` |  | `bool` |  |
| `NationalizeBuildingGroupsConfirm` |  | `void` |  |
| `NationalizeBuildingGroupsGetDesc` |  | `CString` |  |
| `NationalizeBuildingGroupsIsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `SetNationalizeToAll` |  | `void` |  |
| `SetNationalizeToNone` |  | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `ToggleGiveCompensation` |  | `void` |  |
| `WillGiveCompensation` |  | `bool` |  |

## NavalBattle

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAttackerBattleParticipant` |  | `NavalBattleParticipant` |  |
| `AccessDefenderBattleParticipant` |  | `NavalBattleParticipant` |  |
| `GetAttacker` |  | `Country` |  |
| `GetAttackerModifier` |  | `Modifier` |  |
| `GetAttackerSide` |  | `NavalBattleSide` |  |
| `GetBattleCondition` |  | `NavalBattleCondition` |  |
| `GetDefender` |  | `Country` |  |
| `GetDefenderModifier` |  | `Modifier` |  |
| `GetDefenderSide` |  | `NavalBattleSide` |  |
| `GetInvasion` |  | `Invasion` |  |
| `GetLoser` |  | `Country` |  |
| `GetProvince` |  | `Province` |  |
| `GetWinner` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessAttackerBattleParticipant` |  |  |  |
| `AccessDefenderBattleParticipant` |  |  |  |
| `AccessSelf` |  |  |  |
| `CalcCurrentAttackerPowerProjection` |  | `CFixedPoint` |  |
| `CalcCurrentDefenderPowerProjection` |  | `CFixedPoint` |  |
| `EndedInconclusively` |  | `bool` |  |
| `GetAttacker` |  |  |  |
| `GetAttackerLostShips` |  | `int32` |  |
| `GetAttackerModifier` |  |  |  |
| `GetAttackerNumWantedShipsDesc` |  | `CString` |  |
| `GetAttackerRemaingShipsFraction` |  | `CFixedPoint` |  |
| `GetAttackerUnderCommandBreakdown` |  | `CString` |  |
| `GetBattleIcon` |  |  |  |
| `GetCurrentLogPage` |  | `int32` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDateDesc` |  | `CString` |  |
| `GetDefender` |  |  |  |
| `GetDefenderLostShips` |  | `int32` |  |
| `GetDefenderModifier` |  |  |  |
| `GetDefenderNumWantedShipsDesc` |  | `CString` |  |
| `GetDefenderRemaingShipsFraction` |  | `CFixedPoint` |  |
| `GetDefenderUnderCommandBreakdown` |  | `CString` |  |
| `GetDurationInDaysRaw` |  | `int32` |  |
| `GetEndDate` |  | `CString` |  |
| `GetFinalAttackerPowerProjection` |  | `CFixedPoint` |  |
| `GetFinalAttackerShips` |  | `int32` |  |
| `GetFinalDefenderPowerProjection` |  | `CFixedPoint` |  |
| `GetFinalDefenderShips` |  | `int32` |  |
| `GetLocationName` |  | `CString` |  |
| `GetLogEntries` |  |  |  |
| `GetLoser` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumLogPages` |  | `int32` |  |
| `GetProvince` |  |  |  |
| `GetStartDate` |  | `CString` |  |
| `GetStartingAttackerPowerProjection` |  | `CFixedPoint` |  |
| `GetStartingAttackerShips` |  | `int32` |  |
| `GetStartingDefenderPowerProjection` |  | `CFixedPoint` |  |
| `GetStartingDefenderShips` |  | `int32` |  |
| `GetStatusString` |  | `CString` |  |
| `GetTerrain` |  | `CString` |  |
| `GetTerrainDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTurnNumber` |  | `int32` |  |
| `GetWinner` |  |  |  |
| `HasEnded` |  | `bool` |  |
| `HasInvasion` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsLeadCountry` | `Arg0` | `bool` |  |
| `IsLogFilterAll` |  | `bool` |  |
| `IsLogFilterMajor` |  | `bool` |  |
| `IsLogFilterStandard` |  | `bool` |  |
| `IsLoser` | `Arg0` | `bool` |  |
| `IsOnLoserSide` | `Arg0` | `bool` |  |
| `IsOnWinnerSide` | `Arg0` | `bool` |  |
| `IsRelevantForCountry` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsWinner` | `Arg0` | `bool` |  |
| `IsZoomingToMapMarkerPosition` |  | `bool` |  |
| `NextLogPage` |  | `void` |  |
| `PrevLogPage` |  | `void` |  |
| `ResetLogPage` |  | `void` |  |
| `Self` |  |  |  |
| `SetLogFilterAll` |  | `void` |  |
| `SetLogFilterMajor` |  | `void` |  |
| `SetLogFilterStandard` |  | `void` |  |
| `ZoomToMapMarkerPosition` |  | `void` |  |

## NavalBattleCondition

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## NavalBattleMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBattle` |  | `NavalBattle` |  |
| `AccessSelf` |  |  |  |
| `GetBattle` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## NavalBattlePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAttackerShipViewer` |  | `ShipViewer` |  |
| `GetBattle` |  | `NavalBattle` |  |
| `GetDefenderShipViewer` |  | `ShipViewer` |  |
| `GetHighlightedBattleEventLogEntry` |  | `BattleLogEntry` |  |
| `AccessSelf` |  |  |  |
| `GetAttackerShipViewer` |  |  |  |
| `GetBattle` |  |  |  |
| `GetDefenderShipViewer` |  |  |  |
| `GetHighlightedBattleEventLogEntry` |  |  |  |
| `HasHighlightedBattleEvent` |  | `bool` |  |
| `ResetCamera` |  | `void` |  |
| `Self` |  |  |  |

## NavalBattleParticipant

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `AccessCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetNumShips` |  | `int32` |  |
| `Self` |  |  |  |

## NavalBattleShipTemplateGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTemplate` |  | `ShipTemplate` |  |
| `AccessSelf` |  |  |  |
| `GetIDString` |  | `CString` |  |
| `GetNumActiveShips` |  | `int32` |  |
| `GetNumSunkShips` |  | `int32` |  |
| `GetNumTotalShips` |  | `int32` |  |
| `GetNumWithdrawnShips` |  | `int32` |  |
| `GetShips` |  |  |  |
| `Self` |  |  |  |

## NavalBattleSide

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCommander` |  | `Character` |  |
| `GetCountry` |  | `Country` |  |
| `GetDebugExampleShip` |  | `CombatShip` |  |
| `GetFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `GetActiveCrewShare` |  | `CFixedPoint` |  |
| `GetActiveHullShare` |  | `CFixedPoint` |  |
| `GetAverageArmor` |  | `CFixedPoint` |  |
| `GetAverageArmorPriority` |  | `CFixedPoint` |  |
| `GetAverageArmorScreening` |  | `CFixedPoint` |  |
| `GetAverageCrewing` |  | `CFixedPoint` |  |
| `GetAverageCrewingPriority` |  | `CFixedPoint` |  |
| `GetAverageCrewingScreening` |  | `CFixedPoint` |  |
| `GetAverageHullCondition` |  | `CFixedPoint` |  |
| `GetAverageHullConditionPriority` |  | `CFixedPoint` |  |
| `GetAverageHullConditionScreening` |  | `CFixedPoint` |  |
| `GetAverageHullDamage` |  | `CFixedPoint` |  |
| `GetAverageHullDamagePriority` |  | `CFixedPoint` |  |
| `GetAverageHullDamageScreening` |  | `CFixedPoint` |  |
| `GetCrewDamageDone` |  | `int32` |  |
| `GetCrewDamageTaken` |  | `int32` |  |
| `GetHullDamageDone` |  | `CFixedPoint` |  |
| `GetHullDamageTaken` |  | `CFixedPoint` |  |
| `GetLostCrewShare` |  | `CFixedPoint` |  |
| `GetLostHullShare` |  | `CFixedPoint` |  |
| `GetMaxCrew` |  | `int32` |  |
| `GetMaxHull` |  | `CFixedPoint` |  |
| `GetNumFailedWithdrawals` |  | `int32` |  |
| `GetNumMissedAttacks` |  | `int32` |  |
| `GetNumShips` |  | `int32` |  |
| `GetNumShipsAtEndOfBattleDesc` |  | `CString` |  |
| `GetNumShipsAtStartOfBattleDesc` |  | `CString` |  |
| `GetNumShipsDesc` |  | `CString` |  |
| `GetNumShipsSunk` |  | `int32` |  |
| `GetNumShipsWithdrawn` |  | `int32` |  |
| `GetNumSuccessfulAttacks` |  | `int32` |  |
| `GetOutcome` |  | `CString` |  |
| `GetPriorityMaxCrew` |  | `int32` |  |
| `GetPriorityMaxHull` |  | `CFixedPoint` |  |
| `GetPriorityNumShips` |  | `int32` |  |
| `GetPriorityNumShipsSunk` |  | `int32` |  |
| `GetPriorityNumShipsWithdrawn` |  | `int32` |  |
| `GetScreeningMaxCrew` |  | `int32` |  |
| `GetScreeningMaxHull` |  | `CFixedPoint` |  |
| `GetScreeningNumShips` |  | `int32` |  |
| `GetScreeningNumShipsSunk` |  | `int32` |  |
| `GetScreeningNumShipsWithdrawn` |  | `int32` |  |
| `GetShipTemplateGroups` |  |  |  |
| `GetStartingCrew` |  | `int32` |  |
| `GetStartingCrewPriority` |  | `int32` |  |
| `GetStartingCrewScreening` |  | `int32` |  |
| `GetStartingHull` |  | `CFixedPoint` |  |
| `GetStartingHullPriority` |  | `CFixedPoint` |  |
| `GetStartingHullScreening` |  | `CFixedPoint` |  |
| `GetStartingNumShips` |  | `int32` |  |
| `GetStartingNumShipsPriority` |  | `int32` |  |
| `GetStartingNumShipsScreening` |  | `int32` |  |
| `GetStatus` |  | `CString` |  |
| `GetStatusDesc` |  | `CString` |  |
| `GetTotalCrew` |  | `int32` |  |
| `GetTotalCrewWithdrawn` |  | `int32` |  |
| `GetTotalHull` |  | `CFixedPoint` |  |
| `GetTotalHullWithdrawn` |  | `CFixedPoint` |  |
| `GetTotalPriorityCrew` |  | `int32` |  |
| `GetTotalPriorityCrewWithdrawn` |  | `int32` |  |
| `GetTotalPriorityHull` |  | `CFixedPoint` |  |
| `GetTotalPriorityHullWithdrawn` |  | `CFixedPoint` |  |
| `GetTotalScreening` |  | `CFixedPoint` |  |
| `GetTotalScreeningCrew` |  | `int32` |  |
| `GetTotalScreeningCrewWithdrawn` |  | `int32` |  |
| `GetTotalScreeningHull` |  | `CFixedPoint` |  |
| `GetTotalScreeningHullWithdrawn` |  | `CFixedPoint` |  |
| `GetTotalVulnerability` |  | `CFixedPoint` |  |
| `GetWithdrawnCrewShare` |  | `CFixedPoint` |  |
| `GetWithdrawnHullShare` |  | `CFixedPoint` |  |
| `HasLost` |  | `bool` |  |
| `HasWon` |  | `bool` |  |
| `IsAttacker` |  | `bool` |  |
| `IsDefender` |  | `bool` |  |
| `Self` |  |  |  |

## NavalMission

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFleet` |  | `MilitaryFormation` |  |
| `GetType` |  | `NavalMissionType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFleet` |  |  |  |
| `GetMaxSeaRegions` |  | `int32` |  |
| `GetMaxSeaRegionsDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumSeaRegions` |  | `int32` |  |
| `GetSeaRegionBreakdown` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `Self` |  |  |  |

## NavalMissionMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstEnemyFleetOnMissionType` | `Arg0` | `MilitaryFormation` |  |
| `GetFirstFleetOnMissionType` | `Arg0` | `MilitaryFormation` |  |
| `GetProvince` |  | `Province` |  |
| `AccessEnemyFleetsOnMissionType` | `Arg0` |  |  |
| `AccessEnemyNavalMissionTypes` |  |  |  |
| `AccessEnemyPresentFleetsOnMissionType` | `Arg0` |  |  |
| `AccessEnemyTravelingFleetsOnMissionType` | `Arg0` |  |  |
| `AccessFleetsOnMissionType` | `Arg0` |  |  |
| `AccessNavalMissionTypes` |  |  |  |
| `AccessPresentFleetsOnMissionType` | `Arg0` |  |  |
| `AccessSelf` |  |  |  |
| `AccessTravelingFleetsOnMissionType` | `Arg0` |  |  |
| `AreAllFleetsOnMissionTypeRecalledForRepairs` | `Arg0` | `bool` |  |
| `GetFirstEnemyFleetOnMissionType` | `Arg0` |  |  |
| `GetFirstFleetOnMissionType` | `Arg0` |  |  |
| `GetNumEnemyFleetsOnMissionType` | `Arg0` | `int32` |  |
| `GetNumFleetsOnMissionType` | `Arg0` | `int32` |  |
| `GetPosition` |  | `CVector2f` |  |
| `HighlightEnemyFleetsOnMissionType` | `Arg0` | `void` |  |
| `HighlightFleetsOnMissionType` | `Arg0` | `void` |  |
| `IsAnyFleetOnMissionTypeRecalledForRepairs` | `Arg0` | `bool` |  |
| `IsMissionTypeHighlightedByEnemy` | `Arg0` | `bool` |  |
| `IsMissionTypeHighlightedByFriendly` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## NavalMissionType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCommandModifier` |  | `Modifier` |  |
| `GetModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetClickSound` |  |  |  |
| `GetCommandModifier` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetIsPossibleDesc` | `Arg0` | `CString` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsPossible` | `Arg0` | `bool` |  |
| `IsPotential` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## Node

Node Editor - Node

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ContextColor` |  | `CVector4f` |  |
| `Description` |  | `CString` |  |
| `ErrorColor` |  | `CVector4f` |  |
| `ErrorTooltip` |  | `CString` |  |
| `GetBackgroundColor` |  | `CVector4f` |  |
| `GetId` |  | `int32` |  |
| `GetSelectedColor` |  | `CVector4f` |  |
| `HasDescription` |  | `bool` |  |
| `HasError` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Name` |  | `CString` |  |
| `Self` |  |  |  |
| `TextColor` |  | `CVector4f` |  |
| `Texture` |  |  |  |
| `Tooltip` |  | `CString` |  |

## NodeEditorSearch

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearSearchText` |  | `void` |  |
| `CurrentResultIndex` |  | `int32` |  |
| `GetSearchText` |  | `CUTF8String` |  |
| `GoToNextResult` |  | `void` |  |
| `GoToPreviousResult` |  | `void` |  |
| `HasOccurrences` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `IsVisible` |  | `bool` |  |
| `NumOccurrences` |  | `int32` |  |
| `Search` |  | `void` |  |
| `Self` |  |  |  |

## NodeError

Node Editor - Node Error

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GoTo` |  | `void` |  |
| `Message` |  | `CString` |  |
| `Node` |  | `int32` |  |
| `Self` |  |  |  |

## NodeLine

Node Editor - Node Line

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Color` |  | `CVector4f` |  |
| `From` |  | `CVector2f` |  |
| `GetAnimationSpeed` |  | `CVector2f` |  |
| `GetOwnerNodeId` |  | `int32` |  |
| `Highlighted` |  | `bool` |  |
| `IsDisabled` |  | `bool` |  |
| `Self` |  |  |  |
| `SetHighlightedDirectly` | `Arg0` | `void` |  |
| `SetSelected` | `Arg0` | `void` |  |
| `To` |  | `CVector2f` |  |
| `Tooltip` |  |  |  |
| `Width` |  | `float` |  |

## NodePin

Node Editor - Node Pin

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Color` |  | `CVector4f` |  |
| `DrawAsConnected` |  | `bool` |  |
| `Highlight` |  | `bool` |  |
| `IsInlinedNodeConnected` |  | `bool` |  |
| `IsNodePinDisplayNameEmpty` |  | `bool` |  |
| `Name` |  | `CString` |  |
| `Self` |  |  |  |
| `Tooltip` |  | `CString` |  |
| `TypeColor` |  | `CVector4f` |  |

## NodeWindow

Node Editor - Node Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `DescriptionDialog` |  | `void` |  |
| `NameDialog` |  | `void` |  |
| `Self` |  |  |  |
| `SetDescription` |  | `void` |  |

## NonRegisteredDockable

NonRegistered Dockable Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetID` |  | `CString` |  |
| `Self` |  |  |  |

## NotificationDummyContext

Jomini Notification Dummy Context

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## NotificationOptionItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameWithConcept` |  | `CString` |  |
| `IsDefault` |  | `bool` |  |
| `Self` |  |  |  |

## NotificationSettingsItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentOption` |  | `NotificationOptionItem` |  |
| `AccessSelf` |  |  |  |
| `GetCurrentOption` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetTag` |  | `CString` |  |
| `GetValidOptions` |  |  |  |
| `HasAutoPause` |  | `bool` |  |
| `OnSelectOption` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleAutoPause` |  | `void` |  |

## Nudger

Map Editor - Map Object Manager (Nudger)

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CreateNewBlankMapObjectType` |  | `void` |  |
| `DeleteSelected` |  | `void` |  |
| `Deselect` |  | `void` |  |
| `FocusCameraOnSelection` |  | `void` |  |
| `IsAnyMapObjectExpanded` |  | `bool` |  |
| `IsAnyMapObjectHidden` |  | `bool` |  |
| `IsAnyMapObjectLocked` |  | `bool` |  |
| `IsAnyObjectEntrySelected` |  | `bool` |  |
| `IsAnyObjectSelected` |  | `bool` |  |
| `IsAnySelectedMapObjectDynamicType` |  | `bool` |  |
| `IsMultiSpawnEnabled` |  | `bool` |  |
| `OnMapObjectSelected` | `Arg0` | `void` |  |
| `SelectAll` |  | `void` |  |
| `Self` |  |  |  |
| `SetAllMapObjectsExpanded` | `Arg0` | `void` |  |
| `SetAllMapObjectsHidden` | `Arg0` | `void` |  |
| `SetAllMapObjectsLocked` | `Arg0` | `void` |  |
| `SetMapObjectHidden` | `Arg0, Arg1` | `void` |  |
| `SetMapObjectLocked` | `Arg0, Arg1` | `void` |  |
| `SetMapObjectLockedExclusive` | `Arg0, Arg1` | `void` |  |
| `SetMultiSpawnEnabled` | `Arg0` | `void` |  |
| `ToggleInstancesClampToWaterLevel` |  | `void` |  |
| `ToggleInstancesRenderUnderwater` |  | `void` |  |

## NudgerLayerEntryMapObjectDesc

Map Editor - Map Object - Map Content Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsAutoNudgingError` |  | `bool` |  |
| `IsLocked` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |
| `SetLocked` | `Arg0` | `void` |  |

## NudgerMapContentGui

Map Editor - Map Object - Map Content Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AutoNudgeSelection` |  | `void` |  |
| `GetAutoNudgingReadyProgress` |  | `float` |  |
| `IsAutoNudgePreviewEnabled` |  | `bool` |  |
| `IsAutoNudgingReady` |  | `bool` |  |
| `IsAutoNudgingSettingsOpen` |  | `bool` |  |
| `IsAutoNudgingSupported` |  | `bool` |  |
| `Self` |  |  |  |
| `SetAutoNudgePreviewEnabled` | `Arg0` | `void` |  |
| `SetAutoNudgingSettingsOpen` | `Arg0` | `void` |  |

## NudgerMapObjectPropertyListDockable

Map Editor - Map Object

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Delete` |  | `void` |  |
| `HasEntry` |  | `bool` |  |
| `IsGeneratedType` |  | `bool` |  |
| `Self` |  |  |  |

## NudgerMode

Map Editor - Map Object Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |
