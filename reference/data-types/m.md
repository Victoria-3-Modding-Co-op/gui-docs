# Data-binding types: M

Back to the [index](README.md).

## MapContentEditorMode

Map Editor - Map Content Editor Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## MapContentEditorOptions

Map Editor - Map Content Options Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ApplyChanges` |  | `void` |  |
| `CanApplyChanges` |  | `bool` |  |
| `CanErase` |  | `bool` |  |
| `CanMakeGroupingOperation` |  | `bool` |  |
| `CurrentLayerHasChanges` |  | `bool` |  |
| `DiscardChanges` |  | `void` |  |
| `GetAddToGroupModeDescription` |  | `CString` |  |
| `GetApplyButtonDescription` |  | `CString` |  |
| `GetEraserDescription` |  | `CString` |  |
| `GetMapContentSelectionModeDescription` |  | `CString` |  |
| `GetPaintModeDescription` |  | `CString` |  |
| `GetRemoveFromGroupModeDescription` |  | `CString` |  |
| `IsAddToGroupMode` |  | `bool` |  |
| `IsAddToGroupModeAllowed` |  | `bool` |  |
| `IsCurrentLayerPixelBased` |  | `bool` |  |
| `IsEraserMode` |  | `bool` |  |
| `IsEraserModeAllowed` |  | `bool` |  |
| `IsMapContentSelectionMode` |  | `bool` |  |
| `IsMapContentSelectionModeAllowed` |  | `bool` |  |
| `IsPaintMode` |  | `bool` |  |
| `IsPaintModeAllowed` |  | `bool` |  |
| `IsPaintingAllowed` |  | `bool` |  |
| `IsRemoveFromGroupMode` |  | `bool` |  |
| `IsRemoveFromGroupModeAllowed` |  | `bool` |  |
| `Self` |  |  |  |
| `SetAddToGroupMode` |  | `void` |  |
| `SetEraserMode` |  | `void` |  |
| `SetMapContentSelectionMode` | `Arg0` | `void` |  |
| `SetPaintMode` |  | `void` |  |
| `SetRemoveFromGroupMode` |  | `void` |  |

## MapContentEditorViewport

Map Editor - Map Content Viewport

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTooltip` |  | `GuiEditorTooltip` |  |
| `AccessSelf` |  |  |  |
| `CancelPropertyPainting` |  | `void` |  |
| `GetPropertyPaintingModeDesc` |  | `CString` |  |
| `IsInPropertyPaintingMode` |  | `bool` |  |
| `Self` |  |  |  |

## MapContentEntryDesc

Map Editor - Map Content Layer Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ContainsErrors` |  | `bool` |  |
| `GetErrorMessage` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetUniqueId` |  | `int32` |  |
| `IsDone` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## MapContentLayerDesc

Map Editor - Map Content Layer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## MapContentPanel

Map Editor - Map Content Layer List

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanCreateNewEntry` |  | `bool` |  |
| `CanDeleteAnySelectedEntry` |  | `bool` |  |
| `CreateNewEntry` |  | `void` |  |
| `DeleteSelectedEntries` |  | `void` |  |
| `GetCreateNewEntryTooltip` |  | `CString` |  |
| `GetDeleteSelectedEntriesTooltip` |  | `CString` |  |
| `Self` |  |  |  |

## MapContentPropertyGroup

Map Editor - Map Content Property Group

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsExpanded` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpanded` |  | `void` |  |

## MapContentPropertyGroupsGui

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanActivatePropertyPaintingMode` |  | `bool` |  |
| `IsInPropertyPaintingModeForBool` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForCColor` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForCString` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForColor` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForEnum` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForFloat` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForInt` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForString` | `Arg0` | `bool` |  |
| `IsInPropertyPaintingModeForUint` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `TogglePropertyPaintingModeBool` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeCColor` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeCString` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeColor` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeEnum` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeFloat` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeInt` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeString` | `Arg0` | `void` |  |
| `TogglePropertyPaintingModeUint` | `Arg0` | `void` |  |

## MapContentSelector

Map Editor - Map Content Selection

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetErrorsCount` |  | `int32` |  |
| `GetSelectedCount` |  | `int32` |  |
| `IsAllSelectedDone` |  | `bool` |  |
| `IsAllSelectedHasErrors` |  | `bool` |  |
| `IsShowProgress` |  | `bool` |  |
| `Self` |  |  |  |
| `SetSelectedDone` | `Arg0` | `void` |  |
| `SetShowProgress` | `Arg0` | `void` |  |

## MapContentSelectorGui

Map Editor - Map Content Selection Interface

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearEntriesFilter` |  | `void` |  |
| `GetCurrentLayerIndex` |  | `CVector2i` |  |
| `GetEntriesFilter` |  | `CString` |  |
| `GetEntriesWithErrorsCount` |  | `int32` |  |
| `GetSelectedEntriesCount` |  | `int32` |  |
| `IsAllSelectedDone` |  | `bool` |  |
| `IsAllSelectedError` |  | `bool` |  |
| `IsFilterErrors` |  | `bool` |  |
| `IsShowProgress` |  | `bool` |  |
| `OnEntrySelected` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetCurrentLayerIndex` |  | `void` |  |
| `SetEntriesFilter` |  | `void` |  |
| `SetFilterErrors` | `Arg0` | `void` |  |
| `SetSelectedDone` | `Arg0` | `void` |  |
| `SetShowProgress` | `Arg0` | `void` |  |

## MapEditor

Map Editor - Main

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessUndoHistoryViewerClient` |  | `UndoHistoryViewerClient` |  |
| `GetUndoHistoryViewerClient` |  | `UndoHistoryViewerClient` |  |
| `AccessSelf` |  |  |  |
| `AccessUndoHistoryViewerClient` |  |  |  |
| `CanToggleMaterialVisibility` |  | `bool` |  |
| `Exit` |  | `void` |  |
| `ExportTool` |  | `void` |  |
| `GetReferenceOverlayVisibility` |  | `bool` |  |
| `GetTerrainColorMapVisibility` |  | `bool` |  |
| `GetUndoHistoryViewerClient` |  |  |  |
| `ImportTool` |  | `void` |  |
| `IsAutoSaving` |  | `bool` |  |
| `IsDynamicTerrainMaterialFeatureTogglable` |  | `bool` |  |
| `IsDynamicTerrainMaterialSupported` |  | `bool` |  |
| `IsEnabled` |  | `bool` |  |
| `IsSavable` |  | `bool` |  |
| `ReloadHeightmap` |  | `void` |  |
| `Save` |  | `void` |  |
| `SaveAll` |  | `void` |  |
| `SaveAs` |  | `void` |  |
| `Self` |  |  |  |
| `SetDynamicTerrainMaterialSupported` | `Arg0` | `void` |  |
| `SetReferenceOverlayVisibility` | `Arg0` | `void` |  |
| `ToggleTerrainColorMapVisibility` |  | `void` |  |

## MapEditorGui

Map Editor - Main GUI

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessLogViewer` |  | `LogViewer` | Access Central Log Viewer |
| `AccessLogViewer` |  |  | Access Central Log Viewer |
| `AccessSelf` |  |  |  |
| `GetReferenceOverlayOpacity` |  | `float` |  |
| `Self` |  |  |  |
| `SetReferenceOverlayOpacity` |  | `void` |  |
| `ShowSettingsWindow` |  | `void` |  |
| `ToggleBordersSettingsOptions` |  | `void` |  |
| `ToggleReferenceOverlayOptions` |  | `void` |  |

## MapEditorLayerBorder

Map Editor - Map Editor Layer Border

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetLayerIndex` |  | `int32` |  |
| `IsForceShown` |  | `bool` |  |
| `Self` |  |  |  |
| `SetForceShown` | `Arg0` | `void` |  |

## MapEditorLayerBorderDockable

Map Editor - Map Editor Layer Border Settings Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetLayerName` | `Arg0` | `CString` |  |
| `Self` |  |  |  |

## MapInteraction

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapInteractionManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HasAnyActiveMapInteraction` |  | `bool` |  |
| `IsActiveMapInteraction` | `Arg0` | `bool` |  |
| `ResetActiveMapInteraction` |  | `void` |  |
| `Self` |  |  |  |
| `ShowMapInteractionNotification` |  | `void` |  |

## MapListActivateConscriptionCenterOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHQ` |  | `Hq` |  |
| `GetMilitaryFormation` |  | `MilitaryFormation` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetConscriptionLimit` |  | `int32` |  |
| `GetHQ` |  |  |  |
| `GetMilitaryFormation` |  |  |  |
| `GetNumExpectedConscripts` |  | `int32` |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## MapListActivateConscriptionCenterPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListBuildingOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` |  | `Building` |  |
| `AccessMilitaryFormation` |  | `MilitaryFormation` |  |
| `AccessState` |  | `State` |  |
| `GetBuilding` |  | `Building` |  |
| `GetCombatUnitType` |  | `CombatUnitType` |  |
| `GetMilitaryFormation` |  | `MilitaryFormation` |  |
| `GetState` |  | `State` |  |
| `AccessBuilding` |  |  |  |
| `AccessMilitaryFormation` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetBuilding` |  |  |  |
| `GetCombatUnitType` |  |  |  |
| `GetConstructionNeeded` |  | `CFixedPoint` |  |
| `GetMilitaryFormation` |  |  |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## MapListBuildingPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuildingType` |  | `BuildingType` |  |
| `AccessSelf` |  |  |  |
| `GetBuildingType` |  |  |  |
| `HasFilter` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetFilter` | `Arg0` | `void` |  |

## MapListColonyOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStateRegion` |  | `StateRegion` |  |
| `AccessSelf` |  |  |  |
| `GetRegion` |  | `CString` |  |
| `GetState` |  | `CString` |  |
| `GetStateRegion` |  |  |  |
| `Self` |  |  |  |

## MapListCountriesPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListCountryOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListDecreeOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetCost` |  | `CFixedPoint` |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## MapListDecreePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDecreeType` |  | `DecreeType` |  |
| `AccessSelf` |  |  |  |
| `GetDecreeType` |  |  |  |
| `Self` |  |  |  |

## MapListDeployMilitaryFormationToFrontOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFront` |  | `Front` |  |
| `AccessSelf` |  |  |  |
| `GetFront` |  |  |  |
| `Self` |  |  |  |

## MapListDeployMilitaryFormationToFrontPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListDiploActionOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetDiplomaticAction` |  |  |  |
| `Self` |  |  |  |

## MapListHarvestConditionAreasPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListHarvestConditionOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArea` |  | `HarvestConditionArea` |  |
| `AccessSelf` |  |  |  |
| `GetArea` |  |  |  |
| `Self` |  |  |  |

## MapListInterestGroupOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `AccessInterestGroup` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetInterestGroup` |  |  |  |
| `Self` |  |  |  |

## MapListInterestGroupsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListMarketOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMarket` |  | `Market` |  |
| `GetMarket` |  | `Market` |  |
| `AccessMarket` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetMarket` |  |  |  |
| `Self` |  |  |  |

## MapListMarketsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListMilitaryFormationOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHQ` |  | `Hq` |  |
| `AccessSelf` |  |  |  |
| `CanTravelTo` |  | `bool` |  |
| `GetHQ` |  |  |  |
| `GetSupplyShipPredictionDelta` |  | `int32` |  |
| `GetTravelDays` |  | `int32` |  |
| `HasHQ` |  | `bool` |  |
| `RequiresNavalTransport` |  | `bool` |  |
| `Self` |  |  |  |

## MapListMilitaryFormationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListNavalMissionOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSeaRegion` |  | `Province` |  |
| `AccessSelf` |  |  |  |
| `CanTravelTo` |  | `bool` |  |
| `GetNumMissions` |  | `int32` |  |
| `GetSeaRegion` |  |  |  |
| `GetSupplyShipPredictionDelta` |  | `int32` |  |
| `GetTravelDays` |  | `int32` |  |
| `HasMultipleMissions` |  | `bool` |  |
| `Self` |  |  |  |

## MapListNavalMissionPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuildingData` |  | `MapListBuildingOption` |  |
| `AccessInterestGroupData` |  | `MapListInterestGroupOption` |  |
| `AccessMarketData` |  | `MapListMarketOption` |  |
| `AccessPowerBlocData` |  | `MapListPowerBlocOption` |  |
| `AccessStateData` |  | `MapListStateOption` |  |
| `AccessStrategicRegionData` |  | `MapListStrategicRegionOption` |  |
| `GetActivateConscriptionCenterData` |  | `MapListActivateConscriptionCenterOption` |  |
| `GetBuildingData` |  | `MapListBuildingOption` |  |
| `GetColonyData` |  | `MapListColonyOption` |  |
| `GetCountryData` |  | `MapListCountryOption` |  |
| `GetDecreeData` |  | `MapListDecreeOption` |  |
| `GetDestinationData` |  | `MapListMilitaryFormationOption` |  |
| `GetDiploActionData` |  | `MapListDiploActionOption` |  |
| `GetFrontData` |  | `MapListDeployMilitaryFormationToFrontOption` |  |
| `GetHarvestConditionAreaData` |  | `MapListHarvestConditionOption` |  |
| `GetInterestGroupData` |  | `MapListInterestGroupOption` |  |
| `GetMarketData` |  | `MapListMarketOption` |  |
| `GetMilitaryFormationData` |  | `MapListMilitaryFormationOption` |  |
| `GetNavalMissionData` |  | `MapListNavalMissionOption` |  |
| `GetPowerBlocData` |  | `MapListPowerBlocOption` |  |
| `GetStateData` |  | `MapListStateOption` |  |
| `GetStrategicRegionData` |  | `MapListStrategicRegionOption` |  |
| `AccessSelf` |  |  |  |
| `CanClick` |  | `bool` |  |
| `GetBackgroundStatusFrame` |  | `int32` |  |
| `GetIconStatusFrame` |  | `int32` |  |
| `GetSelectionIndex` |  | `uint64` |  |
| `GetTitle` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `IsMapTargetHighlighted` |  | `bool` |  |
| `OnClick` |  | `void` |  |
| `OnMouseEnter` |  | `void` |  |
| `OnMouseLeave` |  | `void` |  |
| `OnRightClick` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldShowStatusIcon` |  | `bool` |  |

## MapListPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFailedOptions` |  |  |  |
| `AccessInvalidOptions` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessValidOptions` |  |  |  |
| `GetBelowTitleText` |  | `CString` |  |
| `GetTitle` |  | `CString` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## MapListPanelManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CloseCurrentPanel` |  | `void` |  |
| `HasCurrentInteraction` |  | `bool` |  |
| `IsAvailable` |  | `bool` |  |
| `IsShowingFailedOptions` |  | `bool` |  |
| `IsShowingInvalidOptions` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `OpenCurrentPanel` |  | `void` |  |
| `ResetActiveMapInteraction` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleCurrentPanel` |  | `void` |  |
| `ToggleFailedOptions` |  | `void` |  |
| `ToggleInvalidOptions` |  | `void` |  |

## MapListPowerBlocInvitationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDiplomaticAction` | `Arg0` | `DiplomaticAction` |  |
| `GetPowerBloc` |  | `PowerBloc` |  |
| `AccessSelf` |  |  |  |
| `GetDiplomaticAction` | `Arg0` |  |  |
| `GetPowerBloc` |  |  |  |
| `Self` |  |  |  |

## MapListPowerBlocOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPowerBloc` |  | `PowerBloc` |  |
| `GetPowerBloc` |  | `PowerBloc` |  |
| `AccessPowerBloc` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetPowerBloc` |  |  |  |
| `Self` |  |  |  |

## MapListPowerBlocsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDiplomaticAction` | `Arg0` | `DiplomaticAction` |  |
| `AccessSelf` |  |  |  |
| `GetDiplomaticAction` | `Arg0` |  |  |
| `Self` |  |  |  |

## MapListStateOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessState` |  | `State` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## MapListStatePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapListStrategicRegionOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessStrategicRegion` |  | `StrategicRegion` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `AccessSelf` |  |  |  |
| `AccessStrategicRegion` |  |  |  |
| `GetStrategicRegion` |  |  |  |
| `Self` |  |  |  |

## MapListStrategicRegionsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MapMode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## MapModeList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedMapMode` |  | `MapMode` |  |
| `AccessSelf` |  |  |  |
| `GetContextName` |  | `CString` |  |
| `GetMapModes` |  |  |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `IsSelectedByKey` | `Arg0` | `bool` |  |
| `Select` | `Arg0` | `void` |  |
| `SelectByKey` | `Arg0` | `void` |  |
| `SelectDefault` |  | `void` |  |
| `Self` |  |  |  |

## MapNotification

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetText` |  | `CString` |  |
| `Self` |  |  |  |

## MapObjectMask

Map Editor - Map Object Mask

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetGeneratorCount` |  | `int32` |  |
| `GetGeneratorNames` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTextValidator` |  |  |  |
| `GetThumbnail` |  |  |  |
| `IsModified` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |
| `SetModified` |  | `void` |  |
| `SetName` |  | `void` |  |
| `SetSelected` |  | `void` |  |

## MapObjectPainter

Map Editor - Map Object Painter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextValidator` |  |  |  |
| `MarkAllMasksModified` |  | `void` |  |
| `MaskList` |  |  |  |
| `Self` |  |  |  |

## MapObjectPainterMode

Map Editor - Map Object Painter Mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## MapObjectPainterOptions

Map Editor - Map Object Painter Options

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBlurThresholdCtx` |  | `BlurThreshold` |  |
| `AccessBlurThresholdCtx` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetPaintValue` |  | `float` |  |
| `IsCurrentBlendMode` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetBlendMode` | `Arg0` | `void` |  |
| `SetPaintValue` |  | `void` |  |
| `SetPaintValueStr` |  | `void` |  |

## MapObjectTool

Map Editor - Map Object Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTooltip` |  | `GuiEditorTooltip` |  |
| `MoveTool` |  | `MoveTool` |  |
| `SelectTool` |  | `SelectTool` |  |
| `AccessSelf` |  |  |  |
| `IsCreateTool` |  | `bool` |  |
| `IsMovingObjects` |  | `bool` |  |
| `IsRotatingObjects` |  | `bool` |  |
| `IsScalingObjects` |  | `bool` |  |
| `IsSelectionModeMapContent` |  | `bool` |  |
| `IsSelectionModeObjects` |  | `bool` |  |
| `RotateRandom` |  | `void` |  |
| `Self` |  |  |  |
| `SetCreateTool` |  | `void` |  |
| `SetMovingObjects` |  | `void` |  |
| `SetRotatingObjects` |  | `void` |  |
| `SetScalingObjects` |  | `void` |  |
| `SetSelectionModeMapContent` |  | `void` |  |
| `SetSelectionModeObjects` |  | `void` |  |

