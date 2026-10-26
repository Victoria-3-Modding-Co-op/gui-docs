# Data-binding types: B

Back to the [index](README.md).

## Battle

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAttackerBattleParticipant` |  | `BattleParticipant` |  |
| `AccessAttackerModifier` |  | `Modifier` |  |
| `AccessDefenderBattleParticipant` |  | `BattleParticipant` |  |
| `AccessDefenderModifier` |  | `Modifier` |  |
| `AccessFront` |  | `Front` |  |
| `GetAttacker` |  | `Country` |  |
| `GetAttackerCondition` |  | `BattleCondition` |  |
| `GetAttackerModifier` |  | `Modifier` |  |
| `GetAttackerSide` |  | `BattleSide` |  |
| `GetBattleUnitFormation` | `Arg0` | `BattleMilitaryFormation` |  |
| `GetCapturingCountry` |  | `Country` |  |
| `GetDefender` |  | `Country` |  |
| `GetDefenderCondition` |  | `BattleCondition` |  |
| `GetDefenderModifier` |  | `Modifier` |  |
| `GetDefenderSide` |  | `BattleSide` |  |
| `GetFront` |  | `Front` |  |
| `GetInvasion` |  | `Invasion` |  |
| `GetLoosingProvincesCountry` |  | `Country` |  |
| `GetLoser` |  | `Country` |  |
| `GetProvince` |  | `Province` |  |
| `GetState` |  | `State` |  |
| `GetWinner` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessAttackerBattleParticipant` |  |  |  |
| `AccessAttackerModifier` |  |  |  |
| `AccessBorrowedAttackerBuildingEntries` |  |  |  |
| `AccessBorrowedDefenderBuildingEntries` |  |  |  |
| `AccessCommandedAttackerBuildingEntries` |  |  |  |
| `AccessCommandedDefenderBuildingEntries` |  |  |  |
| `AccessCountryTrendPairs` |  |  |  |
| `AccessDefenderBattleParticipant` |  |  |  |
| `AccessDefenderModifier` |  |  |  |
| `AccessManpowerTrendPairs` |  |  |  |
| `AccessSelf` |  |  |  |
| `CalcCurrentAttackerManpower` |  | `int64` |  |
| `CalcCurrentAttackerMorale` |  | `CFixedPoint` |  |
| `CalcCurrentDefenderManpower` |  | `int64` |  |
| `CalcCurrentDefenderMorale` |  | `CFixedPoint` |  |
| `CalcPushOfWar` |  | `CFixedPoint` |  |
| `EndedInconclusively` |  | `bool` |  |
| `GetAttacker` |  |  |  |
| `GetAttackerBorrowedFormations` |  |  |  |
| `GetAttackerCondition` |  |  |  |
| `GetAttackerConditionUpdateDesc` |  | `CString` |  |
| `GetAttackerEndCE` |  | `CFixedPoint` |  |
| `GetAttackerLostUnits` |  | `int32` |  |
| `GetAttackerModifier` |  |  |  |
| `GetAttackerNumWantedUnitsDesc` |  | `CString` |  |
| `GetAttackerStartCE` |  | `CFixedPoint` |  |
| `GetAttackerStatistics` |  |  |  |
| `GetAttackerStillFightingTrend` |  | `DataTrend` |  |
| `GetAttackerTotalDead` |  | `CFixedPoint` | Returns total number of dead in attacker side |
| `GetAttackerTotalDemoralized` |  | `CFixedPoint` | Returns total number of demoralized in attacker side |
| `GetAttackerTotalWounded` |  | `CFixedPoint` | Returns total number of wounded in attacker side |
| `GetAttackerTrend` |  | `DataTrend` |  |
| `GetAttackerUnderCommandBreakdown` |  | `CString` |  |
| `GetBattleIcon` |  |  |  |
| `GetBattleUnitFormation` | `Arg0` |  |  |
| `GetBattleUnitTypeList` | `Arg0` |  |  |
| `GetCapturingCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDateDesc` |  | `CString` |  |
| `GetDefender` |  |  |  |
| `GetDefenderBorrowedFormations` |  |  |  |
| `GetDefenderCondition` |  |  |  |
| `GetDefenderConditionUpdateDesc` |  | `CString` |  |
| `GetDefenderEndCE` |  | `CFixedPoint` |  |
| `GetDefenderLostUnits` |  | `int32` |  |
| `GetDefenderModifier` |  |  |  |
| `GetDefenderNumWantedUnitsDesc` |  | `CString` |  |
| `GetDefenderStartCE` |  | `CFixedPoint` |  |
| `GetDefenderStatistics` |  |  |  |
| `GetDefenderStillFightingTrend` |  | `DataTrend` |  |
| `GetDefenderTotalDead` |  | `CFixedPoint` | Returns total number of dead in defender side |
| `GetDefenderTotalDemoralized` |  | `CFixedPoint` | Returns total number of demoralized in defender side |
| `GetDefenderTotalWounded` |  | `CFixedPoint` | Returns total number of wounded in defender side |
| `GetDefenderTrend` |  | `DataTrend` |  |
| `GetDefenderUnderCommandBreakdown` |  | `CString` |  |
| `GetDefenseRaw` |  | `CFixedPoint` | Returns the defender units defense including battle conditions, terrain, etc |
| `GetDurationInDaysRaw` |  | `int32` |  |
| `GetEndDate` |  | `CString` |  |
| `GetEndingAttackerMorale` |  | `CFixedPoint` |  |
| `GetEndingDefenderMorale` |  | `CFixedPoint` |  |
| `GetFinalAttackerManpower` |  | `int64` |  |
| `GetFinalAttackerUnits` |  | `int32` |  |
| `GetFinalDefenderManpower` |  | `int64` |  |
| `GetFinalDefenderUnits` |  | `int32` |  |
| `GetInitialAttackerMorale` |  | `CFixedPoint` |  |
| `GetInitialDefenderMorale` |  | `CFixedPoint` |  |
| `GetLocationName` |  | `CString` |  |
| `GetLoosingProvincesCountry` |  |  |  |
| `GetLoser` |  |  |  |
| `GetMaxNumberInBattleTrends` |  | `CFixedPoint` |  |
| `GetMaxNumberInManpowerTrends` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNumCapturedProvinces` |  | `int32` |  |
| `GetOccupationWon` |  | `CString` |  |
| `GetOccupationWonRaw` |  | `CFixedPoint` |  |
| `GetOffenseRaw` |  | `CFixedPoint` | Returns the attacker units offense including battle conditions, terrain, etc |
| `GetProvince` |  |  |  |
| `GetStartDate` |  | `CString` |  |
| `GetStartingAttackerManpower` |  | `int64` |  |
| `GetStartingAttackerUnits` |  | `int32` |  |
| `GetStartingDefenderManpower` |  | `int64` |  |
| `GetStartingDefenderUnits` |  | `int32` |  |
| `GetState` |  |  |  |
| `GetStatusString` |  | `CString` |  |
| `GetTerrain` |  | `CString` |  |
| `GetTerrainDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUnitIcon` |  | `CString` |  |
| `GetVictoryScore` |  | `CString` |  |
| `GetVictoryScoreRaw` |  | `CFixedPoint` |  |
| `GetWinner` |  |  |  |
| `HasEnded` |  | `bool` |  |
| `HasInvasion` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsLeadCountry` | `Arg0` | `bool` |  |
| `IsLoser` | `Arg0` | `bool` |  |
| `IsManpowerTrendsEmpty` |  | `bool` |  |
| `IsNavalInvasionLandingBattle` |  | `bool` |  |
| `IsOnLoserSide` | `Arg0` | `bool` |  |
| `IsOnWinnerSide` | `Arg0` | `bool` |  |
| `IsRelevantForCountry` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsWinner` | `Arg0` | `bool` |  |
| `IsZoomingToMapMarkerPosition` |  | `bool` |  |
| `LostOrCapturedProvinces` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `ZoomToMapMarkerPosition` |  | `void` |  |

## BattleBuildingEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuilding` |  | `Building` |  |
| `AccessSelf` |  |  |  |
| `GetAverageMorale` |  | `CFixedPoint` |  |
| `GetBuilding` |  |  |  |
| `GetUnits` |  |  |  |
| `IsExpanded` |  | `bool` |  |
| `IsUnderDirectCommand` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpand` |  | `void` |  |

## BattleCondition

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## BattleLogEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessActor` |  | `Ship` |  |
| `AccessAttackerSideCombatShip` |  | `CombatShip` |  |
| `AccessBattleCondition` |  | `NavalBattleCondition` |  |
| `AccessDefenderSideCombatShip` |  | `CombatShip` |  |
| `AccessTarget` |  | `Ship` |  |
| `GetActor` |  | `Ship` |  |
| `GetAttackerSideCombatShip` |  | `CombatShip` |  |
| `GetBattleCondition` |  | `NavalBattleCondition` |  |
| `GetDefenderSideCombatShip` |  | `CombatShip` |  |
| `GetTarget` |  | `Ship` |  |
| `AccessSelf` |  |  |  |
| `GetActorCurrentCrew` |  | `int32` |  |
| `GetActorCurrentCrewPercentage` |  | `CFixedPoint` |  |
| `GetActorCurrentHitPointPercentage` |  | `CFixedPoint` |  |
| `GetActorCurrentHitPoints` |  | `int32` |  |
| `GetActorMaxCrew` |  | `int32` |  |
| `GetActorMaxHitPoints` |  | `int32` |  |
| `GetCrewDamage` |  | `int32` |  |
| `GetDescription` |  | `CString` |  |
| `GetHullDamage` |  | `int32` |  |
| `GetNumAffectedShips` |  | `int32` |  |
| `GetNumSunkShips` |  | `int32` |  |
| `GetTargetCurrentCrew` |  | `int32` |  |
| `GetTargetCurrentCrewPercentage` |  | `CFixedPoint` |  |
| `GetTargetCurrentHitPointPercentage` |  | `CFixedPoint` |  |
| `GetTargetCurrentHitPoints` |  | `int32` |  |
| `GetTargetMaxCrew` |  | `int32` |  |
| `GetTargetMaxHitPoints` |  | `int32` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasBattleCondition` |  | `bool` |  |
| `IsActor` | `Arg0` | `bool` |  |
| `IsActorDefender` |  | `bool` |  |
| `IsAttack` |  | `bool` |  |
| `IsConditionEffectTotal` |  | `bool` |  |
| `IsConditionSunkShip` |  | `bool` |  |
| `IsCritical` |  | `bool` |  |
| `IsHighImportance` |  | `bool` |  |
| `IsLowImportance` |  | `bool` |  |
| `IsStandardImportance` |  | `bool` |  |
| `IsTarget` | `Arg0` | `bool` |  |
| `IsTargetDefender` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsWithdraw` |  | `bool` |  |
| `Self` |  |  |  |
| `TargetSank` |  | `bool` |  |

## BattleMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBattle` |  | `Battle` |  |
| `AccessSelf` |  |  |  |
| `GetBattle` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## BattleMilitaryFormation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAverageDefense` |  | `CFixedPoint` |  |
| `GetAverageOffense` |  | `CFixedPoint` |  |
| `GetCurrentManpowerFromFormation` |  | `int64` |  |
| `GetCurrentMorale` |  | `CFixedPoint` |  |
| `GetMaxManpowerFromFormation` |  | `int64` |  |
| `GetTotalUnitsFromFormation` |  | `int32` |  |
| `Self` |  |  |  |

## BattlePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBattle` |  | `Battle` |  |
| `AccessSelf` |  |  |  |
| `GetBattle` |  |  |  |
| `Self` |  |  |  |

## BattleParticipant

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `AccessCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetMorale` |  | `CFixedPoint` |  |
| `GetNumCombatUnits` |  | `int32` |  |
| `Self` |  |  |  |

## BattleSide

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCommander` |  | `Character` |  |
| `GetCountry` |  | `Country` |  |
| `GetFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `GetIconFrame` |  | `int32` |  |
| `GetNumUnits` |  | `int32` |  |
| `GetNumUnitsAtEndOfBattleDesc` |  | `CString` |  |
| `GetNumUnitsAtStartOfBattleDesc` |  | `CString` |  |
| `GetNumUnitsDesc` |  | `CString` |  |
| `GetOutcome` |  | `CString` |  |
| `GetStatus` |  | `CString` |  |
| `GetStatusDesc` |  | `CString` |  |
| `HasEscaped` |  | `bool` |  |
| `HasLost` |  | `bool` |  |
| `HasWon` |  | `bool` |  |
| `IsAttacker` |  | `bool` |  |
| `IsDefender` |  | `bool` |  |
| `Self` |  |  |  |

