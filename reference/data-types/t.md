# Data-binding types: T

Back to the [index](README.md).

## TaxBurdenItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTaxType` |  | `CString` |  |
| `GetValue` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## Technology

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetEra` |  | `Era` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `AddToQueue` | `Arg0` | `Command` |  |
| `AddToQueueWithUnlocks` | `Arg0` | `Command` |  |
| `GetCategoryKey` |  | `CString` |  |
| `GetCategoryName` |  | `CString` |  |
| `GetCost` | `Arg0` | `CFixedPoint` |  |
| `GetCostDesc` | `Arg0` | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEra` |  |  |  |
| `GetModifiersAsString` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetProgress` | `Arg0` | `CFixedPoint` |  |
| `GetProgressPercentage` | `Arg0` | `float` |  |
| `GetResearchQueuePosition` | `Arg0` | `int32` |  |
| `GetTexture` |  |  |  |
| `GetTimeLeftDesc` | `Arg0` | `CString` |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTooltipWithoutRequirements` | `Arg0` | `CString` |  |
| `GetUnlocks` | `Arg0` |  |  |
| `HasResearchedTech` | `Arg0` | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsInResearchQueue` | `Arg0` | `bool` |  |
| `IsResearchable` |  | `bool` |  |
| `IsResearching` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `PredictTimeLeftDesc` | `Arg0` | `CString` |  |
| `PredictTimeLeftInQueueDesc` | `Arg0` | `CString` |  |
| `RemoveFromQueue` | `Arg0` | `Command` |  |
| `Research` | `Arg0` | `Command` |  |
| `ResearchWithUnlocks` | `Arg0` | `Command` |  |
| `Self` |  |  |  |
| `ShouldShow` | `Arg0` | `bool` |  |

## TechnologyUnlock

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `HasFrame` |  | `bool` |  |
| `IsGroup` |  | `bool` |  |
| `Self` |  |  |  |

## TechTreeItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTechnology` |  | `Technology` |  |
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetTechnology` |  |  |  |
| `IsHighlightedBySearch` |  | `bool` |  |
| `Self` |  |  |  |

## TechTreeLine

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSourceTech` |  | `Technology` |  |
| `GetTargetTech` |  | `Technology` |  |
| `AccessSelf` |  |  |  |
| `GetFrom` |  | `CVector2f` |  |
| `GetLineFrom` |  | `CVector2f` |  |
| `GetLineTo` |  | `CVector2f` |  |
| `GetPoints` |  |  |  |
| `GetPointsInContainer` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetSize` |  | `CVector2f` |  |
| `GetSourceTech` |  |  |  |
| `GetTargetTech` |  |  |  |
| `GetTo` |  | `CVector2f` |  |
| `IsFromNodeVirtual` |  | `bool` |  |
| `IsToNodeVirtual` |  | `bool` |  |
| `Self` |  |  |  |

## TechTreePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSearchBar` |  | `SearchBar` |  |
| `AccessSelf` |  |  |  |
| `GetMilitaryTechTreeItems` |  |  |  |
| `GetMilitaryTechTreeLines` |  |  |  |
| `GetProductionTechTreeItems` |  |  |  |
| `GetProductionTechTreeLines` |  |  |  |
| `GetSearchBar` |  |  |  |
| `GetSocietyTechTreeItems` |  |  |  |
| `GetSocietyTechTreeLines` |  |  |  |
| `GoToTech` | `Arg0` | `void` |  |
| `GoToTechFromKey` | `Arg0` | `void` |  |
| `ResetMilitaryView` |  | `void` |  |
| `ResetProductionView` |  | `void` |  |
| `ResetSocietyView` |  | `void` |  |
| `Self` |  |  |  |

## TerrainToolButton

Map Editor - Terrain Tool Button

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## TextureEntry

Texture Importer - Texture Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetResolution` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `IsAvailable` |  | `bool` |  |
| `OpenTextureViewer` |  | `void` |  |
| `Self` |  |  |  |

## TextureImporter

Texture Importer Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessOutputEntries` |  |  |  |
| `AccessSelf` |  |  |  |
| `AddCustomResolution` |  | `void` |  |
| `Cancel` |  | `void` |  |
| `GetLastConversion` |  | `CString` |  |
| `GetTextures` |  |  |  |
| `HasLastConversion` |  | `bool` |  |
| `Import` |  | `void` |  |
| `IsCustomResolution` |  | `bool` |  |
| `IsImporting` |  | `bool` |  |
| `Refresh` |  | `void` |  |
| `RemoveCustomResolution` |  | `void` |  |
| `Self` |  |  |  |
| `SetOutputScale` | `Arg0` | `void` |  |
| `SetResolution` | `Arg0` | `void` |  |

## TextureList

Texture List - In-memory texture list

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAutoUpdate` |  | `bool` |  |
| `GetCurrentDirectory` |  | `CString` |  |
| `GetDirectories` |  |  |  |
| `GetFilterString` |  | `CUTF8String` |  |
| `GetTextures` |  |  |  |
| `GetTotalSize` |  | `uint64` |  |
| `GetTotalTextureCount` |  | `int32` |  |
| `GoToParentDirectory` |  | `void` |  |
| `IsFlatView` |  | `bool` |  |
| `Self` |  |  |  |
| `SetAutoUpdate` | `Arg0` | `void` |  |
| `SetFilterString` |  | `void` |  |
| `SetFlatView` | `Arg0` | `void` |  |
| `SortByFormat` |  | `void` |  |
| `SortByMipMaps` |  | `void` |  |
| `SortByName` |  | `void` |  |
| `SortByRefCount` |  | `void` |  |
| `SortByResolution` |  | `void` |  |
| `SortBySize` |  | `void` |  |
| `UpdateTextureList` |  | `void` |  |

## TextureListDirectory

Texture Viewer - Directory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMipMaps` |  | `int32` |  |
| `GetName` |  |  |  |
| `GetRefcount` |  | `int32` |  |
| `GetSize` |  | `uint64` |  |
| `GetSubDirectoryCount` |  | `int32` |  |
| `GetTextureCount` |  | `int32` |  |
| `Self` |  |  |  |

## TextureListTexture

Texture Viewer - Texture

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFormat` |  | `CString` |  |
| `GetMipMaps` |  | `int32` |  |
| `GetName` |  |  |  |
| `GetRefcount` |  | `int32` |  |
| `GetResolution` |  | `CString` |  |
| `GetSize` |  | `uint64` |  |
| `Self` |  |  |  |

## TextureNodeWindow

Node Editor - Texture Node Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `FileSelect` |  | `void` |  |
| `Filename` |  | `CString` |  |
| `Self` |  |  |  |
| `Texture` |  |  |  |

## TextureViewer

Texture Viewer - In-memory texture viewer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Fit` |  | `void` |  |
| `GetAlpha` |  | `bool` |  |
| `GetAutoFit` |  | `bool` |  |
| `GetBlue` |  | `bool` |  |
| `GetConstantBuffers` |  |  |  |
| `GetEffect` |  |  |  |
| `GetFlipV` |  | `bool` |  |
| `GetGreen` |  | `bool` |  |
| `GetPointSampling` |  | `bool` |  |
| `GetRed` |  | `bool` |  |
| `GetTexture` |  |  |  |
| `GetTextureSize` |  | `CVector2f` |  |
| `GetTextureString` |  | `CString` |  |
| `GetTextureZoom` |  | `CString` |  |
| `GetToGamma` |  | `bool` |  |
| `OriginalSize` |  | `void` |  |
| `Self` |  |  |  |
| `SetAlpha` | `Arg0` | `void` |  |
| `SetAutoFit` | `Arg0` | `void` |  |
| `SetBlue` | `Arg0` | `void` |  |
| `SetFlipV` | `Arg0` | `void` |  |
| `SetGreen` | `Arg0` | `void` |  |
| `SetPointSampling` | `Arg0` | `void` |  |
| `SetRed` | `Arg0` | `void` |  |
| `SetToGamma` | `Arg0` | `void` |  |
| `ShowFileList` |  | `void` |  |

## Theater

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetOwner` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetID` |  | `uint32` |  |
| `GetName` |  | `CString` |  |
| `GetNumMobilizedUnitsInTheater` |  | `int32` |  |
| `GetNumProvinces` |  | `int32` |  |
| `GetOwner` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `Self` |  |  |  |

