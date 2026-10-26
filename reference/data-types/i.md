# Data-binding types: I

Back to the [index](README.md).

## Ideology

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `EndorsesLaw` | `Arg0` | `bool` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEndorsedLawsInLawGroup` | `Arg0` |  |  |
| `GetLawGroups` |  |  |  |
| `GetLawStanceDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNeutralLawsInLawGroup` | `Arg0` |  |  |
| `GetOpposedLawsInLawGroup` | `Arg0` |  |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsCharacterIdeology` |  | `bool` |  |
| `OpposesLaw` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## Importable

Map Editor - Importable items within a ImportableGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |
| `SetSelected` | `Arg0` | `void` |  |

## ImportableGroup

Map Editor - Importable Group

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AreAllSelected` |  | `bool` |  |
| `GetImportableCount` |  | `int32` |  |
| `GetImportables` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `HasDiffTool` |  | `bool` |  |
| `IsCollapsed` |  | `bool` |  |
| `IsSelectedIndeterminable` |  | `bool` |  |
| `LaunchDiffTool` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleAllSelected` |  | `void` |  |
| `ToggleCollapsed` |  | `void` |  |

## ImportantAlert

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAlert` |  | `Alert` |  |
| `AccessSelf` |  |  |  |
| `GetAlert` |  |  |  |
| `GetAlertGroup` |  |  |  |
| `GetAlerts` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNumAlerts` |  | `int32` |  |
| `GetTexture` |  |  |  |
| `GetToolTip` |  | `CString` |  |
| `HasGroup` |  | `bool` |  |
| `IsAlertGroupExpanded` |  | `bool` |  |
| `IsRead` |  | `bool` |  |
| `MarkAsHidden` |  | `void` |  |
| `MarkAsRead` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleAlertGroupExpanded` |  | `void` |  |

## ImportTool

Map Editor - Import Tool Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AreAllSelected` |  | `bool` |  |
| `Cancel` |  | `void` |  |
| `GetExportMaskTexture` |  |  |  |
| `GetExportNotes` |  | `CString` |  |
| `GetHeightmapTexture` |  |  |  |
| `GetMaskEffect` |  |  |  |
| `HasExportNotes` |  | `bool` |  |
| `Import` |  | `void` |  |
| `IsImporting` |  | `bool` |  |
| `IsSelectedIndeterminable` |  | `bool` |  |
| `IsZipLoaded` |  | `bool` |  |
| `RefreshHeightmap` |  | `void` |  |
| `Self` |  |  |  |
| `SetMaskAsReferenceOverlay` |  | `void` |  |
| `ToggleAllSelected` |  | `void` |  |

## InfoboxNodeWindow

