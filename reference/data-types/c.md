# Data-binding types: C

Back to the [index](README.md).

## CFixedPoint

Number stored with 6 digits of precision.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFixedPoint` |  |  |  |
| `Self` |  |  |  |

## ChangeLawPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetLawGroup` |  | `LawGroup` |  |
| `GetSelectedLaw` |  | `Law` |  |
| `AccessSelf` |  |  |  |
| `GetLawAlternatives` |  |  |  |
| `GetLawGroup` |  |  |  |
| `GetSelectedLaw` |  |  |  |
| `Self` |  |  |  |

## ChangeProductionMethodMenuItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMethod` |  | `ProductionMethod` |  |
| `GetProductionMethodGroup` |  | `ProductionMethodGroup` |  |
| `AccessMethod` |  |  |  |
| `AccessSelf` |  |  |  |
| `Execute` |  | `void` |  |
| `GetProductionMethodGroup` |  |  |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `IsActive` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `OnMenuItemHovered` |  | `void` |  |
| `Self` |  |  |  |

## ChangeProductionMethodsMenuItems

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessItems` |  |  |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## Character

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBattle` |  | `Battle` |  |
| `AccessCountry` |  | `Country` |  |
| `AccessCulture` |  | `Culture` |  |
| `AccessInterestGroup` |  | `InterestGroup` |  |
| `AccessReligion` |  | `Religion` |  |
| `GetAcceptanceStatus` |  | `AcceptanceStatus` |  |
| `GetAcceptanceStatusIn` | `Arg0` | `AcceptanceStatus` |  |
| `GetAssignedState` |  | `State` |  |
| `GetBattle` |  | `Battle` |  |
| `GetCommanderRank` |  | `CommanderRank` |  |
| `GetCompany` |  | `Company` |  |
| `GetCountry` |  | `Country` |  |
| `GetCulture` |  | `Culture` |  |
| `GetFront` |  | `Front` |  |
| `GetHolding` |  | `Building` |  |
| `GetHomeCountry` |  | `Country` |  |
| `GetHomeCountryDefinition` |  | `CountryDefinition` |  |
| `GetHomeRegion` |  | `StateRegion` |  |
| `GetHomeState` |  | `State` |  |
| `GetIdeology` |  | `Ideology` |  |
| `GetInteraction` | `Arg0` | `CharacterInteraction` |  |
| `GetInterestGroup` |  | `InterestGroup` |  |
| `GetInvasion` |  | `Invasion` |  |
| `GetMilitaryFormation` |  | `MilitaryFormation` |  |
| `GetNextCommanderRank` |  | `CommanderRank` |  |
| `GetNextOrderType` |  | `CommanderOrderType` |  |
| `GetOrderType` |  | `CommanderOrderType` |  |
| `GetPoliticalMovement` |  | `PoliticalMovement` |  |
| `GetPrimaryRole` |  | `CharacterRole` |  |
| `GetReligion` |  | `Religion` |  |
| `MakeScope` |  | `Scope` |  |
| `PredictMovementToJoin` | `Arg0` | `PoliticalMovement` |  |
| `PredictMovementTypeToStart` | `Arg0` | `PoliticalMovementType` |  |
| `AccessBattle` |  |  |  |
| `AccessCulture` |  |  |  |
| `AccessInterestGroup` |  |  |  |
| `AccessOrders` |  |  |  |
| `AccessPossibleSpecialOrders` |  |  |  |
| `AccessReligion` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTraits` |  |  |  |
| `AccessUnavailableOrders` |  |  |  |
| `AssignToFormation` | `Arg0` | `Command` |  |
| `GetAcceptanceStatus` |  |  |  |
| `GetAcceptanceStatusIn` | `Arg0` |  |  |
| `GetAcceptanceValue` |  | `int32` |  |
| `GetAcceptanceValueDesc` |  | `CString` |  |
| `GetAcceptanceValueDescIn` | `Arg0` | `CString` |  |
| `GetAcceptanceValueIn` | `Arg0` | `int32` |  |
| `GetAffectedNavalMissionTypes` |  |  |  |
| `GetAge` |  | `int32` |  |
| `GetAgitatorSpawnedNotificationText` |  | `CString` |  |
| `GetAllRoleNames` |  | `CString` |  |
| `GetAnimatedPortrait` | `Arg0, Arg1, Arg2, Arg3` |  |  |
| `GetAssignedState` |  |  |  |
| `GetBattle` |  |  |  |
| `GetBattles` |  |  |  |
| `GetBirthday` |  | `CString` |  |
| `GetCombatUnitsTypeIcon` |  | `CString` |  |
| `GetCommandLimit` |  | `CString` |  |
| `GetCommandLimitDesc` |  | `CString` |  |
| `GetCommandLimitRaw` |  | `int32` |  |
| `GetCommanderDetails` |  | `CString` |  |
| `GetCommanderRank` |  |  |  |
| `GetCompany` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCulture` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDebugDesc` |  | `CString` |  |
| `GetFirstName` |  | `CString` |  |
| `GetFirstNameNoFormatting` |  | `CString` |  |
| `GetFirstNamePossessive` |  | `CString` |  |
| `GetFront` |  |  |  |
| `GetFullName` |  | `CString` |  |
| `GetFullNameNoFormatting` |  | `CString` |  |
| `GetFullNamePossessive` |  | `CString` |  |
| `GetFullNameWithTitle` |  | `CString` |  |
| `GetFullNameWithTitleNoFormatting` |  | `CString` |  |
| `GetFullNameWithTitlePossessive` |  | `CString` |  |
| `GetFullNameWithTitlePossessiveNoFormatting` |  | `CString` |  |
| `GetGender` |  | `CString` |  |
| `GetGenderOpposite` |  | `CString` |  |
| `GetHerHim` |  | `CString` |  |
| `GetHerHimOpposite` |  | `CString` |  |
| `GetHerHis` |  | `CString` |  |
| `GetHerHisOpposite` |  | `CString` |  |
| `GetHerselfHimself` |  | `CString` |  |
| `GetHerselfHimselfOpposite` |  | `CString` |  |
| `GetHistoricalUrl` |  | `CString` |  |
| `GetHolding` |  |  |  |
| `GetHomeCountry` |  |  |  |
| `GetHomeCountryDefinition` |  |  |  |
| `GetHomeRegion` |  |  |  |
| `GetHomeState` |  |  |  |
| `GetID` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetIdeology` |  |  |  |
| `GetInfoTooltip` |  | `CString` |  |
| `GetInteraction` | `Arg0` |  |  |
| `GetInteractions` |  |  |  |
| `GetInterestGroup` |  |  |  |
| `GetInvasion` |  |  |  |
| `GetLastName` |  | `CString` |  |
| `GetLastNameNoFormatting` |  | `CString` |  |
| `GetLastNamePossessive` |  | `CString` |  |
| `GetLoyalty` |  | `CFixedPoint` |  |
| `GetLoyaltyDesc` |  | `CString` |  |
| `GetMaxOffensiveBattles` |  | `int32` |  |
| `GetMilitaryFormation` |  |  |  |
| `GetNextCommanderRank` |  |  |  |
| `GetNextCommanderRankBenefits` |  | `CString` |  |
| `GetNextOrderType` |  |  |  |
| `GetNumOffensiveBattles` |  | `int32` |  |
| `GetOrderType` |  |  |  |
| `GetPoliticalMovement` |  |  |  |
| `GetPopularity` |  | `CFixedPoint` |  |
| `GetPopularityDesc` |  | `CString` |  |
| `GetPortrait` | `Arg0, Arg1, Arg2, Arg3` |  |  |
| `GetPrimaryRole` |  |  |  |
| `GetPrimaryRoleTitle` |  | `CString` |  |
| `GetProminence` |  | `CFixedPoint` |  |
| `GetProminenceDesc` |  | `CString` |  |
| `GetPromoteCommand` |  | `Command` |  |
| `GetRankName` |  | `CString` |  |
| `GetRankNameFor` | `Arg0` | `CString` |  |
| `GetRankTitle` |  | `CString` |  |
| `GetRankTitleFor` | `Arg0` | `CString` |  |
| `GetRecruitCommand` | `Arg0` | `Command` |  |
| `GetRecruitCommandNoFormation` |  | `Command` |  |
| `GetReligion` |  |  |  |
| `GetRepairingTexture` |  |  |  |
| `GetSheHe` |  | `CString` |  |
| `GetSheHeOpposite` |  | `CString` |  |
| `GetStrengthPointsIcon` |  | `CString` |  |
| `GetTimedModifiers` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTraitsAffectedByMissionTypeDesc` | `Arg0` | `CString` |  |
| `GetTraitsDesc` |  | `CString` |  |
| `GetTravelArrivalDate` |  | `CString` |  |
| `GetTravelDaysLeft` |  | `int32` |  |
| `GetWomanMan` |  | `CString` |  |
| `GetWomanManOpposite` |  | `CString` |  |
| `HasAdvancingOrder` |  | `bool` |  |
| `HasAppointment` |  | `bool` |  |
| `HasCompany` |  | `bool` |  |
| `HasHolding` |  | `bool` |  |
| `HasInvasionPlan` |  | `bool` |  |
| `HasMilitaryFormation` |  | `bool` |  |
| `HasOrder` | `Arg0` | `bool` |  |
| `HasUnavailableAdvanceOrders` |  | `bool` |  |
| `HasUnavailableDefendOrders` |  | `bool` |  |
| `IsAdmiral` |  | `bool` |  |
| `IsAgitator` |  | `bool` |  |
| `IsAtFront` |  | `bool` |  |
| `IsAttackingInBattle` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsBusy` |  | `bool` |  |
| `IsCommander` |  | `bool` |  |
| `IsDefeated` |  | `bool` |  |
| `IsDefendingInBattle` |  | `bool` |  |
| `IsExecutive` |  | `bool` |  |
| `IsFemale` |  | `bool` |  |
| `IsGeneral` |  | `bool` |  |
| `IsHeirOfOwnCountry` |  | `bool` |  |
| `IsHistorical` |  | `bool` |  |
| `IsIGLeader` |  | `bool` |  |
| `IsInBattle` |  | `bool` |  |
| `IsInExilePool` |  | `bool` |  |
| `IsMagnate` |  | `bool` |  |
| `IsMaxRank` |  | `bool` |  |
| `IsOffer` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsPolitician` |  | `bool` |  |
| `IsRetired` |  | `bool` |  |
| `IsRulerOfOwnCountry` |  | `bool` |  |
| `IsTravellingToFormation` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsZoomingToOrderTarget` |  | `bool` |  |
| `OpenHistoricalUrl` |  | `void` |  |
| `PredictMovementToJoin` | `Arg0` |  |  |
| `PredictMovementTypeToStart` | `Arg0` |  |  |
| `RecruitCharacter` | `Arg0` | `void` |  |
| `RecruitCharacterNoFormation` |  | `void` |  |
| `SelectOrder` | `Arg0` | `Command` |  |
| `Self` |  |  |  |
| `TogglePinInOutliner` |  | `void` |  |
| `UnassignFromFormation` |  | `Command` |  |
| `WillJoinMovementIfInvited` | `Arg0` | `bool` |  |
| `WillNotStartOrJoinAnyMovementIfInvited` | `Arg0` | `bool` |  |
| `WillStartMovementIfInvited` | `Arg0` | `bool` |  |
| `ZoomToLocation` |  | `void` |  |
| `ZoomToOrderTarget` |  | `void` |  |

## CharacterFilter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCharacters` |  |  |  |
| `GetIGFilters` |  |  |  |
| `GetIdeologyFilters` |  |  |  |
| `GetNumFilteredCharacters` |  | `int32` |  |
| `GetNumTotalCharacters` |  | `int32` |  |
| `GetRoleFilters` |  |  |  |
| `HasCharacters` |  | `bool` |  |
| `IsAppointmentFilterSelected` | `Arg0` | `bool` |  |
| `IsHistoricalFilterSelected` | `Arg0` | `bool` |  |
| `IsIGFilterSelected` | `Arg0` | `bool` |  |
| `IsIdeologyFilterSelected` | `Arg0` | `bool` |  |
| `IsRoleFilterSelected` | `Arg0` | `bool` |  |
| `IsSorted` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetAppointmentFilter` | `Arg0` | `void` |  |
| `SetHistoricalFilter` | `Arg0` | `void` |  |
| `SetIGFilter` | `Arg0` | `void` |  |
| `SetIdeologyFilter` | `Arg0` | `void` |  |
| `SetRoleFilter` | `Arg0` | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `ToggleIGFilter` | `Arg0` | `void` |  |
| `ToggleIdeologyFilter` | `Arg0` | `void` |  |

## CharacterInteraction

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ExecuteCommand` | `Arg0` | `void` |  |
| `GetClickSound` |  |  |  |
| `GetCommandDesc` | `Arg0` | `CString` |  |
| `GetCooldownDesc` | `Arg0` | `CString` |  |
| `GetCooldownDuration` | `Arg0` | `CString` |  |
| `GetCooldownRemaining` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffects` | `Arg0` | `CString` |  |
| `GetIcon` |  |  |  |
| `GetInfo` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetRequirements` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasCooldown` | `Arg0` | `bool` |  |
| `HasIcon` |  | `bool` |  |
| `IsCommandValid` | `Arg0` | `bool` |  |
| `IsOnCooldown` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `ShouldShowRequirements` |  | `bool` |  |

## CharacterPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCharacter` |  | `Character` |  |
| `GetCharacter` |  | `Character` |  |
| `AccessCharacter` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCharacter` |  |  |  |
| `Self` |  |  |  |

## CharacterRole

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCharacterModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBackgroundTexture` |  |  |  |
| `GetCharacterModifier` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetPreposition` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTitle` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasDefinedTitles` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## CharacterTrait

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAffectedNavalMissionTypes` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessUnlockedOrders` |  |  |  |
| `GetAffectedNavalMissionTypesDesc` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetModifiers` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasAffectedNavalMissionTypes` |  | `bool` |  |
| `IsDisabled` |  | `bool` |  |
| `Self` |  |  |  |

## Chat

Jomini Chat - Chat

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetReceiver` |  | `Friend` |  |
| `AccessChatMessages` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetReceiver` |  |  |  |
| `GetReceiverName` |  | `CUTF8String` |  |
| `GetUnreadMessageCount` |  | `int32` |  |
| `HasUnreadMessages` |  | `bool` |  |
| `IsRoomChat` |  | `bool` |  |
| `Self` |  |  |  |

## ChatMessage

Jomini Chat - Message

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetMessage` |  | `CUTF8String` |  |
| `GetName` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## ChatNotificationMessage

Jomini Chat - Notification message

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `ChatMessage` |  | `ChatMessage` |  |
| `AccessSelf` |  |  |  |
| `ChatMessage` |  |  |  |
| `Kill` |  | `void` |  |
| `Self` |  |  |  |
| `StartChat` |  | `void` |  |

## ChatTab

Jomini Chat - Tab

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetChat` |  | `Chat` |  |
| `AccessSelf` |  |  |  |
| `Activate` |  | `void` |  |
| `Close` |  | `void` |  |
| `GetChat` |  |  |  |
| `GetChatTitle` |  | `CUTF8String` |  |
| `IsActive` |  | `bool` |  |
| `Self` |  |  |  |

## ChatWindow

Jomini Chat - Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessChatTabs` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanSendMessage` |  | `bool` |  |
| `Hide` |  | `void` |  |
| `Self` |  |  |  |
| `SendMessage` |  | `void` |  |
| `ShouldBeShown` |  | `bool` |  |
| `Show` |  | `void` |  |

## ChildGenerator

Portrait Editor - Child Generator

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetGenerationItems` |  |  |  |
| `GetRandomChildrenRatio` |  | `float` |  |
| `OnRandomizedRatioChanged` |  | `void` |  |
| `Regenerate` |  | `void` |  |
| `Self` |  |  |  |

## ChildItem