## Market

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMarketCapital` |  | `State` |  |
| `GetFoodSecurity` |  | `FoodSecurity` |  |
| `GetFoodSecurityFilter` |  | `FoodSecurityFilter` |  |
| `GetMarketCapital` |  | `State` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetOwner` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessLocalGoods` | `Arg0` |  |  |
| `AccessLocalPrices` | `Arg0` |  |  |
| `AccessMarketCapital` |  |  |  |
| `AccessMarketGoods` | `Arg0` |  |  |
| `AccessMarketGoodsSortedOnExports` | `Arg0` |  |  |
| `AccessMarketGoodsSortedOnImports` | `Arg0` |  |  |
| `AccessMarketStates` |  |  |  |
| `AccessParticipants` |  |  |  |
| `AccessSelf` |  |  |  |
| `CalcSupplyToDemandRatio` | `Arg0` | `CFixedPoint` |  |
| `CanTradeGoods` | `Arg0` | `bool` |  |
| `GetBalance` |  | `CFixedPoint` |  |
| `GetBalanceDesc` |  | `CString` |  |
| `GetCountryExportedAmount` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetCountryImportedAmount` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetCountryTradeCapacity` | `Arg0` | `int32` |  |
| `GetCountryTradeCapacityBalance` | `Arg0` | `int32` |  |
| `GetCountryTradeCapacityDesc` | `Arg0` | `CString` |  |
| `GetCountryTradeCapacityUsage` | `Arg0` | `int32` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetEmptyFilters` |  |  |  |
| `GetExportAdvantage` | `Arg0` | `CFixedPoint` |  |
| `GetExportedAmount` | `Arg0` | `CFixedPoint` |  |
| `GetExportedAmountToMarket` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetExports` |  |  |  |
| `GetGDPContributionPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetGoodsSortedByBalance` |  |  |  |
| `GetGoodsWithShortage` |  |  |  |
| `GetImportAdvantage` | `Arg0` | `CFixedPoint` |  |
| `GetImportedAmount` | `Arg0` | `CFixedPoint` |  |
| `GetImportedAmountFromMarket` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetImports` |  |  |  |
| `GetMarketCapital` |  |  |  |
| `GetMarketGDPValue` |  | `CFixedPoint` |  |
| `GetMarketSharePercentageFor` | `Arg0` | `CFixedPoint` |  |
| `GetMaxImbalance` |  | `CFixedPoint` |  |
| `GetMaxImbalanceScaledByBasePrice` |  | `CFixedPoint` |  |
| `GetModifier` |  |  |  |
| `GetModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoFormattingIncludingStatus` |  | `CString` |  |
| `GetOwner` |  |  |  |
| `GetRelativeExportAdvantage` | `Arg0` | `CFixedPoint` |  |
| `GetRelativeExportAdvantageDesc` | `Arg0` | `CString` |  |
| `GetRelativeImportAdvantage` | `Arg0` | `CFixedPoint` |  |
| `GetRelativeImportAdvantageDesc` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTopGoodsByHighestBalance` | `Arg0` |  |  |
| `GetTopGoodsByLowestBalance` | `Arg0` |  |  |
| `GetTotalBuyOrders` |  | `CFixedPoint` |  |
| `GetTotalExportedAmount` |  | `CFixedPoint` |  |
| `GetTotalImportedAmount` |  | `CFixedPoint` |  |
| `GetTotalSellOrders` |  | `CFixedPoint` |  |
| `GetTradeSurplus` |  | `CFixedPoint` |  |
| `GetTradeSurplusBreakdown` |  | `CString` |  |
| `HasAnyGoodsShortage` |  | `bool` |  |
| `HasBuildingGoodsShortage` | `Arg0` | `bool` |  |
| `HasGoodsShortage` | `Arg0` | `bool` |  |
| `HasPopGoodsShortage` | `Arg0` | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsCapitalMarket` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsSame` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `RestoreSort` |  | `void` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |
| `SortStates` | `Arg0` | `void` |  |
| `TogglePinInOutliner` |  | `void` |  |

## MarketGoods

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `GetMarket` |  | `Market` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBreakdownOfBuildingsAffectedByShortage` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetGoods` |  |  |  |
| `GetIDString` |  | `CString` |  |
| `GetMarket` |  |  |  |
| `GetNumBuildingsAffectedByShortage` |  | `int32` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## MarketPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFilteredGoodsList` | `Arg0` | `GoodsList` |  |
| `GetHarvestConditionList` | `Arg0` | `HarvestConditionList` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `GetMarket` |  | `Market` |  |
| `GetSearchBar` |  | `SearchBar` |  |
| `AccessSelf` |  |  |  |
| `Filter` | `Arg0` | `void` |  |
| `GetFilters` |  |  |  |
| `GetSearchBar` |  |  |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## MarketsMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAnyMarket` |  | `Market` |  |
| `AccessSelf` |  |  |  |
| `GetAnyMarket` |  |  |  |
| `GetGoodsListCount` |  | `int32` |  |
| `GetMarketsMarkerListItems` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `OpenMarketPanel` |  | `void` |  |
| `Self` |  |  |  |

## MarketsMarkerListItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMarket` |  | `Market` |  |
| `AccessSelf` |  |  |  |
| `GetPanelDescription` |  | `CString` |  |
| `Self` |  |  |  |

## MaskEntry

Map Editor - Texture Mask

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `Self` |  |  |  |

## MaskManagerEntry

Map Editor - Mask Painter - Mask Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `IsLocked` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |
| `SetLocked` | `Arg0` | `void` |  |
| `SetSelected` | `Arg0` | `void` |  |

## MaskPainterDynamicTerrain

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearSelected` |  | `void` |  |
| `GetTerrainType` |  | `CString` |  |
| `GetTerrainValue` |  | `float` |  |
| `HasAnySelectedSetTerrainType` |  | `bool` |  |
| `OpenDatabase` |  | `void` |  |
| `Self` |  |  |  |
| `SetTerrainValue` |  | `void` |  |
| `SetTerrainValueStr` |  | `void` |  |

## MaskPainterManager

Map Editor - Mask Painter Manager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanModify` |  | `bool` |  |
| `ClearFilter` |  | `void` |  |
| `GetFilter` |  | `CString` |  |
| `GetSelectedMaskDesc` |  | `CString` |  |
| `IsAnyMaskSelected` |  | `bool` |  |
| `IsSelectedMaskTypeDeveloper` |  | `bool` |  |
| `IsSelectedMaskTypeLocal` |  | `bool` |  |
| `OnClear` |  | `void` |  |
| `OnClone` |  | `void` |  |
| `OnDelete` |  | `void` |  |
| `OnNew` |  | `void` |  |
| `OnRename` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilter` |  | `void` |  |
| `SetSelectedMaskDesc` |  | `void` |  |
| `ToggleMaskTypeDeveloper` |  | `void` |  |
| `ToggleMaskTypeLocal` |  | `void` |  |

## MaskPainterMapContentPanel

Map Editor - Mask Painter Map Content Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MaskPainterMode

Map Editor - Mask Painter mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## MaskPainterTool

Map Editor - Mask Painter Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsEraserMode` |  | `bool` |  |
| `IsEyeDropperMode` |  | `bool` |  |
| `IsMapContentSelectionMode` |  | `bool` |  |
| `IsPaintMode` |  | `bool` |  |
| `Self` |  |  |  |
| `SetEraserMode` |  | `void` |  |
| `SetEyeDropperMode` | `Arg0` | `void` |  |
| `SetMapContentSelectionMode` | `Arg0` | `void` |  |
| `SetPaintMode` |  | `void` |  |

## MaskPainterViewport

Map Editor - Mask Painter Viewport

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTooltip` |  | `GuiEditorTooltip` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## Material

Map Editor - Material Painter - Material

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDiffuseTexture` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetThumbnail` |  |  |  |
| `IsHighlighted` |  | `bool` |  |
| `IsLocked` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleHighlight` |  | `void` |  |
| `ToggleLocked` |  | `void` |  |
| `ToggleSelected` |  | `void` |  |

## MaterialBrowser

Map Editor - Material Browser

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentMaterial` |  | `Material` |  |
| `AccessSelf` |  |  |  |
| `Apply` |  | `void` |  |
| `Cancel` |  | `void` |  |
| `GetCurrentMaterialsList` |  |  |  |
| `GetSearchFilter` |  | `CUTF8String` |  |
| `IsAnyMaterialSelected` |  | `bool` |  |
| `IsMaterialDisabled` | `Arg0` | `bool` |  |
| `IsMaterialSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetSearchFilter` |  | `void` |  |
| `ToggleMaterialSelected` | `Arg0` | `void` |  |

## MaterialEntry

Map Editor - Material Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMaterial` |  | `Material` |  |
| `AccessSelf` |  |  |  |
| `GetRawValue` |  | `int32` |  |
| `GetValue` |  | `float` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## MaterialMix

Map Editor - Material Mix

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMaterials` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanAddMaterialEntry` |  | `bool` |  |
| `GetMaterials` |  |  |  |
| `GetMaterialsCount` |  | `int32` |  |
| `GetName` |  | `CUTF8String` |  |
| `IsPersistent` |  | `bool` |  |
| `Self` |  |  |  |
| `SetValue` | `Arg0` | `void` |  |
| `TogglePersistence` |  | `void` |  |

## MaterialMixBrush