## BattleUnitType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCombatUnitType` |  | `CombatUnitType` |  |
| `AccessSelf` |  |  |  |
| `GetAverageMorale` |  | `CFixedPoint` |  |
| `GetCombatUnitType` |  |  |  |
| `GetIDString` | `Arg0, Arg1` | `CString` |  |
| `GetNumberOfConscriptUnits` |  | `int32` |  |
| `GetNumberOfRegularUnits` |  | `int32` |  |
| `GetUnits` |  |  |  |
| `Self` |  |  |  |

## BlurThreshold

Map Editor - Blur Threshold

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValue` |  | `float` |  |
| `Self` |  |  |  |
| `SetValue` |  | `void` |  |
| `SetValueStr` |  | `void` |  |

## bool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## BrushBool

Map Editor - Brush bool settings.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Get` |  | `bool` |  |
| `Self` |  |  |  |
| `Set` |  | `void` |  |
| `Toggle` |  | `void` |  |

## BrushFloat

Map Editor - Brush float settings.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `DecreaseBySmallStep` |  | `void` |  |
| `DecreaseByStep` |  | `void` |  |
| `IncreaseBySmallStep` |  | `void` |  |
| `IncreaseByStep` |  | `void` |  |
| `Max` |  | `float` |  |
| `Min` |  | `float` |  |
| `ScaledValue` | `Arg0` | `float` |  |
| `Self` |  |  |  |
| `SetMax` |  | `void` |  |
| `SetMin` |  | `void` |  |
| `SetScaledValue` | `Arg0` | `void` |  |
| `SetStepSize` |  | `void` |  |
| `SetValue` |  | `void` |  |
| `SetValueArg` | `Arg0` | `void` |  |
| `SetValueFromWidget` | `Arg0` | `void` |  |
| `SmallStepSize` |  | `float` |  |
| `StepSize` |  | `float` |  |
| `Value` |  | `float` |  |

## BrushSettings

Map Editor - Brush settings.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `Amount` |  | `BrushFloat` |  |
| `Hardness` |  | `BrushFloat` |  |
| `PixelSnap` |  | `BrushBool` |  |
| `Radius` |  | `BrushFloat` |  |
| `AccessSelf` |  |  |  |
| `Amount` |  |  |  |
| `Diameter` |  | `float` |  |
| `Hardness` |  |  |  |
| `PixelSnap` |  |  |  |
| `Radius` |  |  |  |
| `Self` |  |  |  |
| `SetAmount` |  | `void` |  |
| `SetDiameter` |  | `void` |  |
| `SetHardness` |  | `void` |  |

## BrushSettingsDropdown

Map Editor - Brush settings dropdown.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `Settings` |  | `BrushSettings` |  |
| `AccessSelf` |  |  |  |
| `GetBrushDiameter` |  | `float` |  |
| `Self` |  |  |  |
| `Settings` |  |  |  |
| `Thumbnail` |  |  |  |
| `Toggle` |  | `void` |  |

## BrushSettingsGlobal

Map Editor - Global Brush settings.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDisplayAmountNames` |  |  |  |
| `IsDisplayAmountActive` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetIsDisplayAmountFromString` | `Arg0` | `void` |  |

## BudgetPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMapModeList` |  | `MapModeList` |  |
| `AccessSelf` |  |  |  |
| `AccessTaxableGoods` |  |  |  |
| `AccessTaxedGoods` |  |  |  |
| `CanTaxGoods` |  | `bool` |  |
| `Filter` | `Arg0` | `void` |  |
| `GetFilters` |  |  |  |
| `IsAddConsumptionTaxMenuOpen` |  | `bool` |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `ToggleAddConsumptionTaxMenu` | `Arg0` | `void` |  |

