# Data-binding types: D

Back to the [index](README.md).

## DataColorPicker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetName` |  | `CString` |  |
| `OnColorEdited` |  | `void` |  |
| `Self` |  |  |  |

## DataDynamicTrend

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## DataTrend

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## DatatypesExplorer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `DumpDataTypes` |  | `bool` | Performs the "dump_data_types" console command. |
| `IsEnableFilterFunctions` |  | `bool` |  |
| `IsEnableFilterMacros` |  | `bool` |  |
| `IsEnableFilterOrphanTypes` |  | `bool` |  |
| `IsEnableFilterPromotes` |  | `bool` |  |
| `IsEnableFilterTypes` |  | `bool` |  |
| `Self` |  |  |  |
| `SetDataTypeFilter` |  | `void` |  |
| `SetNameFilter` |  | `void` |  |
| `ToggleFilterFunctions` |  | `void` |  |
| `ToggleFilterMacros` |  | `void` |  |
| `ToggleFilterOrphanTypes` |  | `void` |  |
| `ToggleFilterPromotes` |  | `void` |  |
| `ToggleFilterTypes` |  | `void` |  |

## Date

Jomini Historical Date

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Format` | `Arg0` | `CString` |  |
| `GetString` |  | `CString` |  |
| `Self` |  |  |  |

## Decision

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffects` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |
| `TakeDecision` | `Arg0` | `Command` |  |

## DecommissionSupplyShipsWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAmount` |  | `int32` |  |
| `GetDecommissionCommand` |  | `Command` |  |
| `GetMaxAmount` |  | `int32` |  |
| `OnAmountEditboxValueChanged` |  | `void` |  |
| `OnAmountSliderValueChanged` |  | `void` |  |
| `Self` |  |  |  |

## Decree

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountry` |  | `Country` |  |
| `GetModifier` |  | `Modifier` |  |
| `GetState` |  | `State` |  |
| `GetType` |  | `DecreeType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCost` |  | `CFixedPoint` |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetRemoveCommand` |  | `Command` |  |
| `GetState` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `Self` |  |  |  |

## DecreeMarker

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessDecree` |  | `Decree` |  |
| `GetDecree` |  | `Decree` |  |
| `AccessDecree` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetDecree` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |

## DecreeType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetModifier` |  | `Modifier` |  |
| `AccessSelf` |  |  |  |
| `GetCostFormatted` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffects` |  | `CString` |  |
| `GetErrors` | `Arg0` | `CString` |  |
| `GetModifier` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetSetCommand` | `Arg0` | `Command` |  |
| `GetTexture` |  |  |  |
| `GetTooltip` | `Arg0` | `CString` |  |
| `GetTooltipForState` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## DefineProxyNodeWindow

