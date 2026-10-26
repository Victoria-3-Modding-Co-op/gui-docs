# Data-binding types: F

Back to the [index](README.md).

## FeedMessageItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPlayerMessageItem` |  | `PlayerMessageItem` |  |
| `GetTimeoutTimer` |  | `PieTimer` |  |
| `AccessSelf` |  |  |  |
| `ClickedExpand` |  | `bool` |  |
| `ClickedExpandFinished` |  | `void` |  |
| `ClickedHide` |  | `bool` |  |
| `ClickedHideFinished` |  | `void` |  |
| `Delete` |  | `void` |  |
| `EndAnimation` |  | `void` |  |
| `Expand` |  | `void` |  |
| `GetPlayerMessageItem` |  |  |  |
| `GetTimeoutTimer` |  |  |  |
| `IsExpanded` |  | `bool` |  |
| `IsSetToDelete` |  | `bool` |  |
| `IsToggled` |  | `bool` |  |
| `MarkToDelete` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldHide` |  | `bool` |  |
| `ShouldShow` |  | `bool` |  |
| `StartAnimation` |  | `void` |  |

## FilterablePropertyList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearSearchText` |  | `void` |  |
| `Filter` |  | `void` |  |
| `GetPropertiesLabel` |  | `CString` |  |
| `GetSearchText` |  | `CString` |  |
| `Search` |  | `void` |  |
| `Self` |  |  |  |

## FleetFormationMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstMilitaryFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `CalcAverageOrganizationPercentage` |  | `CFixedPoint` |  |
| `CalcTotalNumCombatUnits` |  | `int32` |  |
| `GetArmorAverage` |  | `CFixedPoint` |  |
| `GetCombatUnitsTypeIcon` |  | `CString` |  |
| `GetCrewDamageAverage` |  | `CFixedPoint` |  |
| `GetDamageAverage` |  | `CFixedPoint` |  |
| `GetFormations` |  |  |  |
| `GetHitPointsPercentage` |  | `CFixedPoint` |  |
| `GetHullDamageAverage` |  | `CFixedPoint` |  |
| `GetNumShips` |  | `int32` |  |
| `GetOrganizationTooltip` |  | `CString` |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetPositionDesc` |  | `CString` |  |
| `GetSummaryTooltip` |  | `CString` |  |
| `HasMultipleFormations` |  | `bool` |  |
| `IsAnyFormationHighlighted` |  | `bool` |  |
| `IsAnyFormationTraveling` |  | `bool` |  |
| `IsEnemies` |  | `bool` |  |
| `OnCtrlClick` |  | `void` |  |
| `OnLeftClick` |  | `void` |  |
| `OnRightClick` |  | `void` |  |
| `OnShiftClick` |  | `void` |  |
| `Self` |  |  |  |

## float

Number stored with `float` precision.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## FoodSecurity

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetNumPopsTotal` |  | `int64` |  |
| `GetNumStarvingPops` |  | `int64` |  |
| `GetNumStarvingPopsMild` |  | `int64` |  |
| `GetNumStarvingPopsSevere` |  | `int64` |  |
| `GetNumStatesWithFamineFormatted` |  | `CString` |  |
| `GetNumStatesWithFamineRaw` |  | `int32` |  |
| `GetPercentageStarvingPops` |  | `CFixedPoint` |  |
| `GetPercentageStarvingPopsMild` |  | `CFixedPoint` |  |
| `GetPercentageStarvingPopsSevere` |  | `CFixedPoint` |  |
| `GetStarvationTypePopulation` | `Arg0` | `int64` |  |
| `GetStarvationTypePopulationAsFloat` | `Arg0` | `float` |  |
| `GetStarvationTypePopulationAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `HasFamine` |  | `bool` |  |
| `Self` |  |  |  |

## FoodSecurityFilter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFoodSecurity` |  | `FoodSecurity` |  |
| `GetFoodSecurityCountryOrMarket` |  | `FoodSecurity` |  |
| `GetMarket` |  | `Market` |  |
| `GetSelectedCountry` |  | `Country` |  |
| `GetSelectedState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetStates` |  |  |  |
| `HasSpecificCountry` |  | `bool` |  |
| `HasSpecificState` |  | `bool` |  |
| `IsCountrySelected` | `Arg0` | `bool` |  |
| `IsStateSelected` | `Arg0` | `bool` |  |
| `ResetCountryFilter` |  | `void` |  |
| `ResetStateFilter` |  | `void` |  |
| `Self` |  |  |  |
| `SetCountryFilter` | `Arg0` | `void` |  |
| `SetStateFilter` | `Arg0` | `void` |  |

## FormationMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstMilitaryFormation` |  | `MilitaryFormation` |  |
| `AccessSelf` |  |  |  |
| `CalcAverageAvailableDefense` |  | `CFixedPoint` |  |
| `CalcAverageAvailableOffense` |  | `CFixedPoint` |  |
| `CalcAverageMorale` |  | `CFixedPoint` |  |
| `CalcAverageOrganizationPercentage` |  | `CFixedPoint` |  |
| `CalcCurrentManpower` |  | `int64` |  |
| `CalcMaxManpower` |  | `int64` |  |
| `CalcTotalNumCombatUnits` |  | `int32` |  |
| `GetCombatUnitsTypeIcon` |  | `CString` |  |
| `GetDefenseTooltip` |  | `CString` |  |
| `GetFormations` |  |  |  |
| `GetManpowerTooltip` |  | `CString` |  |
| `GetMoraleTooltip` |  | `CString` |  |
| `GetOffenseTooltip` |  | `CString` |  |
| `GetOrganizationTooltip` |  | `CString` |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetPositionDesc` |  | `CString` |  |
| `GetSummaryTooltip` |  | `CString` |  |
| `HasMultipleFormations` |  | `bool` |  |
| `IsAnyFormationHighlighted` |  | `bool` |  |
| `IsAnyFormationTraveling` |  | `bool` |  |
| `IsEnemies` |  | `bool` |  |
| `OnCtrlClick` |  | `void` |  |
| `OnLeftClick` |  | `void` |  |
| `OnRightClick` |  | `void` |  |
| `OnShiftClick` |  | `void` |  |
| `Self` |  |  |  |

## FormationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFormation` |  | `MilitaryFormation` |  |
| `AccessCommanderOrdersPossibleForSelectedFormations` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetFormation` |  |  |  |
| `GetSelectedFormations` |  |  |  |
| `HasSelectionView` |  | `bool` |  |
| `IsUnitGroupExpanded` | `Arg0` | `bool` |  |
| `SelectFormation` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `ToggleUnitGroupExpanded` | `Arg0` | `void` |  |

## Friend

Jomini Friend List - Friend

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAvailabilityString` |  | `CUTF8String` |  |
| `GetName` |  | `CUTF8String` |  |
| `GetNameWithColor` |  | `CUTF8String` |  |
| `GetUnreadMessageCount` |  | `int32` |  |
| `HasUnreadMessages` |  | `bool` |  |
| `RemoveWithConfirmation` |  | `void` |  |
| `Self` |  |  |  |
| `StartChat` |  | `void` |  |

## FriendListWindow

Jomini Friend List - Friendlist window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldBeShown` |  | `bool` |  |
| `Show` |  | `void` |  |
| `ShowAddFriendWindow` |  | `void` |  |

## FriendRequest

Jomini Friend List - FriendRequest

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `Accept` |  | `void` |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CUTF8String` |  |
| `Reject` |  | `void` |  |
| `Self` |  |  |  |

## Friends

