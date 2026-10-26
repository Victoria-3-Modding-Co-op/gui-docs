# Data-binding types: P

Back to the [index](README.md).

## PanelMilitary

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `AccessCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanAnyUnitInAnyPlayerFormationBeUpgraded` |  | `bool` |  |
| `GetCountry` |  |  |  |
| `GetUpgradeAllUnitsInAllFormationsCommand` |  | `Command` |  |
| `OnClickRecruitArmyFormation` |  | `void` |  |
| `OnClickRecruitFleetFormation` |  | `void` |  |
| `Self` |  |  |  |

## ParametricSelect

Map Editor - Heightmap Parameter Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsHeightDeltaEnabled` |  | `bool` |  |
| `IsHeightRangeEnabled` |  | `bool` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |
| `SetHeightDeltaMax` |  | `void` |  |
| `SetHeightDeltaMin` |  | `void` |  |
| `SetHeightRangeMax` |  | `void` |  |
| `SetHeightRangeMin` |  | `void` |  |
| `Toggle` |  | `void` |  |

## ParticleUserData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Id` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `Label` |  | `CString` |  |
| `Remove` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleSelected` |  | `void` |  |
| `TypeName` |  |  |  |
| `TypeSize` |  | `int32` |  |

## Party

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetLeader` |  | `InterestGroup` |  |
| `GetLeaderCharacter` |  | `Character` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanJoinGovernment` |  | `bool` |  |
| `GetCanJoinGovernmentDesc` |  | `CString` |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCountry` |  |  |  |
| `GetCurrentPollNumVoters` |  | `int64` |  |
| `GetCurrentPollNumVotersDifference` |  | `int64` |  |
| `GetCurrentPollVotingPower` |  | `int64` |  |
| `GetCurrentPollVotingPowerDifference` |  | `int64` |  |
| `GetCurrentPollVotingPowerShare` |  | `CFixedPoint` |  |
| `GetCurrentVotingPower` |  | `int64` |  |
| `GetCurrentVotingPowerShare` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetElectionVotesTrend` |  | `DataTrend` |  |
| `GetIcon` |  |  |  |
| `GetIndependentIGs` |  |  |  |
| `GetJoinWeightBreakdown` | `Arg0` | `CString` |  |
| `GetLeader` |  |  |  |
| `GetLeaderCharacter` |  |  |  |
| `GetMembers` |  |  |  |
| `GetMembersBreakdown` |  | `CString` |  |
| `GetMembersSummary` |  | `CString` |  |
| `GetMomentum` |  | `CFixedPoint` |  |
| `GetMomentumDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumVotersLastElection` |  | `int64` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsInGovernment` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## PartyPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessParty` |  | `Party` |  |
| `GetParty` |  | `Party` |  |
| `AccessParty` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetParty` |  |  |  |
| `Self` |  |  |  |

## PastBattleMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBattle` |  | `Battle` |  |
| `AccessSelf` |  |  |  |
| `GetBattle` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## PastNavalBattleMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetNavalBattle` |  | `NavalBattle` |  |
| `AccessSelf` |  |  |  |
| `GetNavalBattle` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## PauseMenu

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanLoadIngame` |  | `bool` |  |
| `ExitGame` |  | `void` |  |
| `GetExitName` |  | `CString` |  |
| `IsLobbyOpen` |  | `bool` |  |
| `LoadIngame` |  | `void` |  |
| `LoadIngameTooltip` |  | `CString` |  |
| `OpenLobby` |  | `void` |  |
| `OpenSettings` |  | `void` |  |
| `Resume` |  | `void` |  |
| `Save` |  | `void` |  |
| `Self` |  |  |  |
| `SwitchCountry` |  | `void` |  |

## PdxAccount

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetInventory` |  | `AccountInventory` |  |
| `AccessSelf` |  |  |  |
| `GetLastLinkError` |  |  |  |
| `GetLastLinkErrorLocalized` |  | `CString` |  |
| `GetThirdPartyProviderLocalizationKey` |  | `CString` |  |
| `GetThirdPartyProviderLocalizedName` |  | `CString` |  |
| `IsLinkingPossible` |  | `bool` |  |
| `IsLoggedIn` |  | `bool` |  |
| `Self` |  |  |  |

## PdxCoreSetting

Settings Window - Core Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `RequireApply` |  | `bool` |  |
| `RequireRestart` |  | `bool` |  |
| `Self` |  |  |  |

## PdxEnumSetting

Settings Window - Enum Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HasValueChanged` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## PdxGuiFoldOut

Foldable Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Fold` |  | `void` |  |
| `IsFolded` |  | `bool` |  |
| `IsUnfolded` |  | `bool` |  |
| `Self` |  |  |  |
| `SetFoldState` |  | `void` |  |
| `Toggle` |  | `void` |  |
| `Unfold` |  | `void` |  |

## PdxGuiGfxVideoControl

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsLooping` |  | `bool` |  |
| `IsPlaybackComplete` |  | `bool` |  |
| `IsPlaying` |  | `bool` |  |
| `Restart` |  | `void` |  |
| `Self` |  |  |  |
| `SetLooping` | `Arg0` | `void` |  |
| `Start` |  | `void` |  |
| `Stop` |  | `void` |  |

## PdxGuiTableRow

Generic Tree Table - Row

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIndex` |  | `int32` |  |
| `Self` |  |  |  |

## PdxGuiTreeTable

Generic Tree-Table

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanExpand` | `Arg0` | `bool` |  |
| `Expand` | `Arg0` | `void` |  |
| `GetDepth` | `Arg0` | `int32` |  |
| `GetIndent` | `Arg0, Arg1` | `CVector2f` |  |
| `GetNumChildren` | `Arg0` | `int32` |  |
| `IsExpanded` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpand` | `Arg0` | `void` |  |
| `Unexpand` | `Arg0` | `void` |  |

## PdxGuiWidget

GUI Widget

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessChild` | `Arg0` | `PdxGuiWidget` |  |
| `AccessParent` |  | `PdxGuiWidget` |  |
| `FindChild` | `Arg0` | `PdxGuiWidget` |  |
| `GfxVideoControl` |  | `PdxGuiGfxVideoControl` |  |
| `AccessParent` |  |  |  |
| `AccessSelf` |  |  |  |
| `CountVisibleChildren` |  | `int32` |  |
| `FindChild` | `Arg0` |  |  |
| `GetChildrenCount` |  | `int32` |  |
| `GetIndexInDataModel` |  | `int32` |  |
| `GetRawShortcut` |  | `CUTF8String` |  |
| `GetShortcut` |  | `CUTF8String` |  |
| `GetTooltipLockProgress` |  | `float` |  |
| `HasContext` | `Arg0` | `bool` |  |
| `Hide` |  | `void` |  |
| `InterruptAnimation` | `Arg0` | `void` |  |
| `InterruptThenTriggerAnimation` | `Arg0, Arg1` | `void` |  |
| `IsNestedTooltip` |  | `bool` |  |
| `IsTooltipLocked` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Parent` |  |  |  |
| `Self` |  |  |  |
| `Show` |  | `void` |  |
| `StackBottom` |  | `void` |  |
| `StackTop` |  | `void` |  |
| `TriggerAnimation` | `Arg0` | `void` |  |
| `DisableValueUpdate` |  | `void` | Map Editor Internal usage |
| `EnableValueUpdate` |  | `void` | Map Editor Internal usage |

## PdxSetting

Settings Window - Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSettingPromoted` |  | `PdxCoreSetting` |  |
| `AccessSelf` |  |  |  |
| `AccessSetting` |  |  |  |
| `ChangesNotSaved` |  | `bool` |  |
| `GetSetting` |  |  |  |
| `GetTitle` |  | `CUTF8String` |  |
| `GetTooltip` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## PdxSettingsWindow

Settings Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AllowApply` |  | `bool` |  |
| `AllowRestore` |  | `bool` |  |
| `AppliedOnRestart` |  | `bool` |  |
| `HasChanged` |  | `bool` |  |
| `OnApply` |  | `void` |  |
| `OnCancel` |  | `void` |  |
| `OnRestore` |  | `void` |  |
| `OnSave` |  | `void` |  |
| `Self` |  |  |  |

## PdxSettingsWindowCategory

Settings Window - Category

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## PdxValueSetting

Settings Window - Value Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFormattedPendingValue` | `Arg0` | `CString` |  |
| `GetPendingValue` | `Arg0` | `float` |  |
| `HasValueChanged` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## PieTimer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetSlices` |  |  |  |
| `GetSlicesInverted` |  |  |  |
| `Self` |  |  |  |