Define proxy node window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CUTF8String` |  |
| `Self` |  |  |  |
| `SetName` | `Arg0` | `void` |  |

## DetailData

Map Editor - Map texture details

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `ErrorsCount` |  | `int32` |  |
| `IsUpdating` |  | `bool` |  |
| `MaterialIntensityBias` |  | `float` |  |
| `MaterialsLimit` |  | `int32` |  |
| `Repack` |  | `void` |  |
| `Self` |  |  |  |
| `SetMaterialIntensityBias` | `Arg0` | `void` |  |
| `SetMaterialIntensityBiasStr` |  | `void` |  |
| `SetMaterialsLimit` | `Arg0` | `void` |  |
| `SupportedMaterialsLimits` |  |  |  |

## DiplomaticAction

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessFirstCountry` |  | `Country` |  |
| `AccessFirstState` |  | `State` |  |
| `AccessSecondCountry` |  | `Country` |  |
| `AccessSecondState` |  | `State` |  |
| `GetFirstCountry` |  | `Country` |  |
| `GetFirstState` |  | `State` |  |
| `GetSecondCountry` |  | `Country` |  |
| `GetSecondState` |  | `State` |  |
| `GetType` |  | `DiplomaticActionType` |  |
| `MakeScope` |  | `Scope` |  |
| `AcceptActionProposal` |  | `Command` |  |
| `AccessFirstCountry` |  |  |  |
| `AccessFirstState` |  |  |  |
| `AccessSecondCountry` |  |  |  |
| `AccessSecondState` |  |  |  |
| `AccessSelf` |  |  |  |
| `CanCallInObligation` |  | `bool` |  |
| `CanOweObligation` |  | `bool` |  |
| `CanPotentiallyOweObligation` |  | `bool` |  |
| `DeclineActionProposal` |  | `Command` |  |
| `ExecuteAction` |  | `Command` |  |
| `ExecuteWithConfirmation` |  | `void` |  |
| `GetAcceptanceValue` |  | `int32` |  |
| `GetAcceptanceValueNoObligation` |  | `int32` |  |
| `GetAcceptanceValueWithCallInObligation` |  | `int32` |  |
| `GetAcceptanceValueWithOweObligation` |  | `int32` |  |
| `GetActionAcceptEffectDesc` |  | `CString` |  |
| `GetActionDesc` |  | `CString` |  |
| `GetActionNotificationBreakDesc` |  | `CString` |  |
| `GetActionNotificationBreakName` |  | `CString` |  |
| `GetActionNotificationDesc` |  | `CString` |  |
| `GetActionNotificationName` |  | `CString` |  |
| `GetActionNotificationThirdPartyAcceptedDesc` |  | `CString` |  |
| `GetActionNotificationThirdPartyAcceptedName` |  | `CString` |  |
| `GetActionNotificationThirdPartyBreakAcceptedDesc` |  | `CString` |  |
| `GetActionNotificationThirdPartyBreakAcceptedName` |  | `CString` |  |
| `GetActionNotificationThirdPartyBreakDeclinedDesc` |  | `CString` |  |
| `GetActionNotificationThirdPartyBreakDeclinedName` |  | `CString` |  |
| `GetActionNotificationThirdPartyBreakDesc` |  | `CString` |  |
| `GetActionNotificationThirdPartyBreakName` |  | `CString` |  |
| `GetActionNotificationThirdPartyDeclinedDesc` |  | `CString` |  |
| `GetActionNotificationThirdPartyDeclinedName` |  | `CString` |  |
| `GetActionNotificationThirdPartyDesc` |  | `CString` |  |
| `GetActionNotificationThirdPartyName` |  | `CString` |  |
| `GetAskToBreakName` |  | `CString` |  |
| `GetBaseMaintenanceCost` |  | `CFixedPoint` |  |
| `GetBreakName` |  | `CString` |  |
| `GetCountryInfo` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectsDesc` |  | `CString` |  |
| `GetFirstCountry` |  |  |  |
| `GetFirstState` |  |  |  |
| `GetID` |  | `uint32` |  |
| `GetMaintenanceCost` |  | `CFixedPoint` |  |
| `GetMaintenanceCostDesc` |  | `CString` |  |
| `GetMaintenanceCostForAcceptingCountryDesc` |  | `CString` |  |
| `GetMaintenanceCostFormatted` |  | `CString` |  |
| `GetModifierDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameWithContext` |  | `CString` |  |
| `GetPopupDesc` |  | `CString` |  |
| `GetProposalAcceptedDesc` |  | `CString` |  |
| `GetProposalAcceptedName` |  | `CString` |  |
| `GetProposalBreakAcceptedDesc` |  | `CString` |  |
| `GetProposalBreakAcceptedName` |  | `CString` |  |
| `GetProposalBreakDeclinedDesc` |  | `CString` |  |
| `GetProposalBreakDeclinedName` |  | `CString` |  |
| `GetProposalDeclinedDesc` |  | `CString` |  |
| `GetProposalDeclinedName` |  | `CString` |  |
| `GetProposalNotificationBreakDesc` |  | `CString` |  |
| `GetProposalNotificationBreakName` |  | `CString` |  |
| `GetProposalNotificationDesc` |  | `CString` |  |
| `GetProposalNotificationName` |  | `CString` |  |
| `GetProposeName` |  | `CString` |  |
| `GetRandomAcceptanceChance` |  | `CFixedPoint` |  |
| `GetRandomAcceptanceChanceNoObligation` |  | `CFixedPoint` |  |
| `GetRandomAcceptanceChanceWithCallInObligation` |  | `CFixedPoint` |  |
| `GetRandomAcceptanceChanceWithOweObligation` |  | `CFixedPoint` |  |
| `GetRivalryGains` |  | `CFixedPoint` |  |
| `GetRivalryGainsDetailsDesc` |  | `CString` |  |
| `GetSecondCountry` |  |  |  |
| `GetSecondState` |  |  |  |
| `GetSoundWithConfirmation` |  |  |  |
| `GetTargetStatesDesc` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  |  |  |
| `GetWillAcceptBreakdown` |  | `CString` |  |
| `GetWillAcceptBreakdownNoObligation` |  | `CString` |  |
| `GetWillAcceptBreakdownWithCallInObligation` |  | `CString` |  |
| `GetWillAcceptBreakdownWithOweObligation` |  | `CString` |  |
| `GetWillAcceptDesc` |  | `CString` |  |
| `GetWillAcceptDescNoObligation` |  | `CString` |  |
| `GetWillAcceptDescWithCallInObligation` |  | `CString` |  |
| `GetWillAcceptDescWithOweObligation` |  | `CString` |  |
| `HasIncompleteTargetData` |  | `bool` |  |
| `IsActivePact` |  | `bool` |  |
| `IsCallingInObligation` |  | `bool` |  |
| `IsHostile` |  | `bool` |  |
| `IsHostileToBreak` |  | `bool` |  |
| `IsHostileToPropose` |  | `bool` |  |
| `IsNonActivePact` |  | `bool` |  |
| `IsPersistentPact` |  | `bool` |  |
| `IsPromisingObligation` |  | `bool` |  |
| `IsRivalry` |  | `bool` |  |
| `RequiresApproval` |  | `bool` |  |
| `RequiresApprovalToBreak` |  | `bool` |  |
| `RequiresApprovalToPropose` |  | `bool` |  |
| `RequiresConfirmation` |  | `bool` |  |
| `Self` |  |  |  |
| `ViolatesSovereignty` |  | `bool` |  |
| `WillAIAccept` |  | `bool` |  |
| `WillAIAcceptNoObligation` |  | `bool` |  |
| `WillAIAcceptWithCallInObligation` |  | `bool` |  |
| `WillAIAcceptWithOweObligation` |  | `bool` |  |
| `WillAIMaybeAccept` |  | `bool` |  |
| `WillAIMaybeAcceptNoObligation` |  | `bool` |  |
| `WillAIMaybeAcceptWithCallInObligation` |  | `bool` |  |
| `WillAIMaybeAcceptWithOweObligation` |  | `bool` |  |

## DiplomaticActionType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetFirstModifier` |  | `Modifier` |  |
| `GetModifyPactActionType` |  | `DiplomaticActionType` |  |
| `GetSecondModifier` |  | `Modifier` |  |
| `AccessSelf` |  |  |  |
| `CanSelectAnyState` |  | `bool` |  |
| `CanSelectFirstState` |  | `bool` |  |
| `CanSelectSecondState` |  | `bool` |  |
| `GetBaseMaintenanceCost` |  | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetEffectDescriptionFirst` | `Arg0, Arg1` | `CString` |  |
| `GetEffectDescriptionNoContext` | `Arg0, Arg1` | `CString` |  |
| `GetEffectDescriptionThird` | `Arg0, Arg1` | `CString` |  |
| `GetFirstModifier` |  |  |  |
| `GetIncomeTransfer` |  | `CFixedPoint` |  |
| `GetKey` |  | `CString` |  |
| `GetMaintenanceCost` | `Arg0, Arg1` | `CFixedPoint` |  |
| `GetMaintenanceCostDesc` | `Arg0, Arg1` | `CString` |  |
| `GetMaintenanceCostFormatted` | `Arg0, Arg1` | `CString` |  |
| `GetModifyPactActionType` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameWithCountry` | `Arg0` | `CString` |  |
| `GetSecondModifier` |  |  |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTriggerDescriptionFirst` | `Arg0, Arg1` | `CString` |  |
| `GetTriggerDescriptionFirstNot` | `Arg0, Arg1` | `CString` |  |
| `GetTriggerDescriptionNoContext` | `Arg0, Arg1` | `CString` |  |
| `GetTriggerDescriptionNoContextNot` | `Arg0, Arg1` | `CString` |  |
| `GetTriggerDescriptionThird` | `Arg0, Arg1` | `CString` |  |
| `GetTriggerDescriptionThirdNot` | `Arg0, Arg1` | `CString` |  |
| `HasModifyPact` |  | `bool` |  |
| `HasReversePact` |  | `bool` |  |
| `HasTransferPact` |  | `bool` |  |
| `IsInstantDiplomaticAction` |  | `bool` |  |
| `IsOngoingDiplomaticAction` |  | `bool` |  |
| `IsOngoingDiplomaticPact` |  | `bool` |  |
| `MustSelectFirstState` |  | `bool` |  |
| `MustSelectSecondState` |  | `bool` |  |
| `Self` |  |  |  |

## DiplomaticActionWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessDiplomaticAction` |  | `DiplomaticAction` |  |
| `AccessFirstState` |  | `State` |  |
| `AccessSecondState` |  | `State` |  |
| `AccessStateSelectionTarget` |  | `Country` |  |
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `GetFirstState` |  | `State` |  |
| `GetSecondState` |  | `State` |  |
| `GetStateSelectionTarget` |  | `Country` |  |
| `AccessDiplomaticAction` |  |  |  |
| `AccessFirstState` |  |  |  |
| `AccessPossibleStates` |  |  |  |
| `AccessSecondState` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessStateSelectionTarget` |  |  |  |
| `CanSelectFirstState` |  | `bool` |  |
| `CanSelectSecondState` |  | `bool` |  |
| `ClearFirstState` |  | `void` |  |
| `ClearSecondState` |  | `void` |  |
| `ClearStateSelectionTarget` |  | `void` |  |
| `ExecuteAction` |  | `Command` |  |
| `GetConfirmationSound` |  |  |  |
| `GetConfirmationTooltip` |  | `CString` |  |
| `GetDiplomaticAction` |  |  |  |
| `GetFirstState` |  |  |  |
| `GetSecondState` |  |  |  |
| `GetStateSelectionTarget` |  |  |  |
| `HasStateSelectionTarget` |  | `bool` |  |
| `IsUsingObligation` |  | `bool` |  |
| `SelectState` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetStateSelectionTarget` | `Arg0` | `void` |  |
| `ShowMapNotification` |  | `void` |  |
| `ToggleCallInObligation` |  | `void` |  |
| `ToggleOweObligation` |  | `void` |  |
| `WillCallInObligation` |  | `bool` |  |
| `WillOweObligation` |  | `bool` |  |

