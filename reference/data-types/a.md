# Data-binding types: A

Back to the [index](README.md).

## AcceptanceStatus

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetHigherStatus` |  | `AcceptanceStatus` |  |
| `GetLowerStatus` |  | `AcceptanceStatus` |  |
| `AccessSelf` |  |  |  |
| `GetBackground` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectsDescIn` | `Arg0` | `CString` |  |
| `GetHigherStatus` |  |  |  |
| `GetLargeIcon` |  |  |  |
| `GetLowerBound` |  | `int32` |  |
| `GetLowerStatus` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetOrdinal` |  | `int32` |  |
| `GetSmallIcon` |  |  |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUpperBound` |  | `int32` |  |
| `HasHigherStatus` |  | `bool` |  |
| `HasLowerStatus` |  | `bool` |  |
| `Self` |  |  |  |

## AcceptanceStatusSegment

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetStatus` |  | `AcceptanceStatus` |  |
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetPopulationDesc` |  | `CString` |  |
| `GetStatus` |  |  |  |
| `GetTotalPopulation` |  | `int64` |  |
| `GetTotalPopulationIncreasingInAcceptance` |  | `int64` |  |
| `Self` |  |  |  |

## AccountInventory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `HasItem` | `Arg0` | `bool` |  |
| `HasRetrievedInventory` |  | `bool` |  |
| `Self` |  |  |  |

## Achievement

Jomini Achievement

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsUnlocked` |  | `bool` |  |
| `Self` |  |  |  |

## AchievementPopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessJustUnlockedAchievements` |  |  |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
| `ShowWindow` |  | `void` |  |

## AchievementWindow

Jomini Achievement Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessGroups` |  |  |  |
| `AccessSelf` |  |  |  |
| `HasGameStarted` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldShowAll` |  | `bool` |  |
| `ShouldShowLocked` |  | `bool` |  |
| `ShouldShowPossible` |  | `bool` |  |
| `ShouldShowUnlocked` |  | `bool` |  |
| `Show` |  | `void` |  |
| `ShowAll` |  | `void` |  |
| `ShowLocked` |  | `void` |  |
| `ShowPossible` |  | `void` |  |
| `ShowUnlocked` |  | `void` |  |

## AddFriendWindow

Jomini Friends - Add Friends Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldBeShown` |  | `bool` |  |
| `Show` |  | `void` |  |

## AddWarGoalPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `AccessDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetCountry` |  | `Country` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `AccessCountry` |  |  |  |
| `AccessDiplomaticPlay` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessShownWarGoalTypes` |  |  |  |
| `AccessShownWarGoals` |  |  |  |
| `ClearSelectedWarGoalType` |  | `void` |  |
| `GetCountry` |  |  |  |
| `GetDiplomaticPlay` |  |  |  |
| `HasSelectedWarGoalType` |  | `bool` |  |
| `Self` |  |  |  |
| `SetSelectedWarGoalType` | `Arg0` | `void` |  |

## AgitatorSlot

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAgitator` |  | `Character` |  |
| `AccessSelf` |  |  |  |
| `EnableInvite` |  | `void` |  |
| `GetAgitator` |  |  |  |
| `Self` |  |  |  |

## AIAttitude

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstCountry` |  | `Country` |  |
| `GetSecondCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `CalcScore` |  | `CFixedPoint` |  |
| `GetColor` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetFirstCountry` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetReasonsDesc` |  | `CString` |  |
| `GetSecondCountry` |  |  |  |
| `GetStrategicDesireCatalystDesc` |  | `CString` |  |
| `GetStrategicDesireDesc` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## AIStrategicRegionStanceType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## AIStrategy

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## Alert

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddingFinished` |  | `void` |  |
| `BeginIdleAnimation` |  | `void` |  |
| `GetAction` |  | `CString` |  |
| `GetAlertGroup` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetDescription` |  | `CString` |  |
| `GetHint` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetScopeTexture` |  |  |  |
| `GetTexture` |  |  |  |
| `GetToolTip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasScopeTexture` |  | `bool` |  |
| `IdleAnimationFinished` |  | `void` |  |
| `IsAdded` |  | `bool` |  |
| `IsAdding` |  | `bool` |  |
| `IsAngryImportantAction` |  | `bool` |  |
| `IsHidden` |  | `bool` |  |
| `IsRead` |  | `bool` |  |
| `IsRemovalRequested` |  | `bool` |  |
| `MarkAsHidden` |  | `void` |  |
| `MarkAsRead` |  | `void` |  |
| `RemovingFinished` |  | `void` |  |
| `Self` |  |  |  |
| `StartRemoving` |  | `void` |  |
| `Unhide` |  | `void` |  |

## AlertGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## AlertOptionItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameWithConcept` |  | `CString` |  |
| `IsDefault` |  | `bool` |  |
| `Self` |  |  |  |

## AlertSettingsItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCurrentOption` |  | `AlertOptionItem` |  |
| `AccessSelf` |  |  |  |
| `GetCurrentOption` |  |  |  |
| `GetSettingName` |  | `CString` |  |
| `GetValidOptions` |  |  |  |
| `OnSelectOption` |  | `void` |  |
| `Self` |  |  |  |

## Amendment

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAttachedLaw` |  | `Law` |  |
| `GetParentLawType` |  | `LawType` |  |
| `GetSponsor` |  | `InterestGroup` |  |
| `GetType` |  | `AmendmentType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetAttachedLaw` |  |  |  |
| `GetCooldownEndDate` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetEndorsingInterestGroups` |  |  |  |
| `GetEndorsingInterestGroupsBreakdown` |  | `CString` |  |
| `GetEndorsingInterestGroupsSummary` |  | `CString` |  |
| `GetIndifferentInterestGroups` |  |  |  |
| `GetIndifferentInterestGroupsBreakdown` |  | `CString` |  |
| `GetIndifferentInterestGroupsSummary` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumEndorsingInterestGroups` |  | `int32` |  |
| `GetNumIndifferentInterestGroups` |  | `int32` |  |
| `GetNumOpposingInterestGroups` |  | `int32` |  |
| `GetOnAmendedEffectsDesc` |  | `CString` |  |
| `GetOnRepealEffectsDesc` |  | `CString` |  |
| `GetOpposingInterestGroups` |  |  |  |
| `GetOpposingInterestGroupsBreakdown` |  | `CString` |  |
| `GetOpposingInterestGroupsSummary` |  | `CString` |  |
| `GetParentLawType` |  |  |  |
| `GetSponsor` |  |  |  |
| `GetTimeoutDate` |  | `CString` |  |
| `GetTimeoutMonths` |  | `int32` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `HasCooldown` |  | `bool` |  |
| `HasCooledDown` |  | `bool` |  |
| `HasTimedOut` |  | `bool` |  |
| `HasTimeout` |  | `bool` |  |
| `IsActive` |  | `bool` |  |
| `Repeal` |  | `Command` |  |
| `Self` |  |  |  |

## AmendmentType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifier` |  | `Modifier` |  |
| `GetParentLawType` |  | `LawType` |  |
| `GetSponsorModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetInstitutionModifierDesc` |  | `CString` |  |
| `GetIsPossibleDesc` | `Arg0, Arg1` | `CString` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameWithLaw` | `Arg0` | `CString` |  |
| `GetOnAmendedEffectsDesc` | `Arg0` | `CString` |  |
| `GetOnRepealEffectsDesc` | `Arg0` | `CString` |  |
| `GetParentLawType` |  |  |  |
| `GetSponsorModifier` |  |  |  |
| `GetTaxModifierDesc` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUnlocks` |  | `CString` |  |
| `HasParentLaw` |  | `bool` |  |
| `IsPossible` | `Arg0, Arg1` | `bool` |  |
| `Self` |  |  |  |

## AnchorItem

Map Editor - Spline Network Tool - Anchor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAnchorIndexAsString` |  | `CString` |  |
| `GetDisplayString` |  | `CString` |  |
| `GetIndexValidator` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `IsExpanded` |  | `bool` |  |
| `IsLocked` |  | `bool` |  |
| `Self` |  |  |  |
| `SetAnchorIndexCallback` |  | `void` |  |
| `ToggleExpanded` |  | `void` |  |
| `ToggleLock` |  | `void` |  |

## Application

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Quit` |  | `void` |  |
| `Self` |  |  |  |