Portrait Editor - Child Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CopyDnaToClipboard` |  | `void` |  |
| `GetDna` |  | `CString` |  |
| `GetDnaForTexture` | `Arg0` | `CString` |  |
| `IsRandomized` |  | `bool` |  |
| `PasteDna` |  | `void` |  |
| `Self` |  |  |  |

## Cities

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ClearAll` |  | `void` |  |
| `GetCurrentBuildingCityTypeName` |  | `CString` |  |
| `GetCurrentBuildingLevel` |  | `int32` |  |
| `GetCurrentBuildingTypeName` |  | `CString` |  |
| `GetMidRatio` |  | `float` |  |
| `GetMonumentsMode` |  | `CString` |  |
| `GetPoorRatio` |  | `float` |  |
| `GetRichRatio` |  | `float` |  |
| `IsAutoRefresh` |  | `bool` |  |
| `IsCurrentBuildingTypeValid` |  | `bool` |  |
| `IsCurrentBuildingUnderConstruction` |  | `bool` |  |
| `Random` |  | `void` |  |
| `Refresh` |  | `void` |  |
| `Self` |  |  |  |
| `SetAutoRefresh` | `Arg0` | `void` |  |
| `SetCurrentBuildingLevel` |  | `void` |  |
| `SetCurrentBuildingLevelStr` |  | `void` |  |
| `SetCurrentBuildingUnderConstruction` | `Arg0` | `void` |  |
| `SetMidRatio` |  | `void` |  |
| `SetMidRatioStr` |  | `void` |  |
| `SetPoorRatio` |  | `void` |  |
| `SetPoorRatioStr` |  | `void` |  |
| `SetRichRatio` |  | `void` |  |
| `SetRichRatioStr` |  | `void` |  |

## CityMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetCityName` |  | `CString` |  |
| `GetCountry` |  |  |  |
| `GetState` |  |  |  |
| `IsCountryCapital` |  | `bool` |  |
| `IsRegionCapital` |  | `bool` |  |
| `Self` |  |  |  |

## CivilWar

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessOriginCountry` |  | `Country` |  |
| `AccessPoliticalMovement` |  | `PoliticalMovement` |  |
| `AccessUprisingCountry` |  | `Country` |  |
| `GetLeadingInsurrectionaryIG` |  | `InterestGroup` |  |
| `GetOriginCountry` |  | `Country` |  |
| `GetPoliticalMovement` |  | `PoliticalMovement` |  |
| `GetUprisingCountry` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessInsurrectionaryIGs` | `Arg0` |  |  |
| `AccessOriginCountry` |  |  |  |
| `AccessPoliticalMovement` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessUprisingCountry` |  |  |  |
| `GetClockCheckpointDateString` |  | `CString` |  |
| `GetClockCheckpointRemainingWeeks` |  | `int32` |  |
| `GetClockTime` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetLeadingInsurrectionaryIG` |  |  |  |
| `GetMaxProgress` |  | `CFixedPoint` |  |
| `GetMaxProgressDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNumUprisingBattalions` |  | `int32` |  |
| `GetNumUprisingPotentialConscripts` |  | `int32` |  |
| `GetNumUprisingShips` |  | `int32` |  |
| `GetNumUprisingStates` |  | `int32` |  |
| `GetOriginCountry` |  |  |  |
| `GetPoliticalMovement` |  |  |  |
| `GetProgress` |  | `CFixedPoint` |  |
| `GetProgressAtCheckpoint` |  | `CFixedPoint` |  |
| `GetProgressAtCheckpointDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUprisingConscriptionRateDesc` |  | `CString` |  |
| `GetUprisingCountry` |  |  |  |
| `GetUprisingNumUnitsDesc` |  | `CString` |  |
| `GetUprisingStatesString` |  | `CString` |  |
| `HasBrokenOut` |  | `bool` |  |
| `HasPoliticalMovement` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsOriginCountry` | `Arg0` | `bool` |  |
| `IsRevolution` |  | `bool` |  |
| `IsSecession` |  | `bool` |  |
| `IsUprisingCountry` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## CloudSaveData

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AreCloudSavesAvailable` |  | `bool` |  |
| `GetCloudSaveTooltip` |  | `CString` |  |
| `OnCloudSaveClick` |  | `void` |  |
| `Self` |  |  |  |
| `ShouldSaveToCloud` |  | `bool` |  |

## CoatOfArms

Coat of Arms Sprite

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` | `Arg0` | `CVector4f` |  |
| `GetFrame` | `Arg0, Arg1` | `int32` |  |
| `GetLargeFlagFrame` |  | `int32` |  |
| `GetLargeFlagSlot` |  | `CVector4f` |  |
| `GetLargeFlagTexture` |  |  |  |
| `GetLargePowerBlocCoaFrame` |  | `int32` |  |
| `GetLargePowerBlocCoaSlot` |  | `CVector4f` |  |
| `GetLargePowerBlocCoaTexture` |  |  |  |
| `GetMediumFlagFrame` |  | `int32` |  |
| `GetMediumFlagSlot` |  | `CVector4f` |  |
| `GetMediumFlagTexture` |  |  |  |
| `GetMediumPowerBlocCoaFrame` |  | `int32` |  |
| `GetMediumPowerBlocCoaSlot` |  | `CVector4f` |  |
| `GetMediumPowerBlocCoaTexture` |  |  |  |
| `GetSlot` | `Arg0, Arg1` | `CVector4f` |  |
| `GetSmallFlagFrame` |  | `int32` |  |
| `GetSmallFlagSlot` |  | `CVector4f` |  |
| `GetSmallFlagTexture` |  |  |  |
| `GetSmallPowerBlocCoaFrame` |  | `int32` |  |
| `GetSmallPowerBlocCoaSlot` |  | `CVector4f` |  |
| `GetSmallPowerBlocCoaTexture` |  |  |  |
| `GetTexture` | `Arg0, Arg1` |  |  |
| `GetVeryLargePowerBlocCoaFrame` |  | `int32` |  |
| `GetVeryLargePowerBlocCoaSlot` |  | `CVector4f` |  |
| `GetVeryLargePowerBlocCoaTexture` |  |  |  |
| `GetVerySmallPowerBlocCoaFrame` |  | `int32` |  |
| `GetVerySmallPowerBlocCoaSlot` |  | `CVector4f` |  |
| `GetVerySmallPowerBlocCoaTexture` |  |  |  |
| `Self` |  |  |  |

## CoatOfArmsPreviewWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `GetRandomFlagFrame` | `Arg0` | `int32` |  |
| `GetRandomFlagTexture` | `Arg0` |  |  |
| `RandomSeed` |  | `void` |  |
| `Self` |  |  |  |

## CohesionLevel

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

## ColonyMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessState` |  | `State` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetState` |  |  |  |
| `Self` |  |  |  |

## ColorPicker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetColorSpace` |  |  |  |
| `Self` |  |  |  |

## CombatShip

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetShip` |  | `Ship` |  |
| `AccessSelf` |  |  |  |
| `GetCrewCurrent` |  | `int32` |  |
| `GetCrewPercentage` |  | `CFixedPoint` |  |
| `GetCurrentReadiness` |  | `CFixedPoint` |  |
| `GetHitPoints` |  | `CFixedPoint` |  |
| `GetHitPointsPercentage` |  | `CFixedPoint` |  |
| `GetInitiative` |  | `int32` |  |
| `GetStatus` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsActive` |  | `bool` |  |
| `IsSunk` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsWithdrawn` |  | `bool` |  |
| `Self` |  |  |  |

## CombatUnit

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBattle` |  | `Battle` |  |
| `GetBuilding` |  | `Building` |  |
| `GetCountry` |  | `Country` |  |
| `GetCulture` |  | `Culture` |  |
| `GetFront` |  | `Front` |  |
| `GetMilitaryFormation` |  | `MilitaryFormation` |  |
| `GetUnitType` |  | `CombatUnitType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBattle` |  |  |  |
| `GetBuilding` |  |  |  |
| `GetCasualtiesDesc` |  | `CString` |  |
| `GetCountry` |  |  |  |
| `GetCulture` |  |  |  |
| `GetCurrentExperienceTowardsNextLevel` |  | `CFixedPoint` |  |
| `GetCurrentVeterancyLevel` |  | `int32` |  |
| `GetCurrentVeterancyLevelEffect` |  | `CString` |  |
| `GetCurrentVeterancyLevelIcon` |  |  |  |
| `GetCurrentVeterancyLevelName` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDefenseBreakdown` |  | `CString` |  |
| `GetDefenseFormatted` |  | `CString` |  |
| `GetDefenseRaw` |  | `CFixedPoint` |  |
| `GetDemoralized` |  | `int64` |  |
| `GetExperienceGainDescription` |  | `CString` |  |
| `GetFront` |  |  |  |
| `GetIconString` |  | `CString` |  |
| `GetIconTexture` |  |  |  |
| `GetManpowerFormatted` |  | `CString` |  |
| `GetManpowerRaw` |  | `int64` |  |
| `GetManpowerTooltip` |  | `CString` |  |
| `GetMaxManpower` |  | `int64` |  |
| `GetMilitaryFormation` |  |  |  |
| `GetMobilization` |  | `CFixedPoint` |  |
| `GetMorale` |  | `CString` |  |
| `GetMoraleGainDesc` |  | `CString` |  |
| `GetMoraleModifierBreakdown` |  | `CString` |  |
| `GetMoraleRaw` |  | `CFixedPoint` |  |
| `GetMoraleTooltip` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNeededExperienceForNextLevel` |  | `CFixedPoint` |  |
| `GetOffenseBreakdown` |  | `CString` |  |
| `GetOffenseFormatted` |  | `CString` |  |
| `GetOffenseRaw` |  | `CFixedPoint` |  |
| `GetPowerProjection` |  | `CFixedPoint` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  | `CString` |  |
| `GetUnitType` |  |  |  |
| `HasBattle` |  | `bool` |  |
| `HasFront` |  | `bool` |  |
| `IsConscript` |  | `bool` |  |
| `IsFullyMobilized` |  | `bool` |  |
| `IsMobilizing` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## CombatUnitGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetIDString` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUIColor` |  | `CVector4f` |  |
| `IsMarines` |  | `bool` |  |
| `Self` |  |  |  |

## CombatUnitType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBattleModifier` |  | `Modifier` |  |
| `GetFormationModifier` |  | `Modifier` |  |
| `GetGroup` |  | `CombatUnitGroup` |  |
| `GetUpkeepModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetBasePowerProjection` |  | `CFixedPoint` |  |
| `GetBattleModifier` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDefaultTexture` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetFormationModifier` |  |  |  |
| `GetGroup` |  |  |  |
| `GetIconString` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameWithCulture` | `Arg0` | `CString` |  |
| `GetRequirements` |  | `CString` |  |
| `GetSupplyCapacity` |  | `CFixedPoint` |  |
| `GetTextureForCulture` | `Arg0` |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUpkeepModifier` |  |  |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## Command

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Execute` |  | `void` |  |
| `GetConfirmationDesc` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `IsPotential` |  | `bool` |  |
| `IsRedundant` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `ShouldAskConfirmation` |  | `bool` |  |

## CommanderOrderType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanEscapeFromBattle` |  | `bool` |  |
| `GetAltName` | `Arg0` | `CString` |  |
| `GetClickSound` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEscapePowerRatio` |  | `CFixedPoint` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasAdvanceBehavior` |  | `bool` |  |
| `IsBasicOrderType` |  | `bool` |  |
| `IsStandBy` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## CommanderRank

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetModifiers` | `Arg0` | `CString` |  |
| `GetName` | `Arg0` | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTitle` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## CompaniesPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSearchBar` |  | `SearchBar` |  |
| `AccessSelf` |  |  |  |
| `GetAllBuildingTypes` |  |  |  |
| `GetCompanies` |  |  |  |
| `GetFilteredCompanyTypes` |  |  |  |
| `GetNumFilteredCompanies` |  | `int32` |  |
| `GetSearchBar` |  |  |  |
| `IsBuildingFilterSelected` | `Arg0` | `bool` |  |
| `IsCompanyTypesSorted` | `Arg0` | `bool` |  |
| `IsHistoricalFilterSelected` | `Arg0` | `bool` |  |
| `IsPrestigeGoodsFilterSelected` | `Arg0` | `bool` |  |
| `IsSorted` | `Arg0` | `bool` |  |
| `IsVisibilityFilterSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SetBuildingFilter` | `Arg0` | `void` |  |
| `SetHistoricalFilter` | `Arg0` | `void` |  |
| `SetPrestigeGoodsFilter` | `Arg0` | `void` |  |
| `SetVisibilityFilter` | `Arg0` | `void` |  |
| `Sort` | `Arg0` | `void` |  |
| `SortCompanyTypes` | `Arg0` | `void` |  |
| `ToggleBuildingFilter` | `Arg0` | `void` |  |

## Company

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCompanyType` |  | `CompanyType` |  |
| `AccessExecutive` |  | `Character` |  |
| `GetBuilding` |  | `Building` |  |
| `GetCompanyType` |  | `CompanyType` |  |
| `GetCountry` |  | `Country` |  |
| `GetEstablishmentDate` |  | `Date` |  |
| `GetExecutive` |  | `Character` |  |
| `GetState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessCompanyType` |  |  |  |
| `AccessExecutive` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetActiveCharters` | `Arg0` |  |  |
| `GetAdditionalIndustryTypes` |  |  |  |
| `GetBuilding` |  |  |  |
| `GetBuildingTypeLevels` | `Arg0` | `int32` |  |
| `GetBuildingTypeSizeDescription` | `Arg0` | `CString` |  |
| `GetBuildingTypes` |  |  |  |
| `GetBuildingTypesForTrends` |  |  |  |
| `GetBuildingTypesSizeDescription` |  | `CString` |  |
| `GetColonies` |  |  |  |
| `GetCompanyType` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetEstablishmentDate` |  |  |  |
| `GetExecutive` |  |  |  |
| `GetFormattedProductivity` |  | `CString` |  |
| `GetGlobalProductivityComparison` |  | `CFixedPoint` |  |
| `GetHQProfitDescription` |  | `CString` |  |
| `GetIsProducingPrestigeGoodsDesc` |  | `CString` |  |
| `GetMonopoliesDesc` |  | `CString` |  |
| `GetMonopolyBuildingTypes` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameFromPerspective` | `Arg0` | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNumEmployedBuildingLevels` |  | `int32` |  |
| `GetNumOwnedBuildingLevels` |  | `int32` |  |
| `GetOwnedCountries` |  |  |  |
| `GetOwnedTradeCenters` |  |  |  |
| `GetPrestigeGoods` |  |  |  |
| `GetProducedPrestigeGoodsDesc` |  | `CString` |  |
| `GetProductivity` |  | `CFixedPoint` |  |
| `GetProductivityTrend` |  | `DataTrend` |  |
| `GetProfit` |  | `CFixedPoint` |  |
| `GetProfitTrend` |  | `DataTrend` |  |
| `GetProsperity` |  | `CFixedPoint` |  |
| `GetProsperityChange` |  | `CFixedPoint` |  |
| `GetProsperityChangeDesc` |  | `CString` |  |
| `GetProsperityTrend` |  | `DataTrend` |  |
| `GetRegionalHQs` |  |  |  |
| `GetRevenueTrend` |  | `DataTrend` |  |
| `GetSizeTrend` |  | `DataTrend` |  |
| `GetState` |  |  |  |
| `GetTargetProsperity` |  | `CFixedPoint` |  |
| `GetTargetProsperityBreakdown` |  | `CString` |  |
| `GetTargetProsperityDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTrendForBuildingType` | `Arg0` | `DataTrend` |  |
| `HasAdditionalIndustry` | `Arg0` | `bool` |  |
| `HasAnyColonizationCharterActive` |  | `bool` |  |
| `HasAnyIndustryCharterActive` |  | `bool` |  |
| `HasAnyInvestmentCharterActive` |  | `bool` |  |
| `HasAnyMonopolyCharterActive` |  | `bool` |  |
| `HasAnyTradeCharterActive` |  | `bool` |  |
| `HasHighProductivity` |  | `bool` |  |
| `HasLowProductivity` |  | `bool` |  |
| `HasMonopoly` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsProducingPrestigeGoods` |  | `bool` |  |
| `IsProsperous` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleBuildingCharter` | `Arg0, Arg1` | `Command` |  |
| `ToggleCharter` | `Arg0` | `Command` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `ToggleRegionCharter` | `Arg0, Arg1` | `Command` |  |

## CompanyChangeNamePopup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCompany` |  | `Company` |  |
| `AccessSelf` |  |  |  |
| `Confirm` |  | `Command` |  |
| `GetCompany` |  |  |  |
| `OnEditName` |  | `void` |  |
| `Self` |  |  |  |

