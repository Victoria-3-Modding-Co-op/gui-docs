# Data-binding types: W

Back to the [index](README.md).

## War

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAttackerLeaderParticipant` |  | `WarParticipant` | Access the War Leader for the Attacker (Initiator) side of the War as a WarParticipant |
| `AccessDefenderLeaderParticipant` |  | `WarParticipant` | Access the War Leader for the Defender (Target) side of the War as a WarParticipant |
| `AccessDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `AccessLeftSideLeaderParticipant` |  | `WarParticipant` | Access the War Leader for the (visual-only) Left side of the War as a WarParticipant |
| `AccessParticipant` | `Arg0` | `WarParticipant` |  |
| `AccessRightSideLeaderParticipant` |  | `WarParticipant` | Access the War Leader for the (visual-only) Right side of the War as a WarParticipant |
| `GetAttackerLeader` |  | `Country` |  |
| `GetCountryProposingPeace` |  | `Country` |  |
| `GetDefenderLeader` |  | `Country` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetLeaderOfOppositeSide` | `Arg0` | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessAttackers` |  |  |  |
| `AccessDefenders` |  |  |  |
| `AccessDiplomaticPlay` |  |  |  |
| `AccessFirstWarGoalsForPlayer` |  |  |  |
| `AccessFronts` |  |  |  |
| `AccessSecondWarGoalsForPlayer` |  |  |  |
| `AccessSelf` |  |  |  |
| `AllowsNegotiatedPeace` |  | `bool` |  |
| `Capitulate` | `Arg0` | `Command` |  |
| `GetAcceptActivePeaceDealDesc` |  | `CString` |  |
| `GetAcceptProposedPeaceDealDesc` | `Arg0` | `CString` |  |
| `GetAcceptWhitePeaceDealDesc` |  | `CString` |  |
| `GetActiveBattles` |  |  |  |
| `GetActivePeaceDealAcceptanceScore` | `Arg0` | `CString` |  |
| `GetActivePeaceDealAcceptanceTooltip` | `Arg0` | `CString` |  |
| `GetAllBattles` |  |  |  |
| `GetAttackerLeader` |  |  |  |
| `GetAttackerListString` |  | `CString` |  |
| `GetAttackers` |  |  |  |
| `GetAttackersWarGoals` |  |  |  |
| `GetCapitulationDesire` | `Arg0` | `int32` |  |
| `GetCapitulationDesireDesc` | `Arg0` | `CString` |  |
| `GetCasualties` | `Arg0` | `CFixedPoint` |  |
| `GetCountryProposingPeace` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDaysUntilPeaceDealFails` |  | `int32` |  |
| `GetDefenderLeader` |  |  |  |
| `GetDefenderListString` |  | `CString` |  |
| `GetDefenders` |  |  |  |
| `GetDefendersWarGoals` |  |  |  |
| `GetDiplomaticPlay` |  |  |  |
| `GetEndedBattles` |  |  |  |
| `GetEnemyContestedWarGoalsFraction` | `Arg0` | `CFixedPoint` |  |
| `GetInvasions` |  |  |  |
| `GetLeaderOfOppositeSide` | `Arg0` |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetPeaceDealValidationDesc` |  | `CString` |  |
| `GetPressedWarGoalsString` |  | `CString` |  |
| `GetProposedPeaceDealAcceptanceScore` | `Arg0, Arg1` | `CString` |  |
| `GetProposedPeaceDealAcceptanceTooltip` | `Arg0, Arg1` | `CString` |  |
| `GetSizeWeightedLostBattlesFraction` | `Arg0` | `CFixedPoint` |  |
| `GetStartWarDescriptionForPlayer` |  | `CString` |  |
| `GetStartWarTitleForPlayer` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalDeadWithWarExhaustionTooltip` | `Arg0` | `CString` |  |
| `GetWarPtr` |  |  |  |
| `GetWarSupport` | `Arg0` | `CFixedPoint` |  |
| `GetWhitePeaceDealAcceptanceScore` | `Arg0` | `CString` |  |
| `GetWhitePeaceDealAcceptanceTooltip` | `Arg0` | `CString` |  |
| `HasActivePeaceDeal` |  | `bool` |  |
| `HasActiveWhitePeaceDeal` |  | `bool` |  |
| `HasProposedWhitePeaceDeal` | `Arg0` | `bool` |  |
| `IsAttacker` | `Arg0` | `bool` |  |
| `IsDefender` | `Arg0` | `bool` |  |
| `IsParticipant` | `Arg0` | `bool` |  |
| `IsPeaceDealValid` |  | `bool` |  |
| `IsPeaceNegotiator` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsWarLeader` | `Arg0` | `bool` |  |
| `MustRatifyPeaceDeal` | `Arg0` | `bool` |  |
| `ProposePeaceDeal` | `Arg0` | `Command` |  |
| `Self` |  |  |  |
| `SetWhitePeace` | `Arg0` | `Command` |  |
| `ToggleAcceptPeace` | `Arg0` | `Command` |  |
| `WouldAcceptActivePeaceDeal` | `Arg0` | `bool` |  |
| `WouldAcceptProposedPeaceDeal` | `Arg0, Arg1` | `bool` |  |
| `WouldAcceptWhitePeaceDeal` | `Arg0` | `bool` |  |
| `WouldActivePeaceDealBeAccepted` |  | `bool` |  |
| `WouldProposedPeaceDealBeAccepted` | `Arg0` | `bool` |  |
| `WouldWhitePeaceDealBeAccepted` |  | `bool` |  |

