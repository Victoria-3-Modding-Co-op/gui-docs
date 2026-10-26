# Data-binding types: H

Back to the [index](README.md).

## HarvestCondition

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArea` |  | `HarvestConditionArea` |  |
| `GetState` |  | `State` |  |
| `GetType` |  | `HarvestConditionType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDurationDays` |  | `int32` |  |
| `GetEffectDesc` |  | `CString` |  |
| `GetIntensity` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNumStates` |  | `int32` |  |
| `GetRemainingDays` |  | `int32` |  |
| `GetRemainingDuration` |  | `CString` |  |
| `GetRemainingDurationLabel` |  | `CString` |  |
| `GetRemainingDurationRange` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## HarvestConditionArea

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetEpicenter` |  | `HarvestCondition` |  |
| `GetEpicenterRegion` |  | `StateRegion` |  |
| `GetType` |  | `HarvestConditionType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetEffectDesc` |  | `CString` |  |
| `GetHarvestConditions` |  |  |  |
| `GetHarvestConditionsAffecting` | `Arg0` |  |  |
| `GetHarvestConditionsNotAffecting` | `Arg0` |  |  |
| `GetIntensity` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNumStates` |  | `int32` |  |
| `GetRemainingDays` |  | `int32` |  |
| `GetRemainingDuration` |  | `CString` |  |
| `GetRemainingDurationLabel` |  | `CString` |  |
| `GetRemainingDurationRange` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## HarvestConditionList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetNumStatesWithType` | `Arg0` | `int32` |  |
| `GetStatesBreakdown` | `Arg0` | `CString` |  |
| `GetTypes` |  |  |  |
| `Self` |  |  |  |

## HarvestConditionRegionMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetHarvestConditionAreas` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## HarvestConditionType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetEffectDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `Self` |  |  |  |

## Heightmap

Map Editor - Heightmap

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetHeightmapSize` |  | `float` |  |
| `Self` |  |  |  |

## HeightmapPainter

Map Editor - Heightmap Painter options panel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GenerateAndSaveHeightmapQuadTree` |  | `void` |  |
| `GetSmoothAmount` |  | `int32` |  |
| `ReloadHeightmap` |  | `void` |  |
| `Self` |  |  |  |
| `SetSmoothAmount` |  | `void` |  |

## HeightmapPainterMode

Map Editor - Heightmap Painter Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## HeightmapResolution

Map Editor - Heightmap resolution tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearSelection` |  | `void` |  |
| `Decrease` |  | `void` |  |
| `GetRectangleSelect` |  | `bool` |  |
| `Increase` |  | `void` |  |
| `InvertSelection` |  | `void` |  |
| `Is16Bit` |  | `bool` |  |
| `Is8Bit` |  | `bool` |  |
| `ReloadHeightmap` |  | `void` |  |
| `SelectAll` |  | `void` |  |
| `SelectedCount` |  | `int32` |  |
| `Self` |  |  |  |
| `Set16Bit` |  | `void` |  |
| `Set8Bit` |  | `void` |  |

## HighlightManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HighlightAdjacentPorts` | `Arg0` | `void` |  |
| `HighlightBattle` | `Arg0` | `void` |  |
| `HighlightBuilding` | `Arg0` | `void` |  |
| `HighlightCharacter` | `Arg0` | `void` |  |
| `HighlightCivilWarCountry` | `Arg0` | `void` |  |
| `HighlightCountry` | `Arg0` | `void` |  |
| `HighlightCountryCreation` | `Arg0` | `void` |  |
| `HighlightCountryFormation` | `Arg0` | `void` |  |
| `HighlightFront` | `Arg0` | `void` |  |
| `HighlightGeographicRegion` | `Arg0` | `void` |  |
| `HighlightGoods` | `Arg0` | `void` |  |
| `HighlightHQ` | `Arg0` | `void` |  |
| `HighlightHarvestConditionArea` | `Arg0` | `void` |  |
| `HighlightHarvestConditionType` | `Arg0` | `void` |  |
| `HighlightInvasion` | `Arg0` | `void` |  |
| `HighlightMarket` | `Arg0` | `void` |  |
| `HighlightMilitaryFormation` | `Arg0` | `void` |  |
| `HighlightMilitaryFormationSupplyNetwork` | `Arg0` | `void` |  |
| `HighlightNavalBattle` | `Arg0` | `void` |  |
| `HighlightNavalMissionSeaRegions` | `Arg0` | `void` |  |
| `HighlightPoliticalMovement` | `Arg0` | `void` |  |
| `HighlightPowerBloc` | `Arg0` | `void` |  |
| `HighlightShippingLane` | `Arg0` | `void` |  |
| `HighlightState` | `Arg0` | `void` |  |
| `HighlightStateOccupation` | `Arg0, Arg1` | `void` |  |
| `HighlightStateRegion` | `Arg0` | `void` |  |
| `HighlightStateTrait` | `Arg0` | `void` |  |
| `HighlightStrait` | `Arg0` | `void` |  |
| `HighlightStrategicObjective` | `Arg0` | `void` |  |
| `HighlightStrategicRegion` | `Arg0` | `void` |  |
| `HighlightSupplyNetwork` | `Arg0` | `void` |  |
| `HighlightTechnology` | `Arg0` | `void` |  |
| `HighlightTheaters` | `Arg0` | `void` |  |
| `RemoveHighlight` |  | `void` |  |
| `Self` |  |  |  |

## HistoryViewer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetEntryName` | `Arg0` | `CString` |  |
| `IsEntryAhead` | `Arg0` | `bool` |  |
| `IsEntryCurrent` | `Arg0` | `bool` |  |
| `IsEntryExecutable` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetEntryCurrent` | `Arg0` | `void` |  |

## HomelandMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCulture` |  | `Culture` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetCulture` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## Hq

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCombatUnitsIcon` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFlag` |  | `CString` |  |
| `GetNameNoFlagNoConcept` |  | `CString` |  |
| `GetStates` |  |  |  |
| `GetStationSelectedFormationsCommand` |  | `Command` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsLandHQ` |  | `bool` |  |
| `IsNavalHQ` |  | `bool` |  |
| `IsTemporaryHQ` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsZoomingToHQ` |  | `bool` |  |
| `Self` |  |  |  |
| `ZoomToHQ` |  | `void` |  |

## HQMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHQ` |  | `Hq` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## HQMovementMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHQ` |  | `Hq` |  |
| `AccessSelf` |  |  |  |
| `CanStationSelectedFormationsInHQ` |  | `bool` |  |
| `CanUseNavalTransportAlternative` |  | `bool` |  |
| `GetHQ` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetPresentFormationsBreakdown` |  | `CString` |  |
| `GetSelectedFormationsInvolvementChangeDesc` |  | `CString` |  |
| `GetTravelTimeBreakdown` |  | `CString` |  |
| `IsAllSelectedFormationsLocation` |  | `bool` |  |
| `IsAllSelectedFormationsTarget` |  | `bool` |  |
| `IsAnySelectedFormationsLocation` |  | `bool` |  |
| `IsAnySelectedFormationsTarget` |  | `bool` |  |
| `RequiresNavalTransportForSelectedFormations` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowTransportPlannerForSelectedFormation` |  | `void` |  |