Jomini Friend List - Friends manager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAvailabilityEntries` |  |  |  |
| `AccessFriendRequests` |  |  |  |
| `AccessFriendSearchResults` |  |  |  |
| `AccessFriends` |  |  |  |
| `AccessOutgoingFriendRequests` |  |  |  |
| `AccessSelf` |  |  |  |
| `CalcNumberOfOnlineFriends` |  | `int32` |  |
| `GetAvailabilityStringForLocalAccount` |  | `CUTF8String` |  |
| `GetLocalProfileName` |  | `CUTF8String` |  |
| `GetSearchString` |  | `CUTF8String` |  |
| `GetSelectedAvailabilityEntryIndex` |  | `CVector2i` |  |
| `HasIngoingFriendRequests` |  | `bool` |  |
| `HasOutgoingFriendRequests` |  | `bool` |  |
| `Search` |  | `void` |  |
| `Self` |  |  |  |
| `SetSearchString` |  | `void` |  |
| `SetSelectedAvailabilityEntryIndex` |  | `void` |  |
| `UpdateFriends` |  | `void` |  |

## FriendSearchResult

Jomini Friends - Search Result

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddFriend` |  | `void` |  |
| `GetName` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## Front

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetInitiatorSide` |  | `FrontSide` |  |
| `GetLeftSide` |  | `FrontSide` |  |
| `GetPlayerEnemySide` |  | `FrontSide` |  |
| `GetPlayerSide` |  | `FrontSide` |  |
| `GetRightSide` |  | `FrontSide` |  |
| `GetTargetSide` |  | `FrontSide` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessActiveBattles` |  |  |  |
| `AccessAllBattles` |  |  |  |
| `AccessDiplomaticPlay` |  |  |  |
| `AccessEndedBattles` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetAdvantageFrame` |  | `int32` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDeploySelectedFormationsCommand` |  | `Command` |  |
| `GetDesc` |  | `CString` |  |
| `GetID` |  | `uint32` |  |
| `GetInitiatorTheatersDebugDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameFromPerspective` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetOccupationProgressDesc` |  | `CString` |  |
| `GetPlayerAdvantageDesc` |  | `CString` |  |
| `GetPlayerAdvantageRaw` |  | `int32` |  |
| `GetPlayerSideAlliesCombatUnitsBreakdown` |  | `CString` |  |
| `GetPlayerSideAlliesCombatUnitsTravelingBreakdown` |  | `CString` |  |
| `GetPlayerSideCombatUnitsBreakdown` |  | `CString` |  |
| `GetPlayerSideCombatUnitsTravelingBreakdown` |  | `CString` |  |
| `GetPlayerSideNumUnitsAtFront` |  | `int32` |  |
| `GetPlayerSideNumUnitsTraveling` |  | `int32` |  |
| `GetPlayerSideUnitsTooltip` |  | `CString` |  |
| `GetRequiredAdvanceProgressForBattle` |  | `CFixedPoint` |  |
| `GetTargetTheatersDebugDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasCountry` | `Arg0` | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsVulnerable` | `Arg0` | `bool` | Returns true if the specified DataCountry or its allies do not have any troops on or heading to the front, but enemies do. |
| `IsZoomingToFront` |  | `bool` |  |
| `Self` |  |  |  |
| `ZoomToFront` |  | `void` |  |

## FrontEndCreditsView

Jomini Frontend Credits View

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `OnBack` |  | `void` |  |
| `Self` |  |  |  |

## FrontEndLoadConfirmationWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AnswerNo` |  | `void` |  |
| `AnswerYes` |  | `void` |  |
| `GetDesc` |  | `CString` |  |
| `Self` |  |  |  |

