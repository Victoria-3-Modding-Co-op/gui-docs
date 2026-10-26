# Data-binding types: J

Back to the [index](README.md).

## JominiGameRules

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessNamedGameRule` | `Arg0` | `GuiGameRule` |  |
| `GetSelectedPreset` |  | `GuiGameRulePreset` |  |
| `AccessSelf` |  |  |  |
| `ApplySettings` |  | `void` |  |
| `DeletePresetAtIndex` | `Arg0` | `void` |  |
| `DeletePresetWithName` | `Arg0` | `void` |  |
| `GetInvalidPresetNameTooltip` |  | `CString` |  |
| `GetPresetSaveName` |  | `CString` |  |
| `GetRulePresets` |  |  |  |
| `GetSelectedPreset` |  |  |  |
| `GetSelectedPresetIndex` |  | `int32` |  |
| `GetSettings` |  |  |  |
| `HasPresetWithName` | `Arg0` | `bool` |  |
| `HasRuleWithFlag` | `Arg0` | `bool` |  |
| `HasValidPresetSelected` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `HidePresetWindow` |  | `void` |  |
| `IsIronman` |  | `bool` |  |
| `IsPresetWindowShown` |  | `bool` |  |
| `IsValidPresetName` |  | `bool` |  |
| `OnPresetSaveNameChange` | `Arg0` | `void` |  |
| `OnPresetSaveNameEdit` |  | `void` |  |
| `OnSelectPreset` |  | `void` |  |
| `ResetAllToDefaults` |  | `void` |  |
| `SavePreset` |  | `void` |  |
| `Self` |  |  |  |
| `SetIronman` | `Arg0` | `void` |  |
| `SetPresetSaveName` |  | `void` |  |
| `ShowPresetWindow` |  | `void` |  |

## JominiGUISetting

Jomini Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `HasChanged` |  | `bool` |  |
| `HasChangedSinceStartup` |  | `bool` |  |
| `Self` |  |  |  |
| `ShouldShow` |  | `bool` |  |

## JominiNotification

Jomini Notification Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDate` |  | `Date` |  |
| `SetupDataContexts` | `Arg0` | `NotificationDummyContext` |  |
| `AccessSelf` |  |  |  |
| `GetAcceptButtonText` |  | `CString` |  |
| `GetDate` |  |  |  |
| `GetDateOrTimestamp` |  | `CString` |  |
| `GetDeclineButtonText` |  | `CString` |  |
| `GetText` |  | `CString` |  |
| `GetTimestamp` |  | `CString` |  |
| `GetTitle` |  | `CString` |  |
| `HasDate` |  | `bool` |  |
| `HasOnAccept` |  | `bool` |  |
| `HasOnDecline` |  | `bool` |  |
| `OnAccept` |  | `void` |  |
| `OnDecline` |  | `void` |  |
| `OnNotificationClick` |  | `void` |  |
| `Self` |  |  |  |

