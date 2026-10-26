# Data-binding types: L

Back to the [index](README.md).

## Label

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTypeList` |  | `CString` |  |
| `Self` |  |  |  |

## LabelingHelper

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CapitalizeOnlyFirst` | `Arg0` | `CString` |  |
| `GetDaysLocWithTooltip` | `Arg0, Arg1` | `CString` |  |
| `GetDaysLocWithoutTooltip` | `Arg0` | `CString` |  |
| `GetFormattedDays` | `Arg0` | `CString` |  |
| `GetIconForStandardOfLiving` | `Arg0` | `CString` |  |
| `GetIconForStandardOfLivingCFixedPoint` | `Arg0` | `CString` |  |
| `GetIconForStandardOfLivingFloat` | `Arg0` | `CString` |  |
| `GetLabelForLoyaltyCFixedPoint` | `Arg0` | `CString` |  |
| `GetLabelForLoyaltyFloat` | `Arg0` | `CString` |  |
| `GetLabelForPopularityCFixedPoint` | `Arg0` | `CString` |  |
| `GetLabelForPopularityFloat` | `Arg0` | `CString` |  |
| `GetLabelForProminenceCFixedPoint` | `Arg0` | `CString` |  |
| `GetLabelForProminenceFloat` | `Arg0` | `CString` |  |
| `GetLabelForRadicalism` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLiving` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLivingCFixedPoint` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLivingCFixedPointFormatFromExpected` | `Arg0, Arg1` | `CString` |  |
| `GetLabelForStandardOfLivingFloat` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLivingFloatFormatFromExpected` | `Arg0, Arg1` | `CString` |  |
| `GetLabelForStandardOfLivingFormatFromExpected` | `Arg0, Arg1` | `CString` |  |
| `GetLabelForStandardOfLivingNoIcon` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLivingNoIconCFixedPoint` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLivingNoIconCFixedPointFormatFromExpected` | `Arg0, Arg1` | `CString` |  |
| `GetLabelForStandardOfLivingNoIconFloat` | `Arg0` | `CString` |  |
| `GetLabelForStandardOfLivingNoIconFloatFormatFromExpected` | `Arg0, Arg1` | `CString` |  |
| `GetLabelForStandardOfLivingNoIconFormatFromExpected` | `Arg0, Arg1` | `CString` |  |
| `GetLabelForSupport` | `Arg0` | `CString` |  |
| `GetMultiTypeGameTimeDifferenceFromDays` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetMultiTypeGameTimeDifferenceFromMonths` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetMultiTypeGameTimeDifferenceFromWeeks` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetPriceCompareDesc` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetPriceCompareDescShort` | `Arg0` | `CString` |  |
| `GetPriceCompareIcon` | `Arg0` | `CString` |  |
| `GetPriceCompareIconNoFormatting` | `Arg0` | `CString` |  |
| `GetPriceCompareIconNoTooltip` | `Arg0` | `CString` |  |
| `GetRemainingDuration` | `Arg0, Arg1` | `CString` |  |
| `Self` |  |  |  |