## PieTimerSlice

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetValue` |  | `float` |  |
| `Self` |  |  |  |

## Playable

Jomini Playable

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## Player

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPlayedOrObservedCountry` |  | `Country` |  |
| `GetPlayedOrObservedCountry` |  | `Country` |  |
| `AccessPlayedOrObservedCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetPlayedOrObservedCountry` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasPlayable` |  | `bool` |  |
| `IsHost` |  | `bool` |  |
| `IsObserver` |  | `bool` |  |
| `IsPlayedOrObservedCountry` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## PlayerJoinRequest

Jomini Multiplayer - Player Join Request

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `Accept` |  | `void` |  |
| `AccessSelf` |  |  |  |
| `GetPlayerName` |  | `CString` |  |
| `IsChecked` |  | `bool` |  |
| `Reject` |  | `void` |  |
| `Self` |  |  |  |
| `Toggle` |  | `void` |  |

## PlayerMessageItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetDiploPlay` |  | `DiplomaticPlay` |  |
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `GetInstitution` |  | `Institution` |  |
| `GetLaw` |  | `Law` |  |
| `GetPrevLaw` |  | `Law` |  |
| `GetScopeActorCountry` |  | `Country` |  |
| `GetScopeDiploPlay` |  | `DiplomaticPlay` |  |
| `GetScopeTargetCountry` |  | `Country` |  |
| `GetScopeTechnology` |  | `Technology` |  |
| `GetTopScope` |  | `TopScope` |  |
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCountry` |  |  |  |
| `GetDate` |  | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetDiploPlay` |  |  |  |
| `GetDiplomaticAction` |  |  |  |
| `GetInstitution` |  |  |  |
| `GetLaw` |  |  |  |
| `GetMessageGroupTag` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetOnCreatedSoundEvent` |  |  |  |
| `GetPrevLaw` |  |  |  |
| `GetScopeActorCountry` |  |  |  |
| `GetScopeDiploPlay` |  |  |  |
| `GetScopeTargetCountry` |  |  |  |
| `GetScopeTechnology` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTopScope` |  |  |  |
| `Self` |  |  |  |

## PlotLine

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInterpolatedIndexNearMouse` |  | `float` |  |
| `GetInterpolatedValueNearMouse` |  | `CVector2f` |  |
| `GetPlotRect` |  | `CPdxFloatRect` |  |
| `GetSnappedIndexNearMouse` |  | `int32` |  |
| `GetSnappedValueNearMouse` |  | `CVector2f` |  |
| `HasPositionNearMouse` |  | `bool` |  |
| `Self` |  |  |  |

## PoliticalLobby

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetEstablishmentDate` |  | `Date` |  |
| `GetTargetCountry` |  | `Country` |  |
| `GetType` |  | `PoliticalLobbyType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CalcJoinWeight` | `Arg0` | `CFixedPoint` |  |
| `CalcJoinWeightDesc` | `Arg0` | `CString` |  |
| `GetAppeasement` |  | `int32` |  |
| `GetAppeasementChangesDesc` |  | `CString` |  |
| `GetAppeasementEffectsDesc` |  | `CString` |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDeficitAppeasementForProgressBar` |  | `CFixedPoint` |  |
| `GetDisbandReasonDesc` |  | `CString` |  |
| `GetEstablishmentDate` |  |  |  |
| `GetExcessAppeasementForProgressBar` |  | `CFixedPoint` |  |
| `GetMembers` |  |  |  |
| `GetMembersDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetTargetCountry` |  |  |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalClout` |  | `CFixedPoint` |  |
| `GetTotalCloutBreakdown` |  | `CString` |  |
| `GetType` |  |  |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `TogglePinInOutliner` |  | `void` |  |

## PoliticalLobbyAppeasementFactor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PoliticalLobbyMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPlacementCountry` |  | `Country` |  |
| `GetPoliticalLobby` |  | `PoliticalLobby` |  |
| `AccessSelf` |  |  |  |
| `GetPlacementCountry` |  |  |  |
| `GetPoliticalLobby` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## PoliticalLobbyPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPoliticalLobby` |  | `PoliticalLobby` |  |
| `AccessSelf` |  |  |  |
| `GetPoliticalLobby` |  |  |  |
| `Self` |  |  |  |

## PoliticalLobbyType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetAppeasementFactorsAnti` |  |  |  |
| `GetAppeasementFactorsPro` |  |  |  |
| `GetCategory` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PoliticalMovement

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCivilWar` |  | `CivilWar` |  |
| `GetCoreIdeology` |  | `Ideology` |  |
| `GetCountry` |  | `Country` |  |
| `GetSupportingPops` |  | `PopList` |  |
| `GetType` |  | `PoliticalMovementType` |  |
| `GetUprisingDefinition` |  | `CountryDefinition` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanCauseObstinance` |  | `bool` |  |
| `EndorsesEnactingLaw` | `Arg0` | `bool` |  |
| `GetAffectedLawsStall` |  |  |  |
| `GetAffectedLawsSuccess` |  |  |  |
| `GetAffectedStallPercentageOnLaw` | `Arg0` | `CFixedPoint` |  |
| `GetAffectedSuccessPercentageOnEndorsedLaws` |  | `CFixedPoint` |  |
| `GetAffectedSuccessPercentageOnLaw` | `Arg0` | `CFixedPoint` |  |
| `GetAffectedSuccessPercentageOnOpposedLaws` |  | `CFixedPoint` |  |
| `GetBolsteringEffectDesc` |  | `CString` |  |
| `GetBottomSupportingCharacters` |  |  |  |
| `GetBottomSupportingCharactersDesc` |  | `CString` |  |
| `GetCharacterIdeologies` |  |  |  |
| `GetCivilWar` |  |  |  |
| `GetCoreIdeology` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetHighestStateObstinance` |  | `CFixedPoint` |  |
| `GetInfluencedInterestGroups` |  |  |  |
| `GetMilitarySupport` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNumOfObstinateStates` |  | `int32` |  |
| `GetNumSupportingIndividuals` |  | `int64` |  |
| `GetNumSupportingMilitaryIndividuals` |  | `int64` |  |
| `GetNumSupportingRadicals` |  | `int64` |  |
| `GetObstinateStatesBreakdown` |  | `CString` |  |
| `GetPopSupportFactors` |  |  |  |
| `GetPopularSupport` |  | `CFixedPoint` |  |
| `GetRadicalism` |  | `CFixedPoint` |  |
| `GetRadicalismTrend` |  | `DataTrend` |  |
| `GetSupport` |  | `CFixedPoint` |  |
| `GetSupportDesc` |  | `CString` |  |
| `GetSupportTrend` |  | `DataTrend` |  |
| `GetSupportingCharacters` |  |  |  |
| `GetSupportingInterestGroups` |  |  |  |
| `GetSupportingPops` |  |  |  |
| `GetSuppressionEffectDesc` |  | `CString` |  |
| `GetTargetRadicalism` |  | `CFixedPoint` |  |
| `GetTargetRadicalismDesc` |  | `CString` |  |
| `GetTargetSupport` |  | `CFixedPoint` |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTimedModifiers` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTopSupportingCharacters` |  |  |  |
| `GetType` |  |  |  |
| `GetUprisingDefinition` |  |  |  |
| `HasSeparateUprisingDefinition` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBolstered` |  | `bool` |  |
| `IsCausingObstinance` |  | `bool` |  |
| `IsInsurrectionary` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsRevolutionary` |  | `bool` |  |
| `IsSecessionist` |  | `bool` |  |
| `IsSuppressed` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `OpposesEnactingLaw` | `Arg0` | `bool` |  |
| `PredictNumberOfRadicalsEveryMonth` |  | `int64` |  |
| `Self` |  |  |  |
| `ToggleBolstering` |  | `Command` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `ToggleSuppression` |  | `Command` |  |

## PoliticalMovementCategory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasCulturalIdentity` |  | `bool` |  |
| `HasReligiousIdentity` |  | `bool` |  |
| `Self` |  |  |  |

## PoliticalMovementPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPoliticalMovement` |  | `PoliticalMovement` |  |
| `AccessSelf` |  |  |  |
| `GetPoliticalMovement` |  |  |  |
| `Self` |  |  |  |

