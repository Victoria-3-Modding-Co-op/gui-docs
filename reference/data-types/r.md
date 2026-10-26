# Data-binding types: R

Back to the [index](README.md).

## RandomizableValueFloat

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValue` |  | `float` |  |
| `Randomize` |  | `void` |  |
| `Self` |  |  |  |
| `SetValue` |  | `void` |  |

## RandomizableValueInt

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetValue` |  | `int32` |  |
| `Randomize` |  | `void` |  |
| `Self` |  |  |  |
| `SetValue` |  | `void` |  |

## ReformGovernment

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetLegitimacyLevel` |  | `LegitimacyLevel` |  |
| `GetPredictedLegitimacyLevel` |  | `LegitimacyLevel` |  |
| `GetPredictedNewRuler` | `Arg0` | `Character` |  |
| `AccessSelf` |  |  |  |
| `Confirm` |  | `Command` |  |
| `GetAllPotentialInterestGroups` |  |  |  |
| `GetAllPotentialParties` |  |  |  |
| `GetAllStagedInterestGroups` |  |  |  |
| `GetAllStagedParties` |  |  |  |
| `GetConfirmDesc` |  | `CString` |  |
| `GetCountry` |  |  |  |
| `GetIndependentPotentialInterestGroups` |  |  |  |
| `GetIndependentStagedInterestGroups` |  |  |  |
| `GetLegitimacy` |  | `int32` |  |
| `GetLegitimacyDesc` |  | `CString` |  |
| `GetLegitimacyLevel` |  |  |  |
| `GetOptionIndexText` | `Arg0` | `CString` |  |
| `GetOptionIndexTooltip` | `Arg0` | `CString` |  |
| `GetPredictedLawsWithGovernmentOrMovementSupport` |  |  |  |
| `GetPredictedLawsWithGovernmentOrMovementSupportHeader` |  | `CString` |  |
| `GetPredictedLawsWithoutGovernmentOrMovementSupport` |  |  |  |
| `GetPredictedLawsWithoutGovernmentOrMovementSupportHeader` |  | `CString` |  |
| `GetPredictedLegitimacy` |  | `int32` |  |
| `GetPredictedLegitimacyDelta` |  | `int32` |  |
| `GetPredictedLegitimacyDesc` |  | `CString` |  |
| `GetPredictedLegitimacyLevel` |  |  |  |
| `GetPredictedLoyalistsDelta` |  | `int64` |  |
| `GetPredictedNewRuler` | `Arg0` |  |  |
| `GetPredictedRadicalsDelta` |  | `int64` |  |
| `HasMadeAnyChanges` |  | `bool` |  |
| `HasPredictedLawsWithGovernmentOrMovementSupportChanged` |  | `bool` |  |
| `HasPredictedLawsWithoutGovernmentOrMovementSupportChanged` |  | `bool` |  |
| `HasStagedGroup` |  | `bool` |  |
| `OptionIndexIsActiveGovernment` | `Arg0` | `bool` |  |
| `OptionIndexIsSelected` | `Arg0` | `bool` |  |
| `OptionIndexIsValid` | `Arg0` | `bool` |  |
| `Reset` |  | `void` |  |
| `SelectOptionIndex` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `StageInterestGroup` | `Arg0` | `void` |  |
| `StageParty` | `Arg0` | `void` |  |
| `UnstageInterestGroup` | `Arg0` | `void` |  |
| `UnstageParty` | `Arg0` | `void` |  |
| `WouldGetNewRuler` |  | `bool` |  |

## ReleaseCountryWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountryCreation` |  | `CountryCreation` |  |
| `GetCountryCreation` |  | `CountryCreation` |  |
| `AccessCountryCreation` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanMakeIndependent` |  | `bool` |  |
| `CanMakeOwnSubject` |  | `bool` |  |
| `CanPlayAsReleased` |  | `bool` |  |
| `CanReleaseWithKeepHomelandStates` |  | `bool` |  |
| `GetCountryCreation` |  |  |  |
| `GetKeepHomelandStatesTooltip` |  | `CString` |  |
| `GetMakeIndependentTooltip` |  | `CString` |  |
| `GetMakeOwnSubjectTooltip` |  | `CString` |  |
| `GetPlayAsReleasedTooltip` |  | `CString` |  |
| `GetPopupQuestion` |  | `CString` |  |
| `ReleaseCountry` |  | `Command` |  |
| `Self` |  |  |  |
| `SubjectTypeToMakeOwnSubjectExists` |  | `bool` |  |
| `ToggleKeepHomelandStates` |  | `void` |  |
| `ToggleMakeIndependent` |  | `void` |  |
| `ToggleMakeOwnSubject` |  | `void` |  |
| `TogglePlayAsReleased` |  | `void` |  |
| `WillKeepHomelandStates` |  | `bool` |  |
| `WillMakeIndependent` |  | `bool` |  |
| `WillMakeOwnSubject` |  | `bool` |  |
| `WillPlayAsReleased` |  | `bool` |  |

## Religion

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetAcceptanceDescIn` | `Arg0` | `CString` |  |
| `GetAcceptanceIn` | `Arg0` | `int32` |  |
| `GetAcceptanceStatusSegmentsIn` | `Arg0` |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDependents` | `Arg0` | `int64` |  |
| `GetDependentsAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetPolStr` | `Arg0` | `int64` |  |
| `GetPolStrAsFloat` | `Arg0` | `float` |  |
| `GetPolStrAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetPopulation` | `Arg0` | `int64` |  |
| `GetPopulationAsFloat` | `Arg0` | `float` |  |
| `GetPopulationAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetPopulationChange` | `Arg0` | `int64` |  |
| `GetPopulationChangeDesc` | `Arg0` | `CString` |  |
| `GetReligiousTraitsDesc` |  | `CString` |  |
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
| `GetTaboosDesc` |  | `CString` |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetWorkforce` | `Arg0` | `int64` |  |
| `GetWorkforceAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## ReligionInfoPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPopsList` |  | `PopList` |  |
| `AccessReligion` |  | `Religion` |  |
| `GetReligion` |  | `Religion` |  |
| `AccessPops` |  |  |  |
| `AccessPopsList` |  |  |  |
| `AccessReligion` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetReligion` |  |  |  |
| `IsShowingNationalOnly` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleShowNationalOnly` |  | `void` |  |

