# Data-binding types: O

Back to the [index](README.md).

## ObjectBrowser

Object Explorer - Browser

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CopyAsCSV` |  | `void` |  |
| `CreateNewPreset` |  | `void` |  |
| `DeleteSelectedPreset` |  | `void` |  |
| `ForceUpdate` |  | `void` |  |
| `GetFilterString` |  | `CUTF8String` |  |
| `GetNumObjectsFiltered` |  | `int32` |  |
| `GetNumObjectsTotal` |  | `int32` |  |
| `GetPresets` |  |  |  |
| `GetProviders` |  |  |  |
| `GetSelectedProvider` |  | `CVector2i` |  |
| `GetSelectedView` |  | `CVector2i` |  |
| `GetViews` |  |  |  |
| `HasConfig` |  | `bool` |  |
| `IsObjectSelected` | `Arg0` | `bool` |  |
| `IsOutputFlattened` |  | `bool` |  |
| `IsWaitingForProvider` |  | `bool` |  |
| `RenameSelectedPreset` |  | `void` |  |
| `RequestUpdate` |  | `void` |  |
| `SaveCurrentChanges` |  | `void` |  |
| `SaveDefaults` |  | `void` |  |
| `SelectProvider` |  | `void` |  |
| `SelectView` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilterString` |  | `void` |  |
| `SetObjectSelected` | `Arg0` | `void` |  |
| `SetSelectedPreset` | `Arg0` | `void` |  |
| `ToggleObjectSelected` | `Arg0` | `void` |  |
| `ToggleOutputFlattened` |  | `void` |  |

## ObjectBrowserView

Object Explorer - View

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Name` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## ObjectInspector

Object Explorer - Inspector

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPluginEntries` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetObjectName` |  | `CUTF8String` |  |
| `GetTypeName` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## ObjectInspectorDockable

Object Explorer - Inspector Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Detach` |  | `void` |  |
| `IsAttached` |  | `bool` |  |
| `Self` |  |  |  |

## ObjectInspectorPlugin

Object Explorer - Inspector Plugin

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetErrorMessage` |  | `CUTF8String` |  |
| `GetTitle` |  | `CUTF8String` |  |
| `HasError` |  | `bool` |  |
| `Self` |  |  |  |

## Objective

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetObjectiveType` |  | `ObjectiveType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetDescForCountryDef` | `Arg0` | `CString` |  |
| `GetDisabledBackground` |  |  |  |
| `GetEnabledBackground` |  |  |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetObjectiveType` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## ObjectiveType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetDescForCountryDef` | `Arg0` | `CString` |  |
| `GetDisabledBackground` |  |  |  |
| `GetEnabledBackground` |  |  |  |
| `GetIcon` |  |  |  |
| `GetIdleHeader` |  | `CString` |  |
| `GetIdleHint` |  | `CString` |  |
| `GetIsAvailableDescription` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameForCountryDef` | `Arg0` | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetRecommendedGameRules` |  |  |  |
| `GetRecommendedTags` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasRecommendedGameRules` |  | `bool` |  |
| `IsAvailable` |  | `bool` |  |
| `IsAvailableForAllCountries` |  | `bool` |  |
| `Self` |  |  |  |

## ObjectPreset

Object Explorer - Preset

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsSelected` |  | `bool` |  |
| `PresetName` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## ObjectProvider

Object Explorer - Provider

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Name` |  | `CUTF8String` |  |
| `RequestUpdate` |  | `void` |  |
| `Self` |  |  |  |

## ObstinanceMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## OccupationPiechartData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCountryColor` |  | `CVector4f` |  |
| `GetOccupationFraction` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## OosData

Jomini Multiplayer - Out-of-sync data

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPlayable` |  | `Playable` |  |
| `AccessSelf` |  |  |  |
| `GetFolder` |  | `CString` |  |
| `GetPlayerId` |  | `int32` |  |
| `GetPlayerName` |  | `CString` |  |
| `GetType` |  | `CString` |  |
| `IsLocalPlayer` |  | `bool` |  |
| `IsObserver` |  | `bool` |  |
| `Self` |  |  |  |

## OosWindow

Jomini Multiplayer - Out-of-sync window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `Continue` |  | `void` |  |
| `GetOosData` |  |  |  |
| `GoToMenu` |  | `void` |  |
| `IsLocalOos` |  | `bool` |  |
| `IsMultiplayerHost` |  | `bool` |  |
| `Resync` |  | `void` |  |
| `Self` |  |  |  |

## OpinionMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## OutgoingFriendRequest

Jomini Friend List - Outgoing friend request

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CUTF8String` |  |
| `Remove` |  | `void` |  |
| `Self` |  |  |  |

## Outliner

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCategory` | `Arg0` | `OutlinerEntry` |  |
| `AccessPlayers` |  |  |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## OutlinerEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessScope` |  | `Scope` |  |
| `AccessSituation` |  | `Event` |  |
| `AccessScope` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessSituation` |  |  |  |
| `GetKey` |  | `int32` |  |
| `GetNumSubEntries` |  | `int32` |  |
| `GetPinnedSubEntries` |  |  |  |
| `GetSubEntries` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `IsCategory` |  | `bool` |  |
| `IsExpanded` |  | `bool` |  |
| `IsPinned` |  | `bool` |  |
| `IsPinnedExpanded` |  | `bool` |  |
| `IsShown` |  | `bool` |  |
| `IsShownPinned` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpanded` |  | `void` |  |
| `TogglePinned` |  | `void` |  |
| `TogglePinnedExpanded` |  | `void` |  |

## OutputEntry

Texture Importer - Output Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInputTextures` |  |  |  |
| `GetPath` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleIsSelected` |  | `void` |  |