## PoliticalMovementPopSupportFactor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PoliticalMovementType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCategory` |  | `PoliticalMovementCategory` |  |
| `GetCoreIdeology` |  | `Ideology` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCategory` |  |  |  |
| `GetCoreIdeology` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## PoliticsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessReformGovernment` |  | `ReformGovernment` |  |
| `GetReformGovernment` |  | `ReformGovernment` |  |
| `GetSearchBar` |  | `SearchBar` |  |
| `AccessActiveIGTraits` |  |  |  |
| `AccessReformGovernment` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetAgitatorSlots` |  |  |  |
| `GetCloutGraphDateEnd` |  | `CString` |  |
| `GetCloutGraphDateStart` |  | `CString` |  |
| `GetCloutGraphMax` |  | `CFixedPoint` |  |
| `GetPopulationGroupingsForClout` |  |  |  |
| `GetPopulationGroupingsForPopulation` |  |  |  |
| `GetReformGovernment` |  |  |  |
| `GetSearchBar` |  |  |  |
| `IsCloutGraphInitialized` |  | `bool` |  |
| `ResetAgitatorSlotInvites` |  | `void` |  |
| `Self` |  |  |  |

## Pop

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` |  | `Building` |  |
| `AccessCulture` |  | `Culture` |  |
| `AccessLargestInterestGroup` |  | `InterestGroup` |  |
| `AccessPopType` |  | `PopType` |  |
| `AccessReligion` |  | `Religion` |  |
| `AccessState` |  | `State` |  |
| `GetAcceptanceStatus` |  | `AcceptanceStatus` |  |
| `GetAssimilatingCulture` |  | `Culture` |  |
| `GetBuilding` |  | `Building` |  |
| `GetConvertingReligion` |  | `Religion` |  |
| `GetCountry` |  | `Country` |  |
| `GetCulture` |  | `Culture` |  |
| `GetLargestInterestGroup` |  | `InterestGroup` |  |
| `GetLargestPoliticalMovement` |  | `PoliticalMovement` |  |
| `GetPopType` |  | `PopType` |  |
| `GetReligion` |  | `Religion` |  |
| `GetSocialClass` |  | `SocialClass` |  |
| `GetState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessBuilding` |  |  |  |
| `AccessCulture` |  |  |  |
| `AccessLargestInterestGroup` |  |  |  |
| `AccessPopType` |  |  |  |
| `AccessReligion` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `AccessSupportedInterestGroups` |  |  |  |
| `CalcAnnualPollTaxAmount` |  | `CFixedPoint` |  |
| `GetAcceptanceStatus` |  |  |  |
| `GetAcceptanceValue` |  | `int32` |  |
| `GetAcceptanceValueDesc` |  | `CString` |  |
| `GetAdditionalSOLFactorsDesc` |  | `CString` |  |
| `GetAnimatedTypedPortrait` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5` |  |  |
| `GetAssimilatingCulture` |  |  |  |
| `GetAverageAnnualWage` |  | `CFixedPoint` |  |
| `GetConsumptionFactorDesc` |  | `CString` |  |
| `GetConvertingReligion` |  |  |  |
| `GetCulture` |  |  |  |
| `GetCurrentJobSatisfaction` |  | `CFixedPoint` |  |
| `GetCurrentSoLModifiers` |  | `int32` |  |
| `GetCurrentSoLModifiersDesc` |  | `CString` |  |
| `GetCurrentStandardOfLiving` |  | `int32` |  |
| `GetCurrentStandardOfLivingTrend` |  | `DataTrend` |  |
| `GetCurrentWealth` |  | `int32` |  |
| `GetCurrentWealthDesc` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDebugInfo` |  | `CString` |  |
| `GetDependentIncome` |  | `CFixedPoint` |  |
| `GetDependentIncomeDesc` |  | `CString` |  |
| `GetDependentIncomeSources` |  | `CString` |  |
| `GetDependentsSize` |  | `int64` |  |
| `GetEducationAccess` |  | `CFixedPoint` |  |
| `GetEducationAccessDetailsDesc` |  | `CString` |  |
| `GetExpectedSOLFactorsDesc` |  | `CString` |  |
| `GetExpectedStandardOfLiving` |  | `int32` |  |
| `GetExpectedStandardOfLivingDesc` |  | `CString` |  |
| `GetExpectedStandardOfLivingFromLiteracy` |  | `int32` |  |
| `GetExpectedStandardOfLivingFromLiteracyDesc` |  | `CString` |  |
| `GetExpenses` |  | `CFixedPoint` |  |
| `GetExpensesDesc` |  | `CString` |  |
| `GetFoodSecurityDesc` |  | `CString` |  |
| `GetFoodSecurityLabel` |  | `CString` |  |
| `GetFoodSecurityRaw` |  | `CFixedPoint` |  |
| `GetFormattedStandardOfLiving` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabel` |  | `CString` |  |
| `GetGoodsConsumption` |  |  |  |
| `GetIGMembershipDesc` |  | `CString` |  |
| `GetIncome` |  | `CFixedPoint` |  |
| `GetIncomeDesc` |  | `CString` |  |
| `GetIncomeExpensesBalanceDesc` |  | `CString` |  |
| `GetInterestGroupDependentMembers` | `Arg0` | `int64` |  |
| `GetInterestGroupMembers` | `Arg0` | `int64` |  |
| `GetInterestGroupWorkingAdultMembers` | `Arg0` | `int64` |  |
| `GetLargestInterestGroup` |  |  |  |
| `GetLargestPoliticalMovement` |  |  |  |
| `GetLiteracyDesc` |  | `CString` |  |
| `GetLiteracyGrowth` |  | `CFixedPoint` |  |
| `GetLiteracyGrowthDesc` |  | `CString` |  |
| `GetLiteracyRate` |  | `CFixedPoint` |  |
| `GetLocation` |  | `CString` |  |
| `GetMoney` |  | `CFixedPoint` |  |
| `GetMovementMembershipDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNeedsDesc` |  | `CString` |  |
| `GetNetGrowthRate` |  | `CFixedPoint` |  |
| `GetNextJobSatisfaction` |  | `CFixedPoint` |  |
| `GetNextJobSatisfactionDesc` |  | `CString` |  |
| `GetNumAssimilatingIndividuals` |  | `int64` |  |
| `GetNumConvertingIndividuals` |  | `int64` |  |
| `GetNumDependentPoliticalParticipants` |  | `int64` |  |
| `GetNumLoyalists` |  | `int64` |  |
| `GetNumPoliticalNonParticipants` |  | `int64` |  |
| `GetNumPoliticalParticipants` |  | `int64` |  |
| `GetNumPoliticallyInactive` |  | `int64` |  |
| `GetNumRadicals` |  | `int64` |  |
| `GetNumWorkforce` |  | `int64` |  |
| `GetPoliticalMovementSupportFraction` | `Arg0` | `CFixedPoint` |  |
| `GetPoliticalMovementSupporterCount` | `Arg0` | `int64` |  |
| `GetPoliticalMovementSupportersInterestGroupMembers` | `Arg0, Arg1` | `int64` |  |
| `GetPoliticalMovementSupportersLoyalists` | `Arg0` | `int64` |  |
| `GetPoliticalMovementSupportersPoliticalStrength` | `Arg0` | `int64` |  |
| `GetPoliticalMovementSupportersRadicals` | `Arg0` | `int64` |  |
| `GetPoliticalMovementTotalSupport` | `Arg0` | `CFixedPoint` |  |
| `GetPoliticalMovementTotalSupportDesc` | `Arg0` | `CString` |  |
| `GetPoliticalStrength` |  | `int64` |  |
| `GetPoliticalStrengthDesc` |  | `CString` |  |
| `GetPoliticalStrengthForIG` | `Arg0` | `int64` |  |
| `GetPoliticalStrengthTrend` |  | `DataTrend` |  |
| `GetPopAssimilationDesc` |  | `CString` |  |
| `GetPopConversionDesc` |  | `CString` |  |
| `GetPopGrowth` |  | `CFixedPoint` |  |
| `GetPopGrowthDesc` |  | `CString` |  |
| `GetPopType` |  |  |  |
| `GetQualificationsChangeDesc` | `Arg0` | `CString` |  |
| `GetQualificationsDesc` |  | `CString` |  |
| `GetReligion` |  |  |  |
| `GetSharesDesc` |  | `CString` |  |
| `GetSizeTrend` |  | `DataTrend` |  |
| `GetSocialClass` |  |  |  |
| `GetStarvationEffectDesc` |  | `CString` |  |
| `GetSupportedPoliticalMovements` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTopGoodsConsumption` |  |  |  |
| `GetTotalSize` |  | `int64` |  |
| `GetTypeDesc` |  | `CString` |  |
| `GetTypedPortrait` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5` |  |  |
| `GetWageDiscriminationDesc` |  | `CString` |  |
| `GetWageRequiredToHireFrom` |  | `CFixedPoint` |  |
| `GetWealthProgression` |  | `CFixedPoint` |  |
| `GetWeeklyExpenses` |  | `CFixedPoint` |  |
| `GetWorkforceIncome` |  | `CFixedPoint` |  |
| `GetWorkforceIncomeDesc` |  | `CString` |  |
| `GetWorkforceRatio` |  | `CFixedPoint` |  |
| `GetWorkforceRatioDesc` |  | `CString` |  |
| `GetWorksAt` |  | `CString` |  |
| `GetWorksAtList` |  | `CString` |  |
| `HasSubsistenceIncome` |  | `bool` |  |
| `HasWelfarePayments` |  | `bool` |  |
| `IsAcceptanceStatusIncreasing` |  | `bool` |  |
| `IsAssimilating` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsConverting` |  | `bool` |  |
| `IsEmployed` |  | `bool` |  |
| `IsInSevereStarvation` |  | `bool` |  |
| `IsInStarvation` |  | `bool` |  |
| `IsLookingForJob` |  | `bool` |  |
| `IsPaidWages` |  | `bool` |  |
| `IsSlave` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## PopBrowserPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetSearchBar` |  | `SearchBar` |  |
| `AcceptanceFilterAreNoStatusesShown` |  | `bool` |  |
| `AcceptanceFilterHideAllStatuses` |  | `void` |  |
| `AcceptanceFilterIsStatusShown` | `Arg0` | `bool` |  |
| `AcceptanceFilterShowAllStatuses` |  | `void` |  |
| `AcceptanceFilterToggleShown` | `Arg0` | `void` |  |
| `AcceptanceFiltersAreAllStasusesShown` |  | `bool` |  |
| `AccessSelf` |  |  |  |
| `CultureFilterAreAllShown` |  | `bool` |  |
| `CultureFilterAreNoneShown` |  | `bool` |  |
| `CultureFilterHideAll` |  | `void` |  |
| `CultureFilterIsShown` | `Arg0` | `bool` |  |
| `CultureFilterShowAll` |  | `void` |  |
| `CultureFilterToggleShown` | `Arg0` | `void` |  |
| `Filter` | `Arg0` | `void` |  |
| `GetAllAcceptanceStatuses` |  |  |  |
| `GetAllPopTypes` |  |  |  |
| `GetAllStates` |  |  |  |
| `GetCountry` |  |  |  |
| `GetFilteredAverageJobSatisfaction` |  | `CFixedPoint` |  |
| `GetFilteredAverageLiteracy` |  | `CFixedPoint` |  |
| `GetFilteredAverageStandardOfLiving` |  | `CFixedPoint` |  |
| `GetFilteredCultures` |  |  |  |
| `GetFilteredNumLoyalists` |  | `int64` |  |
| `GetFilteredNumRadicals` |  | `int64` |  |
| `GetFilteredPolStrForPopType` | `Arg0` | `int64` |  |
| `GetFilteredPoliticalStrength` |  | `int64` |  |
| `GetFilteredPopTypes` |  |  |  |
| `GetFilteredPopTypesSortedByPolStr` |  |  |  |
| `GetFilteredReligions` |  |  |  |
| `GetFilteredStates` |  |  |  |
| `GetFilteredTotalSize` |  | `int64` |  |
| `GetFilteredTotalSizeForCulture` | `Arg0` | `int64` |  |
| `GetFilteredTotalSizeForPopType` | `Arg0` | `int64` |  |
| `GetFilteredTotalSizeForReligion` | `Arg0` | `int64` |  |
| `GetFilteredTotalSizeForState` | `Arg0` | `int64` |  |
| `GetSearchBar` |  |  |  |
| `GetSortedAndFilteredPops` |  |  |  |
| `IsAnyFilterActive` |  | `bool` |  |
| `IsFilterNo` | `Arg0` | `bool` |  |
| `IsFilterYes` | `Arg0` | `bool` |  |
| `IsFiltered` | `Arg0` | `bool` |  |
| `IsSorted` | `Arg0` | `bool` |  |
| `PopTypeFilterAreAllShown` |  | `bool` |  |
| `PopTypeFilterAreNoneShown` |  | `bool` |  |
| `PopTypeFilterHideAll` |  | `void` |  |
| `PopTypeFilterIsShown` | `Arg0` | `bool` |  |
| `PopTypeFilterShowAll` |  | `void` |  |
| `PopTypeFilterToggleShown` | `Arg0` | `void` |  |
| `ReligionFilterAreAllShown` |  | `bool` |  |
| `ReligionFilterAreNoneShown` |  | `bool` |  |
| `ReligionFilterHideAll` |  | `void` |  |
| `ReligionFilterIsShown` | `Arg0` | `bool` |  |
| `ReligionFilterShowAll` |  | `void` |  |
| `ReligionFilterToggleShown` | `Arg0` | `void` |  |
| `ResetAllFilters` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilterMode` | `Arg0, Arg1` | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `StateFilterAreNoStatesShown` |  | `bool` |  |
| `StateFilterHideAllStates` |  | `void` |  |
| `StateFilterIsStateShown` | `Arg0` | `bool` |  |
| `StateFilterShowAllStates` |  | `void` |  |
| `StateFilterToggleShown` | `Arg0` | `void` |  |
| `StateFiltersAreAllStatesShown` |  | `bool` |  |

## PopConsumptionGoods

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `GetPop` |  | `Pop` |  |
| `AccessSelf` |  |  |  |
| `GetConsumptionAmount` |  | `CFixedPoint` |  |
| `GetConsumptionRatio` |  | `CFixedPoint` |  |
| `GetGoods` |  |  |  |
| `GetPop` |  |  |  |
| `GetPopNeedsDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PopDetailsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPop` |  | `Pop` |  |
| `AccessPop` |  |  |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## PopList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuildingContext` |  | `Building` |  |
| `GetInterestGroupContext` |  | `InterestGroup` |  |
| `GetItem0` |  | `PopListItem` |  |
| `GetItem1` |  | `PopListItem` |  |
| `GetItem2` |  | `PopListItem` |  |
| `GetItem3` |  | `PopListItem` |  |
| `GetPoliticalMovementContext` |  | `PoliticalMovement` |  |
| `AccessSelf` |  |  |  |
| `GetAverageStandardOfLiving` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingLabel` |  | `CString` |  |
| `GetBuildingContext` |  |  |  |
| `GetInterestGroupContext` |  |  |  |
| `GetItem0` |  |  |  |
| `GetItem1` |  |  |  |
| `GetItem2` |  |  |  |
| `GetItem3` |  |  |  |
| `GetItems` |  |  |  |
| `GetPoliticalMovementContext` |  |  |  |
| `GetPoliticalStrengthAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetTotalPoliticalStrength` |  | `int64` |  |
| `GetTotalPopulation` |  | `int64` |  |
| `HasBuildingContext` |  | `bool` |  |
| `HasInterestGroupContext` |  | `bool` |  |
| `HasPoliticalMovementContext` |  | `bool` |  |
| `Self` |  |  |  |

## PopListItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPopType` |  | `PopType` |  |
| `GetFirstPop` |  | `Pop` |  |
| `GetPopType` |  | `PopType` |  |
| `AccessPopType` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTwoLargestIGs` |  |  |  |
| `GetAverageAnnualWage` |  | `CFixedPoint` |  |
| `GetAverageSoL` |  | `float` |  |
| `GetDependentsPopSize` |  | `int64` |  |
| `GetEmploymentDesc` |  | `CString` |  |
| `GetFirstPop` |  |  |  |
| `GetNumLoyalists` |  | `int64` |  |
| `GetNumRadicals` |  | `int64` |  |
| `GetNumTotalPops` |  | `int32` |  |
| `GetPopType` |  |  |  |
| `GetPops` |  |  |  |
| `GetTotalPolStr` |  | `int64` |  |
| `GetTotalPolStrPercentage` |  | `float` |  |
| `GetTotalPoliticalMovementSupport` |  | `CFixedPoint` |  |
| `GetTotalPopSize` |  | `int64` |  |
| `GetTotalPopSizePercentage` |  | `float` |  |
| `GetWorkingAdultsPopSize` |  | `int64` |  |
| `IsAllPopsShown` |  | `bool` |  |
| `IsExpanded` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpand` |  | `void` |  |