## RemoveFriendConfirmWindow

Jomini Friend List - Remove friend confirm window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ConfirmRemove` |  | `void` |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldBeShown` |  | `bool` |  |
| `Show` |  | `void` |  |

## RepackWindow

Map Editor - Repack Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCurrentTileSize` |  | `int32` |  |
| `Repack` |  | `void` |  |
| `Self` |  |  |  |
| `SetTileSize` | `Arg0` | `void` |  |
| `ShouldWrapX` |  | `bool` |  |
| `Toggle` |  | `void` |  |
| `ToggleShouldWrapX` |  | `void` |  |

## ResignConfirmationWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Cancel` |  | `void` |  |
| `GetText` |  | `CString` |  |
| `IsProgress` |  | `bool` |  |
| `IsShowSave` |  | `bool` |  |
| `OnDesktop` |  | `void` |  |
| `OnMenu` |  | `void` |  |
| `Self` |  |  |  |
| `SetShowSave` | `Arg0` | `void` |  |
| `ShouldSave` |  | `bool` |  |
| `ToggleShouldSave` |  | `void` |  |

## RevolutionaryMovementMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPoliticalMovement` |  | `PoliticalMovement` |  |
| `AccessSelf` |  |  |  |
| `GetPoliticalMovement` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## RightClickMenuManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `IsImportantActionsListOpen` |  | `bool` |  |
| `IsMenuOpen` | `Arg0` | `bool` |  |
| `IsResearchQueueOpen` |  | `bool` |  |
| `IsSwitchProductionMethodMenuOpen` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowForAssignCommander` | `Arg0, Arg1` | `void` |  |
| `ShowForBuilding` | `Arg0` | `void` |  |
| `ShowForBuildingType` | `Arg0` | `void` |  |
| `ShowForCharacter` | `Arg0` | `void` |  |
| `ShowForCountry` | `Arg0` | `void` |  |
| `ShowForDecree` | `Arg0` | `void` |  |
| `ShowForDiplomaticPlay` | `Arg0` | `void` |  |
| `ShowForEmbarkSelectFleet` | `Arg0` | `void` |  |
| `ShowForGoods` | `Arg0` | `void` |  |
| `ShowForIG` | `Arg0` | `void` |  |
| `ShowForImposeLaw` | `Arg0` | `void` |  |
| `ShowForMarket` | `Arg0` | `void` |  |
| `ShowForMilitaryFormation` | `Arg0` | `void` |  |
| `ShowForPoliticalMovement` | `Arg0` | `void` |  |
| `ShowForPowerBloc` | `Arg0` | `void` |  |
| `ShowForSelectArmy` |  | `void` |  |
| `ShowForSelectFleet` |  | `void` |  |
| `ShowForSetDefaultCombatUnitType` | `Arg0, Arg1` | `void` |  |
| `ShowForState` | `Arg0` | `void` |  |
| `ShowForTransportSelectArmy` | `Arg0` | `void` |  |
| `ShowForTransportSelectFleet` |  | `void` |  |
| `ToggleAddArmyToInvasion` | `Arg0, Arg1` | `void` |  |
| `ToggleAddFleetToInvasion` | `Arg0, Arg1` | `void` |  |
| `ToggleArmyAdditionalActions` | `Arg0, Arg1` | `void` |  |
| `ToggleArticleDraftInput` | `Arg0, Arg1, Arg2, Arg3, Arg4` | `void` |  |
| `ToggleArticleTypeInput` | `Arg0, Arg1, Arg2, Arg3, Arg4` | `void` |  |
| `ToggleBlocActions` | `Arg0, Arg1` | `void` |  |
| `ToggleBlocLeaderActions` | `Arg0, Arg1` | `void` |  |
| `ToggleBuildShipTypeOfGroup` | `Arg0, Arg1, Arg2, Arg3` | `void` |  |
| `ToggleBuildShipTypeOfGroupForFleet` | `Arg0, Arg1, Arg2, Arg3` | `void` |  |
| `ToggleBuildingActions` | `Arg0, Arg1` | `void` |  |
| `ToggleBulkChangeTemplateActions` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleColorPicker` | `Arg0, Arg1` | `void` |  |
| `ToggleCompanyCharterType` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleCountryRetrofitActions` | `Arg0, Arg1` | `void` |  |
| `ToggleCustomizationOptionItems` | `Arg0, Arg1` | `void` |  |
| `ToggleEnemyFleetsOnMissionInSeaRegion` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleFilterUnitStates` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleFleetAdditionalActions` | `Arg0, Arg1` | `void` |  |
| `ToggleFleetRetrofitActions` | `Arg0, Arg1` | `void` |  |
| `ToggleFleetsOnMissionInSeaRegion` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleForSelectOrder` | `Arg0, Arg1` | `void` |  |
| `ToggleImportantActionsList` | `Arg0, Arg1` | `void` |  |
| `ToggleMapModes` | `Arg0, Arg1` | `void` |  |
| `ToggleMarketStarvationCountriesFilter` | `Arg0, Arg1` | `void` |  |
| `ToggleMarketStarvationStatesFilter` | `Arg0, Arg1` | `void` |  |
| `ToggleMilitaryFormation` | `Arg0, Arg1` | `void` |  |
| `ToggleNationalizePrivatelyOwnedFilter` | `Arg0, Arg1` | `void` |  |
| `ToggleNegotiationIGSelect` | `Arg0, Arg1, Arg2, Arg3` | `void` |  |
| `ToggleOverlordActions` | `Arg0, Arg1` | `void` |  |
| `TogglePowerBlocCoaPieces` | `Arg0, Arg1` | `void` |  |
| `TogglePowerBlocMapTextureItems` | `Arg0, Arg1` | `void` |  |
| `TogglePrivatizeOrMonopolize` | `Arg0, Arg1` | `void` |  |
| `ToggleResearchQueue` | `Arg0` | `void` |  |
| `ToggleSelectNavalMissionType` | `Arg0` | `void` |  |
| `ToggleSelectNavalMissionTypeForFleet` | `Arg0, Arg1` | `void` |  |
| `ToggleShipChangeTemplateActions` | `Arg0, Arg1` | `void` |  |
| `ToggleShipConstructionFleets` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleShipDesignerSelectShipTypeMenu` | `Arg0, Arg1` | `void` |  |
| `ToggleShipDesignerSkinsMenu` | `Arg0, Arg1` | `void` |  |
| `ToggleShipDesignerTemplateMenu` | `Arg0, Arg1` | `void` |  |
| `ToggleShipDesignerUtilityMenu` | `Arg0, Arg1` | `void` |  |
| `ToggleSubjectActions` | `Arg0, Arg1` | `void` |  |
| `ToggleSwayOfferArticleTypeInput` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleSwitchProductionMethodMenu` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleSwitchProductionMethodMenuForType` | `Arg0, Arg1, Arg2` | `void` |  |
| `ToggleTreatyDraftBindPeriodMenu` | `Arg0, Arg1` | `void` |  |
| `ToggleTreatyDraftReset` | `Arg0, Arg1` | `void` |  |
| `ToggleWarGoalArticleTypeInput` | `Arg0, Arg1, Arg2` | `void` |  |

## RulerSelectionPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessRulersOffer` |  |  |  |
| `AccessSelf` |  |  |  |
| `RandomizeRulersOffer` |  | `Command` |  |
| `Self` |  |  |  |
| `SetRulerCommand` | `Arg0` | `Command` |  |