## CompanyCharter

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuildingType` |  | `BuildingType` |  |
| `GetStateRegion` |  | `StateRegion` |  |
| `GetType` |  | `CompanyCharterType` |  |
| `AccessSelf` |  |  |  |
| `GetBuildingType` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetEffects` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetStateRegion` |  |  |  |
| `GetToggleCommand` |  | `Command` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `Self` |  |  |  |

## CompanyCharterType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAuthorityCost` | `Arg0` | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffects` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetPotentialBuildings` | `Arg0` |  |  |
| `GetPotentialRegions` | `Arg0` |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsColonizationCharter` |  | `bool` |  |
| `IsIndustryCharter` |  | `bool` |  |
| `IsInvestmentCharter` |  | `bool` |  |
| `IsMonopolyCharter` |  | `bool` |  |
| `IsTargettingBuildings` |  | `bool` |  |
| `IsTargettingRegions` |  | `bool` |  |
| `IsTradeCharter` |  | `bool` |  |
| `Self` |  |  |  |

## CompanyPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCompany` |  | `Company` |  |
| `AccessSelf` |  |  |  |
| `GetCompany` |  |  |  |
| `Self` |  |  |  |

## CompanyType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetPotentialState` |  | `State` |  |
| `GetProsperityModifier` |  | `Modifier` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessBuildingTypes` | `Arg0` |  |  |
| `AccessSelf` |  |  |  |
| `CanProducePrestigeGoods` |  | `bool` |  |
| `GetAverageProductivity` |  | `CFixedPoint` |  |
| `GetBackground` |  |  |  |
| `GetCategoryDesc` |  | `CString` |  |
| `GetCategoryName` |  | `CString` |  |
| `GetCategoryNameNoFormatting` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetIcon` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumBuildingLevels` |  | `int32` |  |
| `GetPotentialBuildingTypes` | `Arg0` |  |  |
| `GetPotentialState` |  |  |  |
| `GetPrestigeGoods` |  |  |  |
| `GetProducedPrestigeGoodsDesc` |  | `CString` |  |
| `GetProductivity` |  | `CFixedPoint` |  |
| `GetProsperityModifier` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsFlavoredCompany` |  | `bool` |  |
| `Self` |  |  |  |
| `UsesDynamicNaming` |  | `bool` |  |

## ConfirmationWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `Self` |  |  |  |

## ConsoleMenuItem

Console Menu Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetHelp` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `IsCurrentGroup` |  | `bool` |  |
| `Select` |  | `void` |  |
| `Self` |  |  |  |

## ConsoleWindow

Console Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `IsMenuShown` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleMenu` |  | `void` |  |

## ConstructionPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessCurrentGovernmentConstructionQueuePage` | `Arg0` | `int32` |  |
| `AccessCurrentMilitaryShipConstructionQueuePage` |  | `int32` |  |
| `AccessCurrentPrivateConstructionQueuePage` | `Arg0` | `int32` |  |
| `AccessCurrentSupplyShipConstructionQueuePage` |  | `int32` |  |
| `AccessSelf` |  |  |  |
| `GetConstructionEntries` |  |  |  |
| `GetCountry` |  |  |  |
| `GetFilter` |  |  |  |
| `GetNumGovernmentConstructionQueueElements` | `Arg0` | `int32` |  |
| `GetNumGovernmentConstructionQueuePages` | `Arg0` | `int32` |  |
| `GetNumMilitaryShipConstructionQueuePages` |  | `int32` |  |
| `GetNumPrivateConstructionQueueElements` | `Arg0` | `int32` |  |
| `GetNumPrivateConstructionQueuePages` | `Arg0` | `int32` |  |
| `GetNumSupplyShipConstructionQueuePages` |  | `int32` |  |
| `GetShipConstructionProductionMethodEntries` | `Arg0` |  |  |
| `GetShipConstructions` |  |  |  |
| `GetSupplyShipConstructions` |  |  |  |
| `IsFilterNo` | `Arg0` | `bool` |  |
| `IsFilterYes` | `Arg0` | `bool` |  |
| `IsFiltered` | `Arg0` | `bool` |  |
| `IsShowingGovernmentConstructions` |  | `bool` |  |
| `IsShowingMilitaryShipConstructions` |  | `bool` |  |
| `IsShowingPrivateConstructions` |  | `bool` |  |
| `IsShowingSupplyShipConstructions` |  | `bool` |  |
| `NextGovernmentConstructionQueuePage` | `Arg0` | `void` |  |
| `NextMilitaryShipConstructionQueuePage` |  | `void` |  |
| `NextPrivateConstructionQueuePage` | `Arg0` | `void` |  |
| `NextSupplyShipConstructionQueuePage` |  | `void` |  |
| `PrevGovernmentConstructionQueuePage` | `Arg0` | `void` |  |
| `PrevMilitaryShipConstructionQueuePage` |  | `void` |  |
| `PrevPrivateConstructionQueuePage` | `Arg0` | `void` |  |
| `PrevSupplyShipConstructionQueuePage` |  | `void` |  |
| `Self` |  |  |  |
| `SetFilterMode` | `Arg0, Arg1` | `void` |  |
| `ShowGovernmentConstructions` |  | `void` |  |
| `ShowMilitaryShipConstructions` |  | `void` |  |
| `ShowPrivateConstructions` |  | `void` |  |
| `ShowSupplyShipConstructions` |  | `void` |  |

## ConstructionQueueElement

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessBuilding` |  | `Building` |  |
| `AccessState` |  | `State` |  |
| `GetBuilding` |  | `Building` |  |
| `GetInvestorBuilding` |  | `Building` |  |
| `GetInvestorBuildingType` |  | `BuildingType` |  |
| `GetInvestorCountry` |  | `Country` |  |
| `GetInvestorState` |  | `State` |  |
| `GetState` |  | `State` |  |
| `AccessBuilding` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `CalcPercentComplete` |  | `CFixedPoint` |  |
| `CancelConstruction` |  | `Command` |  |
| `GetBaseConstructionSpeed` |  | `CFixedPoint` |  |
| `GetBuilding` |  |  |  |
| `GetCompanyConstructionBonusDesc` |  | `CString` |  |
| `GetConstructionSpeed` |  | `CFixedPoint` |  |
| `GetConstructionSpeedPerWeekDesc` |  | `CString` |  |
| `GetIndex` |  | `int32` |  |
| `GetInvestorBuilding` |  |  |  |
| `GetInvestorBuildingType` |  |  |  |
| `GetInvestorCountry` |  |  |  |
| `GetInvestorState` |  |  |  |
| `GetQueueNumber` |  | `int32` |  |
| `GetState` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalProgress` |  | `CFixedPoint` |  |
| `GetWeeksLeft` |  | `int32` |  |
| `IsCurrentlyUnderConstruction` |  | `bool` |  |
| `IsPrivatelyFundedConstruction` |  | `bool` |  |
| `IsValidConstruction` |  | `bool` |  |
| `MoveDown` |  | `Command` |  |
| `MoveToBottom` |  | `Command` |  |
| `MoveToIndex` | `Arg0` | `Command` |  |
| `MoveToTop` |  | `Command` |  |
| `MoveUp` |  | `Command` |  |
| `Self` |  |  |  |

## Container

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## ContextMenuItem

