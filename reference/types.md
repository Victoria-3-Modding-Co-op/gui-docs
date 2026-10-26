# Game-defined widget types

The shipped interface declares **1,786 types** with `type NAME = BASE { ... }`. Each one inherits every property of its base and may add or replace entries. This page lists them all, grouped by the file that declares them.

`BASE` is either an engine kind (see [widgets](widgets.md)) or another game type. Following the chain up always ends at an engine kind.

## Index

- [gui/achievements/jomini_achievements_types.gui](#guiachievementsjomini_achievements_typesgui) — 2 types
- [gui/achievements/popup.gui](#guiachievementspopupgui) — 2 types
- [gui/add_wargoal_panel.gui](#guiadd_wargoal_panelgui) — 9 types
- [gui/battle.gui](#guibattlegui) — 7 types
- [gui/block_windows.gui](#guiblock_windowsgui) — 10 types
- [gui/budget_panel.gui](#guibudget_panelgui) — 7 types
- [gui/building_browser_panel.gui](#guibuilding_browser_panelgui) — 10 types
- [gui/building_details_panel.gui](#guibuilding_details_panelgui) — 50 types
- [gui/building_workforce_panel.gui](#guibuilding_workforce_panelgui) — 1 types
- [gui/character_panel.gui](#guicharacter_panelgui) — 12 types
- [gui/color_picker.gui](#guicolor_pickergui) — 2 types
- [gui/combat_unit_types.gui](#guicombat_unit_typesgui) — 18 types
- [gui/companies_panel.gui](#guicompanies_panelgui) — 9 types
- [gui/company_panel.gui](#guicompany_panelgui) — 11 types
- [gui/console.gui](#guiconsolegui) — 1 types
- [gui/construction_panel.gui](#guiconstruction_panelgui) — 8 types
- [gui/construction_queue.gui](#guiconstruction_queuegui) — 4 types
- [gui/countries_panel.gui](#guicountries_panelgui) — 1 types
- [gui/country_diplomacy_panel.gui](#guicountry_diplomacy_panelgui) — 1 types
- [gui/country_formation_panel.gui](#guicountry_formation_panelgui) — 1 types
- [gui/country_interactions_panel.gui](#guicountry_interactions_panelgui) — 1 types
- [gui/country_panel.gui](#guicountry_panelgui) — 42 types
- [gui/country_politics_panel.gui](#guicountry_politics_panelgui) — 4 types
- [gui/credits_window.gui](#guicredits_windowgui) — 1 types
- [gui/culture_info_panel.gui](#guiculture_info_panelgui) — 7 types
- [gui/culture_panel.gui](#guiculture_panelgui) — 17 types
- [gui/custom_tooltip.gui](#guicustom_tooltipgui) — 170 types
- [gui/debug_menues.gui](#guidebug_menuesgui) — 4 types
- [gui/decisions_panel.gui](#guidecisions_panelgui) — 1 types
- [gui/diplomatic_overview.gui](#guidiplomatic_overviewgui) — 11 types
- [gui/diplomatic_play_panel.gui](#guidiplomatic_play_panelgui) — 13 types
- [gui/election_panel.gui](#guielection_panelgui) — 2 types
- [gui/empty_state.gui](#guiempty_stategui) — 2 types
- [gui/eventwindow.gui](#guieventwindowgui) — 2 types
- [gui/front_panel.gui](#guifront_panelgui) — 12 types
- [gui/frontend/frontend_dlc.gui](#guifrontendfrontend_dlcgui) — 2 types
- [gui/frontend/frontend_ingame_menu.gui](#guifrontendfrontend_ingame_menugui) — 1 types
- [gui/frontend/frontend_load.gui](#guifrontendfrontend_loadgui) — 3 types
- [gui/frontend/frontend_loadingscreen.gui](#guifrontendfrontend_loadingscreengui) — 3 types
- [gui/frontend/shared/buttons.gui](#guifrontendsharedbuttonsgui) — 22 types
- [gui/frontend/shared/buttons_icons.gui](#guifrontendsharedbuttons_iconsgui) — 18 types
- [gui/frontend/shared/defaults.gui](#guifrontendshareddefaultsgui) — 16 types
- [gui/frontend/shared/edit_boxes.gui](#guifrontendsharededit_boxesgui) — 3 types
- [gui/frontend/shared/hud.gui](#guifrontendsharedhudgui) — 1 types
- [gui/frontend/shared/icons.gui](#guifrontendsharediconsgui) — 15 types
- [gui/frontend/shared/labels.gui](#guifrontendsharedlabelsgui) — 4 types
- [gui/frontend/shared/lists.gui](#guifrontendsharedlistsgui) — 3 types
- [gui/frontend/shared/sounds.gui](#guifrontendsharedsoundsgui) — 7 types
- [gui/frontend/shared/windows.gui](#guifrontendsharedwindowsgui) — 5 types
- [gui/frontend_ingame_loadingscreen.gui](#guifrontend_ingame_loadingscreengui) — 1 types
- [gui/game_rules.gui](#guigame_rulesgui) — 5 types
- [gui/generate_character.gui](#guigenerate_charactergui) — 1 types
- [gui/goods_local_prices_panel.gui](#guigoods_local_prices_panelgui) — 1 types
- [gui/goods_panel.gui](#guigoods_panelgui) — 17 types
- [gui/goods_state_panel.gui](#guigoods_state_panelgui) — 2 types
- [gui/goods_usage_panel.gui](#guigoods_usage_panelgui) — 1 types
- [gui/goods_world_market_panel.gui](#guigoods_world_market_panelgui) — 1 types
- [gui/graph_tooltips.gui](#guigraph_tooltipsgui) — 48 types
- [gui/important_actions_list.gui](#guiimportant_actions_listgui) — 2 types
- [gui/in_game_menu_logo.gui](#guiin_game_menu_logogui) — 2 types
- [gui/information_panel_bar.gui](#guiinformation_panel_bargui) — 2 types
- [gui/information_panels_types.gui](#guiinformation_panels_typesgui) — 10 types
- [gui/interest_group_panel.gui](#guiinterest_group_panelgui) — 12 types
- [gui/invasion_panel.gui](#guiinvasion_panelgui) — 8 types
- [gui/jomini/music_player/music_player_view.gui](#guijominimusic_playermusic_player_viewgui) — 4 types
- [gui/journal.gui](#guijournalgui) — 14 types
- [gui/journal_entry.gui](#guijournal_entrygui) — 4 types
- [gui/journal_entry_widgets/custom_widgets.gui](#guijournal_entry_widgetscustom_widgetsgui) — 1 types
- [gui/journal_entry_widgets/ep2_japan_widgets.gui](#guijournal_entry_widgetsep2_japan_widgetsgui) — 4 types
- [gui/journal_entry_widgets/rlit_widgets.gui](#guijournal_entry_widgetsrlit_widgetsgui) — 2 types
- [gui/journal_entry_widgets/tsarpoints_widgets.gui](#guijournal_entry_widgetstsarpoints_widgetsgui) — 1 types
- [gui/lens_toolbar.gui](#guilens_toolbargui) — 5 types
- [gui/map_interaction.gui](#guimap_interactiongui) — 1 types
- [gui/map_list_panel.gui](#guimap_list_panelgui) — 59 types
- [gui/map_markers.gui](#guimap_markersgui) — 6 types
- [gui/mapeditor_customizations.gui](#guimapeditor_customizationsgui) — 2 types
- [gui/market_food_security_panel.gui](#guimarket_food_security_panelgui) — 2 types
- [gui/market_panel.gui](#guimarket_panelgui) — 14 types
- [gui/market_states_panel.gui](#guimarket_states_panelgui) — 2 types
- [gui/message_settings.gui](#guimessage_settingsgui) — 4 types
- [gui/military_formation_panel.gui](#guimilitary_formation_panelgui) — 50 types
- [gui/military_panel_formations.gui](#guimilitary_panel_formationsgui) — 8 types
- [gui/modifier_debugger.gui](#guimodifier_debuggergui) — 7 types
- [gui/modifiers_panel.gui](#guimodifiers_panelgui) — 2 types
- [gui/multiplayer_types.gui](#guimultiplayer_typesgui) — 32 types
- [gui/naval_battle.gui](#guinaval_battlegui) — 24 types
- [gui/notifications.gui](#guinotificationsgui) — 7 types
- [gui/objective_types.gui](#guiobjective_typesgui) — 4 types
- [gui/outliner.gui](#guioutlinergui) — 2 types
- [gui/outliner_framework.gui](#guioutliner_frameworkgui) — 11 types
- [gui/outliner_ongoing_types.gui](#guioutliner_ongoing_typesgui) — 24 types
- [gui/outliner_pinnable_types.gui](#guioutliner_pinnable_typesgui) — 39 types
- [gui/panel_military.gui](#guipanel_militarygui) — 17 types
- [gui/party_panel.gui](#guiparty_panelgui) — 1 types
- [gui/pdx_account/base_types.gui](#guipdx_accountbase_typesgui) — 14 types
- [gui/pdx_account/create_account_window.gui](#guipdx_accountcreate_account_windowgui) — 1 types
- [gui/pdx_account/login_window.gui](#guipdx_accountlogin_windowgui) — 2 types
- [gui/political_lobby_panel.gui](#guipolitical_lobby_panelgui) — 6 types
- [gui/political_movement_panel.gui](#guipolitical_movement_panelgui) — 10 types
- [gui/politics_panel.gui](#guipolitics_panelgui) — 1 types
- [gui/politics_panel_change_law.gui](#guipolitics_panel_change_lawgui) — 3 types
- [gui/politics_panel_constitution.gui](#guipolitics_panel_constitutiongui) — 3 types
- [gui/politics_panel_institutions.gui](#guipolitics_panel_institutionsgui) — 2 types
- [gui/politics_panel_overview.gui](#guipolitics_panel_overviewgui) — 6 types
- [gui/politics_panel_reform_government.gui](#guipolitics_panel_reform_governmentgui) — 6 types
- [gui/politics_panel_types.gui](#guipolitics_panel_typesgui) — 63 types
- [gui/pop_browser_panel.gui](#guipop_browser_panelgui) — 7 types
- [gui/pop_details_panel.gui](#guipop_details_panelgui) — 4 types
- [gui/pops_overview.gui](#guipops_overviewgui) — 22 types
- [gui/popups.gui](#guipopupsgui) — 8 types
- [gui/power_bloc_formation_panel.gui](#guipower_bloc_formation_panelgui) — 11 types
- [gui/power_bloc_panel.gui](#guipower_bloc_panelgui) — 27 types
- [gui/production_methods.gui](#guiproduction_methodsgui) — 6 types
- [gui/religion_info_panel.gui](#guireligion_info_panelgui) — 2 types
- [gui/right_click_menu.gui](#guiright_click_menugui) — 59 types
- [gui/sea_region_panel.gui](#guisea_region_panelgui) — 9 types
- [gui/settings/setting_types.gui](#guisettingssetting_typesgui) — 15 types
- [gui/shared/animations.gui](#guisharedanimationsgui) — 3 types
- [gui/shared/animations_special.gui](#guisharedanimations_specialgui) — 1 types
- [gui/shared/backgrounds.gui](#guisharedbackgroundsgui) — 12 types
- [gui/shared/button_icons.gui](#guisharedbutton_iconsgui) — 39 types
- [gui/shared/buttons.gui](#guisharedbuttonsgui) — 5 types
- [gui/shared/character.gui](#guisharedcharactergui) — 51 types
- [gui/shared/defaults.gui](#guishareddefaultsgui) — 14 types
- [gui/shared/dividers.gui](#guishareddividersgui) — 12 types
- [gui/shared/flags.gui](#guisharedflagsgui) — 23 types
- [gui/shared/layout.gui](#guisharedlayoutgui) — 1 types
- [gui/shared/progressbars.gui](#guisharedprogressbarsgui) — 22 types
- [gui/shared/search_bar.gui](#guisharedsearch_bargui) — 2 types
- [gui/shared/tab_bars.gui](#guisharedtab_barsgui) — 3 types
- [gui/ship_designer_popup.gui](#guiship_designer_popupgui) — 6 types
- [gui/ship_panel.gui](#guiship_panelgui) — 114 types
- [gui/state_population_panel.gui](#guistate_population_panelgui) — 5 types
- [gui/states_panel.gui](#guistates_panelgui) — 20 types
- [gui/states_panel_buildings.gui](#guistates_panel_buildingsgui) — 4 types
- [gui/states_panel_modifiers.gui](#guistates_panel_modifiersgui) — 1 types
- [gui/strait_panel.gui](#guistrait_panelgui) — 10 types
- [gui/strategic_region_panel.gui](#guistrategic_region_panelgui) — 10 types
- [gui/sway_country_panel.gui](#guisway_country_panelgui) — 5 types
- [gui/switch_production_method_menu.gui](#guiswitch_production_method_menugui) — 1 types
- [gui/table_tooltips.gui](#guitable_tooltipsgui) — 3 types
- [gui/tech_tree.gui](#guitech_treegui) — 5 types
- [gui/theme_selector_window.gui](#guitheme_selector_windowgui) — 8 types
- [gui/ticktask_debugger.gui](#guiticktask_debuggergui) — 6 types
- [gui/timemanip.gui](#guitimemanipgui) — 5 types
- [gui/tooltip.gui](#guitooltipgui) — 8 types
- [gui/topbar.gui](#guitopbargui) — 3 types
- [gui/topfrontend.gui](#guitopfrontendgui) — 3 types
- [gui/transfer_formation.gui](#guitransfer_formationgui) — 9 types
- [gui/treaty_draft_panel.gui](#guitreaty_draft_panelgui) — 19 types
- [gui/treaty_panel.gui](#guitreaty_panelgui) — 16 types
- [gui/tutorial_highlight.gui](#guitutorial_highlightgui) — 2 types
- [gui/tutorial_popup.gui](#guitutorial_popupgui) — 5 types
- [gui/war_panel.gui](#guiwar_panelgui) — 6 types
- [gui/window_component_library.gui](#guiwindow_component_librarygui) — 5 types
- [gui/world_market_panel.gui](#guiworld_market_panelgui) — 8 types

## gui/achievements/jomini_achievements_types.gui

| Type | Base | Group |
|---|---|---|
| `vbox_achievement_group` | `vbox` | `Achievements` |
| `widget_achievement_list_entry` | `widget` | `Achievements` |

## gui/achievements/popup.gui

| Type | Base | Group |
|---|---|---|
| `achievement_spacer_horizontal` | `widget` | `Achievements` |
| `achievement_spacer_vertical` | `widget` | `Achievements` |

## gui/add_wargoal_panel.gui

| Type | Base | Group |
|---|---|---|
| `add_wargoal_item` | `button` | `wargoal_types` |
| `add_wargoal_panel` | `default_block_window` | `wargoal_types` |
| `add_wargoal_type_item` | `button` | `wargoal_types` |
| `small_wargoal_item` | `flowcontainer` | `wargoal_types` |
| `small_wargoal_item_with_checkmark` | `container` | `wargoal_types` |
| `small_wargoal_item_with_executed_checkmark` | `container` | `wargoal_types` |
| `wargoal_checkmark` | `icon` | `wargoal_types` |
| `wargoal_checkmark_always` | `icon` | `wargoal_types` |
| `wargoal_item` | `container` | `wargoal_types` |

## gui/battle.gui

| Type | Base | Group |
|---|---|---|
| `battle_formation_item` | `flowcontainer` | `battle_panel_types` |
| `battle_panel` | `default_block_window_two_lines` | `battle_panel_types` |
| `battle_panel_details_content` | `flowcontainer` | `battle_panel_types` |
| `battle_panel_overview_content` | `container` | `battle_panel_types` |
| `battle_side_content` | `flowcontainer` | `battle_panel_types` |
| `casualty_item` | `flowcontainer` | `battle_panel_types` |
| `combat_unit_type` | `flowcontainer` | `battle_panel_types` |

## gui/block_windows.gui

| Type | Base | Group |
|---|---|---|
| `default_block_window` | `widget` | `windows` |
| `default_block_window_two_lines` | `default_block_window` | `windows` |
| `default_block_window_vbox` | `default_block_window` | `windows` |
| `default_popup` | `window` | `windows` |
| `default_popup_two_lines` | `default_popup` | `windows` |
| `default_popup_vbox` | `default_popup` | `windows` |
| `fixed_bottom_spacer` | `widget` | `windows` |
| `fullscreen_block_window` | `widget` | `windows` |
| `fullscreen_scrollarea` | `scrollarea` | `windows` |
| `vfx` | `widget` | `vfx_types` |

## gui/budget_panel.gui

| Type | Base | Group |
|---|---|---|
| `budget_panel` | `default_block_window` | `budget` |
| `set_level_bar` | `flowcontainer` | `budget` |
| `set_level_bar_export_tariffs` | `flowcontainer` | `budget` |
| `set_level_bar_import_tariffs` | `flowcontainer` | `budget` |
| `set_level_bar_item` | `widget` | `budget` |
| `tax_exp_frame` | `widget` | `budget` |
| `tax_exp_frame_coin` | `container` | `budget` |

## gui/building_browser_panel.gui

| Type | Base | Group |
|---|---|---|
| `building_browser_building_item` | `flowcontainer` | `building_browser_panel_types` |
| `building_browser_building_type_item` | `container` | `building_browser_panel_types` |
| `building_browser_filter_line` | `widget` | `building_browser_panel_types` |
| `building_browser_filter_line_button` | `button` | `building_browser_panel_types` |
| `building_browser_item_ownership_area` | `widget` | `building_browser_panel_types` |
| `building_browser_panel` | `fullscreen_block_window` | `building_browser_panel_types` |
| `building_panel_potential_buildings` | `flowcontainer` | `building_browser_panel_types` |
| `compact_building_browser_panel` | `default_block_window_two_lines` | `building_browser_panel_types` |
| `filtered_country_ownership_chart` | `browser_chart` | `building_browser_panel_types` |
| `filtered_ownership_distribution_chart` | `browser_chart` | `building_browser_panel_types` |

## gui/building_details_panel.gui

| Type | Base | Group |
|---|---|---|
| `building_auto_expand_icon` | `widget` | `building_panels` |
| `building_auto_expand_toggle` | `widget` | `building_panels` |
| `building_average_wage_label` | `textbox` | `building_panels` |
| `building_country_monopoly_icon` | `widget` | `building_panels` |
| `building_details_panel` | `default_block_window_two_lines` | `building_panels` |
| `building_details_panel_overview_content` | `flowcontainer` | `building_panels` |
| `building_employment_bar` | `widget` | `building_panels` |
| `building_imports_exports_item` | `button` | `building_panels` |
| `building_level_controls` | `container` | `building_panels` |
| `building_level_controls_with_military` | `building_level_controls` | `building_panels` |
| `building_nationalize_button` | `building_nationalize_button_base` | `building_panels` |
| `building_nationalize_button_base` | `button_icon_round` | `building_panels` |
| `building_owner_icon` | `widget` | `building_panels` |
| `building_ownership_chart` | `container` | `building_panels` |
| `building_ownership_or_property_portfolio_stacked_barchart` | `container` | `building_panels` |
| `building_ownership_or_property_portfolio_stacked_barchart_short` | `container` | `building_panels` |
| `building_ownership_stacked_barchart` | `building_ownership_stacked_barchart_base` | `building_panels` |
| `building_ownership_stacked_barchart_base` | `v3_stacked_barchart` | `building_panels` |
| `building_ownership_stacked_barchart_short` | `building_ownership_stacked_barchart_base` | `building_panels` |
| `building_privatize_icon` | `widget` | `building_panels` |
| `building_privatize_toggle` | `building_privatize_toggle_base` | `building_panels` |
| `building_privatize_toggle_base` | `widget` | `building_panels` |
| `building_process_breakdown` | `container` | `building_panels` |
| `building_process_entry` | `widget` | `building_panels` |
| `building_process_entry_small` | `widget` | `building_panels` |
| `building_productivity_mini_chart` | `flowcontainer` | `building_panels` |
| `building_progressbars` | `flowcontainer` | `building_panels` |
| `building_rank_label` | `textbox` | `building_panels` |
| `building_size_with_ownership` | `flowcontainer` | `building_panels` |
| `building_subsidize_toggle` | `widget` | `building_panels` |
| `building_subsidized_icon` | `widget` | `building_panels` |
| `building_type_auto_expand_toggle` | `widget` | `building_panels` |
| `building_type_nationalize_button` | `building_nationalize_button_base` | `building_panels` |
| `building_type_privatize_or_monopolize` | `widget` | `building_panels` |
| `building_type_privatize_toggle` | `building_privatize_toggle_base` | `building_panels` |
| `building_type_subsidize_toggle` | `widget` | `building_panels` |
| `button_icon_round_privatize_or_monopolize_button` | `button_icon_round` | `building_panels` |
| `condensed_building_information` | `flowcontainer` | `building_panels` |
| `condensed_building_information_pms` | `container` | `building_panels` |
| `expand_building_button` | `widget` | `building_panels` |
| `expand_building_button_with_military` | `button_icon_plus_action` | `building_panels` |
| `military_building_combat_unit_summary` | `flowcontainer` | `building_panels` |
| `military_building_combat_unit_summary_list_item` | `flowcontainer` | `building_panels` |
| `ownership_list_name` | `flowcontainer` | `building_panels` |
| `property_portfolio_stacked_bar_chart` | `property_portfolio_stacked_bar_chart_base` | `building_panels` |
| `property_portfolio_stacked_bar_chart_base` | `v3_stacked_barchart` | `building_panels` |
| `property_portfolio_stacked_bar_chart_short` | `property_portfolio_stacked_bar_chart_base` | `building_panels` |
| `simple_building_ownership_stacked_barchart` | `v3_stacked_barchart` | `building_panels` |
| `trade_center_export_headers` | `flowcontainer` | `building_panels` |
| `trade_center_import_headers` | `flowcontainer` | `building_panels` |

## gui/building_workforce_panel.gui

| Type | Base | Group |
|---|---|---|
| `building_details_panel_workforce_content` | `flowcontainer` | `building_panels` |

## gui/character_panel.gui

| Type | Base | Group |
|---|---|---|
| `character_holding` | `container` | `character_panel_types` |
| `character_interactions_button` | `button_icon_round` | `character_panel_types` |
| `character_interest_group_entry` | `character_stats_entry` | `character_stats` |
| `character_no_interest_group_entry` | `character_stats_entry` | `character_stats` |
| `character_panel` | `default_block_window_two_lines` | `character_panel_types` |
| `character_role_icon` | `widget` | `character_stats` |
| `character_stats_entry` | `widget` | `character_stats` |
| `character_traits` | `container` | `character_panel_types` |
| `character_traits_no_label` | `dynamicgridbox` | `character_panel_types` |
| `character_with_background` | `widget` | `character_panel_types` |
| `heir_and_favorite_character_portraits` | `flowcontainer` | `character_panel_types` |
| `promote_commander_button` | `button` | `character_panel_types` |

## gui/color_picker.gui

| Type | Base | Group |
|---|---|---|
| `colorpicker_simple` | `colorpicker` | `ColorPickerTypes` |
| `hbox_colorpicker_simple_components` | `hbox` | `ColorPickerTypes` |

## gui/combat_unit_types.gui

| Type | Base | Group |
|---|---|---|
| `button_all_ships_filter` | `widget` | `combat_unit_types` |
| `button_edit_ships` | `widget` | `combat_unit_types` |
| `cancel_retrofit_ship_button` | `widget` | `combat_unit_types` |
| `combat_unit_grid` | `fixedgridbox` | `combat_unit_types` |
| `combat_unit_item` | `widget` | `combat_unit_types` |
| `combat_unit_simple_grid` | `fixedgridbox` | `combat_unit_types` |
| `combat_unit_simple_item` | `widget` | `combat_unit_types` |
| `compact_ship_info_and_silhouette` | `widget` | `combat_unit_types` |
| `compact_ship_template` | `widget` | `combat_unit_types` |
| `country_ship_types` | `flowcontainer` | `combat_unit_types` |
| `retrofit_ship_button` | `button_icon_round_action` | `combat_unit_types` |
| `ship_bulk_change_buttons` | `flowcontainer` | `combat_unit_types` |
| `ship_group` | `flowcontainer` | `combat_unit_types` |
| `ship_group_fleet` | `flowcontainer` | `combat_unit_types` |
| `ship_item` | `widget` | `combat_unit_types` |
| `ship_silhouette_for_tooltips` | `widget` | `combat_unit_types` |
| `ship_type_silhouette` | `icon` | `combat_unit_types` |
| `ships_list` | `fixedgridbox` | `combat_unit_types` |

## gui/companies_panel.gui

| Type | Base | Group |
|---|---|---|
| `companies_panel` | `default_block_window` | `companies_panel` |
| `company_building_item` | `button` | `companies_panel` |
| `company_change_name_popup_type` | `default_popup` | `company_change_name` |
| `company_filter` | `flowcontainer` | `companies_panel` |
| `company_item` | `container` | `companies_panel` |
| `company_type_building_item` | `button` | `companies_panel` |
| `company_type_prestige_good_item` | `icon` | `companies_panel` |
| `potential_company_item` | `flowcontainer` | `companies_panel` |
| `prosperity_widget` | `flowcontainer` | `companies_panel` |

## gui/company_panel.gui

| Type | Base | Group |
|---|---|---|
| `company_charter_active_widget` | `widget` | `company_panel_types` |
| `company_charter_active_widget_horizontal` | `widget` | `company_panel_types` |
| `company_charter_button` | `button` | `company_panel_types` |
| `company_charter_button_horizontal` | `button` | `company_panel_types` |
| `company_hq_assets_item` | `flowcontainer` | `company_panel_types` |
| `company_info_item` | `vbox` | `company_panel_types` |
| `company_panel` | `default_block_window_two_lines` | `company_panel_types` |
| `company_panel_assets_tab` | `flowcontainer` | `company_panel_types` |
| `company_panel_overview_tab` | `flowcontainer` | `company_panel_types` |
| `company_panel_statistics_tab` | `flowcontainer` | `company_panel_types` |
| `independent_company_country_item` | `flowcontainer` | `company_panel_types` |

## gui/console.gui

| Type | Base | Group |
|---|---|---|
| `console_button` | `button` | `console_widgets` |

## gui/construction_panel.gui

| Type | Base | Group |
|---|---|---|
| `construction_panel` | `default_block_window_two_lines` | `construction_panel` |
| `construction_panel_ships_content` | `flowcontainer` | `construction_panel` |
| `ship_construction_add_to_queue` | `flowcontainer` | `construction_panel` |
| `ship_construction_queue` | `flowcontainer` | `construction_panel` |
| `ship_construction_queue_item` | `widget` | `construction_panel` |
| `ship_construction_queue_item_texts` | `hbox` | `construction_panel` |
| `supply_ship_construction_queue_item` | `widget` | `construction_panel` |
| `supply_ship_construction_queue_item_texts` | `hbox` | `construction_panel` |

## gui/construction_queue.gui

| Type | Base | Group |
|---|---|---|
| `construction_queue` | `flowcontainer` | `construction_queue` |
| `construction_queue_goto_building` | `button` | `construction_queue` |
| `construction_queue_item` | `widget` | `construction_queue` |
| `construction_queue_item_texts` | `widget` | `construction_queue` |

## gui/countries_panel.gui

| Type | Base | Group |
|---|---|---|
| `countries_panel` | `default_block_window` | `countries_panel_types` |

## gui/country_diplomacy_panel.gui

| Type | Base | Group |
|---|---|---|
| `country_panel_diplomacy_content` | `flowcontainer` | `country_panel_types` |

## gui/country_formation_panel.gui

| Type | Base | Group |
|---|---|---|
| `country_formation_panel` | `default_block_window_two_lines` | `country_formation_types` |

## gui/country_interactions_panel.gui

| Type | Base | Group |
|---|---|---|
| `country_panel_interactions_content` | `flowcontainer` | `country_panel_types` |

## gui/country_panel.gui

| Type | Base | Group |
|---|---|---|
| `ai_attitude` | `flowcontainer` | `country_info` |
| `article_icon_all_items` | `container` | `country_panel_treaties_types` |
| `article_icon_item` | `widget` | `country_panel_treaties_types` |
| `attitude_info` | `widget` | `diplomatic` |
| `autonomy_button` | `button_icon_round_action` | `diplomatic` |
| `compact_treaty_item` | `flowcontainer` | `country_panel_treaties_types` |
| `compact_war_reparation_treaty_item` | `flowcontainer` | `country_panel_treaties_types` |
| `country_SP_info` | `flowcontainer` | `country_info` |
| `country_arable_land_info` | `textbox` | `country_info` |
| `country_culture_info` | `textbox` | `country_info` |
| `country_gdp_info` | `textbox` | `country_info` |
| `country_government_info` | `textbox` | `country_info` |
| `country_panel` | `default_block_window_two_lines` | `country_panel_types` |
| `country_panel_information_content` | `flowcontainer` | `country_panel_types` |
| `country_population_info` | `textbox` | `country_info` |
| `country_rank_info` | `textbox` | `country_info` |
| `country_religion_info` | `textbox` | `country_info` |
| `country_stats_entry` | `widget` | `war_panel` |
| `country_stats_entry_game_over` | `widget` | `war_panel` |
| `diplomatic_action_acceptance_icon` | `container` | `war_panel` |
| `diplomatic_action_button` | `button` | `war_panel` |
| `diplomatic_info` | `flowcontainer` | `diplomatic` |
| `diplomatic_obligation_item_from` | `widget` | `war_panel` |
| `diplomatic_obligation_item_to` | `widget` | `war_panel` |
| `diplomatic_pact_container` | `dynamicgridbox` | `war_panel` |
| `diplomatic_pact_item` | `widget` | `war_panel` |
| `diplomatic_pact_type_item` | `container` | `war_panel` |
| `diplomatic_play_button_country` | `button` | `war_panel` |
| `diplomatic_play_button_state` | `button` | `war_panel` |
| `liberty_desire_bar_and_buttons` | `container` | `diplomatic` |
| `literacy_info` | `textbox` | `country_info` |
| `obligations_owed_from_container` | `container` | `war_panel` |
| `obligations_owed_to_container` | `container` | `war_panel` |
| `overlord` | `flowcontainer` | `diplomatic` |
| `panel_dropdown` | `flowcontainer` | `country_info` |
| `return_state_to_subject_button` | `button` | `war_panel` |
| `standard_of_living_clout_info` | `textbox` | `country_info` |
| `standard_of_living_population_info` | `textbox` | `country_info` |
| `treaties_country_list` | `flowcontainer` | `country_panel_treaties_types` |
| `treaty_country_dropdown` | `flowcontainer` | `country_panel_treaties_types` |
| `truce_container` | `container` | `war_panel` |
| `war_item` | `button` | `war_panel` |

## gui/country_politics_panel.gui

| Type | Base | Group |
|---|---|---|
| `country_panel_institution_item` | `widget` | `country_panel_types` |
| `country_panel_law_item` | `button` | `country_panel_types` |
| `country_panel_law_item_is_enacting` | `widget` | `country_panel_types` |
| `country_panel_politics_content` | `flowcontainer` | `country_panel_types` |

## gui/credits_window.gui

| Type | Base | Group |
|---|---|---|
| `JominiFrontEndCreditsView` | `widget` | `FrontEndCreditsView` |

## gui/culture_info_panel.gui

| Type | Base | Group |
|---|---|---|
| `culture_info_avg_sol_label` | `textbox` | `culture_info_panel_types` |
| `culture_info_panel` | `default_block_window_two_lines` | `culture_info_panel_types` |
| `culture_info_pop_label` | `hbox` | `culture_info_panel_types` |
| `culture_info_pop_portrait` | `pop_portrait_base` | `culture_info_panel_types` |
| `culture_or_religion_acceptance_section_flowcontainer` | `flowcontainer` | `culture_info_panel_types` |
| `culture_or_religion_labeled_value_flowcontainer` | `flowcontainer` | `culture_info_panel_types` |
| `culture_or_religion_labeled_value_left` | `flowcontainer` | `culture_info_panel_types` |

## gui/culture_panel.gui

| Type | Base | Group |
|---|---|---|
| `acceptance_group_with_law_status` | `top_illu` | `society_panel` |
| `acceptance_status_fancy_tooltip_large_icon` | `button` | `society_panel` |
| `acceptance_status_large_icon` | `button` | `society_panel` |
| `acceptance_status_portrait_portrait` | `pop_portrait_small` | `society_panel` |
| `acceptance_status_small_icon` | `button` | `society_panel` |
| `clickable_population_acceptance_status_chart` | `v3_clickable_stacked_barchart` | `society_panel` |
| `country_button` | `button` | `society_panel` |
| `culture_or_religion_list_dynamicgridbox` | `dynamicgridbox` | `society_panel` |
| `culture_or_religion_sort_buttons_widget` | `widget` | `society_panel` |
| `formable_country_button` | `container` | `society_panel` |
| `increasing_acceptance_icon` | `icon` | `society_panel` |
| `law_item_small` | `button` | `society_panel` |
| `pop_acceptance_icon` | `acceptance_status_small_icon` | `society_panel` |
| `population_acceptance_status_chart` | `v3_stacked_barchart` | `society_panel` |
| `population_acceptance_status_chart_with_label_flowcontainer` | `flowcontainer` | `society_panel` |
| `social_class_strata_column_flowcontainer` | `flowcontainer` | `society_panel` |
| `society_panel` | `default_block_window` | `society_panel` |

## gui/custom_tooltip.gui

| Type | Base | Group |
|---|---|---|
| `FancyTooltip_AIRegionalObjective` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_AIRegionalObjectiveType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_AIStrategicRegionStanceType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_AcceptanceStatus` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_AcceptanceStatusSegment` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Amendment` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_AmendmentType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_AmendmentTypeWithLaw` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Article` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ArticleDraft` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ArticleDraftWithCountryContext` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ArticleType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ArticleTypeInDraft` | `FancyTooltip_ArticleType` | `TooltipTypes` |
| `FancyTooltip_ArticleWithCountryContext` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_BattleCondition` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Building` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_BuildingGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_BuildingType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Character` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CharacterTrait` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CohesionLevel` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CombatUnitTypeWithCulture` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CombatUnitTypeWithoutCulture` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CommanderOrderType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CommanderRank` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Company` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CompanyCharter` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CompanyCharterType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CompanyType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ConcludedJournalEntry` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Country` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_CulturalCommunity` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Culture` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_DecreeType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_DiplomaticAction` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_DiplomaticActionType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_DiplomaticActionWithTargetCountry` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_DiscriminationTrait` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_DiscriminationTraitGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Front` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_GameConceptType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_GeographicRegion` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_GlossaryType` | `FancyTooltipGlossaryWidgetType` | `TooltipTypes` |
| `FancyTooltip_Goods` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Goods_Pop_Consumption` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_HarvestCondition` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_HarvestConditionArea` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_HarvestConditionType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_IG` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Ideology` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Institution` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_InstitutionType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_InterestGroupTrait` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_InterestTierType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_InterestTierTypeWithCountryAndStrategicRegionContext` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_JournalEntry` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_JournalEntryType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Law` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_LawGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_LawType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_LawWithCountryContext` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_LegitimacyLevel` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_LibertyDesireLevel` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Market` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_MilitaryFormation` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_MilitaryFormation_MapMarker` | `FancyTooltip_MilitaryFormation` | `TooltipTypes` |
| `FancyTooltip_MobilizationOption` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_MobilizationOptionGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ModifierBreakdown` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_NavalBattleCondition` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_NavalMission` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_NavalMissionType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Objective` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ObjectiveType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Party` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PoliticalLobby` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PoliticalMovement` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PoliticalMovementType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PoliticallyUnaligned` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Pop` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopAcceptance` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopNeed` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopSupporters` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopTypeBuilding` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopTypeCulture` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopTypeInterestGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopTypeReligion` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PopTypeState` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PowerBloc` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PowerBlocIdentity` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PowerBlocPrinciple` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PowerBlocPrincipleGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PowerBlocPrincipleSelection` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_PowerBlocPrincipleSlot` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ProductionMethod` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Religion` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Ship` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ShipGroup` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ShipModificationType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ShipTemplate` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ShipType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_ShipVeterancyLevel` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_SocialClass` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_SocialHierarchy` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_State` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_StateRegion` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Strait` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_StrategicRegion` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_SubjectType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Technology` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Technology_Tech_Tree` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_Treaty` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_War` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_WarGoal` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_WarGoalArticle` | `FancyTooltip_WarGoal` | `TooltipTypes` |
| `FancyTooltip_WarGoalDraft` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `FancyTooltip_WarGoalDraftArticle` | `FancyTooltip_WarGoalDraft` | `TooltipTypes` |
| `FancyTooltip_WarGoalType` | `FancyTooltipWidgetType` | `TooltipTypes` |
| `RegularTooltip_AdditionalSeaRegions` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_AdditionalShipTypes` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_AmendmentsList` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_CancelLawEnactment` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_CoastalBuildingMarker` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_CountriesWithInterest_MoreThan10` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_CountriesWithInterest_MoreThan25` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_CountryShips` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_FleetShipTemplateConstruction` | `RegularTooltip_ShipTemplateConstruction` | `TooltipTypes` |
| `RegularTooltip_LawEnactment` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_Leverage` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_LocalPrices` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_MarketFeesIncome` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_MarketWorldMarketExportsTo` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_MarketWorldMarketImportsFrom` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_NavalMissionMarker` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_NavalMissionMarkerEnemy` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_RetrofitShip` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_ShipTemplateConstruction` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_ShipTypeSupersededBy` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_StateWorldMarketExportDependence` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_StateWorldMarketImportDependence` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_SupplyOriginMarker` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_TimedModifierList` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_TreatyArticlesPage` | `RegularTooltip` | `TooltipTypes` |
| `RegularTooltip_TreatyProposal` | `RegularTooltip` | `TooltipTypes` |
| `acceptance_tooltip_bottom_section_flowcontainer` | `flowcontainer` | `TooltipTypes` |
| `coastal_building_marker_tooltip_row` | `flowcontainer` | `TooltipTypes` |
| `custom_tooltip_2_columns` | `flowcontainer` | `TooltipTypes` |
| `custom_tooltip_2_columns_text_values` | `widget` | `TooltipTypes` |
| `custom_tooltip_newline` | `widget` | `TooltipTypes` |
| `custom_tooltip_textbox` | `DefaultTooltipTextBox` | `TooltipTypes` |
| `custom_tooltip_textbox_column_width` | `custom_tooltip_textbox` | `TooltipTypes` |
| `custom_tooltip_textbox_fixed_width` | `custom_tooltip_textbox` | `TooltipTypes` |
| `custom_tooltip_textbox_with_empty_line` | `custom_tooltip_textbox` | `TooltipTypes` |
| `custom_tooltip_textbox_with_empty_line_fixed_width` | `custom_tooltip_textbox_with_empty_line` | `TooltipTypes` |
| `harvest_condition_tooltip_item` | `widget` | `TooltipTypes` |
| `interest_groups_with_approval_changes` | `flowcontainer` | `TooltipTypes` |
| `movement_affected_by_cancel_law_enactment_tooltip_item` | `flowcontainer` | `TooltipTypes` |
| `movement_affected_by_law_enactment_tooltip_item` | `flowcontainer` | `TooltipTypes` |
| `naval_mission_marker_tooltip_fleet` | `flowcontainer` | `TooltipTypes` |
| `principle_main_tooltip` | `flowcontainer` | `TooltipTypes` |
| `regional_objective_target_grid` | `dynamicgridbox` | `TooltipTypes` |
| `regional_objective_targets` | `flowcontainer` | `TooltipTypes` |
| `ship_modifier_stats_list` | `flowcontainer` | `TooltipTypes` |
| `ship_template_stats_list` | `flowcontainer` | `TooltipTypes` |
| `ship_type_obsolete_tooltip_line` | `custom_tooltip_textbox` | `TooltipTypes` |
| `tooltip_divider` | `widget` | `TooltipTypes` |
| `treaty_tooltip_article` | `widget` | `TooltipTypes` |
| `treaty_tooltip_article_entry` | `container` | `TooltipTypes` |
| `world_market_access_info` | `container` | `TooltipTypes` |

## gui/debug_menues.gui

| Type | Base | Group |
|---|---|---|
| `debug_menu_button` | `button` | `debug_menu_types` |
| `debug_menu_sub_button` | `button` | `debug_menu_types` |
| `header_textbox` | `textbox` | `debug_menu_types` |
| `ship_viewer_entity_states_widget` | `flowcontainer` | `ship_viewer_debug_types` |

## gui/decisions_panel.gui

| Type | Base | Group |
|---|---|---|
| `decisions_panel` | `default_block_window` | `decisions_panel_types` |

## gui/diplomatic_overview.gui

| Type | Base | Group |
|---|---|---|
| `country_browser_tab_content` | `flowcontainer` | `diplomatic_panel` |
| `diplo_actions_button` | `button_icon_round` | `diplomatic_panel` |
| `diplomacy_overview_tab_content` | `flowcontainer` | `diplomatic_panel` |
| `diplomatic_overview_panel` | `default_block_window` | `diplomatic_panel` |
| `nation_formation_tab_content` | `container` | `diplomatic_panel` |
| `releasable_country_button` | `container` | `diplomatic_panel` |
| `release_subject_tab_content` | `container` | `diplomatic_panel` |
| `subject_list` | `flowcontainer` | `diplomatic_panel` |
| `subject_list_item` | `flowcontainer` | `diplomatic_panel` |
| `subjects_tab_content` | `flowcontainer` | `diplomatic_panel` |
| `treaty_country_dropdown_player_country` | `flowcontainer` | `diplomatic_panel` |

## gui/diplomatic_play_panel.gui

| Type | Base | Group |
|---|---|---|
| `add_wargoal_button` | `button` | `custom_popup_types` |
| `diplo_play_side` | `flowcontainer` | `custom_popup_types` |
| `diplo_play_side_sway_tab` | `container` | `custom_popup_types` |
| `diplo_play_sway_approval` | `widget` | `custom_popup_types` |
| `diplo_play_sway_disapproval` | `widget` | `custom_popup_types` |
| `diplomatic_play_panel` | `default_block_window` | `diplomatic_play_panel_types` |
| `diplomatic_play_stance_lane_backer` | `flowcontainer` | `custom_popup_types` |
| `diplomatic_play_stance_lane_fence_and_leaning` | `flowcontainer` | `custom_popup_types` |
| `flag_with_str_left` | `widget` | `custom_popup_types` |
| `flag_with_str_right` | `widget` | `custom_popup_types` |
| `involved_countries_summary_gridbox` | `flowcontainer` | `custom_popup_types` |
| `war_goal_article_inputs` | `flowcontainer` | `custom_popup_types` |
| `war_goal_item` | `flowcontainer` | `custom_popup_types` |

## gui/election_panel.gui

| Type | Base | Group |
|---|---|---|
| `election_ig_list` | `flowcontainer` | `election_panel_types` |
| `election_panel` | `default_block_window_two_lines` | `election_panel_types` |

## gui/empty_state.gui

| Type | Base | Group |
|---|---|---|
| `empty_state` | `flowcontainer` | `empty_states` |
| `empty_state_dynamic_width` | `textbox` | `empty_states` |

## gui/eventwindow.gui

| Type | Base | Group |
|---|---|---|
| `event_icon` | `widget` | `event_window_types` |
| `event_window` | `default_popup_two_lines` | `event_window_types` |

## gui/front_panel.gui

| Type | Base | Group |
|---|---|---|
| `active_battles` | `flowcontainer` | `front_panel_types` |
| `battle_item` | `button` | `front_panel_types` |
| `casualties_list` | `flowcontainer` | `front_panel_types` |
| `country_participant_side` | `flowcontainer` | `front_panel_types` |
| `ended_battle_item` | `button` | `front_panel_types` |
| `front_marker_icon` | `flowcontainer` | `front_panel_types` |
| `front_movement_marker_icon` | `flowcontainer` | `front_panel_types` |
| `front_panel` | `default_block_window_two_lines` | `front_panel_types` |
| `front_participants_formations_list` | `flowcontainer` | `front_panel_types` |
| `front_participants_formations_list_item` | `flowcontainer` | `front_panel_types` |
| `front_participants_list_item` | `widget` | `front_panel_types` |
| `present_countries_side` | `flowcontainer` | `front_panel_types` |

## gui/frontend/frontend_dlc.gui

| Type | Base | Group |
|---|---|---|
| `dlc_button` | `button` | `dlc_types` |
| `dlc_collection` | `flowcontainer` | `dlc_types` |

## gui/frontend/frontend_ingame_menu.gui

| Type | Base | Group |
|---|---|---|
| `cloud_save_checkbutton` | `button_checkbox` | `SaveGameTypes` |

## gui/frontend/frontend_load.gui

| Type | Base | Group |
|---|---|---|
| `button_saved_games` | `button_standard_hover` | `LoadGameTypes` |
| `vbox_save_preview` | `vbox` | `LoadGameTypes` |
| `widget_load_game` | `widget` | `LoadGameTypes` |

## gui/frontend/frontend_loadingscreen.gui

| Type | Base | Group |
|---|---|---|
| `clickable_rng_seed` | `button_group` | `BasicFrontendTypes` |
| `clickable_version_number` | `button_group` | `BasicFrontendTypes` |
| `widget_loading_screen` | `widget` | `LoadingScreen` |

## gui/frontend/shared/buttons.gui

| Type | Base | Group |
|---|---|---|
| `button_checkbox` | `checkbutton` | `Buttons` |
| `button_checkbox_label` | `button_group` | `Buttons` |
| `button_drop` | `button_normal` | `Buttons` |
| `button_dropdown` | `button_normal` | `Buttons` |
| `button_expand` | `button_toggle` | `Buttons` |
| `button_frontend` | `button_normal` | `Buttons` |
| `button_primary` | `button_normal` | `Buttons` |
| `button_primary_big` | `button_normal` | `Buttons` |
| `button_radio` | `button_toggle` | `Buttons` |
| `button_radio_label` | `button_group` | `Buttons` |
| `button_standard` | `button_normal` | `Buttons` |
| `button_standard_back` | `button_standard` | `Buttons` |
| `button_standard_big` | `button_standard` | `Buttons` |
| `button_standard_clean` | `button_standard` | `Buttons` |
| `button_standard_hover` | `button_standard_clean` | `Buttons` |
| `button_standard_list` | `button_standard` | `Buttons` |
| `button_standard_small` | `button_standard` | `Buttons` |
| `button_tab` | `button_normal` | `Buttons` |
| `button_tab_vertical` | `button_normal` | `Buttons` |
| `button_tertiary` | `button_normal` | `Buttons` |
| `button_text` | `button` | `Buttons` |
| `buttons_window_control` | `flowcontainer` | `Buttons` |

## gui/frontend/shared/buttons_icons.gui

| Type | Base | Group |
|---|---|---|
| `button_account` | `button_icon` | `ButtonIcons` |
| `button_achievements` | `button_icon` | `ButtonIcons` |
| `button_army_select` | `button_icon` | `ButtonIcons` |
| `button_back` | `button_icon` | `ButtonIcons` |
| `button_change` | `button_icon` | `ButtonIcons` |
| `button_clear` | `button_icon` | `ButtonIcons` |
| `button_copy` | `button_icon` | `ButtonIcons` |
| `button_credits` | `button_icon` | `ButtonIcons` |
| `button_encyclopedia` | `button_icon` | `ButtonIcons` |
| `button_icon` | `button` | `ButtonIcons` |
| `button_icon_custom` | `button_icon` | `ButtonIcons` |
| `button_icon_highlight` | `button_icon` | `ButtonIcons` |
| `button_kick_player` | `button_icon` | `ButtonIcons` |
| `button_play` | `button_icon` | `ButtonIcons` |
| `button_rules` | `button_icon` | `ButtonIcons` |
| `button_select_arrow` | `button_icon_custom` | `ButtonIcons` |
| `button_settings` | `button_icon` | `ButtonIcons` |
| `button_theme_selector` | `button_icon` | `ButtonIcons` |

## gui/frontend/shared/defaults.gui

| Type | Base | Group |
|---|---|---|
| `background` | `background` | `Default` |
| `button_group` | `button_group` | `Default` |
| `container` | `container` | `Default` |
| `editbox` | `editbox` | `Default` |
| `flowcontainer` | `flowcontainer` | `Default` |
| `hbox` | `hbox` | `Default` |
| `highlight_icon` | `button` | `Default` |
| `icon` | `icon` | `Default` |
| `progressbar` | `progressbar` | `Default` |
| `proportional_icon` | `icon` | `Default` |
| `scrollarea` | `scrollarea` | `Default` |
| `textbox` | `textbox` | `Default` |
| `vbox` | `vbox` | `Default` |
| `video_icon` | `icon` | `Default` |
| `widget` | `widget` | `Default` |
| `window` | `window` | `Default` |

## gui/frontend/shared/edit_boxes.gui

| Type | Base | Group |
|---|---|---|
| `editbox_search_field` | `hbox` | `Editboxes` |
| `editbox_standard` | `margin_widget` | `Editboxes` |
| `editbox_standard_with_label` | `vbox` | `Editboxes` |

## gui/frontend/shared/hud.gui

| Type | Base | Group |
|---|---|---|
| `container_saving_indicator` | `container` | `HUD` |

## gui/frontend/shared/icons.gui

| Type | Base | Group |
|---|---|---|
| `achievements_disabled_icon` | `icon` | `IconTypes` |
| `achievements_enabled_icon` | `icon` | `IconTypes` |
| `cloud_save_icon` | `icon_flat_standard` | `IconTypes` |
| `icon_circle_green` | `icon` | `IconTypes` |
| `icon_flat_standard` | `icon` | `IconTypes` |
| `icon_has_password` | `icon_flat_standard` | `IconTypes` |
| `icon_multiplayer` | `icon_flat_standard` | `IconTypes` |
| `icon_observer` | `icon_flat_standard` | `IconTypes` |
| `icon_online_offline` | `icon_flat_standard` | `IconTypes` |
| `icon_ring` | `icon_flat_standard` | `IconTypes` |
| `invalid_save_icon` | `icon` | `IconTypes` |
| `ironman_disabled_icon` | `icon` | `IconTypes` |
| `ironman_save_icon` | `icon` | `IconTypes` |
| `missing_dlcs_icon` | `icon` | `IconTypes` |
| `paused_icon_bad` | `icon` | `IconTypes` |

## gui/frontend/shared/labels.gui

| Type | Base | Group |
|---|---|---|
| `text_label_center` | `text_single` | `LabelTypes` |
| `text_label_left` | `text_single` | `LabelTypes` |
| `text_multi` | `textbox` | `LabelTypes` |
| `text_single` | `textbox` | `LabelTypes` |

## gui/frontend/shared/lists.gui

| Type | Base | Group |
|---|---|---|
| `dropdown_menu_round` | `dropDown` | `Lists` |
| `dropdown_menu_standard` | `dropDown` | `Lists` |
| `scrollbox` | `scrollarea` | `Scrollbar` |

## gui/frontend/shared/sounds.gui

| Type | Base | Group |
|---|---|---|
| `button_arrow` | `button` | `ButtonSounds` |
| `button_decrement` | `button` | `ButtonSounds` |
| `button_increment` | `button` | `ButtonSounds` |
| `button_list_new` | `button` | `ButtonSounds` |
| `button_normal` | `button` | `ButtonSounds` |
| `button_normal_checkbutton` | `checkbutton` | `ButtonSounds` |
| `button_toggle` | `button` | `ButtonSounds` |

## gui/frontend/shared/windows.gui

| Type | Base | Group |
|---|---|---|
| `divider_light` | `divider_clean` | `WindowTypes` |
| `expand` | `widget` | `WindowTypes` |
| `header_pattern` | `widget` | `WindowTypes` |
| `header_standard` | `widget` | `WindowTypes` |
| `spacer` | `widget` | `WindowTypes` |

## gui/frontend_ingame_loadingscreen.gui

| Type | Base | Group |
|---|---|---|
| `loading_tip` | `container` | `loadingscreen_types` |

## gui/game_rules.gui

| Type | Base | Group |
|---|---|---|
| `flowcontainer_game_rules_mini` | `flowcontainer` | `GameRuleTypes` |
| `game_rules_preset_window` | `window` | `GameRuleTypes` |
| `hbox_achievements_info` | `hbox` | `GameRuleTypes` |
| `hbox_ironman_achievements_info` | `hbox` | `GameRuleTypes` |
| `widget_game_rule_option` | `widget` | `GameRuleTypes` |

## gui/generate_character.gui

| Type | Base | Group |
|---|---|---|
| `generate_character_type` | `default_popup` | `generate_character_types` |

## gui/goods_local_prices_panel.gui

| Type | Base | Group |
|---|---|---|
| `goods_local_prices_panel` | `default_block_window_two_lines` | `goods_local_prices_panel_types` |

## gui/goods_panel.gui

| Type | Base | Group |
|---|---|---|
| `consumption_tax_button_toggle` | `button_icon_round_toggle_action` | `production_method_items` |
| `good_icon_and_prize` | `container` | `production_method_items` |
| `goods_panel` | `default_block_window_two_lines` | `goods_panel_types` |
| `goods_prestige_goods_distribution` | `flowcontainer` | `production_method_items` |
| `goods_tooltip_price_info` | `container` | `production_method_items` |
| `map_modes` | `flowcontainer` | `production_method_items` |
| `map_modes_fake_static_filled_radiobutton` | `icon` | `production_method_items` |
| `map_modes_large_button` | `button` | `production_method_items` |
| `map_modes_minimized` | `map_modes` | `production_method_items` |
| `map_modes_single_button_minimized` | `flowcontainer` | `production_method_items` |
| `market_orders_list` | `flowcontainer` | `production_method_items` |
| `market_price_card` | `flowcontainer` | `production_method_items` |
| `producing_building_button` | `container` | `production_method_items` |
| `production_method_item` | `flowcontainer` | `production_method_items` |
| `small_building_type_targets_indicator` | `textbox` | `production_method_items` |
| `state_price_card` | `flowcontainer` | `production_method_items` |
| `world_market_price_card` | `flowcontainer` | `production_method_items` |

## gui/goods_state_panel.gui

| Type | Base | Group |
|---|---|---|
| `goods_state_panel` | `default_block_window_two_lines` | `goods_state_panel_types` |
| `goods_state_panel_input_output_item` | `container` | `goods_state_panel` |

## gui/goods_usage_panel.gui

| Type | Base | Group |
|---|---|---|
| `goods_usage_panel` | `default_block_window_two_lines` | `goods_usage_panel_tyes` |

## gui/goods_world_market_panel.gui

| Type | Base | Group |
|---|---|---|
| `goods_world_market_panel` | `default_block_window_two_lines` | `goods_world_market_panel_tyes` |

## gui/graph_tooltips.gui

| Type | Base | Group |
|---|---|---|
| `GraphTooltip_AdditionalExpenses` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_AdditionalIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_CashReserves` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_ConstructionGoodsExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_ConsumptionTax` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_CountryStandardOfLivingLower` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_CountryStandardOfLivingMiddle` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_CountryStandardOfLivingUpper` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_DiplomaticPactsExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_DiplomaticPactsIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_DividendsTax` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GoodsPrice` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GoodsWorldPrice` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GovernmentGoodsExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GovernmentShareDividends` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GovernmentShareLosses` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GovernmentSlavesExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_GovernmentWagesExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_IGClout` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_InterestExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_InvestmentIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_InvestmentPool` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_MilitaryGoodsExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_MilitarySlavesExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_MilitaryTotalExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_MilitaryWagesExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_Minting` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PiracyIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PoliticalMovementRadicalism` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PoliticalMovementSupport` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PopPoliticalStrength` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PopPopulation` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PopStandardOfLiving` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PowerBlocExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_PowerBlocIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_Productivity` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_SubsidiesExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_SubventionsExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_Tariffs` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TaxIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TaxPoll` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TotalExpenses` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TotalIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TreatyExpense` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TreatyIncome` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_TypeProfitability` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_WelfarePayments` | `TooltipWidgetType` | `graph_tooltips` |
| `GraphTooltip_WorldProfitability` | `TooltipWidgetType` | `graph_tooltips` |

## gui/important_actions_list.gui

| Type | Base | Group |
|---|---|---|
| `important_actions_list_expandable_item` | `flowcontainer` | `important_actions_list` |
| `important_actions_list_item` | `right_click_menu_item` | `important_actions_list` |

## gui/in_game_menu_logo.gui

| Type | Base | Group |
|---|---|---|
| `v3_logo_animation` | `container` | `ingame_menu_logo` |
| `v3_logo_animation_game_start` | `container` | `ingame_menu_logo` |

## gui/information_panel_bar.gui

| Type | Base | Group |
|---|---|---|
| `information_panel_bar` | `widget` | `information_panel_bar_types` |
| `power_bloc_icon_button_widget` | `widget` | `information_panel_bar_types` |

## gui/information_panels_types.gui

| Type | Base | Group |
|---|---|---|
| `panel_button_animation_arrow` | `icon` | `information_panels_types` |
| `panel_button_animation_arrow_small` | `icon` | `information_panels_types` |
| `sidebar_label_button` | `margin_widget` | `information_panels_types` |
| `sidebar_label_button_small` | `margin_widget` | `information_panels_types` |
| `sidebar_label_text` | `textbox` | `information_panels_types` |
| `sidebar_label_text_small` | `sidebar_label_text` | `information_panels_types` |
| `sidebar_tooltip_area` | `widget` | `information_panels_types` |
| `sidebar_tooltip_area_small` | `widget` | `information_panels_types` |
| `sidepanel_button_big` | `button_icon_round` | `information_panels_types` |
| `sidepanel_button_small` | `button_icon_round` | `information_panels_types` |

## gui/interest_group_panel.gui

| Type | Base | Group |
|---|---|---|
| `bolster_icon` | `widget` | `interest_group_panel_types` |
| `ig_heading_pop_portrait` | `widget` | `interest_group_panel_types` |
| `ig_loyal_radical_bar` | `flowcontainer` | `interest_group_panel_types` |
| `ig_overview_value_box` | `widget` | `interest_group_panel_types` |
| `ig_panel_clout_rating` | `widget` | `interest_group_panel_types` |
| `ig_panel_icon_label` | `flowcontainer` | `interest_group_panel_types` |
| `ig_trait_glow` | `widget` | `interest_group_panel_types` |
| `ig_trait_icon` | `widget` | `interest_group_panel_types` |
| `influential_ig_frame_80` | `widget` | `interest_group_panel_types` |
| `interest_group_panel` | `default_block_window_two_lines` | `interest_group_panel_types` |
| `number_of_pops` | `flowcontainer` | `interest_group_panel_types` |
| `suppress_icon` | `widget` | `interest_group_panel_types` |

## gui/invasion_panel.gui

| Type | Base | Group |
|---|---|---|
| `invasion_concluded` | `flowcontainer` | `invasion_types` |
| `invasion_formation` | `button` | `invasion_types` |
| `invasion_list_item` | `button` | `invasion_types` |
| `invasion_panel` | `default_block_window_two_lines` | `invasion_types` |
| `invasion_panel_battles_content` | `flowcontainer` | `invasion_types` |
| `invasion_panel_fail_condition_footer` | `flowcontainer` | `invasion_types` |
| `invasion_panel_land_invasion_overview_content` | `flowcontainer` | `invasion_types` |
| `invasion_panel_naval_invasion_overview_content` | `flowcontainer` | `invasion_types` |

## gui/jomini/music_player/music_player_view.gui

| Type | Base | Group |
|---|---|---|
| `music_category_button` | `button` | `music_player_types` |
| `music_player` | `default_popup` | `music_player_types` |
| `music_player_category` | `widget` | `music_player_types` |
| `music_player_track` | `widget` | `music_player_types` |

## gui/journal.gui

| Type | Base | Group |
|---|---|---|
| `concluded_journal_entry` | `flowcontainer` | `journal` |
| `decision` | `container` | `journal` |
| `journal_entry` | `button` | `journal` |
| `journal_entry_group_with_illustration` | `flowcontainer` | `journal` |
| `journal_entry_groups_list` | `flowcontainer` | `journal` |
| `journal_entry_scripted_progress_bars` | `flowcontainer` | `journal` |
| `journal_entry_themed_group_list` | `flowcontainer` | `journal` |
| `journal_entry_type` | `button` | `journal` |
| `journal_entry_ungrouped_concluded` | `flowcontainer` | `journal` |
| `journal_entry_ungrouped_list` | `flowcontainer` | `journal` |
| `journal_entry_ungrouped_potential` | `flowcontainer` | `journal` |
| `journal_panel` | `default_block_window` | `journal` |
| `player_objective_additional_entries` | `flowcontainer` | `journal` |
| `potential_journal_entry` | `journal_entry` | `journal` |

## gui/journal_entry.gui

| Type | Base | Group |
|---|---|---|
| `historical_journal_entry_outcome_icon_button` | `flowcontainer` | `journal_entry_panel_types` |
| `journal_entry_panel` | `default_block_window_two_lines` | `journal_entry_panel_types` |
| `scripted_journal_entry_button` | `button` | `journal_entry_panel_types` |
| `scripted_journal_entry_goal` | `widget` | `journal_entry_panel_types` |

## gui/journal_entry_widgets/custom_widgets.gui

| Type | Base | Group |
|---|---|---|
| `je_widget_ruler_large_type` | `icon` | `journal_entry_widget_types` |

## gui/journal_entry_widgets/ep2_japan_widgets.gui

| Type | Base | Group |
|---|---|---|
| `ep2_meiji_restoration_character_with_background_japanese_emperor` | `widget` | `ep2_japan_types` |
| `ep2_meiji_restoration_daimyos_widget` | `flowcontainer` | `ep2_japan_types` |
| `ep2_meiji_restoration_faction_button` | `widget` | `ep2_japan_types` |
| `ep2_meiji_restoration_faction_button_base` | `button_icon_round` | `ep2_japan_types` |

## gui/journal_entry_widgets/rlit_widgets.gui

| Type | Base | Group |
|---|---|---|
| `rlit_route_row` | `widget` | `rlit_widget_types` |
| `rlit_section_header` | `widget` | `rlit_widget_types` |

## gui/journal_entry_widgets/tsarpoints_widgets.gui

| Type | Base | Group |
|---|---|---|
| `tsarpoints_decree_button` | `widget` | `tsarpoints_widget_types` |

## gui/lens_toolbar.gui

| Type | Base | Group |
|---|---|---|
| `lens_buttons` | `widget` | `lens_toolbar_types` |
| `lens_option_button` | `widget` | `lens_toolbar_types` |
| `lens_option_menu` | `vbox` | `lens_toolbar_types` |
| `lens_tab_button` | `widget` | `lens_toolbar_types` |
| `lens_toolbar` | `widget` | `lens_toolbar_types` |

## gui/map_interaction.gui

| Type | Base | Group |
|---|---|---|
| `map_interaction_num_selections` | `textbox` | `map_interactions` |

## gui/map_list_panel.gui

| Type | Base | Group |
|---|---|---|
| `activate_conscription_center_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `build_building_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `colony_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `construction_filters` | `flowcontainer` | `map_list_panel_types` |
| `construction_headers_condensed` | `flowcontainer` | `map_list_panel_types` |
| `construction_headers_full` | `flowcontainer` | `map_list_panel_types` |
| `construction_interaction_item_condensed` | `map_list_panel_item_interaction` | `map_list_panel_types` |
| `construction_interaction_item_full` | `flowcontainer` | `map_list_panel_types` |
| `cossack_host_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `countries_map_list_panel` | `countries_map_list_panel_full` | `map_list_panel_types` |
| `countries_map_list_panel_full` | `map_list_panel` | `map_list_panel_types` |
| `countries_military_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `countries_ongoing_diplomatic_play_map_list_panel` | `countries_map_list_panel_full` | `map_list_panel_types` |
| `country_attitude_map_list_panel` | `country_map_list_one_value` | `map_list_panel_types` |
| `country_infamy_map_list_panel` | `country_map_list_one_value` | `map_list_panel_types` |
| `country_map_list_one_value` | `map_list_panel` | `map_list_panel_types` |
| `country_mass_migration_pull_list_panel` | `country_map_list_one_value` | `map_list_panel_types` |
| `country_relations_map_list_panel` | `country_map_list_one_value` | `map_list_panel_types` |
| `decree_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `default_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `diplo_action_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `diplo_action_rivalry_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `empty_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `harvest_condition_areas_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `interest_groups_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `map_list_panel` | `widget` | `map_list_panel_types` |
| `map_list_panel_item` | `button` | `map_list_panel_types` |
| `map_list_panel_item_interaction` | `widget` | `map_list_panel_types` |
| `markets_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `military_formation_deploy_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `military_formation_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `military_formation_set_strategic_objective_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `naval_mission_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `power_bloc_invitation_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `power_blocs_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `productivity_or_other_information` | `container` | `building_info` |
| `state_culture_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `state_gdp_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_gdp_nationally_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_gdp_ownership_ratio_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_literacy_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_loyalists_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_map_list_one_value` | `map_list_panel` | `map_list_panel_types` |
| `state_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `state_mass_migration_pull_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_migration_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_migration_pull_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_obstinance_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_pollution_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_population_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_production_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_radicals_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_religion_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `state_standard_of_living_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_starvation_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `state_state_infamy_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `state_state_value_map_list_panel` | `state_map_list_one_value` | `map_list_panel_types` |
| `strategic_regions_map_list_panel` | `map_list_panel` | `map_list_panel_types` |
| `treaty_article_map_list_panel` | `map_list_panel` | `map_list_panel_types` |

## gui/map_markers.gui

| Type | Base | Group |
|---|---|---|
| `country_with_interest_map_marker_item` | `container` | `map_marker_types` |
| `movement_marker_click_vfx` | `widget` | `map_marker_types` |
| `movement_marker_hover_vfx` | `widget` | `map_marker_types` |
| `movement_marker_knob` | `container` | `map_marker_types` |
| `movement_marker_knob_button` | `button` | `map_marker_types` |
| `naval_mission_marker_dot` | `widget` | `map_marker_types` |

## gui/mapeditor_customizations.gui

| Type | Base | Group |
|---|---|---|
| `CustomSliderWithValue` | `hbox` | `MapEditorCustomizationTypes` |
| `DynamicsMasterSwitch` | `editor_checkbutton` | `MapEditorCustomizationTypes` |

## gui/market_food_security_panel.gui

| Type | Base | Group |
|---|---|---|
| `basic_food_need_bar_chart` | `v3_stacked_barchart` | `market_panel` |
| `market_panel_food_security_content` | `flowcontainer` | `market_panel` |

## gui/market_panel.gui

| Type | Base | Group |
|---|---|---|
| `cannot_be_trade_icon` | `icon` | `market_panel` |
| `filter_background_selected` | `widget` | `market_panel` |
| `filter_button` | `button` | `market_panel` |
| `filter_selected_button` | `button` | `market_panel` |
| `goods_entry_button` | `flowcontainer` | `market_panel` |
| `goods_filter_button` | `button_icon_round_big` | `market_panel` |
| `goods_filters` | `flowcontainer` | `market_panel` |
| `goods_prestige_goods_breakdown_list_item` | `widget` | `market_panel` |
| `goods_prestige_goods_breakdown_list_item_selected` | `widget` | `market_panel` |
| `market_panel` | `default_block_window` | `market_panel` |
| `market_panel_details_content` | `container` | `market_panel` |
| `market_world_market_goods_list_item` | `widget` | `market_panel` |
| `prestige_good_change_name_popup_type` | `default_popup` | `prestige_good_change_name` |
| `state_goods_entry_button` | `button` | `market_panel` |

## gui/market_states_panel.gui

| Type | Base | Group |
|---|---|---|
| `market_panel_states_content` | `flowcontainer` | `market_states_panel` |
| `market_states_panel_state_entry` | `widget` | `market_states_panel` |

## gui/message_settings.gui

| Type | Base | Group |
|---|---|---|
| `alert_type_list_item` | `widget` | `message_settings` |
| `diplomatically_interesting_country_list_item` | `widget` | `message_settings` |
| `message_settings_window` | `default_popup` | `message_settings` |
| `notification_type_list_item` | `widget` | `message_settings` |

## gui/military_formation_panel.gui

| Type | Base | Group |
|---|---|---|
| `action_selection_number` | `textbox` | `military_formation_panel_types` |
| `borrow_lending_setting_option` | `button` | `military_formation_panel_types` |
| `borrow_lending_setting_option_selected` | `widget` | `military_formation_panel_types` |
| `combat_unit_entry` | `widget` | `military_formation_panel_types` |
| `combat_unit_type_group_summary` | `flowcontainer` | `military_formation_panel_types` |
| `combat_units_list` | `fixedgridbox` | `military_formation_panel_types` |
| `commander_order_button` | `widget` | `military_formation_panel_types` |
| `crew_bar` | `white_progressbar_vertical` | `military_formation_panel_types` |
| `default_unit_right_click_item` | `button` | `military_formation_panel_types` |
| `default_unit_right_click_item_selected` | `widget` | `military_formation_panel_types` |
| `fleet_formation_entry` | `widget` | `military_formation_panel_types` |
| `formation_bulk_action_button` | `button` | `military_formation_panel_types` |
| `header_grid_item` | `widget` | `formation_header` |
| `is_mobilizing_progressbar` | `widget` | `mobilization` |
| `manpower_bar` | `white_progressbar_vertical` | `military_formation_panel_types` |
| `military_formation_cancel_invasion_button` | `button` | `military_formation_panel_types` |
| `military_formation_change_name_popup_type` | `default_popup` | `military_formation_change_name` |
| `military_formation_combat_unit` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_commander` | `widget` | `military_formation_panel_types` |
| `military_formation_commander_medium` | `widget` | `military_formation_panel_types` |
| `military_formation_commander_small` | `widget` | `military_formation_panel_types` |
| `military_formation_icon_and_bars` | `widget` | `military_formation_panel_types` |
| `military_formation_mobilize_button` | `widget` | `military_formation_panel_types` |
| `military_formation_panel` | `default_block_window_two_lines` | `military_formation_panel_types` |
| `military_formation_panel_buildings_content_army` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_panel_buildings_content_fleet` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_panel_default_footer` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_panel_mobilization_content` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_panel_overview_content` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_panel_ships_content` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_top_illu_info` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_top_illu_info_fleet` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_top_illu_supply` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_unit_group_simple` | `container` | `military_formation_panel_types` |
| `military_formation_unit_type_default` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_unit_type_default_not_valid` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_unit_type_group` | `flowcontainer` | `military_formation_panel_types` |
| `military_formation_unit_type_group_small` | `flowcontainer` | `military_formation_panel_types` |
| `mobilization_option_group` | `flowcontainer` | `military_formation_panel_types` |
| `naval_mission_button` | `button` | `military_formation_panel_types` |
| `naval_mission_button_small` | `widget` | `military_formation_panel_types` |
| `offense_defense_info` | `flowcontainer` | `military_formation_panel_types` |
| `offense_defense_info_small` | `offense_defense_info` | `military_formation_panel_types` |
| `offense_defense_info_text` | `flowcontainer` | `military_formation_panel_types` |
| `organization_bar` | `white_progressbar_vertical` | `military_formation_panel_types` |
| `raise_conscripts_button` | `widget` | `military_formation_panel_types` |
| `set_level_bar_supply_priority` | `set_level_bar` | `military_formation_panel_types` |
| `small_header_grid_item` | `widget` | `formation_header` |
| `unit_group_default_unit_button` | `button` | `military_formation_panel_types` |
| `unit_group_upgrade_all_unit_button` | `button` | `military_formation_panel_types` |

## gui/military_panel_formations.gui

| Type | Base | Group |
|---|---|---|
| `commander_and_formation_orders` | `widget` | `MilitaryPanelCharacters` |
| `hit_points_bar` | `white_progressbar_vertical` | `MilitaryPanelCharacters` |
| `military_formation_list` | `flowcontainer` | `MilitaryPanelCharacters` |
| `military_formation_supply_ships` | `flowcontainer` | `MilitaryPanelCharacters` |
| `military_panel_formation_entry` | `flowcontainer` | `MilitaryPanelCharacters` |
| `morale_bar` | `white_progressbar_vertical` | `MilitaryPanelCharacters` |
| `rank_icon` | `widget` | `MilitaryPanelCharacters` |
| `retrofit_all_ships` | `flowcontainer` | `MilitaryPanelCharacters` |

## gui/modifier_debugger.gui

| Type | Base | Group |
|---|---|---|
| `modifier_button` | `editor_button` | `modifier_debugger` |
| `modifier_graph` | `zoomarea` | `modifier_debugger` |
| `modifier_list_numberbox` | `modifier_list_textbox` | `modifier_debugger` |
| `modifier_list_plotline` | `plotline` | `modifier_debugger` |
| `modifier_list_scrollbar_spacing` | `widget` | `modifier_debugger` |
| `modifier_list_textbox` | `textbox` | `modifier_debugger` |
| `modifier_list_widget` | `widget` | `modifier_debugger` |

## gui/modifiers_panel.gui

| Type | Base | Group |
|---|---|---|
| `modifier_list` | `flowcontainer` | `modifiers_panel` |
| `modifier_list_content` | `flowcontainer` | `modifiers_panel` |

## gui/multiplayer_types.gui

| Type | Base | Group |
|---|---|---|
| `JominiJoinServerDialogWindow` | `window` | `JominiServerBrowser` |
| `JominiLobbyCollapseButton` | `button_expand` | `JominiMultiplayerLobby` |
| `JominiLobbyExpandButton` | `button_expand` | `JominiMultiplayerLobby` |
| `JominiLobbyRemovePlayer` | `button` | `JominiMultiplayerLobby` |
| `JominiLobbyViewBack` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewButton` | `button_standard` | `JominiMultiplayerLobby` |
| `JominiLobbyViewEndPreparationConfirmation` | `widget` | `JominiMultiplayerLobby` |
| `JominiLobbyViewGameInfoPanel` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewHost` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewHostError` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewHostingStatus` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewMPInfo` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewPlayerItem` | `hbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewPlayerList` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewPreparation` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewSelectionWidget` | `vbox` | `JominiMultiplayerLobby` |
| `JominiLobbyViewServerInfoEntry` | `button` | `JominiMultiplayerLobby` |
| `JominiMultiplayerCheckbutton` | `hbox` | `JominiMultiplayerGameTypes` |
| `JominiMultiplayerFrontEndButton` | `button_standard` | `JominiMultiplayerGameTypes` |
| `JominiMultiplayerFrontendView` | `widget` | `JominiMultiplayerFrontend` |
| `JominiMultiplayerJoinRequest` | `window` | `JominiMultiplayerIngame` |
| `JominiMultiplayerLobby` | `widget` | `JominiMultiplayerLobby` |
| `JominiMultiplayerOosMessage` | `window` | `JominiMultiplayerIngame` |
| `JominiMultiplayerPushButton` | `button` | `JominiServerBrowser` |
| `JominiMultiplayerSetup` | `window` | `JominiMultiplayerSetup` |
| `JominiMultiplayerSetupCheckButton` | `hbox` | `JominiMultiplayerSetup` |
| `JominiMultiplayerSetupEditBox` | `editbox` | `JominiMultiplayerSetup` |
| `JominiMultiplayerSetupTextBox` | `text_single` | `JominiMultiplayerSetup` |
| `JominiMultiplayerSortButtonAsc` | `button` | `JominiMultiplayerGameTypes` |
| `JominiMultiplayerSortButtonDesc` | `button` | `JominiMultiplayerGameTypes` |
| `JominiMultiplayerTextbox` | `textbox` | `JominiMultiplayerGameTypes` |
| `JominiServerBrowserWindow` | `window` | `JominiServerBrowser` |

## gui/naval_battle.gui

| Type | Base | Group |
|---|---|---|
| `attacker_admiral` | `widget` | `naval_battle_panel_types` |
| `attacker_battle_log_actor` | `flowcontainer` | `naval_battle_panel_types` |
| `attacker_battle_log_target` | `flowcontainer` | `naval_battle_panel_types` |
| `attacker_progress` | `flowcontainer` | `naval_battle_panel_types` |
| `battle_log_entry` | `widget` | `naval_battle_panel_types` |
| `battle_log_entry_condition` | `widget` | `naval_battle_panel_types` |
| `battle_log_entry_withdrew` | `widget` | `naval_battle_panel_types` |
| `battle_results` | `flowcontainer` | `naval_battle_panel_types` |
| `defender_admiral` | `widget` | `naval_battle_panel_types` |
| `defender_battle_log_actor` | `flowcontainer` | `naval_battle_panel_types` |
| `defender_battle_log_target` | `flowcontainer` | `naval_battle_panel_types` |
| `defender_progress` | `flowcontainer` | `naval_battle_panel_types` |
| `diorama_stats` | `flowcontainer` | `naval_battle_panel_types` |
| `ended_naval_battle_item` | `button` | `naval_battle_panel_types` |
| `filter_background_selected_battle_log` | `widget` | `naval_battle_panel_types` |
| `filter_button_battle_log` | `button` | `naval_battle_panel_types` |
| `fleets_grid_item` | `widget` | `naval_battle_panel_types` |
| `naval_battle_fleets_grid` | `flowcontainer` | `naval_battle_panel_types` |
| `naval_battle_item` | `button` | `naval_battle_panel_types` |
| `naval_battle_panel` | `default_block_window_two_lines` | `naval_battle_panel_types` |
| `naval_battle_side_content_attacker` | `flowcontainer` | `naval_battle_panel_types` |
| `naval_battle_side_content_defender` | `flowcontainer` | `naval_battle_panel_types` |
| `naval_battle_side_fleet` | `button` | `naval_battle_panel_types` |
| `naval_battle_side_ships_list` | `flowcontainer` | `naval_battle_panel_types` |

## gui/notifications.gui

| Type | Base | Group |
|---|---|---|
| `button_cancel` | `button_icon` | `Toasts` |
| `message_feed_go_to_button` | `button_icon_round` | `notifications` |
| `message_feed_go_to_text_area_button` | `button` | `notifications` |
| `message_feed_group_member_header` | `button` | `notifications` |
| `message_feed_widget` | `widget` | `notifications` |
| `message_feed_widget_inner` | `widget` | `notifications` |
| `notifications_toasts` | `widget` | `notifications` |

## gui/objective_types.gui

| Type | Base | Group |
|---|---|---|
| `game_rules_hbox` | `hbox` | `objective_types` |
| `objective_selection_menu` | `widget` | `objective_types` |
| `recommended_country` | `widget` | `objective_types` |
| `start_game_buttons` | `widget` | `objective_types` |

## gui/outliner.gui

| Type | Base | Group |
|---|---|---|
| `outliner` | `outliner_type` | `outliner_types` |
| `outliner_tab_button` | `container` | `outliner_tabs` |

## gui/outliner_framework.gui

| Type | Base | Group |
|---|---|---|
| `expand_buttons` | `container` | `outliner_framework` |
| `expandable_outliner_entry` | `outliner_entry` | `outliner_framework` |
| `outliner_content` | `vbox` | `outliner_framework` |
| `outliner_entry` | `button` | `outliner_framework` |
| `outliner_group` | `flowcontainer` | `outliner_framework` |
| `outliner_type` | `widget` | `outliner_framework` |
| `pin_buttons` | `widget` | `outliner_framework` |
| `pinnable_expandable_outliner_entry` | `outliner_entry` | `outliner_framework` |
| `pinnable_outliner_entry` | `outliner_entry` | `outliner_framework` |
| `pinnable_outliner_group` | `outliner_group` | `outliner_framework` |
| `pinned_expand_buttons` | `expand_buttons` | `outliner_framework` |

## gui/outliner_ongoing_types.gui

| Type | Base | Group |
|---|---|---|
| `diplomatic_play_item` | `container` | `ongoing_outliner_items` |
| `diplomatic_play_item_impl` | `widget` | `ongoing_outliner_items` |
| `enactment_button` | `widget` | `ongoing_outliner_items` |
| `enactment_phase` | `hbox` | `ongoing_outliner_items` |
| `enactment_setback` | `widget` | `ongoing_outliner_items` |
| `event_item` | `widget` | `ongoing_outliner_items` |
| `event_item_hbox` | `hbox` | `ongoing_outliner_items` |
| `law_enactment_events_vbox` | `vbox` | `ongoing_outliner_items` |
| `law_negotiation_events_vbox` | `vbox` | `ongoing_outliner_items` |
| `outliner_diplomatic_pact_item` | `button` | `ongoing_outliner_items` |
| `outliner_diplomatic_pacts` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_diplomatic_plays` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_election` | `button` | `ongoing_outliner_items` |
| `outliner_events` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_journal_entries` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_journal_entry` | `journal_entry` | `ongoing_outliner_items` |
| `outliner_law_enactment` | `container` | `ongoing_outliner_items` |
| `outliner_law_enactment_events` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_law_negotiation_events` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_players` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_revolutionary_movement_events` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_revolutionary_political_movement_item` | `flowcontainer` | `ongoing_outliner_items` |
| `outliner_war_item` | `widget` | `ongoing_outliner_items` |
| `outliner_wars` | `fixedgridbox` | `ongoing_outliner_items` |

## gui/outliner_pinnable_types.gui

| Type | Base | Group |
|---|---|---|
| `building_in_state_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `character_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `commander_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `company_outliner_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `country_outliner_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `formation_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `goods_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `interest_group_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `market_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `non_revolutionary_political_movement_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `outliner_agitators` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_buildings` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_colonies` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_commanders` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_compact_enforced_treaty_item` | `flowcontainer` | `pinnable_outliner_items` |
| `outliner_compact_treaty_item` | `flowcontainer` | `pinnable_outliner_items` |
| `outliner_companies` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_countries` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_executives` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_formations` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_goods` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_heirs` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_interest_groups` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_magnates` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_markets` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_non_revolutionary_political_movements` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_other` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_political_lobbies` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_politicians` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_rulers` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_states` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_strategic_regions` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `outliner_treaties` | `pinnable_outliner_group` | `pinnable_outliner_items` |
| `player_item` | `flowcontainer` | `pinnable_outliner_items` |
| `political_lobby_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `politician_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `state_item` | `pinnable_outliner_entry` | `pinnable_outliner_items` |
| `strategic_region_outliner_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |
| `treaty_outliner_item` | `pinnable_expandable_outliner_entry` | `pinnable_outliner_items` |

## gui/panel_military.gui

| Type | Base | Group |
|---|---|---|
| `big_mobilize_all_button` | `container` | `mobilization_options` |
| `conscription_icon_big` | `widget` | `panel_military` |
| `icon_with_background_big` | `widget` | `panel_military` |
| `military_panel_army_content` | `flowcontainer` | `panel_military` |
| `military_panel_navy_content` | `flowcontainer` | `panel_military` |
| `military_panel_sailors_info` | `flowcontainer` | `panel_military` |
| `military_panel_ship_info` | `flowcontainer` | `panel_military` |
| `mobilization_controls` | `widget` | `panel_military` |
| `mobilization_icon` | `widget` | `panel_military` |
| `mobilization_option_small` | `widget` | `mobilization_options` |
| `mobilization_widget` | `flowcontainer` | `mobilization_options` |
| `panel_military` | `default_block_window` | `panel_military` |
| `supply_network_information_small` | `flowcontainer` | `panel_military` |
| `supply_route_filter_checkbox` | `flowcontainer` | `panel_military` |
| `supply_route_filter_row` | `flowcontainer` | `panel_military` |
| `tab_army` | `top_illu` | `panel_military` |
| `tab_navy` | `top_illu` | `panel_military` |

## gui/party_panel.gui

| Type | Base | Group |
|---|---|---|
| `party_panel` | `default_block_window_two_lines` | `party_panel_types` |

## gui/pdx_account/base_types.gui

| Type | Base | Group |
|---|---|---|
| `sdk_button` | `button` | `SDK` |
| `sdk_button_load_indicator` | `button_standard` | `SDK` |
| `sdk_button_wide` | `sdk_button` | `SDK` |
| `sdk_checkbutton` | `hbox` | `SDK` |
| `sdk_dropdown` | `dropDown` | `SDK` |
| `sdk_dropdown_entry` | `hbox` | `SDK` |
| `sdk_error_textbox` | `textbox` | `SDK` |
| `sdk_horizontal_spacer` | `widget` | `SDK` |
| `sdk_load_indicator` | `cogwheel_animation_small` | `SDK` |
| `sdk_required_textbox` | `textbox` | `SDK` |
| `sdk_textbox` | `textbox` | `SDK` |
| `sdk_textbox_entry` | `hbox` | `SDK` |
| `sdk_vertical_spacer` | `widget` | `SDK` |
| `sdk_window` | `window` | `SDK` |

## gui/pdx_account/create_account_window.gui

| Type | Base | Group |
|---|---|---|
| `create_account_window` | `window` | `SDK` |

## gui/pdx_account/login_window.gui

| Type | Base | Group |
|---|---|---|
| `login_window` | `window` | `SDK` |
| `sdk_login_accountwidget` | `button_account` | `SDK` |

## gui/political_lobby_panel.gui

| Type | Base | Group |
|---|---|---|
| `appeasement_factor_item` | `flowcontainer` | `political_lobby_panel_types` |
| `political_lobby_icon_and_flag` | `widget` | `political_lobby_panel_types` |
| `political_lobby_icon_and_flag_tiny` | `widget` | `political_lobby_panel_types` |
| `political_lobby_list_item` | `widget` | `political_lobby_panel_types` |
| `political_lobby_panel` | `default_block_window_two_lines` | `political_lobby_panel_types` |
| `politics_panel_top` | `top_illu` | `political_lobby_panel_types` |

## gui/political_movement_panel.gui

| Type | Base | Group |
|---|---|---|
| `agitator_in_movement_panel` | `widget` | `political_movement_panel_types` |
| `ideology_law_group` | `vbox` | `political_movement_panel_types` |
| `ideology_laws_list` | `hbox` | `political_movement_panel_types` |
| `interest_group_in_movement_info` | `widget` | `political_movement_panel_types` |
| `movement_affected_laws_column` | `vbox` | `political_movement_panel_types` |
| `movement_law_icon` | `widget` | `political_movement_panel_types` |
| `political_movement_panel` | `default_block_window_two_lines` | `political_movement_panel_types` |
| `political_movement_top_illu` | `top_illu` | `political_movement_panel_types` |
| `pop_list_gridbox` | `dynamicgridbox` | `political_movement_panel_types` |
| `revolutionary_political_movement_top_illu` | `top_illu` | `political_movement_panel_types` |

## gui/politics_panel.gui

| Type | Base | Group |
|---|---|---|
| `politics_panel` | `fullscreen_block_window` | `politics_panel_types` |

## gui/politics_panel_change_law.gui

| Type | Base | Group |
|---|---|---|
| `law_effects_view_button` | `widget` | `politics_panel_change_law` |
| `politics_panel_change_law` | `fullscreen_block_window` | `politics_panel_change_law` |
| `selected_or_enacting_law_content` | `vbox` | `politics_panel_change_law` |

## gui/politics_panel_constitution.gui

| Type | Base | Group |
|---|---|---|
| `law_enactment_progress` | `widget` | `politics_panel_types` |
| `law_icon` | `widget` | `politics_panel_types` |
| `politics_panel_laws_content` | `vbox` | `politics_panel_types` |

## gui/politics_panel_institutions.gui

| Type | Base | Group |
|---|---|---|
| `institution_icon` | `widget` | `politics_panel_types` |
| `politics_panel_institutions_content` | `vbox` | `politics_panel_types` |

## gui/politics_panel_overview.gui

| Type | Base | Group |
|---|---|---|
| `ig_item_bar` | `hbox` | `politics_panel_types` |
| `ig_item_loyalists_and_radicals` | `vbox` | `politics_panel_types` |
| `politics_panel_legitimacy_item` | `vbox` | `politics_panel_types` |
| `politics_panel_overview_content` | `hbox` | `politics_panel_types` |
| `politics_panel_ruler_item` | `widget` | `politics_panel_types` |
| `ruler_stats_entry` | `widget` | `politics_panel_types` |

## gui/politics_panel_reform_government.gui

| Type | Base | Group |
|---|---|---|
| `laws_support_list` | `vbox` | `politics_panel_types` |
| `politics_panel_government` | `vbox` | `politics_panel_types` |
| `politics_panel_government_details` | `hbox` | `politics_panel_types` |
| `politics_panel_government_reform` | `politics_panel_government_details` | `politics_panel_types` |
| `politics_panel_reform_no_ruler_item` | `widget` | `politics_panel_types` |
| `reform_government_option` | `button` | `politics_panel_types` |

## gui/politics_panel_types.gui

| Type | Base | Group |
|---|---|---|
| `active_law` | `vbox` | `information_panels_types` |
| `agitators_movements_endorsement_list` | `flowcontainer` | `information_panels_types` |
| `amendment` | `vbox` | `information_panels_types` |
| `amendment_flowcontainer` | `flowcontainer` | `information_panels_types` |
| `amendment_list` | `vbox` | `information_panels_types` |
| `amendment_list_flowcontainer` | `flowcontainer` | `information_panels_types` |
| `approval_info` | `flowcontainer` | `information_panels_types` |
| `approval_info2` | `widget` | `information_panels_types` |
| `approval_info_small` | `flowcontainer` | `information_panels_types` |
| `approval_info_small2` | `flowcontainer` | `information_panels_types` |
| `can_enact_icon` | `icon` | `information_panels_types` |
| `character_trait_with_label` | `flowcontainer` | `information_panels_types` |
| `chart` | `container` | `information_panels_types` |
| `compact_chart` | `container` | `information_panels_types` |
| `enactable_generic_law` | `flowcontainer` | `information_panels_types` |
| `enactable_generic_law2` | `hbox` | `information_panels_types` |
| `enactable_generic_law3` | `enactable_generic_law2` | `information_panels_types` |
| `enacting_law` | `hbox` | `information_panels_types` |
| `endorsement_info_bar` | `flowcontainer` | `information_panels_types` |
| `exiled_agitator` | `hbox` | `information_panels_types` |
| `ig_button` | `ig_icon` | `information_panels_types` |
| `ig_icon` | `widget` | `information_panels_types` |
| `ig_item_details` | `vbox` | `information_panels_types` |
| `in_government_header` | `flowcontainer` | `information_panels_types` |
| `in_opposition_header` | `flowcontainer` | `information_panels_types` |
| `influential_icon` | `icon` | `information_panels_types` |
| `interest_group_filter` | `hbox` | `information_panels_types` |
| `investment_button_active` | `button` | `information_panels_types` |
| `investment_button_inactive` | `button` | `information_panels_types` |
| `law_changable_widget` | `widget` | `information_panels_types` |
| `law_content` | `vbox` | `information_panels_types` |
| `law_enactment_controls` | `flowcontainer` | `information_panels_types` |
| `law_enactment_controls2` | `hbox` | `information_panels_types` |
| `laws_list` | `vbox` | `information_panels_types` |
| `marginal_header` | `flowcontainer` | `information_panels_types` |
| `parties_and_ig_list_details` | `vbox` | `information_panels_types` |
| `party_icon` | `widget` | `information_panels_types` |
| `political_movement_item` | `button` | `information_panels_types` |
| `politics_panel_political_movement_item` | `flowcontainer` | `information_panels_types` |
| `revolution_progress_bar` | `bad_progressbar_horizontal` | `information_panels_types` |
| `v3_clickable_stacked_barchart` | `widget` | `information_panels_types` |
| `v3_piechart` | `container` | `information_panels_types` |
| `v3_plotline` | `flowcontainer` | `information_panels_types` |
| `v3_plotline_clout` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_current_value_marker` | `widget` | `information_panels_types` |
| `v3_plotline_current_value_readout` | `widget` | `information_panels_types` |
| `v3_plotline_gdp` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_hbox` | `vbox` | `information_panels_types` |
| `v3_plotline_ig_radicals_loyalists` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_incorporated_literacy` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_money` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_population` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_population_lower` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_population_middle` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_population_upper` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_prestige` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_radicals_loyalists` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_sol` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_sol_lower` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_sol_middle` | `v3_plotline` | `information_panels_types` |
| `v3_plotline_sol_upper` | `v3_plotline` | `information_panels_types` |
| `v3_stacked_barchart` | `widget` | `information_panels_types` |
| `v3_treemapchart` | `container` | `information_panels_types` |

## gui/pop_browser_panel.gui

| Type | Base | Group |
|---|---|---|
| `browser_chart` | `container` | `pop_browser_panel_types` |
| `filtered_culture_population_piechart` | `browser_chart` | `pop_browser_panel_types` |
| `filtered_pop_type_pol_str_piechart` | `browser_chart` | `pop_browser_panel_types` |
| `filtered_pop_type_population_piechart` | `browser_chart` | `pop_browser_panel_types` |
| `filtered_religion_population_piechart` | `browser_chart` | `pop_browser_panel_types` |
| `filtered_state_population_piechart` | `browser_chart` | `pop_browser_panel_types` |
| `pop_browser_panel` | `fullscreen_block_window` | `pop_browser_panel_types` |

## gui/pop_details_panel.gui

| Type | Base | Group |
|---|---|---|
| `consumption_goods_fancy` | `button` | `pop_details_panel` |
| `consumption_goods_list_item` | `widget` | `pop_details_panel` |
| `pop_details_panel` | `default_block_window_two_lines` | `pop_details_panel` |
| `pop_details_side_stats_item` | `widget` | `pop_details_panel` |

## gui/pops_overview.gui

| Type | Base | Group |
|---|---|---|
| `character_filter` | `flowcontainer` | `pops_overview` |
| `character_list_sort_header` | `flowcontainer` | `pops_overview` |
| `character_panel_item` | `widget` | `pops_overview` |
| `culture_pol_str_piechart` | `chart` | `pops_overview` |
| `culture_population_piechart` | `chart` | `pops_overview` |
| `market_exporters_piechart` | `chart` | `pops_overview` |
| `market_importers_piechart` | `chart` | `pops_overview` |
| `market_starvation_piechart` | `chart` | `pops_overview` |
| `pop_list` | `flowcontainer` | `pops_overview` |
| `pop_list_summary_section_item_vbox` | `vbox` | `pops_overview` |
| `pop_list_summary_widget` | `widget` | `pops_overview` |
| `pop_overview_category_entry` | `container` | `pops_overview` |
| `pop_strata_summary` | `flowcontainer` | `pops_overview` |
| `pop_type_pol_str_piechart` | `chart` | `pops_overview` |
| `pop_type_population_piechart` | `chart` | `pops_overview` |
| `pops_overview_panel` | `default_block_window` | `pops_overview` |
| `pops_overview_statistics` | `flowcontainer` | `pops_overview` |
| `religion_pol_str_piechart` | `chart` | `pops_overview` |
| `religion_population_piechart` | `chart` | `pops_overview` |
| `strata_pop_need_item` | `button` | `pops_overview` |
| `strata_taxation_item` | `widget` | `pops_overview` |
| `thin_show_more_button` | `button` | `pops_overview` |

## gui/popups.gui

| Type | Base | Group |
|---|---|---|
| `base_general_information_window` | `container` | `notifications` |
| `default_confirmation_window` | `container` | `notifications` |
| `default_notification` | `notification_popup` | `notifications` |
| `nationalize_effect` | `hbox` | `nationalize_popup_types` |
| `nationalize_effect_divider` | `divider_clean` | `nationalize_popup_types` |
| `notification_popup` | `default_popup` | `notifications` |
| `popup_textbox` | `textbox` | `notifications` |
| `start_diplo_play_table` | `flowcontainer` | `start_diplo_play` |

## gui/power_bloc_formation_panel.gui

| Type | Base | Group |
|---|---|---|
| `color_option` | `flowcontainer` | `power_bloc_formation` |
| `customization_option` | `flowcontainer` | `power_bloc_formation` |
| `customization_option_item` | `widget` | `power_bloc_formation` |
| `framed_customize_button` | `button` | `power_bloc_formation` |
| `framed_icon` | `widget` | `power_bloc_formation` |
| `power_bloc_coa_piece_item` | `widget` | `power_bloc_formation` |
| `power_bloc_customization_popup_type` | `default_popup` | `power_bloc_formation` |
| `power_bloc_formation_panel` | `default_block_window` | `power_bloc_formation` |
| `power_bloc_identity_right_click_menu_item` | `container` | `power_bloc_formation` |
| `power_bloc_map_texture_item` | `widget` | `power_bloc_formation` |
| `principle_group_no_interact` | `flowcontainer` | `power_bloc_formation` |

## gui/power_bloc_panel.gui

| Type | Base | Group |
|---|---|---|
| `active_principle_slot` | `widget` | `power_bloc_panel_types` |
| `leverage_stacked_barchart` | `v3_stacked_barchart` | `power_bloc_panel_types` |
| `leverage_target_stacked_barchart` | `leverage_stacked_barchart` | `power_bloc_panel_types` |
| `locked_active_principle_slot` | `widget` | `power_bloc_panel_types` |
| `locked_principle_slot` | `widget` | `power_bloc_panel_types` |
| `new_principle_slot` | `button` | `power_bloc_panel_types` |
| `power_bloc_debug_info` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_header_grid_item` | `header_grid_item` | `power_bloc_panel_types` |
| `power_bloc_identity_icon` | `icon` | `power_bloc_panel_types` |
| `power_bloc_leader` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_list_item` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_list_item_bottom_buttons` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_list_item_emblem_button` | `button_icon_round` | `power_bloc_panel_types` |
| `power_bloc_list_item_grid_values` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_member_item` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_panel` | `default_block_window_two_lines` | `power_bloc_panel_types` |
| `power_bloc_panel_all_power_blocs` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_panel_members_tab` | `flowcontainer` | `power_bloc_panel_types` |
| `power_bloc_panel_overview_tab` | `flowcontainer` | `power_bloc_panel_types` |
| `power_blocs_cohesion_item` | `flowcontainer` | `power_bloc_panel_types` |
| `principle` | `widget` | `principle_selection` |
| `principle_group` | `widget` | `principle_selection` |
| `principle_icon` | `icon` | `power_bloc_panel_types` |
| `principle_icon_with_bg` | `icon` | `power_bloc_panel_types` |
| `principle_slot` | `container` | `power_bloc_panel_types` |
| `principle_slot_formation` | `container` | `power_bloc_panel_types` |
| `unlocked_new_principle_slot` | `widget` | `power_bloc_panel_types` |

## gui/production_methods.gui

| Type | Base | Group |
|---|---|---|
| `buildings_production_method_item` | `flowcontainer` | `production_methods` |
| `buildings_production_method_item_potential` | `flowcontainer` | `production_methods` |
| `construction_queue_sector_actions` | `hbox` | `production_methods` |
| `has_new_pm_icon` | `icon` | `production_methods` |
| `old_buildings_production_method_item` | `flowcontainer` | `production_methods` |
| `ship_construction_sector_actions` | `hbox` | `production_methods` |

## gui/religion_info_panel.gui

| Type | Base | Group |
|---|---|---|
| `poplist_filter_button` | `widget` | `religion_info_panel_types` |
| `religion_info_panel` | `default_block_window_two_lines` | `religion_info_panel_types` |

## gui/right_click_menu.gui

| Type | Base | Group |
|---|---|---|
| `active_charter_right_click_item` | `widget` | `company_charter_types` |
| `article_input_building_type_list` | `dynamicgridbox` | `article_input_types` |
| `article_input_company_list` | `dynamicgridbox` | `article_input_types` |
| `article_input_company_monopoly` | `flowcontainer` | `article_input_types` |
| `article_input_country_list` | `dynamicgridbox` | `article_input_types` |
| `article_input_goods_list` | `dynamicgridbox` | `article_input_types` |
| `article_input_law_group_list` | `flowcontainer` | `article_input_types` |
| `article_input_law_list` | `flowcontainer` | `article_input_types` |
| `article_input_select_money` | `container` | `article_input_types` |
| `article_input_select_text` | `container` | `article_input_types` |
| `article_input_ship_list` | `flowcontainer` | `article_input_types` |
| `article_input_state_list` | `dynamicgridbox` | `article_input_types` |
| `article_input_strategic_region_list` | `dynamicgridbox` | `article_input_types` |
| `article_market_goods_balance_number` | `hbox` | `article_input_types` |
| `article_market_goods_numbers` | `hbox` | `article_input_types` |
| `available_ship_template` | `right_click_menu_item` | `right_click_menu` |
| `binding_period_button` | `widget` | `treaty_binding_types` |
| `build_ship_type_flowcontainer` | `flowcontainer` | `right_click_menu` |
| `building_type_ownership_active_widget` | `widget` | `ownership_types` |
| `building_type_ownership_button` | `button` | `ownership_types` |
| `compact_ship_template_button` | `button` | `right_click_menu` |
| `country_right_click_menu_items` | `flowcontainer` | `country_right_click_menu` |
| `current_ship_template` | `widget` | `right_click_menu` |
| `diplomatic_action_grid_button` | `grid_button` | `right_click_menu` |
| `goods_interactions` | `flowcontainer` | `right_click_menu` |
| `grid_button` | `widget` | `right_click_menu` |
| `map_mode_right_click_menu_item` | `button` | `right_click_menu_types` |
| `map_mode_right_click_menu_item_selected` | `widget` | `right_click_menu_types` |
| `market_starvation_countries_filter_right_click_menu_item` | `button` | `right_click_menu_types` |
| `market_starvation_countries_filter_right_click_menu_item_selected` | `widget` | `right_click_menu_types` |
| `market_starvation_states_filter_right_click_menu_item` | `button` | `right_click_menu_types` |
| `market_starvation_states_filter_right_click_menu_item_selected` | `widget` | `right_click_menu_types` |
| `military_formation_marker_right_click_menu_item` | `right_click_menu_item` | `shared_formation_marker` |
| `military_formation_right_click_item` | `button` | `right_click_menu_types` |
| `military_formation_right_click_item_selected` | `widget` | `right_click_menu_types` |
| `naval_mission_right_click_item` | `flowcontainer` | `right_click_menu` |
| `negotiate_interest_group_active_widget` | `widget` | `right_click_menu` |
| `negotiate_interest_group_button` | `button` | `right_click_menu` |
| `privately_owned_filter_right_click_menu_item` | `button` | `right_click_menu_types` |
| `privately_owned_filter_right_click_menu_item_selected` | `widget` | `right_click_menu_types` |
| `right_click_commander_recruitment_item` | `right_click_menu_item` | `right_click_commander_items` |
| `right_click_menu` | `right_click_menu_widget` | `right_click_menu_types` |
| `right_click_menu_dropdown` | `flowcontainer` | `right_click_menu_types` |
| `right_click_menu_expandable_item` | `flowcontainer` | `right_click_menu_types` |
| `right_click_menu_item` | `button` | `right_click_menu_types` |
| `selected_company_and_building_type` | `container` | `article_input_types` |
| `selected_country` | `container` | `article_input_types` |
| `selected_goods_and_amount` | `widget` | `article_input_types` |
| `selected_goods_generic` | `container` | `article_input_types` |
| `selected_law` | `container` | `article_input_types` |
| `selected_ship` | `container` | `article_input_types` |
| `selected_state` | `container` | `article_input_types` |
| `selected_strategic_region` | `container` | `article_input_types` |
| `ship_building_menu_fixed_top` | `widget` | `right_click_menu` |
| `ship_header_and_acceptance_icon` | `widget` | `article_input_types` |
| `ship_template_number_and_name_hbox` | `hbox` | `right_click_menu` |
| `treaty_draft_input_acceptance_button_icon` | `button` | `article_input_types` |
| `treaty_draft_input_acceptance_icon` | `icon` | `article_input_types` |
| `warn_busy_fleet` | `icon` | `warn_types` |

## gui/sea_region_panel.gui

| Type | Base | Group |
|---|---|---|
| `country_shipping_lanes` | `vbox` | `sea_region_panel_types` |
| `military_formation_shipping_lane_button` | `button_icon_round` | `sea_region_panel_types` |
| `origin_state_port` | `vbox` | `sea_region_panel_types` |
| `sea_region_fleet_list_item` | `flowcontainer` | `sea_region_panel_types` |
| `sea_region_fleets_list` | `flowcontainer` | `sea_region_panel_types` |
| `sea_region_panel` | `default_block_window_vbox` | `sea_region_panel_types` |
| `sea_region_war_formation_list` | `flowcontainer` | `sea_region_panel_types` |
| `war_supply_network_info` | `flowcontainer` | `sea_region_panel_types` |
| `world_market_traded_goods_item` | `button` | `sea_region_panel_types` |

## gui/settings/setting_types.gui

| Type | Base | Group |
|---|---|---|
| `jomini_setting_bool` | `widget` | `Settings` |
| `jomini_setting_callback` | `widget` | `Settings` |
| `jomini_setting_desc` | `textbox` | `Settings` |
| `jomini_setting_enum` | `flowcontainer` | `Settings` |
| `jomini_setting_input_binding` | `container` | `Settings` |
| `jomini_setting_input_popup_window` | `default_popup` | `Settings` |
| `jomini_setting_string` | `margin_widget` | `Settings` |
| `jomini_setting_title` | `text_single` | `Settings` |
| `jomini_setting_value_scrollbar` | `container` | `Settings` |
| `jomini_settings_grouping` | `container` | `Settings` |
| `jomini_settings_restart_required_indicator` | `text_single` | `Settings` |
| `jomini_settings_window` | `window` | `Settings` |
| `setting_page_button` | `button_standard` | `Settings` |
| `setting_segmented_control_active_button` | `button` | `Settings` |
| `setting_segmented_control_button` | `button` | `Settings` |

## gui/shared/animations.gui

| Type | Base | Group |
|---|---|---|
| `checkmark_animation` | `widget` | `animation_assets` |
| `cogwheel_animation` | `container` | `animation_assets` |
| `cogwheel_animation_small` | `widget` | `animation_assets` |

## gui/shared/animations_special.gui

| Type | Base | Group |
|---|---|---|
| `lensbar_mobilized_animation` | `widget` | `animation_special` |

## gui/shared/backgrounds.gui

| Type | Base | Group |
|---|---|---|
| `default_header` | `default_header_properties` | `background_components` |
| `default_header_2texts` | `default_header_properties` | `background_components` |
| `default_header_2texts_clean` | `default_header_2texts` | `background_components` |
| `default_header_clean` | `default_header` | `background_components` |
| `default_header_clean_faded` | `default_header` | `background_components` |
| `default_header_hbox` | `default_header_properties` | `background_components` |
| `default_header_properties` | `widget` | `background_components` |
| `fullscreen_top_header` | `widget` | `background_components` |
| `popup_bg_frame` | `icon` | `background_components` |
| `popup_bg_frame_frontend` | `icon` | `background_components` |
| `popup_top_header` | `icon` | `background_components` |
| `top_illu` | `widget` | `background_components` |

## gui/shared/button_icons.gui

| Type | Base | Group |
|---|---|---|
| `back_button` | `button_icon_round` | `default_button_icons` |
| `back_button_large` | `back_button` | `default_button_icons` |
| `button_icon_cancel` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_check` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_edit` | `button_icon_round` | `default_button_icons` |
| `button_icon_location_finder` | `button_icon_round` | `default_button_icons` |
| `button_icon_menu` | `button_icon_round` | `default_button_icons` |
| `button_icon_minus` | `button_icon_round` | `default_button_icons` |
| `button_icon_minus_action` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_move_left` | `button_icon_square_action` | `default_button_icons` |
| `button_icon_move_right` | `button_icon_square_action` | `default_button_icons` |
| `button_icon_music_player` | `button_icon_round` | `default_button_icons` |
| `button_icon_next` | `button_icon_round` | `default_button_icons` |
| `button_icon_other` | `button_icon_round` | `default_button_icons` |
| `button_icon_pin` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_plus` | `button_icon_round` | `default_button_icons` |
| `button_icon_plus_action` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_plus_square` | `button_icon_square` | `default_button_icons` |
| `button_icon_random` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_reset` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_round_action` | `button_icon_round` | `default_button_icons` |
| `button_icon_round_big` | `button_icon_round` | `default_button_icons` |
| `button_icon_round_big_action` | `button_icon_round` | `default_button_icons` |
| `button_icon_round_big_map_interaction` | `button_icon_round` | `default_button_icons` |
| `button_icon_round_map_interaction` | `button_icon_round` | `default_button_icons` |
| `button_icon_round_toggle` | `button` | `default_button_icons` |
| `button_icon_round_toggle_action` | `button` | `default_button_icons` |
| `button_icon_settings` | `button_icon_round` | `default_button_icons` |
| `button_icon_square` | `button` | `default_button_icons` |
| `button_icon_square_action` | `button_icon_square` | `default_button_icons` |
| `button_icon_square_map_interaction` | `button_icon_square` | `default_button_icons` |
| `button_icon_toggle_pin` | `button_icon_round_toggle` | `default_button_icons` |
| `button_icon_unpin` | `button_icon_round_action` | `default_button_icons` |
| `button_icon_vickypedia` | `button_icon_round` | `default_button_icons` |
| `close_button` | `button_icon_round` | `default_button_icons` |
| `close_button_large` | `close_button` | `default_button_icons` |
| `minimize_button` | `button_icon_round` | `default_button_icons` |
| `minimize_button_large` | `minimize_button` | `default_button_icons` |
| `store_button` | `button_icon_round` | `default_button_icons` |

## gui/shared/buttons.gui

| Type | Base | Group |
|---|---|---|
| `section_header_button` | `button` | `default_buttons` |
| `section_header_right_text` | `textbox` | `default_buttons` |
| `sort_button` | `button` | `default_buttons` |
| `sort_button_with_textbox` | `button` | `default_buttons` |
| `tab_button` | `button` | `default_buttons` |

## gui/shared/character.gui

| Type | Base | Group |
|---|---|---|
| `add_character_button` | `button` | `character_types` |
| `add_character_button_long` | `button` | `character_types` |
| `character_icon` | `widget` | `character_types` |
| `character_ig_button` | `ig_button` | `character_types` |
| `character_ig_icon` | `ig_icon` | `character_types` |
| `character_portrait_base` | `widget` | `character_types` |
| `character_portrait_base_head` | `character_portrait_base` | `character_types` |
| `character_portrait_base_no_mask` | `widget` | `character_types` |
| `character_portrait_base_torso` | `character_portrait_base` | `character_types` |
| `character_portrait_base_torso_tsarpoint` | `character_portrait_base` | `character_types` |
| `character_portrait_duel_01` | `character_portrait_base` | `character_types` |
| `character_portrait_duel_02` | `character_portrait_base` | `character_types` |
| `character_portrait_frankenstein_situation_1char` | `character_portrait_base` | `character_types` |
| `character_portrait_front_vs_left` | `character_portrait_base_no_mask` | `character_types` |
| `character_portrait_front_vs_right` | `character_portrait_base_no_mask` | `character_types` |
| `character_portrait_large` | `character_portrait_base_head` | `character_types` |
| `character_portrait_large_torso` | `character_portrait_base_torso` | `character_types` |
| `character_portrait_large_torso_historical_info_link` | `character_portrait_large_torso` | `character_types` |
| `character_portrait_large_torso_historical_no_info_link` | `character_portrait_large_torso` | `character_types` |
| `character_portrait_large_torso_tsarpoint` | `character_portrait_base_torso` | `character_types` |
| `character_portrait_medium` | `character_portrait_base_head` | `character_types` |
| `character_portrait_medium_torso` | `character_portrait_base_torso` | `character_types` |
| `character_portrait_medium_torso_historical_info_link` | `character_portrait_medium_torso` | `character_types` |
| `character_portrait_medium_torso_historical_no_info_link` | `character_portrait_medium_torso` | `character_types` |
| `character_portrait_medium_torso_tsarpoint` | `character_portrait_base_torso` | `character_types` |
| `character_portrait_medium_torso_tsarpoint_historical_info_link` | `character_portrait_medium_torso_tsarpoint` | `character_types` |
| `character_portrait_medium_torso_tsarpoint_historical_no_info_link` | `character_portrait_medium_torso_tsarpoint` | `character_types` |
| `character_portrait_mini` | `character_portrait_base_head` | `character_types` |
| `character_portrait_situation_1char` | `character_portrait_base` | `character_types` |
| `character_portrait_small` | `character_portrait_base_head` | `character_types` |
| `character_portrait_small2` | `character_portrait_base_head` | `character_types` |
| `character_portrait_small_with_rank` | `character_portrait_base_head` | `character_types` |
| `character_portrait_xl_torso` | `character_portrait_base_torso` | `character_types` |
| `character_portrait_xl_torso_historical_info_link` | `character_portrait_xl_torso` | `character_types` |
| `character_portrait_xl_torso_historical_no_info_link` | `character_portrait_xl_torso` | `character_types` |
| `character_portrait_xl_torso_tsarpoint` | `character_portrait_base_torso_tsarpoint` | `character_types` |
| `character_portrait_xl_torso_tsarpoint_historical_info_link` | `character_portrait_xl_torso_tsarpoint` | `character_types` |
| `character_portrait_xl_torso_tsarpoint_historical_no_info_link` | `character_portrait_xl_torso_tsarpoint` | `character_types` |
| `pop_portrait_base` | `character_portrait_base` | `character_types` |
| `pop_portrait_big` | `pop_portrait_base` | `character_types` |
| `pop_portrait_big_female` | `pop_portrait_big` | `character_types` |
| `pop_portrait_big_male` | `pop_portrait_big` | `character_types` |
| `pop_portrait_medium` | `pop_portrait_base` | `character_types` |
| `pop_portrait_medium_female` | `pop_portrait_medium` | `character_types` |
| `pop_portrait_medium_male` | `pop_portrait_medium` | `character_types` |
| `pop_portrait_simple` | `pop_portrait_base` | `character_types` |
| `pop_portrait_simple_female` | `pop_portrait_simple` | `character_types` |
| `pop_portrait_simple_male` | `pop_portrait_simple` | `character_types` |
| `pop_portrait_small` | `pop_portrait_base` | `character_types` |
| `pop_portrait_small_female` | `pop_portrait_small` | `character_types` |
| `pop_portrait_small_male` | `pop_portrait_small` | `character_types` |

## gui/shared/defaults.gui

| Type | Base | Group |
|---|---|---|
| `button` | `button` | `Default` |
| `button_icon_goto` | `button_icon_round` | `Default` |
| `button_icon_properties` | `icon` | `Default` |
| `button_icon_round` | `button` | `Default` |
| `button_icon_zoom` | `button_icon_round` | `Default` |
| `checkbutton` | `checkbutton` | `Default` |
| `dropDown` | `dropDown` | `Default` |
| `minimap` | `minimap` | `Default` |
| `minimap_window` | `minimap_window` | `Default` |
| `piechart` | `piechart` | `Default` |
| `pieslice` | `pieslice` | `Default` |
| `progresspie` | `progressbar` | `Default` |
| `scrollbar` | `scrollbar` | `Default` |
| `treemapslice` | `treemapslice` | `Default` |

## gui/shared/dividers.gui

| Type | Base | Group |
|---|---|---|
| `box_vertical_divider` | `vertical_divider` | `dividers` |
| `divider_dark_decorative` | `widget` | `dividers` |
| `divider_decorative` | `widget` | `dividers` |
| `divider_gold` | `icon` | `dividers` |
| `divider_stronger_full` | `widget` | `dividers` |
| `vertical_divider` | `widget` | `dividers` |
| `vertical_divider_dark_stronger_full` | `widget` | `dividers` |
| `vertical_divider_fade_bottom` | `widget` | `dividers` |
| `vertical_divider_full` | `widget` | `dividers` |
| `vertical_divider_navy_frame` | `widget` | `dividers` |
| `vertical_divider_stronger_full` | `widget` | `dividers` |
| `vertical_divider_strongest_full` | `widget` | `dividers` |

## gui/shared/flags.gui

| Type | Base | Group |
|---|---|---|
| `fancy_flag` | `widget` | `flags` |
| `fancy_flag_ui` | `widget` | `flags` |
| `flag` | `widget` | `flags` |
| `flag_3d` | `icon` | `flags` |
| `flag_3d_animated` | `icon` | `flags` |
| `flag_3d_faded_animated` | `icon` | `flags` |
| `flag_icon` | `icon` | `flags` |
| `is_player_glow` | `icon` | `flags` |
| `large_flag` | `widget` | `flags` |
| `miniature_flag` | `widget` | `flags` |
| `miniature_flag_no_interact` | `widget` | `flags` |
| `mobilization_icon_flag` | `mobilization_icon` | `flags` |
| `observer_mode_overlay` | `widget` | `flags` |
| `power_bloc_icon` | `icon` | `flags` |
| `power_bloc_icon_large` | `icon` | `flags` |
| `power_bloc_icon_small` | `icon` | `flags` |
| `power_bloc_rank_badge` | `widget` | `flags` |
| `rank_badge` | `widget` | `flags` |
| `save_game_item_coa` | `icon` | `flags` |
| `small_flag` | `widget` | `flags` |
| `small_flag_no_interact` | `widget` | `flags` |
| `tiny_flag` | `widget` | `flags` |
| `tiny_flag_no_interact` | `widget` | `flags` |

## gui/shared/layout.gui

| Type | Base | Group |
|---|---|---|
| `expanded_list` | `flowcontainer` | `layout_types` |

## gui/shared/progressbars.gui

| Type | Base | Group |
|---|---|---|
| `animated_progresspie` | `progressbar` | `progressbars` |
| `bad_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `bar_horizontal` | `widget` | `progressbars` |
| `bar_horizontal_with_background` | `widget` | `progressbars` |
| `battle_progressbar` | `progressbar_properties` | `progressbars` |
| `changed_value_decreased_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `changed_value_decreased_progressbar_horizontal_green` | `progressbar_properties` | `progressbars` |
| `changed_value_increased_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `changed_value_increased_progressbar_horizontal_bad` | `progressbar_properties` | `progressbars` |
| `default_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `double_direction_progressbar` | `widget` | `progressbars` |
| `double_direction_progressbar_gold` | `widget` | `progressbars` |
| `gold_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `green_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `levels_progressbar` | `hbox` | `progressbars` |
| `progressbar_highlight` | `widget` | `progressbars` |
| `progressbar_properties` | `widget` | `progressbars` |
| `round_progress_bad` | `animated_progresspie` | `progressbars` |
| `round_progress_default` | `animated_progresspie` | `progressbars` |
| `scripted_progressbar_dynamic` | `progressbar_properties` | `progressbars` |
| `white_progressbar_horizontal` | `progressbar_properties` | `progressbars` |
| `white_progressbar_vertical` | `progressbar_properties` | `progressbars` |

## gui/shared/search_bar.gui

| Type | Base | Group |
|---|---|---|
| `search_bar` | `widget` | `SearchBarTypes` |
| `search_bar_results` | `scrollarea` | `SearchBarTypes` |

## gui/shared/tab_bars.gui

| Type | Base | Group |
|---|---|---|
| `tab_buttons` | `hbox` | `tab_bars` |
| `tab_buttons_fullscreen` | `tab_buttons` | `tab_bars` |
| `tab_buttons_icon_only` | `flowcontainer` | `tab_bars` |

## gui/ship_designer_popup.gui

| Type | Base | Group |
|---|---|---|
| `modification_slot` | `widget` | `ship_designer_popup_types` |
| `ship_designer_bars_flowcontainer` | `flowcontainer` | `ship_designer_popup_types` |
| `ship_designer_grid_stat` | `widget` | `ship_designer_popup_types` |
| `ship_designer_popup_type` | `default_popup_two_lines` | `ship_designer_popup_types` |
| `ship_designer_stats_list_flowcontainer` | `flowcontainer` | `ship_designer_popup_types` |
| `utility_modification_slot_button` | `button` | `ship_designer_popup_types` |

## gui/ship_panel.gui

| Type | Base | Group |
|---|---|---|
| `ship_change_name_popup_type` | `default_popup` | `ship_change_name` |
| `ship_modifier_accuracy_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_destroyer_accuracy` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_dreadnought_hull_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_modern_ironclad_hull_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_pre_dreadnought_hull_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_submarine_accuracy` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_super_dreadnought_hull_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_torpedo_boat_accuracy` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_against_torpedo_boat_destroyer_accuracy` | `ship_stat` | `ship_types` |
| `ship_modifier_battle_condition_accuracy_penalty` | `ship_stat` | `ship_types` |
| `ship_modifier_blockade_strength_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_crew_damage_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_critical_hit_chance_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_detection_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_hull_damage_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_naval_invasion_efficiency` | `ship_stat` | `ship_types` |
| `ship_modifier_readiness_gain_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_screening_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_stat_accuracy` | `ship_stat_base_accuracy` | `ship_types` |
| `ship_modifier_stat_armor` | `ship_stat_base_armor` | `ship_types` |
| `ship_modifier_stat_blockade_strength` | `ship_stat_base_blockade_strength` | `ship_types` |
| `ship_modifier_stat_carrying_capacity` | `ship_stat_base_carrying_capacity` | `ship_types` |
| `ship_modifier_stat_crew_damage` | `ship_stat_base_crew_damage` | `ship_types` |
| `ship_modifier_stat_crew_max` | `ship_stat_base_crew_max` | `ship_types` |
| `ship_modifier_stat_critical_hit_chance` | `ship_stat_base_critical_hit_chance` | `ship_types` |
| `ship_modifier_stat_critical_hit_damage` | `ship_stat_base_critical_hit_multiplier` | `ship_types` |
| `ship_modifier_stat_detection` | `ship_stat_base_detection` | `ship_types` |
| `ship_modifier_stat_hit_points` | `ship_stat_base_hit_points` | `ship_types` |
| `ship_modifier_stat_hull_damage` | `ship_stat_base_hull_damage` | `ship_types` |
| `ship_modifier_stat_marine_capacity` | `ship_stat_base_marine_capacity` | `ship_types` |
| `ship_modifier_stat_movement_speed` | `ship_stat_base_movement_speed` | `ship_types` |
| `ship_modifier_stat_power_projection` | `ship_stat_base_power_projection` | `ship_types` |
| `ship_modifier_stat_readiness_gain` | `ship_stat_base_readiness_gain` | `ship_types` |
| `ship_modifier_stat_screening` | `ship_stat_base_screening` | `ship_types` |
| `ship_modifier_stat_supply_capacity` | `ship_stat_base_supply_capacity` | `ship_types` |
| `ship_modifier_stat_supply_efficiency` | `ship_stat_base_supply_efficiency` | `ship_types` |
| `ship_modifier_stat_visibility` | `ship_stat_base_visibility` | `ship_types` |
| `ship_modifier_stat_vulnerability` | `ship_stat_base_vulnerability` | `ship_types` |
| `ship_modifier_suffered_accuracy` | `ship_stat` | `ship_types` |
| `ship_modifier_suffered_crew_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_suffered_crit_chance` | `ship_stat` | `ship_types` |
| `ship_modifier_suffered_crit_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_suffered_hull_damage` | `ship_stat` | `ship_types` |
| `ship_modifier_visibility_mult` | `ship_stat` | `ship_types` |
| `ship_modifier_vulnerability_mult` | `ship_stat` | `ship_types` |
| `ship_panel` | `default_block_window_two_lines` | `ship_panel_types` |
| `ship_stat` | `widget` | `ship_types` |
| `ship_stat_accuracy` | `ship_stat_base_accuracy` | `ship_types` |
| `ship_stat_armor` | `ship_stat_base_armor` | `ship_types` |
| `ship_stat_base_accuracy` | `ship_stat` | `ship_types` |
| `ship_stat_base_armor` | `ship_stat` | `ship_types` |
| `ship_stat_base_blockade_strength` | `ship_stat` | `ship_types` |
| `ship_stat_base_carrying_capacity` | `ship_stat` | `ship_types` |
| `ship_stat_base_crew_damage` | `ship_stat` | `ship_types` |
| `ship_stat_base_crew_max` | `ship_stat` | `ship_types` |
| `ship_stat_base_critical_hit_chance` | `ship_stat` | `ship_types` |
| `ship_stat_base_critical_hit_multiplier` | `ship_stat` | `ship_types` |
| `ship_stat_base_detection` | `ship_stat` | `ship_types` |
| `ship_stat_base_hit_points` | `ship_stat` | `ship_types` |
| `ship_stat_base_hit_points_max` | `ship_stat` | `ship_types` |
| `ship_stat_base_hull_damage` | `ship_stat` | `ship_types` |
| `ship_stat_base_marine_capacity` | `ship_stat` | `ship_types` |
| `ship_stat_base_movement_speed` | `ship_stat` | `ship_types` |
| `ship_stat_base_power_projection` | `ship_stat` | `ship_types` |
| `ship_stat_base_readiness_gain` | `ship_stat` | `ship_types` |
| `ship_stat_base_screening` | `ship_stat` | `ship_types` |
| `ship_stat_base_supply_capacity` | `ship_stat` | `ship_types` |
| `ship_stat_base_supply_efficiency` | `ship_stat` | `ship_types` |
| `ship_stat_base_upkeep` | `ship_stat` | `ship_types` |
| `ship_stat_base_veterancy` | `ship_stat` | `ship_types` |
| `ship_stat_base_visibility` | `ship_stat` | `ship_types` |
| `ship_stat_base_vulnerability` | `ship_stat` | `ship_types` |
| `ship_stat_blockade_strength` | `ship_stat_base_blockade_strength` | `ship_types` |
| `ship_stat_carrying_capacity` | `ship_stat_base_carrying_capacity` | `ship_types` |
| `ship_stat_crew_damage` | `ship_stat_base_crew_damage` | `ship_types` |
| `ship_stat_crew_max` | `ship_stat_base_crew_max` | `ship_types` |
| `ship_stat_critical_hit_chance` | `ship_stat_base_critical_hit_chance` | `ship_types` |
| `ship_stat_critical_hit_multiplier` | `ship_stat_base_critical_hit_multiplier` | `ship_types` |
| `ship_stat_detection` | `ship_stat_base_detection` | `ship_types` |
| `ship_stat_hit_points_max` | `ship_stat_base_hit_points_max` | `ship_types` |
| `ship_stat_hull_damage` | `ship_stat_base_hull_damage` | `ship_types` |
| `ship_stat_marine_capacity` | `ship_stat_base_marine_capacity` | `ship_types` |
| `ship_stat_movement_speed` | `ship_stat_base_movement_speed` | `ship_types` |
| `ship_stat_power_projection` | `ship_stat_base_power_projection` | `ship_types` |
| `ship_stat_readiness_gain` | `ship_stat_base_readiness_gain` | `ship_types` |
| `ship_stat_screening` | `ship_stat_base_screening` | `ship_types` |
| `ship_stat_supply_capacity` | `ship_stat_base_supply_capacity` | `ship_types` |
| `ship_stat_supply_efficiency` | `ship_stat_base_supply_efficiency` | `ship_types` |
| `ship_stat_upkeep` | `ship_stat_base_upkeep` | `ship_types` |
| `ship_stat_veterancy` | `ship_stat_base_veterancy` | `ship_types` |
| `ship_stat_visibility` | `ship_stat_base_visibility` | `ship_types` |
| `ship_stat_vulnerability` | `ship_stat_base_vulnerability` | `ship_types` |
| `ship_template_stat_accuracy` | `ship_stat_base_accuracy` | `ship_types` |
| `ship_template_stat_armor` | `ship_stat_base_armor` | `ship_types` |
| `ship_template_stat_blockade_strength` | `ship_stat_base_blockade_strength` | `ship_types` |
| `ship_template_stat_carrying_capacity` | `ship_stat_base_carrying_capacity` | `ship_types` |
| `ship_template_stat_crew_damage` | `ship_stat_base_crew_damage` | `ship_types` |
| `ship_template_stat_crew_max` | `ship_stat_base_crew_max` | `ship_types` |
| `ship_template_stat_critical_hit_chance` | `ship_stat_base_critical_hit_chance` | `ship_types` |
| `ship_template_stat_critical_hit_damage` | `ship_stat_base_critical_hit_multiplier` | `ship_types` |
| `ship_template_stat_detection` | `ship_stat_base_detection` | `ship_types` |
| `ship_template_stat_hit_points` | `ship_stat_base_hit_points` | `ship_types` |
| `ship_template_stat_hull_damage` | `ship_stat_base_hull_damage` | `ship_types` |
| `ship_template_stat_marine_capacity` | `ship_stat_base_marine_capacity` | `ship_types` |
| `ship_template_stat_movement_speed` | `ship_stat_base_movement_speed` | `ship_types` |
| `ship_template_stat_power_projection` | `ship_stat_base_power_projection` | `ship_types` |
| `ship_template_stat_readiness_gain` | `ship_stat_base_readiness_gain` | `ship_types` |
| `ship_template_stat_screening` | `ship_stat_base_screening` | `ship_types` |
| `ship_template_stat_supply_capacity` | `ship_stat_base_supply_capacity` | `ship_types` |
| `ship_template_stat_supply_efficiency` | `ship_stat_base_supply_efficiency` | `ship_types` |
| `ship_template_stat_visibility` | `ship_stat_base_visibility` | `ship_types` |
| `ship_template_stat_vulnerability` | `ship_stat_base_vulnerability` | `ship_types` |
| `ship_viewer` | `icon` | `ship_viewer_types` |

## gui/state_population_panel.gui

| Type | Base | Group |
|---|---|---|
| `state_culture_piechart` | `chart` | `state_pops_panel` |
| `state_ig_piechart` | `chart` | `state_pops_panel` |
| `state_pop_type_piechart` | `chart` | `state_pops_panel` |
| `state_population_panel` | `default_block_window_two_lines` | `state_pops_panel` |
| `state_religion_piechart` | `chart` | `state_pops_panel` |

## gui/states_panel.gui

| Type | Base | Group |
|---|---|---|
| `building_item` | `widget` | `building_item_types` |
| `building_item_button` | `button` | `building_item_types` |
| `building_item_condensed` | `button` | `building_item_types` |
| `employment_indicator_icon` | `container` | `building_item_types` |
| `header_building_item` | `widget` | `building_item_types` |
| `politics_entry` | `widget` | `information_panels_types` |
| `pop_portraits_datamodel` | `flowcontainer` | `state_panel_types` |
| `state_change_name_popup_type` | `default_popup` | `state_panel_types` |
| `state_panel_button` | `button` | `information_panels_types` |
| `state_panel_button_unclickable` | `widget` | `information_panels_types` |
| `state_panel_condensed` | `flowcontainer` | `state_panel_types` |
| `state_panel_overview_content` | `flowcontainer` | `state_panel_types` |
| `state_panel_population_content` | `flowcontainer` | `state_panel_types` |
| `state_panel_status_item` | `flowcontainer` | `state_panel_types` |
| `state_panel_status_item_condensed` | `container` | `state_panel_types` |
| `state_panel_status_item_condensed_icon` | `icon` | `state_panel_types` |
| `state_panel_status_item_list` | `flowcontainer` | `state_panel_types` |
| `state_panel_status_item_small` | `container` | `state_panel_types` |
| `states_panel` | `default_block_window_two_lines` | `state_panel_types` |
| `toggle_condensed` | `widget` | `information_panels_types` |

## gui/states_panel_buildings.gui

| Type | Base | Group |
|---|---|---|
| `buildings_list` | `flowcontainer` | `state_buildings` |
| `buildings_list_item` | `flowcontainer` | `state_buildings` |
| `state_panel_buildings_content` | `flowcontainer` | `state_panel_types` |
| `state_panel_buildings_fixed_bottom` | `flowcontainer` | `state_panel_types` |

## gui/states_panel_modifiers.gui

| Type | Base | Group |
|---|---|---|
| `state_panel_modifiers_content` | `flowcontainer` | `state_panel_types` |

## gui/strait_panel.gui

| Type | Base | Group |
|---|---|---|
| `building_controls` | `container` | `strait_panel_types` |
| `setting_bar_item` | `widget` | `strait_panel_types` |
| `strait_access_controller` | `flowcontainer` | `strait_panel_types` |
| `strait_allowed_countries_controller` | `flowcontainer` | `strait_panel_types` |
| `strait_panel` | `default_block_window_two_lines` | `strait_panel_types` |
| `strait_state_and_fortification` | `flowcontainer` | `strait_panel_types` |
| `strait_state_info` | `flowcontainer` | `strait_panel_types` |
| `strait_state_info_item` | `widget` | `strait_panel_types` |
| `strait_traded_goods_item` | `button` | `strait_panel_types` |
| `toll_rate_controller` | `flowcontainer` | `strait_panel_types` |

## gui/strategic_region_panel.gui

| Type | Base | Group |
|---|---|---|
| `country_interest_item` | `container` | `strategic_region_panel_types` |
| `country_interest_item_compact` | `widget` | `strategic_region_panel_types` |
| `country_involvement_bar_with_label` | `hbox` | `strategic_region_panel_types` |
| `country_strategic_region_locality_bar` | `flowcontainer` | `strategic_region_panel_types` |
| `country_strategic_region_state_item` | `button` | `strategic_region_panel_types` |
| `country_with_strategic_region_locality_item` | `flowcontainer` | `strategic_region_panel_types` |
| `strategic_region_countries_item` | `flowcontainer` | `strategic_region_panel_types` |
| `strategic_region_countries_locality_bar` | `flowcontainer` | `strategic_region_panel_types` |
| `strategic_region_non_local_countries_item` | `flowcontainer` | `strategic_region_panel_types` |
| `strategic_region_panel` | `default_block_window_two_lines` | `strategic_region_panel_types` |

## gui/sway_country_panel.gui

| Type | Base | Group |
|---|---|---|
| `direct_support_button` | `button` | `sway_country_types` |
| `sway_country_panel` | `default_block_window` | `sway_country_types` |
| `sway_offer_item` | `button` | `sway_country_types` |
| `sway_offer_type_item` | `button` | `sway_country_types` |
| `sway_offer_wargoal_type_item` | `button` | `sway_country_types` |

## gui/switch_production_method_menu.gui

| Type | Base | Group |
|---|---|---|
| `production_methods_right_click_menu_item` | `container` | `production_methods_right_click` |

## gui/table_tooltips.gui

| Type | Base | Group |
|---|---|---|
| `TableTooltip_MarketGoodsOrders` | `RegularTooltip` | `table_tooltips` |
| `TableTooltip_StateGovernmentExpenses` | `RegularTooltip` | `table_tooltips` |
| `TableTooltip_StateTaxationRevenue` | `RegularTooltip` | `table_tooltips` |

## gui/tech_tree.gui

| Type | Base | Group |
|---|---|---|
| `queued_technology` | `widget` | `tech_tree` |
| `tech_tree_graph` | `zoomarea` | `tech_tree` |
| `tech_tree_panel` | `fullscreen_block_window` | `tech_tree` |
| `technology` | `widget` | `tech_tree` |
| `techtree_spline` | `container` | `tech_tree` |

## gui/theme_selector_window.gui

| Type | Base | Group |
|---|---|---|
| `asset_category` | `vbox` | `theme_selector` |
| `forced_season_radio` | `flowcontainer` | `theme_selector` |
| `relevant_dlc` | `widget` | `theme_selector` |
| `seasons_tab_content` | `flowcontainer` | `theme_selector` |
| `settings_tab_content` | `flowcontainer` | `theme_selector` |
| `theme_category` | `widget` | `theme_selector` |
| `theme_selector_asset` | `hbox` | `theme_selector` |
| `theme_tab_content` | `vbox` | `theme_selector` |

## gui/ticktask_debugger.gui

| Type | Base | Group |
|---|---|---|
| `ticktask_button` | `editor_button` | `ticktask_debugger` |
| `ticktask_graph` | `zoomarea` | `ticktask_debugger` |
| `ticktask_list_numberbox` | `ticktask_list_textbox` | `ticktask_debugger` |
| `ticktask_list_scrollbar_spacing` | `widget` | `ticktask_debugger` |
| `ticktask_list_textbox` | `textbox` | `ticktask_debugger` |
| `ticktask_list_widget` | `widget` | `ticktask_debugger` |

## gui/timemanip.gui

| Type | Base | Group |
|---|---|---|
| `mini_construction_queue` | `widget` | `construction_in_outliner` |
| `pause_border` | `widget` | `timekeeper` |
| `tick_of_day_icon` | `widget` | `timekeeper` |
| `time_animation` | `icon` | `timekeeper` |
| `timemanip` | `container` | `timekeeper` |

## gui/tooltip.gui

| Type | Base | Group |
|---|---|---|
| `DefaultTooltipTextBox` | `textbox` | `TooltipTypes` |
| `FancyTooltipGlossaryWidgetType` | `container` | `TooltipTypes` |
| `FancyTooltipWidgetType` | `container` | `TooltipTypes` |
| `RegularTooltip` | `TooltipWidgetType` | `TooltipTypes` |
| `TooltipWidgetType` | `container` | `TooltipTypes` |
| `caligula_table` | `margin_widget` | `Tables` |
| `divider_clean` | `icon` | `dividers` |
| `tooltip_lock_action_tab` | `container` | `TooltipTypes` |

## gui/topbar.gui

| Type | Base | Group |
|---|---|---|
| `topbar` | `widget` | `topbar_components` |
| `topbar_rank` | `button` | `topbar_components` |
| `topbar_secondary_icons` | `container` | `topbar_components` |

## gui/topfrontend.gui

| Type | Base | Group |
|---|---|---|
| `alert_icon` | `icon` | `topfrontend_types` |
| `current_situation_button` | `button` | `topfrontend_types` |
| `topfrontend` | `widget` | `topfrontend_types` |

## gui/transfer_formation.gui

| Type | Base | Group |
|---|---|---|
| `expected_formation_size` | `widget` | `transfer_formation_types` |
| `new_army_button` | `flowcontainer` | `transfer_formation_types` |
| `new_fleet_button` | `flowcontainer` | `transfer_formation_types` |
| `quick_select_menu` | `flowcontainer` | `transfer_formation_types` |
| `ship_type_selection_with_arrow_button` | `flowcontainer` | `transfer_formation_types` |
| `small_combat_unit_with_checkbox` | `margin_widget` | `transfer_formation_types` |
| `small_ship_with_checkbox` | `margin_widget` | `transfer_formation_types` |
| `transfer_unit_filters` | `flowcontainer` | `transfer_formation_types` |
| `unit_type_selection_with_arrow_button` | `flowcontainer` | `transfer_formation_types` |

## gui/treaty_draft_panel.gui

| Type | Base | Group |
|---|---|---|
| `additional_input_article_button` | `widget` | `treaty_draft_panel_types` |
| `article_draft` | `vbox` | `treaty_draft_panel_types` |
| `article_draft_influence_cost` | `article_influence_cost` | `treaty_draft_panel_types` |
| `available_options_number` | `textbox` | `treaty_draft_panel_types` |
| `left_section_scrollarea` | `scrollarea` | `treaty_draft_panel_types` |
| `middle_section_fullscreen_scrollarea` | `scrollarea` | `treaty_draft_panel_types` |
| `right_section_scrollarea` | `scrollarea` | `treaty_draft_panel_types` |
| `seal_and_signature` | `widget` | `treaty_draft_panel_types` |
| `seal_and_signature_unsigned` | `widget` | `treaty_draft_panel_types` |
| `ship_transfer_bundle_draft` | `vbox` | `treaty_draft_panel_types` |
| `side_section_articles` | `vbox` | `treaty_draft_panel_types` |
| `simple_article_button` | `widget` | `treaty_draft_panel_types` |
| `treaty_draft_acceptance_icon` | `container` | `treaty_draft_panel_types` |
| `treaty_draft_character` | `widget` | `treaty_draft_panel_types` |
| `treaty_draft_panel` | `treaty_fullscreen_block_window` | `treaty_draft_panel_types` |
| `treaty_draft_right_character` | `widget` | `treaty_draft_panel_types` |
| `treaty_fullscreen_block_window` | `widget` | `treaty_draft_panel_types` |
| `treaty_textbox` | `textbox` | `treaty_draft_panel_types` |
| `treaty_textbox_red` | `textbox` | `treaty_draft_panel_types` |

## gui/treaty_panel.gui

| Type | Base | Group |
|---|---|---|
| `article` | `vbox` | `treaty_panel_types` |
| `article_influence_cost` | `hbox` | `treaty_panel_types` |
| `company_monopoly_article` | `flowcontainer` | `treaty_panel_types` |
| `country_input_article` | `widget` | `treaty_panel_types` |
| `goods_input_article` | `widget` | `treaty_panel_types` |
| `goods_transfer_article` | `widget` | `treaty_panel_types` |
| `law_commitment_article` | `widget` | `treaty_panel_types` |
| `money_transfer_article` | `widget` | `treaty_panel_types` |
| `ship_input_article` | `widget` | `treaty_panel_types` |
| `ship_transfer_bundle` | `vbox` | `treaty_panel_types` |
| `state_input_article` | `widget` | `treaty_panel_types` |
| `strategic_region_input_article` | `widget` | `treaty_panel_types` |
| `text_input_article` | `widget` | `treaty_panel_types` |
| `total_influence_cost` | `hbox` | `treaty_panel_types` |
| `treaty` | `vbox` | `treaty_panel_types` |
| `treaty_panel` | `default_block_window_two_lines` | `treaty_panel_types` |

## gui/tutorial_highlight.gui

| Type | Base | Group |
|---|---|---|
| `highlight_tutorial` | `widget` | `highlights` |
| `highlight_tutorial_ui` | `widget` | `highlights` |

## gui/tutorial_popup.gui

| Type | Base | Group |
|---|---|---|
| `show_more_button` | `button` | `tutorials` |
| `show_more_content` | `flowcontainer` | `tutorials` |
| `tutorial_diagram` | `widget` | `tutorials` |
| `tutorial_image_and_text` | `container` | `tutorials` |
| `tutorial_popup` | `window` | `tutorials` |

## gui/war_panel.gui

| Type | Base | Group |
|---|---|---|
| `front_list_item` | `container` | `war_panel` |
| `peace_deal_war_goals_list` | `dynamicgridbox` | `war_panel` |
| `war_panel` | `default_block_window_two_lines` | `war_panel` |
| `war_participant_item` | `container` | `war_panel` |
| `war_participant_side` | `flowcontainer` | `war_panel` |
| `war_present_countries_side` | `flowcontainer` | `war_panel` |

## gui/window_component_library.gui

| Type | Base | Group |
|---|---|---|
| `debug_square` | `icon` | `ComponentLibrary` |
| `debug_text` | `textbox` | `ComponentLibrary` |
| `ui_guide_component_area` | `vbox` | `ComponentLibrary` |
| `ui_guide_component_top_info` | `hbox` | `ComponentLibrary` |
| `ui_guide_title_and_info` | `vbox` | `ComponentLibrary` |

## gui/world_market_panel.gui

| Type | Base | Group |
|---|---|---|
| `market_flag` | `small_flag` | `world_market_panel` |
| `small_goods_button` | `button` | `world_market_panel` |
| `small_market_flag` | `widget` | `world_market_panel` |
| `world_market_goods_entry_button` | `flowcontainer` | `world_market_panel` |
| `world_market_goods_filter_button` | `button_icon_round_big` | `world_market_panel` |
| `world_market_goods_filters` | `flowcontainer` | `world_market_panel` |
| `world_market_panel` | `default_block_window` | `world_market_panel` |
| `world_market_panel_details_content` | `container` | `world_market_panel` |