## Theme

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCategory` |  | `ThemeCategory` |  |
| `GetRequiredDlc` |  | `Dlc` |  |
| `AccessSelf` |  |  |  |
| `CanBeSelected` |  | `bool` |  |
| `GetCanBeSelectedDesc` |  | `CString` |  |
| `GetCategory` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetRequiredDlc` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasDlcRequirement` |  | `bool` |  |
| `IsNew` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsUseDynamicTheme` |  | `bool` |  |
| `MarkAsSeen` |  | `void` |  |
| `SelectSingleChoiceTheme` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleMultipleChoiceTheme` |  | `void` |  |

## ThemeBulkSelectionGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetRequiredDlc` |  | `Dlc` |  |
| `AccessSelf` |  |  |  |
| `CanBeSelected` |  | `bool` |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetRequiredDlc` |  |  |  |
| `GetThemeListDesc` |  | `CString` |  |
| `HasAvailableNewThemes` |  | `bool` |  |
| `HasDlcRequirement` |  | `bool` |  |
| `IsCustom` |  | `bool` |  |
| `IsDynamic` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsSpecialGroupType` |  | `bool` |  |
| `MarkThemesAsSeen` |  | `void` |  |
| `Self` |  |  |  |

## ThemeCategory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedSingleChoiceTheme` |  | `Theme` |  |
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetSelectedSingleChoiceTheme` |  |  |  |
| `GetThemes` |  |  |  |
| `HasAnyAvailableNewThemes` |  | `bool` |  |
| `OnSelectSingleChoiceTheme` |  | `void` |  |
| `Self` |  |  |  |

## ThemeWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDayNightEnableManualTime` |  | `PdxSetting` |  |
| `GetDayNightEnableSyncLocalTime` |  | `PdxSetting` |  |
| `GetDayNightEnabled` |  | `PdxSetting` |  |
| `GetDayNightManualTimeHour` |  | `PdxSetting` |  |
| `GetDayNightSpeed` |  | `PdxSetting` |  |
| `GetDayNightSunHours` |  | `PdxSetting` |  |
| `GetDayNightTimeOfSunrise` |  | `PdxSetting` |  |
| `GetSelectedBulkSelectionGroup` |  | `ThemeBulkSelectionGroup` |  |
| `AccessSelf` |  |  |  |
| `GetBulkSelectionGroups` |  |  |  |
| `GetFormattedValue` | `Arg0` | `CString` |  |
| `GetMultipleChoiceThemeCategories` |  |  |  |
| `GetScrollbarMax` | `Arg0` | `float` |  |
| `GetScrollbarMin` | `Arg0` | `float` |  |
| `GetScrollbarStep` | `Arg0` | `float` |  |
| `GetScrollbarValue` | `Arg0` | `float` |  |
| `GetSelectedBulkSelectionGroup` |  |  |  |
| `GetSingleChoiceThemeCategories` |  |  |  |
| `HasAnyAvailableNewBulkGroups` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `IsDawnOfWonderEnabled` |  | `bool` |  |
| `OnBulkGroupSelected` |  | `void` |  |
| `Save` |  | `void` |  |
| `SaveAndHide` |  | `void` |  |
| `ScrollbarOnValueChanged` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `Show` |  | `void` |  |
| `ToggleDayNightEnableManualTime` |  | `void` |  |
| `ToggleDayNightEnableSyncLocalTime` |  | `void` |  |
| `ToggleDayNightEnabled` |  | `void` |  |

## TickTaskData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAverageTime` |  | `int32` |  |
| `GetExecutionPriority` |  | `CString` |  |
| `GetExecutionPriorityFrame` |  | `int32` |  |
| `GetExecutionRate` |  | `CString` |  |
| `GetExecutionRateFrame` |  | `int32` |  |
| `GetHighestLockTime` |  | `int32` |  |
| `GetIndex` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetTimesExecuted` |  | `int32` |  |
| `IsPersisted` |  | `bool` |  |
| `OpenDetails` |  | `void` |  |
| `Self` |  |  |  |

## TickTaskDebuggerView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetGraphItems` |  |  |  |
| `GetGraphLines` |  |  |  |
| `Self` |  |  |  |

## TickTaskDetailsView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTickTask` |  | `TickTaskData` |  |
| `AccessSelf` |  |  |  |
| `GetTickTask` |  |  |  |
| `Self` |  |  |  |

## TickTaskGraphItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTickTask` |  | `TickTaskData` |  |
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetTickTask` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `Self` |  |  |  |

## TickTaskGraphLine

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

## TickTaskListView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTickTasks` |  |  |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## TimedModifier

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetEndDate` |  | `Date` |  |
| `GetStartDate` |  | `Date` |  |
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetEndDate` |  |  |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumRemainingDays` |  | `int32` |  |
| `GetOneLineDesc` |  | `CString` |  |
| `GetPercentageRemainingDays` |  | `float` |  |
| `GetRemainingDuration` |  | `CString` |  |
| `GetStartDate` |  |  |  |
| `GetTimeLeftFormatted` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsDecaying` |  | `bool` |  |
| `Self` |  |  |  |

## TimeKeeper

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentDate` |  | `Date` |  |
| `AccessSelf` |  |  |  |
| `CanAnyoneUnpause` |  | `bool` |  |
| `CanDecreaseGameSpeed` |  | `bool` |  |
| `CanIncreaseGameSpeed` |  | `bool` |  |
| `CanSetGameSpeed` |  | `bool` |  |
| `CanTogglePause` |  | `bool` |  |
| `DecreaseGameSpeed` |  | `void` |  |
| `GetCurrentDateWithDiff` | `Arg0` | `CString` |  |
| `GetDayOfWeek` |  | `CString` |  |
| `GetDecreaseSpeedTooltip` |  | `CString` |  |
| `GetGameSpeed` |  | `int32` |  |
| `GetGameSpeedFrame` |  | `int32` |  |
| `GetIncreaseSpeedTooltip` |  | `CString` |  |
| `GetPausedBy` |  | `CString` |  |
| `GetPausedText` |  | `CString` |  |
| `GetProgressOfWeek` |  | `int32` |  |
| `GetTickOfDay` |  | `int32` |  |
| `GetTimeAnyoneUnpause` |  | `int32` |  |
| `GetTimeOfDay` |  | `CString` |  |
| `GetTogglePauseTooltip` |  | `CString` |  |
| `IncreaseGameSpeed` |  | `void` |  |
| `IsPaused` |  | `bool` |  |
| `IsPausedByMe` |  | `bool` |  |
| `Self` |  |  |  |
| `SetGameSpeed` | `Arg0` | `void` |  |
| `TogglePause` |  | `void` |  |

## TimelineKeyframe

Timeline Widget - Keyframe

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsHovered` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `KeyframeColor` |  | `CVector4f` |  |
| `Label` |  | `CString` |  |
| `Self` |  |  |  |
| `SetHovered` | `Arg0` | `void` |  |
| `SetSelected` | `Arg0` | `void` |  |
| `TimePoint` |  | `float` |  |

## ToastMessageHandler

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMessageItem` |  | `PlayerMessageItem` |  |
| `AccessSelf` |  |  |  |
| `DismissMessage` |  | `void` |  |
| `GetMessageItem` |  |  |  |
| `HasMessage` |  | `bool` |  |
| `Self` |  |  |  |
| `StartDelayingMessage` |  | `void` |  |
| `StopDelayingMessage` |  | `void` |  |

## ToolDialog

Tool Dialog

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Buttons` |  |  |  |
| `Cancel` |  | `void` |  |
| `Close` |  | `void` |  |
| `Confirm` |  | `void` |  |
| `Self` |  |  |  |
| `Title` |  | `CString` |  |

## ToolDialogButton

Tool Dialog - Button

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `OnClick` |  | `bool` |  |
| `Self` |  |  |  |
| `Text` |  | `CString` |  |

## ToolMessageDialog

Tool Message Dialog

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsError` |  | `bool` |  |
| `IsInfo` |  | `bool` |  |
| `IsWarning` |  | `bool` |  |
| `Message` |  | `CString` |  |
| `Self` |  |  |  |

## ToolProgressDialog

Tool Progress Dialog

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetProgress` |  | `float` |  |
| `Self` |  |  |  |

## ToolProperty