## DiplomaticCatalyst

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessDiplomaticCatalystType` |  | `DiplomaticCatalystType` |  |
| `GetCountry` |  | `Country` |  |
| `GetDiplomaticCatalystType` |  | `DiplomaticCatalystType` |  |
| `GetOccuranceDate` |  | `Date` |  |
| `GetTargetCountry` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessDiplomaticCatalystType` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetCountry` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetDiplomaticCatalystType` |  |  |  |
| `GetOccuranceDate` |  |  |  |
| `GetTargetCountry` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |

## DiplomaticCatalystCategory

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCatalystEffectCooldownDays` |  | `int32` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## DiplomaticCatalystType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCategory` |  | `DiplomaticCatalystCategory` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCategory` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDesc` | `Arg0, Arg1` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## DiplomaticDemand

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDemandedWarGoal` |  | `WarGoalDraft` |  |
| `GetDiplomaticPlayType` |  | `DiplomaticPlayType` |  |
| `GetSender` |  | `Country` |  |
| `GetTarget` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AcceptDiplomaticDemand` |  | `Command` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDemandedWarGoal` |  |  |  |
| `GetDiplomaticPlayType` |  |  |  |
| `GetProposalDesc` |  | `CString` |  |
| `GetSender` |  |  |  |
| `GetTarget` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsValid` |  | `bool` |  |
| `RejectDiplomaticDemand` |  | `Command` |  |
| `Self` |  |  |  |

## DiplomaticOverviewPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountriesSearchBar` |  | `SearchBar` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `AccessSelf` |  |  |  |
| `GetCountries` |  |  |  |
| `GetCountriesSearchBar` |  |  |  |
| `IsSorted` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## DiplomaticPact

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetDiplomaticAction` |  | `DiplomaticAction` |  |
| `GetDiplomaticActionType` |  | `DiplomaticActionType` |  |
| `GetFirstCountry` |  | `Country` |  |
| `GetSecondCountry` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetAboutToBreakReasonDesc` |  | `CString` |  |
| `GetAutoBreakReasonDesc` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDailyRelationsProgress` |  | `CFixedPoint` |  |
| `GetDesc` |  | `CString` |  |
| `GetDiplomaticAction` |  |  |  |
| `GetDiplomaticActionType` |  |  |  |
| `GetFirstCountry` |  |  |  |
| `GetID` |  | `uint32` |  |
| `GetName` |  | `CString` |  |
| `GetOutlinerEffectDesc` |  | `CString` |  |
| `GetSecondCountry` |  |  |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasDailyRelationsProgress` |  | `bool` |  |
| `IsFirstCountry` | `Arg0` | `bool` |  |
| `IsSecondCountry` | `Arg0` | `bool` |  |
| `IsSubjectRelation` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowInOutliner` |  | `bool` |  |

## DiplomaticPlay

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessInitiator` |  | `Country` |  |
| `AccessTarget` |  | `Country` |  |
| `AccessWar` |  | `War` |  |
| `GetAcceptedSway` | `Arg0` | `Sway` |  |
| `GetDiplomaticPlayType` |  | `DiplomaticPlayType` |  |
| `GetIncomingSway` | `Arg0, Arg1` | `Sway` |  |
| `GetIncomingSwayByTargetAndSwayer` | `Arg0, Arg1` | `Sway` |  |
| `GetInitiator` |  | `Country` |  |
| `GetInterestMarker` | `Arg0` | `Interest` |  |
| `GetOutgoingSway` | `Arg0, Arg1` | `Sway` |  |
| `GetStrategicRegion` |  | `StrategicRegion` |  |
| `GetTarget` |  | `Country` |  |
| `GetWar` |  | `War` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessExecutedWarGoalsAgainst` | `Arg0` |  |  |
| `AccessInitiator` |  |  |  |
| `AccessInitiatorBackers` |  |  |  |
| `AccessInitiatorBackersNoLoyalSubjects` |  |  |  |
| `AccessInitiatorLeaning` |  |  |  |
| `AccessInitiatorSideCountries` |  |  |  |
| `AccessInitiatorSideCountriesNoLoyalSubjects` |  |  |  |
| `AccessOnTheFence` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTarget` |  |  |  |
| `AccessTargetBackers` |  |  |  |
| `AccessTargetBackersNoLoyalSubjects` |  |  |  |
| `AccessTargetLeaning` |  |  |  |
| `AccessTargetSideCountries` |  |  |  |
| `AccessTargetSideCountriesNoLoyalSubjects` |  |  |  |
| `AccessUndecided` |  |  |  |
| `AccessWar` |  |  |  |
| `AddTreatyWarGoal` | `Arg0, Arg1` | `Command` |  |
| `AddWarGoal` | `Arg0` | `Command` |  |
| `AreOnSameSide` | `Arg0, Arg1` | `bool` |  |
| `AtLeastOneCountryWouldAcceptAnySway` | `Arg0` | `bool` |  |
| `BeOnTheFence` | `Arg0` | `Command` |  |
| `CanAddWarGoal` | `Arg0` | `bool` |  |
| `CanAddWarGoalForOtherCountry` | `Arg0` | `bool` |  |
| `CanBeOnTheFence` | `Arg0` | `bool` |  |
| `CanDeclareNeutrality` | `Arg0` | `bool` |  |
| `CanLeanTowardsInitiator` | `Arg0` | `bool` |  |
| `CanLeanTowardsTarget` | `Arg0` | `bool` |  |
| `CanSupportInitiator` | `Arg0` | `bool` |  |
| `CanSupportTarget` | `Arg0` | `bool` |  |
| `CanSwayCountry` | `Arg0, Arg1` | `bool` |  |
| `CanYield` | `Arg0` | `bool` |  |
| `CreateSway` | `Arg0, Arg1, Arg2` | `Command` |  |
| `DeclareNeutrality` | `Arg0` | `Command` |  |
| `GetAcceptedSway` | `Arg0` |  |  |
| `GetAllWarGoalsOfInitiatorSide` |  |  |  |
| `GetAllWarGoalsOfTargetSide` |  |  |  |
| `GetBeOnTheFenceValidTooltip` | `Arg0` | `CString` |  |
| `GetCanAddWarGoalDesc` | `Arg0` | `CString` |  |
| `GetCanSendSwayOfferDesc` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetCanSwayCountryDesc` | `Arg0, Arg1` | `CString` |  |
| `GetConfidence` | `Arg0` | `int32` |  |
| `GetConfidenceDesc` | `Arg0` | `CString` |  |
| `GetConfidenceLabel` | `Arg0` | `CString` |  |
| `GetCountryCanAddWarGoalDesc` | `Arg0` | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDeclareNeutralityValidTooltip` | `Arg0` | `CString` |  |
| `GetDiplomaticPlayType` |  |  |  |
| `GetEndDate` |  | `CString` |  |
| `GetEnforcedWarGoalsTooltip` |  | `CString` |  |
| `GetEscalation` |  | `int32` |  |
| `GetEscalationPause` |  | `int32` |  |
| `GetEscalationProgress` |  | `CFixedPoint` |  |
| `GetExecutedWarGoalsOfInitiatorSide` |  |  |  |
| `GetExecutedWarGoalsOfTargetSide` |  |  |  |
| `GetIncomingSway` | `Arg0, Arg1` |  |  |
| `GetIncomingSwayByTargetAndSwayer` | `Arg0, Arg1` |  |  |
| `GetInitiator` |  |  |  |
| `GetInitiatorBackersBreakdown` |  | `CString` |  |
| `GetInitiatorPreferenceScore` | `Arg0` | `int32` |  |
| `GetInitiatorPreferenceScoreDesc` | `Arg0` | `CString` |  |
| `GetInitiatorPrimaryWarGoals` |  |  |  |
| `GetInitiatorSecondaryWarGoals` |  |  |  |
| `GetInitiatorSideCasualties` |  | `CFixedPoint` |  |
| `GetInitiatorSideCostOfWar` |  | `CFixedPoint` |  |
| `GetInitiatorSideCostOfWarDesc` |  | `CString` |  |
| `GetInitiatorSideDead` |  | `CFixedPoint` |  |
| `GetInitiatorSideDeadDesc` |  | `CString` |  |
| `GetInitiatorSideWounded` |  | `CFixedPoint` |  |
| `GetInitiatorSideWoundedDesc` |  | `CString` |  |
| `GetInitiatorWarGoals` |  |  |  |
| `GetInterestMarker` | `Arg0` |  |  |
| `GetLeanTowardsInitiatorValidTooltip` | `Arg0` | `CString` |  |
| `GetLeanTowardsTargetValidTooltip` | `Arg0` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNumInitiatorManeuversRemaining` |  | `int32` |  |
| `GetNumLeaningMobilizedBattalionsForSide` | `Arg0` | `int32` |  |
| `GetNumLeaningMobilizedBattalionsForSideBreakdown` | `Arg0` | `CString` |  |
| `GetNumLeaningTotalBattalionsForSide` | `Arg0` | `int32` |  |
| `GetNumLeaningTotalBattalionsForSideBreakdown` | `Arg0` | `CString` |  |
| `GetNumLeaningTotalWarshipsForSide` | `Arg0` | `int32` |  |
| `GetNumLeaningTotalWarshipsForSideBreakdown` | `Arg0` | `CString` |  |
| `GetNumManeuversRemaining` | `Arg0` | `int32` |  |
| `GetNumOnTheFenceBattalionsBreakdown` |  | `CString` |  |
| `GetNumOnTheFenceMobilizedBattalions` |  | `int32` |  |
| `GetNumOnTheFenceTotalBattalions` |  | `int32` |  |
| `GetNumOnTheFenceTotalWarships` |  | `int32` |  |
| `GetNumOnTheFenceWarshipsBreakdown` |  | `CString` |  |
| `GetNumTargetManeuversRemaining` |  | `int32` |  |
| `GetNumberOfPossibleSwayCountriesFormatted` | `Arg0` | `CString` |  |
| `GetOutgoingSway` | `Arg0, Arg1` |  |  |
| `GetPhaseName` |  | `CString` |  |
| `GetPreferenceScoreDesc` | `Arg0` | `CString` |  |
| `GetStartDate` |  | `CString` |  |
| `GetStrategicRegion` |  |  |  |
| `GetSupportInitiatorValidTooltip` | `Arg0` | `CString` |  |
| `GetSupportStanceDesc` | `Arg0` | `CString` |  |
| `GetSupportTargetValidTooltip` | `Arg0` | `CString` |  |
| `GetSwitchSideBreakdown` |  | `CString` |  |
| `GetTarget` |  |  |  |
| `GetTargetBackersBreakdown` |  | `CString` |  |
| `GetTargetPreferenceScore` | `Arg0` | `int32` |  |
| `GetTargetPreferenceScoreDesc` | `Arg0` | `CString` |  |
| `GetTargetPrimaryWarGoals` |  |  |  |
| `GetTargetSecondaryWarGoals` |  |  |  |
| `GetTargetSideCasualties` |  | `CFixedPoint` |  |
| `GetTargetSideCostOfWar` |  | `CFixedPoint` |  |
| `GetTargetSideCostOfWarDesc` |  | `CString` |  |
| `GetTargetSideDead` |  | `CFixedPoint` |  |
| `GetTargetSideDeadDesc` |  | `CString` |  |
| `GetTargetSideWounded` |  | `CFixedPoint` |  |
| `GetTargetSideWoundedDesc` |  | `CString` |  |
| `GetTargetWarGoals` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalNumBattalionsForSide` | `Arg0` | `int32` |  |
| `GetTotalNumMobilizedBattalionsForSide` | `Arg0` | `int32` |  |
| `GetTotalNumMobilizedBattalionsForSideBreakdown` | `Arg0` | `CString` |  |
| `GetTotalNumWarshipsForSide` | `Arg0` | `int32` |  |
| `GetTotalNumWarshipsForSideBreakdown` | `Arg0` | `CString` |  |
| `GetWar` |  |  |  |
| `GetWarDurationString` |  | `CString` |  |
| `GetWarOutcomeString` |  | `CString` |  |
| `GetYieldValidTooltip` | `Arg0` | `CString` |  |
| `HasAcceptedSway` | `Arg0` | `bool` |  |
| `HasAtLeastOneDesiredSwayOfType` | `Arg0, Arg1, Arg2` | `bool` |  |
| `HasAtLeastOneDesiredSwayWargoalOfType` | `Arg0, Arg1, Arg2` | `bool` |  |
| `HasEscalatedIntoWar` |  | `bool` |  |
| `HasExecutedWarGoals` |  | `bool` |  |
| `HasExecutedWarGoalsByCapitulation` |  | `bool` |  |
| `HasExecutedWarGoalsByPeaceDeal` |  | `bool` |  |
| `HasNonExecutedWarGoals` |  | `bool` |  |
| `HasPreferenceForInitiator` | `Arg0` | `bool` |  |
| `HasPreferenceForTarget` | `Arg0` | `bool` |  |
| `IsAmongInitiatorBackers` | `Arg0` | `bool` |  |
| `IsAmongTargetBackers` | `Arg0` | `bool` |  |
| `IsBacker` | `Arg0` | `bool` |  |
| `IsCommittedParticipant` | `Arg0` | `bool` |  |
| `IsInitiator` | `Arg0` | `bool` |  |
| `IsInitiatorBacker` | `Arg0` | `bool` |  |
| `IsInitiatorLeaning` | `Arg0` | `bool` |  |
| `IsInitiatorOrBacker` | `Arg0` | `bool` |  |
| `IsInitiatorVictory` |  | `bool` |  |
| `IsInvolved` | `Arg0` | `bool` |  |
| `IsMixedPeace` |  | `bool` |  |
| `IsOnTheFence` | `Arg0` | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsPrimaryParticipant` | `Arg0` | `bool` |  |
| `IsTarget` | `Arg0` | `bool` |  |
| `IsTargetBacker` | `Arg0` | `bool` |  |
| `IsTargetLeaning` | `Arg0` | `bool` |  |
| `IsTargetOrBacker` | `Arg0` | `bool` |  |
| `IsTargetOrInitiator` | `Arg0` | `bool` |  |
| `IsTargetVictory` |  | `bool` |  |
| `IsUndecidedParticipant` | `Arg0` | `bool` |  |
| `IsValid` |  | `bool` |  |
| `IsValidWarGoalDeclarer` | `Arg0` | `bool` |  |
| `IsWhitePeace` |  | `bool` |  |
| `LeanTowardsInitiator` | `Arg0` | `Command` |  |
| `LeanTowardsTarget` | `Arg0` | `Command` |  |
| `PlayerHasPotentialSwayOffers` | `Arg0` | `bool` |  |
| `Self` |  |  |  |
| `SupportInitiator` | `Arg0` | `Command` |  |
| `SupportTarget` | `Arg0` | `Command` |  |
| `SwitchSide` | `Arg0` | `Command` |  |
| `TogglePinInOutliner` |  | `void` |  |
| `WouldAcceptAnySway` | `Arg0, Arg1` | `bool` |  |
| `Yield` | `Arg0` | `Command` |  |

## DiplomaticPlayConfirmation

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountryDefinition` |  | `CountryDefinition` |  |
| `GetInitiatorCountry` |  | `Country` |  |
| `GetTargetCountry` |  | `Country` |  |
| `GetTargetState` |  | `State` |  |
| `GetType` |  | `DiplomaticPlayType` |  |
| `AccessCountryCreations` |  |  |  |
| `AccessInitiatorCountries` |  |  |  |
| `AccessInvolvedCountries` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTargetCountries` |  |  |  |
| `AccessUndecidedCountries` |  |  |  |
| `CanJoinInitiator` | `Arg0` | `bool` |  |
| `CanJoinTarget` | `Arg0` | `bool` |  |
| `ConfirmAction` |  | `Command` |  |
| `CreateDiplomaticDemand` |  | `Command` |  |
| `GetConfirmationSound` |  |  |  |
| `GetCountryDefinition` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetDiplomaticDemandAcceptanceDesc` |  | `CString` |  |
| `GetInitiatorCountry` |  |  |  |
| `GetTargetCountry` |  |  |  |
| `GetTargetState` |  |  |  |
| `GetType` |  |  |  |
| `IsSelectingCountryCreation` |  | `bool` |  |
| `PredictCannotJoinOrPreferenceForInitiatorDesc` | `Arg0` | `CString` |  |
| `PredictCannotJoinOrPreferenceForTargetDesc` | `Arg0` | `CString` |  |
| `PredictHasPreferenceForInitiator` | `Arg0` | `bool` |  |
| `PredictHasPreferenceForTarget` | `Arg0` | `bool` |  |
| `PredictInitiatorPreferenceScore` | `Arg0` | `int32` |  |
| `PredictInitiatorPreferenceScoreDesc` | `Arg0` | `CString` |  |
| `PredictInitiatorPreferenceScoreFormatted` | `Arg0` | `CString` |  |
| `PredictPreferenceScoreDesc` | `Arg0` | `CString` |  |
| `PredictTargetPreferenceScore` | `Arg0` | `int32` |  |
| `PredictTargetPreferenceScoreDesc` | `Arg0` | `CString` |  |
| `PredictTargetPreferenceScoreFormatted` | `Arg0` | `CString` |  |
| `Self` |  |  |  |
| `SetCountryDefinition` | `Arg0` | `void` |  |
| `ShowMapNotification` |  | `void` |  |
| `ToggleForceDiplomaticPlay` |  | `void` |  |
| `ToggleSelectCountryCreation` |  | `void` |  |
| `TriggerDiplomaticPlay` |  | `Command` |  |
| `WillForceDiplomaticPlay` |  | `bool` |  |

## DiplomaticPlayPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `GetDiplomaticPlay` |  | `DiplomaticPlay` |  |
| `AccessDiplomaticPlay` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetDiplomaticPlay` |  |  |  |
| `Self` |  |  |  |

## DiplomaticPlayType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetWarGoalType` |  | `WarGoalType` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDiplomaticDemandAcceptanceDesc` | `Arg0, Arg1, Arg2, Arg3` | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetSoundWithConfirmation` |  |  |  |
| `GetStartCommandCountry` | `Arg0, Arg1` | `Command` |  |
| `GetStartCommandCountryWithDefinition` | `Arg0, Arg1, Arg2` | `Command` |  |
| `GetStartCommandState` | `Arg0, Arg1` | `Command` |  |
| `GetStartDescCountry` | `Arg0, Arg1` | `CString` |  |
| `GetStartDescCountryWithDefinition` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetStartDescState` | `Arg0, Arg1` | `CString` |  |
| `GetStartTooltipCountry` | `Arg0, Arg1` | `CString` |  |
| `GetStartTooltipCountryWithDefinition` | `Arg0, Arg1, Arg2` | `CString` |  |
| `GetStartTooltipState` | `Arg0, Arg1` | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetWarGoalType` |  |  |  |
| `HasEnableSwitchSides` |  | `bool` |  |
| `IsEpic` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowConfirmationCountry` | `Arg0` | `void` |  |
| `ShowConfirmationCountryWithDefinition` | `Arg0, Arg1` | `void` |  |
| `ShowConfirmationState` | `Arg0` | `void` |  |

## DiplomaticRelations

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetCountryWhichNotOwesObligation` |  | `Country` |  |
| `GetCountryWhichOwesObligation` |  | `Country` |  |
| `GetFirstCountry` |  | `Country` |  |
| `GetSecondCountry` |  | `Country` |  |
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `CalcOwedObligationDaysLeft` | `Arg0` | `int32` |  |
| `GetCountryWhichNotOwesObligation` |  |  |  |
| `GetCountryWhichOwesObligation` |  |  |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetFirstCountry` |  |  |  |
| `GetID` |  | `uint32` |  |
| `GetSecondCountry` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `Self` |  |  |  |

## DiscriminationTrait

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetTraitGroup` |  | `DiscriminationTraitGroup` |  |
| `AccessSelf` |  |  |  |
| `GetCulturesDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetReligionsDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTraitGroup` |  |  |  |
| `GetType` |  | `CString` |  |
| `HasTraitGroup` |  | `bool` |  |
| `IsCulturalTrait` |  | `bool` |  |
| `Self` |  |  |  |

