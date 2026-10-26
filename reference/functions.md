# Data-binding functions

These **1,867 functions** can be called inside a `[ ... ]` expression in any `.gui` file. A function with arguments uses parentheses and comma-separated values; a function without arguments is written bare or with `()`.

The interface layer documents only a small part of them. Functions without a description are listed at the end of their group so they stay searchable without drowning the page.

## Index

- [General](#general) - 1843 functions
- [Jomini Achievements](#jomini-achievements) - 2 functions
- [Jomini Script Systen](#jomini-script-systen) - 1 functions
- [Map Editor](#map-editor) - 5 functions
- [Multiplayer](#multiplayer) - 6 functions
- [Multiplayer GUI](#multiplayer-gui) - 4 functions
- [Portrait System](#portrait-system) - 1 functions
- [Settings](#settings) - 5 functions
- [Macros](#macros) - 14
- [Global getters](#global-getters) - 471

## General

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `And` | `Arg0, Arg1` | `bool` | If both arguments are true |
| `And3` | `Arg0, Arg1, Arg2` | `bool` | If all 3 arguments are true |
| `And4` | `Arg0, Arg1, Arg2, Arg3` | `bool` | If all 4 arguments are true |
| `And5` | `Arg0, Arg1, Arg2, Arg3, Arg4` | `bool` | If all 5 arguments are true |
| `And6` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5` | `bool` | If all 6 arguments are true |
| `And7` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5, Arg6` | `bool` | If all 7 arguments are true |
| `And8` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5, Arg6, Arg7` | `bool` | If all 8 arguments are true |
| `AndEvalAll` | `Arg0, Arg1` | `bool` | Evaluates all arguments and then checks if both arguments are true. Using 'And' is preferred. |
| `BindFoldOutContext` |  | `void` | Add a new PdxGuiFoldOut data context to a widget. |
| `CurrentAndMaxToProgressbarValueInt32` | `Arg0, Arg1` | `float` | Get the progress (0.0-100.0) of CurrentArg to MaxArg. Value is clamped between 0 and 100. |
| `DataModelRepeatedItem` | `Arg0` | `[unregistered]` | The data function used for mocking empty list items, requires int32 (number of items) as a parameter. Example: datamodel = [RepeatedItem( '(int32)4' )] |
| `ExecuteConsoleCommand` | `Arg0` | `void` | Execute a single console command with a given command. |
| `ExecuteConsoleCommands` | `Arg0` | `void` | Execute a sequence of console commands split by ';'. And stops the sequence execution if a console command fails. |
| `ExecuteConsoleCommandsForced` | `Arg0` | `void` | Execute a sequence of console commands split by ';'. Keeps the sequence execution even if a console command fails. |
| `FixedPointToProgressbarValue` | `Arg0` | `float` | Convert to a progress percentage value (by multiplying with 100, unclamped). |
| `GfxGetSkins` |  | `[unregistered]` | Get all skins |
| `GfxSetActiveSkin` | `Arg0` | `void` | Set the active GFX skin |
| `GfxSkinIsActive` | `Arg0` | `bool` | Test if skin is active |
| `InDebugMode` |  | `bool` | Is the game in Debug mode? |
| `InReleaseMode` |  | `bool` | Is the game in Release mode? |
| `IntToFrameIndex` | `Arg0` | `int32` | Adds 1 to Arg1. |
| `NOP` |  | `void` | No Operation (dummy callback function) |
| `Not` | `Arg0` | `bool` | If the argument is not true |
| `OnCreateAccount` |  | `void` | Start the account creation flow |
| `Or` | `Arg0, Arg1` | `bool` | If either argument is true |
| `Or3` | `Arg0, Arg1, Arg2` | `bool` | If any of 3 arguments are true |
| `Or4` | `Arg0, Arg1, Arg2, Arg3` | `bool` | If any of 4 arguments are true |
| `Or5` | `Arg0, Arg1, Arg2, Arg3, Arg4` | `bool` | If any of 5 arguments are true |
| `Or6` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5` | `bool` | If any of 6 arguments are true |
| `Or7` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5, Arg6` | `bool` | If any of 7 arguments are true |
| `Or8` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5, Arg6, Arg7` | `bool` | If any of 8 arguments are true |
| `OrEvalAll` | `Arg0, Arg1` | `bool` | Evaluates all arguments and then checks if either argument is true. Using 'Or' is preferred. |
| `PdxGuiDestroyWidget` | `Arg0` | `void` | Destroy widget |
| `Unfocus` | `Arg0` | `void` | Unfocus widget |

_1809 further function(s) in this group, without a description._

| Function | Arguments | Returns |
|---|---|---|
| `Abs_CFixedPoint` | `Arg0` | `CFixedPoint` |
| `Abs_float` | `Arg0` | `float` |
| `Abs_int32` | `Arg0` | `int32` |
| `Abs_int64` | `Arg0` | `int64` |
| `AccessConstructionSpeeds` |  | `[unregistered]` |
| `AccessMetaPlayer` |  | `[unregistered]` |
| `AccessPlayer` |  | `[unregistered]` |
| `AccessScopeReference` | `Arg0` | `[unregistered]` |
| `Add_CFixedPoint` | `Arg0, Arg1` | `CFixedPoint` |
| `Add_CVector2f` | `Arg0, Arg1` | `CVector2f` |
| `Add_float` | `Arg0, Arg1` | `float` |
| `Add_int32` | `Arg0, Arg1` | `int32` |
| `Add_int64` | `Arg0, Arg1` | `int64` |
| `Add_uint32` | `Arg0, Arg1` | `uint32` |
| `Add_uint64` | `Arg0, Arg1` | `uint64` |
| `AddLocalizationIf` | `Arg0, Arg1` | `CString` |
| `AddTextIf` | `Arg0, Arg1` | `CString` |
| `AreAchievementsAvailable` |  | `bool` |
| `Between_CFixedPoint` | `Arg0, Arg1, Arg2` | `bool` |
| `Between_float` | `Arg0, Arg1, Arg2` | `bool` |
| `Between_int32` | `Arg0, Arg1, Arg2` | `bool` |
| `Between_int64` | `Arg0, Arg1, Arg2` | `bool` |
| `Between_uint32` | `Arg0, Arg1, Arg2` | `bool` |
| `Between_uint64` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusive_CFixedPoint` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusive_float` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusive_int32` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusive_int64` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusive_uint32` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusive_uint64` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMax_CFixedPoint` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMax_float` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMax_int32` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMax_int64` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMax_uint32` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMax_uint64` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMin_CFixedPoint` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMin_float` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMin_int32` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMin_int64` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMin_uint32` | `Arg0, Arg1, Arg2` | `bool` |
| `BetweenInclusiveOfMin_uint64` | `Arg0, Arg1, Arg2` | `bool` |
| `BoolTo1And2` | `Arg0` | `int32` |
| `BoolTo2And1` | `Arg0` | `int32` |
| `CalcDynTrendLatestDate` | `Arg0` | `CString` |
| `CalcDynTrendOldestDate` | `Arg0` | `CString` |
| `CancelRetrofitShips` |  | `Command` |
| `CanEditSeaRegionsForSelectedFleets` |  | `bool` |
| `CanGetAchievements` |  | `bool` |
| `CanOpenLobby` |  | `bool` |
| `CanOpenRightClickContextMenu` |  | `bool` |
| `ChangeAllConstructionSpeed` | `Arg0` | `Command` |
| `ChangeAllConstructionSpeedTooltip` | `Arg0` | `CString` |
| `ClearDefaultMapMode` |  | `void` |
| `ClearDynamicTerrainOverrideForAllProvinces` |  | `void` |
| `CloseAllTooltips` |  | `void` |
| `ColorToVector3f` | `Arg0` | `CVector3f` |
| `ColorToVector3i` | `Arg0` | `CVector3i` |
| `ColorToVector4i` | `Arg0` | `CVector4i` |
| `Concatenate` | `Arg0, Arg1` | `CString` |
| `Concatenate3` | `Arg0, Arg1, Arg2` | `CString` |
| `Concatenate4` | `Arg0, Arg1, Arg2, Arg3` | `CString` |
| `Concatenate5` | `Arg0, Arg1, Arg2, Arg3, Arg4` | `CString` |
| `Concatenate6` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5` | `CString` |
| `Concatenate7` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5, Arg6` | `CString` |
| `Concatenate8` | `Arg0, Arg1, Arg2, Arg3, Arg4, Arg5, Arg6, Arg7` | `CString` |
| `ConcatIfNeitherEmpty` | `Arg0, Arg1` | `CString` |
| `Concept` | `Arg0, Arg1` | `CString` |
| `concept_acceptance` |  | `[unregistered]` |
| `concept_acceptance_desc` |  | `[unregistered]` |
| `concept_acceptance_status` |  | `[unregistered]` |
| `concept_acceptance_status_desc` |  | `[unregistered]` |
| `concept_accepted_culture` |  | `[unregistered]` |
| `concept_accepted_culture_desc` |  | `[unregistered]` |
| `concept_accepted_religion` |  | `[unregistered]` |
| `concept_accepted_religion_desc` |  | `[unregistered]` |
| `concept_accuracy` |  | `[unregistered]` |
| `concept_accuracy_desc` |  | `[unregistered]` |
| `concept_activism` |  | `[unregistered]` |
| `concept_activism_desc` |  | `[unregistered]` |
| `concept_admiral` |  | `[unregistered]` |
| `concept_admiral_defeated` |  | `[unregistered]` |
| `concept_admiral_defeated_desc` |  | `[unregistered]` |
| `concept_admiral_desc` |  | `[unregistered]` |
| `concept_advance_factor` |  | `[unregistered]` |
| `concept_advance_factor_desc` |  | `[unregistered]` |
| `concept_advancement_progress` |  | `[unregistered]` |
| `concept_advancement_progress_desc` |  | `[unregistered]` |
| `concept_advancement_speed` |  | `[unregistered]` |
| `concept_advancement_speed_desc` |  | `[unregistered]` |
| `concept_agitator` |  | `[unregistered]` |
| `concept_agitator_desc` |  | `[unregistered]` |
| `concept_ai_strategy` |  | `[unregistered]` |
| `concept_ai_strategy_desc` |  | `[unregistered]` |
| `concept_alert_settings_alert` |  | `[unregistered]` |
| `concept_alert_settings_alert_desc` |  | `[unregistered]` |
| `concept_alert_settings_angry_important_action` |  | `[unregistered]` |
| `concept_alert_settings_angry_important_action_desc` |  | `[unregistered]` |
| `concept_alert_settings_important_action` |  | `[unregistered]` |
| `concept_alert_settings_important_action_desc` |  | `[unregistered]` |
| `concept_alert_settings_none` |  | `[unregistered]` |
| `concept_alert_settings_none_desc` |  | `[unregistered]` |
| `concept_alliance` |  | `[unregistered]` |
| `concept_alliance_desc` |  | `[unregistered]` |
| `concept_ally` |  | `[unregistered]` |
| `concept_ally_desc` |  | `[unregistered]` |
| `concept_amenability` |  | `[unregistered]` |
| `concept_amenability_desc` |  | `[unregistered]` |
| `concept_amendment` |  | `[unregistered]` |
| `concept_amendment_desc` |  | `[unregistered]` |
| `concept_amendment_repeal` |  | `[unregistered]` |
| `concept_amendment_repeal_desc` |  | `[unregistered]` |
| `concept_approval` |  | `[unregistered]` |
| `concept_approval_desc` |  | `[unregistered]` |
| `concept_arable_land` |  | `[unregistered]` |
| `concept_arable_land_desc` |  | `[unregistered]` |
| `concept_army` |  | `[unregistered]` |
| `concept_army_desc` |  | `[unregistered]` |
| `concept_army_power_projection` |  | `[unregistered]` |
| `concept_army_power_projection_desc` |  | `[unregistered]` |
| `concept_article` |  | `[unregistered]` |
| `concept_article_desc` |  | `[unregistered]` |
| `concept_assimilation` |  | `[unregistered]` |
| `concept_assimilation_desc` |  | `[unregistered]` |
| `concept_attack_damage` |  | `[unregistered]` |
| `concept_attack_damage_desc` |  | `[unregistered]` |
| `concept_attitude` |  | `[unregistered]` |
| `concept_attitude_desc` |  | `[unregistered]` |
| `concept_attrition` |  | `[unregistered]` |
| `concept_attrition_desc` |  | `[unregistered]` |
| `concept_austrian_constitutional_pressure` |  | `[unregistered]` |
| `concept_austrian_constitutional_pressure_desc` |  | `[unregistered]` |
| `concept_authority` |  | `[unregistered]` |
| `concept_authority_desc` |  | `[unregistered]` |
| `concept_autonomy` |  | `[unregistered]` |
| `concept_autonomy_desc` |  | `[unregistered]` |
| `concept_available_battalions` |  | `[unregistered]` |
| `concept_available_battalions_desc` |  | `[unregistered]` |
| `concept_average_wage` |  | `[unregistered]` |
| `concept_average_wage_desc` |  | `[unregistered]` |
| `concept_balkan_culture` |  | `[unregistered]` |
| `concept_balkan_culture_desc` |  | `[unregistered]` |
| `concept_bankroll` |  | `[unregistered]` |
| `concept_bankroll_desc` |  | `[unregistered]` |
| `concept_bankruptcy` |  | `[unregistered]` |
| `concept_bankruptcy_desc` |  | `[unregistered]` |
| `concept_base_price` |  | `[unregistered]` |
| `concept_base_price_desc` |  | `[unregistered]` |
| `concept_base_success_chance` |  | `[unregistered]` |
| `concept_base_success_chance_desc` |  | `[unregistered]` |
| `concept_base_template` |  | `[unregistered]` |
| `concept_base_template_desc` |  | `[unregistered]` |
| `concept_battalion` |  | `[unregistered]` |
| `concept_battalion_desc` |  | `[unregistered]` |
| `concept_battle` |  | `[unregistered]` |
| `concept_battle_condition` |  | `[unregistered]` |
| `concept_battle_condition_desc` |  | `[unregistered]` |
| `concept_battle_desc` |  | `[unregistered]` |
| `concept_bavarocratic_ire` |  | `[unregistered]` |
| `concept_bavarocratic_ire_desc` |  | `[unregistered]` |
| `concept_binding_period` |  | `[unregistered]` |
| `concept_binding_period_desc` |  | `[unregistered]` |
| `concept_bio_tomas_de_zumalacarregui` |  | `[unregistered]` |
| `concept_bio_tomas_de_zumalacarregui_desc` |  | `[unregistered]` |
| `concept_bloc_leader_action` |  | `[unregistered]` |
| `concept_bloc_leader_action_desc` |  | `[unregistered]` |
| `concept_bloc_member_action` |  | `[unregistered]` |
| `concept_bloc_member_action_desc` |  | `[unregistered]` |
| `concept_blockade` |  | `[unregistered]` |
| `concept_blockade_desc` |  | `[unregistered]` |
| `concept_blockade_efficiency` |  | `[unregistered]` |
| `concept_blockade_efficiency_desc` |  | `[unregistered]` |
| `concept_blockade_resistance` |  | `[unregistered]` |
| `concept_blockade_resistance_desc` |  | `[unregistered]` |
| `concept_blockade_strength` |  | `[unregistered]` |
| `concept_blockade_strength_desc` |  | `[unregistered]` |
| `concept_boddhisattva` |  | `[unregistered]` |
| `concept_boddhisattva_desc` |  | `[unregistered]` |
| `concept_bolster` |  | `[unregistered]` |
| `concept_bolster_desc` |  | `[unregistered]` |
| `concept_brz_national_hero` |  | `[unregistered]` |
| `concept_brz_national_hero_desc` |  | `[unregistered]` |
| `concept_budget_additional_expenses` |  | `[unregistered]` |
| `concept_budget_additional_expenses_desc` |  | `[unregistered]` |
| `concept_budget_additional_income` |  | `[unregistered]` |
| `concept_budget_additional_income_desc` |  | `[unregistered]` |
| `concept_budget_construction_goods` |  | `[unregistered]` |
| `concept_budget_construction_goods_desc` |  | `[unregistered]` |
| `concept_budget_consumption_taxes` |  | `[unregistered]` |
| `concept_budget_consumption_taxes_desc` |  | `[unregistered]` |
| `concept_budget_diplomatic_pacts` |  | `[unregistered]` |
| `concept_budget_diplomatic_pacts_desc` |  | `[unregistered]` |
| `concept_budget_dividends_taxes` |  | `[unregistered]` |
| `concept_budget_dividends_taxes_desc` |  | `[unregistered]` |
| `concept_budget_goods_for_government_buildings` |  | `[unregistered]` |
| `concept_budget_goods_for_government_buildings_desc` |  | `[unregistered]` |
| `concept_budget_goods_for_military_upkeep` |  | `[unregistered]` |
| `concept_budget_goods_for_military_upkeep_desc` |  | `[unregistered]` |
| `concept_budget_government_slaves` |  | `[unregistered]` |
| `concept_budget_government_slaves_desc` |  | `[unregistered]` |
| `concept_budget_government_wages` |  | `[unregistered]` |
| `concept_budget_government_wages_desc` |  | `[unregistered]` |
| `concept_budget_heathen_taxes` |  | `[unregistered]` |
| `concept_budget_heathen_taxes_desc` |  | `[unregistered]` |
| `concept_budget_income_taxes` |  | `[unregistered]` |
| `concept_budget_income_taxes_desc` |  | `[unregistered]` |
| `concept_budget_interest` |  | `[unregistered]` |
| `concept_budget_interest_desc` |  | `[unregistered]` |
| `concept_budget_investment_income` |  | `[unregistered]` |
| `concept_budget_investment_income_desc` |  | `[unregistered]` |
| `concept_budget_land_taxes` |  | `[unregistered]` |
| `concept_budget_land_taxes_desc` |  | `[unregistered]` |
| `concept_budget_military_slaves` |  | `[unregistered]` |
| `concept_budget_military_slaves_desc` |  | `[unregistered]` |
| `concept_budget_military_wages` |  | `[unregistered]` |
| `concept_budget_military_wages_desc` |  | `[unregistered]` |
| `concept_budget_minting` |  | `[unregistered]` |
| `concept_budget_minting_desc` |  | `[unregistered]` |
| `concept_budget_per_capita_taxes` |  | `[unregistered]` |
| `concept_budget_per_capita_taxes_desc` |  | `[unregistered]` |
| `concept_budget_poll_taxes` |  | `[unregistered]` |
| `concept_budget_poll_taxes_desc` |  | `[unregistered]` |
| `concept_budget_power_bloc` |  | `[unregistered]` |
| `concept_budget_power_bloc_desc` |  | `[unregistered]` |
| `concept_budget_treaties` |  | `[unregistered]` |
| `concept_budget_treaties_desc` |  | `[unregistered]` |
| `concept_budget_wages` |  | `[unregistered]` |
| `concept_budget_wages_desc` |  | `[unregistered]` |
| `concept_building` |  | `[unregistered]` |
| `concept_building_balance` |  | `[unregistered]` |
| `concept_building_balance_desc` |  | `[unregistered]` |
| `concept_building_desc` |  | `[unregistered]` |
| `concept_building_group` |  | `[unregistered]` |
| `concept_building_group_desc` |  | `[unregistered]` |
| `concept_building_level` |  | `[unregistered]` |
| `concept_building_level_desc` |  | `[unregistered]` |
| `concept_building_owners` |  | `[unregistered]` |
| `concept_building_owners_desc` |  | `[unregistered]` |
| `concept_building_wage` |  | `[unregistered]` |
| `concept_building_wage_desc` |  | `[unregistered]` |
| `concept_bureaucracy` |  | `[unregistered]` |
| `concept_bureaucracy_desc` |  | `[unregistered]` |
| `concept_busy` |  | `[unregistered]` |
| `concept_busy_desc` |  | `[unregistered]` |
| `concept_buy_orders` |  | `[unregistered]` |
| `concept_buy_orders_desc` |  | `[unregistered]` |
| `concept_canal` |  | `[unregistered]` |
| `concept_canal_desc` |  | `[unregistered]` |
| `concept_capacity` |  | `[unregistered]` |
| `concept_capacity_desc` |  | `[unregistered]` |
| `concept_capital_state` |  | `[unregistered]` |
| `concept_capital_state_desc` |  | `[unregistered]` |
| `concept_capitulation_desire` |  | `[unregistered]` |
| `concept_capitulation_desire_desc` |  | `[unregistered]` |
| `concept_carrying_capacity` |  | `[unregistered]` |
| `concept_carrying_capacity_desc` |  | `[unregistered]` |
| `concept_cash_reserves` |  | `[unregistered]` |
| `concept_cash_reserves_desc` |  | `[unregistered]` |
| `concept_casualties` |  | `[unregistered]` |
| `concept_casualties_desc` |  | `[unregistered]` |
| `concept_change_rate_scaling` |  | `[unregistered]` |
| `concept_change_rate_scaling_desc` |  | `[unregistered]` |
| `concept_character` |  | `[unregistered]` |
| `concept_character_desc` |  | `[unregistered]` |
| `concept_character_role` |  | `[unregistered]` |
| `concept_character_role_desc` |  | `[unregistered]` |
| `concept_character_trait` |  | `[unregistered]` |
| `concept_character_trait_desc` |  | `[unregistered]` |
| `concept_chartered_company` |  | `[unregistered]` |
| `concept_chartered_company_desc` |  | `[unregistered]` |
| `concept_civil_war` |  | `[unregistered]` |
| `concept_civil_war_desc` |  | `[unregistered]` |
| `concept_claim` |  | `[unregistered]` |
| `concept_claim_desc` |  | `[unregistered]` |
| `concept_clout` |  | `[unregistered]` |
| `concept_clout_desc` |  | `[unregistered]` |
| `concept_coastal_building` |  | `[unregistered]` |
| `concept_coastal_building_desc` |  | `[unregistered]` |
| `concept_colonial_growth` |  | `[unregistered]` |
| `concept_colonial_growth_desc` |  | `[unregistered]` |
| `concept_colonization_rights` |  | `[unregistered]` |
| `concept_colonization_rights_desc` |  | `[unregistered]` |
| `concept_colony` |  | `[unregistered]` |
| `concept_colony_desc` |  | `[unregistered]` |
| `concept_colony_subject` |  | `[unregistered]` |
| `concept_colony_subject_desc` |  | `[unregistered]` |
| `concept_combat_unit_group` |  | `[unregistered]` |
| `concept_combat_unit_group_desc` |  | `[unregistered]` |
| `concept_combat_unit_type` |  | `[unregistered]` |
| `concept_combat_unit_type_desc` |  | `[unregistered]` |
| `concept_combat_width` |  | `[unregistered]` |
| `concept_combat_width_desc` |  | `[unregistered]` |
| `concept_command_limit` |  | `[unregistered]` |
| `concept_command_limit_desc` |  | `[unregistered]` |
| `concept_commander` |  | `[unregistered]` |
| `concept_commander_desc` |  | `[unregistered]` |
| `concept_commander_rank` |  | `[unregistered]` |
| `concept_commander_rank_desc` |  | `[unregistered]` |
| `concept_company` |  | `[unregistered]` |
| `concept_company_category` |  | `[unregistered]` |
| `concept_company_category_desc` |  | `[unregistered]` |
| `concept_company_charter` |  | `[unregistered]` |
| `concept_company_charter_desc` |  | `[unregistered]` |
| `concept_company_desc` |  | `[unregistered]` |
| `concept_company_hq` |  | `[unregistered]` |
| `concept_company_hq_desc` |  | `[unregistered]` |
| `concept_company_monopoly` |  | `[unregistered]` |
| `concept_company_monopoly_desc` |  | `[unregistered]` |
| `concept_concept` |  | `[unregistered]` |
| `concept_concept_desc` |  | `[unregistered]` |
| `concept_confidence` |  | `[unregistered]` |
| `concept_confidence_desc` |  | `[unregistered]` |
| `concept_conscript_battalion` |  | `[unregistered]` |
| `concept_conscript_battalion_desc` |  | `[unregistered]` |
| `concept_conscription_center` |  | `[unregistered]` |
| `concept_conscription_center_desc` |  | `[unregistered]` |
| `concept_conscription_limit` |  | `[unregistered]` |
| `concept_conscription_limit_desc` |  | `[unregistered]` |
| `concept_construction` |  | `[unregistered]` |
| `concept_construction_desc` |  | `[unregistered]` |
| `concept_construction_queue` |  | `[unregistered]` |
| `concept_construction_queue_desc` |  | `[unregistered]` |
| `concept_consumption_tax` |  | `[unregistered]` |
| `concept_consumption_tax_desc` |  | `[unregistered]` |
| `concept_contravention` |  | `[unregistered]` |
| `concept_contravention_desc` |  | `[unregistered]` |
| `concept_controlled_war_goal` |  | `[unregistered]` |
| `concept_controlled_war_goal_desc` |  | `[unregistered]` |
| `concept_conversion` |  | `[unregistered]` |
| `concept_conversion_desc` |  | `[unregistered]` |
| `concept_core_movement_ideology` |  | `[unregistered]` |
| `concept_core_movement_ideology_desc` |  | `[unregistered]` |
| `concept_countdown_to_war` |  | `[unregistered]` |
| `concept_countdown_to_war_desc` |  | `[unregistered]` |
| `concept_country` |  | `[unregistered]` |
| `concept_country_desc` |  | `[unregistered]` |
| `concept_country_monopoly` |  | `[unregistered]` |
| `concept_country_monopoly_desc` |  | `[unregistered]` |
| `concept_country_tier` |  | `[unregistered]` |
| `concept_country_tier_desc` |  | `[unregistered]` |
| `concept_coup` |  | `[unregistered]` |
| `concept_coup_desc` |  | `[unregistered]` |
| `concept_coup_resistance` |  | `[unregistered]` |
| `concept_coup_resistance_desc` |  | `[unregistered]` |
| `concept_coup_strength` |  | `[unregistered]` |
| `concept_coup_strength_desc` |  | `[unregistered]` |
| `concept_court_intrigue` |  | `[unregistered]` |
| `concept_court_intrigue_desc` |  | `[unregistered]` |
| `concept_credit` |  | `[unregistered]` |
| `concept_credit_desc` |  | `[unregistered]` |
| `concept_crew_attack_damage` |  | `[unregistered]` |
| `concept_crew_attack_damage_desc` |  | `[unregistered]` |
| `concept_crew_casualties` |  | `[unregistered]` |
| `concept_crew_casualties_desc` |  | `[unregistered]` |
| `concept_critical_hit_chance` |  | `[unregistered]` |
| `concept_critical_hit_chance_desc` |  | `[unregistered]` |
| `concept_critical_hit_multiplier` |  | `[unregistered]` |
| `concept_critical_hit_multiplier_desc` |  | `[unregistered]` |
| `concept_crown_land` |  | `[unregistered]` |
| `concept_crown_land_desc` |  | `[unregistered]` |
| `concept_crown_land_subject` |  | `[unregistered]` |
| `concept_crown_land_subject_desc` |  | `[unregistered]` |
| `concept_cultural_community` |  | `[unregistered]` |
| `concept_cultural_community_desc` |  | `[unregistered]` |
| `concept_cultural_movement` |  | `[unregistered]` |
| `concept_cultural_movement_desc` |  | `[unregistered]` |
| `concept_cultural_turmoil` |  | `[unregistered]` |
| `concept_cultural_turmoil_desc` |  | `[unregistered]` |
| `concept_culture` |  | `[unregistered]` |
| `concept_culture_desc` |  | `[unregistered]` |
| `concept_customs_union` |  | `[unregistered]` |
| `concept_customs_union_desc` |  | `[unregistered]` |
| `concept_dead` |  | `[unregistered]` |
| `concept_dead_desc` |  | `[unregistered]` |
| `concept_decay` |  | `[unregistered]` |
| `concept_decay_desc` |  | `[unregistered]` |
| `concept_decentralized_nation` |  | `[unregistered]` |
| `concept_decentralized_nation_desc` |  | `[unregistered]` |
| `concept_decision` |  | `[unregistered]` |
| `concept_decision_desc` |  | `[unregistered]` |
| `concept_decree` |  | `[unregistered]` |
| `concept_decree_desc` |  | `[unregistered]` |
| `concept_default` |  | `[unregistered]` |
| `concept_default_desc` |  | `[unregistered]` |
| `concept_default_unit` |  | `[unregistered]` |
| `concept_default_unit_desc` |  | `[unregistered]` |
| `concept_defense` |  | `[unregistered]` |
| `concept_defense_desc` |  | `[unregistered]` |
| `concept_defensive_pact` |  | `[unregistered]` |
| `concept_defensive_pact_desc` |  | `[unregistered]` |
| `concept_dependent_income` |  | `[unregistered]` |
| `concept_dependent_income_desc` |  | `[unregistered]` |
| `concept_dependents` |  | `[unregistered]` |
| `concept_dependents_desc` |  | `[unregistered]` |
| `concept_detection` |  | `[unregistered]` |
| `concept_detection_desc` |  | `[unregistered]` |
| `concept_devastation` |  | `[unregistered]` |
| `concept_devastation_desc` |  | `[unregistered]` |
| `concept_diplomatic_action` |  | `[unregistered]` |
| `concept_diplomatic_action_desc` |  | `[unregistered]` |
| `concept_diplomatic_catalyst` |  | `[unregistered]` |
| `concept_diplomatic_catalyst_desc` |  | `[unregistered]` |
| `concept_diplomatic_demand` |  | `[unregistered]` |
| `concept_diplomatic_demand_desc` |  | `[unregistered]` |
| `concept_diplomatic_incident` |  | `[unregistered]` |
| `concept_diplomatic_incident_desc` |  | `[unregistered]` |
| `concept_diplomatic_lens` |  | `[unregistered]` |
| `concept_diplomatic_lens_desc` |  | `[unregistered]` |
| `concept_diplomatic_maneuvers` |  | `[unregistered]` |
| `concept_diplomatic_maneuvers_desc` |  | `[unregistered]` |
| `concept_diplomatic_pact` |  | `[unregistered]` |
| `concept_diplomatic_pact_desc` |  | `[unregistered]` |
| `concept_diplomatic_play` |  | `[unregistered]` |
| `concept_diplomatic_play_desc` |  | `[unregistered]` |
| `concept_diplomatic_relevancy` |  | `[unregistered]` |
| `concept_diplomatic_relevancy_desc` |  | `[unregistered]` |
| `concept_discrimination` |  | `[unregistered]` |
| `concept_discrimination_desc` |  | `[unregistered]` |
| `concept_discrimination_trait` |  | `[unregistered]` |
| `concept_discrimination_trait_desc` |  | `[unregistered]` |
| `concept_discrimination_trait_group` |  | `[unregistered]` |
| `concept_discrimination_trait_group_desc` |  | `[unregistered]` |
| `concept_disenfranchised` |  | `[unregistered]` |
| `concept_disenfranchised_desc` |  | `[unregistered]` |
| `concept_disqualified_culture` |  | `[unregistered]` |
| `concept_disqualified_culture_desc` |  | `[unregistered]` |
| `concept_dividends` |  | `[unregistered]` |
| `concept_dividends_desc` |  | `[unregistered]` |
| `concept_dominion` |  | `[unregistered]` |
| `concept_dominion_desc` |  | `[unregistered]` |
| `concept_dynastic_loyalty` |  | `[unregistered]` |
| `concept_dynastic_loyalty_desc` |  | `[unregistered]` |
| `concept_economic_dependence` |  | `[unregistered]` |
| `concept_economic_dependence_desc` |  | `[unregistered]` |
| `concept_economy_health` |  | `[unregistered]` |
| `concept_economy_health_desc` |  | `[unregistered]` |
| `concept_economy_of_scale` |  | `[unregistered]` |
| `concept_economy_of_scale_desc` |  | `[unregistered]` |
| `concept_education_access` |  | `[unregistered]` |
| `concept_education_access_desc` |  | `[unregistered]` |
| `concept_election` |  | `[unregistered]` |
| `concept_election_desc` |  | `[unregistered]` |
| `concept_electoral_confidence` |  | `[unregistered]` |
| `concept_electoral_confidence_desc` |  | `[unregistered]` |
| `concept_embargo` |  | `[unregistered]` |
| `concept_embargo_desc` |  | `[unregistered]` |
| `concept_empire_stability` |  | `[unregistered]` |
| `concept_empire_stability_desc` |  | `[unregistered]` |
| `concept_employment` |  | `[unregistered]` |
| `concept_employment_desc` |  | `[unregistered]` |
| `concept_enactment_advance` |  | `[unregistered]` |
| `concept_enactment_advance_desc` |  | `[unregistered]` |
| `concept_enactment_debate` |  | `[unregistered]` |
| `concept_enactment_debate_desc` |  | `[unregistered]` |
| `concept_enactment_of_laws` |  | `[unregistered]` |
| `concept_enactment_of_laws_desc` |  | `[unregistered]` |
| `concept_enactment_phase` |  | `[unregistered]` |
| `concept_enactment_phase_desc` |  | `[unregistered]` |
| `concept_enactment_setback` |  | `[unregistered]` |
| `concept_enactment_setback_desc` |  | `[unregistered]` |
| `concept_enactment_stall` |  | `[unregistered]` |
| `concept_enactment_stall_desc` |  | `[unregistered]` |
| `concept_enactment_success` |  | `[unregistered]` |
| `concept_enactment_success_desc` |  | `[unregistered]` |
| `concept_end_of_discussion_factor` |  | `[unregistered]` |
| `concept_end_of_discussion_factor_desc` |  | `[unregistered]` |
| `concept_endorse_oppose` |  | `[unregistered]` |
| `concept_endorse_oppose_desc` |  | `[unregistered]` |
| `concept_enforced_treaty` |  | `[unregistered]` |
| `concept_enforced_treaty_desc` |  | `[unregistered]` |
| `concept_escalation` |  | `[unregistered]` |
| `concept_escalation_desc` |  | `[unregistered]` |
| `concept_executive` |  | `[unregistered]` |
| `concept_executive_desc` |  | `[unregistered]` |
| `concept_executives` |  | `[unregistered]` |
| `concept_executives_desc` |  | `[unregistered]` |
| `concept_exile` |  | `[unregistered]` |
| `concept_exile_desc` |  | `[unregistered]` |
| `concept_exiled_army` |  | `[unregistered]` |
| `concept_exiled_army_desc` |  | `[unregistered]` |
| `concept_expected_sol` |  | `[unregistered]` |
| `concept_expected_sol_desc` |  | `[unregistered]` |
| `concept_export_price` |  | `[unregistered]` |
| `concept_export_price_desc` |  | `[unregistered]` |
| `concept_famine` |  | `[unregistered]` |
| `concept_famine_desc` |  | `[unregistered]` |
| `concept_fervor` |  | `[unregistered]` |
| `concept_fervor_desc` |  | `[unregistered]` |
| `concept_flagship` |  | `[unregistered]` |
| `concept_flagship_desc` |  | `[unregistered]` |
| `concept_fleet` |  | `[unregistered]` |
| `concept_fleet_desc` |  | `[unregistered]` |
| `concept_fleet_hit_points` |  | `[unregistered]` |
| `concept_fleet_hit_points_desc` |  | `[unregistered]` |
| `concept_food_security` |  | `[unregistered]` |
| `concept_food_security_desc` |  | `[unregistered]` |
| `concept_foreign_investment` |  | `[unregistered]` |
| `concept_foreign_investment_desc` |  | `[unregistered]` |
| `concept_foreign_investment_rights` |  | `[unregistered]` |
| `concept_foreign_investment_rights_desc` |  | `[unregistered]` |
| `concept_front` |  | `[unregistered]` |
| `concept_front_desc` |  | `[unregistered]` |
| `concept_fully_mobilized_battalions` |  | `[unregistered]` |
| `concept_fully_mobilized_battalions_desc` |  | `[unregistered]` |
| `concept_fund_lobbies` |  | `[unregistered]` |
| `concept_fund_lobbies_desc` |  | `[unregistered]` |
| `concept_gdp` |  | `[unregistered]` |
| `concept_gdp_desc` |  | `[unregistered]` |
| `concept_gdp_ownership` |  | `[unregistered]` |
| `concept_gdp_ownership_desc` |  | `[unregistered]` |
| `concept_gdp_per_capita` |  | `[unregistered]` |
| `concept_gdp_per_capita_desc` |  | `[unregistered]` |
| `concept_general` |  | `[unregistered]` |
| `concept_general_desc` |  | `[unregistered]` |
| `concept_generated_pollution` |  | `[unregistered]` |
| `concept_generated_pollution_desc` |  | `[unregistered]` |
| `concept_georegion` |  | `[unregistered]` |
| `concept_georegion_desc` |  | `[unregistered]` |
| `concept_gold_reserves` |  | `[unregistered]` |
| `concept_gold_reserves_desc` |  | `[unregistered]` |
| `concept_gongen` |  | `[unregistered]` |
| `concept_gongen_desc` |  | `[unregistered]` |
| `concept_good` |  | `[unregistered]` |
| `concept_good_consumption` |  | `[unregistered]` |
| `concept_good_consumption_desc` |  | `[unregistered]` |
| `concept_good_desc` |  | `[unregistered]` |
| `concept_good_production` |  | `[unregistered]` |
| `concept_good_production_desc` |  | `[unregistered]` |
| `concept_goods_substitution` |  | `[unregistered]` |
| `concept_goods_substitution_desc` |  | `[unregistered]` |
| `concept_government` |  | `[unregistered]` |
| `concept_government_building` |  | `[unregistered]` |
| `concept_government_building_desc` |  | `[unregistered]` |
| `concept_government_construction` |  | `[unregistered]` |
| `concept_government_construction_desc` |  | `[unregistered]` |
| `concept_government_desc` |  | `[unregistered]` |
| `concept_government_dividends` |  | `[unregistered]` |
| `concept_government_dividends_desc` |  | `[unregistered]` |
| `concept_government_expenses` |  | `[unregistered]` |
| `concept_government_expenses_desc` |  | `[unregistered]` |
| `concept_government_good` |  | `[unregistered]` |
| `concept_government_good_desc` |  | `[unregistered]` |
| `concept_government_premium` |  | `[unregistered]` |
| `concept_government_premium_desc` |  | `[unregistered]` |
| `concept_government_reform` |  | `[unregistered]` |
| `concept_government_reform_desc` |  | `[unregistered]` |
| `concept_government_type` |  | `[unregistered]` |
| `concept_government_type_desc` |  | `[unregistered]` |
| `concept_government_wage` |  | `[unregistered]` |
| `concept_government_wage_desc` |  | `[unregistered]` |
| `concept_great_power` |  | `[unregistered]` |
| `concept_great_power_desc` |  | `[unregistered]` |
| `concept_guarantee_independence` |  | `[unregistered]` |
| `concept_guarantee_independence_desc` |  | `[unregistered]` |
| `concept_guerilla_war` |  | `[unregistered]` |
| `concept_guerilla_war_desc` |  | `[unregistered]` |
| `concept_harvest_condition` |  | `[unregistered]` |
| `concept_harvest_condition_desc` |  | `[unregistered]` |
| `concept_harvest_condition_intensity` |  | `[unregistered]` |
| `concept_harvest_condition_intensity_desc` |  | `[unregistered]` |
| `concept_head_of_state` |  | `[unregistered]` |
| `concept_head_of_state_desc` |  | `[unregistered]` |
| `concept_heir` |  | `[unregistered]` |
| `concept_heir_desc` |  | `[unregistered]` |
| `concept_heritage_trait` |  | `[unregistered]` |
| `concept_heritage_trait_desc` |  | `[unregistered]` |
| `concept_holding` |  | `[unregistered]` |
| `concept_holding_desc` |  | `[unregistered]` |
| `concept_home_state` |  | `[unregistered]` |
| `concept_home_state_desc` |  | `[unregistered]` |
| `concept_homeland` |  | `[unregistered]` |
| `concept_homeland_desc` |  | `[unregistered]` |
| `concept_house_of_karadjordjevic` |  | `[unregistered]` |
| `concept_house_of_karadjordjevic_desc` |  | `[unregistered]` |
| `concept_house_of_obrenovic` |  | `[unregistered]` |
| `concept_house_of_obrenovic_desc` |  | `[unregistered]` |
| `concept_hq` |  | `[unregistered]` |
| `concept_hq_desc` |  | `[unregistered]` |
| `concept_hull_attack_damage` |  | `[unregistered]` |
| `concept_hull_attack_damage_desc` |  | `[unregistered]` |
| `concept_humiliation` |  | `[unregistered]` |
| `concept_humiliation_desc` |  | `[unregistered]` |
| `concept_ideological_incoherence` |  | `[unregistered]` |
| `concept_ideological_incoherence_desc` |  | `[unregistered]` |
| `concept_ideology` |  | `[unregistered]` |
| `concept_ideology_desc` |  | `[unregistered]` |
| `concept_import_price` |  | `[unregistered]` |
| `concept_import_price_desc` |  | `[unregistered]` |
| `concept_in_government` |  | `[unregistered]` |
| `concept_in_government_desc` |  | `[unregistered]` |
| `concept_in_opposition` |  | `[unregistered]` |
| `concept_in_opposition_desc` |  | `[unregistered]` |
| `concept_incoming_units` |  | `[unregistered]` |
| `concept_incoming_units_desc` |  | `[unregistered]` |
| `concept_incorporated_state` |  | `[unregistered]` |
| `concept_incorporated_state_desc` |  | `[unregistered]` |
| `concept_individual` |  | `[unregistered]` |
| `concept_individual_desc` |  | `[unregistered]` |
| `concept_infamy` |  | `[unregistered]` |
| `concept_infamy_desc` |  | `[unregistered]` |
| `concept_influence` |  | `[unregistered]` |
| `concept_influence_desc` |  | `[unregistered]` |
| `concept_influential` |  | `[unregistered]` |
| `concept_influential_desc` |  | `[unregistered]` |
| `concept_infrastructure` |  | `[unregistered]` |
| `concept_infrastructure_desc` |  | `[unregistered]` |
| `concept_infrastructure_usage` |  | `[unregistered]` |
| `concept_infrastructure_usage_desc` |  | `[unregistered]` |
| `concept_initiator` |  | `[unregistered]` |
| `concept_initiator_desc` |  | `[unregistered]` |
| `concept_innovation` |  | `[unregistered]` |
| `concept_innovation_desc` |  | `[unregistered]` |
| `concept_input_mult` |  | `[unregistered]` |
| `concept_input_mult_desc` |  | `[unregistered]` |
| `concept_insignificant_power` |  | `[unregistered]` |
| `concept_insignificant_power_desc` |  | `[unregistered]` |
| `concept_instant_diplomatic_action` |  | `[unregistered]` |
| `concept_instant_diplomatic_action_desc` |  | `[unregistered]` |
| `concept_institution` |  | `[unregistered]` |
| `concept_institution_desc` |  | `[unregistered]` |
| `concept_insurrection` |  | `[unregistered]` |
| `concept_insurrection_desc` |  | `[unregistered]` |
| `concept_integrated_culture` |  | `[unregistered]` |
| `concept_integrated_culture_desc` |  | `[unregistered]` |
| `concept_interest` |  | `[unregistered]` |
| `concept_interest_desc` |  | `[unregistered]` |
| `concept_interest_group` |  | `[unregistered]` |
| `concept_interest_group_attraction` |  | `[unregistered]` |
| `concept_interest_group_attraction_desc` |  | `[unregistered]` |
| `concept_interest_group_desc` |  | `[unregistered]` |
| `concept_interest_group_trait` |  | `[unregistered]` |
| `concept_interest_group_trait_desc` |  | `[unregistered]` |
| `concept_interest_tier` |  | `[unregistered]` |
| `concept_interest_tier_desc` |  | `[unregistered]` |
| `concept_invasion` |  | `[unregistered]` |
| `concept_invasion_desc` |  | `[unregistered]` |
| `concept_investment_level` |  | `[unregistered]` |
| `concept_investment_level_desc` |  | `[unregistered]` |
| `concept_investment_pool` |  | `[unregistered]` |
| `concept_investment_pool_desc` |  | `[unregistered]` |
| `concept_involvement` |  | `[unregistered]` |
| `concept_involvement_desc` |  | `[unregistered]` |
| `concept_isolated_state` |  | `[unregistered]` |
| `concept_isolated_state_desc` |  | `[unregistered]` |
| `concept_japanese_emperor` |  | `[unregistered]` |
| `concept_japanese_emperor_desc` |  | `[unregistered]` |
| `concept_job_satisfaction` |  | `[unregistered]` |
| `concept_job_satisfaction_desc` |  | `[unregistered]` |
| `concept_jobseeker` |  | `[unregistered]` |
| `concept_jobseeker_desc` |  | `[unregistered]` |
| `concept_journal_entry` |  | `[unregistered]` |
| `concept_journal_entry_desc` |  | `[unregistered]` |
| `concept_junior_partner` |  | `[unregistered]` |
| `concept_junior_partner_desc` |  | `[unregistered]` |
| `concept_kill_rate` |  | `[unregistered]` |
| `concept_kill_rate_desc` |  | `[unregistered]` |
| `concept_landing_progress` |  | `[unregistered]` |
| `concept_landing_progress_desc` |  | `[unregistered]` |
| `concept_lands_of_anarchy_control` |  | `[unregistered]` |
| `concept_lands_of_anarchy_control_desc` |  | `[unregistered]` |
| `concept_language_trait` |  | `[unregistered]` |
| `concept_language_trait_desc` |  | `[unregistered]` |
| `concept_law` |  | `[unregistered]` |
| `concept_law_desc` |  | `[unregistered]` |
| `concept_law_group` |  | `[unregistered]` |
| `concept_law_group_desc` |  | `[unregistered]` |
| `concept_leader` |  | `[unregistered]` |
| `concept_leader_desc` |  | `[unregistered]` |
| `concept_legitimacy` |  | `[unregistered]` |
| `concept_legitimacy_desc` |  | `[unregistered]` |
| `concept_liberty_desire` |  | `[unregistered]` |
| `concept_liberty_desire_desc` |  | `[unregistered]` |
| `concept_life_experience` |  | `[unregistered]` |
| `concept_life_experience_desc` |  | `[unregistered]` |
| `concept_literacy` |  | `[unregistered]` |
| `concept_literacy_desc` |  | `[unregistered]` |
| `concept_loans` |  | `[unregistered]` |
| `concept_loans_desc` |  | `[unregistered]` |
| `concept_local_country` |  | `[unregistered]` |
| `concept_local_country_desc` |  | `[unregistered]` |
| `concept_local_good` |  | `[unregistered]` |
| `concept_local_good_desc` |  | `[unregistered]` |
| `concept_local_price` |  | `[unregistered]` |
| `concept_local_price_desc` |  | `[unregistered]` |
| `concept_locality` |  | `[unregistered]` |
| `concept_locality_desc` |  | `[unregistered]` |
| `concept_lower_strata` |  | `[unregistered]` |
| `concept_lower_strata_desc` |  | `[unregistered]` |
| `concept_loyalist` |  | `[unregistered]` |
| `concept_loyalist_desc` |  | `[unregistered]` |
| `concept_loyalty` |  | `[unregistered]` |
| `concept_loyalty_desc` |  | `[unregistered]` |
| `concept_magnate` |  | `[unregistered]` |
| `concept_magnate_desc` |  | `[unregistered]` |
| `concept_major_power` |  | `[unregistered]` |
| `concept_major_power_desc` |  | `[unregistered]` |
| `concept_maneuver` |  | `[unregistered]` |
| `concept_maneuver_desc` |  | `[unregistered]` |
| `concept_manpower` |  | `[unregistered]` |
| `concept_manpower_desc` |  | `[unregistered]` |
| `concept_marginalized` |  | `[unregistered]` |
| `concept_marginalized_desc` |  | `[unregistered]` |
| `concept_marine_capacity` |  | `[unregistered]` |
| `concept_marine_capacity_desc` |  | `[unregistered]` |
| `concept_market` |  | `[unregistered]` |
| `concept_market_access` |  | `[unregistered]` |
| `concept_market_access_desc` |  | `[unregistered]` |
| `concept_market_area` |  | `[unregistered]` |
| `concept_market_area_desc` |  | `[unregistered]` |
| `concept_market_capital` |  | `[unregistered]` |
| `concept_market_capital_desc` |  | `[unregistered]` |
| `concept_market_desc` |  | `[unregistered]` |
| `concept_market_impact` |  | `[unregistered]` |
| `concept_market_impact_desc` |  | `[unregistered]` |
| `concept_market_owner` |  | `[unregistered]` |
| `concept_market_owner_desc` |  | `[unregistered]` |
| `concept_market_price` |  | `[unregistered]` |
| `concept_market_price_desc` |  | `[unregistered]` |
| `concept_market_share` |  | `[unregistered]` |
| `concept_market_share_desc` |  | `[unregistered]` |
| `concept_mass_migration` |  | `[unregistered]` |
| `concept_mass_migration_desc` |  | `[unregistered]` |
| `concept_mass_migration_pull` |  | `[unregistered]` |
| `concept_mass_migration_pull_desc` |  | `[unregistered]` |
| `concept_message_settings_feed` |  | `[unregistered]` |
| `concept_message_settings_feed_desc` |  | `[unregistered]` |
| `concept_message_settings_none` |  | `[unregistered]` |
| `concept_message_settings_none_desc` |  | `[unregistered]` |
| `concept_message_settings_popup` |  | `[unregistered]` |
| `concept_message_settings_popup_desc` |  | `[unregistered]` |
| `concept_message_settings_toast` |  | `[unregistered]` |
| `concept_message_settings_toast_desc` |  | `[unregistered]` |
| `concept_middle_strata` |  | `[unregistered]` |
| `concept_middle_strata_desc` |  | `[unregistered]` |
| `concept_migration` |  | `[unregistered]` |
| `concept_migration_desc` |  | `[unregistered]` |
| `concept_migration_pull` |  | `[unregistered]` |
| `concept_migration_pull_desc` |  | `[unregistered]` |
| `concept_migration_target` |  | `[unregistered]` |
| `concept_migration_target_desc` |  | `[unregistered]` |
| `concept_military_access` |  | `[unregistered]` |
| `concept_military_access_desc` |  | `[unregistered]` |
| `concept_military_assistance` |  | `[unregistered]` |
| `concept_military_assistance_desc` |  | `[unregistered]` |
| `concept_military_building` |  | `[unregistered]` |
| `concept_military_building_desc` |  | `[unregistered]` |
| `concept_military_formation` |  | `[unregistered]` |
| `concept_military_formation_desc` |  | `[unregistered]` |
| `concept_military_good` |  | `[unregistered]` |
| `concept_military_good_desc` |  | `[unregistered]` |
| `concept_military_lens` |  | `[unregistered]` |
| `concept_military_lens_desc` |  | `[unregistered]` |
| `concept_military_wage` |  | `[unregistered]` |
| `concept_military_wage_desc` |  | `[unregistered]` |
| `concept_minor_power` |  | `[unregistered]` |
| `concept_minor_power_desc` |  | `[unregistered]` |
| `concept_mission_efficiency` |  | `[unregistered]` |
| `concept_mission_efficiency_desc` |  | `[unregistered]` |
| `concept_mobilization_option` |  | `[unregistered]` |
| `concept_mobilization_option_desc` |  | `[unregistered]` |
| `concept_mobilize_army` |  | `[unregistered]` |
| `concept_mobilize_army_desc` |  | `[unregistered]` |
| `concept_mobilize_battalion` |  | `[unregistered]` |
| `concept_mobilize_battalion_desc` |  | `[unregistered]` |
| `concept_modifier` |  | `[unregistered]` |
| `concept_modifier_desc` |  | `[unregistered]` |
| `concept_momentum` |  | `[unregistered]` |
| `concept_momentum_desc` |  | `[unregistered]` |
| `concept_money` |  | `[unregistered]` |
| `concept_money_desc` |  | `[unregistered]` |
| `concept_monopoly` |  | `[unregistered]` |
| `concept_monopoly_desc` |  | `[unregistered]` |
| `concept_monument` |  | `[unregistered]` |
| `concept_monument_desc` |  | `[unregistered]` |
| `concept_morale` |  | `[unregistered]` |
| `concept_morale_damage` |  | `[unregistered]` |
| `concept_morale_damage_desc` |  | `[unregistered]` |
| `concept_morale_demoralized` |  | `[unregistered]` |
| `concept_morale_demoralized_desc` |  | `[unregistered]` |
| `concept_morale_desc` |  | `[unregistered]` |
| `concept_nation_formation` |  | `[unregistered]` |
| `concept_nation_formation_desc` |  | `[unregistered]` |
| `concept_national_awakening` |  | `[unregistered]` |
| `concept_national_awakening_desc` |  | `[unregistered]` |
| `concept_nationalize` |  | `[unregistered]` |
| `concept_nationalize_desc` |  | `[unregistered]` |
| `concept_nationally_owned` |  | `[unregistered]` |
| `concept_nationally_owned_desc` |  | `[unregistered]` |
| `concept_native_uprising` |  | `[unregistered]` |
| `concept_native_uprising_desc` |  | `[unregistered]` |
| `concept_naval_battle` |  | `[unregistered]` |
| `concept_naval_battle_condition` |  | `[unregistered]` |
| `concept_naval_battle_condition_desc` |  | `[unregistered]` |
| `concept_naval_battle_desc` |  | `[unregistered]` |
| `concept_naval_hostilities` |  | `[unregistered]` |
| `concept_naval_hostilities_desc` |  | `[unregistered]` |
| `concept_naval_invasion` |  | `[unregistered]` |
| `concept_naval_invasion_desc` |  | `[unregistered]` |
| `concept_naval_invasion_support` |  | `[unregistered]` |
| `concept_naval_invasion_support_desc` |  | `[unregistered]` |
| `concept_naval_mission` |  | `[unregistered]` |
| `concept_naval_mission_area_limit` |  | `[unregistered]` |
| `concept_naval_mission_area_limit_desc` |  | `[unregistered]` |
| `concept_naval_mission_desc` |  | `[unregistered]` |
| `concept_naval_power_projection` |  | `[unregistered]` |
| `concept_naval_power_projection_desc` |  | `[unregistered]` |
| `concept_negotiation` |  | `[unregistered]` |
| `concept_negotiation_desc` |  | `[unregistered]` |
| `concept_neighbors` |  | `[unregistered]` |
| `concept_neighbors_desc` |  | `[unregistered]` |
| `concept_neutral` |  | `[unregistered]` |
| `concept_neutral_desc` |  | `[unregistered]` |
| `concept_neutrality` |  | `[unregistered]` |
| `concept_neutrality_desc` |  | `[unregistered]` |
| `concept_non_fulfillment` |  | `[unregistered]` |
| `concept_non_fulfillment_desc` |  | `[unregistered]` |
| `concept_normal_wage` |  | `[unregistered]` |
| `concept_normal_wage_desc` |  | `[unregistered]` |
| `concept_obligation` |  | `[unregistered]` |
| `concept_obligation_desc` |  | `[unregistered]` |
| `concept_observer_mode` |  | `[unregistered]` |
| `concept_observer_mode_desc` |  | `[unregistered]` |
| `concept_obsession` |  | `[unregistered]` |
| `concept_obsession_desc` |  | `[unregistered]` |
| `concept_obstinance` |  | `[unregistered]` |
| `concept_obstinance_desc` |  | `[unregistered]` |
| `concept_occupancy` |  | `[unregistered]` |
| `concept_occupancy_desc` |  | `[unregistered]` |
| `concept_occupation` |  | `[unregistered]` |
| `concept_occupation_desc` |  | `[unregistered]` |
| `concept_offense` |  | `[unregistered]` |
| `concept_offense_desc` |  | `[unregistered]` |
| `concept_offer_support` |  | `[unregistered]` |
| `concept_offer_support_desc` |  | `[unregistered]` |
| `concept_ongoing_diplomatic_action` |  | `[unregistered]` |
| `concept_ongoing_diplomatic_action_desc` |  | `[unregistered]` |
| `concept_open_market` |  | `[unregistered]` |
| `concept_open_market_desc` |  | `[unregistered]` |
| `concept_opening_moves` |  | `[unregistered]` |
| `concept_opening_moves_desc` |  | `[unregistered]` |
| `concept_order` |  | `[unregistered]` |
| `concept_order_desc` |  | `[unregistered]` |
| `concept_organization` |  | `[unregistered]` |
| `concept_organization_desc` |  | `[unregistered]` |
| `concept_ottoman_integrity` |  | `[unregistered]` |
| `concept_ottoman_integrity_desc` |  | `[unregistered]` |
| `concept_overlord` |  | `[unregistered]` |
| `concept_overlord_action` |  | `[unregistered]` |
| `concept_overlord_action_desc` |  | `[unregistered]` |
| `concept_overlord_desc` |  | `[unregistered]` |
| `concept_ownership_share` |  | `[unregistered]` |
| `concept_ownership_share_desc` |  | `[unregistered]` |
| `concept_parent_law` |  | `[unregistered]` |
| `concept_parent_law_desc` |  | `[unregistered]` |
| `concept_party` |  | `[unregistered]` |
| `concept_party_desc` |  | `[unregistered]` |
| `concept_party_leader` |  | `[unregistered]` |
| `concept_party_leader_desc` |  | `[unregistered]` |
| `concept_party_leaders` |  | `[unregistered]` |
| `concept_party_leaders_desc` |  | `[unregistered]` |
| `concept_party_whip` |  | `[unregistered]` |
| `concept_party_whip_desc` |  | `[unregistered]` |
| `concept_peace_deal` |  | `[unregistered]` |
| `concept_peace_deal_desc` |  | `[unregistered]` |
| `concept_personal_union` |  | `[unregistered]` |
| `concept_personal_union_desc` |  | `[unregistered]` |
| `concept_piracy` |  | `[unregistered]` |
| `concept_piracy_desc` |  | `[unregistered]` |
| `concept_political_lens` |  | `[unregistered]` |
| `concept_political_lens_desc` |  | `[unregistered]` |
| `concept_political_lobby` |  | `[unregistered]` |
| `concept_political_lobby_appeasement` |  | `[unregistered]` |
| `concept_political_lobby_appeasement_desc` |  | `[unregistered]` |
| `concept_political_lobby_demand` |  | `[unregistered]` |
| `concept_political_lobby_demand_desc` |  | `[unregistered]` |
| `concept_political_lobby_desc` |  | `[unregistered]` |
| `concept_political_lobby_opportunity` |  | `[unregistered]` |
| `concept_political_lobby_opportunity_desc` |  | `[unregistered]` |
| `concept_political_movement` |  | `[unregistered]` |
| `concept_political_movement_desc` |  | `[unregistered]` |
| `concept_political_movement_pressure` |  | `[unregistered]` |
| `concept_political_movement_pressure_desc` |  | `[unregistered]` |
| `concept_political_movement_support` |  | `[unregistered]` |
| `concept_political_movement_support_desc` |  | `[unregistered]` |
| `concept_political_strength` |  | `[unregistered]` |
| `concept_political_strength_desc` |  | `[unregistered]` |
| `concept_politically_unaligned_aligned` |  | `[unregistered]` |
| `concept_politically_unaligned_aligned_desc` |  | `[unregistered]` |
| `concept_politician` |  | `[unregistered]` |
| `concept_politician_desc` |  | `[unregistered]` |
| `concept_pollution_impact` |  | `[unregistered]` |
| `concept_pollution_impact_desc` |  | `[unregistered]` |
| `concept_pop` |  | `[unregistered]` |
| `concept_pop_desc` |  | `[unregistered]` |
| `concept_pop_growth` |  | `[unregistered]` |
| `concept_pop_growth_desc` |  | `[unregistered]` |
| `concept_pop_income` |  | `[unregistered]` |
| `concept_pop_income_desc` |  | `[unregistered]` |
| `concept_pop_needs` |  | `[unregistered]` |
| `concept_pop_needs_desc` |  | `[unregistered]` |
| `concept_pop_qualifications` |  | `[unregistered]` |
| `concept_pop_qualifications_desc` |  | `[unregistered]` |
| `concept_popularity` |  | `[unregistered]` |
| `concept_popularity_desc` |  | `[unregistered]` |
| `concept_port_connection` |  | `[unregistered]` |
| `concept_port_connection_desc` |  | `[unregistered]` |
| `concept_potential_battalions` |  | `[unregistered]` |
| `concept_potential_battalions_desc` |  | `[unregistered]` |
| `concept_power_bloc` |  | `[unregistered]` |
| `concept_power_bloc_cohesion` |  | `[unregistered]` |
| `concept_power_bloc_cohesion_desc` |  | `[unregistered]` |
| `concept_power_bloc_desc` |  | `[unregistered]` |
| `concept_power_bloc_identity` |  | `[unregistered]` |
| `concept_power_bloc_identity_desc` |  | `[unregistered]` |
| `concept_power_bloc_leader` |  | `[unregistered]` |
| `concept_power_bloc_leader_desc` |  | `[unregistered]` |
| `concept_power_bloc_leverage` |  | `[unregistered]` |
| `concept_power_bloc_leverage_advantage` |  | `[unregistered]` |
| `concept_power_bloc_leverage_advantage_desc` |  | `[unregistered]` |
| `concept_power_bloc_leverage_desc` |  | `[unregistered]` |
| `concept_power_bloc_leverage_share` |  | `[unregistered]` |
| `concept_power_bloc_leverage_share_desc` |  | `[unregistered]` |
| `concept_power_bloc_mandate` |  | `[unregistered]` |
| `concept_power_bloc_mandate_desc` |  | `[unregistered]` |
| `concept_power_bloc_mandate_progress` |  | `[unregistered]` |
| `concept_power_bloc_mandate_progress_desc` |  | `[unregistered]` |
| `concept_power_bloc_member` |  | `[unregistered]` |
| `concept_power_bloc_member_desc` |  | `[unregistered]` |
| `concept_power_bloc_primary_principle_group` |  | `[unregistered]` |
| `concept_power_bloc_primary_principle_group_desc` |  | `[unregistered]` |
| `concept_power_bloc_principle` |  | `[unregistered]` |
| `concept_power_bloc_principle_desc` |  | `[unregistered]` |
| `concept_power_bloc_principle_group` |  | `[unregistered]` |
| `concept_power_bloc_principle_group_desc` |  | `[unregistered]` |
| `concept_power_bloc_rank` |  | `[unregistered]` |
| `concept_power_bloc_rank_desc` |  | `[unregistered]` |
| `concept_power_bloc_unclaimed_leverage` |  | `[unregistered]` |
| `concept_power_bloc_unclaimed_leverage_desc` |  | `[unregistered]` |
| `concept_power_projection` |  | `[unregistered]` |
| `concept_power_projection_desc` |  | `[unregistered]` |
| `concept_power_struggle` |  | `[unregistered]` |
| `concept_power_struggle_desc` |  | `[unregistered]` |
| `concept_powerful` |  | `[unregistered]` |
| `concept_powerful_desc` |  | `[unregistered]` |
| `concept_presence` |  | `[unregistered]` |
| `concept_presence_desc` |  | `[unregistered]` |
| `concept_presidency` |  | `[unregistered]` |
| `concept_presidency_desc` |  | `[unregistered]` |
| `concept_presidency_stability` |  | `[unregistered]` |
| `concept_presidency_stability_desc` |  | `[unregistered]` |
| `concept_prestige` |  | `[unregistered]` |
| `concept_prestige_desc` |  | `[unregistered]` |
| `concept_prestige_good` |  | `[unregistered]` |
| `concept_prestige_good_desc` |  | `[unregistered]` |
| `concept_primary_cultures` |  | `[unregistered]` |
| `concept_primary_cultures_desc` |  | `[unregistered]` |
| `concept_primary_demand` |  | `[unregistered]` |
| `concept_primary_demand_desc` |  | `[unregistered]` |
| `concept_princely_state` |  | `[unregistered]` |
| `concept_princely_state_desc` |  | `[unregistered]` |
| `concept_principal` |  | `[unregistered]` |
| `concept_principal_desc` |  | `[unregistered]` |
| `concept_private_construction` |  | `[unregistered]` |
| `concept_private_construction_desc` |  | `[unregistered]` |
| `concept_privately_owned` |  | `[unregistered]` |
| `concept_privately_owned_desc` |  | `[unregistered]` |
| `concept_privatize` |  | `[unregistered]` |
| `concept_privatize_desc` |  | `[unregistered]` |
| `concept_privy_purse` |  | `[unregistered]` |
| `concept_privy_purse_desc` |  | `[unregistered]` |
| `concept_production_lens` |  | `[unregistered]` |
| `concept_production_lens_desc` |  | `[unregistered]` |
| `concept_production_method` |  | `[unregistered]` |
| `concept_production_method_desc` |  | `[unregistered]` |
| `concept_productivity` |  | `[unregistered]` |
| `concept_productivity_desc` |  | `[unregistered]` |
| `concept_profession` |  | `[unregistered]` |
| `concept_profession_desc` |  | `[unregistered]` |
| `concept_prominence` |  | `[unregistered]` |
| `concept_prominence_desc` |  | `[unregistered]` |
| `concept_pronunciamento` |  | `[unregistered]` |
| `concept_pronunciamento_desc` |  | `[unregistered]` |
| `concept_prosperity` |  | `[unregistered]` |
| `concept_prosperity_desc` |  | `[unregistered]` |
| `concept_protectorate` |  | `[unregistered]` |
| `concept_protectorate_desc` |  | `[unregistered]` |
| `concept_province` |  | `[unregistered]` |
| `concept_province_desc` |  | `[unregistered]` |
| `concept_puppet` |  | `[unregistered]` |
| `concept_puppet_desc` |  | `[unregistered]` |
| `concept_radical` |  | `[unregistered]` |
| `concept_radical_desc` |  | `[unregistered]` |
| `concept_radicalized_interest_group` |  | `[unregistered]` |
| `concept_radicalized_interest_group_desc` |  | `[unregistered]` |
| `concept_raiding` |  | `[unregistered]` |
| `concept_raiding_desc` |  | `[unregistered]` |
| `concept_raiding_frequency` |  | `[unregistered]` |
| `concept_raiding_frequency_desc` |  | `[unregistered]` |
| `concept_rank` |  | `[unregistered]` |
| `concept_rank_desc` |  | `[unregistered]` |
| `concept_readiness` |  | `[unregistered]` |
| `concept_readiness_desc` |  | `[unregistered]` |
| `concept_recognized_power` |  | `[unregistered]` |
| `concept_recognized_power_desc` |  | `[unregistered]` |
| `concept_recovery_rate` |  | `[unregistered]` |
| `concept_recovery_rate_desc` |  | `[unregistered]` |
| `concept_regime_change` |  | `[unregistered]` |
| `concept_regime_change_desc` |  | `[unregistered]` |
| `concept_regional_company_hq` |  | `[unregistered]` |
| `concept_regional_company_hq_desc` |  | `[unregistered]` |
| `concept_reinvestment` |  | `[unregistered]` |
| `concept_reinvestment_desc` |  | `[unregistered]` |
| `concept_relations` |  | `[unregistered]` |
| `concept_relations_desc` |  | `[unregistered]` |
| `concept_religion` |  | `[unregistered]` |
| `concept_religion_desc` |  | `[unregistered]` |
| `concept_religious_movement` |  | `[unregistered]` |
| `concept_religious_movement_desc` |  | `[unregistered]` |
| `concept_resource_potential` |  | `[unregistered]` |
| `concept_resource_potential_desc` |  | `[unregistered]` |
| `concept_revenue` |  | `[unregistered]` |
| `concept_revenue_desc` |  | `[unregistered]` |
| `concept_revolution` |  | `[unregistered]` |
| `concept_revolution_desc` |  | `[unregistered]` |
| `concept_risk` |  | `[unregistered]` |
| `concept_risk_desc` |  | `[unregistered]` |
| `concept_rivalry` |  | `[unregistered]` |
| `concept_rivalry_desc` |  | `[unregistered]` |
| `concept_ruler` |  | `[unregistered]` |
| `concept_ruler_desc` |  | `[unregistered]` |
| `concept_russian_aid` |  | `[unregistered]` |
| `concept_russian_aid_desc` |  | `[unregistered]` |
| `concept_sailor` |  | `[unregistered]` |
| `concept_sailor_desc` |  | `[unregistered]` |
| `concept_screening` |  | `[unregistered]` |
| `concept_screening_desc` |  | `[unregistered]` |
| `concept_sea_node` |  | `[unregistered]` |
| `concept_sea_node_desc` |  | `[unregistered]` |
| `concept_secession` |  | `[unregistered]` |
| `concept_secession_desc` |  | `[unregistered]` |
| `concept_secondary_demand` |  | `[unregistered]` |
| `concept_secondary_demand_desc` |  | `[unregistered]` |
| `concept_sell_orders` |  | `[unregistered]` |
| `concept_sell_orders_desc` |  | `[unregistered]` |
| `concept_senior_partner` |  | `[unregistered]` |
| `concept_senior_partner_desc` |  | `[unregistered]` |
| `concept_ship` |  | `[unregistered]` |
| `concept_ship_armor` |  | `[unregistered]` |
| `concept_ship_armor_desc` |  | `[unregistered]` |
| `concept_ship_complexity` |  | `[unregistered]` |
| `concept_ship_complexity_desc` |  | `[unregistered]` |
| `concept_ship_construction` |  | `[unregistered]` |
| `concept_ship_construction_capacity` |  | `[unregistered]` |
| `concept_ship_construction_capacity_desc` |  | `[unregistered]` |
| `concept_ship_construction_desc` |  | `[unregistered]` |
| `concept_ship_construction_queue` |  | `[unregistered]` |
| `concept_ship_construction_queue_desc` |  | `[unregistered]` |
| `concept_ship_crew` |  | `[unregistered]` |
| `concept_ship_crew_desc` |  | `[unregistered]` |
| `concept_ship_desc` |  | `[unregistered]` |
| `concept_ship_group` |  | `[unregistered]` |
| `concept_ship_group_desc` |  | `[unregistered]` |
| `concept_ship_hit_points` |  | `[unregistered]` |
| `concept_ship_hit_points_desc` |  | `[unregistered]` |
| `concept_ship_modification` |  | `[unregistered]` |
| `concept_ship_modification_desc` |  | `[unregistered]` |
| `concept_ship_retrofit` |  | `[unregistered]` |
| `concept_ship_retrofit_desc` |  | `[unregistered]` |
| `concept_ship_speed` |  | `[unregistered]` |
| `concept_ship_speed_desc` |  | `[unregistered]` |
| `concept_ship_template` |  | `[unregistered]` |
| `concept_ship_template_desc` |  | `[unregistered]` |
| `concept_ship_type` |  | `[unregistered]` |
| `concept_ship_type_desc` |  | `[unregistered]` |
| `concept_ship_under_construction` |  | `[unregistered]` |
| `concept_ship_under_construction_desc` |  | `[unregistered]` |
| `concept_ship_upkeep` |  | `[unregistered]` |
| `concept_ship_upkeep_desc` |  | `[unregistered]` |
| `concept_shipping_lane` |  | `[unregistered]` |
| `concept_shipping_lane_desc` |  | `[unregistered]` |
| `concept_shipping_lane_effectiveness` |  | `[unregistered]` |
| `concept_shipping_lane_effectiveness_desc` |  | `[unregistered]` |
| `concept_shortage` |  | `[unregistered]` |
| `concept_shortage_desc` |  | `[unregistered]` |
| `concept_slavery` |  | `[unregistered]` |
| `concept_slavery_desc` |  | `[unregistered]` |
| `concept_social_class` |  | `[unregistered]` |
| `concept_social_class_desc` |  | `[unregistered]` |
| `concept_social_hierarchy` |  | `[unregistered]` |
| `concept_social_hierarchy_desc` |  | `[unregistered]` |
| `concept_sol` |  | `[unregistered]` |
| `concept_sol_desc` |  | `[unregistered]` |
| `concept_sovereignty` |  | `[unregistered]` |
| `concept_sovereignty_desc` |  | `[unregistered]` |
| `concept_special_unit` |  | `[unregistered]` |
| `concept_special_unit_desc` |  | `[unregistered]` |
| `concept_split_state` |  | `[unregistered]` |
| `concept_split_state_desc` |  | `[unregistered]` |
| `concept_starvation` |  | `[unregistered]` |
| `concept_starvation_desc` |  | `[unregistered]` |
| `concept_state` |  | `[unregistered]` |
| `concept_state_desc` |  | `[unregistered]` |
| `concept_state_region` |  | `[unregistered]` |
| `concept_state_region_desc` |  | `[unregistered]` |
| `concept_state_religion` |  | `[unregistered]` |
| `concept_state_religion_desc` |  | `[unregistered]` |
| `concept_strait` |  | `[unregistered]` |
| `concept_strait_access` |  | `[unregistered]` |
| `concept_strait_access_desc` |  | `[unregistered]` |
| `concept_strait_allowed_countries` |  | `[unregistered]` |
| `concept_strait_allowed_countries_desc` |  | `[unregistered]` |
| `concept_strait_control` |  | `[unregistered]` |
| `concept_strait_control_desc` |  | `[unregistered]` |
| `concept_strait_desc` |  | `[unregistered]` |
| `concept_strategic_adjacency` |  | `[unregistered]` |
| `concept_strategic_adjacency_desc` |  | `[unregistered]` |
| `concept_strategic_desire` |  | `[unregistered]` |
| `concept_strategic_desire_desc` |  | `[unregistered]` |
| `concept_strategic_objective` |  | `[unregistered]` |
| `concept_strategic_objective_desc` |  | `[unregistered]` |
| `concept_strategic_region` |  | `[unregistered]` |
| `concept_strategic_region_desc` |  | `[unregistered]` |
| `concept_strategic_region_stance` |  | `[unregistered]` |
| `concept_strategic_region_stance_desc` |  | `[unregistered]` |
| `concept_subject` |  | `[unregistered]` |
| `concept_subject_action` |  | `[unregistered]` |
| `concept_subject_action_desc` |  | `[unregistered]` |
| `concept_subject_desc` |  | `[unregistered]` |
| `concept_subject_type` |  | `[unregistered]` |
| `concept_subject_type_desc` |  | `[unregistered]` |
| `concept_subsidies` |  | `[unregistered]` |
| `concept_subsidies_desc` |  | `[unregistered]` |
| `concept_subsidized_wage` |  | `[unregistered]` |
| `concept_subsidized_wage_desc` |  | `[unregistered]` |
| `concept_subsistence_building` |  | `[unregistered]` |
| `concept_subsistence_building_desc` |  | `[unregistered]` |
| `concept_subsistence_output` |  | `[unregistered]` |
| `concept_subsistence_output_desc` |  | `[unregistered]` |
| `concept_subventions` |  | `[unregistered]` |
| `concept_subventions_desc` |  | `[unregistered]` |
| `concept_sunk_ships` |  | `[unregistered]` |
| `concept_sunk_ships_desc` |  | `[unregistered]` |
| `concept_supply` |  | `[unregistered]` |
| `concept_supply_capacity` |  | `[unregistered]` |
| `concept_supply_capacity_desc` |  | `[unregistered]` |
| `concept_supply_desc` |  | `[unregistered]` |
| `concept_supply_efficiency` |  | `[unregistered]` |
| `concept_supply_efficiency_desc` |  | `[unregistered]` |
| `concept_supply_network` |  | `[unregistered]` |
| `concept_supply_network_desc` |  | `[unregistered]` |
| `concept_supply_priority` |  | `[unregistered]` |
| `concept_supply_priority_desc` |  | `[unregistered]` |
| `concept_supply_route` |  | `[unregistered]` |
| `concept_supply_route_desc` |  | `[unregistered]` |
| `concept_supply_ship` |  | `[unregistered]` |
| `concept_supply_ship_desc` |  | `[unregistered]` |
| `concept_suppress` |  | `[unregistered]` |
| `concept_suppress_desc` |  | `[unregistered]` |
| `concept_sway` |  | `[unregistered]` |
| `concept_sway_desc` |  | `[unregistered]` |
| `concept_sympathy` |  | `[unregistered]` |
| `concept_sympathy_desc` |  | `[unregistered]` |
| `concept_taboo` |  | `[unregistered]` |
| `concept_taboo_desc` |  | `[unregistered]` |
| `concept_target` |  | `[unregistered]` |
| `concept_target_desc` |  | `[unregistered]` |
| `concept_tariffs` |  | `[unregistered]` |
| `concept_tariffs_desc` |  | `[unregistered]` |
| `concept_tax_capacity` |  | `[unregistered]` |
| `concept_tax_capacity_desc` |  | `[unregistered]` |
| `concept_tax_waste` |  | `[unregistered]` |
| `concept_tax_waste_desc` |  | `[unregistered]` |
| `concept_taxes` |  | `[unregistered]` |
| `concept_taxes_desc` |  | `[unregistered]` |
| `concept_technology` |  | `[unregistered]` |
| `concept_technology_desc` |  | `[unregistered]` |
| `concept_technology_era` |  | `[unregistered]` |
| `concept_technology_era_desc` |  | `[unregistered]` |
| `concept_technology_spread` |  | `[unregistered]` |
| `concept_technology_spread_desc` |  | `[unregistered]` |
| `concept_tension` |  | `[unregistered]` |
| `concept_tension_desc` |  | `[unregistered]` |
| `concept_terrain` |  | `[unregistered]` |
| `concept_terrain_desc` |  | `[unregistered]` |
| `concept_terrain_labels` |  | `[unregistered]` |
| `concept_terrain_labels_desc` |  | `[unregistered]` |
| `concept_theater` |  | `[unregistered]` |
| `concept_theater_desc` |  | `[unregistered]` |
| `concept_throughput` |  | `[unregistered]` |
| `concept_throughput_desc` |  | `[unregistered]` |
| `concept_timed_modifier` |  | `[unregistered]` |
| `concept_timed_modifier_desc` |  | `[unregistered]` |
| `concept_tolls` |  | `[unregistered]` |
| `concept_tolls_desc` |  | `[unregistered]` |
| `concept_trade` |  | `[unregistered]` |
| `concept_trade_advantage` |  | `[unregistered]` |
| `concept_trade_advantage_desc` |  | `[unregistered]` |
| `concept_trade_capacity` |  | `[unregistered]` |
| `concept_trade_capacity_desc` |  | `[unregistered]` |
| `concept_trade_desc` |  | `[unregistered]` |
| `concept_trade_potential` |  | `[unregistered]` |
| `concept_trade_potential_desc` |  | `[unregistered]` |
| `concept_trade_privilege` |  | `[unregistered]` |
| `concept_trade_privilege_desc` |  | `[unregistered]` |
| `concept_trade_revenue` |  | `[unregistered]` |
| `concept_trade_revenue_desc` |  | `[unregistered]` |
| `concept_traded_quantity` |  | `[unregistered]` |
| `concept_traded_quantity_desc` |  | `[unregistered]` |
| `concept_tradition_trait` |  | `[unregistered]` |
| `concept_tradition_trait_desc` |  | `[unregistered]` |
| `concept_training_rate` |  | `[unregistered]` |
| `concept_training_rate_desc` |  | `[unregistered]` |
| `concept_transfer_of_power` |  | `[unregistered]` |
| `concept_transfer_of_power_desc` |  | `[unregistered]` |
| `concept_treasury` |  | `[unregistered]` |
| `concept_treasury_desc` |  | `[unregistered]` |
| `concept_treaty` |  | `[unregistered]` |
| `concept_treaty_desc` |  | `[unregistered]` |
| `concept_treaty_port` |  | `[unregistered]` |
| `concept_treaty_port_desc` |  | `[unregistered]` |
| `concept_tributary` |  | `[unregistered]` |
| `concept_tributary_desc` |  | `[unregistered]` |
| `concept_truce` |  | `[unregistered]` |
| `concept_truce_desc` |  | `[unregistered]` |
| `concept_turmoil` |  | `[unregistered]` |
| `concept_turmoil_desc` |  | `[unregistered]` |
| `concept_under_construction` |  | `[unregistered]` |
| `concept_under_construction_desc` |  | `[unregistered]` |
| `concept_unemployed` |  | `[unregistered]` |
| `concept_unemployed_desc` |  | `[unregistered]` |
| `concept_unification` |  | `[unregistered]` |
| `concept_unification_candidate` |  | `[unregistered]` |
| `concept_unification_candidate_desc` |  | `[unregistered]` |
| `concept_unification_desc` |  | `[unregistered]` |
| `concept_unification_supporter` |  | `[unregistered]` |
| `concept_unification_supporter_desc` |  | `[unregistered]` |
| `concept_unincorporated_state` |  | `[unregistered]` |
| `concept_unincorporated_state_desc` |  | `[unregistered]` |
| `concept_unit` |  | `[unregistered]` |
| `concept_unit_desc` |  | `[unregistered]` |
| `concept_unit_experience` |  | `[unregistered]` |
| `concept_unit_experience_desc` |  | `[unregistered]` |
| `concept_unrealized_taxes` |  | `[unregistered]` |
| `concept_unrealized_taxes_desc` |  | `[unregistered]` |
| `concept_unrecognized_power` |  | `[unregistered]` |
| `concept_unrecognized_power_desc` |  | `[unregistered]` |
| `concept_upper_strata` |  | `[unregistered]` |
| `concept_upper_strata_desc` |  | `[unregistered]` |
| `concept_urbanization` |  | `[unregistered]` |
| `concept_urbanization_desc` |  | `[unregistered]` |
| `concept_vassal` |  | `[unregistered]` |
| `concept_vassal_desc` |  | `[unregistered]` |
| `concept_veterancy_level` |  | `[unregistered]` |
| `concept_veterancy_level_desc` |  | `[unregistered]` |
| `concept_visibility` |  | `[unregistered]` |
| `concept_visibility_desc` |  | `[unregistered]` |
| `concept_votes` |  | `[unregistered]` |
| `concept_votes_desc` |  | `[unregistered]` |
| `concept_vulnerability` |  | `[unregistered]` |
| `concept_vulnerability_desc` |  | `[unregistered]` |
| `concept_war` |  | `[unregistered]` |
| `concept_war_desc` |  | `[unregistered]` |
| `concept_war_exhaustion` |  | `[unregistered]` |
| `concept_war_exhaustion_desc` |  | `[unregistered]` |
| `concept_war_goal` |  | `[unregistered]` |
| `concept_war_goal_desc` |  | `[unregistered]` |
| `concept_war_leader` |  | `[unregistered]` |
| `concept_war_leader_desc` |  | `[unregistered]` |
| `concept_war_reparations` |  | `[unregistered]` |
| `concept_war_reparations_desc` |  | `[unregistered]` |
| `concept_war_support` |  | `[unregistered]` |
| `concept_war_support_desc` |  | `[unregistered]` |
| `concept_wealth` |  | `[unregistered]` |
| `concept_wealth_desc` |  | `[unregistered]` |
| `concept_welfare_payments` |  | `[unregistered]` |
| `concept_welfare_payments_desc` |  | `[unregistered]` |
| `concept_withdrawn_ships` |  | `[unregistered]` |
| `concept_withdrawn_ships_desc` |  | `[unregistered]` |
| `concept_workforce` |  | `[unregistered]` |
| `concept_workforce_desc` |  | `[unregistered]` |
| `concept_working_adults` |  | `[unregistered]` |
| `concept_working_adults_desc` |  | `[unregistered]` |
| `concept_world_market` |  | `[unregistered]` |
| `concept_world_market_access` |  | `[unregistered]` |
| `concept_world_market_access_desc` |  | `[unregistered]` |
| `concept_world_market_desc` |  | `[unregistered]` |
| `concept_world_market_hub` |  | `[unregistered]` |
| `concept_world_market_hub_desc` |  | `[unregistered]` |
| `concept_world_market_price` |  | `[unregistered]` |
| `concept_world_market_price_desc` |  | `[unregistered]` |
| `concept_wounded` |  | `[unregistered]` |
| `concept_wounded_desc` |  | `[unregistered]` |
| `concept_zaibatsu` |  | `[unregistered]` |
| `concept_zaibatsu_desc` |  | `[unregistered]` |
| `CopyBuildVersionInfoToClipboard` |  | `void` |
| `CopyRNGSeedToClipboard` |  | `void` |
| `CreateNavalMissionsForSelectedFleets` | `Arg0` | `Command` |
| `DataModelFirst` | `Arg0, Arg1` | `[unregistered]` |
| `DataModelHasItems` | `Arg0` | `bool` |
| `DataModelLast` | `Arg0, Arg1` | `[unregistered]` |
| `DataModelSkipFirst` | `Arg0, Arg1` | `[unregistered]` |
| `DataModelSkipLast` | `Arg0, Arg1` | `[unregistered]` |
| `DataModelSubSpan` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `DebugGetMapMode` |  | `CString` |
| `DemobilizeSelectedArmies` |  | `Command` |
| `Divide_CFixedPoint` | `Arg0, Arg1` | `CFixedPoint` |
| `Divide_CVector2f` | `Arg0, Arg1` | `CVector2f` |
| `Divide_float` | `Arg0, Arg1` | `float` |
| `Divide_int32` | `Arg0, Arg1` | `int32` |
| `Divide_int64` | `Arg0, Arg1` | `int64` |
| `Divide_uint32` | `Arg0, Arg1` | `uint32` |
| `Divide_uint64` | `Arg0, Arg1` | `uint64` |
| `DoubleToFloat` | `Arg0` | `float` |
| `EqualTo_CFixedPoint` | `Arg0, Arg1` | `bool` |
| `EqualTo_CVector2f` | `Arg0, Arg1` | `bool` |
| `EqualTo_float` | `Arg0, Arg1` | `bool` |
| `EqualTo_int32` | `Arg0, Arg1` | `bool` |
| `EqualTo_int64` | `Arg0, Arg1` | `bool` |
| `EqualTo_string` | `Arg0, Arg1` | `bool` |
| `EqualTo_uint32` | `Arg0, Arg1` | `bool` |
| `EqualTo_uint64` | `Arg0, Arg1` | `bool` |
| `Execute` | `Arg0` | `void` |
| `FixedPointToFloat` | `Arg0` | `float` |
| `FixedPointToInt` | `Arg0` | `int32` |
| `FocusCameraOnCityOutOfState` |  | `void` |
| `GameHasMultiplePlayers` |  | `bool` |
| `GameIsMultiplayer` |  | `bool` |
| `GetAcceptanceStatus` | `Arg0` | `[unregistered]` |
| `GetAchievementsAvailableString` |  | `CString` |
| `GetActionLockInputText` |  | `CString` |
| `GetActivismLabelsDesc` |  | `CString` |
| `GetAIStrategy` | `Arg0` | `[unregistered]` |
| `GetAllPowerBlocs` |  | `[unregistered]` |
| `GetAmendmentType` | `Arg0` | `[unregistered]` |
| `GetApprovalRatingFromValue` | `Arg0` | `CString` |
| `GetArrowIcon_CFixedPoint` | `Arg0` | `CString` |
| `GetArrowIcon_int32` | `Arg0` | `CString` |
| `GetArrowIcon_int64` | `Arg0` | `CString` |
| `GetArticleType` | `Arg0` | `[unregistered]` |
| `GetAutosaveName` |  | `CString` |
| `GetBasicGeneralOrdersBreakdown` |  | `CString` |
| `GetBattalionGroupsList` |  | `CString` |
| `GetBattleCondition` | `Arg0` | `[unregistered]` |
| `GetBuildingGroup` | `Arg0` | `[unregistered]` |
| `GetBuildingType` | `Arg0` | `[unregistered]` |
| `GetBuildVersionDescriptionWithClickToCopy` |  | `CString` |
| `GetCanEditMissionSeaRegionsForSelectedFleetsDesc` |  | `CString` |
| `GetCharacterRole` | `Arg0` | `[unregistered]` |
| `GetCharacterTrait` | `Arg0` | `[unregistered]` |
| `GetCoastalBuildingTypesList` |  | `CString` |
| `GetCohesionLevel` | `Arg0` | `[unregistered]` |
| `GetCohesionLevels` |  | `[unregistered]` |
| `GetCombatUnitGroup` | `Arg0` | `[unregistered]` |
| `GetCombatUnitType` | `Arg0` | `[unregistered]` |
| `GetCommanderOrderType` | `Arg0` | `[unregistered]` |
| `GetCompanyCharterType` | `Arg0` | `[unregistered]` |
| `GetCompanyCharterTypes` |  | `[unregistered]` |
| `GetConfirmationDesc` | `Arg0` | `CString` |
| `GetConstructionSectorType` |  | `[unregistered]` |
| `GetContainer` | `Arg0` | `[unregistered]` |
| `GetCountryDiplomaticAction` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `GetCountryStrategicObjectiveInStateDesc` | `Arg0, Arg1` | `CString` |
| `GetCulture` | `Arg0` | `[unregistered]` |
| `GetCurrentFps` |  | `float` |
| `GetCurrentLoadingScreen` |  | `[unregistered]` |
| `GetDataModelSize` | `Arg0` | `int32` |
| `GetDecreeType` | `Arg0` | `[unregistered]` |
| `GetDefaultServerName` |  | `CUTF8String` |
| `GetDefine` | `Arg0, Arg1` | `[unregistered]` |
| `GetDefineAtIndex` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `GetDesc` | `Arg0` | `CString` |
| `GetDescriptiveText` | `Arg0` | `CString` |
| `GetDiplomaticActionType` | `Arg0` | `[unregistered]` |
| `GetDiplomaticPlayType` | `Arg0` | `[unregistered]` |
| `GetDiscordUrl` |  | `[unregistered]` |
| `GetDlcCollection` |  | `[unregistered]` |
| `GetDynTrendMax` | `Arg0` | `CFixedPoint` |
| `GetDynTrendMaxPadded` | `Arg0` | `CFixedPoint` |
| `GetDynTrendMin` | `Arg0` | `CFixedPoint` |
| `GetDynTrendMinPadded` | `Arg0` | `CFixedPoint` |
| `GetDynTrendPlotPoints` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `GetEconomicDependenceOnLabel` | `Arg0` | `CString` |
| `GetEnabledDlcNames` |  | `[unregistered]` |
| `GetEventOptionTextAlignment` |  | `[unregistered]` |
| `GetGameVersionDisplay` |  | `CString` |
| `GetGameVersionInfo` |  | `CString` |
| `GetGameVersionInfoShort` |  | `CString` |
| `GetGeographicRegion` | `Arg0` | `[unregistered]` |
| `GetGlobalList` | `Arg0` | `[unregistered]` |
| `GetGlobalMapKeys` | `Arg0` | `[unregistered]` |
| `GetGlobalMaxLandDefense` |  | `CFixedPoint` |
| `GetGlobalMaxLandOffense` |  | `CFixedPoint` |
| `GetGlobalRandomSeed` |  | `uint32` |
| `GetGlobalRandomSeedString` |  | `CString` |
| `GetGlobalVariable` | `Arg0` | `[unregistered]` |
| `GetGoods` | `Arg0` | `[unregistered]` |
| `GetGuiEntityShaderRenderpass` |  | `[unregistered]` |
| `GetGuiPositionFromPercentCoordinates` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `GetHarvestConditionType` | `Arg0` | `[unregistered]` |
| `GetHarvestConditionTypesList` |  | `CString` |
| `GetIdeology` | `Arg0` | `[unregistered]` |
| `GetInstitutionType` | `Arg0` | `[unregistered]` |
| `GetInteger` | `Arg0` | `int32` |
| `GetInterestGroupVariant` | `Arg0, Arg1` | `[unregistered]` |
| `GetInterestingCountrySettings` |  | `[unregistered]` |
| `GetInterestTierType` | `Arg0` | `[unregistered]` |
| `GetInterestTierTypes` |  | `[unregistered]` |
| `GetInterestTierTypesDesc` |  | `CString` |
| `GetInvParentScale` | `Arg0` | `float` |
| `GetJournalEntryGroup` | `Arg0` | `[unregistered]` |
| `GetLabel` | `Arg0` | `[unregistered]` |
| `GetLargeFlagFrameSize` |  | `CVector2i` |
| `GetLargePowerBlocCoaFrameSize` |  | `CVector2i` |
| `GetLatestDate` | `Arg0` | `CString` |
| `GetLawGroup` | `Arg0` | `[unregistered]` |
| `GetLawType` | `Arg0` | `[unregistered]` |
| `GetLegitimacyLevel` | `Arg0` | `[unregistered]` |
| `GetLegitimacyLevels` |  | `[unregistered]` |
| `GetLensToolbar` |  | `[unregistered]` |
| `GetLibertyDesireLevel` | `Arg0` | `[unregistered]` |
| `GetLibertyDesireLevels` |  | `[unregistered]` |
| `GetLoadingScreenManager` |  | `[unregistered]` |
| `GetLocalizedDefine` | `Arg0, Arg1` | `CString` |
| `GetLocalizedDefineAtIndex` | `Arg0, Arg1, Arg2` | `CString` |
| `GetLoyaltyTypes` |  | `[unregistered]` |
| `GetManpowerColorVec` | `Arg0` | `CVector4f` |
| `GetMapMode` | `Arg0` | `[unregistered]` |
| `GetMapModeIcon` | `Arg0` | `[unregistered]` |
| `GetMapModeIndices` |  | `[unregistered]` |
| `GetMapModeName` | `Arg0` | `CString` |
| `GetMapPerspectiveCountry` |  | `[unregistered]` |
| `GetMax` | `Arg0` | `CFixedPoint` |
| `GetMaxPadded` | `Arg0` | `CFixedPoint` |
| `GetMediumFlagFrameSize` |  | `CVector2i` |
| `GetMediumPowerBlocCoaFrameSize` |  | `CVector2i` |
| `GetMetaPlayer` |  | `[unregistered]` |
| `GetMin` | `Arg0` | `CFixedPoint` |
| `GetMinPadded` | `Arg0` | `CFixedPoint` |
| `GetMobilizationOption` | `Arg0` | `[unregistered]` |
| `GetMobilizationOptionGroup` | `Arg0` | `[unregistered]` |
| `GetMobilizationOptionGroups` |  | `[unregistered]` |
| `GetMoraleColorString` | `Arg0` | `CString` |
| `GetMoraleColorVec` | `Arg0` | `CVector4f` |
| `GetMPChecksum` |  | `CString` |
| `GetNavalBattleCondition` | `Arg0` | `[unregistered]` |
| `GetNavalMissionType` | `Arg0` | `[unregistered]` |
| `GetNavalMissionTypes` |  | `[unregistered]` |
| `GetNumberAbove_int32` | `Arg0, Arg1` | `int32` |
| `GetNumberOfSelectedFleetsDifferentNavalMissionTypes` |  | `int32` |
| `GetNumberOfShadersCompiled` |  | `int32` |
| `GetNumCoastalBuildingTypes` |  | `int32` |
| `GetNumCommandersInSelectedFormations` |  | `int32` |
| `GetNumCommandersInSelectedFormationsWithOrderActive` | `Arg0` | `int32` |
| `GetNumCommandersInSelectedFormationsWithOrderBlocked` | `Arg0` | `int32` |
| `GetNumCommandersInSelectedFormationsWithOrderNext` | `Arg0` | `int32` |
| `GetNumCommandersInSelectedFormationsWithOrderPossible` | `Arg0` | `int32` |
| `GetNumSelectedArmies` |  | `int32` |
| `GetNumSelectedArmiesWithDemobilizationActive` |  | `int32` |
| `GetNumSelectedArmiesWithDemobilizationBlocked` |  | `int32` |
| `GetNumSelectedArmiesWithDemobilizationPossible` |  | `int32` |
| `GetNumSelectedArmiesWithMobilizationActive` |  | `int32` |
| `GetNumSelectedArmiesWithMobilizationBlocked` |  | `int32` |
| `GetNumSelectedArmiesWithMobilizationPossible` |  | `int32` |
| `GetNumSelectedArmiesWithRaiseConscriptsActive` |  | `int32` |
| `GetNumSelectedArmiesWithRaiseConscriptsBlocked` |  | `int32` |
| `GetNumSelectedArmiesWithRaiseConscriptsPossible` |  | `int32` |
| `GetNumSelectedFleets` |  | `int32` |
| `GetNumSelectedFormations` |  | `int32` |
| `GetOldestDate` | `Arg0` | `CString` |
| `GetOpenLobbyTooltip` |  | `CString` |
| `GetOrganizationColorVec` | `Arg0` | `CVector4f` |
| `GetPlayer` |  | `[unregistered]` |
| `GetPlayerResourcesUrl` |  | `[unregistered]` |
| `GetPopNeed` | `Arg0` | `[unregistered]` |
| `GetPopType` | `Arg0` | `[unregistered]` |
| `GetPortraitRenderSize` | `Arg0` | `CVector2f` |
| `GetPortraitTextureFromDna` | `Arg0, Arg1` | `[unregistered]` |
| `GetPowerBlocIdentity` | `Arg0` | `[unregistered]` |
| `GetPowerBlocPrincipleGroup` | `Arg0` | `[unregistered]` |
| `GetPrevTrendValue` | `Arg0` | `CFixedPoint` |
| `GetPrevTrendValueFor` | `Arg0, Arg1` | `CFixedPoint` |
| `GetRandomLogInfo` |  | `CString` |
| `GetRankModifier` | `Arg0` | `[unregistered]` |
| `GetRawTextTooltipTag` | `Arg0` | `CString` |
| `GetRawTrendPlotRectWithFixedY` | `Arg0, Arg1, Arg2` | `CPdxFloatRect` |
| `GetReligion` | `Arg0` | `[unregistered]` |
| `GetResolutionWithAspectRatio` |  | `CVector2f` |
| `GetRomanNumeral` | `Arg0` | `CString` |
| `GetSelectedFleetsMissionRegionsBreakdown` |  | `CString` |
| `GetSelectedFleetsMissionSeaRegions` |  | `[unregistered]` |
| `GetSelectedFleetsNavalMissionType` |  | `[unregistered]` |
| `GetSelectedFleetsPotentialAndPossibleMissions` |  | `[unregistered]` |
| `GetSelectedFormationsList` |  | `CString` |
| `GetSelectedMapMode` |  | `CVector2i` |
| `GetSelectedMapModeIcon` |  | `[unregistered]` |
| `GetSelectedMapModeName` |  | `CString` |
| `GetShipGroup` | `Arg0` | `[unregistered]` |
| `GetShipGroups` |  | `[unregistered]` |
| `GetShipModificationSlotType` | `Arg0` | `[unregistered]` |
| `GetShipModificationType` | `Arg0` | `[unregistered]` |
| `GetShipType` | `Arg0` | `[unregistered]` |
| `GetShipTypes` |  | `[unregistered]` |
| `GetShipVeterancyLevel` | `Arg0` | `[unregistered]` |
| `GetSmallFlagFrameSize` |  | `CVector2i` |
| `GetSmallPowerBlocCoaFrameSize` |  | `CVector2i` |
| `GetStarvationTypes` |  | `[unregistered]` |
| `GetStateRegion` | `Arg0` | `[unregistered]` |
| `GetStaticModifier` | `Arg0` | `[unregistered]` |
| `GetStrategicRegion` | `Arg0` | `[unregistered]` |
| `GetString_CPdxFloatRect` | `Arg0` | `CString` |
| `GetString_CPdxIntRect` | `Arg0` | `CString` |
| `GetString_CVector2f` | `Arg0` | `CString` |
| `GetString_CVector2i` | `Arg0` | `CString` |
| `GetString_CVector3f` | `Arg0` | `CString` |
| `GetString_CVector3i` | `Arg0` | `CString` |
| `GetString_CVector4f` | `Arg0` | `CString` |
| `GetString_CVector4i` | `Arg0` | `CString` |
| `GetSubjectType` | `Arg0` | `[unregistered]` |
| `GetSubjectTypes` |  | `[unregistered]` |
| `GetSubjectTypesList` |  | `CString` |
| `GetSupplyNetworkColorstring` | `Arg0` | `CString` |
| `GetSupportLabelsDesc` |  | `CString` |
| `GetTechnology` | `Arg0` | `[unregistered]` |
| `GetTrendIcon` | `Arg0` | `CString` |
| `GetTrendIconFor` | `Arg0, Arg1` | `CString` |
| `GetTrendPlotPoints` | `Arg0` | `[unregistered]` |
| `GetTrendPlotPointsAbsolute` | `Arg0` | `[unregistered]` |
| `GetTrendPlotPointsNormalized` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `GetTrendValue` | `Arg0` | `CFixedPoint` |
| `GetTrendValueFor` | `Arg0, Arg1` | `CFixedPoint` |
| `GetUnitStrengthHeader` | `Arg0, Arg1, Arg2` | `CString` |
| `GetUnitStrengthHeaderNoIcon` | `Arg0, Arg1` | `CString` |
| `GetVariableFromGlobalVariableMap` | `Arg0, Arg1` | `[unregistered]` |
| `GetVarTimeRemaining` | `Arg0, Arg1` | `int32` |
| `GetVeryLargePowerBlocCoaFrameSize` |  | `CVector2i` |
| `GetVerySmallPowerBlocCoaFrameSize` |  | `CVector2i` |
| `GetWarGoalType` | `Arg0` | `[unregistered]` |
| `GetWikiUrl` |  | `[unregistered]` |
| `GetYoutubeChannelUrl` |  | `[unregistered]` |
| `GlobalVariableMapContainsKey` | `Arg0, Arg1` | `bool` |
| `GlobalVariableMapContainsValue` | `Arg0, Arg1` | `bool` |
| `GlobalVariableMapExists` | `Arg0` | `bool` |
| `GreaterThan_CFixedPoint` | `Arg0, Arg1` | `bool` |
| `GreaterThan_float` | `Arg0, Arg1` | `bool` |
| `GreaterThan_int32` | `Arg0, Arg1` | `bool` |
| `GreaterThan_int64` | `Arg0, Arg1` | `bool` |
| `GreaterThan_uint32` | `Arg0, Arg1` | `bool` |
| `GreaterThan_uint64` | `Arg0, Arg1` | `bool` |
| `GreaterThanOrEqualTo_CFixedPoint` | `Arg0, Arg1` | `bool` |
| `GreaterThanOrEqualTo_float` | `Arg0, Arg1` | `bool` |
| `GreaterThanOrEqualTo_int32` | `Arg0, Arg1` | `bool` |
| `GreaterThanOrEqualTo_int64` | `Arg0, Arg1` | `bool` |
| `GreaterThanOrEqualTo_uint32` | `Arg0, Arg1` | `bool` |
| `GreaterThanOrEqualTo_uint64` | `Arg0, Arg1` | `bool` |
| `HasActionLock` |  | `bool` |
| `HasAnyAvailableNewThemes` |  | `bool` |
| `HasAnySelections` | `Arg0` | `bool` |
| `HasAnyThemeIssues` |  | `bool` |
| `HasCitiesOutOfState` |  | `bool` |
| `HasDefaultMapMode` |  | `bool` |
| `HasDlcFeature` | `Arg0` | `bool` |
| `HasGameLoadedToMainMenu` |  | `bool` |
| `HasGameStartedForTheFirstTime` |  | `bool` |
| `HasGameState` |  | `bool` |
| `HasMouseTendency` |  | `bool` |
| `HasValidSelectedFormationsToCancelStrategicObjective` | `Arg0` | `bool` |
| `HasValidSelectedFormationsToSetStrategicObjective` | `Arg0` | `bool` |
| `IntToFixedPoint` | `Arg0` | `float` |
| `IntToFloat` | `Arg0` | `float` |
| `IntToUnsigned` | `Arg0` | `float` |
| `IsCurrentProductionMethod` | `Arg0` | `bool` |
| `IsDataModelEmpty` | `Arg0` | `bool` |
| `IsDrawCityDebugGrid` |  | `bool` |
| `IsDrawCityDebugSpheres` |  | `bool` |
| `IsDynamicsEnabled` |  | `bool` |
| `IsDynamicTerrainAutoUpdate` |  | `bool` |
| `IsDynTrendEmpty` | `Arg0` | `bool` |
| `IsEmpty` | `Arg0` | `bool` |
| `IsEven_int32` | `Arg0` | `bool` |
| `IsEven_int64` | `Arg0` | `bool` |
| `IsEven_uint32` | `Arg0` | `bool` |
| `IsEven_uint64` | `Arg0` | `bool` |
| `IsGameChecksumOk` |  | `bool` |
| `IsGameOverScreenShown` |  | `bool` |
| `IsGamePaused` |  | `bool` |
| `IsHost` |  | `bool` |
| `IsInGame` |  | `bool` |
| `IsIronmanEnabled` |  | `bool` |
| `IsLoadedFromSave` |  | `bool` |
| `IsMapModeIndexSelected` | `Arg0` | `bool` |
| `IsMapModeLocked` |  | `bool` |
| `IsMapModeSelected` | `Arg0` | `bool` |
| `IsObserver` |  | `bool` |
| `IsOdd_int32` | `Arg0` | `bool` |
| `IsOdd_int64` | `Arg0` | `bool` |
| `IsOdd_uint32` | `Arg0` | `bool` |
| `IsOdd_uint64` | `Arg0` | `bool` |
| `IsPauseMenuShown` |  | `bool` |
| `IsPotential` | `Arg0` | `bool` |
| `IsPreparationLobby` |  | `bool` |
| `IsRedundant` | `Arg0` | `bool` |
| `IsSaving` |  | `bool` |
| `IsTerrainManipulatorProvincesPreview` |  | `bool` |
| `IsTutorialLessonActive` | `Arg0` | `bool` |
| `IsValid` | `Arg0` | `bool` |
| `IsZoomLevelFar` |  | `bool` |
| `IsZoomLevelMax` |  | `bool` |
| `IsZoomLevelMid` |  | `bool` |
| `IsZoomLevelNear` |  | `bool` |
| `JoinText` | `Arg0, Arg1, Arg2` | `CString` |
| `JominiAccessPlayerJoinRequests` |  | `[unregistered]` |
| `JominiGetMultiplayerAccessibleString` |  | `CString` |
| `JominiHasPlayerJoinRequests` |  | `bool` |
| `JominiIsHostOrLocal` |  | `bool` |
| `JominiIsMultiplayerAccessible` |  | `bool` |
| `JominiMultiplayerIsCrossplayEnabled` |  | `bool` |
| `JominiMultiplayerIsCrossplayFilterAvailable` |  | `bool` |
| `LessThan_CFixedPoint` | `Arg0, Arg1` | `bool` |
| `LessThan_float` | `Arg0, Arg1` | `bool` |
| `LessThan_int32` | `Arg0, Arg1` | `bool` |
| `LessThan_int64` | `Arg0, Arg1` | `bool` |
| `LessThan_uint32` | `Arg0, Arg1` | `bool` |
| `LessThan_uint64` | `Arg0, Arg1` | `bool` |
| `LessThanOrEqualTo_CFixedPoint` | `Arg0, Arg1` | `bool` |
| `LessThanOrEqualTo_float` | `Arg0, Arg1` | `bool` |
| `LessThanOrEqualTo_int32` | `Arg0, Arg1` | `bool` |
| `LessThanOrEqualTo_int64` | `Arg0, Arg1` | `bool` |
| `LessThanOrEqualTo_uint32` | `Arg0, Arg1` | `bool` |
| `LessThanOrEqualTo_uint64` | `Arg0, Arg1` | `bool` |
| `Localize` | `Arg0` | `CString` |
| `LocalizeInputAction` | `Arg0` | `CString` |
| `MakeScopeBool` | `Arg0` | `Scope` |
| `MakeScopeFlag` | `Arg0` | `Scope` |
| `MakeScopeValue` | `Arg0` | `Scope` |
| `Max_CFixedPoint` | `Arg0, Arg1` | `CFixedPoint` |
| `Max_float` | `Arg0, Arg1` | `float` |
| `Max_int32` | `Arg0, Arg1` | `int32` |
| `Max_int64` | `Arg0, Arg1` | `int64` |
| `Max_uint32` | `Arg0, Arg1` | `uint32` |
| `Max_uint64` | `Arg0, Arg1` | `uint64` |
| `MergeSelectedFormations` |  | `Command` |
| `Min_CFixedPoint` | `Arg0, Arg1` | `CFixedPoint` |
| `Min_float` | `Arg0, Arg1` | `float` |
| `Min_int32` | `Arg0, Arg1` | `int32` |
| `Min_int64` | `Arg0, Arg1` | `int64` |
| `Min_uint32` | `Arg0, Arg1` | `uint32` |
| `Min_uint64` | `Arg0, Arg1` | `uint64` |
| `MobilizeSelectedArmies` |  | `Command` |
| `Modulo_int32` | `Arg0, Arg1` | `int32` |
| `Modulo_int64` | `Arg0, Arg1` | `int64` |
| `Modulo_uint32` | `Arg0, Arg1` | `uint32` |
| `Modulo_uint64` | `Arg0, Arg1` | `uint64` |
| `Multiply_CFixedPoint` | `Arg0, Arg1` | `CFixedPoint` |
| `Multiply_CVector2f` | `Arg0, Arg1` | `CVector2f` |
| `Multiply_float` | `Arg0, Arg1` | `float` |
| `Multiply_int32` | `Arg0, Arg1` | `int32` |
| `Multiply_int64` | `Arg0, Arg1` | `int64` |
| `Multiply_uint32` | `Arg0, Arg1` | `uint32` |
| `Multiply_uint64` | `Arg0, Arg1` | `uint64` |
| `Nbsp` |  | `CString` |
| `Negate_CFixedPoint` | `Arg0` | `CFixedPoint` |
| `Negate_float` | `Arg0` | `float` |
| `Negate_int32` | `Arg0` | `int32` |
| `Negate_int64` | `Arg0` | `int64` |
| `NoSelectedFleetsHaveNavalMissions` |  | `bool` |
| `NotEqualTo_CFixedPoint` | `Arg0, Arg1` | `bool` |
| `NotEqualTo_CVector2f` | `Arg0, Arg1` | `bool` |
| `NotEqualTo_float` | `Arg0, Arg1` | `bool` |
| `NotEqualTo_int32` | `Arg0, Arg1` | `bool` |
| `NotEqualTo_int64` | `Arg0, Arg1` | `bool` |
| `NotEqualTo_uint32` | `Arg0, Arg1` | `bool` |
| `NotEqualTo_uint64` | `Arg0, Arg1` | `bool` |
| `ObjectsEqual` | `Arg0, Arg1` | `bool` |
| `ObserveCountryCommand` | `Arg0` | `Command` |
| `OnEditSelectedFleetsSeaRegionsClicked` |  | `void` |
| `OnToggleLoginWindow` |  | `void` |
| `OpenAchievements` |  | `void` |
| `OpenDiscordUrl` |  | `void` |
| `OpenGameRules` |  | `void` |
| `OpenPlayerResourcesUrl` |  | `void` |
| `OpenWikiUrl` |  | `void` |
| `OpenYoutubeChannelUrl` |  | `void` |
| `PauseAllConstruction` |  | `Command` |
| `PauseAllConstructionTooltip` |  | `CString` |
| `PdxClearEditBoxText` | `Arg0` | `void` |
| `PdxGetProfilerNames` |  | `[unregistered]` |
| `PdxGetWidgetScreenSize` | `Arg0` | `CVector2f` |
| `PdxGuiEditboxGetText` | `Arg0` | `CUTF8String` |
| `PdxGuiInterruptAllAnimations` | `Arg0` | `void` |
| `PdxGuiInterruptThenTriggerAllAnimations` | `Arg0, Arg1` | `void` |
| `PdxGuiTriggerAllAnimations` | `Arg0` | `void` |
| `PdxProfilerFilterNext` |  | `void` |
| `PdxProfilerFilterPrev` |  | `void` |
| `PdxProfilerFilterTimers` |  | `void` |
| `PdxProfilerGetCurrentFrame` |  | `int32` |
| `PdxProfilerGetFrameTimeMs` |  | `float` |
| `PdxProfilerGetNsPerTick` |  | `float` |
| `PdxProfilerGuiGraphLinesEnabled` |  | `bool` |
| `PdxProfilerGuiToggleGraphLines` |  | `void` |
| `PdxProfilerGuiToggleStats` |  | `void` |
| `PdxProfilerGuiTrackCurrentFrame` |  | `void` |
| `PdxProfilerGuiWriteFrameCSV` |  | `void` |
| `PdxProfilerIsRecording` |  | `bool` |
| `PdxProfilerSelectThread` |  | `void` |
| `PdxProfilerSetFrame` |  | `void` |
| `PdxProfilerToggleRecording` |  | `void` |
| `PopCursorOverride` |  | `void` |
| `PushCursorOverride` | `Arg0` | `void` |
| `RaiseConscriptsInSelectedArmies` |  | `Command` |
| `ReleaseMode` |  | `bool` |
| `RemoveNavalMissionForSelectedFleets` | `Arg0` | `Command` |
| `RemoveSelectedFleetsMissions` |  | `Command` |
| `RemoveTempMapMode` |  | `void` |
| `ResetCursorOverrides` |  | `void` |
| `ResumeAllConstruction` |  | `Command` |
| `ResumeAllConstructionTooltip` |  | `CString` |
| `RetrofitShips` |  | `Command` |
| `RetrofitShipsAndStation` |  | `Command` |
| `ReturnToMenu` |  | `void` |
| `ScaleToFitElementInside` | `Arg0, Arg1` | `float` |
| `ScaleToFitElementOutside` | `Arg0, Arg1` | `float` |
| `ScrollPanelToNamedWidget` | `Arg0, Arg1` | `void` |
| `ScrollPanelToTop` | `Arg0` | `void` |
| `Select_CFixedPoint` | `Arg0, Arg1, Arg2` | `CFixedPoint` |
| `Select_CString` | `Arg0, Arg1, Arg2` | `CString` |
| `Select_CVector2f` | `Arg0, Arg1, Arg2` | `CVector2f` |
| `Select_CVector2i` | `Arg0, Arg1, Arg2` | `CVector2i` |
| `Select_CVector3f` | `Arg0, Arg1, Arg2` | `CVector3f` |
| `Select_CVector3i` | `Arg0, Arg1, Arg2` | `CVector3i` |
| `Select_CVector4f` | `Arg0, Arg1, Arg2` | `CVector4f` |
| `Select_CVector4i` | `Arg0, Arg1, Arg2` | `CVector4i` |
| `Select_float` | `Arg0, Arg1, Arg2` | `float` |
| `Select_int16` | `Arg0, Arg1, Arg2` | `int16` |
| `Select_int32` | `Arg0, Arg1, Arg2` | `int32` |
| `Select_int64` | `Arg0, Arg1, Arg2` | `int64` |
| `Select_int8` | `Arg0, Arg1, Arg2` | `int8` |
| `Select_uint16` | `Arg0, Arg1, Arg2` | `uint16` |
| `Select_uint32` | `Arg0, Arg1, Arg2` | `uint32` |
| `Select_uint64` | `Arg0, Arg1, Arg2` | `uint64` |
| `Select_uint8` | `Arg0, Arg1, Arg2` | `uint8` |
| `SelectedFleetsHaveEquivalentNavalMissionAreas` |  | `bool` |
| `SelectedFleetsHaveNavalMissionType` | `Arg0` | `bool` |
| `SelectedFleetsHaveTheSameNavalMissionType` |  | `bool` |
| `SelectLocalization` | `Arg0, Arg1, Arg2` | `CString` |
| `SelectSound` | `Arg0, Arg1, Arg2` | `[unregistered]` |
| `SetCanOpenRightClickContextMenu` | `Arg0` | `void` |
| `SetCharacterOrderForSelectedFormations` | `Arg0` | `Command` |
| `SetDefaultMapMode` |  | `void` |
| `SetDrawCityDebugGrid` | `Arg0` | `void` |
| `SetDrawCityDebugSpheres` | `Arg0` | `void` |
| `SetDynamicsEnabled` | `Arg0` | `void` |
| `SetDynamicTerrainAutoUpdate` | `Arg0` | `void` |
| `SetInteraction` | `Arg0` | `void` |
| `SetIronmanEnabledStatus` | `Arg0` | `void` |
| `SetRandomPlayableObserverCharacter` |  | `void` |
| `SetStrategicObjective` | `Arg0, Arg1` | `Command` |
| `SetStrategicObjectiveForSelectedFormations` | `Arg0` | `Command` |
| `SetTempMapModeByKey` | `Arg0` | `void` |
| `SetTerrainManipulatorProvincesPreview` | `Arg0` | `void` |
| `ShouldAskConfirmation` | `Arg0` | `bool` |
| `ShouldShowAnimationInfo` |  | `bool` |
| `StatusCanLogin` |  | `bool` |
| `StatusGetLoginStatus` |  | `CUTF8String` |
| `StatusGetUserEmailMasked` |  | `CUTF8String` |
| `StatusGetUserName` |  | `CUTF8String` |
| `StatusIsAccountConnected` |  | `bool` |
| `StatusIsLoggedIn` |  | `bool` |
| `StatusIsLoggingIn` |  | `bool` |
| `StatusIsOffline` |  | `bool` |
| `StatusIsSupportConnectedAccount` |  | `bool` |
| `StatusIsUserNameEmpty` |  | `bool` |
| `StringIsEmpty` | `Arg0` | `bool` |
| `Subtract_CFixedPoint` | `Arg0, Arg1` | `CFixedPoint` |
| `Subtract_CVector2f` | `Arg0, Arg1` | `CVector2f` |
| `Subtract_float` | `Arg0, Arg1` | `float` |
| `Subtract_int32` | `Arg0, Arg1` | `int32` |
| `Subtract_int64` | `Arg0, Arg1` | `int64` |
| `Subtract_uint32` | `Arg0, Arg1` | `uint32` |
| `Subtract_uint64` | `Arg0, Arg1` | `uint64` |
| `TextureListFormatkB` | `Arg0` | `CString` |
| `TextureListFormatSize` | `Arg0` | `CString` |
| `TimerOrActionLock` |  | `bool` |
| `ToggleEncyclopedia` |  | `void` |
| `ToggleInteraction` | `Arg0` | `void` |
| `ToggleMainMenu` |  | `void` |
| `ToggleMapModeLock` |  | `void` |
| `ToggleMessageSettings` |  | `void` |
| `ToggleMessageSettingsForSingleItem` | `Arg0` | `void` |
| `ToggleMusicPlayer` |  | `void` |
| `ToggleObserveCountry` | `Arg0` | `void` |
| `ToggleThemeSettings` |  | `void` |
| `ToString_int16` | `Arg0` | `CString` |
| `ToString_int32` | `Arg0` | `CString` |
| `ToString_int64` | `Arg0` | `CString` |
| `ToString_int8` | `Arg0` | `CString` |
| `ToString_uint16` | `Arg0` | `CString` |
| `ToString_uint32` | `Arg0` | `CString` |
| `ToString_uint64` | `Arg0` | `CString` |
| `ToString_uint8` | `Arg0` | `CString` |
| `TransparentIfFalse` | `Arg0` | `float` |
| `TransparentIfTrue` | `Arg0` | `float` |
| `TransparentIfZero` | `Arg0` | `float` |
| `TransparentIfZero_int32` | `Arg0` | `float` |
| `TransparentIfZero_int64` | `Arg0` | `float` |
| `UpdateDynamicTerrainInAllProvinces` |  | `void` |
| `UsesTimerLocking` |  | `bool` |
| `Vector3fToColor` | `Arg0` | `CVector4f` |
| `Vector3iToColor` | `Arg0` | `CVector4f` |
| `Vector4iToColor` | `Arg0` | `CVector4f` |

## Jomini Achievements

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `JominiAreAchievementsAvailable` |  | `bool` | Jomini Achievements - Are achievements available? |
| `JominiGetAchievementsNotAvailableString` |  | `CString` | Jomini Achievements - Get text why achievements are not available |

## Jomini Script Systen

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `JominiPlayer` |  | `[unregistered]` | Jomini Script Systen - Get generic current playable object |

## Map Editor

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMapEditorLayerBorders` |  | `[unregistered]` | Map Editor - Access all Layer borders |
| `GetSmartBrushInterpolationNames` |  | `[unregistered]` | Map Editor - Smart Material Painter - Interpolation Names |
| `GetSmartBrushPatternNames` |  | `[unregistered]` | Map Editor - Smart Material Painter - Pattern Names |
| `IsCameraRestrictionsEnabled` |  | `bool` | Map Editor - If camera restrictions are on |
| `SetCameraRestrictionsEnabled` | `Arg0` | `void` | Map Editor - Set camera restrictions toggle |

## Multiplayer

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `CanEditSettingsAfterHost` |  | `bool` | Multiplayer - If you can edit settings after hosting (depends on MP platform) |
| `ClearHostError` |  | `void` | Multiplayer - Clear host error |
| `CopyServerID` |  | `void` | Multiplayer - Copy Server ID of current session to clipboard |
| `GetHostError` |  | `CUTF8String` | Multiplayer - Get host error |
| `GetPlayersCount` |  | `int32` | Multiplayer - No of players of current session |
| `HasHostError` |  | `bool` | Multiplayer - Does the host have an error |

## Multiplayer GUI

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `GetCanGoToFrontend` |  | `bool` | Multiplayer GUI - Can we go back to the frontend? |
| `GetCanGoToFrontendDesc` |  | `CString` | Multiplayer GUI - Message if we can't go back to the frontend |
| `GoToFrontend` |  | `void` | Multiplayer GUI - Go back to the frontend |
| `PlayerIsHost` |  | `bool` | Multiplayer GUI - Is the current player the host? |

## Portrait System

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `GetEthnicities` |  | `[unregistered]` | Portrait System - Get all Ethnicities |

## Settings

| Function | Arguments | Returns | Description |
|---|---|---|---|
| `GetEnumIndex` | `Arg0` | `CVector2i` | Settings - Get the dropdown index of an enum setting. |
| `GetIsChecked` | `Arg0` | `bool` | Settings - If the bool setting is checked |
| `GetStringSettingText` | `Arg0` | `CString` | Settings - Get the string setting text |
| `SelectEnumWithString` | `Arg0, Arg1` | `void` | Settings - Select enum by string input |
| `ShouldShowSegmentedControlForSetting` | `Arg0` | `bool` | Settings - Should show segmented control or not? |

## Macros

Macros are expanded by the expression parser before evaluation. They are defined in `data_binding/gui_macros.txt`.

| Macro | Arguments | Expands to | Description |
|---|---|---|---|
| `FactorToMult` | `Value` | `Subtract_CFixedPoint(Value, '(CFixedPoint)1')` | Transforms factor (1.25) to mult (0.25) by subtracting 1 from the value |
| `GreaterThanZero` | `Value` | `GreaterThan_int32(Value, '(int32)0')` | Tests if a int32 is greater than zero or not |
| `GreaterThanZero_CFixedPoint` | `Value` | `GreaterThan_CFixedPoint(Value, '(CFixedPoint)0')` | Tests if a CFixedPoint is greater than zero or not |
| `IsZero` | `Value` | `EqualTo_int32(Value, '(int32)0')` | Tests if a int32 is zero or not |
| `IsZero_CFixedPoint` | `Value` | `EqualTo_CFixedPoint(Value, '(CFixedPoint)0')` | Tests if a CFixedPoint is zero or not |
| `IsZero_int64` | `Value` | `EqualTo_int64(Value, '(int64)0')` | Tests if a int64 is zero or not |
| `LessThanZero` | `Value` | `LessThan_int32(Value, '(int32)0')` | Tests if a int32 is greater than zero or not |
| `LessThanZero_CFixedPoint` | `Value` | `LessThan_CFixedPoint(Value, '(CFixedPoint)0')` | Tests if a CFixedPoint is less than zero or not |
| `MakeLineIf` | `Condition, LocKey` | `ConcatIfNeitherEmpty(AddLocalizationIf(Condition, LocKey), Localize( 'NEWLINE' ))` | Add a loc key with a trailing newline if a condition is satisfied |
| `MakeParagraphIf` | `Condition, LocKey` | `ConcatIfNeitherEmpty(AddLocalizationIf(Condition, LocKey), Localize( 'DOUBLE_NEWLINE' ))` | Add a loc key with a double trailing newline if a condition is satisfied |
| `Negate` | `Value` | `Subtract_CFixedPoint('(CFixedPoint)0', Value)` | Change the sign of the value |
| `NotZero` | `Value` | `NotEqualTo_int32(Value, '(int32)0')` | Tests if a int32 is zero or not |
| `NotZero_CFixedPoint` | `Value` | `NotEqualTo_CFixedPoint(Value, '(CFixedPoint)0')` | Tests if a CFixedPoint is zero or not |
| `NotZero_int64` | `Value` | `NotEqualTo_int64(Value, '(int64)0')` | Tests if a int64 is zero or not |

## Global getters

Global promotes are implicit conversions rather than function calls. Most of them are named scope accessors: writing the name yields an object of the given type.

| Name | Yields | Description |
|---|---|---|
| `ACCEPTANCE_STATUS` | `AcceptanceStatus` |  |
| `AccessGameRules` | `JominiGameRules` |  |
| `AccessHighlightManager` | `HighlightManager` |  |
| `AccessLogViewer` | `LogViewer` | Access Central Log Viewer |
| `AccessMetaPlayer` | `Player` |  |
| `AccessPlayer` | `Country` |  |
| `AccessPlayerJournalEntry` | `JournalEntry` |  |
| `AccessScopeReference` | `Scope` |  |
| `AIATTITUDE` | `AIAttitude` |  |
| `AISTRATEGIC_REGION_STANCE_TYPE` | `AIStrategicRegionStanceType` |  |
| `AISTRATEGY` | `AIStrategy` |  |
| `ALERT` | `Alert` |  |
| `ALERT_GROUP` | `AlertGroup` |  |
| `ALLY_COUNTRY` | `Country` |  |
| `AMENDMENT` | `Amendment` |  |
| `AMENDMENT_TYPE` | `AmendmentType` |  |
| `Application` | `Application` |  |
| `BATTLE` | `Battle` |  |
| `BATTLE_CONDITION` | `BattleCondition` |  |
| `BUILDING` | `Building` |  |
| `BUILDING_GROUP` | `BuildingGroup` |  |
| `BUILDING_OWNERSHIP` | `BuildingOwnership` |  |
| `BUILDING_TYPE` | `BuildingType` |  |
| `CHARACTER` | `Character` |  |
| `CHARACTER_INTERACTION` | `CharacterInteraction` |  |
| `CHARACTER_ROLE` | `CharacterRole` |  |
| `CHARACTER_TRAIT` | `CharacterTrait` |  |
| `CIVIL_WAR` | `CivilWar` |  |
| `COHESION_LEVEL` | `CohesionLevel` |  |
| `COMBAT_SHIP` | `CombatShip` |  |
| `COMBAT_UNIT` | `CombatUnit` |  |
| `COMBAT_UNIT_GROUP` | `CombatUnitGroup` |  |
| `COMBAT_UNIT_TYPE` | `CombatUnitType` |  |
| `COMMANDER_ORDER_TYPE` | `CommanderOrderType` |  |
| `COMMANDER_RANK` | `CommanderRank` |  |
| `COMPANY` | `Company` |  |
| `COMPANY_CHARTER` | `CompanyCharter` |  |
| `COMPANY_CHARTER_TYPE` | `CompanyCharterType` |  |
| `COMPANY_TYPE` | `CompanyType` |  |
| `CONSTRUCTION_QUEUE_ELEMENT` | `ConstructionQueueElement` |  |
| `CONTEXTUAL_DIPLOMATIC_ACTION_TYPE` | `ContextualDiplomaticActionType` |  |
| `CONTEXTUAL_DIPLOMATIC_PACT` | `ContextualDiplomaticPact` |  |
| `COUNTRY` | `Country` |  |
| `COUNTRY_CREATION` | `CountryCreation` |  |
| `COUNTRY_DEFINITION` | `CountryDefinition` |  |
| `COUNTRY_FORMATION` | `CountryFormation` |  |
| `COUNTRY_THIRD_PARTY` | `Country` |  |
| `CULTURAL_COMMUNITY` | `CulturalCommunity` |  |
| `CULTURE` | `Culture` |  |
| `DATE` | `Date` | Jomini Date |
| `DATE_MAX` | `Date` | Jomini Date - Max |
| `DATE_MIN` | `Date` | Jomini Date - Min |
| `DECISION_TYPE` | `Decision` |  |
| `DECREE` | `Decree` |  |
| `DECREE_TYPE` | `DecreeType` |  |
| `DIPLOMATIC_ACTION` | `DiplomaticAction` |  |
| `DIPLOMATIC_ACTION_TYPE` | `DiplomaticActionType` |  |
| `DIPLOMATIC_CATALYST` | `DiplomaticCatalyst` |  |
| `DIPLOMATIC_CATALYST_CATEGORY` | `DiplomaticCatalystCategory` |  |
| `DIPLOMATIC_CATALYST_TYPE` | `DiplomaticCatalystType` |  |
| `DIPLOMATIC_DEMAND` | `DiplomaticDemand` |  |
| `DIPLOMATIC_PACT` | `DiplomaticPact` |  |
| `DIPLOMATIC_PLAY` | `DiplomaticPlay` |  |
| `DIPLOMATIC_PLAY_TYPE` | `DiplomaticPlayType` |  |
| `DIPLOMATIC_RELATIONS` | `DiplomaticRelations` |  |
| `DISCRIMINATION_TRAIT` | `DiscriminationTrait` |  |
| `DISCRIMINATION_TRAIT_GROUP` | `DiscriminationTraitGroup` |  |
| `DLC_METADATA` | `Dlc` |  |
| `ELECTION` | `Election` |  |
| `EMPLOYEE_TRANSFER` | `EmployeeTransfer` |  |
| `EmptyScope` | `TopScope` |  |
| `ENEMY_COUNTRY` | `Country` |  |
| `ERA` | `Era` |  |
| `EVENT` | `Event` |  |
| `FIRST_COUNTRY` | `Country` |  |
| `FIRSTMARKET` | `Market` |  |
| `FRONT` | `Front` |  |
| `GAME_CONCEPT_TYPE` | `GameConceptType` |  |
| `GAME_RULE` | `GameRule` |  |
| `GAME_RULE_SETTING` | `GameRuleSetting` |  |
| `GC` | `GameConceptType` |  |
| `GEOGRAPHIC_REGION` | `GeographicRegion` |  |
| `GetAcceptanceStatus` | `AcceptanceStatus` |  |
| `GetAIStrategy` | `AIStrategy` |  |
| `GetAmendmentType` | `AmendmentType` |  |
| `GetArticleType` | `ArticleType` |  |
| `GetBattleCondition` | `BattleCondition` |  |
| `GetBuildingGroup` | `BuildingGroup` |  |
| `GetBuildingType` | `BuildingType` |  |
| `GetCharacterRole` | `CharacterRole` |  |
| `GetCharacterTrait` | `CharacterTrait` |  |
| `GetCohesionLevel` | `CohesionLevel` |  |
| `GetCombatUnitGroup` | `CombatUnitGroup` |  |
| `GetCombatUnitType` | `CombatUnitType` |  |
| `GetCommanderOrderType` | `CommanderOrderType` |  |
| `GetCompanyCharterType` | `CompanyCharterType` |  |
| `GetConstructionSectorType` | `BuildingType` |  |
| `GetContainer` | `ScriptContainer` |  |
| `GetCountryDiplomaticAction` | `DiplomaticAction` |  |
| `GetCulture` | `Culture` |  |
| `GetCurrentGameDate` | `Date` |  |
| `GetDecreeType` | `DecreeType` |  |
| `GetDiplomaticActionType` | `DiplomaticActionType` |  |
| `GetDiplomaticPlayType` | `DiplomaticPlayType` |  |
| `GetExilePool` | `ExilePool` |  |
| `GetGameEndDate` | `Date` |  |
| `GetGameRules` | `JominiGameRules` |  |
| `GetGameStartDate` | `Date` |  |
| `GetGeographicRegion` | `GeographicRegion` |  |
| `GetGlobalVariable` | `Scope` |  |
| `GetGoods` | `Goods` |  |
| `GetHarvestConditionType` | `HarvestConditionType` |  |
| `GetIdeology` | `Ideology` |  |
| `GetInstitutionType` | `InstitutionType` |  |
| `GetInterestGroupVariant` | `InterestGroup` |  |
| `GetInterestTierType` | `InterestTierType` |  |
| `GetJournalEntryGroup` | `JournalEntryGroup` |  |
| `GetLabel` | `Label` |  |
| `GetLawGroup` | `LawGroup` |  |
| `GetLawType` | `LawType` |  |
| `GetLegitimacyLevel` | `LegitimacyLevel` |  |
| `GetLensToolbar` | `LensToolbar` |  |
| `GetLibertyDesireLevel` | `LibertyDesireLevel` |  |
| `GetLoadingScreenManager` | `LoadingScreenManager` |  |
| `GetMapMode` | `MapMode` |  |
| `GetMapPerspectiveCountry` | `Country` |  |
| `GetMetaPlayer` | `Player` |  |
| `GetMobilizationOption` | `MobilizationOption` |  |
| `GetMobilizationOptionGroup` | `MobilizationOptionGroup` |  |
| `GetNavalBattleCondition` | `NavalBattleCondition` |  |
| `GetNavalMissionType` | `NavalMissionType` |  |
| `GetPlayer` | `Country` |  |
| `GetPlayerJournalEntry` | `JournalEntry` |  |
| `GetPopNeed` | `PopNeed` |  |
| `GetPopType` | `PopType` |  |
| `GetPowerBlocIdentity` | `PowerBlocIdentity` |  |
| `GetPowerBlocPrincipleGroup` | `PowerBlocPrincipleGroup` |  |
| `GetRankModifier` | `Modifier` |  |
| `GetReligion` | `Religion` |  |
| `GetScriptedGui` | `ScriptedGui` | Jomini Scripted GUI - Get scripted GUI by name |
| `GetSelectedFleetsNavalMissionType` | `NavalMissionType` |  |
| `GetSelectedFormation` | `MilitaryFormation` |  |
| `GetServerInfo` | `ServerInformation` | Multiplayer - Server Info of current session |
| `GetShipGroup` | `ShipGroup` |  |
| `GetShipModificationSlotType` | `ShipModificationSlotType` |  |
| `GetShipModificationType` | `ShipModificationType` |  |
| `GetShipPanel` | `ShipPanel` |  |
| `GetShipType` | `ShipType` |  |
| `GetShipVeterancyLevel` | `ShipVeterancyLevel` |  |
| `GetStateRegion` | `StateRegion` |  |
| `GetStaticModifier` | `Modifier` |  |
| `GetStrategicObjectiveFormationInState` | `MilitaryFormation` |  |
| `GetStrategicRegion` | `StrategicRegion` |  |
| `GetSubjectType` | `SubjectType` |  |
| `GetTechnology` | `Technology` |  |
| `GetTutorialJournalEntry` | `JournalEntry` |  |
| `GetVariableFromGlobalVariableMap` | `Scope` |  |
| `GetVariableSystem` | `VariableSystem` | Access the global variable system |
| `GetWarGoalType` | `WarGoalType` |  |
| `GOODS` | `Goods` |  |
| `GOODSPRODUCTIONINFO` | `GoodsProductionInfo` |  |
| `GOVERNMENT_TYPE` | `GovernmentType` |  |
| `GuiScope` | `TopScope` | Jomini Scripted GUI - Get GUI top jomini scope |
| `HARVEST_CONDITION` | `HarvestCondition` |  |
| `HARVEST_CONDITION_AREA` | `HarvestConditionArea` |  |
| `HARVEST_CONDITION_TYPE` | `HarvestConditionType` |  |
| `HQ` | `Hq` |  |
| `IDEOLOGY` | `Ideology` |  |
| `InformationPanelBar` | `InformationPanelBar` |  |
| `INITIATOR_COUNTRY` | `Country` |  |
| `INITIATOR_STATE` | `State` |  |
| `INSTITUTION` | `Institution` |  |
| `INSTITUTION_TYPE` | `InstitutionType` |  |
| `INTEREST` | `Interest` |  |
| `INTEREST_GROUP` | `InterestGroup` |  |
| `INTEREST_GROUP_TRAIT` | `InterestGroupTrait` |  |
| `INTEREST_TIER_TYPE` | `InterestTierType` |  |
| `INVASION` | `Invasion` |  |
| `JominiPlayer` | `Playable` | Jomini Script Systen - Get generic current playable object |
| `JOURNAL_ENTRY` | `JournalEntry` |  |
| `JOURNAL_ENTRY_GROUP` | `JournalEntryGroup` |  |
| `JOURNAL_ENTRY_TYPE` | `JournalEntryType` |  |
| `LabelingHelper` | `LabelingHelper` |  |
| `LAW` | `Law` |  |
| `LAW_GROUP` | `LawGroup` |  |
| `LAW_OTHER` | `Law` |  |
| `LAW_TYPE` | `LawType` |  |
| `LEGITIMACY_LEVEL` | `LegitimacyLevel` |  |
| `LIBERTY_DESIRE_LEVEL` | `LibertyDesireLevel` |  |
| `MAP_MODE` | `MapMode` |  |
| `MapInteractions` | `MapInteractionManager` |  |
| `MapListPanelManager` | `MapListPanelManager` |  |
| `MARKET` | `Market` |  |
| `MARKET_GOODS` | `MarketGoods` |  |
| `MILITARY_FORMATION` | `MilitaryFormation` |  |
| `MILITARY_FORMATION_FLAG` | `MilitaryFormationFlag` |  |
| `MOBILIZATION_OPTION` | `MobilizationOption` |  |
| `MOBILIZATION_OPTION_GROUP` | `MobilizationOptionGroup` |  |
| `MODIFIER` | `Modifier` |  |
| `MODIFIER_BREAKDOWN` | `ModifierBreakdown` |  |
| `MultiplayerSynchronizationInfo` | `MultiplayerSynchronizationInfo` |  |
| `NAVAL_BATTLE` | `NavalBattle` |  |
| `NAVAL_BATTLE_CONDITION` | `NavalBattleCondition` |  |
| `NAVAL_BATTLE_LOG_ENTRY` | `BattleLogEntry` |  |
| `NAVAL_MISSION` | `NavalMission` |  |
| `NAVAL_MISSION_TYPE` | `NavalMissionType` |  |
| `OBJECT_SCOPE` | `Scope` |  |
| `OBJECTIVE` | `Objective` |  |
| `OBJECTIVE_TYPE` | `ObjectiveType` |  |
| `OTHER_COUNTRY` | `Country` |  |
| `Outliner` | `Outliner` |  |
| `PARTY` | `Party` |  |
| `PdxAccount` | `PdxAccount` |  |
| `PLAYER` | `Player` |  |
| `POLITICAL_LOBBY` | `PoliticalLobby` |  |
| `POLITICAL_LOBBY_APPEASEMENT_FACTOR` | `PoliticalLobbyAppeasementFactor` |  |
| `POLITICAL_LOBBY_TYPE` | `PoliticalLobbyType` |  |
| `POLITICAL_MOVEMENT` | `PoliticalMovement` |  |
| `POLITICAL_MOVEMENT_CATEGORY` | `PoliticalMovementCategory` |  |
| `POLITICAL_MOVEMENT_POP_SUPPORT_FACTOR` | `PoliticalMovementPopSupportFactor` |  |
| `POLITICAL_MOVEMENT_TYPE` | `PoliticalMovementType` |  |
| `POP` | `Pop` |  |
| `POP_GOODS_CONSUMPTION` | `PopConsumptionGoods` |  |
| `POP_NEED` | `PopNeed` |  |
| `POP_TYPE` | `PopType` |  |
| `POP_WITH_IG` | `PopWithIG` |  |
| `PopupManager` | `PopupManager` |  |
| `POWER_BLOC` | `PowerBloc` |  |
| `POWER_BLOC_IDENTITY` | `PowerBlocIdentity` |  |
| `POWER_BLOC_MAP_TEXTURE` | `PowerBlocMapTexture` |  |
| `POWER_BLOC_OTHER` | `PowerBloc` |  |
| `POWER_BLOC_PRINCIPLE` | `PowerBlocPrinciple` |  |
| `POWER_BLOC_PRINCIPLE_DATA` | `PowerBlocPrincipleData` |  |
| `POWER_BLOC_PRINCIPLE_GROUP` | `PowerBlocPrincipleGroup` |  |
| `POWER_BLOC_PRINCIPLE_OTHER` | `PowerBlocPrinciple` |  |
| `POWER_BLOC_STATUE` | `PowerBlocStatue` |  |
| `POWER_BLOC_STATUE_ACCESSORY_TYPE` | `PowerBlocStatueAccessoryType` |  |
| `POWER_BLOC_STATUE_HERO_TYPE` | `PowerBlocStatueHeroType` |  |
| `POWER_BLOC_STATUE_PEDESTAL_TYPE` | `PowerBlocStatuePedestalType` |  |
| `PowerBlocPanel` | `PowerBlocPanel` |  |
| `PREV` | `Scope` | Script Scope |
| `PRODUCTION_METHOD` | `ProductionMethod` |  |
| `PRODUCTION_METHOD_GROUP` | `ProductionMethodGroup` |  |
| `PROPOSAL` | `Proposal` |  |
| `PROVINCE` | `Province` |  |
| `PROVINCE_OTHER` | `Province` |  |
| `RELIGION` | `Religion` |  |
| `RightClickMenuManager` | `RightClickMenuManager` |  |
| `ROOT` | `Scope` | Script Scope |
| `SCOPE` | `TopScope` | Script Scope |
| `SCRIPT_CONTAINER` | `ScriptContainer` |  |
| `SCRIPTED_BUTTON` | `ScriptedButton` |  |
| `SCRIPTED_PROGRESS_BAR` | `ScriptedProgressBar` |  |
| `SECOND_COUNTRY` | `Country` |  |
| `SECONDMARKET` | `Market` |  |
| `SHIP` | `Ship` |  |
| `SHIP_CONSTRUCTION` | `ShipConstruction` |  |
| `SHIP_CONSTRUCTION_QUEUE` | `ShipConstructionQueue` |  |
| `SHIP_GROUP` | `ShipGroup` |  |
| `SHIP_LIST` | `ShipList` |  |
| `SHIP_MODIFICATION_SLOT_TYPE` | `ShipModificationSlotType` |  |
| `SHIP_MODIFICATION_TYPE` | `ShipModificationType` |  |
| `SHIP_TEMPLATE` | `ShipTemplate` |  |
| `SHIP_TEMPLATE_VERSION` | `ShipTemplateVersion` |  |
| `SHIP_TYPE` | `ShipType` |  |
| `SHIP_VETERANCY_LEVEL` | `ShipVeterancyLevel` |  |
| `SHIPPING_LANE` | `ShippingLane` |  |
| `ShipTemplateList` | `ShipTemplateList` |  |
| `SOCIAL_CLASS` | `SocialClass` |  |
| `SOCIAL_HIERARCHY` | `SocialHierarchy` |  |
| `SOURCE_COUNTRY` | `Country` |  |
| `STATE` | `State` |  |
| `STATE_GOODS` | `StateGoods` |  |
| `STATE_OTHER` | `State` |  |
| `STATE_REGION` | `StateRegion` |  |
| `STATE_TRAIT` | `StateTrait` |  |
| `STRAIT` | `Strait` |  |
| `STRAIT_DEFINITION` | `StraitDefinition` |  |
| `STRATEGIC_REGION` | `StrategicRegion` |  |
| `SUBJECT_SCOPE` | `Scope` |  |
| `SUBJECT_TYPE` | `SubjectType` |  |
| `SUPPLY_SHIP_CONSTRUCTION` | `SupplyShipConstruction` |  |
| `SWAY` | `Sway` |  |
| `SWAY_OFFER` | `SwayOffer` |  |
| `SWAY_OFFER_TYPE` | `SwayOfferType` |  |
| `SwayCountryPanel` | `SwayCountryPanel` |  |
| `TARGET_ACCEPTANCE_STATUS` | `AcceptanceStatus` |  |
| `TARGET_AIATTITUDE` | `AIAttitude` |  |
| `TARGET_AISTRATEGIC_REGION_STANCE_TYPE` | `AIStrategicRegionStanceType` |  |
| `TARGET_AISTRATEGY` | `AIStrategy` |  |
| `TARGET_ALERT` | `Alert` |  |
| `TARGET_ALERT_GROUP` | `AlertGroup` |  |
| `TARGET_AMENDMENT` | `Amendment` |  |
| `TARGET_AMENDMENT_TYPE` | `AmendmentType` |  |
| `TARGET_BATTLE` | `Battle` |  |
| `TARGET_BATTLE_CONDITION` | `BattleCondition` |  |
| `TARGET_BUILDING` | `Building` |  |
| `TARGET_BUILDING_GROUP` | `BuildingGroup` |  |
| `TARGET_BUILDING_OWNERSHIP` | `BuildingOwnership` |  |
| `TARGET_BUILDING_TYPE` | `BuildingType` |  |
| `TARGET_CHARACTER` | `Character` |  |
| `TARGET_CHARACTER_INTERACTION` | `CharacterInteraction` |  |
| `TARGET_CHARACTER_ROLE` | `CharacterRole` |  |
| `TARGET_CHARACTER_TRAIT` | `CharacterTrait` |  |
| `TARGET_CIVIL_WAR` | `CivilWar` |  |
| `TARGET_COHESION_LEVEL` | `CohesionLevel` |  |
| `TARGET_COMBAT_SHIP` | `CombatShip` |  |
| `TARGET_COMBAT_UNIT` | `CombatUnit` |  |
| `TARGET_COMBAT_UNIT_GROUP` | `CombatUnitGroup` |  |
| `TARGET_COMBAT_UNIT_TYPE` | `CombatUnitType` |  |
| `TARGET_COMMANDER_ORDER_TYPE` | `CommanderOrderType` |  |
| `TARGET_COMMANDER_RANK` | `CommanderRank` |  |
| `TARGET_COMPANY` | `Company` |  |
| `TARGET_COMPANY_CHARTER` | `CompanyCharter` |  |
| `TARGET_COMPANY_CHARTER_TYPE` | `CompanyCharterType` |  |
| `TARGET_COMPANY_TYPE` | `CompanyType` |  |
| `TARGET_CONSTRUCTION_QUEUE_ELEMENT` | `ConstructionQueueElement` |  |
| `TARGET_CONTEXTUAL_DIPLOMATIC_ACTION_TYPE` | `ContextualDiplomaticActionType` |  |
| `TARGET_CONTEXTUAL_DIPLOMATIC_PACT` | `ContextualDiplomaticPact` |  |
| `TARGET_COUNTRY` | `Country` |  |
| `TARGET_COUNTRY_CREATION` | `CountryCreation` |  |
| `TARGET_COUNTRY_DEFINITION` | `CountryDefinition` |  |
| `TARGET_COUNTRY_FORMATION` | `CountryFormation` |  |
| `TARGET_CULTURAL_COMMUNITY` | `CulturalCommunity` |  |
| `TARGET_CULTURE` | `Culture` |  |
| `TARGET_DECISION_TYPE` | `Decision` |  |
| `TARGET_DECREE` | `Decree` |  |
| `TARGET_DECREE_TYPE` | `DecreeType` |  |
| `TARGET_DIPLOMATIC_ACTION` | `DiplomaticAction` |  |
| `TARGET_DIPLOMATIC_ACTION_TYPE` | `DiplomaticActionType` |  |
| `TARGET_DIPLOMATIC_CATALYST` | `DiplomaticCatalyst` |  |
| `TARGET_DIPLOMATIC_CATALYST_CATEGORY` | `DiplomaticCatalystCategory` |  |
| `TARGET_DIPLOMATIC_CATALYST_TYPE` | `DiplomaticCatalystType` |  |
| `TARGET_DIPLOMATIC_DEMAND` | `DiplomaticDemand` |  |
| `TARGET_DIPLOMATIC_PACT` | `DiplomaticPact` |  |
| `TARGET_DIPLOMATIC_PLAY` | `DiplomaticPlay` |  |
| `TARGET_DIPLOMATIC_PLAY_TYPE` | `DiplomaticPlayType` |  |
| `TARGET_DIPLOMATIC_RELATIONS` | `DiplomaticRelations` |  |
| `TARGET_DISCRIMINATION_TRAIT` | `DiscriminationTrait` |  |
| `TARGET_DISCRIMINATION_TRAIT_GROUP` | `DiscriminationTraitGroup` |  |
| `TARGET_DLC_METADATA` | `Dlc` |  |
| `TARGET_ELECTION` | `Election` |  |
| `TARGET_EMPLOYEE_TRANSFER` | `EmployeeTransfer` |  |
| `TARGET_ERA` | `Era` |  |
| `TARGET_EVENT` | `Event` |  |
| `TARGET_FRONT` | `Front` |  |
| `TARGET_GAME_CONCEPT_TYPE` | `GameConceptType` |  |
| `TARGET_GEOGRAPHIC_REGION` | `GeographicRegion` |  |
| `TARGET_GOODS` | `Goods` |  |
| `TARGET_GOVERNMENT_TYPE` | `GovernmentType` |  |
| `TARGET_HARVEST_CONDITION` | `HarvestCondition` |  |
| `TARGET_HARVEST_CONDITION_AREA` | `HarvestConditionArea` |  |
| `TARGET_HARVEST_CONDITION_TYPE` | `HarvestConditionType` |  |
| `TARGET_HQ` | `Hq` |  |
| `TARGET_IDEOLOGY` | `Ideology` |  |
| `TARGET_INSTITUTION` | `Institution` |  |
| `TARGET_INSTITUTION_TYPE` | `InstitutionType` |  |
| `TARGET_INTEREST` | `Interest` |  |
| `TARGET_INTEREST_GROUP` | `InterestGroup` |  |
| `TARGET_INTEREST_GROUP_TRAIT` | `InterestGroupTrait` |  |
| `TARGET_INTEREST_TIER_TYPE` | `InterestTierType` |  |
| `TARGET_INVASION` | `Invasion` |  |
| `TARGET_JOURNAL_ENTRY` | `JournalEntry` |  |
| `TARGET_JOURNAL_ENTRY_GROUP` | `JournalEntryGroup` |  |
| `TARGET_JOURNAL_ENTRY_TYPE` | `JournalEntryType` |  |
| `TARGET_LAW` | `Law` |  |
| `TARGET_LAW_GROUP` | `LawGroup` |  |
| `TARGET_LAW_TYPE` | `LawType` |  |
| `TARGET_LEGITIMACY_LEVEL` | `LegitimacyLevel` |  |
| `TARGET_LIBERTY_DESIRE_LEVEL` | `LibertyDesireLevel` |  |
| `TARGET_MAP_MODE` | `MapMode` |  |
| `TARGET_MARKET` | `Market` |  |
| `TARGET_MARKET_GOODS` | `MarketGoods` |  |
| `TARGET_MILITARY_FORMATION` | `MilitaryFormation` |  |
| `TARGET_MILITARY_FORMATION_FLAG` | `MilitaryFormationFlag` |  |
| `TARGET_MOBILIZATION_OPTION` | `MobilizationOption` |  |
| `TARGET_MOBILIZATION_OPTION_GROUP` | `MobilizationOptionGroup` |  |
| `TARGET_MODIFIER` | `Modifier` |  |
| `TARGET_MODIFIER_BREAKDOWN` | `ModifierBreakdown` |  |
| `TARGET_NAVAL_BATTLE` | `NavalBattle` |  |
| `TARGET_NAVAL_BATTLE_CONDITION` | `NavalBattleCondition` |  |
| `TARGET_NAVAL_BATTLE_LOG_ENTRY` | `BattleLogEntry` |  |
| `TARGET_NAVAL_MISSION` | `NavalMission` |  |
| `TARGET_NAVAL_MISSION_TYPE` | `NavalMissionType` |  |
| `TARGET_OBJECTIVE` | `Objective` |  |
| `TARGET_OBJECTIVE_TYPE` | `ObjectiveType` |  |
| `TARGET_PARTY` | `Party` |  |
| `TARGET_PLAYER` | `Player` |  |
| `TARGET_POLITICAL_LOBBY` | `PoliticalLobby` |  |
| `TARGET_POLITICAL_LOBBY_APPEASEMENT_FACTOR` | `PoliticalLobbyAppeasementFactor` |  |
| `TARGET_POLITICAL_LOBBY_TYPE` | `PoliticalLobbyType` |  |
| `TARGET_POLITICAL_MOVEMENT` | `PoliticalMovement` |  |
| `TARGET_POLITICAL_MOVEMENT_CATEGORY` | `PoliticalMovementCategory` |  |
| `TARGET_POLITICAL_MOVEMENT_POP_SUPPORT_FACTOR` | `PoliticalMovementPopSupportFactor` |  |
| `TARGET_POLITICAL_MOVEMENT_TYPE` | `PoliticalMovementType` |  |
| `TARGET_POP` | `Pop` |  |
| `TARGET_POP_GOODS_CONSUMPTION` | `PopConsumptionGoods` |  |
| `TARGET_POP_NEED` | `PopNeed` |  |
| `TARGET_POP_TYPE` | `PopType` |  |
| `TARGET_POP_WITH_IG` | `PopWithIG` |  |
| `TARGET_POWER_BLOC` | `PowerBloc` |  |
| `TARGET_POWER_BLOC_IDENTITY` | `PowerBlocIdentity` |  |
| `TARGET_POWER_BLOC_MAP_TEXTURE` | `PowerBlocMapTexture` |  |
| `TARGET_POWER_BLOC_PRINCIPLE` | `PowerBlocPrinciple` |  |
| `TARGET_POWER_BLOC_PRINCIPLE_DATA` | `PowerBlocPrincipleData` |  |
| `TARGET_POWER_BLOC_PRINCIPLE_GROUP` | `PowerBlocPrincipleGroup` |  |
| `TARGET_POWER_BLOC_STATUE` | `PowerBlocStatue` |  |
| `TARGET_POWER_BLOC_STATUE_ACCESSORY_TYPE` | `PowerBlocStatueAccessoryType` |  |
| `TARGET_POWER_BLOC_STATUE_HERO_TYPE` | `PowerBlocStatueHeroType` |  |
| `TARGET_POWER_BLOC_STATUE_PEDESTAL_TYPE` | `PowerBlocStatuePedestalType` |  |
| `TARGET_PRODUCTION_METHOD` | `ProductionMethod` |  |
| `TARGET_PRODUCTION_METHOD_GROUP` | `ProductionMethodGroup` |  |
| `TARGET_PROPOSAL` | `Proposal` |  |
| `TARGET_PROVINCE` | `Province` |  |
| `TARGET_RELIGION` | `Religion` |  |
| `TARGET_SCRIPT_CONTAINER` | `ScriptContainer` |  |
| `TARGET_SCRIPTED_BUTTON` | `ScriptedButton` |  |
| `TARGET_SCRIPTED_PROGRESS_BAR` | `ScriptedProgressBar` |  |
| `TARGET_SHIP` | `Ship` |  |
| `TARGET_SHIP_CONSTRUCTION` | `ShipConstruction` |  |
| `TARGET_SHIP_CONSTRUCTION_QUEUE` | `ShipConstructionQueue` |  |
| `TARGET_SHIP_GROUP` | `ShipGroup` |  |
| `TARGET_SHIP_LIST` | `ShipList` |  |
| `TARGET_SHIP_MODIFICATION_SLOT_TYPE` | `ShipModificationSlotType` |  |
| `TARGET_SHIP_MODIFICATION_TYPE` | `ShipModificationType` |  |
| `TARGET_SHIP_TEMPLATE` | `ShipTemplate` |  |
| `TARGET_SHIP_TEMPLATE_VERSION` | `ShipTemplateVersion` |  |
| `TARGET_SHIP_TYPE` | `ShipType` |  |
| `TARGET_SHIP_VETERANCY_LEVEL` | `ShipVeterancyLevel` |  |
| `TARGET_SHIPPING_LANE` | `ShippingLane` |  |
| `TARGET_SOCIAL_CLASS` | `SocialClass` |  |
| `TARGET_SOCIAL_HIERARCHY` | `SocialHierarchy` |  |
| `TARGET_STATE` | `State` |  |
| `TARGET_STATE_GOODS` | `StateGoods` |  |
| `TARGET_STATE_REGION` | `StateRegion` |  |
| `TARGET_STATE_TRAIT` | `StateTrait` |  |
| `TARGET_STRAIT` | `Strait` |  |
| `TARGET_STRAIT_DEFINITION` | `StraitDefinition` |  |
| `TARGET_STRATEGIC_REGION` | `StrategicRegion` |  |
| `TARGET_SUBJECT_TYPE` | `SubjectType` |  |
| `TARGET_SUPPLY_SHIP_CONSTRUCTION` | `SupplyShipConstruction` |  |
| `TARGET_SWAY` | `Sway` |  |
| `TARGET_SWAY_OFFER` | `SwayOffer` |  |
| `TARGET_SWAY_OFFER_TYPE` | `SwayOfferType` |  |
| `TARGET_TECHNOLOGY` | `Technology` |  |
| `TARGET_THEATER` | `Theater` |  |
| `TARGET_THEME` | `Theme` |  |
| `TARGET_TIMED_MODIFIER` | `TimedModifier` |  |
| `TARGET_TREATY` | `Treaty` |  |
| `TARGET_TREATY_ARTICLE` | `Article` |  |
| `TARGET_TREATY_ARTICLE_TYPE` | `ArticleType` |  |
| `TARGET_TYPE_LABEL` | `Label` |  |
| `TARGET_WAR` | `War` |  |
| `TARGET_WAR_GOAL` | `WarGoal` |  |
| `TARGET_WAR_GOAL_DRAFT` | `WarGoalDraft` |  |
| `TARGET_WAR_GOAL_TYPE` | `WarGoalType` |  |
| `TECHNOLOGY` | `Technology` |  |
| `THEATER` | `Theater` |  |
| `THEME` | `Theme` |  |
| `THIS` | `Scope` | Script Scope |
| `TIMED_MODIFIER` | `TimedModifier` |  |
| `TimeKeeper` | `TimeKeeper` |  |
| `TREATY` | `Treaty` |  |
| `TREATY_ARTICLE` | `Article` |  |
| `TREATY_ARTICLE_TYPE` | `ArticleType` |  |
| `TYPE_LABEL` | `Label` |  |
| `WAR` | `War` |  |
| `WAR_GOAL` | `WarGoal` |  |
| `WAR_GOAL_DRAFT` | `WarGoalDraft` |  |
| `WAR_GOAL_TYPE` | `WarGoalType` |  |
| `WarManager` | `WarManager` |  |