Tool Property

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessActions` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetActions` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetLabel` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipWithLabel` |  | `CString` |  |
| `HasCheckbox` |  | `bool` |  |
| `HasDefaultValue` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsValueDefault` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |
| `SetSelected` | `Arg0` | `void` |  |
| `SetValueToDefault` |  | `void` |  |

## ToolProperty2SearchList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AreSelectButtonsVisible` |  | `bool` |  |
| `GetSelectedLabel` |  | `CUTF8String` |  |
| `GetSelectedValueColor` |  | `CVector4f` |  |
| `HasNext` |  | `bool` |  |
| `HasPrev` |  | `bool` |  |
| `NextEntryTooltip` |  | `CUTF8String` |  |
| `OpenSearchList` |  | `void` |  |
| `PrevEntryTooltip` |  | `CUTF8String` |  |
| `SelectNext` |  | `void` |  |
| `SelectPrev` |  | `void` |  |
| `Self` |  |  |  |

## ToolPropertyAction

Additional Action available on a given ToolProperty.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Execute` |  | `void` |  |
| `GetIcon` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `IsAvailable` |  | `bool` |  |
| `IsButton` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## ToolPropertyBool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsEnabled` |  | `bool` |  |
| `Self` |  |  |  |
| `SetEnabled` | `Arg0` | `void` |  |

## ToolPropertyCColor

Tool Property Color - CColor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetCColor` |  | `void` |  |

## ToolPropertyColor

Tool Property Color - Vector4f

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetColor` |  | `void` |  |

## ToolPropertyCString

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetString` |  | `CString` |  |
| `Self` |  |  |  |
| `SetString` |  | `void` |  |

## ToolPropertyCurve

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetPreviewTexture` | `Arg0, Arg1, Arg2, Arg3` |  |  |
| `HasCurveEditor` |  | `bool` |  |
| `OpenCurveEditor` |  | `void` |  |
| `ResetCurve` |  | `void` |  |
| `Self` |  |  |  |
| `SetCurve` | `Arg0` | `void` |  |
| `ToggleCurveEditor` |  | `void` |  |

## ToolPropertyFloat

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFloat` |  | `float` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetFloat` |  | `void` |  |

## ToolPropertyInt

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt` |  | `int32` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetInt` |  | `void` |  |

## ToolPropertyInt16

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt16` |  | `int16` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetInt16` |  | `void` |  |

## ToolPropertyInt8

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt8` |  | `int8` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetInt8` |  | `void` |  |

## ToolPropertyList

Tool Property List

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetLabel` |  | `CString` |  |
| `IsExpanded` |  | `bool` |  |
| `Self` |  |  |  |
| `SetExpanded` | `Arg0` | `void` |  |

## ToolPropertySearchList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetSelectedText` |  | `CUTF8String` |  |
| `GetSelectedValueColor` |  | `CVector4f` |  |
| `OpenSearchList` |  | `void` |  |
| `Self` |  |  |  |

## ToolPropertyString

Tool Property UTF8 String

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetString` |  | `CUTF8String` |  |
| `Self` |  |  |  |
| `SetString` |  | `void` |  |

## ToolPropertyUint

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetUint` |  | `uint32` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetUint` |  | `void` |  |

## ToolPropertyUint16

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetUint16` |  | `uint16` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetUint16` |  | `void` |  |

## ToolPropertyUint8

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetUint8` |  | `uint8` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `Self` |  |  |  |
| `SetUint8` |  | `void` |  |

## ToolPropertyUndoableSearchList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AreSelectButtonsVisible` |  | `bool` |  |
| `GetSelectedText` |  | `CUTF8String` |  |
| `GetSelectedValueColor` |  | `CVector4f` |  |
| `HasNext` |  | `bool` |  |
| `HasPrev` |  | `bool` |  |
| `NextEntryTooltip` |  | `CString` |  |
| `OpenSearchList` |  | `void` |  |
| `PrevEntryTooltip` |  | `CString` |  |
| `SelectNext` |  | `void` |  |
| `SelectPrev` |  | `void` |  |
| `Self` |  |  |  |

## ToolPropertyVec1fPercent

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetX` |  | `CString` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |

## ToolPropertyVec2f

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |

## ToolPropertyVec2fPercent

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |

## ToolPropertyVec2i

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |

## ToolPropertyVec3f

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValue` |  | `CVector3f` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `GetZ` |  | `CString` |  |
| `Self` |  |  |  |
| `SetValueFromColor` |  | `void` |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `SetZ` |  | `void` |  |

## ToolPropertyVec3i

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValue` |  | `CVector3i` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `GetZ` |  | `CString` |  |
| `Self` |  |  |  |
| `SetValueFromColor` |  | `void` |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `SetZ` |  | `void` |  |

## ToolPropertyVec4i

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValue` |  | `CVector4i` |  |
| `GetValueColor` |  | `CVector4f` |  |
| `GetW` |  | `CString` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `GetZ` |  | `CString` |  |
| `Self` |  |  |  |
| `SetValueFromColor` |  | `void` |  |
| `SetW` |  | `void` |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `SetZ` |  | `void` |  |

## ToolsPropertyDraggableValueFloat

Tools Property Draggable Float

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidator` |  |  |  |
| `GetValue` |  | `float` |  |
| `OnMouseDragFinished` |  | `void` |  |
| `OnMouseDragStarted` |  | `void` |  |
| `Self` |  |  |  |
| `SetValueFromText` |  | `void` |  |
| `UpdateValue` |  | `void` |  |

## ToolsPropertyDraggableValueInt

Tools Property Draggable Int

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidator` |  |  |  |
| `GetValue` |  | `int32` |  |
| `OnMouseDragFinished` |  | `void` |  |
| `OnMouseDragStarted` |  | `void` |  |
| `Self` |  |  |  |
| `SetValueFromText` |  | `void` |  |
| `UpdateValue` |  | `void` |  |

## ToolsPropertyDraggableValueVector2f

Tools Property Draggable Vector2 Float

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidatorX` |  |  |  |
| `GetValidatorY` |  |  |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `OnMouseDragFinishedX` |  | `void` |  |
| `OnMouseDragFinishedY` |  | `void` |  |
| `OnMouseDragStartedX` |  | `void` |  |
| `OnMouseDragStartedY` |  | `void` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `UpdateValueX` |  | `void` |  |
| `UpdateValueY` |  | `void` |  |

## ToolsPropertyDraggableValueVector2i

Tools Property Draggable Vector2 Integer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidatorX` |  |  |  |
| `GetValidatorY` |  |  |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `OnMouseDragFinishedX` |  | `void` |  |
| `OnMouseDragFinishedY` |  | `void` |  |
| `OnMouseDragStartedX` |  | `void` |  |
| `OnMouseDragStartedY` |  | `void` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `UpdateValueX` |  | `void` |  |
| `UpdateValueY` |  | `void` |  |

## ToolsPropertyDraggableValueVector3f

Tools Property Draggable Vector3 Float

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidatorX` |  |  |  |
| `GetValidatorY` |  |  |  |
| `GetValidatorZ` |  |  |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `GetZ` |  | `CString` |  |
| `OnMouseDragFinishedX` |  | `void` |  |
| `OnMouseDragFinishedY` |  | `void` |  |
| `OnMouseDragFinishedZ` |  | `void` |  |
| `OnMouseDragStartedX` |  | `void` |  |
| `OnMouseDragStartedY` |  | `void` |  |
| `OnMouseDragStartedZ` |  | `void` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `SetZ` |  | `void` |  |
| `UpdateValueX` |  | `void` |  |
| `UpdateValueY` |  | `void` |  |
| `UpdateValueZ` |  | `void` |  |

## ToolsPropertyDraggableValueVector3i

Tools Property Draggable Vector3 Integer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidatorX` |  |  |  |
| `GetValidatorY` |  |  |  |
| `GetValidatorZ` |  |  |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `GetZ` |  | `CString` |  |
| `OnMouseDragFinishedX` |  | `void` |  |
| `OnMouseDragFinishedY` |  | `void` |  |
| `OnMouseDragFinishedZ` |  | `void` |  |
| `OnMouseDragStartedX` |  | `void` |  |
| `OnMouseDragStartedY` |  | `void` |  |
| `OnMouseDragStartedZ` |  | `void` |  |
| `Self` |  |  |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `SetZ` |  | `void` |  |
| `UpdateValueX` |  | `void` |  |
| `UpdateValueY` |  | `void` |  |
| `UpdateValueZ` |  | `void` |  |

## ToolsPropertyDraggableValueVector4i

