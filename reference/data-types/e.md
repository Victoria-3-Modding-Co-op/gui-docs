# Data-binding types: E

Back to the [index](README.md).

## EditorSettingCategory

Editor Settings - Category

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## EditorSettingsPage

Editor Settings - Settings Page

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCategories` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `OnClick` |  | `void` |  |
| `Self` |  |  |  |

## EditorSettingsWindow

Editor Settings Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessActivePage` |  | `EditorSettingsPage` |  |
| `AccessActivePage` |  |  |  |
| `AccessPages` |  |  |  |
| `AccessSelf` |  |  |  |
| `AllowApply` |  | `bool` |  |
| `AppliedOnRestart` |  | `bool` |  |
| `Close` |  | `void` |  |
| `GetWindowName` |  | `CString` |  |
| `HasChanged` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `OnApply` |  | `void` |  |
| `RequireRestart` |  | `bool` |  |
| `Restore` |  | `void` |  |
| `Save` |  | `void` |  |
| `SaveAndClose` |  | `void` |  |
| `Self` |  |  |  |
| `Show` |  | `void` |  |

## Election

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCountryName` |  | `CString` |  |
| `GetDateFormatted` |  | `CString` |  |
| `GetEligibleVoters` |  | `int64` |  |
| `GetIndependentIGs` |  |  |  |
| `GetLastElectionDateDesc` |  | `CString` |  |
| `GetLastElectionYearRaw` |  | `int32` |  |
| `GetNextElectionYearRaw` |  | `int32` |  |
| `GetParties` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalVoters` |  | `int64` |  |
| `GetVoterTurnout` |  | `CFixedPoint` |  |
| `GetVotesGraphDateEnd` |  | `CString` |  |
| `GetVotesGraphDateStart` |  | `CString` |  |
| `GetVotesGraphMax` |  | `CFixedPoint` |  |
| `HasPreviousElection` |  | `bool` |  |
| `IsInCampaignPeriod` |  | `bool` |  |
| `Self` |  |  |  |

## ElectionPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetElection` |  | `Election` |  |
| `AccessSelf` |  |  |  |
| `GetElection` |  |  |  |
| `Self` |  |  |  |

## EmitterNodeWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddUserData` | `Arg0` | `void` |  |
| `GetNodeTitleColor` |  | `CVector4f` |  |
| `IsAnotherWindowIsolated` |  | `bool` |  |
| `IsIsolated` |  | `bool` |  |
| `IsVisuallyEnabled` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleSetEmitterIsolatedExclusive` |  | `void` |  |
| `ToggleSetEmitterIsolatedIncremental` |  | `void` |  |
| `ToggleSetVisuallyEnabled` |  | `void` |  |

## EmployeeTransfer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetNewEmployment` |  | `BuildingType` |  |
| `GetNewPopType` |  | `PopType` |  |
| `GetOldEmployment` |  | `BuildingType` |  |
| `GetOldPopType` |  | `PopType` |  |
| `AccessSelf` |  |  |  |
| `GetIlliterate` |  | `int64` |  |
| `GetLiterate` |  | `int64` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotal` |  | `int64` |  |
| `Self` |  |  |  |

## Encyclopedia

Jomini Encyclopedia

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCurrentPage` |  | `EncyclopediaPage` |  |
| `GetAllPage` |  | `EncyclopediaPage` |  |
| `GetCurrentPage` |  | `EncyclopediaPage` |  |
| `AccessCurrentPage` |  |  |  |
| `AccessPages` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanFilterFromHistoryBack` |  | `bool` |  |
| `CanFilterFromHistoryForward` |  | `bool` |  |
| `FilterFromHistoryBack` |  | `void` |  |
| `FilterFromHistoryForward` |  | `void` |  |
| `GetAllPage` |  |  |  |
| `GetCurrentPage` |  |  |  |
| `GetPages` |  |  |  |
| `GetViewedEntries` |  |  |  |
| `Hide` |  | `void` |  |
| `IsShown` |  | `bool` |  |
| `Self` |  |  |  |
| `SetCurrentPage` | `Arg0` | `void` |  |
| `ViewAllEntries` |  | `void` |  |

## EncyclopediaEntry

Jomini Encyclopedia - Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBody` |  | `CString` |  |
| `GetFrame` |  | `int32` |  |
| `GetFrameSize` |  | `CVector2i` |  |
| `GetImage` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `HasImage` |  | `bool` |  |
| `Self` |  |  |  |