## Law

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetActiveGroupLaw` |  | `Law` |  |
| `GetCheckpointEndDate` |  | `Date` |  |
| `GetCountry` |  | `Country` |  |
| `GetEnactmentLastCheckpointDate` |  | `Date` |  |
| `GetGroup` |  | `LawGroup` |  |
| `GetInstitution` |  | `Institution` |  |
| `GetInstitutionModifier` |  | `Modifier` |  |
| `GetInstitutionType` |  | `InstitutionType` |  |
| `GetLawType` |  | `LawType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessApprovingIGs` |  |  |  |
| `AccessDisapprovingIGs` |  |  |  |
| `AccessNeutralIGs` |  |  |  |
| `AccessSelf` |  |  |  |
| `AppliesTo` | `Arg0` | `bool` |  |
| `CannotEnactDesc` |  | `CString` |  |
| `GetActiveAmendments` |  |  |  |
| `GetActiveGroupLaw` |  |  |  |
| `GetAffectedMovementsFromCancelEnact` |  |  |  |
| `GetAffectedMovementsFromStartEnact` |  |  |  |
| `GetAllAmendments` |  |  |  |
| `GetCancelTooltip` |  | `CString` |  |
| `GetCheckpointAdvanceBreakdown` |  | `CString` |  |
| `GetCheckpointAdvanceChance` |  | `CFixedPoint` |  |
| `GetCheckpointAdvanceWithImpositionBreakdown` |  | `CString` |  |
| `GetCheckpointAdvanceWithImpositionChance` |  | `CFixedPoint` |  |
| `GetCheckpointBaseDays` |  | `int32` |  |
| `GetCheckpointDebateBreakdown` |  | `CString` |  |
| `GetCheckpointDebateChance` |  | `CFixedPoint` |  |
| `GetCheckpointDebateWithImpositionBreakdown` |  | `CString` |  |
| `GetCheckpointDebateWithImpositionChance` |  | `CFixedPoint` |  |
| `GetCheckpointEndDateString` |  | `CString` |  |
| `GetCheckpointProgress` |  | `CFixedPoint` |  |
| `GetCheckpointRemainingDays` |  | `int32` |  |
| `GetCheckpointStallBreakdown` |  | `CString` |  |
| `GetCheckpointStallChance` |  | `CFixedPoint` |  |
| `GetCheckpointStallWithImpositionBreakdown` |  | `CString` |  |
| `GetCheckpointStallWithImpositionChance` |  | `CFixedPoint` |  |
| `GetCheckpointSuccessBreakdown` |  | `CString` |  |
| `GetCheckpointSuccessChance` |  | `CFixedPoint` |  |
| `GetCheckpointSuccessWithImpositionBreakdown` |  | `CString` |  |
| `GetCheckpointSuccessWithImpositionChance` |  | `CFixedPoint` |  |
| `GetCheckpointTotalDays` |  | `int32` |  |
| `GetCheckpointTotalDaysBreakdown` |  | `CString` |  |
| `GetCountry` |  |  |  |
| `GetCurrentEnactmentPhaseKey` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDailyProgress` |  | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetEnactmentLastCheckpointDate` |  |  |  |
| `GetEnactmentLastCheckpointResult` |  | `CString` |  |
| `GetEnactmentPhase` |  | `int32` |  |
| `GetEnactmentPhaseKey` | `Arg0` | `CString` |  |
| `GetEnactmentSetbackCount` |  | `int32` |  |
| `GetExilesThatWouldJoinMovementSupportingLaw` |  |  |  |
| `GetExilesThatWouldStartMovementSupportingLaw` |  |  |  |
| `GetFlavor` |  | `CString` |  |
| `GetFullName` |  | `CString` |  |
| `GetFullNameWithStatus` |  | `CString` |  |
| `GetGroup` |  |  |  |
| `GetGroupName` |  | `CString` |  |
| `GetIGsApproveList` |  | `CString` |  |
| `GetIGsDisapproveList` |  | `CString` |  |
| `GetIGsEnactmentList` |  | `CString` |  |
| `GetIGsUndecidedList` |  | `CString` |  |
| `GetIGsWithApprovalChanges` |  |  |  |
| `GetInstitution` |  |  |  |
| `GetInstitutionModifier` |  |  |  |
| `GetInstitutionTooltip` |  | `CString` |  |
| `GetInstitutionType` |  |  |  |
| `GetLawAlternatives` |  |  |  |
| `GetLawType` |  |  |  |
| `GetMarginalizedIGsWithApprovalChanges` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNextEnactmentPhaseKey` |  | `CString` |  |
| `GetNumIGsApprove` |  | `uint32` |  |
| `GetNumIGsDisapprove` |  | `uint32` |  |
| `GetNumIGsUndecided` |  | `uint32` |  |
| `GetNumSupportingInterestGroups` |  | `int32` |  |
| `GetOnActivateDesc` |  | `CString` |  |
| `GetOnDeactivateDesc` |  | `CString` |  |
| `GetOnEnactDesc` |  | `CString` |  |
| `GetOnImposeDesc` |  | `CString` |  |
| `GetPercentPolStrApprove` |  | `CFixedPoint` |  |
| `GetPercentPolStrDisapprove` |  | `CFixedPoint` |  |
| `GetPercentPolStrUndecided` |  | `CFixedPoint` |  |
| `GetPreviousEnactmentPhaseKey` |  | `CString` |  |
| `GetRadicalismDriftTargetOnMovementFromCancelEnact` | `Arg0` | `CFixedPoint` |  |
| `GetRadicalismDriftTargetOnMovementFromStartEnact` | `Arg0` | `CFixedPoint` |  |
| `GetRadicalismEffectOnMovementFromCancelEnact` | `Arg0` | `CFixedPoint` |  |
| `GetRadicalismEffectOnMovementFromStartEnact` | `Arg0` | `CFixedPoint` |  |
| `GetReplacedLawEffect` |  | `CString` |  |
| `GetSupportingInterestGroupsBreakdown` |  | `CString` |  |
| `GetSupportingInterestGroupsSummary` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipNoRequirements` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTypeDesc` |  | `CString` |  |
| `HasEnactmentLastCheckpoint` |  | `bool` |  |
| `HasInstitution` |  | `bool` |  |
| `HasNecessaryLaws` |  | `bool` |  |
| `HasNecessaryTech` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `IsBeingEnacted` |  | `bool` |  |
| `IsMissingSupport` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsSupported` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `PredictApprovalChangesDuringEnactmentDesc` |  | `CString` |  |
| `PredictLegitimacyChangeToEnact` |  | `int32` |  |
| `PredictLegitimacyChangeToEnactDesc` |  | `CString` |  |
| `PredictMovementLoyalistsFromEnactmentDesc` |  | `CString` |  |
| `PredictRadicalismChangesFromCancellationDesc` |  | `CString` |  |
| `PredictRadicalismChangesFromEnactmentDesc` |  | `CString` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |
| `StartEnacting` |  | `Command` |  |
| `StartImposing` |  | `Command` |  |
| `StopEnacting` |  | `Command` |  |

## LawGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentlyActive` |  | `Law` |  |
| `GetCurrentlyEnacting` |  | `Law` |  |
| `GetFirstInstitutionType` |  | `InstitutionType` |  |
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetFirstInstitutionType` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumEnactable` |  | `int32` |  |
| `GetNumImposeOptions` | `Arg0` | `int32` |  |
| `GetNumPotentialEnactable` |  | `int32` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsHighlightedBySearch` |  | `bool` |  |
| `Self` |  |  |  |

## LawType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGroup` |  | `LawGroup` |  |
| `GetParentLawType` |  | `LawType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetAdditionalEffectDesc` |  | `CString` |  |
| `GetBlockingRequirements` | `Arg0` | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectDesc` | `Arg0` | `CString` |  |
| `GetFullName` |  | `CString` |  |
| `GetFullNameWithStatus` | `Arg0` | `CString` |  |
| `GetGroup` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetParentLawType` |  |  |  |
| `GetRequirements` | `Arg0` | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTypeDesc` |  | `CString` |  |
| `GetUnlocks` |  | `CString` |  |
| `Self` |  |  |  |

## Layer

Map Editor - Map Object Layer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## LayerTreeItem

Map Editor - Map Object Layer Tree Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetEntry` |  | `Type` |  |
| `AccessSelf` |  |  |  |
| `GetInstanceCount` |  | `int32` |  |
| `GetLayer` |  | `CString` |  |
| `IsExpanded` |  | `bool` |  |
| `IsGenerated` |  | `bool` |  |
| `IsHidden` |  | `bool` |  |
| `IsLayer` |  | `bool` |  |
| `IsLocked` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `SelectItem` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleExclusiveLayerHidden` |  | `void` |  |
| `ToggleExclusiveLock` |  | `void` |  |
| `ToggleLayerHidden` |  | `void` |  |
| `ToggleLock` |  | `void` |  |

## LegalDocsViewer

Legal Documents Viewer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Agree` |  | `void` |  |
| `GetDocumentText` |  | `CUTF8String` |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `Show` |  | `void` |  |