Tools Property Draggable Vector4 Integer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValidatorW` |  |  |  |
| `GetValidatorX` |  |  |  |
| `GetValidatorY` |  |  |  |
| `GetValidatorZ` |  |  |  |
| `GetW` |  | `CString` |  |
| `GetX` |  | `CString` |  |
| `GetY` |  | `CString` |  |
| `GetZ` |  | `CString` |  |
| `OnMouseDragFinishedW` |  | `void` |  |
| `OnMouseDragFinishedX` |  | `void` |  |
| `OnMouseDragFinishedY` |  | `void` |  |
| `OnMouseDragFinishedZ` |  | `void` |  |
| `OnMouseDragStartedW` |  | `void` |  |
| `OnMouseDragStartedX` |  | `void` |  |
| `OnMouseDragStartedY` |  | `void` |  |
| `OnMouseDragStartedZ` |  | `void` |  |
| `Self` |  |  |  |
| `SetW` |  | `void` |  |
| `SetX` |  | `void` |  |
| `SetY` |  | `void` |  |
| `SetZ` |  | `void` |  |
| `UpdateValueW` |  | `void` |  |
| `UpdateValueX` |  | `void` |  |
| `UpdateValueY` |  | `void` |  |
| `UpdateValueZ` |  | `void` |  |

## ToolsPropertyPath

Tools Property Path

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetPathFontColor` |  | `CVector4f` |  |
| `GetPathValue` |  | `CString` |  |
| `GetTooltipText` |  | `CString` |  |
| `OpenFileDialog` |  | `void` |  |
| `Self` |  |  |  |
| `SetPathFromText` |  | `void` |  |

## ToolsPropertyRangedValueFloat

Tools Property Ranged Float

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMax` |  | `float` |  |
| `GetMin` |  | `float` |  |
| `GetStep` |  | `float` |  |
| `GetValue` |  | `float` |  |
| `GetWheelStep` |  | `float` |  |
| `OnSetValueEnd` | `Arg0` | `void` |  |
| `OnSetValueStart` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetValue` |  | `void` |  |
| `SetValueFromText` | `Arg0` | `void` |  |

## ToolsPropertyRangedValueInt

Tools Property Ranged Int

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMax` |  | `int32` |  |
| `GetMin` |  | `int32` |  |
| `GetStep` |  | `int32` |  |
| `GetValue` |  | `int32` |  |
| `GetWheelStep` |  | `int32` |  |
| `OnSetValueEnd` | `Arg0` | `void` |  |
| `OnSetValueStart` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetValue` |  | `void` |  |
| `SetValueFromText` | `Arg0` | `void` |  |

## ToolsPropertyTextureStringValue

Tools Property Texture Value

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTexturePath` |  | `CString` |  |
| `SelectTexture` |  | `void` |  |
| `Self` |  |  |  |
| `SetValueFromText` |  | `void` |  |

## ToolsPropertyTextureValue

Tools Property Texture

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTexturePath` |  | `CString` |  |
| `SelectTexture` |  | `void` |  |
| `Self` |  |  |  |
| `SetValueFromText` |  | `void` |  |

## ToolsPropertyValueList

Tools property representing a list of elements

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddItem` |  | `void` |  |
| `CanAddOrRemoveItems` |  | `bool` |  |
| `RemoveItem` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## ToolsPropertyValueListEntry

Single element in the datamodel provided by a ToolsPropertyValueList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIndex` |  | `int32` |  |
| `GetLabel` |  | `CString` |  |
| `HasLabel` |  | `bool` |  |
| `IsItemVisible` |  | `bool` |  |
| `Self` |  |  |  |

## ToolsPropertyVfsMountPath

Tools Property for Vfs-Mount-Path

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CloseBrowser` |  | `void` |  |
| `GetFullPath` |  | `CString` |  |
| `GetFullPathFromMountTag` | `Arg0` | `CString` |  |
| `GetMountTagIndex` |  | `CVector2i` |  |
| `GetPathFontColor` |  | `CVector4f` |  |
| `GetTags` |  |  |  |
| `GetVfsMountPathAsString` |  | `CString` |  |
| `GetVfsPath` |  | `CString` |  |
| `IsBrowserOpen` |  | `bool` |  |
| `IsDisplayModeFullPath` |  | `bool` |  |
| `OpenBrowser` |  | `void` |  |
| `Self` |  |  |  |
| `SetMountTagIndex` |  | `void` |  |
| `SetVfsPathFromText` |  | `void` |  |
| `ToggleBrowser` |  | `void` |  |
| `ToggleDisplayMode` |  | `void` |  |

## ToolsSearch

Tools Search (OmniSearch)

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Results` |  |  |  |
| `Search` |  | `void` |  |
| `Self` |  |  |  |

## ToolsSearchResult

Tools Search - Result

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Callback` |  | `void` |  |
| `Description` |  | `CUTF8String` |  |
| `DoesTooltipMatch` |  | `bool` |  |
| `Self` |  |  |  |
| `SortScore` |  | `int32` |  |
| `Text` |  | `CUTF8String` |  |
| `Tooltip` |  | `CUTF8String` |  |

## ToolsUndoableValueBundleBool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleCColor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleColor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleCString

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` |  | `void` |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleFloat

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` |  | `void` |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleInt

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` |  | `void` |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleString

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` |  | `void` |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleUint

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` |  | `void` |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleUint16

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` |  | `void` |  |
| `ShouldDisplayMixedValuesOverlay` |  | `bool` |  |

## ToolsUndoableValueBundleVec2f

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0, Arg1` | `void` |  |
| `SetValue` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` | `Arg0` | `void` |  |
| `ShouldDisplayMixedValuesOverlay` | `Arg0` | `bool` |  |

## ToolsUndoableValueBundleVec2i

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0, Arg1` | `void` |  |
| `SetValue` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` | `Arg0` | `void` |  |
| `ShouldDisplayMixedValuesOverlay` | `Arg0` | `bool` |  |

## ToolsUndoableValueBundleVec3f

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` | `Arg0` | `CString` |  |
| `GetValue` |  | `CVector3f` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0, Arg1` | `void` |  |
| `SetValue` | `Arg0` | `void` |  |
| `SetValueFromColor` |  | `void` |  |
| `SetValueOnFocusOut` | `Arg0` | `void` |  |
| `ShouldDisplayMixedValuesOverlay` | `Arg0` | `bool` |  |

## ToolsUndoableValueBundleVec3i

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0, Arg1` | `void` |  |
| `SetValue` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` | `Arg0` | `void` |  |
| `ShouldDisplayMixedValuesOverlay` | `Arg0` | `bool` |  |

## ToolsUndoableValueBundleVec4i

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTextboxDisplayValue` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `SetIsFocused` | `Arg0, Arg1` | `void` |  |
| `SetValue` | `Arg0` | `void` |  |
| `SetValueOnFocusOut` | `Arg0` | `void` |  |
| `ShouldDisplayMixedValuesOverlay` | `Arg0` | `bool` |  |