## WarGoal

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArticleDraft` |  | `ArticleDraft` |  |
| `GetArticleType` |  | `ArticleType` |  |
| `GetCountryCreation` |  | `CountryCreation` |  |
| `GetCountryFormation` |  | `CountryFormation` |  |
| `GetCreator` |  | `Country` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetHolder` |  | `Country` |  |
| `GetTarget` |  | `Country` |  |
| `GetTargetState` |  | `State` |  |
| `GetType` |  | `WarGoalType` |  |
| `GetWar` |  | `War` |  |
| `GetWarGoalStakeholder` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CalcMakePrimaryDemandInfamyAmount` |  | `CFixedPoint` |  |
| `CalcMakePrimaryDemandManeuversCost` |  | `int32` |  |
| `GetAddWarGoalDiplomaticIncidentDesc` |  | `CString` |  |
| `GetArticleDraft` |  |  |  |
| `GetArticleType` |  |  |  |
| `GetCountryCreation` |  |  |  |
| `GetCountryFormation` |  |  |  |
| `GetCreator` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetDiplomaticPlay` |  |  |  |
| `GetHolder` |  |  |  |
| `GetIcon` |  |  |  |
| `GetInfamyAmount` |  | `CFixedPoint` |  |
| `GetInfamyDesc` |  | `CString` |  |
| `GetIsContestedDesc` |  | `CString` |  |
| `GetMakePrimaryDemandDiplomaticIncidentDesc` |  | `CString` |  |
| `GetMakePrimaryDemandManeuversCostDesc` |  | `CString` |  |
| `GetManeuversCostToAdd` |  | `int32` |  |
| `GetManeuversCostToAddDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetRegimeChangeLawsEnactedDesc` |  | `CString` |  |
| `GetStartDiploPlayDesc` |  | `CString` |  |
| `GetStatusString` |  | `CString` |  |
| `GetSubjectTypeName` |  | `CString` |  |
| `GetSwayDesc` |  | `CString` |  |
| `GetTarget` |  |  |  |
| `GetTargetState` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `GetWar` |  |  |  |
| `GetWarGoalStakeholder` |  |  |  |
| `HasCountryCreation` |  | `bool` |  |
| `HasCountryFormation` |  | `bool` |  |
| `HoldsArticle` |  | `bool` |  |
| `IsContested` |  | `bool` |  |
| `IsExecuted` |  | `bool` |  |
| `IsExecutedByCapitulation` |  | `bool` |  |
| `IsExecutedByPeaceDeal` |  | `bool` |  |
| `IsPartOfPlay` |  | `bool` |  |
| `IsPartOfWar` |  | `bool` |  |
| `IsPotentialWarGoal` |  | `bool` |  |
| `IsPressedInCurrentPeaceDeal` |  | `bool` |  |
| `IsPressedInPotentialPeaceDeal` | `Arg0` | `bool` |  |
| `IsPressedInShownPeaceDeal` | `Arg0` | `bool` |  |
| `IsPrimaryDemand` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsValidDataContext` |  | `bool` |  |
| `MakeWarGoalPrimaryDemand` | `Arg0` | `Command` |  |
| `Self` |  |  |  |
| `SetArticleInputsFromDraft` | `Arg0` | `void` |  |
| `ShowHighlight` |  | `void` |  |
| `ToggleIsPressedInPotentialPeaceDeal` | `Arg0` | `Command` |  |

## WarGoalDraft

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetArticleDraft` |  | `ArticleDraft` |  |
| `GetArticleType` |  | `ArticleType` |  |
| `GetCountryCreation` |  | `CountryCreation` |  |
| `GetCountryFormation` |  | `CountryFormation` |  |
| `GetCreator` |  | `Country` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetHolder` |  | `Country` |  |
| `GetTarget` |  | `Country` |  |
| `GetTargetRegion` |  | `StrategicRegion` |  |
| `GetTargetState` |  | `State` |  |
| `GetType` |  | `WarGoalType` |  |
| `GetWarGoalStakeholder` |  | `Country` |  |
| `AccessSelf` |  |  |  |
| `GetAddWarGoalDiplomaticIncidentDesc` |  | `CString` |  |
| `GetArticleDraft` |  |  |  |
| `GetArticleType` |  |  |  |
| `GetCountryCreation` |  |  |  |
| `GetCountryFormation` |  |  |  |
| `GetCreator` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetDiplomaticPlay` |  |  |  |
| `GetHolder` |  |  |  |
| `GetIcon` |  |  |  |
| `GetInfamyAmount` |  | `CFixedPoint` |  |
| `GetInfamyDesc` |  | `CString` |  |
| `GetManeuversCostToAdd` |  | `int32` |  |
| `GetManeuversCostToAddDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetRegimeChangeLawsEnactedDesc` |  | `CString` |  |
| `GetSubjectTypeName` |  | `CString` |  |
| `GetTarget` |  |  |  |
| `GetTargetRegion` |  |  |  |
| `GetTargetState` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `GetWarGoalStakeholder` |  |  |  |
| `HasCountryCreation` |  | `bool` |  |
| `HasCountryFormation` |  | `bool` |  |
| `HasIncompleteSelectionData` |  | `bool` |  |
| `HoldsArticle` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsValidDataContext` |  | `bool` |  |
| `Self` |  |  |  |
| `SetArticleInputsFromDraft` | `Arg0` | `void` |  |
| `ShowHighlight` |  | `void` |  |

## WarGoalMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessWarGoal` |  | `WarGoal` |  |
| `GetWarGoal` |  | `WarGoal` |  |
| `AccessSelf` |  |  |  |
| `AccessWarGoal` |  |  |  |
| `GetWarGoal` |  |  |  |
| `Self` |  |  |  |