## EncyclopediaEntryView

Jomini Encyclopedia - Entry View

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `Get` |  | `EncyclopediaEntry` |  |
| `AccessSelf` |  |  |  |
| `Get` |  |  |  |
| `Self` |  |  |  |

## EncyclopediaPage

Jomini Encyclopedia - Page

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `FilterFromText` |  | `void` |  |
| `GetTitle` |  | `CString` |  |
| `ResetFilter` |  | `void` |  |
| `SearchFromEnteredText` |  | `void` |  |
| `Self` |  |  |  |

## EndPrepConfirm

Jomini Multiplayer - End preparation confirm

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Cancel` |  | `void` |  |
| `Confirm` |  | `void` |  |
| `Self` |  |  |  |

## EntityEditor

Entity Editor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `Entity` |  | `ViewerEntity` |  |
| `AccessSelf` |  |  |  |
| `AddAudioLayer` |  | `void` |  |
| `AddEntityRemovalLayer` |  | `void` |  |
| `AddEntitySpawnLayer` |  | `void` |  |
| `AddKeyframeOnMouseToHoveredLane` |  | `void` |  |
| `AddKeyframeOnNeedleToHoveredLane` |  | `void` |  |
| `AddVfxLayer` |  | `void` |  |
| `CanInteract` |  | `bool` |  |
| `CurrentAnimationMax` |  | `float` |  |
| `DeleteKeyframe` | `Arg0` | `void` |  |
| `Entity` |  |  |  |
| `FitCamera` |  | `void` |  |
| `GetLastAutoSaveDuration` |  | `double` |  |
| `GetLastAutoSaveTimestamp` |  |  |  |
| `HasEntities` |  | `bool` |  |
| `HasEntity` |  | `bool` |  |
| `HasLastSaveTimestamp` |  | `bool` |  |
| `IsAutoSaving` |  | `bool` |  |
| `IsGridVisible` |  | `bool` |  |
| `IsLoading` |  | `bool` |  |
| `IsScrubbing` |  | `bool` |  |
| `IsWorldMuted` |  | `bool` |  |
| `MovePlayerWithKeyframe` |  | `bool` |  |
| `OnAddLayerClick` |  | `void` |  |
| `OnKeyframeClick` | `Arg0, Arg1` | `void` |  |
| `OnKeyframeMove` | `Arg0, Arg1` | `void` |  |
| `OnKeyframePressed` | `Arg0, Arg1` | `void` |  |
| `OnKeyframeReleased` | `Arg0, Arg1` | `void` |  |
| `OnKeyframeRightClick` | `Arg0` | `void` |  |
| `OnLayerRightClick` | `Arg0` | `void` |  |
| `OnScrubEnd` |  | `void` |  |
| `OnScrubStart` |  | `void` |  |
| `OpenEventEditor` | `Arg0` | `void` |  |
| `SaveChanges` |  | `void` |  |
| `ScrubPlayer` |  | `void` |  |
| `Self` |  |  |  |
| `SetClickedLane` | `Arg0` | `void` |  |
| `SetMovePlayerWithKeyframe` | `Arg0` | `void` |  |
| `ToggleGridVisible` |  | `void` |  |
| `ToggleMovePlayerWithKeyframe` |  | `void` |  |
| `ToggleMuteWorld` |  | `void` |  |

## EntityEditorAudioEventHandler

Entity Editor - Audio Event Handler

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddSoundParamter` | `Arg0` | `void` |  |
| `RemoveLastSoundParameter` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## EntityEditorEventLayer