## Article

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArticleType` |  | `ArticleType` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `GetCompany` |  | `Company` |  |
| `GetCountry` |  | `Country` |  |
| `GetFirstOrSourceCountry` |  | `Country` |  |
| `GetGoods` |  | `Goods` |  |
| `GetLaw` |  | `LawType` |  |
| `GetMaintenancePayer` |  | `Country` |  |
| `GetSecondOrTargetCountry` |  | `Country` |  |
| `GetShip` |  | `Ship` |  |
| `GetShippingLane` |  | `ShippingLane` |  |
| `GetSourceCountry` |  | `Country` |  |
| `GetState` |  | `State` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `GetTargetCountry` |  | `Country` |  |
| `GetTreaty` |  | `Treaty` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanWithdraw` | `Arg0` | `bool` |  |
| `ExceedsMaxContraventions` | `Arg0` | `bool` |  |
| `GetAboutToBreakReasonDesc` |  | `CString` |  |
| `GetArticleNumber` |  | `int32` |  |
| `GetArticleType` |  |  |  |
| `GetAutoBreakReasonDesc` |  | `CString` |  |
| `GetBaseCost` |  | `CFixedPoint` |  |
| `GetBuildingType` |  |  |  |
| `GetCompany` |  |  |  |
| `GetCostFor` | `Arg0` | `CFixedPoint` |  |
| `GetCostForDesc` | `Arg0` | `CString` |  |
| `GetCostWithTooltipFor` | `Arg0` | `CString` |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetEffectsDesc` |  | `CString` |  |
| `GetFirstOrSourceCountry` |  |  |  |
| `GetGoods` |  |  |  |
| `GetIcon` |  |  |  |
| `GetImmediateEffectsDesc` |  | `CString` |  |
| `GetInvolvementEffectsDesc` |  | `CString` |  |
| `GetLaw` |  |  |  |
| `GetMaintenancePayer` |  |  |  |
| `GetMutualModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNonFulfillmentDesc` |  | `CString` |  |
| `GetNonFulfillmentDescFor` | `Arg0` | `CString` |  |
| `GetQuantity` |  | `CFixedPoint` |  |
| `GetRelationsEffectDesc` |  | `CString` |  |
| `GetSecondOrTargetCountry` |  |  |  |
| `GetShip` |  |  |  |
| `GetShippingLane` |  |  |  |
| `GetShortDesc` |  | `CString` |  |
| `GetSourceCountry` |  |  |  |
| `GetSourceModifierDesc` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetStrategicRegion` |  |  |  |
| `GetTargetCountry` |  |  |  |
| `GetTargetModifierDesc` |  | `CString` |  |
| `GetText` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTreaty` |  |  |  |
| `HasContraventions` | `Arg0` | `bool` |  |
| `HasFlag` | `Arg0` | `bool` |  |
| `HasKind` | `Arg0` | `bool` |  |
| `HasType` | `Arg0` | `bool` |  |
| `RequiresInput` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## ArticleDraft

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArticleType` |  | `ArticleType` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `GetCompany` |  | `Company` |  |
| `GetCountry` |  | `Country` |  |
| `GetFirstOrSource` |  | `Country` |  |
| `GetGoods` |  | `Goods` |  |
| `GetLawType` |  | `LawType` |  |
| `GetMaintenancePayer` |  | `Country` |  |
| `GetSecondOrTarget` |  | `Country` |  |
| `GetShip` |  | `Ship` |  |
| `GetShipTypeFilterList` |  | `TreatyShipFilterList` |  |
| `GetState` |  | `State` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `AccessSelf` |  |  |  |
| `CanAddWarGoal` | `Arg0, Arg1` | `bool` |  |
| `CanBeModified` |  | `bool` |  |
| `CanBeModifiedDesc` |  | `CString` |  |
| `FilterGoods` | `Arg0` | `void` |  |
| `GetAcceptance` | `Arg0` | `int32` |  |
| `GetAcceptanceBreakdown` | `Arg0` | `CString` |  |
| `GetArticleNumber` |  | `int32` |  |
| `GetArticleType` |  |  |  |
| `GetBaseCost` |  | `CFixedPoint` |  |
| `GetBuildingType` |  |  |  |
| `GetCompany` |  |  |  |
| `GetCostFor` | `Arg0` | `CFixedPoint` |  |
| `GetCostForDesc` | `Arg0` | `CString` |  |
| `GetCostWithTooltipFor` | `Arg0` | `CString` |  |
| `GetCountry` |  |  |  |
| `GetEffectsDesc` |  | `CString` |  |
| `GetFirstOrSource` |  |  |  |
| `GetGoods` |  |  |  |
| `GetIcon` |  |  |  |
| `GetImmediateEffectsDesc` |  | `CString` |  |
| `GetInvolvementEffectsDesc` |  | `CString` |  |
| `GetLawType` |  |  |  |
| `GetMaintenancePayer` |  |  |  |
| `GetMaxValidQuantity` |  | `int32` |  |
| `GetMinValidQuantity` |  | `int32` |  |
| `GetMutualModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNumInputs` |  | `int32` |  |
| `GetQuantity` |  | `CFixedPoint` |  |
| `GetQuantityPercentage` |  | `float` |  |
| `GetQuantityValidator` |  |  |  |
| `GetRelationsEffectDesc` |  | `CString` |  |
| `GetRequiredInputsDesc` |  | `CString` |  |
| `GetSecondOrTarget` |  |  |  |
| `GetShip` |  |  |  |
| `GetShortDesc` |  | `CString` |  |
| `GetSourceModifierDesc` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetStrategicRegion` |  |  |  |
| `GetTargetModifierDesc` |  | `CString` |  |
| `GetText` |  | `CString` |  |
| `GetValidBuildingTypes` |  |  |  |
| `GetValidCompanies` |  |  |  |
| `GetValidCountries` |  |  |  |
| `GetValidGoods` |  |  |  |
| `GetValidLaws` | `Arg0` |  |  |
| `GetValidShips` |  |  |  |
| `GetValidStates` |  |  |  |
| `GetValidStrategicRegions` |  |  |  |
| `GetWarGoalInfamyValue` | `Arg0` | `CFixedPoint` |  |
| `GetWarGoalInfamyValueDesc` | `Arg0` | `CString` |  |
| `GetWarGoalManeuversCost` | `Arg0, Arg1` | `int32` |  |
| `GetWarGoalManeuversCostDesc` | `Arg0, Arg1` | `CString` |  |
| `HasAllRequiredInputsSet` |  | `bool` |  |
| `HasFlag` | `Arg0` | `bool` |  |
| `HasInputValue` | `Arg0` | `bool` |  |
| `HasKind` | `Arg0` | `bool` |  |
| `HasType` | `Arg0` | `bool` |  |
| `IsLawTypeValidInput` | `Arg0` | `bool` |  |
| `IsPossible` |  | `bool` |  |
| `IsSelectedGoods` | `Arg0` | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `OnInputTextChanged` |  | `void` |  |
| `OnQuantityChanged` |  | `void` |  |
| `OnQuantityChangedSlider` |  | `void` |  |
| `OnTextChanged` |  | `void` |  |
| `RequiresAnyInput` |  | `bool` |  |
| `RequiresInput` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetBuildingType` | `Arg0` | `void` |  |
| `SetCompany` | `Arg0` | `void` |  |
| `SetCountry` | `Arg0` | `void` |  |
| `SetGood` | `Arg0` | `void` |  |
| `SetLaw` | `Arg0` | `void` |  |
| `SetQuantity` | `Arg0` | `void` |  |
| `SetShip` | `Arg0` | `void` |  |
| `SetState` | `Arg0` | `void` |  |
| `SetStrategicRegion` | `Arg0` | `void` |  |
| `SetText` | `Arg0` | `void` |  |
| `SortGoods` | `Arg0` | `void` |  |