Node Editor - Infobox Node Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTitleScale` |  | `float` |  |
| `Self` |  |  |  |

## InformationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsTabSelected` | `Arg0` | `bool` |  |
| `SelectTab` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## InformationPanelBar

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClosePanel` |  | `void` |  |
| `IsAnyPanelOpen` |  | `bool` |  |
| `IsAvailable` |  | `bool` |  |
| `IsPanelOpen` | `Arg0` | `bool` |  |
| `IsPanelTabOpen` | `Arg0, Arg1` | `bool` |  |
| `OpenAddWarGoalPanel` | `Arg0, Arg1` | `void` |  |
| `OpenBattlePanel` | `Arg0` | `void` |  |
| `OpenBattlePanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenBuildingBrowserPanel` | `Arg0` | `void` |  |
| `OpenBuildingBrowserPanelForType` | `Arg0, Arg1` | `void` |  |
| `OpenBuildingDetailsPanel` | `Arg0` | `void` |  |
| `OpenBuildingDetailsPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenChangeLaw` | `Arg0` | `void` |  |
| `OpenCharacterPanel` | `Arg0` | `void` |  |
| `OpenCompactBuildingBrowserPanel` | `Arg0` | `void` |  |
| `OpenCompactBuildingBrowserPanelCycleFilters` | `Arg0, Arg1` | `void` |  |
| `OpenCompanyPanel` | `Arg0` | `void` |  |
| `OpenConstructionCampPanel` | `Arg0` | `void` |  |
| `OpenConstructionCampPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenConstructionPanel` | `Arg0` | `void` |  |
| `OpenConstructionPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenCountryFormationPanel` | `Arg0` | `void` |  |
| `OpenCountryPanel` | `Arg0` | `void` |  |
| `OpenCountryPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenCultureInfoPanel` | `Arg0` | `void` |  |
| `OpenDiplomaticPlayPanel` | `Arg0` | `void` |  |
| `OpenDiplomaticPlayPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenElectionPanel` | `Arg0` | `void` |  |
| `OpenFrontPanel` | `Arg0` | `void` |  |
| `OpenGoodsLocalPricesPanel` | `Arg0` | `void` |  |
| `OpenGoodsPanel` | `Arg0, Arg1` | `void` |  |
| `OpenGoodsStatePanel` | `Arg0, Arg1` | `void` |  |
| `OpenGoodsUsagePanel` | `Arg0` | `void` |  |
| `OpenGoodsWorldMarketPanel` | `Arg0` | `void` |  |
| `OpenInterestGroupPanel` | `Arg0` | `void` |  |
| `OpenInvasionPanel` | `Arg0` | `void` |  |
| `OpenInvasionPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenJournalEntryPanel` | `Arg0` | `void` |  |
| `OpenJournalEntryPanelDontToggle` | `Arg0` | `void` |  |
| `OpenMarketPanel` | `Arg0` | `void` |  |
| `OpenMarketPanelCycleTabs` | `Arg0, Arg1, Arg2` | `void` |  |
| `OpenMarketPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenMilitaryFormationPanel` | `Arg0` | `void` |  |
| `OpenMilitaryFormationPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenMilitaryFormationPanelTabForDoubleClick` | `Arg0, Arg1` | `void` |  |
| `OpenMilitaryPanelTab` | `Arg0` | `void` |  |
| `OpenNavalBattlePanel` | `Arg0` | `void` |  |
| `OpenNavalBattlePanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenPanel` | `Arg0` | `void` |  |
| `OpenPanelCycleTabs` | `Arg0, Arg1` | `void` |  |
| `OpenPanelDontToggle` | `Arg0` | `void` |  |
| `OpenPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenPanelTabDontToggle` | `Arg0, Arg1` | `void` |  |
| `OpenPartyPanel` | `Arg0` | `void` |  |
| `OpenPoliticalLobbyPanel` | `Arg0` | `void` |  |
| `OpenPoliticalMovementPanel` | `Arg0` | `void` |  |
| `OpenPopBrowserPanel` | `Arg0` | `void` |  |
| `OpenPopDetailsPanel` | `Arg0` | `void` |  |
| `OpenPowerBlocFormationPanel` |  | `void` |  |
| `OpenPowerBlocPanel` | `Arg0` | `void` |  |
| `OpenPowerBlocPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenPreviousPanel` |  | `void` |  |
| `OpenReligionInfoPanel` | `Arg0` | `void` |  |
| `OpenSeaRegionPanel` | `Arg0` | `void` |  |
| `OpenSeaRegionPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenShipPanel` | `Arg0` | `void` |  |
| `OpenShipPanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenStatePanel` | `Arg0` | `void` |  |
| `OpenStatePanelTab` | `Arg0, Arg1` | `void` |  |
| `OpenStatePopulationPanel` | `Arg0` | `void` |  |
| `OpenStraitPanel` | `Arg0` | `void` |  |
| `OpenStrategicRegionPanel` | `Arg0` | `void` |  |
| `OpenSwayCountryPanel` | `Arg0, Arg1` | `void` |  |
| `OpenTechnologyPanel` | `Arg0` | `void` |  |
| `OpenTreatyDraftPanel` | `Arg0` | `void` |  |
| `OpenTreatyDraftPanelForNewDraft` | `Arg0, Arg1` | `void` |  |
| `OpenTreatyPanel` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `ToggleLocationFinder` |  | `void` |  |
| `ToggleTop` |  | `void` |  |

## IngameHud

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## InputActionBinding

Input Context Manager - Input Action

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## InspectorPanel

Map Editor - Spline Network Tool - Anchor Inspector Panel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAnchorItems` |  |  |  |
| `GetSearchFilter` |  | `CString` |  |
| `Self` |  |  |  |
| `SetSearchFilter` |  | `void` |  |