Entity Editor - Entity Event Layer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddStartEventKeyframe` | `Arg0` | `void` |  |
| `HasKeyframes` |  | `bool` |  |
| `IsExpanded` |  | `bool` |  |
| `IsHovered` |  | `bool` |  |
| `Keyframes` |  |  |  |
| `Self` |  |  |  |
| `SetHovered` | `Arg0` | `void` |  |
| `Title` |  |  |  |
| `ToggleExpanded` |  | `void` |  |

## EntityEditorKeyframe

Entity Editor - Entity Key Frame

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HasEvent` |  | `bool` |  |
| `IsHovered` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsStartEvent` |  | `bool` |  |
| `KeyframeColor` |  | `CVector4f` |  |
| `Label` |  | `CString` |  |
| `Self` |  |  |  |
| `SetHovered` | `Arg0` | `void` |  |
| `SetSelected` | `Arg0` | `void` |  |
| `TimePoint` |  | `float` |  |

## EntityEditorTimelineState

Entity Editor - Timeline State

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AnimationLength` |  | `float` |  |
| `KeyframeLayers` |  |  |  |
| `Name` |  |  |  |
| `Self` |  |  |  |

## EntityViewerProperties

Entity Editor - Properties

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearSelection` |  | `void` |  |
| `IsBloomEvPropertiesVisible` |  | `bool` |  |
| `IsCubemapEvPropertiesVisible` |  | `bool` |  |
| `IsEnvSelected` |  | `bool` |  |
| `IsFogEvPropertiesVisible` |  | `bool` |  |
| `IsLightEnvPropertiesVisible` |  | `bool` |  |
| `IsMeshSelected` |  | `bool` |  |
| `SelectEnvWindow` |  | `void` |  |
| `SelectMeshWindow` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleIsBloomEvPropertiesVisible` |  | `void` |  |
| `ToggleIsCubemapEvPropertiesVisible` |  | `void` |  |
| `ToggleIsFogEvPropertiesVisible` |  | `void` |  |
| `ToggleIsLightEnvPropertiesVisible` |  | `void` |  |

## EnumSettingEntry

Jomini Settings - Enum Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AccessSetting` |  |  |  |
| `GetEnumString` |  | `CString` |  |
| `GetGUIName` |  | `CUTF8String` |  |
| `GetRecommendedText` |  | `CString` |  |
| `GetTooltip` |  | `CUTF8String` |  |
| `HasValueChanged` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |

## Era

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumber` |  | `CString` |  |
| `GetTechnologyCost` |  | `int32` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## ErrorDeer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `HasErrors` |  | `bool` |  |
| `HasSlowTicks` |  | `bool` |  |
| `NumberOrErrors` |  | `int32` |  |
| `OpenErrorLog` |  | `void` |  |
| `Self` |  |  |  |

## Ethnicity

Portrait System - Ethnicity

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## EthnicityItem

Portrait Editor - Ethnicity Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## Event

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessState` |  | `State` |  |
| `GetIcon` | `Arg0` | `EventIcon` |  |
| `GetState` |  | `State` |  |
| `GetTopScope` |  | `TopScope` |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetDLCIcon` |  |  |  |
| `GetDLCName` |  | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetEventIcon` |  |  |  |
| `GetFlavor` |  | `CString` |  |
| `GetKey` |  | `CString` |  |
| `GetNumRemainingDays` |  | `int32` |  |
| `GetOnCreatedSoundEvent` |  |  |  |
| `GetOnOpenedSoundEvent` |  |  |  |
| `GetPercentageRemainingDays` |  | `float` |  |
| `GetRemainingDays` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTriggerDesc` |  | `CString` |  |
| `GetVideo` |  | `CString` |  |
| `HasCategory` | `Arg0` | `bool` |  |
| `HasTexture` |  | `bool` |  |
| `HasVideo` |  | `bool` |  |
| `IsDLCContent` |  | `bool` |  |
| `OpenInEditor` |  | `void` |  |
| `Self` |  |  |  |