## PopNeed

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDefaultGoods` |  | `Goods` |  |
| `GetPop` |  | `Pop` |  |
| `AccessSelf` |  |  |  |
| `CalcBaseCost` |  | `CFixedPoint` |  |
| `CalcTotalCost` |  | `CFixedPoint` |  |
| `GetConsumptionDesc` |  | `CString` |  |
| `GetDefaultGoods` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetDetailsDesc` |  | `CString` |  |
| `GetExpensesDesc` |  | `CString` |  |
| `GetGoods` |  |  |  |
| `GetGoodsDesc` |  | `CString` |  |
| `GetGoodsEquivalenceDesc` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetPop` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PopsOverviewPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPopsList` |  | `PopList` |  |
| `GetCharacterFilter` |  | `CharacterFilter` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `GetPopSearchBar` |  | `SearchBar` |  |
| `GetSearchBar` |  | `SearchBar` |  |
| `AccessPops` |  |  |  |
| `AccessPopsList` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetAverageIncomeMiddle` |  | `CFixedPoint` |  |
| `GetAverageIncomePoor` |  | `CFixedPoint` |  |
| `GetAverageIncomeRich` |  | `CFixedPoint` |  |
| `GetGoodsExpenseItemsMiddle` |  |  |  |
| `GetGoodsExpenseItemsPoor` |  |  |  |
| `GetGoodsExpenseItemsRich` |  |  |  |
| `GetGoodsExpensesMiddle` |  | `CFixedPoint` |  |
| `GetGoodsExpensesPoor` |  | `CFixedPoint` |  |
| `GetGoodsExpensesRich` |  | `CFixedPoint` |  |
| `GetIncomeRemainderMiddle` |  | `CFixedPoint` |  |
| `GetIncomeRemainderPoor` |  | `CFixedPoint` |  |
| `GetIncomeRemainderRich` |  | `CFixedPoint` |  |
| `GetPopSearchBar` |  |  |  |
| `GetSearchBar` |  |  |  |
| `GetTaxBurdenItemsMiddle` |  |  |  |
| `GetTaxBurdenItemsPoor` |  |  |  |
| `GetTaxBurdenItemsRich` |  |  |  |
| `GetTaxBurdenMiddle` |  | `CFixedPoint` |  |
| `GetTaxBurdenPoor` |  | `CFixedPoint` |  |
| `GetTaxBurdenRich` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## PopType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDependents` | `Arg0` | `int64` |  |
| `GetDependentsAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetInterestGroupSupportDesc` | `Arg0` | `CString` |  |
| `GetLoyalists` | `Arg0` | `int64` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNameNoIconNoFormatting` |  | `CString` |  |
| `GetPolStr` | `Arg0` | `int64` |  |
| `GetPolStrAsFloat` | `Arg0` | `float` |  |
| `GetPolStrAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetPopulation` | `Arg0` | `int64` |  |
| `GetPopulationAsFloat` | `Arg0` | `float` |  |
| `GetPopulationAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetQualificationsGrowthDesc` |  | `CString` |  |
| `GetRadicals` | `Arg0` | `int64` |  |
| `GetStateDependents` | `Arg0` | `int64` |  |
| `GetStateDependentsAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetStatePolStr` | `Arg0` | `int64` |  |
| `GetStatePolStrAsFloat` | `Arg0` | `float` |  |
| `GetStatePolStrAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetStatePopulation` | `Arg0` | `int64` |  |
| `GetStatePopulationAsFloat` | `Arg0` | `float` |  |
| `GetStatePopulationAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetStateWorkforce` | `Arg0` | `int64` |  |
| `GetStateWorkforceAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetStrataBreakdownInCountry` | `Arg0` | `CString` |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetWorkforce` | `Arg0` | `int64` |  |
| `GetWorkforceAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `HasSubsistenceIncome` |  | `bool` |  |
| `IsPaidWages` | `Arg0` | `bool` |  |
| `IsSlave` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## PopulationGrouping

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `AccessInterestGroup` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetGroupName` |  | `CString` |  |
| `GetInterestGroup` |  |  |  |
| `GetSizeInPercentage` |  | `float` |  |
| `IsInterestGroup` |  | `bool` |  |
| `Self` |  |  |  |

## PopupManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessShipDesignerPopup` |  | `ShipDesignerPopup` |  |
| `GetRecruitFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `AccessShipDesignerPopup` |  |  |  |
| `AnswerNo` | `Arg0` | `void` |  |
| `AnswerYes` | `Arg0` | `void` |  |
| `AskConfirmation` | `Arg0` | `void` |  |
| `AskConfirmationCustom` | `Arg0, Arg1` | `void` |  |
| `AskConfirmationCustomWithSound` | `Arg0, Arg1, Arg2` | `void` |  |
| `AskConfirmationWithSound` | `Arg0, Arg1` | `void` |  |
| `CloseGeneralInformationWindow` |  | `void` |  |
| `CloseMessage` | `Arg0` | `void` |  |
| `ClosePopups` |  | `void` |  |
| `CloseProposal` | `Arg0` | `void` |  |
| `DeclineProposal` | `Arg0` | `void` |  |
| `ExecuteOrAskConfirmationIfNeeded` | `Arg0` | `void` |  |
| `ExecuteOrAskConfirmationIfNeededCustom` | `Arg0, Arg1` | `void` |  |
| `ExecuteOrAskConfirmationIfNeededCustomWithSound` | `Arg0, Arg1, Arg2` | `void` |  |
| `ExecuteOrAskConfirmationIfNeededWithSound` | `Arg0, Arg1` | `void` |  |
| `GetRecruitFormation` |  |  |  |
| `Hide` |  | `void` |  |
| `HideCompanyChangeName` |  | `void` |  |
| `HideDecommissionSupplyShipsWindow` |  | `void` |  |
| `HideDiplomaticActionConfirmation` |  | `void` |  |
| `HideDiplomaticPlayConfirmation` |  | `void` |  |
| `HideInvasionPlannerPopup` |  | `void` |  |
| `HideMilitaryFormationChangeName` |  | `void` |  |
| `HideNationalizeBuildingWindow` |  | `void` |  |
| `HideOpenEvent` | `Arg0` | `void` |  |
| `HidePowerBlocCustomizationPopup` |  | `bool` |  |
| `HidePowerBlocPrincipleSelectionWindow` |  | `bool` |  |
| `HidePrestigeGoodChangeName` |  | `void` |  |
| `HideProposal` | `Arg0` | `void` |  |
| `HideRecruitAdmiral` |  | `bool` |  |
| `HideRecruitGeneral` |  | `bool` |  |
| `HideReleaseCountryConfirmation` |  | `void` |  |
| `HideRulerSelectionPopup` |  | `void` |  |
| `HideShipChangeName` |  | `void` |  |
| `HideShipDesignerPopup` |  | `bool` |  |
| `HideStateChangeName` |  | `void` |  |
| `HideTransferFormation` |  | `void` |  |
| `HideTransportPlannerPopup` |  | `void` |  |
| `OpenAlert` | `Arg0` | `void` |  |
| `OpenEvent` | `Arg0` | `void` |  |
| `OpenProposal` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `ShowCompanyChangeName` | `Arg0` | `void` |  |
| `ShowDecommissionSupplyShipsWindow` |  | `void` |  |
| `ShowDiplomaticPlayConfirmation` | `Arg0, Arg1, Arg2, Arg3` | `void` |  |
| `ShowInvasionPlannerPopup` | `Arg0` | `void` |  |
| `ShowMilitaryFormationChangeName` | `Arg0` | `void` |  |
| `ShowNationalizeBuildingWindow` | `Arg0` | `void` |  |
| `ShowPowerBlocCustomizationPopup` | `Arg0` | `void` |  |
| `ShowPowerBlocPrincipleSelectionWindow` | `Arg0, Arg1` | `void` |  |
| `ShowPrestigeGoodChangeName` | `Arg0` | `void` |  |
| `ShowReleaseCountryConfirmation` | `Arg0` | `void` |  |
| `ShowRulerSelectionPopup` | `Arg0` | `void` |  |
| `ShowShipChangeName` | `Arg0` | `void` |  |
| `ShowShipDesignerPopup` | `Arg0` | `void` |  |
| `ShowStateChangeName` | `Arg0` | `void` |  |
| `ShowTransferFormation` | `Arg0` | `void` |  |
| `TogglePowerBlocCustomizationPopup` |  | `void` |  |
| `ToggleRecruitAdmiral` |  | `bool` |  |
| `ToggleRecruitFormationAdmiral` | `Arg0` | `bool` |  |
| `ToggleRecruitFormationGeneral` | `Arg0` | `bool` |  |
| `ToggleRecruitGeneral` |  | `bool` |  |
| `ToggleShipDesignerPopup` |  | `void` |  |
| `ToggleShipDesignerPopupWithTemplate` | `Arg0` | `void` |  |

## PopWithIG

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetInterestGroup` |  | `InterestGroup` |  |
| `GetPop` |  | `Pop` |  |
| `AccessSelf` |  |  |  |
| `CalcAttractionToIG` |  | `CFixedPoint` |  |
| `GetAttractionToIGDesc` |  | `CString` |  |
| `GetInterestGroup` |  |  |  |
| `GetPop` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## Portrait3dView