## Institution

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessModifier` |  | `Modifier` |  |
| `GetCountry` |  | `Country` |  |
| `GetModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessInvestmentLevels` |  |  |  |
| `AccessModifier` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanChangeLevelTo` | `Arg0` | `bool` |  |
| `GetBackground` |  |  |  |
| `GetChangeLevelDesc` | `Arg0` | `CString` |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetGrowDesc` |  | `CString` |  |
| `GetGrowthProgress` |  | `CFixedPoint` |  |
| `GetIcon` |  |  |  |
| `GetInvestmentCost` |  | `CFixedPoint` |  |
| `GetInvestmentLevel` |  | `int32` |  |
| `GetMaxLevel` |  | `int32` |  |
| `GetModifier` |  |  |  |
| `GetModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetProvidingLawsDesc` |  | `CString` |  |
| `GetShrinkDesc` |  | `CString` |  |
| `GetShrinkProgress` |  | `CFixedPoint` |  |
| `GetTargetInvestmentLevel` |  | `int32` |  |
| `GetTimeToReachTargetLevelDesc` |  | `CString` |  |
| `GetTimedModifiersDesc` |  | `CString` |  |
| `GetTooltipModifierDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsChangingLevel` |  | `bool` |  |
| `IsGrowing` |  | `bool` |  |
| `IsShrinking` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `StartChangingLevelTo` | `Arg0` | `Command` |  |
| `StartGrowing` |  | `Command` |  |
| `StartShrinking` |  | `Command` |  |
| `StopSizeChange` |  | `Command` |  |

## InstitutionInvestmentLevel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetLevel` |  | `int32` |  |
| `IsActive` |  | `bool` |  |
| `IsDecreasing` |  | `bool` |  |
| `IsDecreasingToThisLevel` |  | `bool` |  |
| `IsIncreasing` |  | `bool` |  |
| `IsIncreasingToThisLevel` |  | `bool` |  |
| `IsTargetLevel` |  | `bool` |  |
| `Self` |  |  |  |

## InstitutionType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBackground` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## int16

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt` |  |  |  |
| `Self` |  |  |  |

## int32

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt` |  |  |  |
| `Self` |  |  |  |

## int64

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt` |  |  |  |
| `Self` |  |  |  |

## int8

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetInt` |  |  |  |
| `Self` |  |  |  |