## EventIcon

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCharacter` |  | `Character` |  |
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetTexture` |  |  |  |
| `IsCoatOfArms` |  | `bool` |  |
| `IsPortrait` |  | `bool` |  |
| `IsTexture` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## EventLayerForEntityEditor

Entity Editor - Entity Event Layer Keyframe

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HasKeyframes` |  | `bool` |  |
| `IsHovered` |  | `bool` |  |
| `Keyframes` |  |  |  |
| `Self` |  |  |  |
| `SetHovered` | `Arg0` | `void` |  |

## EventMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAnyEvent` |  | `Event` |  |
| `GetAnyEvent` |  | `Event` |  |
| `AccessAnyEvent` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetAnyEvent` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetTexture` |  |  |  |
| `Self` |  |  |  |

## EventMarkerListItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `Self` |  |  |  |

## EventOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetText` |  | `CString` |  |
| `IsDefaultOption` |  | `bool` |  |
| `IsEnabled` |  | `bool` |  |
| `IsHighlightedOption` |  | `bool` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |

## EventTargetSetupContext

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessVariableLists` |  | `VariableListStore` |  |
| `AccessVariables` |  | `VariableStore` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## EventWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessEvent` |  | `Event` |  |
| `GetEvent` |  | `Event` |  |
| `AccessEvent` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetEvent` |  |  |  |
| `GetFlavor` |  | `CString` |  |
| `GetOptions` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `GetTitleTooltip` |  | `CString` |  |
| `Self` |  |  |  |

## ExilePool

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetExiles` |  |  |  |
| `GetNumAllExiles` |  | `int32` |  |
| `GetNumInviteableExiles` |  | `int32` |  |
| `IsInterestGroupFiltered` | `Arg0` | `bool` |  |
| `IsInterestGroupFilteredToShowOnly` | `Arg0` | `bool` |  |
| `IsSorted` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetInterestGroupFilter` | `Arg0` | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `ToggleInterestGroupFilter` | `Arg0` | `void` |  |

## ExportTool

Map Editor - Export Tool Dockable

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanExport` |  | `bool` |  |
| `Cancel` |  | `void` |  |
| `CurrentProgress` |  | `float` |  |
| `CurrentProgressDesc` |  | `CString` |  |
| `Export` |  | `void` |  |
| `GetHeightmapTexture` |  |  |  |
| `GetMaskEffect` |  |  |  |
| `GetNotes` |  | `CString` |  |
| `GetSelectedMaskIndex` |  | `CVector2i` |  |
| `GetTexture` |  |  |  |
| `HasMasks` |  | `bool` |  |
| `IsExporting` |  | `bool` |  |
| `MaxProgress` |  | `float` |  |
| `Refresh` |  | `void` |  |
| `Self` |  |  |  |
| `SetExportNotes` |  | `void` |  |
| `SetSelectedMaskIndex` |  | `void` |  |

## EyeDropper

Map Editor - Eye Dropper

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHoverSample` |  | `MaterialsSample` |  |
| `AccessSelf` |  |  |  |
| `IsEnabled` |  | `bool` |  |
| `PackedSamples` |  |  |  |
| `PackedSamplesDynamic` |  |  |  |
| `Self` |  |  |  |
| `SetEnabled` | `Arg0` | `void` |  |

## EyeDropperPackedSample

Map Editor - Packed Sample data for Eye Dropper

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSample` |  | `MaterialEntry` |  |
| `AccessSelf` |  |  |  |
| `GetChannel` |  | `CString` |  |
| `Self` |  |  |  |