## TooltipInfo

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTintColor` |  | `CVector4f` |  |
| `Self` |  |  |  |

## TopFrontend

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAlerts` |  |  |  |
| `AccessHiddenAlerts` |  |  |  |
| `AccessHiddenImportantActions` |  |  |  |
| `AccessHiddenProposals` |  |  |  |
| `AccessImportantActions` |  |  |  |
| `AccessProposals` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCurrentSituationSetting` |  | `int32` |  |
| `GetNumHiddenImportantActions` |  | `int32` |  |
| `GetNumUnreadImportantActions` |  | `int32` |  |
| `GetTotalNumOfImportantActionGroups` |  | `int32` |  |
| `Self` |  |  |  |
| `UnhideAllImportantActions` |  | `void` |  |

## TopScope

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AddList` | `Arg0, Arg1` | `TopScope` |  |
| `AddScope` | `Arg0, Arg1` | `TopScope` |  |
| `GetLocalVariable` | `Arg0` | `Scope` |  |
| `GetRootScope` |  | `Scope` |  |
| `SetRoot` | `Arg0` | `TopScope` |  |
| `gsIG` | `Arg0` | `InterestGroup` |  |
| `gsInterestGroup` | `Arg0` | `InterestGroup` |  |
| `sAmendmentType` | `Arg0` | `AmendmentType` |  |
| `sB` | `Arg0` | `Building` |  |
| `sBG` | `Arg0` | `BuildingGroup` |  |
| `sBT` | `Arg0` | `BuildingType` |  |
| `sBuilding` | `Arg0` | `Building` |  |
| `sBuildingGroup` | `Arg0` | `BuildingGroup` |  |
| `sBuildingType` | `Arg0` | `BuildingType` |  |
| `sC` | `Arg0` | `Country` |  |
| `sCF` | `Arg0` | `CountryFormation` |  |
| `sCM` | `Arg0` | `Company` |  |
| `sCMT` | `Arg0` | `CompanyType` |  |
| `sCOT` | `Arg0` | `CommanderOrderType` |  |
| `sCR` | `Arg0` | `CharacterRole` |  |
| `sCU` | `Arg0` | `Culture` |  |
| `sCW` | `Arg0` | `CivilWar` |  |
| `sCha` | `Arg0` | `Character` |  |
| `sCharacter` | `Arg0` | `Character` |  |
| `sCharacterRole` | `Arg0` | `CharacterRole` |  |
| `sCivilWar` | `Arg0` | `CivilWar` |  |
| `sCommanderOrderType` | `Arg0` | `CommanderOrderType` |  |
| `sCompany` | `Arg0` | `Company` |  |
| `sCompanyType` | `Arg0` | `CompanyType` |  |
| `sCountry` | `Arg0` | `Country` |  |
| `sCountryFormation` | `Arg0` | `CountryFormation` |  |
| `sCulture` | `Arg0` | `Culture` |  |
| `sD` | `Arg0` | `Decision` |  |
| `sDA` | `Arg0` | `DiplomaticAction` |  |
| `sDC` | `Arg0` | `DiplomaticCatalyst` |  |
| `sDCC` | `Arg0` | `DiplomaticCatalystCategory` |  |
| `sDCT` | `Arg0` | `DiplomaticCatalystType` |  |
| `sDD` | `Arg0` | `DiplomaticDemand` |  |
| `sDP` | `Arg0` | `DiplomaticPlay` |  |
| `sDPT` | `Arg0` | `DiplomaticPlayType` |  |
| `sDR` | `Arg0` | `DiplomaticRelations` |  |
| `sDecision` | `Arg0` | `Decision` |  |
| `sDiplomaticAction` | `Arg0` | `DiplomaticAction` |  |
| `sDiplomaticCatalyst` | `Arg0` | `DiplomaticCatalyst` |  |
| `sDiplomaticCatalystCategory` | `Arg0` | `DiplomaticCatalystCategory` |  |
| `sDiplomaticCatalystType` | `Arg0` | `DiplomaticCatalystType` |  |
| `sDiplomaticDemand` | `Arg0` | `DiplomaticDemand` |  |
| `sDiplomaticPact` | `Arg0` | `DiplomaticPact` |  |
| `sDiplomaticPlay` | `Arg0` | `DiplomaticPlay` |  |
| `sDiplomaticPlayType` | `Arg0` | `DiplomaticPlayType` |  |
| `sDiplomaticRelations` | `Arg0` | `DiplomaticRelations` |  |
| `sF` | `Arg0` | `Front` |  |
| `sFront` | `Arg0` | `Front` |  |
| `sG` | `Arg0` | `Goods` |  |
| `sGoods` | `Arg0` | `Goods` |  |
| `sHC` | `Arg0` | `HarvestCondition` |  |
| `sHCA` | `Arg0` | `HarvestConditionArea` |  |
| `sHCT` | `Arg0` | `HarvestConditionType` |  |
| `sHQ` | `Arg0` | `Hq` |  |
| `sHarvestCondition` | `Arg0` | `HarvestCondition` |  |
| `sHarvestConditionArea` | `Arg0` | `HarvestConditionArea` |  |
| `sHarvestConditionType` | `Arg0` | `HarvestConditionType` |  |
| `sIGT` | `Arg0` | `InterestGroupTrait` |  |
| `sIdeology` | `Arg0` | `Ideology` |  |
| `sInstitution` | `Arg0` | `Institution` |  |
| `sInstitutionType` | `Arg0` | `InstitutionType` |  |
| `sInterestGroupTrait` | `Arg0` | `InterestGroupTrait` |  |
| `sInterestTierType` | `Arg0` | `InterestTierType` |  |
| `sJE` | `Arg0` | `JournalEntry` |  |
| `sJournalEntry` | `Arg0` | `JournalEntry` |  |
| `sL` | `Arg0` | `Law` |  |
| `sLaw` | `Arg0` | `Law` |  |
| `sLawType` | `Arg0` | `LawType` |  |
| `sMilitaryFormation` | `Arg0` | `MilitaryFormation` |  |
| `sP` | `Arg0` | `Party` |  |
| `sPB` | `Arg0` | `PowerBloc` |  |
| `sPBI` | `Arg0` | `PowerBlocIdentity` |  |
| `sPBP` | `Arg0` | `PowerBlocPrinciple` |  |
| `sPL` | `Arg0` | `PoliticalLobby` |  |
| `sPLA` | `Arg0` | `PoliticalLobbyAppeasementFactor` |  |
| `sPLT` | `Arg0` | `PoliticalLobbyType` |  |
| `sPM` | `Arg0` | `PoliticalMovement` |  |
| `sPMC` | `Arg0` | `PoliticalMovementCategory` |  |
| `sPMT` | `Arg0` | `PoliticalMovementType` |  |
| `sPT` | `Arg0` | `PopType` |  |
| `sPact` | `Arg0` | `DiplomaticPact` |  |
| `sParty` | `Arg0` | `Party` |  |
| `sPoliticalLobby` | `Arg0` | `PoliticalLobby` |  |
| `sPoliticalLobbyAppeasement` | `Arg0` | `PoliticalLobbyAppeasementFactor` |  |
| `sPoliticalLobbyType` | `Arg0` | `PoliticalLobbyType` |  |
| `sPoliticalMovement` | `Arg0` | `PoliticalMovement` |  |
| `sPoliticalMovementCategory` | `Arg0` | `PoliticalMovementCategory` |  |
| `sPoliticalMovementType` | `Arg0` | `PoliticalMovementType` |  |
| `sPop` | `Arg0` | `Pop` |  |
| `sPopType` | `Arg0` | `PopType` |  |
| `sPowerBloc` | `Arg0` | `PowerBloc` |  |
| `sPowerBlocIdentity` | `Arg0` | `PowerBlocIdentity` |  |
| `sPowerBlocPrinciple` | `Arg0` | `PowerBlocPrinciple` |  |
| `sPowerBlocPrincipleGroup` | `Arg0` | `PowerBlocPrincipleGroup` |  |
| `sProvince` | `Arg0` | `Province` |  |
| `sReligion` | `Arg0` | `Religion` |  |
| `sS` | `Arg0` | `State` |  |
| `sSR` | `Arg0` | `StrategicRegion` |  |
| `sSW` | `Arg0` | `Sway` |  |
| `sState` | `Arg0` | `State` |  |
| `sStateRegion` | `Arg0` | `StateRegion` |  |
| `sStrait` | `Arg0` | `Strait` |  |
| `sStrategicRegion` | `Arg0` | `StrategicRegion` |  |
| `sSway` | `Arg0` | `Sway` |  |
| `sT` | `Arg0` | `Technology` |  |
| `sTechnology` | `Arg0` | `Technology` |  |
| `sTreaty` | `Arg0` | `Treaty` |  |
| `sTreatyArticle` | `Arg0` | `Article` |  |
| `sW` | `Arg0` | `War` |  |
| `sWar` | `Arg0` | `War` |  |
| `sWarGoal` | `Arg0` | `WarGoal` |  |
| `sWarGoalType` | `Arg0` | `WarGoalType` |  |
| `AccessSelf` |  |  |  |
| `End` |  | `TopScope` |  |
| `GetFlagName` | `Arg0` | `CString` |  |
| `GetLocalVariable` | `Arg0` |  |  |
| `GetRootScope` |  |  |  |
| `GetScriptValueDesc` | `Arg0` | `CString` |  |
| `GetValue` | `Arg0` | `CFixedPoint` |  |
| `ScriptValue` | `Arg0` | `CFixedPoint` |  |
| `Self` |  |  |  |
| `gsIG` | `Arg0` |  |  |
| `gsInterestGroup` | `Arg0` |  |  |
| `sAmendmentType` | `Arg0` |  |  |
| `sB` | `Arg0` |  |  |
| `sBG` | `Arg0` |  |  |
| `sBT` | `Arg0` |  |  |
| `sBuilding` | `Arg0` |  |  |
| `sBuildingGroup` | `Arg0` |  |  |
| `sBuildingType` | `Arg0` |  |  |
| `sC` | `Arg0` |  |  |
| `sCF` | `Arg0` |  |  |
| `sCM` | `Arg0` |  |  |
| `sCMT` | `Arg0` |  |  |
| `sCOT` | `Arg0` |  |  |
| `sCR` | `Arg0` |  |  |
| `sCU` | `Arg0` |  |  |
| `sCW` | `Arg0` |  |  |
| `sCha` | `Arg0` |  |  |
| `sCharacter` | `Arg0` |  |  |
| `sCharacterRole` | `Arg0` |  |  |
| `sCivilWar` | `Arg0` |  |  |
| `sCommanderOrderType` | `Arg0` |  |  |
| `sCompany` | `Arg0` |  |  |
| `sCompanyType` | `Arg0` |  |  |
| `sCountry` | `Arg0` |  |  |
| `sCountryFormation` | `Arg0` |  |  |
| `sCulture` | `Arg0` |  |  |
| `sD` | `Arg0` |  |  |
| `sDA` | `Arg0` |  |  |
| `sDC` | `Arg0` |  |  |
| `sDCC` | `Arg0` |  |  |
| `sDCT` | `Arg0` |  |  |
| `sDD` | `Arg0` |  |  |
| `sDP` | `Arg0` |  |  |
| `sDPT` | `Arg0` |  |  |
| `sDR` | `Arg0` |  |  |
| `sDecision` | `Arg0` |  |  |
| `sDiplomaticAction` | `Arg0` |  |  |
| `sDiplomaticCatalyst` | `Arg0` |  |  |
| `sDiplomaticCatalystCategory` | `Arg0` |  |  |
| `sDiplomaticCatalystType` | `Arg0` |  |  |
| `sDiplomaticDemand` | `Arg0` |  |  |
| `sDiplomaticPact` | `Arg0` |  |  |
| `sDiplomaticPlay` | `Arg0` |  |  |
| `sDiplomaticPlayType` | `Arg0` |  |  |
| `sDiplomaticRelations` | `Arg0` |  |  |
| `sF` | `Arg0` |  |  |
| `sFront` | `Arg0` |  |  |
| `sG` | `Arg0` |  |  |
| `sGoods` | `Arg0` |  |  |
| `sHC` | `Arg0` |  |  |
| `sHCA` | `Arg0` |  |  |
| `sHCT` | `Arg0` |  |  |
| `sHQ` | `Arg0` |  |  |
| `sHarvestCondition` | `Arg0` |  |  |
| `sHarvestConditionArea` | `Arg0` |  |  |
| `sHarvestConditionType` | `Arg0` |  |  |
| `sIGT` | `Arg0` |  |  |
| `sIdeology` | `Arg0` |  |  |
| `sInstitution` | `Arg0` |  |  |
| `sInstitutionType` | `Arg0` |  |  |
| `sInterestGroupTrait` | `Arg0` |  |  |
| `sInterestTierType` | `Arg0` |  |  |
| `sJE` | `Arg0` |  |  |
| `sJournalEntry` | `Arg0` |  |  |
| `sL` | `Arg0` |  |  |
| `sLaw` | `Arg0` |  |  |
| `sLawType` | `Arg0` |  |  |
| `sMilitaryFormation` | `Arg0` |  |  |
| `sP` | `Arg0` |  |  |
| `sPB` | `Arg0` |  |  |
| `sPBI` | `Arg0` |  |  |
| `sPBP` | `Arg0` |  |  |
| `sPL` | `Arg0` |  |  |
| `sPLA` | `Arg0` |  |  |
| `sPLT` | `Arg0` |  |  |
| `sPM` | `Arg0` |  |  |
| `sPMC` | `Arg0` |  |  |
| `sPMT` | `Arg0` |  |  |
| `sPT` | `Arg0` |  |  |
| `sPact` | `Arg0` |  |  |
| `sParty` | `Arg0` |  |  |
| `sPoliticalLobby` | `Arg0` |  |  |
| `sPoliticalLobbyAppeasement` | `Arg0` |  |  |
| `sPoliticalLobbyType` | `Arg0` |  |  |
| `sPoliticalMovement` | `Arg0` |  |  |
| `sPoliticalMovementCategory` | `Arg0` |  |  |
| `sPoliticalMovementType` | `Arg0` |  |  |
| `sPop` | `Arg0` |  |  |
| `sPopType` | `Arg0` |  |  |
| `sPowerBloc` | `Arg0` |  |  |
| `sPowerBlocIdentity` | `Arg0` |  |  |
| `sPowerBlocPrinciple` | `Arg0` |  |  |
| `sPowerBlocPrincipleGroup` | `Arg0` |  |  |
| `sProvince` | `Arg0` |  |  |
| `sReligion` | `Arg0` |  |  |
| `sS` | `Arg0` |  |  |
| `sSR` | `Arg0` |  |  |
| `sSW` | `Arg0` |  |  |
| `sState` | `Arg0` |  |  |
| `sStateRegion` | `Arg0` |  |  |
| `sStrait` | `Arg0` |  |  |
| `sStrategicRegion` | `Arg0` |  |  |
| `sSway` | `Arg0` |  |  |
| `sT` | `Arg0` |  |  |
| `sTechnology` | `Arg0` |  |  |
| `sTreaty` | `Arg0` |  |  |
| `sTreatyArticle` | `Arg0` |  |  |
| `sW` | `Arg0` |  |  |
| `sWar` | `Arg0` |  |  |
| `sWarGoal` | `Arg0` |  |  |
| `sWarGoalType` | `Arg0` |  |  |

## TransferFormationPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetLeftFormation` |  | `MilitaryFormation` |  |
| `GetLeftStagedFormation` |  | `StagedFormation` |  |
| `GetRightFormation` |  | `MilitaryFormation` |  |
| `GetRightStagedFormation` |  | `StagedFormation` |  |
| `AccessSelf` |  |  |  |
| `CanReset` |  | `bool` |  |
| `Confirm` |  | `Command` |  |
| `DeselectLeftFormation` |  | `void` |  |
| `DeselectRightFormation` |  | `void` |  |
| `GetConfirmDesc` |  | `CString` |  |
| `GetConfirmationSound` |  |  |  |
| `GetContextualUnitTypeIcon` |  | `CString` |  |
| `GetCulturalTexture` | `Arg0` |  |  |
| `GetHintDesc` |  | `CString` |  |
| `GetLeftFormation` |  |  |  |
| `GetLeftStagedFormation` |  |  |  |
| `GetOrganizationImpactDesc` |  | `CString` |  |
| `GetResetDesc` |  | `CString` |  |
| `GetRightFormation` |  |  |  |
| `GetRightStagedFormation` |  |  |  |
| `GetSelectedUnitsDesc` |  | `CString` |  |
| `GetTravelTimeDesc` |  | `CString` |  |
| `HasAnyUnitSelectedLeft` |  | `bool` |  |
| `HasAnyUnitSelectedRight` |  | `bool` |  |
| `HasArmyContext` |  | `bool` |  |
| `HasFleetContext` |  | `bool` |  |
| `HasLeftFormation` |  | `bool` |  |
| `HasRightFormation` |  | `bool` |  |
| `IsFormationSelected` | `Arg0` | `bool` |  |
| `MoveConscripts` | `Arg0` | `void` |  |
| `MovePercentageLeft` | `Arg0` | `void` |  |
| `MovePercentageRight` | `Arg0` | `void` |  |
| `MoveRegulars` | `Arg0` | `void` |  |
| `MoveSelectedFromLeftToRight` |  | `void` |  |
| `MoveSelectedFromRightToLeft` |  | `void` |  |
| `MoveShips` | `Arg0` | `void` |  |
| `Reset` |  | `void` |  |
| `SelectLeftFormation` |  | `void` |  |
| `SelectRightFormation` |  | `void` |  |
| `Self` |  |  |  |
| `SetSelectedLeftFormation` | `Arg0` | `void` |  |
| `SetSelectedRightFormation` | `Arg0` | `void` |  |

## TransportPlannerPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArmyFormation` |  | `MilitaryFormation` |  |
| `GetSelectedFleet` |  | `MilitaryFormation` |  |
| `GetTargetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetArmyFormation` |  |  |  |
| `GetCommandValidityDesc` |  | `CString` |  |
| `GetFleetsForTransport` |  |  |  |
| `GetInvolvementChangeDesc` |  | `CString` |  |
| `GetSelectedFleet` |  |  |  |
| `GetSortedFleets` |  |  |  |
| `GetTargetName` |  | `CString` |  |
| `GetTargetState` |  |  |  |
| `GetTransportCommand` | `Arg0` | `Command` |  |
| `HasFrontTarget` |  | `bool` |  |
| `HasSelectedFleet` |  | `bool` |  |
| `IsFleetSelected` | `Arg0` | `bool` |  |
| `OnSelectedFleet` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `StartTransport` |  | `Command` |  |

## Treaty

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBindingPeriodEndGameDate` |  | `Date` |  |
| `GetEnforcedOnCountry` |  | `Country` |  |
| `GetEnforcerCountry` |  | `Country` |  |
| `GetFirstCountry` |  | `Country` |  |
| `GetLeftCountry` |  | `Country` |  |
| `GetOtherCountry` | `Arg0` | `Country` |  |
| `GetRightCountry` |  | `Country` |  |
| `GetSecondCountry` |  | `Country` |  |
| `GetShippingLaneOf` | `Arg0` | `ShippingLane` |  |
| `GetStartGameDate` |  | `Date` |  |
| `MakeScope` |  | `Scope` |  |
| `AcceptTreatyProposal` |  | `Command` |  |
| `AccessSelf` |  |  |  |
| `AreObligationsEffectuated` |  | `bool` |  |
| `Binds` | `Arg0` | `bool` |  |
| `DeclineTreatyProposal` |  | `Command` |  |
| `DoesCallInObligation` | `Arg0` | `bool` |  |
| `DoesOweObligation` | `Arg0` | `bool` |  |
| `GetAcceptance` | `Arg0` | `int32` |  |
| `GetAcceptanceBreakdown` | `Arg0` | `CString` |  |
| `GetAllArticles` |  |  |  |
| `GetBindingDays` |  | `int32` |  |
| `GetBindingDaysLeft` |  | `int32` |  |
| `GetBindingPeriodEndGameDate` |  |  |  |
| `GetBindingPeriodFormatted` |  | `CString` |  |
| `GetBindingPeriodRemainingFormatted` |  | `CString` |  |
| `GetBreakPenaltiesDesc` | `Arg0` | `CString` |  |
| `GetCanWithdrawDesc` | `Arg0` | `CString` |  |
| `GetCost` | `Arg0` | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDemands` |  |  |  |
| `GetDirectedEffectsDesc` | `Arg0` | `CString` |  |
| `GetEffectsDesc` |  | `CString` |  |
| `GetEnforcedOnCountry` |  |  |  |
| `GetEnforcerCountry` |  |  |  |
| `GetFirstCountry` |  |  |  |
| `GetImmediateEffectsDesc` | `Arg0` | `CString` |  |
| `GetInvolvementEffectsDesc` |  | `CString` |  |
| `GetLeftCountry` |  |  |  |
| `GetMutualAgreements` |  |  |  |
| `GetMutualEffectsDesc` |  | `CString` |  |
| `GetMutualModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNonFulfilledArticlesFromSource` | `Arg0` |  |  |
| `GetNonFulfillmentDescFor` | `Arg0` | `CString` |  |
| `GetOffers` |  |  |  |
| `GetOtherCountry` | `Arg0` |  |  |
| `GetRelationsEffectDesc` |  | `CString` |  |
| `GetRightCountry` |  |  |  |
| `GetSecondCountry` |  |  |  |
| `GetShippingLaneOf` | `Arg0` |  |  |
| `GetSourceModifierDesc` |  | `CString` |  |
| `GetStartDate` |  | `CString` |  |
| `GetStartGameDate` |  |  |  |
| `GetTargetModifierDesc` |  | `CString` |  |
| `GetThreatenedHostilityTypeDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTreatyDeclineObligationDesc` |  | `CString` |  |
| `GetWithdrawPenaltiesDesc` | `Arg0` | `CString` |  |
| `IsDraft` |  | `bool` |  |
| `IsEnforced` |  | `bool` |  |
| `IsEnforcedOn` | `Arg0` | `bool` |  |
| `IsFrozenFor` | `Arg0` | `bool` |  |
| `IsFrozenForBothCountries` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsThreateningHostilities` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `TogglePinInOutliner` |  | `void` |  |
| `WithdrawFromTreaty` |  | `Command` |  |

## TreatyDraft

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAmendedTreaty` |  | `Treaty` |  |
| `GetFirstCountry` |  | `Country` |  |
| `GetLeftCountry` |  | `Country` |  |
| `GetOtherCountry` | `Arg0` | `Country` |  |
| `GetRightCountry` |  | `Country` |  |
| `GetSecondCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `AddArticle` | `Arg0, Arg1, Arg2` | `void` |  |
| `AddArticleDraft` | `Arg0` | `void` |  |
| `CanAskForObligation` | `Arg0` | `bool` |  |
| `CanCallInObligation` | `Arg0` | `bool` |  |
| `CanIncludeArticleDraft` | `Arg0` | `bool` |  |
| `CanIncludeArticleType` | `Arg0, Arg1, Arg2` | `bool` |  |
| `CanMakeThisWork` | `Arg0` | `bool` |  |
| `CanOweObligation` | `Arg0` | `bool` |  |
| `CanThreatenNavalHostilities` |  | `bool` |  |
| `GetAcceptance` | `Arg0` | `int32` |  |
| `GetAcceptanceStatus` | `Arg0` | `CString` |  |
| `GetAmendedTreaty` |  |  |  |
| `GetArticleTypeAcceptance` | `Arg0, Arg1` | `int32` |  |
| `GetArticleTypeAcceptanceBreakdown` | `Arg0, Arg1` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithBuilding` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithCompany` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithCompanyAndBuilding` | `Arg0, Arg1, Arg2, Arg3` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithCountry` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithGood` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithLaw` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithRegion` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithShip` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceBreakdownWithState` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetArticleTypeAcceptanceWithBuilding` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithCompany` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithCompanyAndBuilding` | `Arg0, Arg1, Arg2, Arg3` | `int32` |  |
| `GetArticleTypeAcceptanceWithCountry` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithGood` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithLaw` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithRegion` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithShip` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeAcceptanceWithState` | `Arg0, Arg1, Arg2` | `int32` |  |
| `GetArticleTypeInfluenceCostDesc` | `Arg0, Arg1` | `CString` |  |
| `GetAskForObligationDesc` | `Arg0` | `CString` |  |
| `GetBindingDays` |  | `int32` |  |
| `GetBindingPeriodDesc` |  | `CString` |  |
| `GetBindingPeriodFormatted` |  | `CString` |  |
| `GetBreakPenaltiesDesc` |  | `CString` |  |
| `GetCallInObligationDesc` | `Arg0` | `CString` |  |
| `GetCanIncludeArticleDraftDesc` | `Arg0` | `CString` |  |
| `GetCanIncludeArticleTypeDesc` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetCanMakeThisWorkDesc` | `Arg0` | `CString` |  |
| `GetCost` | `Arg0` | `CFixedPoint` |  |
| `GetCustomName` |  | `CString` |  |
| `GetFirstCountry` |  |  |  |
| `GetImmediateEffectsDesc` |  | `CString` |  |
| `GetLeftCountry` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNegativeAcceptanceBreakdown` | `Arg0` | `CString` |  |
| `GetNumAvailableInputOptions` | `Arg0, Arg1` | `int32` |  |
| `GetOtherCountry` | `Arg0` |  |  |
| `GetOweObligationDesc` | `Arg0` | `CString` |  |
| `GetPositiveAcceptanceBreakdown` | `Arg0` | `CString` |  |
| `GetPotentialDemands` |  |  |  |
| `GetPotentialMutualAgreements` |  |  |  |
| `GetPotentialOffers` |  |  |  |
| `GetRelationsEffectDesc` |  | `CString` |  |
| `GetRightCountry` |  |  |  |
| `GetSecondCountry` |  |  |  |
| `GetSelectedDemands` |  |  |  |
| `GetSelectedDirectedArticles` | `Arg0` |  |  |
| `GetSelectedMutualAgreements` |  |  |  |
| `GetSelectedOffers` |  |  |  |
| `GetThreatenNavalHostilitiesDesc` |  | `CString` |  |
| `GetThreatenNavalHostilitiesInfamyWarning` |  | `CString` |  |
| `GetUnavailableDemands` |  |  |  |
| `GetUnavailableMutualAgreements` |  |  |  |
| `GetUnavailableOffers` |  |  |  |
| `GetWithdrawPenaltiesDesc` |  | `CString` |  |
| `HasSelectedArticle` | `Arg0, Arg1` | `bool` |  |
| `IsRenegotiation` |  | `bool` |  |
| `IsValidDataContext` |  | `bool` |  |
| `MakeThisWork` | `Arg0` | `void` |  |
| `OnEditName` |  | `void` |  |
| `RandomizeName` |  | `void` |  |
| `RemoveArticle` | `Arg0` | `void` |  |
| `ResetAll` |  | `void` |  |
| `ResetLeftSide` |  | `void` |  |
| `ResetRightSide` |  | `void` |  |
| `Self` |  |  |  |
| `SendProposal` |  | `Command` |  |
| `SetBindingDays` | `Arg0` | `void` |  |
| `ToggleAskForObligation` | `Arg0` | `void` |  |
| `ToggleCallInObligation` | `Arg0` | `void` |  |
| `ToggleOweObligation` | `Arg0` | `void` |  |
| `ToggleThreatenNavalHostilities` |  | `void` |  |
| `WillAIAccept` | `Arg0` | `bool` |  |
| `WillAIAcceptNoObligation` | `Arg0` | `bool` |  |
| `WillAIAcceptWithCallInObligation` | `Arg0` | `bool` |  |
| `WillAIAcceptWithOweObligation` | `Arg0` | `bool` |  |
| `WillAIMaybeAccept` | `Arg0` | `bool` |  |
| `WillAIMaybeAcceptNoObligation` | `Arg0` | `bool` |  |
| `WillAIMaybeAcceptWithCallInObligation` | `Arg0` | `bool` |  |
| `WillAIMaybeAcceptWithOweObligation` | `Arg0` | `bool` |  |
| `WillAskForObligation` | `Arg0` | `bool` |  |
| `WillCallInObligation` | `Arg0` | `bool` |  |
| `WillOweObligation` | `Arg0` | `bool` |  |
| `WillThreatenNavalHostilities` |  | `bool` |  |

## TreatyDraftPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDraft` |  | `TreatyDraft` |  |
| `AccessSelf` |  |  |  |
| `GetDraft` |  |  |  |
| `Self` |  |  |  |

## TreatyPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTreaty` |  | `Treaty` |  |
| `AccessSelf` |  |  |  |
| `GetTreaty` |  |  |  |
| `Self` |  |  |  |

## TreatyShipFilter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetShipType` |  | `ShipType` |  |
| `AccessSelf` |  |  |  |
| `GetNumShipsOfType` |  | `int32` |  |
| `IsFilterSelected` |  | `bool` |  |
| `SelectFilter` |  | `void` |  |
| `Self` |  |  |  |

## TreatyShipFilterList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetShipTypeFilters` |  |  |  |
| `IsFiltered` |  | `bool` |  |
| `ResetFilters` |  | `void` |  |
| `Self` |  |  |  |

## Truce

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFirstCountry` |  | `Country` |  |
| `AccessSecondCountry` |  | `Country` |  |
| `GetFirstCountry` |  | `Country` |  |
| `GetSecondCountry` |  | `Country` |  |
| `AccessFirstCountry` |  |  |  |
| `AccessSecondCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetFirstCountry` |  |  |  |
| `GetFirstTruceDate` |  | `CString` |  |
| `GetSecondCountry` |  |  |  |
| `GetSecondTruceDate` |  | `CString` |  |
| `GetTruceExpirationDesc` |  | `CString` |  |
| `Self` |  |  |  |

## Tutorial

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanReplayVoiceover` |  | `bool` |  |
| `GetReplayVoiceoverTooltip` |  | `CString` |  |
| `GetStepHeaderInfo` |  | `CString` |  |
| `GetStepInstructions` |  | `CString` |  |
| `GetStepName` |  | `CString` |  |
| `GetStepText` |  | `CString` |  |
| `GetTransitionText` | `Arg0` | `CString` |  |
| `GetTransitionTooltip` | `Arg0` | `CString` |  |
| `HasStepInstructions` |  | `bool` |  |
| `HasTransition` | `Arg0` | `bool` |  |
| `IsTransitionEnabled` | `Arg0` | `bool` |  |
| `OnClickTransition` | `Arg0` | `void` |  |
| `ReplayVoiceover` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldBeVisible` |  | `bool` |  |

## Tweakable

Tweakable field in the Tweaker tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBool` |  | `bool` |  |
| `GetColor` |  | `CVector4f` |  |
| `GetDescription` |  | `CString` |  |
| `GetEnumValueIndex` |  | `CVector2i` |  |
| `GetEnumValues` |  |  |  |
| `GetGuiName` |  | `CString` |  |
| `GetTweakableId` |  | `CString` |  |
| `GetValue` |  | `CString` |  |
| `OnValueEdited` |  | `void` |  |
| `Self` |  |  |  |
| `SetEnumValueIndex` |  | `void` |  |

## TweakableCategory

A single Tweakable category in the Tweaker Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMargin` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `IsExpanded` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpanded` |  | `void` |  |
| `ToggleTreeExpanded` |  | `void` |  |

## TweakablesSnapshot

A snapshot of tweakable values represented in the Tweaker tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Name` |  | `CString` |  |
| `Self` |  |  |  |

## TweakableUiEntry

A single Tweakable Entry in the Tweaker Tool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFriendlyName` |  | `CString` |  |
| `GetMargin` |  | `int32` |  |
| `Self` |  |  |  |

## Tweaker

Tweaker Tool Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanResetTweakable` | `Arg0` | `bool` |  |
| `ClearSearchString` |  | `void` |  |
| `GetSearchString` |  | `CString` |  |
| `GetSelectedCategory` |  | `CString` |  |
| `GetTweakableOriginalValue` | `Arg0` | `CString` |  |
| `GetTweakableValueColor` | `Arg0` | `CVector4f` |  |
| `OnOptionsPressed` |  | `void` |  |
| `OriginalSnapshotValid` |  | `bool` |  |
| `RebuildTree` |  | `void` |  |
| `RemoveSnapshot` | `Arg0` | `void` |  |
| `RemoveSnapshotEnabled` | `Arg0` | `bool` |  |
| `RenameSnapshot` | `Arg0` | `void` |  |
| `ResetTweakable` | `Arg0` | `void` |  |
| `RootCategories` |  |  |  |
| `SelectedSnapshot` |  | `CString` |  |
| `Self` |  |  |  |
| `SetSearchString` |  | `void` |  |
| `SnapshotVisible` | `Arg0` | `bool` |  |
| `TakeNewSnapshot` |  | `void` |  |
| `ToggleSelectedCategory` | `Arg0` | `void` |  |
| `ToggleSelectedSnapshot` | `Arg0` | `void` |  |
| `UpdateSnapshot` | `Arg0` | `void` |  |
| `UpdateSnapshotEnabled` | `Arg0` | `bool` |  |

## Type

Map Editor - Map Object Type

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Delete` |  | `void` |  |
| `GetAssetName` |  | `CString` |  |
| `GetEntityIndex` |  | `CVector2i` |  |
| `GetInstanceCount` |  | `int32` |  |
| `GetKey` |  | `CString` |  |
| `GetLayer` |  | `CString` |  |
| `GetLayerIndex` |  | `CVector2i` |  |
| `GetMeshIndex` |  | `CVector2i` |  |
| `GetTypeIndex` |  | `CVector2i` |  |
| `IsHidden` |  | `bool` |  |
| `IsLocked` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Rename` |  |  |  |
| `Self` |  |  |  |
| `SetClampToWaterLevel` | `Arg0` | `void` |  |
| `SetEntityFromIndex` |  | `void` |  |
| `SetLayerFromIndex` |  | `void` |  |
| `SetMeshFromIndex` |  | `void` |  |
| `SetRenderUnderwater` | `Arg0` | `void` |  |
| `SetTypeFromIndex` |  | `void` |  |
| `ShouldClampToWaterLevel` |  | `bool` |  |
| `ShouldRenderUnderwater` |  | `bool` |  |