## Interest

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetOwner` |  | `Country` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetIconTooltip` |  | `CString` |  |
| `GetInterestSourceDesc` |  | `CString` |  |
| `GetInterestStatusIcon` |  | `CString` |  |
| `GetInterestStatusName` |  | `CString` |  |
| `GetOwner` |  |  |  |
| `GetStrategicRegion` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsActive` |  | `bool` |  |
| `Self` |  |  |  |

## InterestGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `AccessLeader` |  | `Character` |  |
| `AccessModifier` |  | `Modifier` |  |
| `GetCountry` |  | `Country` |  |
| `GetLeader` |  | `Character` |  |
| `GetLeaderIdeology` |  | `Ideology` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetParty` |  | `Party` |  |
| `GetPartyAffiliationHighest` |  | `Party` |  |
| `GetPopWithIG` | `Arg0` | `PopWithIG` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessAllIdeologies` |  |  |  |
| `AccessCheapestLawsToPass` |  |  |  |
| `AccessCountry` |  |  |  |
| `AccessIntrinsicIdeologies` |  |  |  |
| `AccessLeader` |  |  |  |
| `AccessModifier` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTraits` |  |  |  |
| `CalcApprovalFromLoyalties` |  | `int32` |  |
| `CalcApprovalFromLoyaltiesDesc` |  | `CString` |  |
| `GetAffiliationBreakdown` |  | `CString` |  |
| `GetAffiliationBreakdownForParty` | `Arg0` | `CString` |  |
| `GetAffiliationRaw` |  | `CFixedPoint` |  |
| `GetAgitators` |  |  |  |
| `GetAmenability` |  | `CFixedPoint` |  |
| `GetAmenabilityLabel` |  | `CString` |  |
| `GetApprovalRating` |  | `CString` |  |
| `GetApprovalValue` |  | `int32` |  |
| `GetApprovalValueDecayIfEnactedDesc` | `Arg0` | `CString` |  |
| `GetApprovalValueDeltaFromEnactment` | `Arg0` | `int32` |  |
| `GetApprovalValueDesc` |  | `CString` |  |
| `GetApprovalValueIfEnacted` | `Arg0` | `int32` |  |
| `GetClout` |  | `CFixedPoint` |  |
| `GetCloutAsFloat` |  | `float` |  |
| `GetCloutSupportingMovement` | `Arg0` | `CFixedPoint` |  |
| `GetCloutTrend` |  | `DataTrend` |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCountry` |  |  |  |
| `GetCountrySupport` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetFractionOfCloutSupportingMovement` | `Arg0` | `CFixedPoint` |  |
| `GetGraphicalLoyalistsRatioInAllInterestGroups` |  | `float` |  |
| `GetGraphicalRadicalsRatioInAllInterestGroups` |  | `float` |  |
| `GetID` |  | `uint32` |  |
| `GetIdeologyDesc` |  | `CString` |  |
| `GetInfluenceDesc` |  | `CString` |  |
| `GetInfluenceReason` |  | `CString` |  |
| `GetInfluencingMovements` |  |  |  |
| `GetLawApprovalBreakdown` | `Arg0` | `CString` |  |
| `GetLawApprovalValue` | `Arg0` | `int32` |  |
| `GetLawStanceLabel` | `Arg0` | `CString` |  |
| `GetLeader` |  |  |  |
| `GetLeaderIdeology` |  |  |  |
| `GetLeaderIdeologyDesc` |  | `CString` |  |
| `GetLoyalistsPoliticalStrength` |  | `int64` |  |
| `GetLoyalistsTrend` |  | `DataTrend` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNameWithCountryVariant` |  | `CString` |  |
| `GetNumLoyalists` |  | `int64` |  |
| `GetNumLoyalistsRatio` |  | `float` |  |
| `GetNumNeutrals` |  | `int64` |  |
| `GetNumNeutralsRatio` |  | `float` |  |
| `GetNumPossibleLeaderIdeologies` |  | `int32` |  |
| `GetNumRadicals` |  | `int64` |  |
| `GetNumRadicalsRatio` |  | `float` |  |
| `GetNumSupportersForMovement` | `Arg0` | `int64` |  |
| `GetParty` |  |  |  |
| `GetPartyAffiliationHighest` |  |  |  |
| `GetPartyAffiliationTooltip` |  | `CString` |  |
| `GetPoliticalLobbies` |  |  |  |
| `GetPoliticalStrength` |  | `int64` |  |
| `GetPoliticalStrengthDesc` |  | `CString` |  |
| `GetPoliticalStrengthInState` | `Arg0` | `int64` |  |
| `GetPoliticalStrengthInStateAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetPoliticallyActivePercentage` |  | `CFixedPoint` |  |
| `GetPoliticallyActiveRaw` |  | `int64` |  |
| `GetPopPotentialDesc` |  | `CString` |  |
| `GetPopWithIG` | `Arg0` |  |  |
| `GetPopulation` |  | `int64` |  |
| `GetPopulationAsFloat` |  | `float` |  |
| `GetPopulationInCountryAsPercentage` |  | `CFixedPoint` |  |
| `GetPopulationInState` | `Arg0` | `int64` |  |
| `GetPopulationNonZero` |  | `int64` |  |
| `GetPossibleLeaderIdeologies` |  |  |  |
| `GetRadicalsPoliticalStrength` |  | `int64` |  |
| `GetRadicalsTrend` |  | `DataTrend` |  |
| `GetStatusTooltip` |  | `CString` |  |
| `GetSupportingPopTypesDesc` |  | `CString` |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalPoliticalStrengthIncludingPartyVotes` |  | `int64` |  |
| `GetTraitsDesc` |  | `CString` |  |
| `GetWillJoinPartyDesc` |  | `CString` |  |
| `GetWillJoinPartyTooltip` |  | `CString` |  |
| `HasNegotiated` |  | `bool` |  |
| `HasParty` |  | `bool` |  |
| `IsEndorsingLawEnactment` | `Arg0` | `bool` |  |
| `IsInGovernment` |  | `bool` |  |
| `IsIndifferentToLawEnactment` | `Arg0` | `bool` |  |
| `IsInfluencedByMovement` | `Arg0` | `bool` |  |
| `IsInsurrectionary` |  | `bool` |  |
| `IsLeaderInfluencingEnactment` | `Arg0` | `bool` |  |
| `IsLeadingGovernment` |  | `bool` |  |
| `IsMarginal` |  | `bool` |  |
| `IsNegotiating` |  | `bool` |  |
| `IsOpposingLawEnactment` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsPowerful` |  | `bool` |  |
| `IsRevolutionary` |  | `bool` |  |
| `IsSecessionist` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `PredictLegitimacyChangeDesc` |  | `CString` |  |
| `PredictLegitimacyChangeToSwitch` |  | `CFixedPoint` |  |
| `Self` |  |  |  |
| `TogglePinInOutliner` |  | `void` |  |
| `WillRadicalizeIfEnacted` | `Arg0` | `bool` |  |

## InterestGroupAndTraitPair

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `GetTrait` |  | `InterestGroupTrait` |  |
| `AccessInterestGroup` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetInterestGroup` |  |  |  |
| `GetTrait` |  |  |  |
| `Self` |  |  |  |

## InterestGroupMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `AccessInterestGroup` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetInterestGroup` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## InterestGroupPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `AccessPopsList` |  | `PopList` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `AccessInterestGroup` |  |  |  |
| `AccessPops` |  |  |  |
| `AccessPopsList` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetInterestGroup` |  |  |  |
| `Self` |  |  |  |

## InterestGroupTrait

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBaseModifiersDesc` |  | `CString` |  |
| `GetBaseTriggersDesc` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetInactiveString` | `Arg0` | `CString` |  |
| `GetModifiersDesc` | `Arg0` | `CString` |  |
| `GetName` | `Arg0` | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameWithStatus` | `Arg0` | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTriggersDesc` | `Arg0` | `CString` |  |
| `IsEnabled` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## InterestingCountryItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetSetting` |  | `InterestingCountrySetting` |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetSetting` |  |  |  |
| `OnSelectOption` |  | `void` |  |
| `Self` |  |  |  |

## InterestingCountrySetting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIsActiveDesc` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## InterestTierType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStateModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetLeverageGenerationMultDesc` |  | `CString` |  |
| `GetLowerBound` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetOnActivateEffectDesc` | `Arg0, Arg1` | `CString` |  |
| `GetOnDeactivateEffectDesc` | `Arg0, Arg1` | `CString` |  |
| `GetProgress` | `Arg0` | `float` |  |
| `GetRank` |  | `int32` |  |
| `GetSmallIcon` |  |  |  |
| `GetSmallTextIcon` |  | `CString` |  |
| `GetStateModifier` |  |  |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTradeAdvantageDesc` |  | `CString` |  |
| `GetUpperBound` |  | `CFixedPoint` |  |
| `GetWidth` |  | `int32` |  |
| `IsActive` | `Arg0, Arg1` | `bool` |  |
| `Self` |  |  |  |