Tools Context Menu Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Enabled` |  | `bool` |  |
| `GetIcon` |  |  |  |
| `GetLabel` |  | `CString` |  |
| `Self` |  |  |  |

## ContextualDiplomaticActionType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `GetDiplomaticActionType` |  | `DiplomaticActionType` |  |
| `AccessCountry` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetDiplomaticActionType` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## ContextualDiplomaticPact

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessDiplomaticPact` |  | `DiplomaticPact` |  |
| `GetContextCountry` |  | `Country` |  |
| `GetDiplomaticActionType` |  | `DiplomaticActionType` |  |
| `GetDiplomaticPact` |  | `DiplomaticPact` |  |
| `GetOtherCountry` |  | `Country` |  |
| `AccessDiplomaticPact` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetContextCountry` |  |  |  |
| `GetDiplomaticActionType` |  |  |  |
| `GetDiplomaticPact` |  |  |  |
| `GetOtherCountry` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsOngoingForContextCountry` |  | `bool` |  |
| `IsOngoingForOtherCountry` |  | `bool` |  |
| `Self` |  |  |  |

## CountriesPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCountries` |  |  |  |
| `IsSorted` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## Country

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessActiveLawFromGroup` | `Arg0` | `Law` |  |
| `AccessCapital` |  | `State` |  |
| `AccessCurrentlyResearchedTechnology` |  | `Technology` |  |
| `AccessDefinition` |  | `CountryDefinition` |  |
| `AccessFirstMarket` |  | `Market` |  |
| `AccessGovernment` |  | `GovernmentType` |  |
| `AccessHeaviestJournalEntry` |  | `JournalEntry` |  |
| `AccessHeir` |  | `Character` |  |
| `AccessLawBeingEnacted` |  | `Law` |  |
| `AccessModifier` |  | `Modifier` |  |
| `AccessOverlord` |  | `Country` |  |
| `AccessPowerBloc` |  | `PowerBloc` |  |
| `AccessRuler` |  | `Character` |  |
| `AccessStateReligion` |  | `Religion` |  |
| `AccessTopOverlord` |  | `Country` |  |
| `CalcLibertyDesireLevel` |  | `LibertyDesireLevel` |  |
| `GetAIStrategicRegionStanceTypeIn` | `Arg0` | `AIStrategicRegionStanceType` |  |
| `GetActiveLawFrom` | `Arg0` | `Law` |  |
| `GetActiveLawFromGroup` | `Arg0` | `Law` |  |
| `GetAttitudeTowards` | `Arg0` | `AIAttitude` |  |
| `GetCapital` |  | `State` |  |
| `GetClosestFriendlyPort` | `Arg0` | `Building` |  |
| `GetCurrentInterestTierTypeIn` | `Arg0` | `InterestTierType` |  |
| `GetCurrentlyResearchedTechnology` |  | `Technology` |  |
| `GetDefaultConstructionFleet` |  | `MilitaryFormation` |  |
| `GetDefinition` |  | `CountryDefinition` |  |
| `GetDiplomaticAction` | `Arg0, Arg1` | `DiplomaticAction` |  |
| `GetDiplomaticActionWithStates` | `Arg0, Arg1, Arg2, Arg3` | `DiplomaticAction` |  |
| `GetElection` |  | `Election` |  |
| `GetFirstPrimaryCulture` |  | `Culture` |  |
| `GetFlag` |  | `CoatOfArms` |  |
| `GetFlagship` |  | `Ship` |  |
| `GetFoodSecurity` |  | `FoodSecurity` |  |
| `GetGovernment` |  | `GovernmentType` |  |
| `GetGovernmentLegitimacyLevel` |  | `LegitimacyLevel` |  |
| `GetHeir` |  | `Character` |  |
| `GetInterestGroupOfType` | `Arg0` | `InterestGroup` |  |
| `GetJournalEntry` | `Arg0` | `JournalEntry` |  |
| `GetLawBeingEnacted` |  | `Law` |  |
| `GetLawBeingEnactedFromGroup` | `Arg0` | `Law` |  |
| `GetMarket` |  | `Market` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetMonopolyCountryOnBuildingType` | `Arg0` | `Country` |  |
| `GetNegotiatingInterestGroup` |  | `InterestGroup` |  |
| `GetObjective` |  | `Objective` |  |
| `GetOtherPowerBlocWithHighestLeverage` | `Arg0` | `PowerBloc` |  |
| `GetOverlord` |  | `Country` |  |
| `GetOwningCompany` |  | `Company` |  |
| `GetPlayer` |  | `Player` |  |
| `GetPowerBloc` |  | `PowerBloc` |  |
| `GetPowerBlocWithHighestLeverage` |  | `PowerBloc` |  |
| `GetPreviousAttitudeTowards` | `Arg0` | `AIAttitude` |  |
| `GetRankModifier` |  | `Modifier` |  |
| `GetRuler` |  | `Character` |  |
| `GetSampleLowerStrataPop` |  | `Pop` |  |
| `GetSampleLowerStrataPopForCulture` | `Arg0` | `Pop` |  |
| `GetSampleMiddleStrataPop` |  | `Pop` |  |
| `GetSampleMiddleStrataPopForCulture` | `Arg0` | `Pop` |  |
| `GetSampleUpperStrataPop` |  | `Pop` |  |
| `GetSampleUpperStrataPopForCulture` | `Arg0` | `Pop` |  |
| `GetSelectedLaw` |  | `Law` |  |
| `GetShipList` |  | `ShipList` |  |
| `GetSocialHierarchy` |  | `SocialHierarchy` |  |
| `GetSpecialSocialHierarchy` |  | `SocialHierarchy` |  |
| `GetStateReligion` |  | `Religion` |  |
| `GetSubjectPact` |  | `DiplomaticPact` |  |
| `GetSubjectType` |  | `SubjectType` |  |
| `GetTimedModifier` | `Arg0` | `TimedModifier` |  |
| `GetTopOverlord` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessActiveDiplomaticPactTypes` |  |  |  |
| `AccessActiveDiplomaticPacts` | `Arg0` |  |  |
| `AccessActiveDiplomaticPlays` |  |  |  |
| `AccessActiveEconomyLaws` |  |  |  |
| `AccessActiveHumanRightsLaws` |  |  |  |
| `AccessActiveInterestGroups` |  |  |  |
| `AccessActiveJournalEntries` |  |  |  |
| `AccessActiveLawFromGroup` | `Arg0` |  |  |
| `AccessActiveNonPlayerObjectiveJournalEntries` |  |  |  |
| `AccessActiveOtherLaws` |  |  |  |
| `AccessActiveParties` |  |  |  |
| `AccessActivePinnedNonPlayerObjectiveJournalEntries` |  |  |  |
| `AccessActivePinnedPlayerObjectiveJournalEntries` |  |  |  |
| `AccessActivePlayerObjectiveJournalEntries` |  |  |  |
| `AccessActivePowerStructureLaws` |  |  |  |
| `AccessAdmirals` |  |  |  |
| `AccessAdmiralsOffer` |  |  |  |
| `AccessAllInterestGroups` |  |  |  |
| `AccessCapital` |  |  |  |
| `AccessCivilWars` |  |  |  |
| `AccessConstructionQueue` |  |  |  |
| `AccessCurrentlyResearchedTechnology` |  |  |  |
| `AccessDefinition` |  |  |  |
| `AccessFirstMarket` |  |  |  |
| `AccessFormableCountries` |  |  |  |
| `AccessGenerals` |  |  |  |
| `AccessGeneralsOffer` |  |  |  |
| `AccessGovernment` |  |  |  |
| `AccessGovernmentConstructionQueue` |  |  |  |
| `AccessHeaviestJournalEntry` |  |  |  |
| `AccessHeir` |  |  |  |
| `AccessInactiveJournalEntries` |  |  |  |
| `AccessInstitutions` |  |  |  |
| `AccessInterestGroupsInGovernment` |  |  |  |
| `AccessInterestGroupsInOpposition` |  |  |  |
| `AccessInterests` |  |  |  |
| `AccessLandHQs` |  |  |  |
| `AccessLastElectionParties` |  |  |  |
| `AccessLawBeingEnacted` |  |  |  |
| `AccessLawsWithGovernmentOrMovementSupport` |  |  |  |
| `AccessLawsWithoutGovernmentOrMovementSupport` |  |  |  |
| `AccessMarginalInterestGroups` |  |  |  |
| `AccessModifier` |  |  |  |
| `AccessNavalHQs` |  |  |  |
| `AccessNonRevolutionaryPoliticalMovements` |  |  |  |
| `AccessNumResearchableTechnologies` |  | `int32` |  |
| `AccessOverlord` |  |  |  |
| `AccessPagedGovernmentConstructionQueue` | `Arg0, Arg1` |  |  |
| `AccessPagedPrivateConstructionQueue` | `Arg0, Arg1` |  |  |
| `AccessPoliticalMovements` |  |  |  |
| `AccessPopCultures` |  |  |  |
| `AccessPopCulturesSortedByPolStr` |  |  |  |
| `AccessPopCulturesSortedByPopulation` |  |  |  |
| `AccessPopReligionsSortedByPolStr` |  |  |  |
| `AccessPopReligionsSortedByPopulation` |  |  |  |
| `AccessPopTypes` |  |  |  |
| `AccessPopTypesSortedOnPolStr` |  |  |  |
| `AccessPopTypesSortedOnPopulation` |  |  |  |
| `AccessPowerBloc` |  |  |  |
| `AccessPrivateConstructionQueue` |  |  |  |
| `AccessReleasableCountries` |  |  |  |
| `AccessResearchableTechnologiesMilitary` |  |  |  |
| `AccessResearchableTechnologiesOther` |  |  |  |
| `AccessResearchableTechnologiesProduction` |  |  |  |
| `AccessResearchableTechnologiesSociety` |  |  |  |
| `AccessRuler` |  |  |  |
| `AccessSecessions` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessShippingLanes` |  |  |  |
| `AccessShippingOriginStates` | `Arg0` |  |  |
| `AccessShownCurrentlyConstructingGovernmentQueue` |  |  |  |
| `AccessShownCurrentlyConstructingPrivateQueue` |  |  |  |
| `AccessShownCurrentlyConstructingQueue` |  |  |  |
| `AccessStateReligion` |  |  |  |
| `AccessStates` |  |  |  |
| `AccessStrategies` |  |  |  |
| `AccessTopOverlord` |  |  |  |
| `AccessTruces` |  |  |  |
| `AccessVioSovInterestedCountries` | `Arg0` |  |  |
| `AccessVioSovWars` | `Arg0` |  |  |
| `AccessVisibleJournalEntries` |  |  |  |
| `AccessWars` |  |  |  |
| `CalcBaseConstructionSpeed` |  | `CFixedPoint` |  |
| `CalcConscriptableBattalions` |  | `int32` |  |
| `CalcCulturalTurmoil` | `Arg0` | `CFixedPoint` |  |
| `CalcLibertyDesireLevel` |  |  |  |
| `CalcNumStatesInTurmoil` |  | `int32` |  |
| `CalcRelativeUsedGovernmentConstruction` |  | `CFixedPoint` |  |
| `CalcRelativeUsedPrivateConstruction` |  | `CFixedPoint` |  |
| `CalcTurmoil` |  | `CFixedPoint` |  |
| `CalcUnusedConstruction` |  | `CFixedPoint` |  |
| `CalcUsedConstruction` |  | `CFixedPoint` |  |
| `CalcUsedGovernmentConstruction` |  | `CFixedPoint` |  |
| `CalcUsedPrivateConstruction` |  | `CFixedPoint` |  |
| `CanBuildingTypeBeMonopolized` | `Arg0` | `bool` |  |
| `CanSignTreatyWith` | `Arg0` | `bool` |  |
| `CanTradeGoods` | `Arg0` | `bool` |  |
| `ClearDefaultConstructionFleet` |  | `Command` |  |
| `CreateCompany` | `Arg0` | `Command` |  |
| `DeclareBankruptcy` |  | `Command` |  |
| `DemobilizeAllArmies` |  | `Command` |  |
| `EstimatedConstructionQueueDuration` |  | `int32` |  |
| `EstimatedGovernmentConstructionQueueDuration` |  | `int32` |  |
| `EstimatedPrivateConstructionQueueDuration` |  | `int32` |  |
| `Exists` |  | `bool` |  |
| `GetAIStrategicRegionStanceDescIn` | `Arg0` | `CString` |  |
| `GetAIStrategicRegionStanceTypeIn` | `Arg0` |  |  |
| `GetAIStrategiesDesc` |  | `CString` |  |
| `GetActiveConstructionProjectsDesc` |  | `CString` |  |
| `GetActiveLawFrom` | `Arg0` |  |  |
| `GetActiveLawFromGroup` | `Arg0` |  |  |
| `GetActivePeaceDealDesc` |  | `CString` |  |
| `GetAdditionalExpensesTrend` |  | `DataTrend` |  |
| `GetAdditionalIncomeTrend` |  | `DataTrend` |  |
| `GetAdditionalSOLFactorsDescAll` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescMiddle` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescPoor` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescRich` |  | `CString` |  |
| `GetAdditionalSOLFactorsDescWithCulture` | `Arg0` | `CString` |  |
| `GetAdditionalSOLFactorsDescWithCultureMiddle` | `Arg0` | `CString` |  |
| `GetAdditionalSOLFactorsDescWithCulturePoor` | `Arg0` | `CString` |  |
| `GetAdditionalSOLFactorsDescWithCultureRich` | `Arg0` | `CString` |  |
| `GetAdjective` |  | `CString` |  |
| `GetAdjectiveNoFlag` |  | `CString` |  |
| `GetAdjectiveNoFormatting` |  | `CString` |  |
| `GetAllAcceptanceStatusSegments` |  |  |  |
| `GetAllGeneralDiploActions` |  |  |  |
| `GetAllOverlordDiploActions` |  |  |  |
| `GetAllPowerBlocLeaderDiploActions` |  |  |  |
| `GetAllPowerBlocMemberDiploActions` |  |  |  |
| `GetAllSubjectDiploActions` |  |  |  |
| `GetAllianceLikeTreatiesBrokenDesc` | `Arg0` | `CString` |  |
| `GetAllianceLikeTreatiesBrokenFromPlayDesc` | `Arg0` | `CString` |  |
| `GetAllianceLikeTreatiesBrokenOnWarDesc` | `Arg0` | `CString` |  |
| `GetAllianceLikeTreatiesList` | `Arg0` | `CString` |  |
| `GetAltAdjective` | `Arg0` | `CString` |  |
| `GetAltAdjectiveNoFlag` | `Arg0` | `CString` |  |
| `GetAltAdjectiveNoFormatting` | `Arg0` | `CString` |  |
| `GetAltName` | `Arg0` | `CString` |  |
| `GetAltNameNoFlag` | `Arg0` | `CString` |  |
| `GetAltNameNoFormatting` | `Arg0` | `CString` |  |
| `GetArableLand` |  | `int32` |  |
| `GetArableLandDesc` |  | `CString` |  |
| `GetArmiesBreakdown` |  | `CString` |  |
| `GetArmyGoodsExpenses` |  | `CFixedPoint` |  |
| `GetArmyGoodsExpensesDesc` |  | `CString` |  |
| `GetArmyPowerProjection` |  | `CFixedPoint` |  |
| `GetArmyPowerProjectionDesc` |  | `CString` |  |
| `GetArmyReadinessStatusDesc` |  | `CString` |  |
| `GetArmyWagesExpenses` |  | `CFixedPoint` |  |
| `GetArmyWagesExpensesBreakdown` |  | `CString` |  |
| `GetAssignedAdmirals` |  |  |  |
| `GetAssignedGenerals` |  |  |  |
| `GetAttainableCompanies` |  |  |  |
| `GetAttitudeColor` | `Arg0` | `CVector4f` |  |
| `GetAttitudeTowards` | `Arg0` |  |  |
| `GetAvailableCompanies` |  |  |  |
| `GetAvailableGeneralDiploActions` |  |  |  |
| `GetAvailableOverlordDiploActions` |  |  |  |
| `GetAvailablePowerBlocLeaderDiploActions` |  |  |  |
| `GetAvailablePowerBlocMemberDiploActions` |  |  |  |
| `GetAvailableSubjectDiploActions` |  |  |  |
| `GetAverageExpectedStandardOfLivingWithCultureMiddle` | `Arg0` | `CFixedPoint` |  |
| `GetAverageExpectedStandardOfLivingWithCulturePoor` | `Arg0` | `CFixedPoint` |  |
| `GetAverageExpectedStandardOfLivingWithCultureRich` | `Arg0` | `CFixedPoint` |  |
| `GetAverageSoLByPoliticalStrength` |  | `CFixedPoint` |  |
| `GetAverageSoLByPopulation` |  | `CFixedPoint` |  |
| `GetAverageSoLByPopulationTrend` |  | `DataTrend` |  |
| `GetAverageSoLByPopulationWithCulture` | `Arg0` | `CFixedPoint` |  |
| `GetAverageSoLLowerTrend` |  | `DataTrend` |  |
| `GetAverageSoLMiddleTrend` |  | `DataTrend` |  |
| `GetAverageSoLUpperTrend` |  | `DataTrend` |  |
| `GetAverageStandardOfLivingMiddle` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingPoor` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingRich` |  | `CFixedPoint` |  |
| `GetAverageStandardOfLivingWithCultureMiddle` | `Arg0` | `CFixedPoint` |  |
| `GetAverageStandardOfLivingWithCulturePoor` | `Arg0` | `CFixedPoint` |  |
| `GetAverageStandardOfLivingWithCultureRich` | `Arg0` | `CFixedPoint` |  |
| `GetAverageStateTaxCollectionMult` |  | `CFixedPoint` |  |
| `GetAverageStateTaxCollectionMultBreakdown` |  | `CString` |  |
| `GetAverageTaxWaste` |  | `CFixedPoint` |  |
| `GetAverageTaxWasteBreakdown` |  | `CString` |  |
| `GetBalanceTrend` |  | `DataDynamicTrend` |  |
| `GetBaseConstructionSpeedDesc` |  | `CString` |  |
| `GetBaseWeeklyTechnologySpread` |  | `CFixedPoint` |  |
| `GetBaseWeeklyTechnologySpreadForTech` | `Arg0` | `CFixedPoint` |  |
| `GetBattalions` |  | `int32` |  |
| `GetBattalionsDesc` |  | `CString` |  |
| `GetBattalionsMobilizing` |  | `int32` |  |
| `GetBattalionsRanking` |  | `CString` |  |
| `GetBolsterDesc` |  | `CString` |  |
| `GetBolsteringCostDesc` |  | `CString` |  |
| `GetCanBuildingTypeBeMonopolizedDesc` | `Arg0` | `CString` |  |
| `GetCanSignTreatyWithDesc` | `Arg0` | `CString` |  |
| `GetCapital` |  |  |  |
| `GetClosestFriendlyPort` | `Arg0` |  |  |
| `GetColonialGrowthDetails` |  | `CString` |  |
| `GetCompanies` |  |  |  |
| `GetCompanyConstructionEfficiencyBonusFormatted` |  | `CString` |  |
| `GetCompanyThroughputBonusFormatted` |  | `CString` |  |
| `GetConscriptedBattalions` |  | `int32` |  |
| `GetConscriptionRatio` |  | `CFixedPoint` |  |
| `GetConstructionGoodsExpenseTrend` |  | `DataTrend` |  |
| `GetConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetConstructionGoodsExpensesDesc` |  | `CString` |  |
| `GetConstructionQueueDesc` |  | `CString` |  |
| `GetConstructionsInCountry` | `Arg0` |  |  |
| `GetConsumptionTaxIncome` |  | `CFixedPoint` |  |
| `GetConsumptionTaxTrend` |  | `DataTrend` |  |
| `GetConsumptionTaxesDesc` |  | `CString` |  |
| `GetCountriesWithTreaties` |  |  |  |
| `GetCountryScorePosition` |  | `int32` |  |
| `GetCountryScorePositionDesc` |  | `CString` |  |
| `GetCreditRatio` |  | `CFixedPoint` |  |
| `GetCreditTooltip` |  | `CString` |  |
| `GetCulturePolStrAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetCulturePopulation` | `Arg0` | `int64` |  |
| `GetCurrentInterestTierTypeIn` | `Arg0` |  |  |
| `GetCurrentInvolvementIn` | `Arg0` | `CFixedPoint` |  |
| `GetCurrentLeverage` | `Arg0` | `CFixedPoint` |  |
| `GetCurrentLeverageShare` | `Arg0` | `CFixedPoint` |  |
| `GetCurrentPowerStruggleMonth` |  | `int32` |  |
| `GetCurrentSailors` |  | `int32` |  |
| `GetCurrentlyResearchedTechnology` |  |  |  |
| `GetCurrentlySpreadingTechsDesc` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDailyRelationsProgress` | `Arg0` | `CFixedPoint` |  |
| `GetDaysUntilElection` |  | `int32` |  |
| `GetDaysUntilRankLoss` |  | `int32` |  |
| `GetDecisions` |  |  |  |
| `GetDeclareBankruptcyDesc` |  | `CString` |  |
| `GetDecreasingInterestsDesc` |  | `CString` |  |
| `GetDeficitPowerRatio` | `Arg0` | `CFixedPoint` |  |
| `GetDeficitPowerRatioForProgressBar` | `Arg0` | `CFixedPoint` |  |
| `GetDeficitSupplyShipRatioForProgressBar` |  | `CFixedPoint` |  |
| `GetDefinition` |  |  |  |
| `GetDependents` |  | `int64` |  |
| `GetDiplomaticAction` | `Arg0, Arg1` |  |  |
| `GetDiplomaticActionWithStates` | `Arg0, Arg1, Arg2, Arg3` |  |  |
| `GetDiplomaticPactsExpenseTrend` |  | `DataTrend` |  |
| `GetDiplomaticPactsIncomeTrend` |  | `DataTrend` |  |
| `GetDiplomaticStatusColor` | `Arg0` | `CVector4f` |  |
| `GetDistanceToClosestFriendlyPort` | `Arg0` | `int32` |  |
| `GetDividendsTaxTrend` |  | `DataTrend` |  |
| `GetDomesticallyOwnedGDP` |  | `CFixedPoint` |  |
| `GetDomesticallyOwnedGDPFraction` |  | `CFixedPoint` |  |
| `GetDraftTreaties` |  |  |  |
| `GetDraftTreatiesWith` | `Arg0` |  |  |
| `GetEconomicDependenceOn` | `Arg0` | `CString` |  |
| `GetEconomicDependenceOnDesc` | `Arg0` | `CString` |  |
| `GetEconomicDependenceOnRaw` | `Arg0` | `CFixedPoint` |  |
| `GetElection` |  |  |  |
| `GetElectionPollTooltip` |  | `CString` |  |
| `GetElectoralConfidence` |  | `CFixedPoint` |  |
| `GetElectoralConfidenceEffectDesc` |  | `CString` |  |
| `GetEmployedWorkingAdults` |  | `int64` |  |
| `GetEmptyAgitatorSlots` |  | `int32` |  |
| `GetEnemyOccupation` |  | `CFixedPoint` |  |
| `GetEnforcedTreaties` |  |  |  |
| `GetEnforcedTreatiesWith` | `Arg0` |  |  |
| `GetEnforcedTreatiesWithDesc` | `Arg0` | `CString` |  |
| `GetEventsByCategory` | `Arg0` |  |  |
| `GetExcessPowerRatio` | `Arg0` | `CFixedPoint` |  |
| `GetExcessPowerRatioForProgressBar` | `Arg0` | `CFixedPoint` |  |
| `GetExcessSupplyShipRatioForProgressBar` |  | `CFixedPoint` |  |
| `GetExpectedSOLFactorsDescAll` |  | `CString` |  |
| `GetExpectedSOLFactorsDescMiddle` |  | `CString` |  |
| `GetExpectedSOLFactorsDescPoor` |  | `CString` |  |
| `GetExpectedSOLFactorsDescRich` |  | `CString` |  |
| `GetExpectedSOLFactorsDescWithCulture` | `Arg0` | `CString` |  |
| `GetExpectedSoLByPopulation` |  | `CFixedPoint` |  |
| `GetExpectedStandardOfLivingMiddle` |  | `CFixedPoint` |  |
| `GetExpectedStandardOfLivingPoor` |  | `CFixedPoint` |  |
| `GetExpectedStandardOfLivingRich` |  | `CFixedPoint` |  |
| `GetExpensesBreakdown` |  | `CString` |  |
| `GetExportSubventionsDescHigh` | `Arg0` | `CString` |  |
| `GetExportSubventionsDescLow` | `Arg0` | `CString` |  |
| `GetExportSubventionsDescMax` | `Arg0` | `CString` |  |
| `GetExportTariffsDescHigh` | `Arg0` | `CString` |  |
| `GetExportTariffsDescLow` | `Arg0` | `CString` |  |
| `GetExportTariffsDescMax` | `Arg0` | `CString` |  |
| `GetExportTariffsDescNone` | `Arg0` | `CString` |  |
| `GetExportedAmount` | `Arg0` | `CFixedPoint` |  |
| `GetExports` |  |  |  |
| `GetFirstPrimaryCulture` |  |  |  |
| `GetFlag` |  |  |  |
| `GetFlagTextIcon` |  | `CString` |  |
| `GetFlavorText` |  | `CString` |  |
| `GetFleetsBreakdown` |  | `CString` |  |
| `GetForeignOwnedGDP` |  | `CFixedPoint` |  |
| `GetForeignOwnedGDPDesc` |  | `CString` |  |
| `GetForeignOwnedGDPFraction` |  | `CFixedPoint` |  |
| `GetFormattedStandardOfLivingAll` |  | `CString` |  |
| `GetFormattedStandardOfLivingAllWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingLabelAll` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelAllWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingLabelMiddle` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelMiddleWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingLabelPoor` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelPoorWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingLabelRich` |  | `CString` |  |
| `GetFormattedStandardOfLivingLabelRichWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingMiddle` |  | `CString` |  |
| `GetFormattedStandardOfLivingMiddleWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingPoor` |  | `CString` |  |
| `GetFormattedStandardOfLivingPoorWithCulture` | `Arg0` | `CString` |  |
| `GetFormattedStandardOfLivingRich` |  | `CString` |  |
| `GetFormattedStandardOfLivingRichWithCulture` | `Arg0` | `CString` |  |
| `GetFreeArableLand` |  | `int32` |  |
| `GetFreeMilitaryConstructionCapacity` |  | `CFixedPoint` |  |
| `GetFreeSupplyConstructionCapacity` |  | `CFixedPoint` |  |
| `GetGDP` |  | `CFixedPoint` |  |
| `GetGDPOwnedInForeignCountries` |  | `CFixedPoint` |  |
| `GetGDPOwnedInForeignCountriesDesc` |  | `CString` |  |
| `GetGDPPerCapita` |  | `CFixedPoint` |  |
| `GetGDPPerCapitaRanking` |  | `CString` |  |
| `GetGDPRanking` |  | `CString` |  |
| `GetGDPTrend` |  | `DataTrend` |  |
| `GetGDPWithOwnershipsInForeignCountries` |  | `CFixedPoint` |  |
| `GetGameOverDateString` |  | `CString` |  |
| `GetGdpRatioOwnedBy` | `Arg0` | `CString` |  |
| `GetGdpRatioOwnedByDesc` | `Arg0` | `CString` |  |
| `GetGdpRatioOwnedByRaw` | `Arg0` | `CFixedPoint` |  |
| `GetGoldProgressDesc` |  | `CString` |  |
| `GetGoldReserveLimit` |  | `CFixedPoint` |  |
| `GetGoldReserveLimitDesc` |  | `CString` |  |
| `GetGoldReserveRatio` |  | `CFixedPoint` |  |
| `GetGoldReserves` |  | `CFixedPoint` |  |
| `GetGoldReservesTrend` |  | `DataDynamicTrend` |  |
| `GetGoodsLeaderboardDesc` |  | `CString` |  |
| `GetGovernment` |  |  |  |
| `GetGovernmentConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetGovernmentConstructionGoodsExpensesByGoodsDesc` |  | `CString` |  |
| `GetGovernmentGoodsExpenseTrend` |  | `DataTrend` |  |
| `GetGovernmentGoodsExpenses` |  | `CFixedPoint` |  |
| `GetGovernmentGoodsExpensesByGoodsDesc` |  | `CString` |  |
| `GetGovernmentGoodsExpensesDesc` |  | `CString` |  |
| `GetGovernmentIGsDesc` |  | `CString` |  |
| `GetGovernmentInterestGroupsDesc` |  | `CString` |  |
| `GetGovernmentInterestGroupsPopulationDesc` |  | `CString` |  |
| `GetGovernmentLegitimacy` |  | `int32` |  |
| `GetGovernmentLegitimacyDesc` |  | `CString` |  |
| `GetGovernmentLegitimacyLevel` |  |  |  |
| `GetGovernmentSelfDebt` |  | `CFixedPoint` |  |
| `GetGovernmentSelfDebtFraction` |  | `CFixedPoint` |  |
| `GetGovernmentShareDividendsTrend` |  | `DataTrend` |  |
| `GetGovernmentShareLossesTrend` |  | `DataTrend` |  |
| `GetGovernmentSlavesExpenseTrend` |  | `DataTrend` |  |
| `GetGovernmentSlavesExpenses` |  | `CFixedPoint` |  |
| `GetGovernmentSlavesExpensesDesc` |  | `CString` |  |
| `GetGovernmentWageLevelDescHigh` |  | `CString` |  |
| `GetGovernmentWageLevelDescLow` |  | `CString` |  |
| `GetGovernmentWageLevelDescMedium` |  | `CString` |  |
| `GetGovernmentWageLevelDescVeryHigh` |  | `CString` |  |
| `GetGovernmentWageLevelDescVeryLow` |  | `CString` |  |
| `GetGovernmentWagesExpenseTrend` |  | `DataTrend` |  |
| `GetGovernmentWagesExpenses` |  | `CFixedPoint` |  |
| `GetGovernmentWagesExpensesDesc` |  | `CString` |  |
| `GetGroupsForActiveJournalEntries` |  |  |  |
| `GetGroupsForInActiveJournalEntries` |  |  |  |
| `GetGrowingCivilWars` |  |  |  |
| `GetHeir` |  |  |  |
| `GetHighestPossibleRank` |  | `CString` |  |
| `GetID` |  | `int32` |  |
| `GetIDString` |  | `CString` |  |
| `GetIGApprovalFromLoyalistsBreakdown` |  | `CString` |  |
| `GetIGApprovalFromRadicalsBreakdown` |  | `CString` |  |
| `GetImportSubventionsDescHigh` | `Arg0` | `CString` |  |
| `GetImportSubventionsDescLow` | `Arg0` | `CString` |  |
| `GetImportSubventionsDescMax` | `Arg0` | `CString` |  |
| `GetImportTariffsDescHigh` | `Arg0` | `CString` |  |
| `GetImportTariffsDescLow` | `Arg0` | `CString` |  |
| `GetImportTariffsDescMax` | `Arg0` | `CString` |  |
| `GetImportTariffsDescNone` | `Arg0` | `CString` |  |
| `GetImportedAmount` | `Arg0` | `CFixedPoint` |  |
| `GetImports` |  |  |  |
| `GetInDefaultEffectsDesc` |  | `CString` |  |
| `GetInForceTreaties` |  |  |  |
| `GetInactiveConstructionProjectsDesc` |  | `CString` |  |
| `GetInactivePopulation` |  | `int64` |  |
| `GetInactivePopulationDesc` |  | `CString` |  |
| `GetIncomeBreakdown` |  | `CString` |  |
| `GetIncomeTaxIncome` |  | `CFixedPoint` |  |
| `GetIncorporatedLiteracyRanking` |  | `CString` |  |
| `GetIncorporatedLiteracyRate` |  | `CFixedPoint` |  |
| `GetIncorporatedLiteracyTrend` |  | `DataTrend` |  |
| `GetIncorporatedPopulation` |  | `int64` |  |
| `GetIncorporatedStatesLawCostDesc` |  | `CString` |  |
| `GetIndependentInterestGroupsInGovernment` |  |  |  |
| `GetIndependentInterestGroupsInOpposition` |  |  |  |
| `GetInfamy` |  | `CFixedPoint` |  |
| `GetInfamyColor` |  | `CVector4f` |  |
| `GetInfamyDesc` |  | `CString` |  |
| `GetInfamyIconTexture` |  |  |  |
| `GetInfamyLabel` |  | `CString` |  |
| `GetInstitutionInvestment` |  | `CFixedPoint` |  |
| `GetInstitutionInvestmentBureaucracyCost` |  | `CFixedPoint` |  |
| `GetInstitutionInvestmentBureaucracyCostDesc` |  | `CString` |  |
| `GetInstitutionInvestmentBureaucracyFactor` |  | `CFixedPoint` |  |
| `GetInstitutionInvestmentBureaucracyFactorDesc` |  | `CString` |  |
| `GetInstitutionInvestmentDesc` |  | `CString` |  |
| `GetInstitutionsSummary` |  | `CString` |  |
| `GetInsurrectionaryIGsDesc` |  | `CString` |  |
| `GetInterestExpenseTrend` |  | `DataTrend` |  |
| `GetInterestGroupOfType` | `Arg0` |  |  |
| `GetInterestPayment` |  | `CFixedPoint` |  |
| `GetInterestRateTooltip` |  | `CString` |  |
| `GetInvestmentFundTrend` |  | `DataTrend` |  |
| `GetInvestmentGdpFractionInCountry` | `Arg0` | `CFixedPoint` |  |
| `GetInvestmentIncome` |  | `CFixedPoint` |  |
| `GetInvestmentIncomeTrend` |  | `DataTrend` |  |
| `GetInvestmentLevelsInCountry` | `Arg0` | `int32` |  |
| `GetInvestmentPool` |  | `CFixedPoint` |  |
| `GetInvestmentPoolChange` |  | `CFixedPoint` |  |
| `GetInvestmentPoolChangeFromConstructionDesc` |  | `CString` |  |
| `GetInvestmentPoolChangeFromInvestmentBreakdown` |  | `CString` |  |
| `GetInvestmentPoolChangeFromInvestmentDesc` |  | `CString` |  |
| `GetInvestmentPoolPredictedNextBuildingDesc` |  | `CString` |  |
| `GetInvolvementGrowth` | `Arg0` | `CFixedPoint` |  |
| `GetJournalEntry` | `Arg0` |  |  |
| `GetKillRateNavy` |  | `CFixedPoint` |  |
| `GetLabel` | `Arg0` | `CString` |  |
| `GetLackOfAutonomousInvestmentReasonDesc` |  | `CString` |  |
| `GetLastCatalystExpiryDate` | `Arg0, Arg1` | `CString` |  |
| `GetLastElectionResultsTooltip` |  | `CString` |  |
| `GetLawBeingEnacted` |  |  |  |
| `GetLawBeingEnactedFromGroup` | `Arg0` |  |  |
| `GetLawEnactmentProgress` |  | `CFixedPoint` |  |
| `GetLawEnactmentProgressDesc` |  | `CString` |  |
| `GetLeaderReligionPercentage` |  | `CFixedPoint` |  |
| `GetLeverageAdvantage` | `Arg0` | `CFixedPoint` |  |
| `GetLeverageAdvantageTarget` | `Arg0` | `CFixedPoint` |  |
| `GetLeverageBreakdown` |  | `CString` |  |
| `GetLeverageComparisonDesc` | `Arg0` | `CString` |  |
| `GetLeverageGain` | `Arg0` | `CFixedPoint` |  |
| `GetLeverageGainBreakdown` | `Arg0` | `CString` |  |
| `GetLeverageResistance` |  | `CFixedPoint` |  |
| `GetLeverageTarget` | `Arg0` | `CFixedPoint` |  |
| `GetLeverageTooltip` |  | `CString` |  |
| `GetLibertyDesireLevelLabel` |  | `CString` |  |
| `GetLibertyDesireRaw` |  | `CFixedPoint` |  |
| `GetLimitedMassMigrationCountryAttraction` |  | `CFixedPoint` |  |
| `GetLobbyJournalEntries` |  |  |  |
| `GetLocalityDescIn` | `Arg0` | `CString` |  |
| `GetLocalityIn` | `Arg0` | `CFixedPoint` |  |
| `GetLocalityInDisplay` | `Arg0` | `CFixedPoint` |  |
| `GetLowerStrataPopulationTrend` |  | `DataTrend` |  |
| `GetLoyalistsChangeSummary` |  | `CString` |  |
| `GetLoyalistsDecreaseBreakdown` |  | `CString` |  |
| `GetLoyalistsIncreaseBreakdown` |  | `CString` |  |
| `GetLoyalistsOrRadicalsGainedFromLegitimacy` |  | `int64` |  |
| `GetLoyalistsOrRadicalsGainedFromLegitimacyModifierDescription` | `Arg0` | `CString` |  |
| `GetLoyalistsSummaryDesc` |  | `CString` |  |
| `GetLoyalistsTrend` |  | `DataTrend` |  |
| `GetLoyaltiesGain` |  | `CFixedPoint` |  |
| `GetMapColor` |  | `CVector4f` |  |
| `GetMarginalAndInactivePopulationInCountryAsPercentage` |  | `float` |  |
| `GetMarginalCloutInCountryAsPercentage` |  | `float` |  |
| `GetMarginalInterestGroupsDesc` |  | `CString` |  |
| `GetMarginalInterestGroupsPopulationDesc` |  | `CString` |  |
| `GetMarket` |  |  |  |
| `GetMarketFeesIncome` |  | `CFixedPoint` |  |
| `GetMarketFeesIncomeDesc` |  | `CString` |  |
| `GetMarketOwnerName` |  | `CString` |  |
| `GetMassMigrationAttractionBreakdown` |  | `CString` |  |
| `GetMassMigrationAttractionDesc` |  | `CString` |  |
| `GetMaxCloutOrPopulationPercentage` |  | `float` |  |
| `GetMaxCredit` |  | `CFixedPoint` |  |
| `GetMaxFreeCharters` |  | `int32` |  |
| `GetMaxLawEnactmentSetbacks` |  | `int32` |  |
| `GetMaxNumCompanies` |  | `int32` |  |
| `GetMaxNumCompaniesDesc` |  | `CString` |  |
| `GetMaxPowerStruggleMonth` |  | `int32` |  |
| `GetMaxUnassignedAdmirals` |  | `int32` |  |
| `GetMaxUnassignedGenerals` |  | `int32` |  |
| `GetMaxWeeklyTechnologyProgressForTech` | `Arg0` | `CFixedPoint` |  |
| `GetMaxWeeklyTechnologySpread` |  | `CFixedPoint` |  |
| `GetMaxWeeklyTechnologySpreadForTech` | `Arg0` | `CFixedPoint` |  |
| `GetMerchantMarineShortage` |  | `CFixedPoint` |  |
| `GetMerchantMarineShortageTarget` |  | `CFixedPoint` |  |
| `GetMiddleStrataPopulationTrend` |  | `DataTrend` |  |
| `GetMilitaryConstructionCapacity` |  | `CFixedPoint` |  |
| `GetMilitaryConstructionQueueCount` |  | `int32` |  |
| `GetMilitaryConstructionQueueUsage` |  | `CFixedPoint` |  |
| `GetMilitaryConstructionUsageTotal` |  | `CFixedPoint` |  |
| `GetMilitaryFormationsArmy` |  |  |  |
| `GetMilitaryFormationsFleet` |  |  |  |
| `GetMilitaryGoodsExpenseTrend` |  | `DataTrend` |  |
| `GetMilitaryGoodsExpenses` |  | `CFixedPoint` |  |
| `GetMilitaryGoodsExpensesByGoodsDesc` |  | `CString` |  |
| `GetMilitaryGoodsExpensesDesc` |  | `CString` |  |
| `GetMilitaryInterfaceColor` |  | `CVector4f` |  |
| `GetMilitaryMaintenanceDemand` |  | `CFixedPoint` |  |
| `GetMilitaryMaintenanceDemandDesc` |  | `CString` |  |
| `GetMilitaryMaintenanceFulfillment` |  | `CFixedPoint` |  |
| `GetMilitaryMaintenanceUsage` |  | `CFixedPoint` |  |
| `GetMilitaryShipConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetMilitaryShipCount` |  | `int32` |  |
| `GetMilitaryShipMaintenanceExpenses` |  | `CFixedPoint` |  |
| `GetMilitaryShipMaintenanceExpensesDesc` |  | `CString` |  |
| `GetMilitarySlavesExpenseTrend` |  | `DataTrend` |  |
| `GetMilitarySlavesExpenses` |  | `CFixedPoint` |  |
| `GetMilitarySlavesExpensesDesc` |  | `CString` |  |
| `GetMilitaryWageLevelDescHigh` |  | `CString` |  |
| `GetMilitaryWageLevelDescLow` |  | `CString` |  |
| `GetMilitaryWageLevelDescMedium` |  | `CString` |  |
| `GetMilitaryWageLevelDescVeryHigh` |  | `CString` |  |
| `GetMilitaryWageLevelDescVeryLow` |  | `CString` |  |
| `GetMilitaryWagesExpenseTrend` |  | `DataTrend` |  |
| `GetMilitaryWagesExpenses` |  | `CFixedPoint` |  |
| `GetMilitaryWagesExpensesDesc` |  | `CString` |  |
| `GetMinWeeklyTechnologyProgressForTech` | `Arg0` | `CFixedPoint` |  |
| `GetMinWeeklyTechnologySpread` |  | `CFixedPoint` |  |
| `GetMinWeeklyTechnologySpreadForTech` | `Arg0` | `CFixedPoint` |  |
| `GetMintingTrend` |  | `DataTrend` |  |
| `GetMobilizationRatio` |  | `CFixedPoint` |  |
| `GetModifier` |  |  |  |
| `GetMoveCapitalEffectsDesc` |  | `CString` |  |
| `GetMoveMarketCapitalEffectsDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFlag` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNavalHostilitiesCountriesDesc` |  | `CString` |  |
| `GetNavalHostilitiesDamageAgainst` | `Arg0` | `CString` |  |
| `GetNavyCombatPower` |  | `CFixedPoint` |  |
| `GetNavyGoodsExpenses` |  | `CFixedPoint` |  |
| `GetNavyGoodsExpensesDesc` |  | `CString` |  |
| `GetNavyPowerProjection` |  | `CFixedPoint` |  |
| `GetNavyPowerProjectionDesc` |  | `CString` |  |
| `GetNavyWagesExpenses` |  | `CFixedPoint` |  |
| `GetNavyWagesExpensesBreakdown` |  | `CString` |  |
| `GetNeededSailors` |  | `int32` |  |
| `GetNegotiatingInterestGroup` |  |  |  |
| `GetNextElectionDate` |  | `CString` |  |
| `GetNextRank` |  | `CString` |  |
| `GetNextRankDesc` |  | `CString` |  |
| `GetNextRankNumber` |  | `int32` |  |
| `GetNextStartOfCampaignDate` |  | `CString` |  |
| `GetNonPotentialDiploPlays` |  |  |  |
| `GetNonSubjectDiplomaticPactsWith` | `Arg0` |  |  |
| `GetNumActiveConstructionQueueElements` |  | `int32` |  |
| `GetNumActiveGovernmentConstructionQueueElements` |  | `int32` |  |
| `GetNumActivePrivateConstructionQueueElements` |  | `int32` |  |
| `GetNumActiveShownConstructionQueueElements` |  | `int32` |  |
| `GetNumActiveShownGovernmentConstructionQueueElements` |  | `int32` |  |
| `GetNumActiveShownPrivateConstructionQueueElements` |  | `int32` |  |
| `GetNumAssignedSupplyShips` |  | `int32` |  |
| `GetNumAssignedSupplyShipsToArmies` |  | `int32` |  |
| `GetNumAssignedSupplyShipsToFleets` |  | `int32` |  |
| `GetNumAvailableCompanies` |  | `int32` |  |
| `GetNumAvailableNegotiations` |  | `int32` |  |
| `GetNumAvailableSupplyShips` |  | `int32` |  |
| `GetNumBattalions` |  | `int32` |  |
| `GetNumBuildingsInConstructionQueueInState` | `Arg0` | `int32` |  |
| `GetNumBuildingsUnderConstructionInState` | `Arg0` | `int32` |  |
| `GetNumCombatUnitsAndShips` |  | `int32` |  |
| `GetNumCompanies` |  | `int32` |  |
| `GetNumGovernmentConstructionsInQueue` |  | `int32` |  |
| `GetNumInactiveAndNonShownGovernmentConstructionQueueElements` |  | `int32` |  |
| `GetNumInactiveAndNonShownPrivateConstructionQueueElements` |  | `int32` |  |
| `GetNumInactiveConstructionQueueElements` |  | `int32` |  |
| `GetNumInactiveGovernmentConstructionQueueElements` |  | `int32` |  |
| `GetNumInactivePrivateConstructionQueueElements` |  | `int32` |  |
| `GetNumIncorporatedLiteratePops` |  | `int64` |  |
| `GetNumIncorporatedStates` |  | `int32` |  |
| `GetNumIncorporatedStatesDesc` |  | `CString` |  |
| `GetNumInsufficientTaxCapacityStates` |  | `int32` |  |
| `GetNumInterestGroupMembers` |  | `int64` |  |
| `GetNumIsolatedStates` |  | `int32` |  |
| `GetNumLowMarketAccessStates` |  | `int32` |  |
| `GetNumLoyalists` |  | `int64` |  |
| `GetNumNeutrals` |  | `int64` |  |
| `GetNumPoliticallyInactiveLoyalists` |  | `int64` |  |
| `GetNumPoliticallyInactiveNeutrals` |  | `int64` |  |
| `GetNumPoliticallyInactiveRadicals` |  | `int64` |  |
| `GetNumPreviousAutonomousInvestments` |  | `int32` |  |
| `GetNumPreviousAutonomousPrivateConstructions` |  | `int32` |  |
| `GetNumPreviousAutonomousPrivatizations` |  | `int32` |  |
| `GetNumPrivateConstructionsInQueue` |  | `int32` |  |
| `GetNumRadicals` |  | `int64` |  |
| `GetNumRequiredSupplyShips` |  | `int32` |  |
| `GetNumRequiredSupplyShipsToArmies` |  | `int32` |  |
| `GetNumRequiredSupplyShipsToFleets` |  | `int32` |  |
| `GetNumShips` |  | `int32` |  |
| `GetNumStatesThatCanBeIncorporated` |  | `int32` |  |
| `GetNumStatesWithConstruction` |  | `int32` |  |
| `GetNumStatesWithoutConstruction` |  | `int32` |  |
| `GetNumSupplyShips` |  | `int32` |  |
| `GetNumTotalLiteratePops` |  | `int64` |  |
| `GetNumTurmoilStates` |  | `int32` |  |
| `GetNumUnassignedAdmirals` |  | `int32` |  |
| `GetNumUnassignedGenerals` |  | `int32` |  |
| `GetNumUnincorporatedStates` |  | `int32` |  |
| `GetNumUnincorporatedStatesDesc` |  | `CString` |  |
| `GetNumberOfActiveConscriptionCenters` |  | `int32` |  |
| `GetNumberOfInactiveConscriptionCenters` |  | `int32` |  |
| `GetObjective` |  |  |  |
| `GetObligationFromExpirationDate` | `Arg0` | `CString` |  |
| `GetObligationFromExpirationDesc` | `Arg0` | `CString` |  |
| `GetObligationToExpirationDate` | `Arg0` | `CString` |  |
| `GetObligationToExpirationDesc` | `Arg0` | `CString` |  |
| `GetObligationsOwedFrom` |  |  |  |
| `GetObligationsOwedTo` |  |  |  |
| `GetOppositionInterestGroupsDesc` |  | `CString` |  |
| `GetOppositionInterestGroupsPopulationDesc` |  | `CString` |  |
| `GetOtherPowerBlocWithHighestLeverage` | `Arg0` |  |  |
| `GetOverlord` |  |  |  |
| `GetOwningCompany` |  |  |  |
| `GetPartiesInGovernment` |  |  |  |
| `GetPartiesInOpposition` |  |  |  |
| `GetPeopleAbroad` |  | `int64` |  |
| `GetPiracyIncome` |  | `CFixedPoint` |  |
| `GetPiracyIncomeDesc` |  | `CString` |  |
| `GetPiracyIncomeTrend` |  | `DataTrend` |  |
| `GetPlayedByDesc` |  | `CString` |  |
| `GetPlayer` |  |  |  |
| `GetPoliticalLobbies` |  |  |  |
| `GetPoliticallyInvolvedPercentage` |  | `CFixedPoint` |  |
| `GetPoliticallyInvolvedPopulation` |  | `int64` |  |
| `GetPoliticallyInvolvedPopulationDesc` |  | `CString` |  |
| `GetPollTaxIncome` |  | `CFixedPoint` |  |
| `GetPollTaxTrend` |  | `DataTrend` |  |
| `GetPopConsumptionDependenceOn` | `Arg0` | `CString` |  |
| `GetPopConsumptionDependenceOnDesc` | `Arg0` | `CString` |  |
| `GetPopConsumptionDependenceOnRaw` | `Arg0` | `CFixedPoint` |  |
| `GetPopGrowthDesc` |  | `CString` |  |
| `GetPopReligions` |  |  |  |
| `GetPopulationRanking` |  | `CString` |  |
| `GetPopulationTrend` |  | `DataTrend` |  |
| `GetPortConnectionExpenses` |  | `CFixedPoint` |  |
| `GetPortConnectionExpensesDesc` |  | `CString` |  |
| `GetPotentialCompanies` |  |  |  |
| `GetPotentialDiploPlays` |  |  |  |
| `GetPotentialGeneralDiploActions` |  |  |  |
| `GetPotentialInvestors` |  |  |  |
| `GetPotentialLabor` |  | `int64` |  |
| `GetPotentialOverlordDiploActions` |  |  |  |
| `GetPotentialPowerBlocLeaderDiploActions` |  |  |  |
| `GetPotentialPowerBlocMemberDiploActions` |  |  |  |
| `GetPotentialSubjectDiploActions` |  |  |  |
| `GetPowerBloc` |  |  |  |
| `GetPowerBlocExpenseDesc` |  | `CString` |  |
| `GetPowerBlocExpenseRaw` |  | `CFixedPoint` |  |
| `GetPowerBlocExpenseTrend` |  | `DataTrend` |  |
| `GetPowerBlocIncomeDesc` |  | `CString` |  |
| `GetPowerBlocIncomeRaw` |  | `CFixedPoint` |  |
| `GetPowerBlocIncomeTrend` |  | `DataTrend` |  |
| `GetPowerBlocNonMemberCountryTooltip` |  | `CString` |  |
| `GetPowerBlocWithHighestLeverage` |  |  |  |
| `GetPowerBlocsTotalLeverageShare` |  | `CFixedPoint` |  |
| `GetPowerBlocsWithLeverage` |  |  |  |
| `GetPowerBlocsWithTargetLeverage` |  |  |  |
| `GetPowerDelta` | `Arg0` | `CFixedPoint` |  |
| `GetPowerDeltaIcon` | `Arg0` | `CString` |  |
| `GetPowerExpensesString` | `Arg0` | `CString` |  |
| `GetPowerIncome` | `Arg0` | `CFixedPoint` |  |
| `GetPowerIncomeString` | `Arg0` | `CString` |  |
| `GetPowerTooltip` | `Arg0` | `CString` |  |
| `GetPredictedBalanceFromBankruptcy` |  | `CFixedPoint` |  |
| `GetPrestige` |  | `int32` |  |
| `GetPrestigeDesc` |  | `CString` |  |
| `GetPrestigeForCurrentRank` |  | `int32` |  |
| `GetPrestigeForNextRank` |  | `int32` |  |
| `GetPrestigeGoodsLeaderboardDesc` |  | `CString` |  |
| `GetPrestigeToMaintainRank` |  | `int32` |  |
| `GetPrestigeTrend` |  | `DataTrend` |  |
| `GetPreviousAttitudeTowards` | `Arg0` |  |  |
| `GetPreviousAutonomousInvestmentsDesc` |  | `CString` |  |
| `GetPreviousRank` |  | `CString` |  |
| `GetPriceReportDesc` |  | `CString` |  |
| `GetPrimaryCulturesDesc` |  | `CString` |  |
| `GetPrincipal` |  | `CFixedPoint` |  |
| `GetPrivateConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetPrivateConstructionGoodsExpensesByGoodsDesc` |  | `CString` |  |
| `GetPrivateConstructionQueueDesc` |  | `CString` |  |
| `GetRadicalizationFromBankruptcy` |  | `int64` |  |
| `GetRadicalsChangeSummary` |  | `CString` |  |
| `GetRadicalsDecreaseBreakdown` |  | `CString` |  |
| `GetRadicalsIncreaseBreakdown` |  | `CString` |  |
| `GetRadicalsLoyalistsChangeStartDate` |  | `CString` |  |
| `GetRadicalsSummaryDesc` |  | `CString` |  |
| `GetRadicalsTrend` |  | `DataTrend` |  |
| `GetRank` |  | `CString` |  |
| `GetRankDesc` |  | `CString` |  |
| `GetRankIconIndex` |  | `int32` |  |
| `GetRankModifier` |  |  |  |
| `GetRankNumber` |  | `int32` |  |
| `GetRankProgress` |  | `float` |  |
| `GetRankTooltip` |  | `CString` |  |
| `GetRecentPartiesDesc` |  | `CString` |  |
| `GetRegularBattalions` |  | `int32` |  |
| `GetReinforcementRateArmy` |  | `CFixedPoint` |  |
| `GetReinforcementRateNavy` |  | `CFixedPoint` |  |
| `GetRelationsColor` | `Arg0` | `CVector4f` |  |
| `GetRelationsIconTexture` | `Arg0` |  |  |
| `GetRelationsProgress` | `Arg0` | `CFixedPoint` |  |
| `GetRelationsProgressDesc` | `Arg0` | `CString` |  |
| `GetRelationsTooltip` | `Arg0` | `CString` |  |
| `GetRelationsWith` | `Arg0` | `int32` |  |
| `GetRelationsWithDesc` | `Arg0` | `CString` |  |
| `GetRelativeNavyCombatPower` | `Arg0` | `CFixedPoint` |  |
| `GetRelativePrestige` | `Arg0` | `CFixedPoint` |  |
| `GetRemainingCredit` |  | `CFixedPoint` |  |
| `GetRemainingDaysForFreeGovernmentReformRaw` |  | `int32` |  |
| `GetResearchQueueBottom` |  |  |  |
| `GetResearchQueueTop` |  |  |  |
| `GetRetrofitCost` |  | `CFixedPoint` |  |
| `GetRetrofitCostDesc` |  | `CString` |  |
| `GetRuler` |  |  |  |
| `GetRulingIGsDesc` |  | `CString` |  |
| `GetSOLDescForAllStratas` |  | `CString` |  |
| `GetSalariedWorkingAdults` |  | `int64` |  |
| `GetSeaNodesMightBeConvoyRaidedInDesc` |  | `CString` |  |
| `GetSealAndSignatureTexture` |  |  |  |
| `GetSelectedLaw` |  |  |  |
| `GetShipConstruction` |  | `CFixedPoint` |  |
| `GetShipConstructionDesc` |  | `CString` |  |
| `GetShipConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetShipConstructionGoodsExpensesByGoodsDesc` |  | `CString` |  |
| `GetShipConstructionUsage` |  | `CFixedPoint` |  |
| `GetShipConstructionWeeksLeft` |  | `int32` |  |
| `GetShipList` |  |  |  |
| `GetShipsRanking` |  | `CString` |  |
| `GetSocialHierarchy` |  |  |  |
| `GetSpecialSocialHierarchy` |  |  |  |
| `GetStandardOfLivingRanking` |  | `CString` |  |
| `GetStateOwnedBuildingsBureaucracyCostForLevels` | `Arg0` | `CFixedPoint` |  |
| `GetStateReligion` |  |  |  |
| `GetStatesInTurmoilBreakdown` |  | `CString` |  |
| `GetStatus` | `Arg0` | `CString` |  |
| `GetStrategicObjectives` |  |  |  |
| `GetStrategicRegions` |  |  |  |
| `GetSubjectOrPowerBlocHierarchyLabel` | `Arg0` | `CString` |  |
| `GetSubjectPact` |  |  |  |
| `GetSubjectType` |  |  |  |
| `GetSubjectTypeName` |  | `CString` |  |
| `GetSubjects` |  |  |  |
| `GetSubjectsOfType` | `Arg0` |  |  |
| `GetSubsidiesExpenseTrend` |  | `DataTrend` |  |
| `GetSubsidiesExpenses` |  | `CFixedPoint` |  |
| `GetSubsidiesExpensesDesc` |  | `CString` |  |
| `GetSubsistingWorkingAdults` |  | `int64` |  |
| `GetSubventionsExpenseTrend` |  | `DataTrend` |  |
| `GetSubventionsExpenses` |  | `CFixedPoint` |  |
| `GetSubventionsExpensesDesc` |  | `CString` |  |
| `GetSupplyConstructionCapacity` |  | `CFixedPoint` |  |
| `GetSupplyConstructionQueueCount` |  | `int32` |  |
| `GetSupplyConstructionQueueUsage` |  | `CFixedPoint` |  |
| `GetSupplyConstructionUsageTotal` |  | `CFixedPoint` |  |
| `GetSupplyMaintenanceDemand` |  | `CFixedPoint` |  |
| `GetSupplyMaintenanceDemandDesc` |  | `CString` |  |
| `GetSupplyMaintenanceFulfillment` |  | `CFixedPoint` |  |
| `GetSupplyMaintenanceUsage` |  | `CFixedPoint` |  |
| `GetSupplyNetworkNumSeaNodes` |  | `int32` |  |
| `GetSupplyNetworkNumSeaNodesDesc` |  | `CString` |  |
| `GetSupplyNetworkStrength` |  | `CFixedPoint` |  |
| `GetSupplyNetworkStrengthTarget` |  | `CFixedPoint` |  |
| `GetSupplyNetworkStrengthWeeklyChange` |  | `CFixedPoint` |  |
| `GetSupplyShipConstructionGoodsExpenses` |  | `CFixedPoint` |  |
| `GetSupplyShipConstructionLevelDescHigh` |  | `CString` |  |
| `GetSupplyShipConstructionLevelDescLow` |  | `CString` |  |
| `GetSupplyShipConstructionLevelDescMedium` |  | `CString` |  |
| `GetSupplyShipConstructionLevelDescVeryHigh` |  | `CString` |  |
| `GetSupplyShipConstructionLevelDescVeryLow` |  | `CString` |  |
| `GetSupplyShipMaintenanceExpenses` |  | `CFixedPoint` |  |
| `GetSupplyShipMaintenanceExpensesDesc` |  | `CString` |  |
| `GetSupplyShipsArmiesBreakdown` |  | `CString` |  |
| `GetSupplyShipsFleetsBreakdown` |  | `CString` |  |
| `GetSuppressionCostDesc` |  | `CString` |  |
| `GetSuppressionDesc` |  | `CString` |  |
| `GetTagName` |  | `CString` |  |
| `GetTargetInvolvementDescIn` | `Arg0` | `CString` |  |
| `GetTargetInvolvementIn` | `Arg0` | `CFixedPoint` |  |
| `GetTargetLeverage` | `Arg0` | `CFixedPoint` |  |
| `GetTargetLeverageShare` | `Arg0` | `CFixedPoint` |  |
| `GetTargetRank` |  | `CString` |  |
| `GetTariffTrend` |  | `DataTrend` |  |
| `GetTaxIncomeFor` | `Arg0` | `CFixedPoint` |  |
| `GetTaxIncomeTrend` |  | `DataTrend` |  |
| `GetTaxLevelDescHigh` |  | `CString` |  |
| `GetTaxLevelDescLow` |  | `CString` |  |
| `GetTaxLevelDescMedium` |  | `CString` |  |
| `GetTaxLevelDescVeryHigh` |  | `CString` |  |
| `GetTaxLevelDescVeryLow` |  | `CString` |  |
| `GetTemporaryHostilityEndDate` | `Arg0, Arg1` | `Date` |  |
| `GetTensionIconTexture` | `Arg0` |  |  |
| `GetTensionTooltip` | `Arg0` | `CString` |  |
| `GetTensionWith` | `Arg0` | `int32` |  |
| `GetTensionWithDesc` | `Arg0` | `CString` |  |
| `GetTimeUntilTargetReachedArmy` |  | `CString` |  |
| `GetTimeUntilTargetReachedNavy` |  | `CString` |  |
| `GetTimedModifier` | `Arg0` |  |  |
| `GetTimedModifierDurationRemaining` | `Arg0` | `CString` |  |
| `GetTimedModifiers` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTopOverlord` |  |  |  |
| `GetTotalAgitatorSlots` |  | `int32` |  |
| `GetTotalExpensesTrend` |  | `DataTrend` |  |
| `GetTotalExportedAmount` |  | `CFixedPoint` |  |
| `GetTotalForeignConstructions` |  | `int32` |  |
| `GetTotalGovernmentClout` |  | `CFixedPoint` |  |
| `GetTotalImportedAmount` |  | `CFixedPoint` |  |
| `GetTotalIncomeTrend` |  | `DataTrend` |  |
| `GetTotalLeverageFactors` |  | `CFixedPoint` |  |
| `GetTotalLeverageFactorsBreakdown` |  | `CString` |  |
| `GetTotalLeverageFactorsWithResistance` |  | `CFixedPoint` |  |
| `GetTotalLeverageFactorsWithResistanceBreakdown` |  | `CString` |  |
| `GetTotalLiteracyRanking` |  | `CString` |  |
| `GetTotalLiteracyRate` |  | `CFixedPoint` |  |
| `GetTotalMaintenanceDemand` |  | `CFixedPoint` |  |
| `GetTotalMarginalClout` |  | `CFixedPoint` |  |
| `GetTotalNumLoyalistsChange` |  | `int64` |  |
| `GetTotalNumLoyalistsDecrease` |  | `int64` |  |
| `GetTotalNumLoyalistsIncrease` |  | `int64` |  |
| `GetTotalNumRadicalsChange` |  | `int64` |  |
| `GetTotalNumRadicalsDecrease` |  | `int64` |  |
| `GetTotalNumRadicalsIncrease` |  | `int64` |  |
| `GetTotalOppositionClout` |  | `CFixedPoint` |  |
| `GetTotalPopulation` |  | `int64` |  |
| `GetTotalSupplyShipCount` |  | `int32` |  |
| `GetTotalUrbanization` |  | `int32` |  |
| `GetTravelDistanceToClosestFriendlyPort` | `Arg0` | `CFixedPoint` |  |
| `GetTreatiesBrokenFromNeutralityDesc` | `Arg0` | `CString` |  |
| `GetTreatiesExpenseTrend` |  | `DataTrend` |  |
| `GetTreatiesIncomeTrend` |  | `DataTrend` |  |
| `GetTreatiesWith` | `Arg0` |  |  |
| `GetTreatiesWithDesc` | `Arg0` | `CString` |  |
| `GetTruceDate` | `Arg0` | `CString` |  |
| `GetUnassignedAdmirals` |  |  |  |
| `GetUnassignedGenerals` |  |  |  |
| `GetUnclaimedLeverage` |  | `CFixedPoint` |  |
| `GetUnclaimedLeverageFormatted` |  | `CString` |  |
| `GetUnclaimedLeverageShare` |  | `CFixedPoint` |  |
| `GetUnclaimedLeverageShareTarget` |  | `CFixedPoint` |  |
| `GetUnclaimedLeverageTarget` |  | `CFixedPoint` |  |
| `GetUnemployedWorkingAdults` |  | `int64` |  |
| `GetUnenforcedTreaties` |  |  |  |
| `GetUnenforcedTreatiesWith` | `Arg0` |  |  |
| `GetUnenforcedTreatiesWithDesc` | `Arg0` | `CString` |  |
| `GetUnreachableConstructionFleetsDesc` |  | `CString` |  |
| `GetUnrealizedTaxes` |  | `CFixedPoint` |  |
| `GetUpperStrataPopulationTrend` |  | `DataTrend` |  |
| `GetUsedAgitatorSlots` |  | `int32` |  |
| `GetUsedFreeCharters` |  | `int32` |  |
| `GetWeeklyBalance` |  | `CFixedPoint` |  |
| `GetWeeklyCostArmy` |  | `CFixedPoint` |  |
| `GetWeeklyCostNavy` |  | `CFixedPoint` |  |
| `GetWeeklyExpenses` |  | `CFixedPoint` |  |
| `GetWeeklyFixedExpenses` |  | `CFixedPoint` |  |
| `GetWeeklyGDP` |  | `CFixedPoint` |  |
| `GetWeeklyIncome` |  | `CFixedPoint` |  |
| `GetWeeklyInnovation` |  | `CFixedPoint` |  |
| `GetWeeklyInnovationDesc` |  | `CString` |  |
| `GetWeeklyInterestRate` |  | `CFixedPoint` |  |
| `GetWeeklyLeverageGain` | `Arg0` | `CFixedPoint` |  |
| `GetWeeklyLibertyDesireChange` |  | `CFixedPoint` |  |
| `GetWeeklyLibertyDesireChangeDesc` |  | `CString` |  |
| `GetWeeklyLibertyDesireChangeFromSupportIndependence` |  | `CFixedPoint` |  |
| `GetWeeklyLibertyDesireChangeFromSupportIndependenceDesc` |  | `CString` |  |
| `GetWeeklyMaxInnovation` |  | `CFixedPoint` |  |
| `GetWeeklyMaxInnovationDesc` |  | `CString` |  |
| `GetWeeklyRawInnovation` |  | `CFixedPoint` |  |
| `GetWeeklyResearchSpeed` |  | `CFixedPoint` |  |
| `GetWeeklyResearchSpeedDesc` |  | `CString` |  |
| `GetWeeklyTechnologyProgressDescForTech` | `Arg0` | `CString` |  |
| `GetWeeklyTechnologySpreadBreakdown` |  | `CString` |  |
| `GetWeeklyTechnologySpreadDesc` |  | `CString` |  |
| `GetWeeklyTechnologySpreadForTechDesc` | `Arg0` | `CString` |  |
| `GetWeeklyTemporaryExpenses` |  | `CFixedPoint` |  |
| `GetWeeklyTemporaryIncome` |  | `CFixedPoint` |  |
| `GetWelfarePaymentsExpenses` |  | `CFixedPoint` |  |
| `GetWelfarePaymentsTrend` |  | `DataTrend` |  |
| `GetWorkingAdults` |  | `int64` |  |
| `GetYearlyInterestRate` |  | `CFixedPoint` |  |
| `GetYouOrCountryName` |  | `CString` |  |
| `GetZeroBalancePlotPoints` |  |  |  |
| `GetZeroMoneyPlotPoints` |  |  |  |
| `HasAccessToFriendlyPort` | `Arg0` | `bool` |  |
| `HasActiveDiplomacy` |  | `bool` |  |
| `HasAnyAllianceLikeTreatiesWith` | `Arg0` | `bool` |  |
| `HasAnySlavery` |  | `bool` |  |
| `HasAnyTaxes` |  | `bool` |  |
| `HasConstructionQueued` |  | `bool` |  |
| `HasCurrentlyResearchedTechnology` |  | `bool` |  |
| `HasDecreasingInterests` |  | `bool` |  |
| `HasDefaultConstructionFleet` |  | `bool` |  |
| `HasDiplomaticPactWith` | `Arg0, Arg1` | `bool` |  |
| `HasElectionTrendData` |  | `bool` |  |
| `HasElections` |  | `bool` |  |
| `HasExportSubventionsHigh` | `Arg0` | `bool` |  |
| `HasExportSubventionsLow` | `Arg0` | `bool` |  |
| `HasExportSubventionsMax` | `Arg0` | `bool` |  |
| `HasExportTariffsHigh` | `Arg0` | `bool` |  |
| `HasExportTariffsLow` | `Arg0` | `bool` |  |
| `HasExportTariffsMax` | `Arg0` | `bool` |  |
| `HasExportTariffsNone` | `Arg0` | `bool` |  |
| `HasForeignInvestmentRights` | `Arg0` | `bool` |  |
| `HasGovernmentWages` |  | `bool` |  |
| `HasHeir` |  | `bool` |  |
| `HasHigherUnclaimedLeverage` |  | `bool` |  |
| `HasHigherUnclaimedLeverageTarget` |  | `bool` |  |
| `HasIGApprovalFromLoyalists` |  | `bool` |  |
| `HasIGApprovalFromRadicals` |  | `bool` |  |
| `HasImportSubventionsHigh` | `Arg0` | `bool` |  |
| `HasImportSubventionsLow` | `Arg0` | `bool` |  |
| `HasImportSubventionsMax` | `Arg0` | `bool` |  |
| `HasImportTariffsHigh` | `Arg0` | `bool` |  |
| `HasImportTariffsLow` | `Arg0` | `bool` |  |
| `HasImportTariffsMax` | `Arg0` | `bool` |  |
| `HasImportTariffsNone` | `Arg0` | `bool` |  |
| `HasInsufficientMaxSailors` |  | `bool` |  |
| `HasInterestIn` | `Arg0` | `bool` |  |
| `HasMilitaryWages` |  | `bool` |  |
| `HasNewProductionMethodInGroup` | `Arg0` | `bool` |  |
| `HasNewProductionMethodInSameGroup` | `Arg0, Arg1` | `bool` |  |
| `HasObjective` |  | `bool` |  |
| `HasOverlappingInterestsWith` | `Arg0` | `bool` |  |
| `HasOwningCompany` |  | `bool` |  |
| `HasProgressingLawEnactment` |  | `bool` |  |
| `HasRuler` |  | `bool` |  |
| `HasSelectedLaw` |  | `bool` |  |
| `HasShipConstructionQueued` |  | `bool` |  |
| `HasSpecialSocialHierarchy` |  | `bool` |  |
| `HasSpecialSocialHierarchyLawGroup` | `Arg0` | `bool` |  |
| `HasTimedModifier` | `Arg0` | `bool` |  |
| `InDefault` |  | `bool` |  |
| `IsAI` |  | `bool` |  |
| `IsAIOrOtherPlayer` |  | `bool` |  |
| `IsAlliedInDiploPlayWith` | `Arg0` | `bool` |  |
| `IsAnySubjectOf` | `Arg0` | `bool` |  |
| `IsAtWar` |  | `bool` |  |
| `IsAtWarWith` | `Arg0` | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsBeingTutorialHighlighted` |  | `bool` |  |
| `IsColonizable` |  | `bool` |  |
| `IsCommittedInDiplomaticPlay` |  | `bool` |  |
| `IsConscripting` |  | `bool` |  |
| `IsConstructionPaused` |  | `bool` |  |
| `IsDead` |  | `bool` |  |
| `IsDiplomaticallyRelevantCountry` | `Arg0` | `bool` |  |
| `IsEconomyHealthy` |  | `bool` |  |
| `IsEconomyHealthyDesc` |  | `CString` |  |
| `IsEnactingLaw` |  | `bool` |  |
| `IsHighestRank` |  | `bool` |  |
| `IsIgnoringCountryFormation` | `Arg0` | `bool` |  |
| `IsIgnoringDecision` | `Arg0` | `bool` |  |
| `IsInElectionCampaignPeriod` |  | `bool` |  |
| `IsInPowerBloc` |  | `bool` |  |
| `IsInsurrectionary` |  | `bool` |  |
| `IsInvolvedInActiveConflict` |  | `bool` |  |
| `IsInvolvementDecreasingIn` | `Arg0` | `bool` |  |
| `IsInvolvementIncreasingIn` | `Arg0` | `bool` |  |
| `IsLandlocked` |  | `bool` |  |
| `IsLocalIn` | `Arg0` | `bool` |  |
| `IsLocalPlayer` |  | `bool` |  |
| `IsLowestRank` |  | `bool` |  |
| `IsMobilized` |  | `bool` |  |
| `IsNegotiating` |  | `bool` |  |
| `IsNeighborsWith` | `Arg0` | `bool` |  |
| `IsNewProductionMethod` | `Arg0` | `bool` |  |
| `IsObjectiveIdle` |  | `bool` |  |
| `IsOtherPlayer` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsPlayer` |  | `bool` |  |
| `IsPowerBlocLeader` |  | `bool` |  |
| `IsPowerStruggling` |  | `bool` |  |
| `IsRank` | `Arg0` | `bool` |  |
| `IsRevolutionary` |  | `bool` |  |
| `IsSecessionist` |  | `bool` |  |
| `IsShipConstructionPaused` |  | `bool` |  |
| `IsSubject` |  | `bool` |  |
| `IsSubjectOf` | `Arg0` | `bool` |  |
| `IsTaxingAnyGood` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `LeavePowerBloc` |  | `Command` |  |
| `MatchesSearchQuery` | `Arg0` | `bool` |  |
| `MobilizeAllArmies` |  | `Command` |  |
| `OwesObligationTo` | `Arg0` | `bool` |  |
| `PauseConstruction` |  | `Command` |  |
| `PauseConstructionTooltip` |  | `CString` |  |
| `PauseShipConstruction` |  | `Command` |  |
| `PredictBalanceWithoutTemporaryIncomeAndExpenses` |  | `CFixedPoint` |  |
| `PredictConsumptionTaxes` |  | `CFixedPoint` |  |
| `PredictDiplomaticPactsExpenses` |  | `CFixedPoint` |  |
| `PredictDiplomaticPactsExpensesDesc` |  | `CString` |  |
| `PredictDiplomaticPactsIncome` |  | `CFixedPoint` |  |
| `PredictDiplomaticPactsIncomeDesc` |  | `CString` |  |
| `PredictDividendsTaxes` |  | `CFixedPoint` |  |
| `PredictDividendsTaxesDesc` |  | `CString` |  |
| `PredictEconomyHealthDesc` |  | `CString` |  |
| `PredictGovernmentShareDividends` |  | `CFixedPoint` |  |
| `PredictGovernmentShareDividendsDesc` |  | `CString` |  |
| `PredictGovernmentShareLosses` |  | `CFixedPoint` |  |
| `PredictGovernmentShareLossesDesc` |  | `CString` |  |
| `PredictGovernmentWagesExpenses` |  | `CFixedPoint` |  |
| `PredictMaxWeeklyTechnologyProgressForTech` | `Arg0` | `CFixedPoint` |  |
| `PredictMilitaryWagesExpenses` |  | `CFixedPoint` |  |
| `PredictMinWeeklyTechnologyProgressForTech` | `Arg0` | `CFixedPoint` |  |
| `PredictMinting` |  | `CFixedPoint` |  |
| `PredictMintingDesc` |  | `CString` |  |
| `PredictTariffs` |  | `CFixedPoint` |  |
| `PredictTariffsDesc` |  | `CString` |  |
| `PredictTolls` |  | `CFixedPoint` |  |
| `PredictTollsDesc` |  | `CString` |  |
| `PredictTotalArmyExpenses` |  | `CFixedPoint` |  |
| `PredictTotalMilitaryExpenses` |  | `CFixedPoint` |  |
| `PredictTotalNavyExpenses` |  | `CFixedPoint` |  |
| `PredictTreatyExpenses` |  | `CFixedPoint` |  |
| `PredictTreatyExpensesDesc` |  | `CString` |  |
| `PredictTreatyIncome` |  | `CFixedPoint` |  |
| `PredictTreatyIncomeDesc` |  | `CString` |  |
| `PredictWeeklyBalance` |  | `CFixedPoint` |  |
| `PredictWeeklyBalanceWithEconomyHealthHint` |  | `CString` |  |
| `PredictWeeklyFixedIncome` |  | `CFixedPoint` |  |
| `PredictWeeklyIncome` |  | `CFixedPoint` |  |
| `RemoveCompany` | `Arg0` | `Command` |  |
| `ResumeConstruction` |  | `Command` |  |
| `ResumeConstructionTooltip` |  | `CString` |  |
| `ResumeShipConstruction` |  | `Command` |  |
| `Self` |  |  |  |
| `SetDefaultConstructionFleet` | `Arg0` | `Command` |  |
| `SetExportSubventionsHigh` | `Arg0` | `Command` |  |
| `SetExportSubventionsLow` | `Arg0` | `Command` |  |
| `SetExportSubventionsMax` | `Arg0` | `Command` |  |
| `SetExportTariffsHigh` | `Arg0` | `Command` |  |
| `SetExportTariffsLow` | `Arg0` | `Command` |  |
| `SetExportTariffsMax` | `Arg0` | `Command` |  |
| `SetExportTariffsNone` | `Arg0` | `Command` |  |
| `SetGovernmentWageLevelHigh` |  | `Command` |  |
| `SetGovernmentWageLevelLow` |  | `Command` |  |
| `SetGovernmentWageLevelMedium` |  | `Command` |  |
| `SetGovernmentWageLevelVeryHigh` |  | `Command` |  |
| `SetGovernmentWageLevelVeryLow` |  | `Command` |  |
| `SetImportSubventionsHigh` | `Arg0` | `Command` |  |
| `SetImportSubventionsLow` | `Arg0` | `Command` |  |
| `SetImportSubventionsMax` | `Arg0` | `Command` |  |
| `SetImportTariffsHigh` | `Arg0` | `Command` |  |
| `SetImportTariffsLow` | `Arg0` | `Command` |  |
| `SetImportTariffsMax` | `Arg0` | `Command` |  |
| `SetImportTariffsNone` | `Arg0` | `Command` |  |
| `SetMilitaryWageLevelHigh` |  | `Command` |  |
| `SetMilitaryWageLevelLow` |  | `Command` |  |
| `SetMilitaryWageLevelMedium` |  | `Command` |  |
| `SetMilitaryWageLevelVeryHigh` |  | `Command` |  |
| `SetMilitaryWageLevelVeryLow` |  | `Command` |  |
| `SetSupplyShipConstructionLevelHigh` |  | `Command` |  |
| `SetSupplyShipConstructionLevelLow` |  | `Command` |  |
| `SetSupplyShipConstructionLevelMedium` |  | `Command` |  |
| `SetSupplyShipConstructionLevelVeryHigh` |  | `Command` |  |
| `SetSupplyShipConstructionLevelVeryLow` |  | `Command` |  |
| `SetTaxLevelHigh` |  | `Command` |  |
| `SetTaxLevelLow` |  | `Command` |  |
| `SetTaxLevelMedium` |  | `Command` |  |
| `SetTaxLevelVeryHigh` |  | `Command` |  |
| `SetTaxLevelVeryLow` |  | `Command` |  |
| `ShowInvestmentPoolPredictedNextBuilding` |  | `bool` |  |
| `SortCultures` | `Arg0` | `void` |  |
| `SortInterests` | `Arg0` | `void` |  |
| `SortReligions` | `Arg0` | `void` |  |
| `SortStates` | `Arg0` | `void` |  |
| `SortSubjects` | `Arg0` | `void` |  |
| `StartNegotiationWith` | `Arg0` | `Command` |  |
| `ToggleIgnoreCountryFormation` | `Arg0` | `Command` |  |
| `ToggleIgnoreDecision` | `Arg0` | `Command` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `TryGetOverlordTooltipEntry` |  | `CString` |  |
| `TryGetSubjectsTooltipEntry` |  | `CString` |  |

## CountryCreation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCapital` |  | `StateRegion` |  |
| `GetDefinition` |  | `CountryDefinition` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CanReleaseCountry` | `Arg0` | `bool` |  |
| `CanReleaseCountryAs` | `Arg0, Arg1` | `bool` |  |
| `GetAdjective` |  | `CString` |  |
| `GetCapital` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDefinition` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNumControlledStates` | `Arg0` | `int32` |  |
| `GetNumProvincesToRelease` |  | `int32` |  |
| `GetNumReleasableStates` | `Arg0` | `int32` |  |
| `GetNumRequiredStates` |  | `int32` |  |
| `GetReleaseDesc` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalNumStates` |  | `int32` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsReleasedInSpecificProvinces` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `ListCultures` |  | `CString` |  |
| `ListPotentialReleasableStates` | `Arg0` | `CString` |  |
| `ListPotentialStates` | `Arg0` | `CString` |  |
| `ListReleasableStates` | `Arg0` | `CString` |  |
| `ListReleasableStatesWithoutHomeland` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `ShowRequiredNumStates` | `Arg0` | `bool` |  |

## CountryDefinition

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBaseFlag` |  | `CoatOfArms` |  |
| `GetFlag` | `Arg0` | `CoatOfArms` |  |
| `GetPrimaryCulture` |  | `Culture` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetAdjective` |  | `CString` |  |
| `GetBaseFlag` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFlag` | `Arg0` |  |  |
| `GetName` |  | `CString` |  |
| `GetPrimaryCulture` |  |  |  |
| `GetPrimaryCultureName` |  | `CString` |  |
| `GetTier` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## CountryEntry