## Building

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessHoldingCharacter` |  | `Character` |  |
| `AccessModifier` |  | `Modifier` |  |
| `AccessOwnerPopsList` |  | `PopList` |  |
| `AccessPopsList` |  | `PopList` |  |
| `AccessProductionMethod` | `Arg0` | `ProductionMethod` |  |
| `AccessState` |  | `State` |  |
| `AccessStateRegion` |  | `StateRegion` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `GetCompany` |  | `Company` |  |
| `GetDefaultOutputGoods` |  | `Goods` |  |
| `GetHQ` |  | `Hq` |  |
| `GetHoldingCharacter` |  | `Character` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetOwner` |  | `Country` |  |
| `GetProducedModifiers` |  | `Modifier` |  |
| `GetProductionMethodGroup` | `Arg0` | `ProductionMethodGroup` |  |
| `GetState` |  | `State` |  |
| `GetStateRegion` |  | `StateRegion` |  |
| `GetWorstGoodsShortage` |  | `Goods` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessConsumedGoods` |  |  |  |
| `AccessHoldingCharacter` |  |  |  |
| `AccessModifier` |  |  |  |
| `AccessOwnerPopsList` |  |  |  |
| `AccessPopsList` |  |  |  |
| `AccessProducedGoods` |  |  |  |
| `AccessProductionMethod` | `Arg0` |  |  |
| `AccessProductionMethodGroups` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessShortageGoods` |  |  |  |
| `AccessState` |  |  |  |
| `AccessStateRegion` |  |  |  |
| `CalcInfrastructureUsage` |  | `CFixedPoint` |  |
| `CalcInputAvailabilityOutputMult` |  | `CFixedPoint` |  |
| `CalcInputGoodsShortageTargetPenalty` |  | `CFixedPoint` |  |
| `CalcInputGoodsShortageTargetPenaltyFromGoods` | `Arg0` | `CFixedPoint` |  |
| `CalcUrbanizationProvided` |  | `int32` |  |
| `CanBeAffectedByInputShortage` | `Arg0` | `bool` |  |
| `CanBePrivatized` |  | `bool` |  |
| `CancelConstruction` |  | `Command` |  |
| `Downsize` |  | `Command` |  |
| `GeneratesCombatUnits` |  | `bool` |  |
| `GeneratesNavy` |  | `bool` |  |
| `GetAdjustHiringTargetDesc` |  | `CString` |  |
| `GetAllEmployeesTransferDesc` |  | `CString` |  |
| `GetAllFailedHiresDesc` |  | `CString` |  |
| `GetArmyManpower` |  | `int64` |  |
| `GetArmyReadinessStatusDesc` |  | `CString` |  |
| `GetAutoDownsizeTooltip` |  | `CString` |  |
| `GetAutoExpandTooltip` |  | `CString` |  |
| `GetAutoExpandTriggers` |  | `CString` |  |
| `GetAverageAnnualEarningsPerEmployee` |  | `CFixedPoint` |  |
| `GetAverageAnnualEarningsPerEmployeeFormatted` |  | `CString` |  |
| `GetAverageAnnualWage` |  | `CFixedPoint` |  |
| `GetAverageAnnualWageBreakdown` |  | `CString` |  |
| `GetAverageAnnualWageBreakdownForPopType` | `Arg0` | `CString` |  |
| `GetAverageAnnualWageForPopType` | `Arg0` | `CFixedPoint` |  |
| `GetAverageAnnualWageForPopTypeDesc` | `Arg0` | `CString` |  |
| `GetAverageAnnualWageSubsidies` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLiving` |  | `CFixedPoint` |  |
| `GetBalance` |  | `CFixedPoint` |  |
| `GetBalanceDesc` |  | `CString` |  |
| `GetBombardmentDestructionChanceDesc` |  | `CString` |  |
| `GetBombardmentDestructionChancePerDay` |  | `CFixedPoint` |  |
| `GetBuildingAssets` |  |  |  |
| `GetBuildingGroupName` |  | `CString` |  |
| `GetBuildingOwnerships` |  |  |  |
| `GetBuildingType` |  |  |  |
| `GetCancelConstructionTooltip` |  | `CString` |  |
| `GetCappedAssetsLong` |  |  |  |
| `GetCappedAssetsLongRest` |  |  |  |
| `GetCappedAssetsShort` |  |  |  |
| `GetCappedAssetsShortRest` |  |  |  |
| `GetCappedOwnersLong` |  |  |  |
| `GetCappedOwnersLongRest` |  |  |  |
| `GetCappedOwnersShort` |  |  |  |
| `GetCappedOwnersShortRest` |  |  |  |
| `GetCashReservesTrend` |  | `DataTrend` |  |
| `GetCasualtiesDesc` |  | `CString` |  |
| `GetChangeProductionMethodPopQualificationsWarningBreakdown` | `Arg0` | `CString` |  |
| `GetCombatUnitCapacity` |  | `int32` |  |
| `GetCombatUnitCapacityDesc` |  | `CString` |  |
| `GetCombatUnitProduction` |  | `CString` |  |
| `GetCombatUnitProductionBreakdown` |  | `CString` |  |
| `GetCombatUnitTypes` |  |  |  |
| `GetCombatUnits` |  |  |  |
| `GetCombatUnitsIcon` |  | `CString` |  |
| `GetCombatUnitsInFormation` | `Arg0` |  |  |
| `GetCompany` |  |  |  |
| `GetConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetConstructionProgressPercentage` |  | `float` |  |
| `GetConstructionRemainingWeeksDesc` |  | `CString` |  |
| `GetConstructionSpeedPerWeek` |  | `CFixedPoint` |  |
| `GetConstructionSpeedPerWeekDesc` |  | `CString` |  |
| `GetConsumption` | `Arg0` | `CFixedPoint` |  |
| `GetConsumptionDesc` | `Arg0` | `CString` |  |
| `GetConsumptionValue` | `Arg0` | `CFixedPoint` |  |
| `GetCurrentCashReserves` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDebugTooltip` |  | `CString` |  |
| `GetDefaultOutputGoods` |  |  |  |
| `GetDownsizeTooltip` |  | `CString` |  |
| `GetEarnings` |  | `CFixedPoint` |  |
| `GetEarningsPerEmployeeTrend` |  | `DataTrend` |  |
| `GetEmployeeCap` |  | `int64` |  |
| `GetEmployeesBreakdown` |  | `CString` |  |
| `GetEmployeesTransferDesc` | `Arg0` | `CString` |  |
| `GetEmploymentPercentage` |  | `CFixedPoint` |  |
| `GetEmploymentTooltip` |  | `CString` |  |
| `GetEstablishmentDate` |  | `CString` |  |
| `GetExpansionLevel` |  | `int32` |  |
| `GetExpansionLevelBreakdown` |  | `CString` |  |
| `GetExpansionLevelBreakdownDesc` |  | `CString` |  |
| `GetExpansionLevelDesc` |  | `CString` |  |
| `GetExpansionLevelsInQueue` |  | `int32` |  |
| `GetFailedHiresDesc` | `Arg0` | `CString` |  |
| `GetGoodsShortageListDesc` |  | `CString` |  |
| `GetGovernmentExpenses` |  | `CFixedPoint` |  |
| `GetGovernmentExpensesDesc` |  | `CString` |  |
| `GetHQ` |  |  |  |
| `GetHoldingCharacter` |  |  |  |
| `GetID` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetInfrastructureUsageBreakdown` |  | `CString` |  |
| `GetInputMult` |  | `CFixedPoint` |  |
| `GetInputMultDesc` |  | `CString` |  |
| `GetInputOutputTooltip` |  | `CString` |  |
| `GetInputShortagePenalty` |  | `CFixedPoint` |  |
| `GetLastIncome` |  | `CFixedPoint` |  |
| `GetLastMaterialExpenses` |  | `CFixedPoint` |  |
| `GetLastMaterialExpensesDesc` |  | `CString` |  |
| `GetLastRevenue` |  | `CFixedPoint` |  |
| `GetLastRevenueBalancedSI` | `Arg0, Arg1` | `CString` |  |
| `GetLastSlaveBasket` |  | `int32` |  |
| `GetLastSlaveBasketDesc` |  | `CString` |  |
| `GetLastSlaveUpkeep` |  | `CFixedPoint` |  |
| `GetLastSlaveUpkeepDesc` |  | `CString` |  |
| `GetLastWagesExpenses` |  | `CFixedPoint` |  |
| `GetLastWagesExpensesDesc` |  | `CString` |  |
| `GetManpowerCapacity` |  | `int64` |  |
| `GetMaxCashReserves` |  | `CFixedPoint` |  |
| `GetMaxLevels` |  | `int32` |  |
| `GetMaxPopSize` | `Arg0` | `int64` |  |
| `GetMaxPopSizeDesc` | `Arg0` | `CString` |  |
| `GetMilitaryFormations` |  |  |  |
| `GetMilitaryShipMaintenanceRevenue` |  | `CFixedPoint` |  |
| `GetMilitaryShipMaintenanceRevenueBreakdown` |  | `CString` |  |
| `GetMobilizationRatio` |  | `CFixedPoint` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNationalizeBuildingNoCompensationDesc` | `Arg0` | `CString` |  |
| `GetNationalizeBuildingWithCompensationDesc` | `Arg0` | `CString` |  |
| `GetNavyManpower` |  | `int64` |  |
| `GetNoLevelsCanBeNationalizedDesc` |  | `CString` |  |
| `GetNoOfEmployed` |  | `int64` |  |
| `GetNotHiringReasonDesc` |  | `CString` |  |
| `GetNumActiveUnitsProvidedToFormation` | `Arg0` | `int32` |  |
| `GetNumEmployeesOfType` | `Arg0` | `int64` |  |
| `GetNumLevelsCanBeNationalized` |  | `int32` |  |
| `GetNumOwnedLevels` |  | `int32` |  |
| `GetNumShipAssignmentsFilled` |  | `int32` |  |
| `GetNumShipAssignmentsMax` |  | `int32` |  |
| `GetNumSupplyShips` |  | `int32` |  |
| `GetNumUnitsOfCombatUnitType` | `Arg0` | `int32` |  |
| `GetNumUnitsOfCombatUnitTypeProvidedToFormation` | `Arg0, Arg1` | `int32` |  |
| `GetNumberOfCombatUnits` |  | `int32` |  |
| `GetNumberOfFullyMobilizedBattalions` |  | `int32` |  |
| `GetOutputPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetOutputRatio` |  | `CFixedPoint` |  |
| `GetOwner` |  |  |  |
| `GetPopTypeFullyReplacedDesc` | `Arg0` | `CString` |  |
| `GetPopTypeReplacementDesc` | `Arg0` | `CString` |  |
| `GetPrivatizationTooltip` |  | `CString` |  |
| `GetProducedModifiers` |  |  |  |
| `GetProducedSupply` |  | `CFixedPoint` |  |
| `GetProduction` | `Arg0` | `CFixedPoint` |  |
| `GetProductionDesc` | `Arg0` | `CString` |  |
| `GetProductionMethodGroup` | `Arg0` |  |  |
| `GetProductionValue` | `Arg0` | `CFixedPoint` |  |
| `GetProfitability` |  | `CString` |  |
| `GetProfitabilityCompareIcon` |  | `CString` |  |
| `GetProfitabilityCompareIconInType` |  | `CString` |  |
| `GetProfitabilityInType` |  | `CString` |  |
| `GetProfitabilityInTypeTrend` |  | `DataTrend` |  |
| `GetProfitabilityRank` |  | `int32` |  |
| `GetProfitabilityRankInType` |  | `int32` |  |
| `GetProfitabilityTrend` |  | `DataTrend` |  |
| `GetQueueConstructionPopQualificationsWarningBreakdown` |  | `CString` |  |
| `GetQueueConstructionTooltip` |  | `CString` |  |
| `GetQueueMilitaryConstructionTooltip` | `Arg0, Arg1` | `CString` |  |
| `GetResetProductionMethodsToStandardTooltip` |  | `CString` |  |
| `GetSamplePops` |  |  |  |
| `GetShipConstructionRevenue` |  | `CFixedPoint` |  |
| `GetShipsWithAssignments` |  |  |  |
| `GetSizeTooltip` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetStateRegion` |  |  |  |
| `GetStatusDesc` |  | `CString` |  |
| `GetSubsidies` |  | `CFixedPoint` |  |
| `GetSubsidiesDesc` |  | `CString` |  |
| `GetSubsidizeTooltip` |  | `CString` |  |
| `GetSubsistenceOutput` |  | `CFixedPoint` |  |
| `GetSubsistenceOutputDesc` |  | `CString` |  |
| `GetSubventions` |  | `CFixedPoint` |  |
| `GetSuppliedFormations` |  |  |  |
| `GetSupplyShipMaintenanceRevenue` |  | `CFixedPoint` |  |
| `GetSupplyShipMaintenanceRevenueBreakdown` |  | `CString` |  |
| `GetSupplyWithoutShortage` |  | `CFixedPoint` |  |
| `GetTariffsPaid` |  | `CFixedPoint` |  |
| `GetTaxationRevenue` |  | `CFixedPoint` |  |
| `GetTaxationRevenueTooltip` |  | `CString` |  |
| `GetThroughputBonusCurrent` |  | `CFixedPoint` |  |
| `GetThroughputBonusTarget` |  | `CFixedPoint` |  |
| `GetThroughputDesc` |  | `CString` |  |
| `GetTimedModifiers` |  |  |  |
| `GetTogglePrivatizationTooltip` |  | `CString` |  |
| `GetTollsPaid` |  | `CFixedPoint` |  |
| `GetTollsPaidDesc` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalConsumptionValue` |  | `CFixedPoint` |  |
| `GetTotalExpenses` |  | `CFixedPoint` |  |
| `GetTotalExpensesBalancedSI` | `Arg0, Arg1` | `CString` |  |
| `GetTotalLevels` |  | `int32` |  |
| `GetTotalProductionValue` |  | `CFixedPoint` |  |
| `GetTradeRevenue` |  | `CFixedPoint` |  |
| `GetTrainingRate` |  | `int64` |  |
| `GetTrainingRateDesc` |  | `CString` |  |
| `GetUnitsProvidedToFormationBreakdown` | `Arg0` | `CString` |  |
| `GetUrbanizationProvidedBreakdown` |  | `CString` |  |
| `GetWageRate` |  | `CFixedPoint` |  |
| `GetWorstGoodsShortage` |  |  |  |
| `HasAnyInputShortage` |  | `bool` |  |
| `HasConstructionQueued` |  | `bool` |  |
| `HasFailedHires` |  | `bool` |  |
| `HasGovernmentConstructionQueued` |  | `bool` |  |
| `HasHoldingCharacter` |  | `bool` |  |
| `HasInputGoods` |  | `bool` |  |
| `HasInputShortage` | `Arg0` | `bool` |  |
| `HasMaximumInputShortage` | `Arg0` | `bool` |  |
| `HasOutputGoods` |  | `bool` |  |
| `HasPrivateConstructionQueued` |  | `bool` |  |
| `HasReachedLevelCap` |  | `bool` |  |
| `HasSlaves` |  | `bool` |  |
| `HasTradeRevenue` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsActiveStr` |  | `CString` |  |
| `IsAutoDownsizing` |  | `bool` |  |
| `IsAutoExpanding` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsBuildingType` | `Arg0` | `bool` |  |
| `IsCappedBuilding` |  | `bool` |  |
| `IsConstructionOutputPaused` |  | `bool` |  |
| `IsCurrentlyUnderConstruction` |  | `bool` |  |
| `IsDownsizeable` |  | `bool` |  |
| `IsExpandable` |  | `bool` |  |
| `IsGovernmentFunded` |  | `bool` |  |
| `IsLogisticsCenter` |  | `bool` |  |
| `IsMilitaryBuilding` |  | `bool` |  |
| `IsNavalLogisticsCenter` |  | `bool` |  |
| `IsOwner` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsPotentialQueueConstruction` |  | `bool` |  |
| `IsRoleFullyReplacedByAnotherPopType` | `Arg0` | `bool` |  |
| `IsSelfFunded` |  | `bool` |  |
| `IsSubsidized` |  | `bool` |  |
| `IsSubsistenceBuilding` |  | `bool` |  |
| `IsUrbanCenter` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `NationalizeBuildingLevels` | `Arg0` | `Command` |  |
| `PauseConstructionOutput` |  | `Command` |  |
| `ProvidesUrbanization` |  | `bool` |  |
| `QueueConstruction` |  | `Command` |  |
| `QueueMilitaryConstruction` | `Arg0, Arg1` | `Command` |  |
| `ResetProductionMethodsToStandard` |  | `Command` |  |
| `ResumeConstructionOutput` |  | `Command` |  |
| `Self` |  |  |  |
| `ShouldShowAsHiring` |  | `bool` |  |
| `ShouldShowAsUnableToHire` |  | `bool` |  |
| `ShouldShowAsUnwillingToHire` |  | `bool` |  |
| `ShowLevelAndMaxLevel` |  | `bool` |  |
| `SortBuildings` | `Arg0` | `void` |  |
| `SortOwnerships` | `Arg0` | `void` |  |
| `SortSuppliedFormations` | `Arg0` | `void` |  |
| `ToggleAutoExpand` |  | `Command` |  |
| `ToggleAutoExpandOff` |  | `Command` |  |
| `ToggleAutoExpandOn` |  | `Command` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `TogglePrivatization` |  | `Command` |  |
| `ToggleSubsidies` |  | `Command` |  |
| `ToggleSubsidiesOff` |  | `Command` |  |
| `ToggleSubsidiesOn` |  | `Command` |  |
| `UsesInfrastructure` |  | `bool` |  |

## BuildingBrowserBuildingTypeItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuildingType` |  | `BuildingType` |  |
| `AccessSelf` |  |  |  |
| `CanShowNationalizeBuildingsWindow` |  | `bool` |  |
| `GetAllSameProductionMethodTexture` | `Arg0` |  |  |
| `GetBuildingType` |  |  |  |
| `GetBuildings` |  |  |  |
| `GetBuildingsInCountry` |  |  |  |
| `GetBulkChangeTooltip` | `Arg0` | `CString` |  |
| `GetFilteredAverageProductivity` |  | `CFixedPoint` |  |
| `GetNationalizeBuildingsButtonTooltip` |  | `CString` |  |
| `GetTotalFilteredCashReserves` |  | `CFixedPoint` |  |
| `GetTotalFilteredEmployed` |  | `int64` |  |
| `GetTotalFilteredEmployeeCap` |  | `int64` |  |
| `GetTotalFilteredMaxCashReserves` |  | `CFixedPoint` |  |
| `GetTotalFilteredSizeDesc` |  | `CString` |  |
| `HasAllAutoExpand` |  | `bool` |  |
| `HasAllDisallowedPrivatization` |  | `bool` |  |
| `HasAllForcedPrivatization` |  | `bool` |  |
| `HasAllNoAutoExpand` |  | `bool` |  |
| `HasAllNoPrivatization` |  | `bool` |  |
| `HasAllNoSubsidies` |  | `bool` |  |
| `HasAllPrivatization` |  | `bool` |  |
| `HasAllSameProductionMethod` | `Arg0` | `bool` |  |
| `HasAllSubsidies` |  | `bool` |  |
| `HasMixedAutoExpand` |  | `bool` |  |
| `HasMixedPrivatization` |  | `bool` |  |
| `HasMixedSubsidies` |  | `bool` |  |
| `RemoveAllPrivatization` |  | `Command` |  |
| `Self` |  |  |  |
| `ShowNationalizeBuildingsWindow` |  | `void` |  |
| `ToggleAllAutoExpand` |  | `Command` |  |
| `ToggleAllPrivatization` |  | `Command` |  |
| `ToggleAllSubsidies` |  | `Command` |  |
| `ToggleSwitchProductionMethodMenu` | `Arg0, Arg1` | `void` |  |

## BuildingBrowserPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `GetSearchBar` |  | `SearchBar` |  |
| `AccessSelf` |  |  |  |
| `BuildingTypeFilterAreAllTypesShown` |  | `bool` |  |
| `BuildingTypeFilterAreNoTypesShown` |  | `bool` |  |
| `BuildingTypeFilterHideAllTypes` |  | `void` |  |
| `BuildingTypeFilterIsTypeShown` | `Arg0` | `bool` |  |
| `BuildingTypeFilterShowAllTypes` |  | `void` |  |
| `BuildingTypeFilterToggleShown` | `Arg0` | `void` |  |
| `CanShowNationalizeBuildingsWindow` |  | `bool` |  |
| `Filter` | `Arg0` | `void` |  |
| `GetAllBuildingTypes` |  |  |  |
| `GetAllStates` |  |  |  |
| `GetBuildingBrowserBuildingTypeItems` |  |  |  |
| `GetCountry` |  |  |  |
| `GetFilteredBuildingTypes` |  |  |  |
| `GetNationalizeBuildingsButtonTooltip` |  | `CString` |  |
| `GetPotentialDevelopmentBuildingTypes` |  |  |  |
| `GetPotentialRuralBuildingTypes` |  |  |  |
| `GetPotentialUrbanBuildingTypes` |  |  |  |
| `GetSearchBar` |  |  |  |
| `GetSortedAndFilteredBuildings` |  |  |  |
| `IsAnyFilterActive` |  | `bool` |  |
| `IsBuildingTypeExpanded` | `Arg0` | `bool` |  |
| `IsFilterNo` | `Arg0` | `bool` |  |
| `IsFilterYes` | `Arg0` | `bool` |  |
| `IsFiltered` | `Arg0` | `bool` |  |
| `IsGroupedByBuildingType` |  | `bool` |  |
| `ResetAllFilters` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilterMode` | `Arg0, Arg1` | `void` |  |
| `ShowNationalizeBuildingsWindow` |  | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `StateFilterAreNoStatesShown` |  | `bool` |  |
| `StateFilterHideAllStates` |  | `void` |  |
| `StateFilterIsStateShown` | `Arg0` | `bool` |  |
| `StateFilterShowAllStates` |  | `void` |  |
| `StateFilterToggleShown` | `Arg0` | `void` |  |
| `StateFiltersAreAllStatesShown` |  | `bool` |  |
| `ToggleExpandBuildingType` | `Arg0` | `void` |  |
| `ToggleGroupedByBuildingType` |  | `void` |  |

## BuildingDetailsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` |  | `Building` |  |
| `AccessState` |  | `State` |  |
| `GetBuilding` |  | `Building` |  |
| `GetState` |  | `State` |  |
| `AccessBuilding` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetBuilding` |  |  |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## BuildingGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBuildingTypes` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBuildingGroup` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## BuildingMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` |  | `Building` |  |
| `GetBuilding` |  | `Building` |  |
| `AccessBuilding` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetBuilding` |  |  |  |
| `IsOpenInBuildingPanel` |  | `bool` |  |
| `Self` |  |  |  |

## BuildingOwnership

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetOwnedBuilding` |  | `Building` |  |
| `GetOwnerBuilding` |  | `Building` |  |
| `GetOwnerCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetDividendToOwner` |  | `CFixedPoint` |  |
| `GetLevel` |  | `int32` |  |
| `GetOwnedBuilding` |  |  |  |
| `GetOwnerBuilding` |  |  |  |
| `GetOwnerCountry` |  |  |  |
| `GetOwnershipRatio` |  | `CFixedPoint` |  |
| `GetOwnershipTypeColor` |  | `CVector4f` |  |
| `GetPropertyRatio` |  | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsCountryOwned` |  | `bool` |  |
| `Self` |  |  |  |

## BuildingPotentialMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessState` |  | `State` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetBuildingType` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## BuildingProductionMethodsEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAllSameProductionMethod` | `Arg0` | `ProductionMethod` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `AccessSelf` |  |  |  |
| `GetAllSameProductionMethod` | `Arg0` |  |  |
| `GetAllSameProductionMethodTexture` | `Arg0` |  |  |
| `GetBuildingType` |  |  |  |
| `GetBuildings` |  |  |  |
| `GetBulkChangeTooltip` | `Arg0` | `CString` |  |
| `HasAllAutoExpand` |  | `bool` |  |
| `HasAllNoAutoExpand` |  | `bool` |  |
| `HasAllNoSubsidies` |  | `bool` |  |
| `HasAllSameProductionMethod` | `Arg0` | `bool` |  |
| `HasAllSubsidies` |  | `bool` |  |
| `HasMixedAutoExpand` |  | `bool` |  |
| `HasMixedSubsidies` |  | `bool` |  |
| `IsExpanded` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleAllAutoExpand` |  | `Command` |  |
| `ToggleAllSubsidies` |  | `Command` |  |
| `ToggleExpand` |  | `void` |  |

## BuildingType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuildingGroup` |  | `BuildingGroup` |  |
| `GetBuildingModifier` |  | `Modifier` |  |
| `GetCountryModifier` |  | `Modifier` |  |
| `GetMonopolyCompanyIn` | `Arg0` | `Company` |  |
| `GetMonopolyCountryIn` | `Arg0` | `Country` |  |
| `GetStateModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessProductionMethodGroups` |  |  |  |
| `AccessSelf` |  |  |  |
| `ActivateExpansionLens` |  | `void` |  |
| `CanBeAutoExpanded` |  | `bool` |  |
| `CanBeSubsidized` |  | `bool` |  |
| `CanSwitchOwner` |  | `bool` |  |
| `CreatedByUrbanization` |  | `bool` |  |
| `FiredPopsBecomeRadical` |  | `bool` |  |
| `GeneratesCombatUnits` |  | `bool` |  |
| `GetBackground` |  |  |  |
| `GetBuildingGroup` |  |  |  |
| `GetBuildingGroupName` |  | `CString` |  |
| `GetBuildingKindDesc` | `Arg0` | `CString` |  |
| `GetBuildingModifier` |  |  |  |
| `GetConstructionCosts` |  | `CString` |  |
| `GetCountryModifier` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDiscoveredResourceName` |  | `CString` |  |
| `GetExpansionMissingQualificationsDesc` | `Arg0, Arg1` | `CString` |  |
| `GetExpansionProductivityDesc` | `Arg0, Arg1` | `CString` |  |
| `GetExpansionProductivityImpact` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetExpansionProductivityImpactDesc` | `Arg0, Arg1` | `CString` |  |
| `GetExpansionRevenueImpact` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetExpansionRevenueImpactDesc` | `Arg0, Arg1` | `CString` |  |
| `GetID` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetModifierEffectsAsString` |  | `CString` |  |
| `GetMonopolyCompanyIn` | `Arg0` |  |  |
| `GetMonopolyCountryIn` | `Arg0` |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumAvailableStatesForBuilding` |  | `int32` |  |
| `GetNumLevelsInCountryFormatted` | `Arg0` | `CString` |  |
| `GetNumLevelsInCountryRaw` | `Arg0` | `int32` |  |
| `GetNumLevelsOwnedByCompanyFormatted` | `Arg0` | `CString` |  |
| `GetNumLevelsOwnedByCompanyRaw` | `Arg0` | `int32` |  |
| `GetProductivitySpanDesc` | `Arg0` | `CString` |  |
| `GetRequiredConstruction` |  | `CFixedPoint` |  |
| `GetResetProductionMethodsToStandardTooltip` |  | `CString` |  |
| `GetStandardProductionMethodDesc` | `Arg0` | `CString` |  |
| `GetStateModifier` |  |  |  |
| `GetTabName` |  | `CString` |  |
| `GetToggleMonopolyEffectDesc` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipForBuilding` | `Arg0` | `CString` |  |
| `GetTooltipForState` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUrbanizationProvidedBreakdown` |  | `CString` |  |
| `HasCompanyMonopoly` | `Arg0` | `bool` |  |
| `HasCountryMonopoly` |  | `bool` |  |
| `HasInputGoods` |  | `bool` |  |
| `HasMonopoly` |  | `bool` |  |
| `HasOutputGoods` |  | `bool` |  |
| `HasRequiredPrinciplesInCountry` | `Arg0` | `bool` |  |
| `HasRequiredTechnologiesInCountry` | `Arg0` | `bool` |  |
| `IsAlwaysSelfOwning` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsBuildable` |  | `bool` |  |
| `IsBuildableInAnyState` | `Arg0` | `bool` |  |
| `IsCappedBuilding` |  | `bool` |  |
| `IsConstructionSector` |  | `bool` |  |
| `IsDownsizeable` |  | `bool` |  |
| `IsExpandable` |  | `bool` |  |
| `IsGovernmentFunded` |  | `bool` |  |
| `IsMilitaryBuilding` |  | `bool` |  |
| `IsRural` |  | `bool` |  |
| `IsSelfFunded` |  | `bool` |  |
| `IsSubsistenceBuilding` |  | `bool` |  |
| `IsUnique` |  | `bool` |  |
| `IsUrban` |  | `bool` |  |
| `IsUsingArableLand` |  | `bool` |  |
| `IssDevelopment` |  | `bool` |  |
| `ProvidesUrbanization` |  | `bool` |  |
| `RecruitsCombatUnits` |  | `bool` |  |
| `ResetProductionMethodsToStandard` |  | `Command` |  |
| `Self` |  |  |  |
| `ToggleMonopoly` |  | `Command` |  |
| `UsesInfrastructure` |  | `bool` |  |