## Invasion

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDefenderHQ` |  | `Hq` |  |
| `GetEnemyState` |  | `State` |  |
| `GetFleet` |  | `MilitaryFormation` |  |
| `GetFront` |  | `Front` |  |
| `GetInvadedCountry` |  | `Country` |  |
| `GetInvaderCountry` |  | `Country` |  |
| `GetSeaNode` |  | `Province` |  |
| `GetSourceState` |  | `State` |  |
| `GetTargetState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanFormationBlockLanding` | `Arg0` | `bool` |  |
| `Cancel` |  | `Command` |  |
| `DeployArmyToDefend` | `Arg0` | `Command` |  |
| `DeployFleetToDefend` | `Arg0` | `Command` |  |
| `GetActiveLandBattles` |  |  |  |
| `GetActiveNavalBattles` |  |  |  |
| `GetAdvancementProgress` |  | `CFixedPoint` |  |
| `GetArmies` |  |  |  |
| `GetBlockingFleets` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDefenderHQ` |  |  |  |
| `GetDefendingArmies` |  |  |  |
| `GetDefendingArmiesTooltipBreakdown` |  | `CString` |  |
| `GetDefendingFleets` |  |  |  |
| `GetDefendingFleetsTooltipBreakdown` |  | `CString` |  |
| `GetDeploySelectedFormationsCommand` |  | `Command` |  |
| `GetEndedLandBattles` |  |  |  |
| `GetEndedNavalBattles` |  |  |  |
| `GetEnemyState` |  |  |  |
| `GetFleet` |  |  |  |
| `GetFront` |  |  |  |
| `GetInvadedCountry` |  |  |  |
| `GetInvaderCountry` |  |  |  |
| `GetInvadingArmies` |  |  |  |
| `GetInvadingArmiesTooltipBreakdown` |  | `CString` |  |
| `GetInvadingFleets` |  |  |  |
| `GetInvadingFleetsTooltipBreakdown` |  | `CString` |  |
| `GetLandingProgress` |  | `CFixedPoint` |  |
| `GetMaxLandBattleDefeatsAtZeroOccupation` |  | `int32` |  |
| `GetName` |  | `CString` |  |
| `GetNeededPowerProjection` |  | `CFixedPoint` |  |
| `GetNeededPowerProjectionDesc` |  | `CString` |  |
| `GetNonBlockingFleets` |  |  |  |
| `GetNumBlockingFleets` |  | `int32` |  |
| `GetNumBlockingFleetsUnits` |  | `int32` |  |
| `GetNumDefendingArmies` |  | `int32` |  |
| `GetNumDefendingArmiesUnits` |  | `int32` |  |
| `GetNumDefendingFleets` |  | `int32` |  |
| `GetNumDefendingFleetsUnits` |  | `int32` |  |
| `GetNumInvadingArmies` |  | `int32` |  |
| `GetNumInvadingArmiesUnits` |  | `int32` |  |
| `GetNumInvadingFleets` |  | `int32` |  |
| `GetNumInvadingFleetsUnits` |  | `int32` |  |
| `GetNumLandBattleDefeatsAtZeroOccupation` |  | `int32` |  |
| `GetNumNonBlockingFleets` |  | `int32` |  |
| `GetNumNonBlockingFleetsUnits` |  | `int32` |  |
| `GetParticipatingFormationsBreakdown` |  | `CString` |  |
| `GetPreparationDaysLeftRaw` |  | `int32` |  |
| `GetProgress` |  | `CFixedPoint` |  |
| `GetSeaNode` |  |  |  |
| `GetSeaNodeName` |  | `CString` |  |
| `GetSourceState` |  |  |  |
| `GetStatus` |  | `CString` |  |
| `GetTargetState` |  |  |  |
| `GetTargetStateFortificationBreakdown` |  | `CString` |  |
| `GetTargetStateFortificationUnitDefense` |  | `CFixedPoint` |  |
| `GetTargetStateUnitDefenseBreakdown` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalPowerProjection` |  | `CFixedPoint` |  |
| `GetTotalPowerProjectionBreakdown` |  | `CString` |  |
| `HasBlockingEnemyFleetOnSeaNode` |  | `bool` |  |
| `HasEnded` |  | `bool` |  |
| `HasFailed` |  | `bool` |  |
| `HasSucceeded` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsFightingLandBattle` |  | `bool` |  |
| `IsFightingNavalBattle` |  | `bool` |  |
| `IsLandInvasion` |  | `bool` |  |
| `IsNavalInvasion` |  | `bool` |  |
| `IsOnInvaderSide` | `Arg0` | `bool` |  |
| `IsPreparing` |  | `bool` |  |
| `IsRelevantForCountry` | `Arg0` | `bool` |  |
| `IsStalledDueToCommanderOrders` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsWaiting` |  | `bool` |  |
| `IsZoomingToMapMarkerPosition` |  | `bool` |  |
| `Self` |  |  |  |
| `ZoomToMapMarkerPosition` |  | `void` |  |

## InvasionMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetInvasion` |  | `Invasion` |  |
| `AccessSelf` |  |  |  |
| `CanDeploySelectedFormationsToDefend` |  | `bool` |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## InvasionPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetInvasion` |  | `Invasion` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## InvasionPlannerPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSlowestArmy` |  | `MilitaryFormation` |  |
| `GetSlowestFleet` |  | `MilitaryFormation` |  |
| `GetSourceState` |  | `State` |  |
| `GetTargetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `CanAddMoreArmies` |  | `bool` |  |
| `CanLandInvade` |  | `bool` |  |
| `CanMilitaryFormationBeSelected` | `Arg0` | `bool` |  |
| `CanNavalInvade` |  | `bool` |  |
| `GetArmyDaysDesc` |  | `CString` |  |
| `GetArmySplitWarning` |  | `CString` |  |
| `GetAssignedPowerProjectionDesc` |  | `CString` |  |
| `GetCanMilitaryFormationBeSelectedTooltip` | `Arg0` | `CString` |  |
| `GetCommandValidityDesc` |  | `CString` |  |
| `GetEfficiencyRaw` |  | `CFixedPoint` |  |
| `GetFleetDaysDesc` |  | `CString` |  |
| `GetFleetInvasionCommand` | `Arg0` | `Command` |  |
| `GetNeededPowerProjectionDesc` |  | `CString` |  |
| `GetSelectedAdmirals` |  |  |  |
| `GetSelectedArmies` |  |  |  |
| `GetSelectedFleets` |  |  |  |
| `GetSelectedGenerals` |  |  |  |
| `GetSlowestArmy` |  |  |  |
| `GetSlowestFleet` |  |  |  |
| `GetSortedFleets` |  |  |  |
| `GetSourceState` |  |  |  |
| `GetTargetState` |  |  |  |
| `GetTargetStateFortificationBreakdown` |  | `CString` |  |
| `GetTargetStateFortificationNavalDefense` |  | `CFixedPoint` |  |
| `GetTargetStateFortificationUnitDefense` |  | `CFixedPoint` |  |
| `GetTargetStateUnitDefenseBreakdown` |  | `CString` |  |
| `GetTargetStateUnitDefenseDesc` |  | `CString` |  |
| `GetTravelDaysDesc` |  | `CString` |  |
| `GetTravelTimeDesc` |  | `CString` |  |
| `HasAdvancingGeneral` |  | `bool` |  |
| `HasNavalInvasionContext` |  | `bool` |  |
| `HasSelectedNecessaryFormations` |  | `bool` |  |
| `IsFormationAutoIncluded` | `Arg0` | `bool` |  |
| `IsMilitaryFormationSelected` | `Arg0` | `bool` |  |
| `OnSelectedArmy` | `Arg0` | `void` |  |
| `OnSelectedFleet` | `Arg0` | `void` |  |
| `RemoveFormation` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `StartInvasion` |  | `Command` |  |