Map Editor - Material Mix Brush

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHoverSample` |  | `MaterialsSample` |  |
| `AccessSamples` |  |  |  |
| `AccessSelf` |  |  |  |
| `ChangeSampleEntryComposition` | `Arg0, Arg1` | `void` |  |
| `Delete` | `Arg0` | `void` |  |
| `EndSampleCompositionEdit` | `Arg0` | `void` |  |
| `IsSampling` |  | `bool` |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `RenameSample` | `Arg0` | `void` | Map Editor - Rename Material Sample Dialog |
| `Samples` |  |  |  |
| `Self` |  |  |  |
| `StartSampleCompositionEdit` | `Arg0` | `void` |  |
| `ToggleSampleEntryLock` | `Arg0, Arg1` | `void` |  |
| `ToggleSamplePersistence` | `Arg0` | `void` |  |
| `ToggleSelected` | `Arg0` | `void` |  |

## MaterialMixEntry

Map Editor - Material Mix

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMaterial` |  | `Material` |  |
| `GetMaterial` |  | `Material` |  |
| `AccessSelf` |  |  |  |
| `GetPercentageValue` |  | `float` |  |
| `GetValue` |  | `float` |  |
| `GetValueAsText` |  | `CString` |  |
| `IsLocked` |  | `bool` |  |
| `Self` |  |  |  |
| `SetPercentageValue` | `Arg0` | `void` |  |
| `ToggleLocked` |  | `void` |  |

## MaterialPaintingMode

Map Editor - Map texture material painting mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBlurThresholdCtx` |  | `BlurThreshold` |  |
| `AccessBlurThresholdCtx` |  |  |  |
| `AccessSelf` |  |  |  |
| `FocusCameraOnError` |  | `void` |  |
| `IsBlurSelected` |  | `bool` |  |
| `IsBrushSettingsLock` |  | `bool` |  |
| `IsEraserSelected` |  | `bool` |  |
| `IsEyeDropperSelected` |  | `bool` |  |
| `IsPainterSelected` |  | `bool` |  |
| `IsPaintingAllowed` |  | `bool` |  |
| `IsSearchingForError` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsTrimWhilePainting` |  | `bool` |  |
| `IsTrimmerSelected` |  | `bool` |  |
| `SelectBlur` |  | `void` |  |
| `SelectEraser` |  | `void` |  |
| `SelectEyeDropper` |  | `void` |  |
| `SelectPainter` |  | `void` |  |
| `SelectTrimmer` |  | `void` |  |
| `Self` |  |  |  |
| `SetBrushSettingsLock` | `Arg0` | `void` |  |
| `SetTrimWhilePainting` | `Arg0` | `void` |  |

## Materials

Map Editor - Material Painter - Materials

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetList` |  |  |  |
| `List` |  |  |  |
| `SelectFirst` |  | `void` |  |
| `SelectLast` |  | `void` |  |
| `SelectNext` |  | `void` |  |
| `SelectPrevious` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleHighlight` |  | `void` |  |
| `ToggleLocked` |  | `void` |  |

## MaterialsSample

Map Editor - Materials Sample

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Entries` |  |  |  |
| `GetX` |  | `int32` |  |
| `GetY` |  | `int32` |  |
| `Self` |  |  |  |

## MeshImporter

Mesh Importer Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMaterialImportSettings` |  | `MeshImporterMaterials` |  |
| `AccessUndoer` |  | `UndoStack` |  |
| `AccessMaterialImportSettings` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessUndoer` |  |  |  |
| `EditShaderSets` |  | `void` |  |
| `GetInputFileName` |  | `CString` |  |
| `GetLogEntryCountCritical` |  | `int32` |  |
| `GetLogEntryCountError` |  | `int32` |  |
| `GetLogEntryCountInfo` |  | `int32` |  |
| `GetLogEntryCountWarning` |  | `int32` |  |
| `GetSettingsFileName` |  | `CString` |  |
| `ImportCurrentlySelected` |  | `void` |  |
| `IsAutoSaveOnImport` |  | `bool` |  |
| `IsBrowserViewOpen` |  | `bool` |  |
| `IsLogViewOpen` |  | `bool` |  |
| `IsMeshLodded` |  | `bool` |  |
| `IsSettingsDifferentThanDiskFile` |  | `bool` |  |
| `IsSettingsDiskFileExist` |  | `bool` |  |
| `IsTargetMesh2` |  | `bool` |  |
| `SaveSettings` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleAutoSaveOnImport` |  | `void` |  |
| `ToggleBrowserView` |  | `void` |  |
| `ToggleLogView` |  | `void` |  |

## MeshImporterBrowser

Mesh Importer Browser Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearQueue` |  | `void` |  |
| `DeselectAllFiles` |  | `void` |  |
| `GetAllFiles` |  |  |  |
| `GetQueuedFiles` |  |  |  |
| `ImportAllInQueue` |  | `void` |  |
| `ReloadAllFiles` |  | `void` |  |
| `SelectAllFiles` |  | `void` |  |
| `Self` |  |  |  |

## MeshImporterBrowserEntry

Mesh Importer Browser File Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFileDescription` |  | `CString` |  |
| `GetFileName` |  |  |  |
| `GetFullPath` |  |  |  |
| `IsInQueue` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsSettingsDifferentThanDiskFile` |  | `bool` |  |
| `IsSettingsDiskFileExist` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleQueue` |  | `void` |  |
| `ToggleSelect` |  | `void` |  |

## MeshImporterMaterialEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDetailsDescription` |  | `CString` |  |
| `GetMaterialIndex` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetNumberGeometriesUsingMaterial` |  | `int32` |  |
| `InjectPropertyList` | `Arg0, Arg1` | `void` |  |
| `IsCollision` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleCollision` |  | `void` |  |

## MeshImporterMaterials

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMaterialEntries` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetMaterialEntries` |  |  |  |
| `Self` |  |  |  |

## MessageFeedHandler

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetItems` |  |  |  |
| `GetNumberOfQueuedMessages` |  | `int32` |  |
| `HasQueuedMessages` |  | `bool` |  |
| `MarkAllForDelete` |  | `void` |  |
| `Self` |  |  |  |
| `ShowNotificationFeedNextToOutliner` |  | `bool` |  |

## MessageSettingsWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CurrentSituationLabelSelectTotal` |  | `void` |  |
| `CurrentSituationLabelSelectUnread` |  | `void` |  |
| `GetAlertSettingsItems` |  |  |  |
| `GetInterestingCountryItems` |  |  |  |
| `GetNotificationSettingsItems` |  |  |  |
| `HasPauseOnEvent` |  | `bool` |  |
| `HasSingleShownItem` |  | `bool` |  |
| `IsCurrentSituationLabelTotal` |  | `bool` |  |
| `OnChangeInterestingCountrySettings` |  | `void` |  |
| `RemoveSingleShownItem` |  | `void` |  |
| `ResetAlertSettings` |  | `void` |  |
| `ResetNotificationSettings` |  | `void` |  |
| `Self` |  |  |  |
| `SetSingleShownItem` | `Arg0` | `void` |  |
| `ShouldBeShown` | `Arg0` | `bool` |  |
| `SortInterestingCountryItemsIfNeeded` |  | `void` |  |
| `TogglePauseOnEvent` |  | `void` |  |

## MetadataWindow

Window to edit metadata of selected nodes.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `GetTitle` |  | `CString` |  |
| `IsOpen` |  | `bool` |  |
| `IsSelectedAnyNode` |  | `bool` |  |
| `Open` |  | `void` |  |
| `Self` |  |  |  |
| `Toggle` |  | `void` |  |