## FrontEndLoadView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetContinueSave` |  | `SaveGameItem` |  |
| `GetSelectedSavegame` |  | `SaveGameItem` |  |
| `AccessSelf` |  |  |  |
| `CanDoContinue` |  | `bool` |  |
| `GetContinueSave` |  |  |  |
| `GetSaveGames` |  |  |  |
| `GetSelectedSavegame` |  |  |  |
| `HasSelectedSavegame` |  | `bool` |  |
| `IsEmpty` |  | `bool` |  |
| `OnBack` |  | `void` |  |
| `OnConfirmContinue` | `Arg0` | `void` |  |
| `OnContinue` |  | `void` |  |
| `OnDelete` |  | `void` |  |
| `OnDeleteAll` |  | `void` |  |
| `OnIncompatibleLoadConfirm` |  | `void` |  |
| `OnIncompatibleLoadDeny` |  | `void` |  |
| `OnLoad` |  | `void` |  |
| `OnShowInvalidSavegames` |  | `void` |  |
| `PreContinueSaveCheck` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldShowInvalidSavegames` |  | `bool` |  |

## FrontEndMainView

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessLoadView` |  | `FrontEndLoadView` |  |
| `AccessLoadView` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetMainMenuImage` |  | `CString` |  |
| `OnCredits` |  | `void` |  |
| `OnHost` |  | `void` |  |
| `OnLoad` |  | `void` |  |
| `OnLogin` |  | `void` |  |
| `OnMultiPlayer` |  | `void` |  |
| `OnNewGame` |  | `void` |  |
| `OnQuit` |  | `void` |  |
| `OnSettings` |  | `void` |  |
| `Self` |  |  |  |

## FrontEndMultiplayerView

Jomini Multiplayer - Frontendview

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `OnBack` |  | `void` |  |
| `OnHost` |  | `void` |  |
| `OnLoad` |  | `void` |  |
| `OnNewGame` |  | `void` |  |
| `Self` |  |  |  |

## FrontMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFront` |  | `Front` |  |
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `OnClick` |  | `void` |  |
| `Self` |  |  |  |

## FrontMovementMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFront` |  | `Front` |  |
| `GetFront` |  | `Front` |  |
| `AccessFront` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanDeploySelectedFormationsToFront` |  | `bool` |  |
| `GetFront` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetPresentFormationsBreakdown` |  | `CString` |  |
| `GetSelectedFormationsInvolvementChangeDesc` |  | `CString` |  |
| `GetTravelTimeBreakdown` |  | `CString` |  |
| `IsAllSelectedFormationsLocation` |  | `bool` |  |
| `IsAllSelectedFormationsTarget` |  | `bool` |  |
| `IsAnySelectedFormationsLocation` |  | `bool` |  |
| `IsAnySelectedFormationsTarget` |  | `bool` |  |
| `RequiresNavalTransportForSelectedFormations` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowTransportPlannerForSelectedFormation` |  | `void` |  |

## FrontPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFront` |  | `Front` |  |
| `GetFront` |  | `Front` |  |
| `AccessFront` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetFront` |  |  |  |
| `IsShowingBattles` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleShowPastBattles` |  | `void` |  |

## FrontSide

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetFront` |  | `Front` |  |
| `AccessSelf` |  |  |  |
| `GetAdvancement` |  | `CFixedPoint` |  |
| `GetAdvancementProgress` |  | `CFixedPoint` |  |
| `GetAdvantage` |  | `int32` |  |
| `GetAdvantageDesc` |  | `CString` |  |
| `GetAdvantageFrame` |  | `int32` |  |
| `GetArmies` |  |  |  |
| `GetCountries` |  |  |  |
| `GetCountry` |  |  |  |
| `GetNumCasualties` | `Arg0` | `int64` |  |
| `GetNumDead` | `Arg0` | `int64` |  |
| `GetNumUnits` |  | `int32` |  |
| `GetNumUnitsBreakdown` |  | `CString` |  |
| `GetNumWounded` | `Arg0` | `int64` |  |
| `GetOutsideTopFiveArmies` |  |  |  |
| `GetOutsideTopFiveArmiesTooltip` |  | `CString` |  |
| `GetTopFiveArmies` |  |  |  |
| `GetTotalNumCasualties` |  | `int64` |  |
| `GetTotalNumDead` |  | `int64` |  |
| `GetTotalNumWounded` |  | `int64` |  |
| `GetUnitDefense` |  | `CFixedPoint` |  |
| `GetUnitMorale` |  | `CFixedPoint` |  |
| `GetUnitMoraleDesc` |  | `CString` |  |
| `GetUnitOffense` |  | `CFixedPoint` |  |
| `HasCountry` | `Arg0` | `bool` |  |
| `IsInitiatorSide` |  | `bool` |  |
| `IsTargetSide` |  | `bool` |  |
| `Self` |  |  |  |