## ArticleType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCost` |  | `CFixedPoint` |  |
| `GetCostFor` | `Arg0, Arg1, Arg2` | `CFixedPoint` |  |
| `GetCostForDesc` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetDailyRelationsProgress` |  | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectsDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetInvolvementEffectDesc` |  | `CString` |  |
| `GetIsAvailableDesc` | `Arg0, Arg1` | `CString` |  |
| `GetIsPossibleDesc` | `Arg0, Arg1` | `CString` |  |
| `GetIsVisibleDesc` | `Arg0, Arg1` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNumInputs` |  | `int32` |  |
| `GetRelationsEffectDesc` |  | `CString` |  |
| `GetRelationsImprovementMax` |  | `int32` |  |
| `GetRelationsImprovementMin` |  | `int32` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasFlag` | `Arg0` | `bool` |  |
| `HasKind` | `Arg0` | `bool` |  |
| `HasType` | `Arg0` | `bool` |  |
| `IsAvailable` | `Arg0, Arg1` | `bool` |  |
| `IsPossible` | `Arg0, Arg1` | `bool` |  |
| `IsVisible` | `Arg0, Arg1` | `bool` |  |
| `RequiresAnyInput` |  | `bool` |  |
| `Self` |  |  |  |

## Attribute

Portrait Editor - Attribute

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetValue` |  | `float` |  |
| `OnValueChanged` |  | `void` |  |
| `Self` |  |  |  |

## AvailabilityEntry

Jomini Friend List - Availibility Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAvailabilityString` |  | `CUTF8String` |  |
| `Self` |  |  |  |