Country Entry

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCountry` |  | `CUTF8String` |  |
| `Self` |  |  |  |

## CountryFormation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDefinition` |  | `CountryDefinition` |  |
| `GetSupportedCandidateCountry` | `Arg0` | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessFormationCandidates` |  |  |  |
| `AccessFormationCultureCountries` |  |  |  |
| `AccessFormationStateRegions` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanFormCountry` | `Arg0` | `bool` |  |
| `CanLaunchLeadershipPlay` | `Arg0` | `bool` |  |
| `CanLaunchUnificationPlay` |  | `bool` |  |
| `ControlsStateRegion` | `Arg0, Arg1` | `bool` |  |
| `FormCountry` | `Arg0` | `Command` |  |
| `GetAdjective` |  | `CString` |  |
| `GetControlsStateRegionDesc` | `Arg0, Arg1` | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDefinition` |  |  |  |
| `GetFormDesc` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNumControlledStates` | `Arg0` | `int32` |  |
| `GetNumRequiredStates` |  | `int32` |  |
| `GetNumSupportingCountries` | `Arg0` | `int32` |  |
| `GetSupportCandidateDesc` | `Arg0, Arg1` | `CString` |  |
| `GetSupportForAllCandidatesDesc` | `Arg0` | `CString` |  |
| `GetSupportForCandidateBreakdown` | `Arg0, Arg1` | `CString` |  |
| `GetSupportedCandidateCountry` | `Arg0` |  |  |
| `GetSupportingCountriesDesc` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalNumStates` |  | `int32` |  |
| `GetTriggerLeadershipPlayDesc` | `Arg0, Arg1` | `CString` |  |
| `GetTriggerUnificationPlayDesc` | `Arg0` | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsCandidateForFormation` | `Arg0` | `bool` |  |
| `IsMajorFormation` |  | `bool` |  |
| `IsSupportingAnyCandidate` | `Arg0` | `bool` |  |
| `IsSupportingCandidate` | `Arg0, Arg1` | `bool` |  |
| `ListCultures` |  | `CString` |  |
| `ListRequiredStates` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `ShowLeadershipPlayConfirmation` | `Arg0` | `void` |  |
| `ShowUnificationPlayConfirmation` |  | `void` |  |
| `SupportCandidate` | `Arg0, Arg1` | `Command` |  |

## CountryFormationPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountryFormation` |  | `CountryFormation` |  |
| `GetCountryFormation` |  | `CountryFormation` |  |
| `AccessCountryFormation` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCountryFormation` |  |  |  |
| `Self` |  |  |  |

## CountryMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## CountryPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## CountryTrendPair

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetTrend` |  | `DataTrend` |  |
| `Self` |  |  |  |

## CPdxEnumValue

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AreBundleValuesMixed` |  | `bool` | Only intended to be used with EnumValuesBundles. Indicates whether the bundle contains multiple different values or not |
| `GetDropdownEntries` |  |  |  |
| `GetDropdownValueIndex` |  | `CVector2i` |  |
| `GetValueString` |  | `CString` |  |
| `Self` |  |  |  |
| `SetDropdownValueIndex` |  | `void` |  |

## CPdxFloatRect

Rectangle within an 2D float space.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetRect` |  |  |  |
| `Self` |  |  |  |

## CPdxInputBindingSetting

Jomini Settings - Rebindable Input Binding Setting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## CPdxIntRect

Rectangle within an 2D integer space.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetRect` |  |  |  |
| `Self` |  |  |  |

## CreateAccount

Create Account View

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanCreateAccount` |  | `bool` |  |
| `CreateAccount` |  | `void` |  |
| `GetCountries` |  |  |  |
| `GetDays` |  |  |  |
| `GetEmail` |  | `CUTF8String` |  |
| `GetErrorMessage` |  | `CUTF8String` |  |
| `GetMonths` |  |  |  |
| `GetOptedIntoMarketingChecked` |  | `bool` |  |
| `GetPassword` |  | `CUTF8String` |  |
| `GetSelectedCountryIndex` |  | `CVector2i` |  |
| `GetSelectedDayIndex` |  | `CVector2i` |  |
| `GetSelectedMonthIndex` |  | `CVector2i` |  |
| `GetSelectedYearIndex` |  | `CVector2i` |  |
| `GetYears` |  |  |  |
| `Hide` |  | `void` |  |
| `IsCreatingAccount` |  | `bool` |  |
| `OnCountryChanged` |  | `void` |  |
| `OnDayChanged` |  | `void` |  |
| `OnMonthChanged` |  | `void` |  |
| `OnOptedIntoMarketingToggled` |  | `void` |  |
| `OnYearChanged` |  | `void` |  |
| `Self` |  |  |  |
| `SetEmail` |  | `void` |  |
| `SetPassword` |  | `void` |  |
| `Show` |  | `void` |  |