## LegitimacyLevel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDeltaSign` | `Arg0, Arg1` | `int32` |  |
| `GetEffects` |  | `CString` |  |
| `GetEffectsWithLoyaltiesGain` | `Arg0` | `CString` |  |
| `GetLowerBound` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetProgress` | `Arg0` | `float` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUpperBound` |  | `int32` |  |
| `GetWidth` |  | `int32` |  |
| `IsActive` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## LensOption

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDecreeType` |  | `DecreeType` |  |
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `AccessSelf` |  |  |  |
| `Activate` |  | `void` |  |
| `CanActivate` |  | `bool` |  |
| `GetCostText` |  | `CString` |  |
| `GetDecreeType` |  |  |  |
| `GetDiplomaticAction` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetMapInteraction` |  | `MapInteraction` |  |
| `GetNumberOfActiveOptions` |  | `int32` |  |
| `GetNumberOfInactiveSelectableOptions` |  | `int32` |  |
| `GetNumberOfSelections` |  | `int32` |  |
| `GetText` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `IsActive` |  | `bool` |  |
| `IsDecree` |  | `bool` |  |
| `IsDiplomaticAction` |  | `bool` |  |
| `IsMapInteraction` |  | `bool` |  |
| `Self` |  |  |  |
| `ShouldShowNumberOfSelections` |  | `bool` |  |
| `Toggle` |  | `void` |  |