## DiscriminationTraitGroup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCulturesDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetReligionsDesc` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetType` |  | `CString` |  |
| `IsCulturalTrait` |  | `bool` |  |
| `Self` |  |  |  |

## Dlc

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetBanner` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetIcon` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetThemeBreakdown` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `IsEnabled` |  | `bool` |  |
| `IsMajor` |  | `bool` |  |
| `IsThemeProvider` |  | `bool` |  |
| `IsVerified` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowInStore` |  | `void` |  |

## DockableLayout

Dockable Layout Manager - Layout

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## DockableLayoutManager

Dockable Layout Manager Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessActiveLayout` |  | `DockableLayout` |  |
| `AccessLayoutSearchList` |  | `ToolPropertySearchList` |  |
| `AccessSelectedLayout` |  | `DockableLayout` |  |
| `AccessActiveLayout` |  |  |  |
| `AccessLayoutSearchList` |  |  |  |
| `AccessLayouts` |  |  |  |
| `AccessSelectedLayout` |  |  |  |
| `AccessSelf` |  |  |  |
| `DeleteUserLayout` |  | `void` |  |
| `SaveAsNewUserLayout` |  | `void` |  |
| `SaveUserLayout` |  | `void` |  |
| `Self` |  |  |  |
| `SwitchToSelectedLayout` |  | `void` |  |

## DockableWindow

Dockable Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Close` |  | `void` |  |
| `IsHidden` |  | `bool` |  |
| `IsMoving` |  | `bool` |  |
| `Position` |  | `CVector2f` |  |
| `ResizeHandleSize` |  | `CVector2f` |  |
| `Self` |  |  |  |
| `Size` |  | `CVector2f` |  |
| `Title` |  | `CString` |  |
| `WidgetPosition` |  | `CVector2f` |  |
| `WidgetSize` |  | `CVector2f` |  |