Portrait Editor - 3D view window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAnimationTooltip` |  | `CString` |  |
| `GetPortraitContext` |  |  |  |
| `GetPortraitEntity` | `Arg0` |  |  |
| `SaveScreenshot` |  | `void` |  |
| `Self` |  |  |  |

## PortraitDataContext

Portrait Editor - Portrait Data

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## PortraitEditorAnimationItem

Portrait Editor - Animation Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## PortraitEditorWindow

Portrait Editor Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetChildGenerator` |  | `ChildGenerator` |  |
| `GetPortraitDataContext` |  | `PortraitDataContext` |  |
| `GetSelectedEthnicityItem` |  | `EthnicityItem` |  |
| `GetSelectedGeneItem` |  | `GeneItem` |  |
| `AccessSelf` |  |  |  |
| `CanOptimize` |  | `bool` |  |
| `GetAge` |  | `int32` |  |
| `GetAgePercent` |  | `float` |  |
| `GetAnimationItems` |  |  |  |
| `GetAnimationTooltip` | `Arg0` | `CString` |  |
| `GetCameraName` |  | `CString` |  |
| `GetCurrentAnimationFileDesc` |  | `CString` |  |
| `GetCurrentCameraFileDesc` |  | `CString` |  |
| `GetCurrentEnvironmentFileDesc` |  | `CString` |  |
| `GetCurrentEthnicityFileDesc` |  | `CString` |  |
| `GetCurrentGeneAccessoryString` |  | `CString` |  |
| `GetCurrentGeneFileDesc` |  | `CString` |  |
| `GetDNA` |  | `CString` |  |
| `GetEnvironmentName` |  | `CString` |  |
| `GetPortraitTexture` | `Arg0` |  |  |
| `GetSelectedAnimationIndex` |  | `CVector2i` |  |
| `GetSelectedGeneTemplateColorX` |  | `float` |  |
| `GetSelectedGeneTemplateColorY` |  | `float` |  |
| `GetSelectedGeneTemplateStrength` |  | `float` |  |
| `GetSliderMaxValue` |  | `float` |  |
| `GetSliderMinValue` |  | `float` |  |
| `HasAnySliders` |  | `bool` |  |
| `HasPoses` |  | `bool` |  |
| `HasSubGenes` |  | `bool` |  |
| `IsCurrentContentTab` | `Arg0` | `bool` |  |
| `IsSelectedAccessoryGene` |  | `bool` |  |
| `IsSelectedColorGene` |  | `bool` |  |
| `IsSelectedMorphGene` |  | `bool` |  |
| `IsSliderMode` | `Arg0` | `bool` |  |
| `IsSliderPortraitType` | `Arg0` | `bool` |  |
| `OnAgeChanged` |  | `void` |  |
| `OnChangeAnimationItemLeft` |  | `void` |  |
| `OnChangeAnimationItemRight` |  | `void` |  |
| `OnChangeEthnicityLeft` |  | `void` |  |
| `OnChangeEthnicityRight` |  | `void` |  |
| `OnChangeGeneLeft` |  | `void` |  |
| `OnChangeGeneRight` |  | `void` |  |
| `OnChangePoseItemLeft` |  | `void` |  |
| `OnChangePoseItemRight` |  | `void` |  |
| `OnChangeSubGeneItemLeft` |  | `void` |  |
| `OnChangeSubGeneItemRight` |  | `void` |  |
| `OnCopyDNA` |  | `void` |  |
| `OnCopyPersistentPortraitInfo` | `Arg0` | `void` |  |
| `OnGenerateFromEthnicity` |  | `void` |  |
| `OnGenerateFromEthnicityExcept` |  | `void` |  |
| `OnNextCamera` |  | `void` |  |
| `OnNextEnvironment` |  | `void` |  |
| `OnPasteDNA` |  | `void` |  |
| `OnPastePersistentPortraitInfo` |  | `void` |  |
| `OnPreviousCamera` |  | `void` |  |
| `OnPreviousEnvironment` |  | `void` |  |
| `OnRandomizePortraitId` |  | `void` |  |
| `OnReloadAssets` |  | `void` |  |
| `OnReloadColorPalettes` |  | `void` |  |
| `OnReloadDecals` |  | `void` |  |
| `OnResetDNA` |  | `void` |  |
| `OnRestartPortrait` |  | `void` |  |
| `OnRunTextureOptimization` |  | `void` |  |
| `Open3dView` | `Arg0` | `void` |  |
| `OpenCurrentAnimationFile` |  | `void` |  |
| `OpenCurrentCameraFile` |  | `void` |  |
| `OpenCurrentEnvironmentFile` |  | `void` |  |
| `OpenCurrentEthnicityFile` |  | `void` |  |
| `OpenCurrentGeneFile` |  | `void` |  |
| `ResetSliders` |  | `void` |  |
| `Self` |  |  |  |
| `SetContentTab` | `Arg0` | `void` |  |
| `SetSelectedAnimation` |  | `void` |  |
| `SetSliderMode` | `Arg0` | `void` |  |
| `SetSliderPortraitType` | `Arg0` | `void` |  |

## PortraitTooltip

Portrait Tooltip

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## PotentialLeaderIdeology

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCharacter` |  | `Character` |  |
| `GetIdeology` |  | `Ideology` |  |
| `AccessSelf` |  |  |  |
| `GetChanceBreakdown` |  | `CString` |  |
| `GetChancePercentage` |  | `CFixedPoint` |  |
| `HasCharacter` |  | `bool` |  |
| `HasMovement` |  | `bool` |  |
| `Self` |  |  |  |

## PowerBloc

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCohesionLevel` |  | `CohesionLevel` |  |
| `GetFlag` |  | `CoatOfArms` |  |
| `GetFoundingDate` |  | `Date` |  |
| `GetIdentity` |  | `PowerBlocIdentity` |  |
| `GetLeader` |  | `Country` |  |
| `GetLeaderModifier` |  | `Modifier` |  |
| `GetMember` | `Arg0` | `Country` |  |
| `GetMemberWithUniqueHeadOfState` | `Arg0` | `Country` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetNextMandateDate` |  | `Date` |  |
| `GetNonLeaderModifier` |  | `Modifier` |  |
| `GetParticipantWithHighestInfamy` |  | `Country` |  |
| `GetParticipantWithHighestLeaderLawProgressivenessDifference` |  | `Country` |  |
| `GetParticipantWithHighestLibertyDesire` |  | `Country` |  |
| `GetParticipantWithLowestEconomicDependence` |  | `Country` |  |
| `GetParticipantWithLowestEconomicDependenceOnLeader` |  | `Country` |  |
| `GetParticipantWithLowestLeaderRelations` |  | `Country` |  |
| `GetParticipantWithLowestLeaderReligionPercentage` |  | `Country` |  |
| `GetPowerBlocStatue` |  | `PowerBlocStatue` |  |
| `GetPowerStruggleContender` |  | `Country` |  |
| `GetPrincipleData` | `Arg0` | `PowerBlocPrincipleData` |  |
| `GetRequestToJoin` | `Arg0` | `DiplomaticAction` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBattalions` |  | `int32` |  |
| `GetBattalionsBreakdown` |  | `CString` |  |
| `GetCohesion` |  | `CFixedPoint` |  |
| `GetCohesionDesc` |  | `CString` |  |
| `GetCohesionLevel` |  |  |  |
| `GetCohesionTarget` |  | `CFixedPoint` |  |
| `GetCohesionWeeklyChange` |  | `CFixedPoint` |  |
| `GetConscriptableBattalions` |  | `int32` |  |
| `GetCurrentMandateProgress` |  | `CFixedPoint` |  |
| `GetCurrentMandateProgressPercentage` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFlag` |  |  |  |
| `GetFlagTextIcon` |  | `CString` |  |
| `GetFoundingDate` |  |  |  |
| `GetGdp` |  | `CFixedPoint` |  |
| `GetGdpDesc` |  | `CString` |  |
| `GetIdentity` |  |  |  |
| `GetIndividualLeverage` | `Arg0` | `CFixedPoint` |  |
| `GetLeader` |  |  |  |
| `GetLeaderModifier` |  |  |  |
| `GetLeverageAdvantage` | `Arg0` | `CFixedPoint` |  |
| `GetLeverageAdvantageDesc` | `Arg0` | `CString` |  |
| `GetLeverageFactor` | `Arg0` | `CFixedPoint` |  |
| `GetLeverageFactorDesc` | `Arg0` | `CString` |  |
| `GetMapTexture` |  |  |  |
| `GetMember` | `Arg0` |  |  |
| `GetMemberWithUniqueHeadOfState` | `Arg0` |  |  |
| `GetMembers` |  |  |  |
| `GetMembersBreakdown` |  | `CString` |  |
| `GetMembersWithUniqueHeadsOfState` |  |  |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNextMandateDate` |  |  |  |
| `GetNonLeaderModifier` |  |  |  |
| `GetNumMandates` |  | `int32` |  |
| `GetNumMembers` |  | `int32` |  |
| `GetParticipantWithHighestInfamy` |  |  |  |
| `GetParticipantWithHighestLeaderLawProgressivenessDifference` |  |  |  |
| `GetParticipantWithHighestLibertyDesire` |  |  |  |
| `GetParticipantWithLowestEconomicDependence` |  |  |  |
| `GetParticipantWithLowestEconomicDependenceOnLeader` |  |  |  |
| `GetParticipantWithLowestLeaderRelations` |  |  |  |
| `GetParticipantWithLowestLeaderReligionPercentage` |  |  |  |
| `GetPowerBlocStatue` |  |  |  |
| `GetPowerStruggleContender` |  |  |  |
| `GetPowerStruggleDesc` |  | `CString` |  |
| `GetPrestigeDesc` |  | `CString` |  |
| `GetPreviousName` |  | `CString` |  |
| `GetPrimaryColor` |  | `CVector4f` |  |
| `GetPrincipleData` | `Arg0` |  |  |
| `GetPrinciples` |  |  |  |
| `GetRankFormatted` |  | `CString` |  |
| `GetRankRaw` |  | `int32` |  |
| `GetRankTooltip` |  | `CString` |  |
| `GetRegularBattalions` |  | `int32` |  |
| `GetRequestToJoin` | `Arg0` |  |  |
| `GetShips` |  | `int32` |  |
| `GetShipsBreakdown` |  | `CString` |  |
| `GetTimedModifiers` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalPrestige` |  | `int32` |  |
| `GetWeeklyMandateProgress` |  | `CFixedPoint` |  |
| `GetWeeklyMandateProgressDesc` |  | `CString` |  |
| `HasIdentity` | `Arg0` | `bool` |  |
| `HasPendingInvitationForCountry` | `Arg0` | `bool` |  |
| `HasPendingRequestToJoinFromCountry` | `Arg0` | `bool` |  |
| `HasPrinciple` | `Arg0` | `bool` |  |
| `HasPrincipleFromGroup` | `Arg0` | `bool` |  |
| `Invite` | `Arg0` | `Command` |  |
| `IsActive` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsLeader` | `Arg0` | `bool` |  |
| `IsMember` | `Arg0` | `bool` |  |
| `IsPrincipleOnCooldown` | `Arg0` | `bool` |  |
| `IsRanked` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsZoomingToMapMarkerPosition` |  | `bool` |  |
| `Kick` | `Arg0` | `Command` |  |
| `MeetsPrimaryPrincipleRequirement` |  | `bool` |  |
| `OpenPendingInvitationForCountry` | `Arg0` | `void` |  |
| `PredictCohesionWithMember` | `Arg0` | `CFixedPoint` |  |
| `RequestToJoin` |  | `Command` |  |
| `Self` |  |  |  |
| `SortMembers` | `Arg0` | `void` |  |
| `ZoomToMapMarkerPosition` |  | `void` |  |

## PowerBlocCoaPiece

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCoa` |  | `CoatOfArms` |  |
| `AccessSelf` |  |  |  |
| `GetCoa` |  |  |  |
| `GetIndex` |  | `int32` |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `OnClicked` |  | `void` |  |
| `Self` |  |  |  |