## LensTab

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetText` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `IsOpen` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Open` |  | `void` |  |
| `Self` |  |  |  |

## LensToolbar

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentTab` |  | `LensTab` |  |
| `AccessSelf` |  |  |  |
| `ActivateOption` | `Arg0` | `void` |  |
| `Close` |  | `void` |  |
| `GetCurrentTab` |  |  |  |
| `GetMaxNumItemsPerRow` |  | `int32` |  |
| `GetOptions` |  |  |  |
| `GetTabs` |  |  |  |
| `IsAnyLensOpen` |  | `bool` |  |
| `IsLensOpen` | `Arg0` | `bool` |  |
| `Open` | `Arg0` | `void` |  |
| `OpenTab` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `Toggle` | `Arg0` | `void` |  |
| `ToggleOption` | `Arg0` | `void` |  |

## LibertyDesireLevel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBackground` |  |  |  |
| `GetEffects` |  | `CString` |  |
| `GetLowerBound` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetProgress` | `Arg0` | `float` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUpperBound` |  | `CFixedPoint` |  |
| `GetWidth` |  | `CFixedPoint` |  |
| `IsActive` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## LoadIngameWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedSavegame` |  | `SaveGameItem` |  |
| `AccessSelf` |  |  |  |
| `GetSaveGames` |  |  |  |
| `GetSelectedSavegame` |  |  |  |
| `HasSelectedSavegame` |  | `bool` |  |
| `IsEmpty` |  | `bool` |  |
| `OnBack` |  | `void` |  |
| `OnDelete` |  | `void` |  |
| `OnDeleteAll` |  | `void` |  |
| `OnLoad` |  | `void` |  |
| `OnShowInvalidSavegames` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldShowInvalidSavegames` |  | `bool` |  |

## LoadingScreenManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetConceptTip` |  | `GameConceptType` |  |
| `AccessSelf` |  |  |  |
| `GetConceptTip` |  |  |  |
| `GetStaticTip` |  | `CString` |  |
| `HasConceptTip` |  | `bool` |  |
| `HasStaticTip` |  | `bool` |  |
| `RollLoadingTip` |  | `void` |  |
| `Self` |  |  |  |

## LobbyPlayer

Jomini Multiplayer - Lobby Player

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetLobbyView` |  | `LobbyView` |  |
| `GetPlayable` |  | `Playable` |  |
| `AccessSelf` |  |  |  |
| `CanRemovePlayer` |  | `bool` |  |
| `GetID` |  | `int32` |  |
| `GetLoadingString` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTransferProgress` |  | `float` |  |
| `HasPlayable` |  | `bool` |  |
| `IsHost` |  | `bool` |  |
| `IsHotjoining` |  | `bool` |  |
| `IsLocalPlayer` |  | `bool` |  |
| `IsObserver` |  | `bool` |  |
| `IsReady` |  | `bool` |  |
| `RemovePlayer` |  | `void` |  |
| `Self` |  |  |  |
| `ShowReadyStatus` |  | `bool` |  |