## MilitaryFormation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `FindLeastExperiencedConscriptUnit` | `Arg0` | `CombatUnit` |  |
| `FindLeastExperiencedRegularUnit` | `Arg0` | `CombatUnit` |  |
| `GetCommander` |  | `Character` |  |
| `GetCountry` |  | `Country` |  |
| `GetCurrentFront` |  | `Front` |  |
| `GetCurrentHQ` |  | `Hq` |  |
| `GetCurrentSeaNode` |  | `Province` |  |
| `GetFlagship` |  | `Ship` |  |
| `GetHomeHQ` |  | `Hq` |  |
| `GetInvasion` |  | `Invasion` |  |
| `GetMarinesGroup` |  | `CombatUnitGroup` |  |
| `GetMobilizationModifier` |  | `Modifier` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetNavalAdminBuildingTypeItem` |  | `BuildingBrowserBuildingTypeItem` |  |
| `GetNavalMission` |  | `NavalMission` |  |
| `GetOriginFormation` |  | `MilitaryFormation` |  |
| `GetPrimaryCultureForGroup` | `Arg0` | `Culture` |  |
| `GetPrimaryCultureForType` | `Arg0` | `Culture` |  |
| `GetSelectedUnitTypeForGroup` | `Arg0` | `CombatUnitType` |  |
| `GetShipList` |  | `ShipList` |  |
| `GetStateAtPosition` |  | `State` |  |
| `GetStrategicObjective` |  | `State` |  |
| `GetSupplyHub` |  | `State` |  |
| `GetTargetFront` |  | `Front` |  |
| `GetTargetHQ` |  | `Hq` |  |
| `GetTargetSeaNode` |  | `Province` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanAnyUnitBeUpgraded` |  | `bool` |  |
| `CanDeployToFront` |  | `bool` |  |
| `CanDeployToSeaNode` |  | `bool` |  |
| `CanEditMissionSeaRegions` |  | `bool` |  |
| `CanEmbark` |  | `bool` |  |
| `CanInvade` |  | `bool` |  |
| `CanRecruitConscriptUnit` | `Arg0` | `bool` |  |
| `CanRecruitConscriptUnitTooltip` | `Arg0` | `CString` |  |
| `CanRecruitRegularUnit` | `Arg0` | `bool` |  |
| `CanRecruitRegularUnitTooltip` | `Arg0` | `CString` |  |
| `CanStation` |  | `bool` |  |
| `CanTransportArmy` |  | `bool` |  |
| `CancelRetrofitShips` |  | `Command` |  |
| `CreateNavalMission` | `Arg0` | `Command` |  |
| `CreateNavalMissionWithPreviousArea` | `Arg0` | `Command` |  |
| `Demobilize` |  | `Command` |  |
| `Deselect` |  | `void` |  |
| `Disband` |  | `Command` |  |
| `DisembarkFormation` |  | `Command` |  |
| `FindLeastExperiencedConscriptUnit` | `Arg0` |  |  |
| `FindLeastExperiencedRegularUnit` | `Arg0` |  |  |
| `GetAIDebugInfo` |  | `CString` |  |
| `GetActiveBattles` |  |  |  |
| `GetActiveNavalBattles` |  |  |  |
| `GetAdvancementSpeed` |  | `CFixedPoint` |  |
| `GetAdvancementSpeedDesc` |  | `CString` |  |
| `GetAdvancementUnitShare` |  | `CFixedPoint` |  |
| `GetArmorBreakdown` |  | `CString` |  |
| `GetAttachedFormations` |  |  |  |
| `GetAttritionRaw` |  | `CFixedPoint` |  |
| `GetAttritionRiskDesc` |  | `CString` |  |
| `GetAvailableCarryingCapacity` |  | `int32` |  |
| `GetAverageAttritionPerWeek` |  | `CFixedPoint` |  |
| `GetAverageDefense` |  | `CFixedPoint` |  |
| `GetAverageDefenseExcludeUnavailableManpower` |  | `CFixedPoint` |  |
| `GetAverageDetection` |  | `CFixedPoint` |  |
| `GetAverageOffense` |  | `CFixedPoint` |  |
| `GetAverageOffenseExcludeUnavailableManpower` |  | `CFixedPoint` |  |
| `GetBaseSupplyConsumptionBreakdown` |  | `CString` |  |
| `GetBlockadeAffectedBuildingCount` |  | `int32` |  |
| `GetBlockadeAffectedShippingLaneCount` |  | `int32` |  |
| `GetBlockadeAffectedShippingLaneCountForState` | `Arg0` | `int32` |  |
| `GetBlockadeEfficiency` |  | `CFixedPoint` |  |
| `GetBlockadeEfficiencyDesc` |  | `CString` |  |
| `GetBlockadeEfficiencyMax` |  | `CFixedPoint` |  |
| `GetBlockadeEfficiencyMaxDesc` |  | `CString` |  |
| `GetBlockadeStatesBreakdown` |  | `CString` |  |
| `GetBlockadeStrength` |  | `CFixedPoint` |  |
| `GetBlockadeStrengthMax` |  | `CFixedPoint` |  |
| `GetBlockadedStates` |  |  |  |
| `GetBombardedStates` |  |  |  |
| `GetBorrowSettings` |  |  |  |
| `GetBuildingDestructionChanceForBombardedState` | `Arg0` | `CFixedPoint` |  |
| `GetBuildings` |  |  |  |
| `GetBuildingsDesc` |  | `CString` |  |
| `GetCanEditMissionSeaRegionsDesc` |  | `CString` |  |
| `GetCanEmbarkDesc` |  | `CString` |  |
| `GetCarryingCapacity` |  | `int32` |  |
| `GetCarryingCapacityBreakdown` |  | `CString` |  |
| `GetCombatUnitEntries` |  |  |  |
| `GetCombatUnitsTypeIcon` |  | `CString` |  |
| `GetCommandLimit` |  | `CString` |  |
| `GetCommandLimitDesc` |  | `CString` |  |
| `GetCommandLimitRaw` |  | `int32` |  |
| `GetCommandLimitUsage` |  | `int32` |  |
| `GetCommonDebugInfo` |  | `CString` |  |
| `GetConscriptPowerProjection` |  | `CFixedPoint` |  |
| `GetConscriptPowerProjectionDesc` |  | `CString` |  |
| `GetConscriptUnitsByTypeBreakdown` | `Arg0` | `CString` |  |
| `GetConscriptsGroupsBreakdown` |  | `CString` |  |
| `GetConscriptsMobilizationPercentage` |  | `CFixedPoint` |  |
| `GetCountry` |  |  |  |
| `GetCrewBreakdown` |  | `CString` |  |
| `GetCrewDamageBreakdown` |  | `CString` |  |
| `GetCurrentFront` |  |  |  |
| `GetCurrentHQ` |  |  |  |
| `GetCurrentManpower` |  | `int64` |  |
| `GetCurrentManpowerFromConscripts` |  | `int64` |  |
| `GetCurrentManpowerFromRegulars` |  | `int64` |  |
| `GetCurrentSeaNode` |  |  |  |
| `GetCurrentSupplyAmount` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDailyDevastationForBombardedState` | `Arg0` | `CFixedPoint` |  |
| `GetDailyDevastationFromBombardment` |  | `CFixedPoint` |  |
| `GetDailyDevastationFromBombardmentDesc` |  | `CString` |  |
| `GetDefenseCommanderBreakdown` |  | `CString` |  |
| `GetDemobilizationStatus` |  | `CString` |  |
| `GetDetectionBreakdown` |  | `CString` |  |
| `GetDisbandUnitCommand` | `Arg0` | `Command` |  |
| `GetDisbandUnitTypeConscriptCommand` | `Arg0` | `Command` |  |
| `GetDisbandUnitTypeRegularCommand` | `Arg0` | `Command` |  |
| `GetDistanceToHomePort` |  | `CFixedPoint` |  |
| `GetDistanceToHomePortFormatted` |  | `CString` |  |
| `GetEffectFromBeingExiledDesc` |  | `CString` |  |
| `GetEffectFromCommandLimitDesc` |  | `CString` |  |
| `GetEffectFromSpecialUnitsDesc` |  | `CString` |  |
| `GetEffectOfDefaultUnitTypeChange` | `Arg0` | `CString` |  |
| `GetEffectiveSupplyDistance` |  | `CFixedPoint` |  |
| `GetEligibleGroups` |  |  |  |
| `GetEligibleTypesByGroup` | `Arg0` |  |  |
| `GetEstimatedMobilizationCostDesc` |  | `CString` |  |
| `GetEstimatedMobilizationCostFormatted` |  | `CString` |  |
| `GetEstimatedMobilizationCostRaw` |  | `CFixedPoint` |  |
| `GetExpectedNumRegulars` |  | `int32` |  |
| `GetFlag` |  |  |  |
| `GetFlagColor` |  | `CVector4f` |  |
| `GetFormationStatusDesc` |  | `CString` |  |
| `GetFriendlyPortDiscount` |  | `CFixedPoint` |  |
| `GetFrontDistributionDesc` |  | `CString` |  |
| `GetGoodsConsumptionCostRaw` |  | `CFixedPoint` |  |
| `GetGoodsConsumptionDesc` |  | `CString` |  |
| `GetHitPointsBreakdown` |  | `CString` |  |
| `GetHitPointsPercentage` |  | `CFixedPoint` |  |
| `GetHullDamageBreakdown` |  | `CString` |  |
| `GetIDString` |  | `CString` |  |
| `GetIncomingNumRegulars` |  | `int32` |  |
| `GetIncomingNumRegularsFromBuilding` | `Arg0` | `int32` |  |
| `GetIncomingNumRegularsOfUnitType` | `Arg0` | `int32` |  |
| `GetInterceptBlockedFleetsInRegion` | `Arg0` |  |  |
| `GetInterceptChancePerDay` |  | `CFixedPoint` |  |
| `GetInterceptRegions` |  |  |  |
| `GetInterceptTargetsInRegion` | `Arg0` |  |  |
| `GetInvasionTooltip` |  | `CString` |  |
| `GetInvolvementGenerated` |  | `CFixedPoint` |  |
| `GetLocationString` |  | `CString` |  |
| `GetLogisticsCenterSupplyAvailability` |  | `CFixedPoint` |  |
| `GetLowOrganizationDesc` |  | `CString` |  |
| `GetMarineCapacity` |  | `int32` |  |
| `GetMarineCapacityBreakdown` |  | `CString` |  |
| `GetMaxConscripts` |  | `int32` |  |
| `GetMaxManpower` |  | `int64` |  |
| `GetMaxManpowerFromConscripts` |  | `int64` |  |
| `GetMaxManpowerFromRegulars` |  | `int64` |  |
| `GetMaxSupplyShipsDestroyablePerBattle` |  | `int32` |  |
| `GetMaxSupplyShipsProtectablePerBattle` |  | `int32` |  |
| `GetMissionEfficiency` |  | `CFixedPoint` |  |
| `GetMissionEfficiencyDesc` |  | `CString` |  |
| `GetMobilizationModifier` |  |  |  |
| `GetMobilizationOptions` |  |  |  |
| `GetMobilizationPercentage` |  | `CFixedPoint` |  |
| `GetMobilizationPercentageFormatted` |  | `CString` |  |
| `GetModifier` |  |  |  |
| `GetMorale` |  | `CFixedPoint` |  |
| `GetMoraleBreakdown` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNameWithCountryFlag` |  | `CString` |  |
| `GetNavalMissionSeaRegions` |  |  |  |
| `GetNavalMissionSupplyFactor` |  | `CFixedPoint` |  |
| `GetNonMarineUnitCount` |  | `int32` |  |
| `GetNumActiveShips` |  | `int32` |  |
| `GetNumAssignedSupplyShips` |  | `int32` |  |
| `GetNumAttachedMarineUnits` |  | `int32` |  |
| `GetNumBlockadedStates` |  | `int32` |  |
| `GetNumCombatUnits` |  | `int32` |  |
| `GetNumConscripts` |  | `int32` |  |
| `GetNumConscriptsCombatUnitsOfType` | `Arg0` | `int32` |  |
| `GetNumConscriptsUnitsInGroup` | `Arg0` | `int32` |  |
| `GetNumCrewlessShips` |  | `int32` |  |
| `GetNumDeployToFrontSelections` |  | `int32` |  |
| `GetNumDeployToSeaNodeSelections` |  | `int32` |  |
| `GetNumEmbarkSelections` |  | `int32` |  |
| `GetNumExpectedConscriptsCombatUnitsOfType` | `Arg0` | `int32` |  |
| `GetNumExpectedConscriptsCombatUnitsOfTypeFromState` | `Arg0, Arg1` | `int32` |  |
| `GetNumExpectedConscriptsUnitsInGroup` | `Arg0` | `int32` |  |
| `GetNumExpectedRegularCombatUnitsOfType` | `Arg0` | `int32` |  |
| `GetNumFullyBlockadedStates` |  | `int32` |  |
| `GetNumFullyMobilizedConscripts` |  | `int32` |  |
| `GetNumFullyMobilizedRegulars` |  | `int32` |  |
| `GetNumFullyMobilizedTotalUnits` |  | `int32` |  |
| `GetNumInvasionSelections` |  | `int32` |  |
| `GetNumRegularCombatUnitsOfType` | `Arg0` | `int32` |  |
| `GetNumRegulars` |  | `int32` |  |
| `GetNumRegularsUnitsInGroup` | `Arg0` | `int32` |  |
| `GetNumShips` |  | `int32` |  |
| `GetNumSpecialUnits` |  | `int32` |  |
| `GetNumSpecialUnitsExpected` |  | `int32` |  |
| `GetNumStationSelections` |  | `int32` |  |
| `GetNumStrategicObjectiveActive` |  | `int32` |  |
| `GetNumStrategicObjectiveSelections` |  | `int32` |  |
| `GetNumTotalCombatUnitsExpectedInGroup` | `Arg0` | `int32` |  |
| `GetNumTotalCombatUnitsInGroup` | `Arg0` | `int32` |  |
| `GetNumTotalCombatUnitsOfType` | `Arg0` | `int32` |  |
| `GetNumTotalUnits` |  | `int32` |  |
| `GetNumTransportArmySelections` |  | `int32` |  |
| `GetNumWantedSupplyShips` |  | `int32` |  |
| `GetNumWantedSupplyShipsForEquilibrium` |  | `int32` |  |
| `GetNumWantedSupplyShipsOnMission` |  | `int32` |  |
| `GetOffenseCommanderBreakdown` |  | `CString` |  |
| `GetOrganization` |  | `CString` |  |
| `GetOrganizationDailyChange` |  | `CFixedPoint` |  |
| `GetOrganizationDailyChangeDesc` |  | `CString` |  |
| `GetOrganizationPercentage` |  | `CFixedPoint` |  |
| `GetOrganizationRaw` |  | `CFixedPoint` |  |
| `GetOrganizationTargetDesc` |  | `CString` |  |
| `GetOrganizationTargetFormatted` |  | `CString` |  |
| `GetOrganizationTargetPercentage` |  | `CFixedPoint` |  |
| `GetOrganizationTargetRaw` |  | `CFixedPoint` |  |
| `GetOwnSupplyShipsInArea` |  | `int32` |  |
| `GetPilferedGoods` |  |  |  |
| `GetPilferedGoodsAmount` | `Arg0` | `CFixedPoint` |  |
| `GetPotentialMissionsTypes` |  |  |  |
| `GetPowerProjection` |  | `CFixedPoint` |  |
| `GetPowerProjectionDesc` |  | `CString` |  |
| `GetPredictedDistanceToHomePortFromSeaNode` | `Arg0` | `CFixedPoint` |  |
| `GetPredictedSupplyShipsAtSeaNode` | `Arg0` | `int32` |  |
| `GetPredictedSupplyShipsDelta` | `Arg0` | `int32` |  |
| `GetPredictedSupplyShipsDeltaWithMission` | `Arg0` | `int32` |  |
| `GetPredictedTravelDaysToSeaNode` | `Arg0` | `int32` |  |
| `GetPrimaryCultureForGroup` | `Arg0` |  |  |
| `GetPrimaryCultureForType` | `Arg0` |  |  |
| `GetRegularPowerProjection` |  | `CFixedPoint` |  |
| `GetRegularPowerProjectionDesc` |  | `CString` |  |
| `GetRegularUnitsByTypeBreakdown` | `Arg0` | `CString` |  |
| `GetRegularsGroupsBreakdown` |  | `CString` |  |
| `GetRegularsMobilizationPercentage` |  | `CFixedPoint` |  |
| `GetRepairProgress` |  | `CFixedPoint` |  |
| `GetRetrofitCost` |  | `CFixedPoint` |  |
| `GetRetrofitCostDesc` |  | `CString` |  |
| `GetRetrofitProgress` |  | `CFixedPoint` |  |
| `GetScreeningRatio` |  | `CFixedPoint` |  |
| `GetScreeningRatioBreakdown` |  | `CString` |  |
| `GetSeaPresence` |  | `CFixedPoint` |  |
| `GetSeaPresencePerDay` |  | `CFixedPoint` |  |
| `GetSelectedUnitTypeForGroup` | `Arg0` |  |  |
| `GetSetDefaultUnitTypeCommand` | `Arg0` | `Command` |  |
| `GetShortFormationStatusDesc` |  | `CString` |  |
| `GetSlowestShipsBreakdown` |  | `CString` |  |
| `GetSpeed` |  | `CFixedPoint` |  |
| `GetSpeedBreakdown` |  | `CString` |  |
| `GetSupplyCapacity` |  | `CFixedPoint` |  |
| `GetSupplyCapacityBreakdown` |  | `CString` |  |
| `GetSupplyCapacityDesc` |  | `CString` |  |
| `GetSupplyCapacityRaw` |  | `CFixedPoint` |  |
| `GetSupplyConsumption` |  | `CFixedPoint` |  |
| `GetSupplyConsumptionBase` |  | `CFixedPoint` |  |
| `GetSupplyConsumptionBreakdown` |  | `CString` |  |
| `GetSupplyDelivered` |  | `CFixedPoint` |  |
| `GetSupplyGoodsRequest` |  |  |  |
| `GetSupplyGoodsRequestAmount` | `Arg0` | `CFixedPoint` |  |
| `GetSupplyRaidTargetsBreakdown` |  | `CString` |  |
| `GetSupplyRatio` |  | `CFixedPoint` |  |
| `GetSupplyRaw` |  | `CFixedPoint` |  |
| `GetSupplyReplenishMult` |  | `CFixedPoint` |  |
| `GetSupplyShipCarryCapacity` |  | `CFixedPoint` |  |
| `GetSupplyShipsRaidableInArea` |  | `int32` |  |
| `GetSupplyShortageRatio` |  | `CFixedPoint` |  |
| `GetSupplyWeeklyChange` |  | `CFixedPoint` |  |
| `GetTargetSeaNode` |  |  |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalVisibility` |  | `CFixedPoint` |  |
| `GetTransportMissionQueueCount` |  | `int32` |  |
| `GetTransportedFormations` |  |  |  |
| `GetTravelDaysLeft` |  | `int32` |  |
| `GetTravelDaysLeftFormatted` |  | `CString` |  |
| `GetTravelDistanceLeft` |  | `CFixedPoint` |  |
| `GetTravelTimeLeftLabel` |  | `CString` |  |
| `GetUnitIcon` |  | `CString` |  |
| `GetUnitLabel` |  | `CString` |  |
| `GetUnitTypesByConscriptsGroupBreakdown` | `Arg0` | `CString` |  |
| `GetUnitTypesByRegularsGroupBreakdown` | `Arg0` | `CString` |  |
| `GetUpgradeAllUnitsCommand` |  | `Command` |  |
| `GetUpgradeConscriptUnitTypeCommand` | `Arg0` | `Command` |  |
| `GetUpgradeRegularUnitTypeCommand` | `Arg0` | `Command` |  |
| `GetUpgradeUnitGroupCommand` | `Arg0` | `Command` |  |
| `GetVisibilityBreakdown` |  | `CString` |  |
| `HasBlockadeMission` |  | `bool` |  |
| `HasCoastalBombardmentTargets` |  | `bool` |  |
| `HasCommander` |  | `bool` |  |
| `HasFullSupplyPath` |  | `bool` |  |
| `HasInvasion` |  | `bool` |  |
| `HasLogisticsCenterGoodsShortage` |  | `bool` |  |
| `HasNavalMission` |  | `bool` |  |
| `HasNavalMissionType` | `Arg0` | `bool` |  |
| `HasOwnSupplyShipsPassingThrough` |  | `bool` |  |
| `HasPendingPickup` |  | `bool` |  |
| `HasRaisedConscripts` |  | `bool` |  |
| `HasSelectedUnitTypeForGroup` | `Arg0` | `bool` |  |
| `HasSufficientSeaPresenceForBombardment` |  | `bool` |  |
| `HasSupplyRaidTargets` |  | `bool` |  |
| `HasSupplyRoute` |  | `bool` |  |
| `HasSupplyShortageOrganizationPenalty` |  | `bool` |  |
| `HasTooManySpecialUnits` |  | `bool` |  |
| `HasTooManySpecialUnitsExpected` |  | `bool` |  |
| `HasTooManySpecialUnitsExpectedInGroup` | `Arg0` | `bool` |  |
| `HasTooManySpecialUnitsInGroup` | `Arg0` | `bool` |  |
| `HasTransportMission` |  | `bool` |  |
| `HasTransportedArmyOnboard` |  | `bool` |  |
| `IsAboutToTransportArmies` |  | `bool` |  |
| `IsActiveInNavalMission` |  | `bool` |  |
| `IsAdvancing` |  | `bool` |  |
| `IsAdvancingInBattle` |  | `bool` |  |
| `IsArmy` |  | `bool` |  |
| `IsAttachedToFleet` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsBlockadeAtMaxLevel` |  | `bool` |  |
| `IsBlockadeFullyEffective` |  | `bool` |  |
| `IsCommander` | `Arg0` | `bool` |  |
| `IsConscriptUnitTypeUpgrading` | `Arg0` | `bool` |  |
| `IsCurrentHQ` | `Arg0` | `bool` |  |
| `IsCurrentSeaNode` | `Arg0` | `bool` |  |
| `IsDefaultConstructionFleet` |  | `bool` |  |
| `IsDefendingInBattle` |  | `bool` |  |
| `IsDemobilizing` |  | `bool` |  |
| `IsDocked` |  | `bool` |  |
| `IsExiled` |  | `bool` |  |
| `IsFleet` |  | `bool` |  |
| `IsFullyDefeated` |  | `bool` |  |
| `IsFullyMobilized` |  | `bool` |  |
| `IsInBattle` |  | `bool` |  |
| `IsMobilized` |  | `bool` |  |
| `IsMobilizing` |  | `bool` |  |
| `IsOnInterceptMission` |  | `bool` |  |
| `IsOnPiracyMission` |  | `bool` |  |
| `IsOnPortBombardmentMission` |  | `bool` |  |
| `IsOnProtectSupplyMission` |  | `bool` |  |
| `IsOnRaidSupplyMission` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsReadyToDefendNavalInvasion` |  | `bool` |  |
| `IsRecalledForRepairs` |  | `bool` |  |
| `IsRegularUnitTypeUpgrading` | `Arg0` | `bool` |  |
| `IsReplenishingSupply` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsSupplyPrioritySelected` | `Arg0` | `bool` |  |
| `IsTargetHQ` | `Arg0` | `bool` |  |
| `IsTargetSeaNode` | `Arg0` | `bool` |  |
| `IsTransportingArmiesToTarget` |  | `bool` |  |
| `IsTraveling` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsZoomingToMapMarkerPosition` |  | `bool` |  |
| `Mobilize` |  | `Command` |  |
| `OnClickRecruitCombatUnit` | `Arg0` | `void` |  |
| `OnClickRecruitConscript` | `Arg0` | `void` |  |
| `OnDeployToFrontClicked` |  | `void` |  |
| `OnDeployToSeaNodeClicked` |  | `void` |  |
| `OnEditMissionSeaRegionsClicked` |  | `void` |  |
| `OnInvasionClicked` |  | `void` |  |
| `OnRehomeClicked` |  | `void` |  |
| `OnSetStrategicObjectiveClicked` |  | `void` |  |
| `OnStationClicked` |  | `void` |  |
| `RaiseConscripts` |  | `Command` |  |
| `RecallForRepairs` |  | `Command` |  |
| `RemoveNavalMission` |  | `Command` |  |
| `RetrofitShips` |  | `Command` |  |
| `RetrofitShipsAndStation` |  | `Command` |  |
| `Select` |  | `void` |  |
| `SelectSupplyPriority` | `Arg0` | `Command` |  |
| `Self` |  |  |  |
| `SortAttachedFormations` | `Arg0` | `void` |  |
| `SortTransportedFormations` | `Arg0` | `void` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `ToggleSelected` |  | `void` |  |
| `ZoomToMapMarkerPosition` |  | `void` |  |

## MilitaryFormationBorrowSetting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBorrowingCommand` |  | `Command` |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `OnClicked` |  | `void` |  |
| `Self` |  |  |  |

## MilitaryFormationChangeNamePopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `Confirm` |  | `Command` |  |
| `GetArmyFormationColors` |  |  |  |
| `GetArmyFormationFlags` |  |  |  |
| `GetCurrentUnitName` |  | `CString` |  |
| `GetFleetFormationColors` |  |  |  |
| `GetFleetFormationFlags` |  |  |  |
| `GetFormation` |  |  |  |
| `GetSelectedColor` |  | `CVector4f` |  |
| `IsColorSelected` | `Arg0` | `bool` |  |
| `IsFlagSelected` | `Arg0` | `bool` |  |
| `IsNameUnitsAfterCultureSelected` |  | `bool` |  |
| `IsNameUnitsAfterStateSelected` |  | `bool` |  |
| `OnEditName` |  | `void` |  |
| `OnSelectColor` | `Arg0` | `void` |  |
| `OnSelectFlag` | `Arg0` | `void` |  |
| `SelectNameUnitsAfterCulture` |  | `void` |  |
| `SelectNameUnitsAfterState` |  | `void` |  |
| `Self` |  |  |  |

## MilitaryFormationColor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `Self` |  |  |  |

## MilitaryFormationFlag

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## MilitaryFormationUnitEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetUnitType` |  | `CombatUnitType` |  |
| `AccessSelf` |  |  |  |
| `GetCombatUnits` |  |  |  |
| `GetCurrentNumConscriptUnits` |  | `int32` |  |
| `GetCurrentNumRegularUnits` |  | `int32` |  |
| `GetCurrentNumTotalUnits` |  | `int32` |  |
| `GetExpectedNumConscriptUnits` |  | `int32` |  |
| `GetExpectedNumRegularUnits` |  | `int32` |  |
| `GetExpectedNumTotalUnits` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetMobilization` |  | `CFixedPoint` |  |
| `GetRegularUnitsAndRaisedConscripts` |  |  |  |
| `GetUnitType` |  |  |  |
| `IsDefaultType` |  | `bool` |  |
| `IsForGroup` | `Arg0` | `bool` |  |
| `IsFullyMobilized` |  | `bool` |  |
| `IsMobilizing` |  | `bool` |  |
| `Self` |  |  |  |

## MilitaryFormationWrapped

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `CanFleetTransportArmy` | `Arg0` | `bool` |  |
| `EmbarkFormation` | `Arg0` | `Command` |  |
| `GetCanFleetTransportArmyDesc` | `Arg0` | `CString` |  |
| `GetFleetsSortedByMarineCapacity` |  |  |  |
| `Self` |  |  |  |
| `TransportArmyForFleet` | `Arg0` | `void` |  |

## MilitaryPanelBuildingEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuilding` |  | `Building` |  |
| `AccessSelf` |  |  |  |
| `GetBuilding` |  |  |  |
| `IsExpanded` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpand` |  | `void` |  |

## MixBrushMode

Map Editor - Material painter mix brush mode

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## MobilizationOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetUnitModifier` |  | `Modifier` |  |
| `GetUpkeepModifier` |  | `Modifier` |  |
| `GetUpkeepUnscaledModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanBeTurnedOff` | `Arg0` | `bool` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumActiveForSelected` |  | `int32` |  |
| `GetNumBlockedForSelected` |  | `int32` |  |
| `GetNumCouldBeActivatedForSelected` |  | `int32` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTooltipWithActivateDesc` | `Arg0` | `CString` |  |
| `GetTooltipWithActivateDescForSelected` |  | `CString` |  |
| `GetTooltipWithDeactivateDesc` | `Arg0` | `CString` |  |
| `GetTooltipWithDeactivateDescForSelected` |  | `CString` |  |
| `GetTooltipWithToggleDesc` | `Arg0` | `CString` |  |
| `GetUnitModifier` |  |  |  |
| `GetUpkeepModifier` |  |  |  |
| `GetUpkeepUnscaledModifier` |  |  |  |
| `IsActivated` | `Arg0` | `bool` |  |
| `IsActivatedForSelected` |  | `bool` |  |
| `IsActiveForSomeButNotAllSelected` |  | `bool` |  |
| `IsBlockedForSomeSelected` |  | `bool` |  |
| `IsDeactivatedForSelected` |  | `bool` |  |
| `IsMixedActivationForSelected` |  | `bool` |  |
| `IsPossible` | `Arg0` | `bool` |  |
| `IsShown` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `Toggle` | `Arg0` | `Command` |  |
| `ToggleForSelected` |  | `Command` |  |

## MobilizationOptionGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetMobilizationOptions` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUpkeepGoodsDescShort` | `Arg0` | `CString` |  |
| `Self` |  |  |  |

## Modifier

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBreakdownFor` | `Arg0` | `ModifierBreakdown` |  |
| `AccessSelf` |  |  |  |
| `GetBreakdownFor` | `Arg0` |  |  |
| `GetDesc` |  | `CString` |  |
| `GetDescFor` | `Arg0` | `CString` |  |
| `GetDescNoGoods` |  | `CString` |  |
| `GetEntries` |  |  |  |
| `GetFormattedValueFor` | `Arg0` | `CString` |  |
| `GetFullEntryDescFor` | `Arg0` | `CString` |  |
| `GetInvertedValueFor` | `Arg0` | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNonFormattedValueWithBreakdownAndNoDecimalsFor` | `Arg0` | `CString` |  |
| `GetNonFormattedValueWithBreakdownFor` | `Arg0` | `CString` |  |
| `GetShipAccuracy` |  | `CFixedPoint` |  |
| `GetShipAccuracyTooltip` |  | `CString` |  |
| `GetShipArmor` |  | `CFixedPoint` |  |
| `GetShipArmorTooltip` |  | `CString` |  |
| `GetShipAverageDamage` |  | `CFixedPoint` |  |
| `GetShipBlockadeStrength` |  | `CFixedPoint` |  |
| `GetShipBlockadeStrengthTooltip` |  | `CString` |  |
| `GetShipCarryingCapacity` |  | `CFixedPoint` |  |
| `GetShipCarryingCapacityTooltip` |  | `CString` |  |
| `GetShipConstructionProgressMax` |  | `CFixedPoint` |  |
| `GetShipConstructionProgressMaxTooltip` |  | `CString` |  |
| `GetShipCrewDamage` |  | `CFixedPoint` |  |
| `GetShipCrewDamageTooltip` |  | `CString` |  |
| `GetShipCrewMax` |  | `CFixedPoint` |  |
| `GetShipCrewMaxTooltip` |  | `CString` |  |
| `GetShipCriticalHitChance` |  | `CFixedPoint` |  |
| `GetShipCriticalHitChanceTooltip` |  | `CString` |  |
| `GetShipCriticalHitMultiplier` |  | `CFixedPoint` |  |
| `GetShipCriticalHitMultiplierTooltip` |  | `CString` |  |
| `GetShipDetection` |  | `CFixedPoint` |  |
| `GetShipDetectionTooltip` |  | `CString` |  |
| `GetShipHitPointsMax` |  | `CFixedPoint` |  |
| `GetShipHitPointsMaxTooltip` |  | `CString` |  |
| `GetShipHullDamage` |  | `CFixedPoint` |  |
| `GetShipHullDamageTooltip` |  | `CString` |  |
| `GetShipMarineCapacity` |  | `CFixedPoint` |  |
| `GetShipMarineCapacityTooltip` |  | `CString` |  |
| `GetShipReadinessGain` |  | `CFixedPoint` |  |
| `GetShipReadinessGainTooltip` |  | `CString` |  |
| `GetShipScreening` |  | `CFixedPoint` |  |
| `GetShipScreeningTooltip` |  | `CString` |  |
| `GetShipSpeed` |  | `CFixedPoint` |  |
| `GetShipSpeedTooltip` |  | `CString` |  |
| `GetShipSupplyCapacity` |  | `CFixedPoint` |  |
| `GetShipSupplyCapacityTooltip` |  | `CString` |  |
| `GetShipSupplyEfficiency` |  | `CFixedPoint` |  |
| `GetShipSupplyEfficiencyTooltip` |  | `CString` |  |
| `GetShipVisibility` |  | `CFixedPoint` |  |
| `GetShipVisibilityTooltip` |  | `CString` |  |
| `GetShipVulnerability` |  | `CFixedPoint` |  |
| `GetShipVulnerabilityTooltip` |  | `CString` |  |
| `GetTooltipFor` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetValueFor` | `Arg0` | `CFixedPoint` |  |
| `GetValueWithBreakdownFor` | `Arg0` | `CString` |  |
| `IsEmpty` |  | `bool` |  |
| `Self` |  |  |  |

## ModifierBreakdown

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifier` |  | `Modifier` |  |
| `AccessSelf` |  |  |  |
| `GetBreakdown` |  | `CString` |  |
| `GetFormattedMultipliedValue` |  | `CString` |  |
| `GetFormattedRawValue` |  | `CString` |  |
| `GetModifier` |  |  |  |
| `GetMultipliedValue` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetRawValue` |  | `CFixedPoint` |  |
| `GetSourceMultiplier` |  | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTypeDescription` |  | `CString` |  |
| `GetTypeName` |  | `CString` |  |
| `Self` |  |  |  |

## ModifierEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBreakdown` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetFormattedValue` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetValue` |  | `CFixedPoint` |  |
| `GetValueWithBreakdown` |  | `CString` |  |
| `Self` |  |  |  |

## ModifierNodeData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetTotalCount` |  | `int32` |  |
| `GetUpdatedCount` |  | `int32` |  |
| `GetUpdatedTrend` |  | `DataTrend` |  |
| `OpenDetails` |  | `void` |  |
| `Self` |  |  |  |

## ModifierNodeDebuggerView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetGraphItems` |  |  |  |
| `GetGraphLines` |  |  |  |
| `Self` |  |  |  |

## ModifierNodeDetailsView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifierNodeData` |  | `ModifierNodeData` |  |
| `AccessSelf` |  |  |  |
| `GetModifierNodeData` |  |  |  |
| `Self` |  |  |  |

## ModifierNodeGraphItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifierNodeData` |  | `ModifierNodeData` |  |
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetModifierNodeData` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetTooltip` |  | `CString` |  |
| `Self` |  |  |  |

## ModifierNodeGraphLine

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFrom` |  | `CVector2f` |  |
| `GetLineFrom` |  | `CVector2f` |  |
| `GetLineTo` |  | `CVector2f` |  |
| `GetPoints` |  |  |  |
| `GetPointsInContainer` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetSize` |  | `CVector2f` |  |
| `GetTo` |  | `CVector2f` |  |
| `IsFromNodeVirtual` |  | `bool` |  |
| `IsToNodeVirtual` |  | `bool` |  |
| `Self` |  |  |  |

## ModifierNodeListView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetModifierNodes` |  |  |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## ModifiersPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifier` |  | `Modifier` |  |
| `AccessSelf` |  |  |  |
| `GetModifier` |  |  |  |
| `GetTimedModifiers` |  |  |  |
| `Self` |  |  |  |

## MoveTool

Map Editor - Map Object - Move Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## MPConfig

Jomini Multiplayer - Configuration

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetOfflinePlayerToolTip` |  | `CString` |  |
| `GetPrivateToolTip` |  | `CString` |  |
| `GetPublicToolTip` |  | `CString` |  |
| `IsCrossplayChecked` |  | `bool` |  |
| `IsHotjoinAutoAccept` |  | `bool` |  |
| `IsOffline` |  | `bool` |  |
| `IsPrivate` |  | `bool` |  |
| `IsPublic` |  | `bool` |  |
| `Self` |  |  |  |
| `SetOffline` |  | `void` |  |
| `SetPrivate` |  | `void` |  |
| `SetPublic` |  | `void` |  |
| `ToggleCrossplay` |  | `void` |  |
| `ToggleHotjoinAutoAccept` |  | `void` |  |

## MultiplayerSetupWindow

Jomini Multiplayer - Setup window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMPConfig` |  | `MPConfig` |  |
| `GetMPConfig` |  | `MPConfig` |  |
| `AccessSelf` |  |  |  |
| `CanHost` |  | `bool` |  |
| `Cancel` |  | `void` |  |
| `GetDefaultServerName` |  | `CUTF8String` |  |
| `GetDefaultServerPassword` |  | `CUTF8String` |  |
| `Host` |  | `void` |  |
| `HostToolTip` |  | `CString` |  |
| `Self` |  |  |  |
| `ShouldShowMPConfig` |  | `bool` |  |

## MultiplayerSynchronizationInfo

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetPlayerDatesString` |  | `CString` |  |
| `Self` |  |  |  |

## MusicPlayer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCategories` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTracksFromSelectedCategory` |  |  |  |
| `GetCategoryEnabledText` | `Arg0` | `CString` |  |
| `GetCategoryName` | `Arg0` | `CString` |  |
| `GetCategoryNameLocKey` | `Arg0` | `CString` |  |
| `GetMusicDensity` |  | `float` |  |
| `GetMusicDensityString` |  | `CString` |  |
| `GetPlaybackStatusFrameIndex` |  | `int32` |  |
| `GetPlayingTrackElapsedTime` |  | `CString` |  |
| `GetPlayingTrackName` |  | `CString` |  |
| `GetSelectedCategory` |  |  |  |
| `GetTrackEnabledText` | `Arg0` | `CString` |  |
| `GetTrackName` | `Arg0` | `CString` |  |
| `GetTrackTextColor` | `Arg0` | `CVector4f` |  |
| `GetVolume` |  | `float` |  |
| `GetVolumeString` |  | `CString` |  |
| `HasSelectedCategory` |  | `bool` |  |
| `IsPlaying` |  | `bool` |  |
| `IsSelectedCategory` | `Arg0` | `bool` |  |
| `OnNextTrack` |  | `void` |  |
| `OnSelectAndPlayTrack` | `Arg0` | `void` |  |
| `OnSelectCategory` | `Arg0` | `void` |  |
| `OnSelectTrack` | `Arg0` | `void` |  |
| `OnToggleCategoryEnabled` | `Arg0` | `void` |  |
| `OnTogglePlayPause` |  | `void` |  |
| `OnToggleTrackEnabled` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetMusicDensity` |  | `void` |  |
| `SetVolume` |  | `void` |  |

## MusicPlayerCategory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameLocKey` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTracks` |  |  |  |
| `HasTexture` |  | `bool` |  |
| `IsEnabled` |  | `bool` |  |
| `IsPlaying` |  | `bool` |  |
| `Self` |  |  |  |

## MusicTrack

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCategory` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsEnabled` |  | `bool` |  |
| `IsPlaying` |  | `bool` |  |
| `Self` |  |  |  |