## PowerBlocCoaPieceSelector

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedItem` |  | `PowerBlocCoaPiece` |  |
| `AccessSelf` |  |  |  |
| `GetItems` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetSelectedItem` |  |  |  |
| `OnNextClicked` |  | `void` |  |
| `OnPreviousClicked` |  | `void` |  |
| `Self` |  |  |  |

## PowerBlocCustomizationPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCustomCoaPreview` |  | `CoatOfArms` |  |
| `GetPowerBloc` |  | `PowerBloc` |  |
| `GetPowerBlocMapTextureSelector` |  | `PowerBlocMapTextureSelector` |  |
| `GetStatue` |  | `PowerBlocStatue` |  |
| `GetStatueHeroType` |  | `PowerBlocStatueHeroType` |  |
| `GetStatuePedestalType` |  | `PowerBlocStatuePedestalType` |  |
| `AccessSelf` |  |  |  |
| `AccessStatueAccessorySelectors` |  |  |  |
| `ConfirmClicked` |  | `void` |  |
| `ConfirmGetDesc` |  | `CString` |  |
| `ConfirmIsValid` |  | `bool` |  |
| `DisableStatueMouseRotation` |  | `void` |  |
| `EnableStatueMouseRotation` |  | `void` |  |
| `GetCameraPosition` |  | `CVector3f` |  |
| `GetCoaPieces` |  |  |  |
| `GetColorPickers` |  |  |  |
| `GetCustomCoaPreview` |  |  |  |
| `GetEmblemColor` |  | `CVector4f` |  |
| `GetMapColor` |  | `CVector4f` |  |
| `GetMapTexture` |  |  |  |
| `GetNewCustomName` |  | `CString` |  |
| `GetPowerBloc` |  |  |  |
| `GetPowerBlocMapTextureSelector` |  |  |  |
| `GetPrimaryColor` |  | `CVector4f` |  |
| `GetSecondaryColor` |  | `CVector4f` |  |
| `GetStatueHeroTypeOptions` |  |  |  |
| `GetStatuePedestalTypeOptions` |  |  |  |
| `OnEditName` |  | `void` |  |
| `RandomizeName` |  | `void` |  |
| `RandomizeStatue` |  | `void` |  |
| `Self` |  |  |  |
| `SetNextStatueHeroType` |  | `void` |  |
| `SetNextStatuePedestalType` |  | `void` |  |
| `SetPrevStatueHeroType` |  | `void` |  |
| `SetPrevStatuePedestalType` |  | `void` |  |
| `SetStatueHeroType` |  | `void` |  |
| `SetStatuePedestalType` |  | `void` |  |

## PowerBlocFormation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetConfirmedCustomCoaPreview` |  | `CoatOfArms` |  |
| `GetPrincipleSlot` | `Arg0` | `PowerBlocFormationPrincipleSlot` |  |
| `GetSelectedIdentity` |  | `PowerBlocIdentity` |  |
| `GetStatue` |  | `PowerBlocStatue` |  |
| `AccessSelf` |  |  |  |
| `CanSelectPrinciple` | `Arg0, Arg1` | `bool` |  |
| `Confirm` |  | `Command` |  |
| `GetCanSelectPrincipleDesc` | `Arg0, Arg1` | `CString` |  |
| `GetChosenName` |  | `CString` |  |
| `GetConfirmedCustomCoaPreview` |  |  |  |
| `GetIdentities` |  |  |  |
| `GetMapColor` |  | `CVector4f` |  |
| `GetMapTexture` |  |  |  |
| `GetNumSelectedPrinciples` |  | `int32` |  |
| `GetPrinciplePointsCostRaw` |  | `int32` |  |
| `GetPrinciplePointsRemainingRaw` |  | `int32` |  |
| `GetPrincipleSlot` | `Arg0` |  |  |
| `GetPrincipleSlots` |  |  |  |
| `GetPrinciples` |  |  |  |
| `HasSelectedPrimaryPrinciple` |  | `bool` |  |
| `HasSelectedPrinciple` | `Arg0` | `bool` |  |
| `HasSelectedPrincipleGroup` | `Arg0` | `bool` |  |
| `IsAnyIdentitySelected` |  | `bool` |  |
| `IsSelectedIdentity` | `Arg0` | `bool` |  |
| `RandomizeName` |  | `void` |  |
| `ResetPrinciples` |  | `void` |  |
| `SelectIdentity` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## PowerBlocFormationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPowerBlocFormation` |  | `PowerBlocFormation` |  |
| `AccessSelf` |  |  |  |
| `GetPowerBlocFormation` |  |  |  |
| `OnEditName` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleSelectPowerBlocIdentityMenu` | `Arg0` | `void` |  |

## PowerBlocFormationPrincipleSlot

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedPrinciple` |  | `PowerBlocPrinciple` |  |
| `AccessSelf` |  |  |  |
| `IsActive` |  | `bool` |  |
| `IsAnyPrincipleSelected` |  | `bool` |  |
| `IsChangingPrinciple` |  | `bool` |  |
| `IsNext` |  | `bool` |  |
| `IsSelectedPrinciple` | `Arg0` | `bool` |  |
| `IsUnlocked` |  | `bool` |  |
| `OnAnimationFinished` |  | `void` |  |
| `RemovePrinciple` |  | `void` |  |
| `Self` |  |  |  |

## PowerBlocIdentity

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBackground` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetIsPossibleDesc` |  | `CString` |  |
| `GetLeaderEffectDesc` |  | `CString` |  |
| `GetMemberEffectDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNonLeaderEffectDesc` |  | `CString` |  |
| `GetOnCreatedEffectDesc` | `Arg0` | `CString` |  |
| `GetPowerBlocEffectDesc` |  | `CString` |  |
| `GetPrimaryPrincipleGroups` |  |  |  |
| `GetPrinciplesDesc` |  | `CString` |  |
| `GetProductionMethodsDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUnlockedPrincipleGroups` |  |  |  |
| `IsPossible` |  | `bool` |  |
| `Self` |  |  |  |

## PowerBlocMapTexture

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetIndex` |  | `int32` |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `OnClicked` |  | `void` |  |
| `Self` |  |  |  |

## PowerBlocMapTextureSelector

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedItem` |  | `PowerBlocMapTexture` |  |
| `AccessSelf` |  |  |  |
| `GetItems` |  |  |  |
| `GetSelectedItem` |  |  |  |
| `OnNextClicked` |  | `void` |  |
| `OnPreviousClicked` |  | `void` |  |
| `Self` |  |  |  |

## PowerBlocPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetMapModeList` |  | `MapModeList` |  |
| `GetMembersSearchBar` |  | `SearchBar` |  |
| `GetPrincipleSlot` | `Arg0` | `PowerBlocPrincipleSlot` |  |
| `GetSelectedPowerBloc` |  | `PowerBloc` |  |
| `AccessSelf` |  |  |  |
| `GetMembersSearchBar` |  |  |  |
| `GetNumInvitableCountries` |  | `int32` |  |
| `GetPrincipleSlot` | `Arg0` |  |  |
| `GetSelectedPowerBloc` |  |  |  |
| `IsPowerBlocSelected` |  | `bool` |  |
| `OnClickInviteCountries` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleFormationSelectionWindow` | `Arg0` | `void` |  |
| `ToggleSelectionWindow` | `Arg0` | `void` |  |

## PowerBlocPrinciple

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGroup` |  | `PowerBlocPrincipleGroup` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBackground` |  |  |  |
| `GetBuildingTypesDesc` |  | `CString` |  |
| `GetCompanyTypesDesc` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetGroup` |  |  |  |
| `GetIcon` |  |  |  |
| `GetIncompatibilitiesDesc` |  | `CString` |  |
| `GetInstitutionEffectDesc` |  | `CString` |  |
| `GetIsPossibleDesc` |  | `CString` |  |
| `GetIsPossibleTriggerDesc` |  | `CString` |  |
| `GetLeaderEffectDesc` |  | `CString` |  |
| `GetMemberEffectDesc` |  | `CString` |  |
| `GetMobilizationOptionsDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNonLeaderEffectDesc` |  | `CString` |  |
| `GetPowerBlocEffectDesc` |  | `CString` |  |
| `GetProductionMethodsDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsPossible` |  | `bool` |  |
| `Self` |  |  |  |
| `UpgradeToNextLevel` |  | `Command` |  |