## LobbyView

Multiplayer GUI - Lobby View

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessLocalPlayer` |  | `LobbyPlayer` |  |
| `AccessSelectedPlayable` |  | `Playable` |  |
| `GetSelectedPlayable` |  | `Playable` |  |
| `GetServerInfo` |  | `ServerInformation` |  |
| `AccessSelectedPlayable` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanControlSelected` |  | `bool` |  |
| `CanGoBack` |  | `bool` |  |
| `CanReady` |  | `bool` |  |
| `CanStart` |  | `bool` |  |
| `ClearSelection` |  | `void` |  |
| `ControlSelected` |  | `void` |  |
| `CopyServerID` |  | `void` |  |
| `GetControlToolTip` |  | `CString` |  |
| `GetEnabledDLCs` |  |  |  |
| `GetEnabledMods` |  |  |  |
| `GetGoBackToolTip` |  | `CString` |  |
| `GetOpenMultiplayerToolTip` |  | `CString` |  |
| `GetOtherPlayersCount` |  | `int32` |  |
| `GetReadyToolTip` |  | `CString` |  |
| `GetSelectText` |  | `CString` |  |
| `GetTransferSpeedSettingIndex` |  | `CVector2i` |  |
| `GetTransferSpeedSettingOptions` |  |  |  |
| `GoBack` |  | `void` |  |
| `HasEnabledDLCs` |  | `bool` |  |
| `HasEnabledMods` |  | `bool` |  |
| `HasGameConfigurationWindow` |  | `bool` |  |
| `HasSelectedPlayable` |  | `bool` |  |
| `HasServerInfo` |  | `bool` |  |
| `IsAutoAccept` |  | `bool` |  |
| `IsInvite` |  | `bool` |  |
| `IsObserver` |  | `bool` |  |
| `IsPublicCrossplay` |  | `bool` |  |
| `IsPublicNoCrossplay` |  | `bool` |  |
| `IsReady` |  | `bool` |  |
| `OnNameEdit` |  | `void` |  |
| `OnPasswordEdit` |  | `void` |  |
| `OnTransferSpeedSettingChanged` |  | `void` |  |
| `OpenGameConfigurationWindow` |  | `void` |  |
| `OpenMultiplayer` |  | `void` |  |
| `Players` |  |  |  |
| `Ready` |  | `void` |  |
| `Self` |  |  |  |
| `SetInvite` |  | `void` |  |
| `SetName` |  | `void` |  |
| `SetPassword` |  | `void` |  |
| `SetPublicCrossplay` |  | `void` |  |
| `SetPublicNoCrossplay` |  | `void` |  |
| `SetShowPlayerList` | `Arg0` | `void` |  |
| `ShouldShowEnabledDLCs` |  | `bool` |  |
| `ShouldShowEnabledMods` |  | `bool` |  |
| `ShowHosting` |  | `bool` |  |
| `ShowModifyServer` |  | `bool` |  |
| `ShowPlayerList` |  | `bool` |  |
| `Start` |  | `void` |  |
| `StartToolTip` |  | `CString` |  |
| `ToggleAutoAccept` |  | `void` |  |
| `ToggleObserve` |  | `void` |  |
| `ToggleShowEnabledDLCs` |  | `void` |  |
| `ToggleShowEnabledMods` |  | `void` |  |
| `ToggleVisibility` |  | `void` |  |
| `UnReady` |  | `void` |  |

## Location

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetID` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetType` |  | `CString` |  |
| `GoToLocation` |  | `void` |  |
| `Self` |  |  |  |

## LocationFinder

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `GetLocations` |  |  |  |
| `Self` |  |  |  |

## LogEntry