## WarGoalPanelPair

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessPanel` |  | `WarPanel` |  |
| `AccessWarGoal` |  | `WarGoal` |  |
| `GetWar` |  | `War` |  |
| `GetWarGoal` |  | `WarGoal` |  |
| `AccessSelf` |  |  |  |
| `GetWar` |  |  |  |
| `GetWarGoal` |  |  |  |
| `Self` |  |  |  |

## WarGoalType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetKind` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |
| `TargetsCountryCreation` |  | `bool` |  |

## WarManager

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |
| `ToggleWarPanel` | `Arg0` | `void` |  |

## WarPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessWar` |  | `War` |  |
| `GetLeftLeader` |  | `Country` |  |
| `GetRightLeader` |  | `Country` |  |
| `GetWar` |  | `War` |  |
| `AccessAttackers` |  |  |  |
| `AccessAttackersWarGoals` |  |  |  |
| `AccessDefenders` |  |  |  |
| `AccessDefendersWarGoals` |  |  |  |
| `AccessFronts` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessWar` |  |  |  |
| `GetAttackersAvailableBattalionsRaw` |  | `int32` | Gets the total number of Battalions currently available on the Attacker's (Initiator's) side |
| `GetAttackersDeadRaw` |  | `int64` | Gets the number of Dead casualties so far on the Attacker's (Initiator's) side of the War |
| `GetAttackersMobilizationRatioRaw` |  | `CFixedPoint` | Gets the percentage of Battalions currently (Fully) Mobilized on the Attacker's (Initiator's) side compared to their Available Battalions |
| `GetAttackersMobilizedBattalionsRaw` |  | `int32` | Gets the total number of (Fully) Mobilized Battalions on the Attacker's (Initiator's) side |
| `GetAttackersPotentialBattalionsRaw` |  | `int32` | Gets the potential number of Battalions the Attacker's (Initiator's) side could get if all Conscription Centers were activated and all military buildings were fully employed |
| `GetAttackersShipsRaw` |  | `int32` | Gets the total number of Ships on the Attacker's (Initiator's) side |
| `GetAttackersWarMobilizationCostRaw` |  | `CFixedPoint` | Gets the total Mobilization cost of the War so far on the Attacker's (Initiator's) side of the War |
| `GetAttackersWoundedRaw` |  | `int64` | Gets the number of Wounded casualties so far on the Attacker's (Initiator's) side of the War |
| `GetDefendersAvailableBattalionsRaw` |  | `int32` | Gets the total number of Battalions currently available on the Defender's (Target's) side |
| `GetDefendersDeadRaw` |  | `int64` | Gets the number of Dead casualties so far on the Defender's (Target's) side of the War |
| `GetDefendersMobilizationRatioRaw` |  | `CFixedPoint` | Gets the percentage of Battalions currently (Fully) Mobilized on the Defender's (Target's) side compared to their Available Battalions |
| `GetDefendersMobilizedBattalionsRaw` |  | `int32` | Gets the total number of (Fully) Mobilized Battalions on the Defender's (Target's) side |
| `GetDefendersPotentialBattalionsRaw` |  | `int32` | Gets the potential number of Battalions the Defender's (Target's) side could get if all Conscription Centers were activated and all military buildings were fully employed |
| `GetDefendersShipsRaw` |  | `int32` | Gets the total number of Ships on the Defender's (Target's) side |
| `GetDefendersWarMobilizationCostRaw` |  | `CFixedPoint` | Gets the total Mobilization cost of the War so far on the Defender's (Target's) side of the War |
| `GetDefendersWoundedRaw` |  | `int64` | Gets the number of Wounded casualties so far on the Defender's (Target's) side of the War |
| `GetLeftAvailableBattalionsRaw` |  | `int32` | Gets the total number of Battalions currently available on the Left panel side |
| `GetLeftBattalionsBreakdown` |  | `CString` |  |
| `GetLeftCostOfWarDesc` |  | `CString` | Gets the total Mobilization cost of the War so far on the Left panel side of the War |
| `GetLeftCostOfWarRaw` |  | `CFixedPoint` | Gets the total Mobilization cost of the War so far on the Left panel side of the War |
| `GetLeftDeadBreakdown` |  | `CString` | Gets the breakdown for the total number of Dead casualties so far on the Left panel side of the War |
| `GetLeftDeadRaw` |  | `int64` | Gets the number of Dead casualties so far on the Left panel side of the War |
| `GetLeftLeader` |  |  |  |
| `GetLeftMobilizationRatioRaw` |  | `CFixedPoint` | Gets the percentage of Battalions currently (Fully) Mobilized on the Left panel side compared to their Available Battalions |
| `GetLeftMobilizedBattalionsRaw` |  | `int32` | Gets the total number of (Fully) Mobilized Battalions on the Left panel side |
| `GetLeftPotentialBattalionsRaw` |  | `int32` | Gets the potential number of Battalions the Left panel side could get if all Conscription Centers were activated and all military buildings were fully employed |
| `GetLeftShipsBreakdown` |  | `CString` |  |
| `GetLeftShipsRaw` |  | `int32` | Gets the total number of Ships on the Left panel side |
| `GetLeftWarParticipantsExcludingLeader` |  |  |  |
| `GetLeftWoundedBreakdown` |  | `CString` | Gets the breakdown for the total number of Wounded casualties so far on the Left panel side of the War |
| `GetLeftWoundedRaw` |  | `int64` | Gets the number of Wounded casualties so far on the Left panel side of the War |
| `GetRightAvailableBattalionsRaw` |  | `int32` | Gets the total number of Battalions currently available on the Right panel side |
| `GetRightBattalionsBreakdown` |  | `CString` |  |
| `GetRightCostOfWarDesc` |  | `CString` | Gets the total Mobilization cost of the War so far on the Right panel side of the War |
| `GetRightCostOfWarRaw` |  | `CFixedPoint` | Gets the total Mobilization cost of the War so far on the Right panel side of the War |
| `GetRightDeadBreakdown` |  | `CString` | Gets the breakdown for the total number of Dead casualties so far on the Right panel side of the War |
| `GetRightDeadRaw` |  | `int64` | Gets the number of Dead casualties so far on the Right panel side of the War |
| `GetRightLeader` |  |  |  |
| `GetRightMobilizationRatioRaw` |  | `CFixedPoint` | Gets the percentage of Battalions currently (Fully) Mobilized on the Right panel side compared to their Available Battalions |
| `GetRightMobilizedBattalionsRaw` |  | `int32` | Gets the total number of (Fully) Mobilized Battalions on the Right panel side |
| `GetRightPotentialBattalionsRaw` |  | `int32` | Gets the potential number of Battalions the Right panel side could get if all Conscription Centers were activated and all military buildings were fully employed |
| `GetRightShipsBreakdown` |  | `CString` |  |
| `GetRightShipsRaw` |  | `int32` | Gets the total number of Ships on the Right panel side |
| `GetRightWarParticipantsExcludingLeader` |  |  |  |
| `GetRightWoundedBreakdown` |  | `CString` | Gets the breakdown for the total number of Wounded casualties so far on the Left panel side of the War |
| `GetRightWoundedRaw` |  | `int64` | Gets the number of Wounded casualties so far on the Right panel side of the War |
| `GetWar` |  |  |  |
| `IsShowingPeaceDeal` |  | `bool` |  |
| `Self` |  |  |  |
| `SortFronts` | `Arg0` | `void` | Sorts the list of Fronts in the War on the specified key string (possible: advantage) |
| `ToggleShowPeaceDeal` |  | `void` |  |

## WarParticipant

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessCountry` |  | `Country` |  |
| `GetCountry` |  | `Country` |  |
| `GetWar` |  | `War` |  |
| `AccessSelf` |  |  |  |
| `GetCanCapitulateDesc` |  | `CString` |  |
| `GetCasualties` |  | `int64` |  |
| `GetCountry` |  |  |  |
| `GetExhaustionDesc` |  | `CString` |  |
| `GetNumDead` |  | `int64` |  |
| `GetNumDeadFromAttrition` |  | `int64` |  |
| `GetNumDeadFromBattle` |  | `int64` |  |
| `GetNumWounded` |  | `int64` |  |
| `GetNumWoundedFromAttrition` |  | `int64` |  |
| `GetNumWoundedFromBattle` |  | `int64` |  |
| `GetPosition` | `Arg0, Arg1, Arg2` | `CVector2f` |  |
| `GetWar` |  |  |  |
| `GetWarExhaustionFromAcceptanceOfDeadDesc` |  | `CString` |  |
| `GetWarSupportDesc` |  | `CString` |  |
| `GetWarSupportDescDelayed` |  | `CString` |  |
| `IsPeaceNegotiator` |  | `bool` |  |
| `IsWarLeader` |  | `bool` |  |
| `MustRatifyPeaceDeal` |  | `bool` |  |
| `Self` |  |  |  |
| `WouldAcceptActivePeaceDeal` |  | `bool` |  |
| `WouldAcceptProposedPeaceDeal` | `Arg0` | `bool` |  |
| `WouldAcceptWhitePeaceDeal` |  | `bool` |  |

## WorldMarketPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Filter` | `Arg0` | `void` |  |
| `GetFilters` |  |  |  |
| `GetGoods` | `Arg0` |  |  |
| `GetMarkets` |  |  |  |
| `GetMarketsSortedOnExports` |  |  |  |
| `GetMarketsSortedOnImports` |  |  |  |
| `GetMaxImbalance` |  | `CFixedPoint` |  |
| `GetMaxImbalanceScaledByBasePrice` |  | `CFixedPoint` |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SortGoods` | `Arg0` | `void` |  |
| `SortMarkets` | `Arg0` | `void` |  |