## PowerBlocPrincipleData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCooldownDate` |  | `Date` |  |
| `GetSelectionDate` |  | `Date` |  |
| `AccessSelf` |  |  |  |
| `GetCooldownDate` |  |  |  |
| `GetSelectionDate` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PowerBlocPrincipleGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetLevels` |  |  |  |
| `GetLevelsDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsPrimaryFor` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## PowerBlocPrincipleSelectionWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPowerBloc` |  | `PowerBloc` |  |
| `GetPowerBlocFormation` |  | `PowerBlocFormation` |  |
| `GetReplacedPrinciple` |  | `PowerBlocPrinciple` |  |
| `GetSelectedPrinciple` |  | `PowerBlocPrinciple` |  |
| `AccessSelf` |  |  |  |
| `CanAffordPrinciple` | `Arg0` | `bool` |  |
| `CanSelectPrinciple` | `Arg0` | `bool` |  |
| `GetAvailableGroups` |  |  |  |
| `GetDescForPrincipleSelection` | `Arg0` | `CString` |  |
| `GetMandateCostDescForSelectedPrinciple` |  | `CString` |  |
| `GetMandateCostForSelectedPrinciple` |  | `int32` |  |
| `GetNumMandates` |  | `int32` |  |
| `GetPotentialGroups` |  |  |  |
| `GetPowerBloc` |  |  |  |
| `GetPowerBlocFormation` |  |  |  |
| `GetReplacedPrinciple` |  |  |  |
| `GetSelectedPrinciple` |  |  |  |
| `HasPrinciple` | `Arg0` | `bool` |  |
| `HasPrincipleFromGroup` | `Arg0` | `bool` |  |
| `HasSelectedPrimaryPrinciple` |  | `bool` |  |
| `HasSelectedPrinciple` |  | `bool` |  |
| `IsPowerBlocFormation` |  | `bool` |  |
| `IsReplacedPrinciple` | `Arg0` | `bool` |  |
| `IsReplacingPrinciple` |  | `bool` |  |
| `IsSelectedPrinciple` | `Arg0` | `bool` |  |
| `IsUpgradingPrinciple` |  | `bool` |  |
| `Self` |  |  |  |
| `SubmitFormationPrincipleSelection` |  | `void` |  |
| `SubmitPrincipleSelection` |  | `Command` |  |
| `TogglePrincipleSelection` | `Arg0` | `void` |  |

## PowerBlocPrincipleSlot

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPrinciple` |  | `PowerBlocPrinciple` |  |
| `AccessSelf` |  |  |  |
| `GetPrinciple` |  |  |  |
| `GetUnlockDesc` |  | `CString` |  |
| `IsActive` |  | `bool` |  |
| `IsChangingPrinciple` |  | `bool` |  |
| `IsNext` |  | `bool` |  |
| `IsUnlocked` |  | `bool` |  |
| `OnAnimationFinished` |  | `void` |  |
| `Self` |  |  |  |

## PowerBlocStatue

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetEntity` | `Arg0` |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PowerBlocStatueAccessoryType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetEntity` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PowerBlocStatueAccessoryTypeSelector

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStatueAccessoryType` |  | `PowerBlocStatueAccessoryType` |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetStatueAccessoryTypeOptions` |  |  |  |
| `Self` |  |  |  |
| `SetNextStatueAccessoryType` |  | `void` |  |
| `SetPrevStatueAccessoryType` |  | `void` |  |
| `SetStatueAccessoryType` |  | `void` |  |

## PowerBlocStatueHeroType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetEntity` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PowerBlocStatuePedestalType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetEntity` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## PrestigeGoodChangeNamePopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPrestigeGood` |  | `Goods` |  |
| `AccessSelf` |  |  |  |
| `Confirm` |  | `Command` |  |
| `GetPrestigeGood` |  |  |  |
| `OnEditName` |  | `void` |  |
| `Self` |  |  |  |

## PreviewMaskTexture

Map Editor - Preview Mask

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetOpacity` |  | `float` |  |
| `Self` |  |  |  |
| `SetOpacity` |  | `void` |  |
| `SetOpacityStr` |  | `void` |  |

## ProductionMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `AccessTopItems` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## ProductionMethod

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBuildingTypesUsingThisDesc` | `Arg0` | `CString` |  |
| `GetCompactEmploymentSummaryDesc` |  | `CString` |  |
| `GetCompactGoodsSummaryDesc` |  | `CString` |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumOfBuildingsUsingThis` | `Arg0` | `int32` |  |
| `GetSwitch` | `Arg0` | `Command` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `GetTooltipForBuilding` | `Arg0, Arg1` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTooltipWithoutRequirements` | `Arg0, Arg1` | `CString` |  |
| `IsHiddenWhenUnavailable` |  | `bool` |  |
| `Self` |  |  |  |

## ProductionMethodConfirmationPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanExempt` |  | `bool` |  |
| `Cancel` |  | `void` |  |
| `Continue` |  | `void` |  |
| `Exempt` |  | `void` |  |
| `GetExemptedBuildingCount` |  | `int32` |  |
| `GetLowProductivityBreakdown` |  | `CString` |  |
| `GetTotalBuildingCount` |  | `int32` |  |
| `Self` |  |  |  |

## ProductionMethodGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuildingProductionMethods` | `Arg0` |  |  |
| `AccessCountryProductionMethods` | `Arg0` |  |  |
| `AccessSelf` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetMixedIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumAvailableOptions` | `Arg0` | `int32` |  |
| `GetNumAvailableOptionsForBuildingType` | `Arg0` | `int32` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## ProgressInterface

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetProgress` |  | `CString` |  |
| `Self` |  |  |  |

## PropertyListCategory

A category in a property list

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMargin` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `IsEmpty` |  | `bool` |  |
| `IsExpanded` |  | `bool` |  |
| `IsRoot` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleExpanded` |  | `void` |  |
| `ToggleTreeExpanded` |  | `void` |  |

## Proposal

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessTimeoutTimer` |  | `PieTimer` |  |
| `GetActor` |  | `Country` |  |
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `GetDiplomaticDemand` |  | `DiplomaticDemand` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetRecipient` |  | `Country` |  |
| `GetTarget` |  | `Country` |  |
| `GetTreaty` |  | `Treaty` |  |
| `AccessSelf` |  |  |  |
| `AccessTimeoutTimer` |  |  |  |
| `GetActor` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetDiplomaticAction` |  |  |  |
| `GetDiplomaticDemand` |  |  |  |
| `GetDiplomaticPlay` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetRecipient` |  |  |  |
| `GetTarget` |  |  |  |
| `GetTexture` |  |  |  |
| `GetToolTip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTreaty` |  |  |  |
| `IsHidden` |  | `bool` |  |
| `MarkAsHidden` |  | `void` |  |
| `Self` |  |  |  |
| `Unhide` |  | `void` |  |

## Province

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessStateRegion` |  | `StateRegion` |  |
| `GetController` |  | `Country` |  |
| `GetState` |  | `State` |  |
| `GetStateRegion` |  | `StateRegion` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `AccessStateRegion` |  |  |  |
| `AddSeaRegionToSelectedFleetMissions` |  | `Command` |  |
| `AssignSelectedFleetsToNewMissionInRegion` | `Arg0` | `Command` |  |
| `GetArea` |  | `int32` |  |
| `GetBestTexture` |  |  |  |
| `GetController` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDeploySelectedFormationsCommand` |  | `Command` |  |
| `GetID` |  | `CString` |  |
| `GetIndex` |  | `int32` |  |
| `GetScreenPosition` |  | `CVector2f` |  |
| `GetSeaNodeName` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetStateRegion` |  |  |  |
| `GetTerrainCombatWidth` |  | `CFixedPoint` |  |
| `GetTerrainName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsCoastal` |  | `bool` |  |
| `Self` |  |  |  |
| `WouldAddSeaRegionToSelectedFleetMissions` |  | `bool` |  |
| `WouldAssignSelectedFleetsToNewMission` | `Arg0` | `bool` |  |
| `WouldAssignSelectedFleetsToNewMissionWithConfirmation` | `Arg0` | `bool` |  |
| `WouldAssignSelectedFleetsToNewMissionWithoutConfirmation` | `Arg0` | `bool` |  |