Texture Importer - Log Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetText` |  | `CString` |  |
| `GetTime` |  | `CString` |  |
| `Self` |  |  |  |

## LoginView

Login View

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetEmail` |  | `CUTF8String` |  |
| `GetErrorMessage` |  | `CUTF8String` |  |
| `GetLoginString` |  | `CUTF8String` |  |
| `GetPassword` |  | `CUTF8String` |  |
| `Hide` |  | `void` |  |
| `IsChangingUserName` |  | `bool` |  |
| `IsConnectingAccount` |  | `bool` |  |
| `IsEmailSent` |  | `bool` |  |
| `IsEmptyUserNamePrompt` |  | `bool` |  |
| `IsLoggedIn` |  | `bool` |  |
| `IsLogin` |  | `bool` |  |
| `IsRestoringPassword` |  | `bool` |  |
| `IsSuccessfulSetName` |  | `bool` |  |
| `IsValidLoginInfo` |  | `bool` |  |
| `Login` |  | `void` |  |
| `Logout` |  | `void` |  |
| `OnUserNameChange` |  | `void` |  |
| `ResetPassword` |  | `void` |  |
| `Self` |  |  |  |
| `SetEmail` |  | `void` |  |
| `SetPassword` |  | `void` |  |
| `SetState` | `Arg0` | `void` |  |
| `SetUserName` |  | `void` |  |
| `Show` |  | `void` |  |
| `ToggleConnected` |  | `void` |  |

## LogViewer

Log Viewer Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetLastLogEntry` |  | `LogViewerEntry` |  |
| `GetSelectedLogEntry` |  | `LogViewerEntry` |  |
| `AccessCategories` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTypes` |  |  |  |
| `DecreaseLogInfoExpandSize` |  | `void` |  |
| `FlushLog` |  | `void` |  |
| `GetFilteredNum` |  | `int32` |  |
| `GetLastLogEntry` |  |  |  |
| `GetLogInfoExpandSize` |  | `int32` |  |
| `GetLogInfoExpandSizeVector` | `Arg0` | `CVector2f` |  |
| `GetSelectedLogEntry` |  |  |  |
| `GetTextFilter` |  | `CUTF8String` |  |
| `HasEntries` |  | `bool` |  |
| `IncreaseLogInfoExpandSize` |  | `void` |  |
| `IsAnyEntrySelected` |  | `bool` |  |
| `OpenLinkedLogViewer` |  | `void` |  |
| `OpenLinkedLogViewerFilteredByType` | `Arg0` | `void` |  |
| `ResetFilters` |  | `void` |  |
| `ResetTextFilter` |  | `void` |  |
| `Self` |  |  |  |
| `SetTextFilter` |  | `void` |  |
| `ToggleHidden` |  | `void` |  |

## LogViewerCategory

Log Viewer - Log Category

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFilteredCount` |  | `int32` |  |
| `GetIcon` |  |  |  |
| `GetIsFiltered` |  | `bool` |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFiltered` | `Arg0` | `void` |  |

## LogViewerEntry

Log Viewer - Log Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ContainsScriptFile` |  | `bool` |  |
| `GetFileLineNo` |  | `int32` |  |
| `GetFilename` |  |  |  |
| `GetFilepath` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetMessage` |  | `CString` |  |
| `GetTimestampLong` |  | `CString` |  |
| `GetTimestampShort` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `OpenInCodeEditor` |  | `void` |  |
| `OpenInEditor` |  | `void` |  |
| `OpenInExternalLogViewer` |  | `void` |  |
| `OpenInScriptEditor` |  | `void` |  |
| `Self` |  |  |  |
| `SetSelected` | `Arg0` | `void` |  |

## LogViewerType

Log Viewer - Log Entry Type

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFilteredCount` |  | `int32` |  |
| `GetIcon` |  |  |  |
| `GetId` |  | `int32` |  |
| `GetIsFiltered` |  | `bool` |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |
| `SetIsFiltered` | `Arg0` | `void` |  |

## LoyaltyType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCountryGraphicalRatio` | `Arg0` | `float` |  |
| `GetCountryTooltip` | `Arg0` | `CString` |  |
| `GetCountryTrend` | `Arg0` | `DataTrend` |  |
| `GetHeader` |  | `CString` |  |
| `GetInterestGroupTooltip` | `Arg0` | `CString` |  |
| `GetInterestGroupTrend` | `Arg0` | `DataTrend` |  |
| `HasTrend` |  | `bool` |  |
| `Self` |  |  |  |