## JominiNotificationOverlay

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAlertCount` |  | `int32` |  |
| `GetAlerts` |  |  |  |
| `GetNotificationCategoryCount` | `Arg0` | `int32` |  |
| `GetNotificationCount` |  | `int32` |  |
| `GetNotifications` |  |  |  |
| `HideSidebar` |  | `void` |  |
| `Self` |  |  |  |
| `ShowSidebar` |  | `void` |  |
| `ToggleSidebar` |  | `void` |  |

## JominiPasswordPopup

Jomini Multiplayer - Password Popup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `OnDecline` |  | `void` |  |
| `OnSubmit` |  | `void` |  |
| `Self` |  |  |  |

## JominiServer

Jomini Multiplayer - Server

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetHasPassword` |  | `bool` |  |
| `GetMaxPlayers` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetNumPlayers` |  | `int32` |  |
| `GetStatus` |  | `CString` |  |
| `GetVersion` |  | `CString` |  |
| `IsSameVersion` |  | `bool` |  |
| `Join` |  | `void` |  |
| `Self` |  |  |  |

## JominiServerBrowserGui

Jomini Multiplayer - Server Browser

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AccessServers` |  |  |  |
| `GetServers` |  |  |  |
| `IsCrossPlatformFilterSet` |  | `bool` |  |
| `IsEmptyFilterSet` |  | `bool` |  |
| `IsFullFilterSet` |  | `bool` |  |
| `IsHasPasswordFilterSet` |  | `bool` |  |
| `IsRefreshing` |  | `bool` |  |
| `IsSameModsFilterSet` |  | `bool` |  |
| `IsSameVersionFilterSet` |  | `bool` |  |
| `IsSortAscending` |  | `bool` |  |
| `IsSortedBy` | `Arg0` | `bool` |  |
| `JoinServerWithId` |  | `void` |  |
| `JoinServerWithTextWidget` | `Arg0` | `void` |  |
| `OnFilterTextEdit` |  | `void` |  |
| `RefreshServers` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilterText` |  | `void` |  |
| `SetServerId` |  | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `ToggleCrossPlatformFilter` |  | `void` |  |
| `ToggleEmptyFilter` |  | `void` |  |
| `ToggleFullFilter` |  | `void` |  |
| `ToggleHasPasswordFilter` |  | `void` |  |
| `ToggleSameModsFilter` |  | `void` |  |
| `ToggleSameVersionFilter` |  | `void` |  |

## JominiSettingsWindow

Jomini Settings Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessActivePage` |  | `SettingsPage` |  |
| `AccessActivePage` |  |  |  |
| `AccessPages` |  |  |  |
| `AccessSelf` |  |  |  |
| `AllowApply` |  | `bool` |  |
| `AppliedOnApply` |  | `bool` |  |
| `AppliedOnRestart` |  | `bool` |  |
| `Close` |  | `void` |  |
| `GetInputActionName` | `Arg0` | `CString` |  |
| `GetInputBindingText` |  | `CString` |  |
| `GetKeyCodeName` | `Arg0, Arg1` | `CString` |  |
| `GetUserBindingFileName` |  | `CString` |  |
| `GetWarningText` |  | `CString` |  |
| `HasChanged` |  | `bool` |  |
| `HasUserBindingFileName` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `IsConfirmButtonEnabled` |  | `bool` |  |
| `IsCurrentActivePageId` | `Arg0` | `bool` |  |
| `IsInputPopUpEnabled` |  | `bool` |  |
| `OnApply` |  | `void` |  |
| `OnClickCancel` |  | `void` |  |
| `OnClickClear` |  | `void` |  |
| `OnClickConfirm` |  | `void` |  |
| `OnClickLoadDefaultProfile` |  | `void` |  |
| `OnClickLoadProfile` |  | `void` |  |
| `OnClickSaveProfile` |  | `void` |  |
| `OnEditProfileFileName` |  | `void` |  |
| `RequireRestart` |  | `bool` |  |
| `Restore` |  | `void` |  |
| `Save` |  | `void` |  |
| `SaveAndClose` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldShowWarningText` |  | `bool` |  |
| `Show` |  | `void` |  |
| `ShowInputPopUp` | `Arg0, Arg1, Arg2` | `void` |  |

## JournalEntry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessModifier` |  | `Modifier` |  |
| `GetBuildingTarget` |  | `Building` |  |
| `GetCountry` |  | `Country` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetTarget` |  | `Scope` |  |
| `GetTopScope` |  | `TopScope` |  |
| `GetType` |  | `JournalEntryType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessModifier` |  |  |  |
| `AccessSelf` |  |  |  |
| `CalcCurrentGoalValue` |  | `CFixedPoint` |  |
| `CalcInitialGoalAddValue` |  | `CFixedPoint` |  |
| `CanComplete` |  | `bool` |  |
| `CanStartTutorialLesson` |  | `bool` |  |
| `CanStartTutorialLessonDesc` |  | `CString` |  |
| `CanTimeOut` |  | `bool` |  |
| `GetActivationTooltip` |  | `CString` |  |
| `GetBaselineValue` |  | `CFixedPoint` |  |
| `GetBuildingTarget` |  |  |  |
| `GetCompletionTooltip` |  | `CString` |  |
| `GetCountry` |  |  |  |
| `GetCurrentBarProgress` | `Arg0` | `float` |  |
| `GetCurrentBarValue` | `Arg0` | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFailureTooltip` |  | `CString` |  |
| `GetGoalAddValue` |  | `CFixedPoint` |  |
| `GetGoalDesc` |  | `CString` |  |
| `GetGoalProgressPercent` |  | `CFixedPoint` |  |
| `GetGoalProgressValue` |  | `CFixedPoint` |  |
| `GetIcon` |  |  |  |
| `GetInvalidationTooltip` |  | `CString` |  |
| `GetInvolvedCountries` |  |  |  |
| `GetInvolvedCountriesDesc` |  | `CString` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumPossibleScriptedButtons` |  | `int32` |  |
| `GetOnActivationTooltip` |  | `CString` |  |
| `GetOnCompleteTooltip` |  | `CString` |  |
| `GetOnFailTooltip` |  | `CString` |  |
| `GetOnInvalidationTooltip` |  | `CString` |  |
| `GetOnTimeoutTooltip` |  | `CString` |  |
| `GetProgressDesc` |  | `CString` |  |
| `GetReason` |  | `CString` |  |
| `GetRemainingProgressValue` |  | `CFixedPoint` |  |
| `GetScriptedButtons` |  |  |  |
| `GetScriptedProgressBars` |  |  |  |
| `GetStatusDesc` |  | `CString` |  |
| `GetTarget` |  |  |  |
| `GetTimedModifiers` |  |  |  |
| `GetTimedModifiersTooltip` |  | `CString` |  |
| `GetTimeoutDaysLeft` |  | `int32` |  |
| `GetTimeoutTooltip` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalGoalValue` |  | `CFixedPoint` |  |
| `GetType` |  |  |  |
| `HasCustomWidget` | `Arg0` | `bool` |  |
| `HasGoal` |  | `bool` |  |
| `HasHowTutorialLesson` |  | `bool` |  |
| `HasProgressBar` |  | `bool` |  |
| `HasWhyTutorialLesson` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsComplete` |  | `bool` |  |
| `IsContextless` |  | `bool` |  |
| `IsDead` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsProgressing` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowProgressbarAsMonths` |  | `bool` |  |
| `ShowProgressbarAsTime` |  | `bool` |  |
| `ShowProgressbarAsWeeks` |  | `bool` |  |
| `StartHowTutorialLesson` |  | `void` |  |
| `StartWhyTutorialLesson` |  | `void` |  |
| `TogglePinInOutliner` |  | `void` |  |

## JournalEntryGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetActiveJournalEntryTypes` | `Arg0` |  |  |
| `GetInactiveJournalEntryTypes` | `Arg0` |  |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## JournalEntryPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessJournalEntry` |  | `JournalEntry` |  |
| `GetJournalEntry` |  | `JournalEntry` |  |
| `AccessJournalEntry` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetJournalEntry` |  |  |  |
| `Self` |  |  |  |

## JournalEntryType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGroup` |  | `JournalEntryGroup` |  |
| `AccessSelf` |  |  |  |
| `GetGroup` |  |  |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetLobbyDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## JournalPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