## CreateSocialProfileWindow

Jomini Social Profile - Create window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Create` |  | `void` |  |
| `GetErrorMessage` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `Hide` |  | `void` |  |
| `IsCreatingProfile` |  | `bool` |  |
| `IsValidName` |  | `bool` |  |
| `Self` |  |  |  |
| `SetName` |  | `void` |  |
| `ShouldBeShown` |  | `bool` |  |
| `Show` |  | `void` |  |

## CreditsWindow

Jomini Credits Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCredits` |  | `CUTF8String` |  |
| `HasReachedEnd` |  | `bool` |  |
| `IsFastest` |  | `bool` |  |
| `IsPaused` |  | `bool` |  |
| `IsSlowest` |  | `bool` |  |
| `OnClose` |  | `void` |  |
| `OnFaster` |  | `void` |  |
| `OnSlower` |  | `void` |  |
| `OnTogglePause` |  | `void` |  |
| `Self` |  |  |  |

## CString

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetString` |  |  |  |
| `Self` |  |  |  |

## CulturalCommunity

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCulture` |  | `Culture` |  |
| `GetState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCulture` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetID` |  | `uint32` |  |
| `GetLocalAcceptanceDifference` |  | `CFixedPoint` |  |
| `GetLocalAcceptanceDifferenceDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## Culture

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessReligion` |  | `Religion` |  |
| `GetHeritageTrait` |  | `DiscriminationTrait` |  |
| `GetLanguageTrait` |  | `DiscriminationTrait` |  |
| `GetReligion` |  | `Religion` |  |
| `GetSampleGlobalLowerStrataPop` |  | `Pop` |  |
| `GetSampleGlobalMiddleStrataPop` |  | `Pop` |  |
| `GetSampleGlobalUpperStrataPop` |  | `Pop` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessHomelands` |  |  |  |
| `AccessReligion` |  |  |  |
| `AccessSameHeritageCultures` |  |  |  |
| `AccessSelf` |  |  |  |
| `CalcAvgSoL` |  | `CFixedPoint` |  |
| `CalcAvgSoLForMiddle` |  | `CFixedPoint` |  |
| `CalcAvgSoLForPoor` |  | `CFixedPoint` |  |
| `CalcAvgSoLForRich` |  | `CFixedPoint` |  |
| `CalcTurmoilInCountry` | `Arg0` | `CFixedPoint` |  |
| `GetAcceptanceDescIn` | `Arg0` | `CString` |  |
| `GetAcceptanceIn` | `Arg0` | `int32` |  |
| `GetAllAcceptanceStatusSegments` | `Arg0` |  |  |
| `GetCasualtiesFromWars` |  | `int64` |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCulturalTraitsDesc` |  | `CString` |  |
| `GetCurrentFervor` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDependents` | `Arg0` | `int64` |  |
| `GetDependentsAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetHeritageTrait` |  |  |  |
| `GetID` |  | `uint32` |  |
| `GetLanguageTrait` |  |  |  |
| `GetMigrationTargetsDesc` |  | `CString` |  |
| `GetMonthlyChangeFervor` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetObsessionsDesc` |  | `CString` |  |
| `GetPolStr` | `Arg0` | `int64` |  |
| `GetPolStrAsFloat` | `Arg0` | `float` |  |
| `GetPolStrAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetPopulation` | `Arg0` | `int64` |  |
| `GetPopulationAsFloat` | `Arg0` | `float` |  |
| `GetPopulationAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetPopulationChange` | `Arg0` | `int64` |  |
| `GetPopulationChangeDesc` | `Arg0` | `CString` |  |
| `GetPopulationInCountryAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `GetReligion` |  |  |  |
| `GetReligionsDesc` |  | `CString` |  |
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
| `GetTargetFervor` |  | `CFixedPoint` |  |
| `GetTargetFervorBreakdown` |  | `CString` |  |
| `GetTargetFervorFromCountryModifiers` |  | `CFixedPoint` |  |
| `GetTargetFervorFromCountryModifiersBreakdown` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTraditionTraits` |  |  |  |
| `GetTurmoil` |  | `CFixedPoint` |  |
| `GetWorkforce` | `Arg0` | `int64` |  |
| `GetWorkforceAsPercentage` | `Arg0` | `CFixedPoint` |  |
| `HasNationalAwakening` |  | `bool` |  |
| `HasSecessionMovement` | `Arg0` | `bool` |  |
| `IsPrimaryCultureIn` | `Arg0` | `bool` |  |
| `IsPrimaryCultureInYesNo` | `Arg0` | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## CultureCasualtyStatistics

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCulture` |  | `Culture` |  |
| `AccessSelf` |  |  |  |
| `GetDead` |  | `int64` |  |
| `GetDemoralized` |  | `int64` |  |
| `GetWounded` |  | `int64` |  |
| `Self` |  |  |  |

## CultureInfoPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCulture` |  | `Culture` |  |
| `AccessPopsList` |  | `PopList` |  |
| `GetCulture` |  | `Culture` |  |
| `AccessCulture` |  |  |  |
| `AccessPops` |  |  |  |
| `AccessPopsList` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCulture` |  |  |  |
| `IsShowingNationalOnly` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleShowNationalOnly` |  | `void` |  |

## CurveEditor

Curve Editor

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Configure` |  | `void` |  |
| `Delete` |  | `void` |  |
| `Self` |  |  |  |

## CurvePoint

Curve Editor - Curve Point

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Position` |  | `CVector2f` |  |
| `Self` |  |  |  |

## CUTF8String

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetString` |  |  |  |
| `Self` |  |  |  |

## CVector2f

Type containing two float numbers.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetVector` |  |  |  |
| `Self` |  |  |  |

## CVector2i

Type containing two integer numbers.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetVector` |  |  |  |
| `Self` |  |  |  |

## CVector3f

Type containing three float numbers.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetVector` |  |  |  |
| `Self` |  |  |  |

## CVector3i

Type containing three integer numbers.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetVector` |  |  |  |
| `Self` |  |  |  |

## CVector4f

Type containing four float numbers.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetVector` |  |  |  |
| `Self` |  |  |  |

## CVector4i

Type containing four integer numbers.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetVector` |  |  |  |
| `Self` |  |  |  |