## double

Number stored with `double float` precision.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Self` |  |  |  |

## DrawCmdsList

Draw Commands List

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetAttachmentInfo` |  | `CString` |  |
| `GetDrawNumber` |  | `CString` |  |
| `GetFormat` |  | `CString` |  |
| `GetResolution` |  | `CString` |  |
| `GetSize` |  | `uint64` |  |
| `GetTextureName` |  |  |  |
| `GetZoneName` |  | `CString` |  |
| `IsCaptured` |  | `bool` |  |
| `Self` |  |  |  |

## DrawCmdsViewer

Draw Commands Viewer

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CaptureFrame` |  | `void` |  |
| `ClearCapture` |  | `void` |  |
| `DecrementCapturedDrawCount` |  | `void` |  |
| `DecrementCapturedDrawNumberOffset` |  | `void` |  |
| `GetCapturedDrawCount` |  | `uint32` |  |
| `GetCapturedDrawNumberOffset` |  | `uint32` |  |
| `GetCapturedFrameNumber` |  | `uint32` |  |
| `GetDrawCommandData` |  |  |  |
| `IncrementCapturedDrawCount` |  | `void` |  |
| `IncrementCapturedDrawNumberOffset` |  | `void` |  |
| `Self` |  |  |  |
| `SetDrawCount` |  | `void` |  |
| `SetDrawOffset` |  | `void` |  |
