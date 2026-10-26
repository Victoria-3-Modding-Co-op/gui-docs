# Templates

**690 templates** are declared with `template NAME { ... }` and pulled into a widget with `using = NAME`. A template is a bag of entries, not a type: it cannot be instantiated as a child and it cannot be inherited from.

## Index

| Template | File | Entries |
|---|---|---|
| `12_frames_animation` | gui/shared/animations_frame_by_frame.gui | state |
| `13_frames_animation` | gui/shared/animations_frame_by_frame.gui | state |
| `14_frames_animation` | gui/shared/animations_frame_by_frame.gui | state |
| `16_frames_animation` | gui/shared/animations_frame_by_frame.gui | state |
| `24_frames_animation` | gui/shared/animations_frame_by_frame.gui | state |
| `32_frames_animation` | gui/shared/animations_frame_by_frame.gui | state |
| `Animation_Character_Panel_Refresh` | gui/character_panel.gui | state |
| `Animation_Character_Panel_Refresh_Short` | gui/character_panel.gui | state |
| `Animation_Curve_Default` | gui/shared/animation_curves.gui | bezier |
| `Animation_Curve_EaseIn` | gui/shared/animation_curves.gui | bezier |
| `Animation_Curve_EaseOut` | gui/shared/animation_curves.gui | bezier |
| `Animation_Curve_FastSlow` | gui/shared/animation_curves.gui | bezier |
| `Animation_FadeIn_Quick` | gui/frontend/shared/animation.gui | using, duration, alpha |
| `Animation_FadeIn_Standard` | gui/frontend/shared/animation.gui | using, duration, alpha |
| `Animation_FadeOut_Quick` | gui/frontend/shared/animation.gui | using, duration, alpha |
| `Animation_FadeOut_Standard` | gui/frontend/shared/animation.gui | using, duration, alpha |
| `Animation_LoadingScreen_ShowHide` | gui/frontend/frontend_loadingscreen.gui | alpha, state |
| `Animation_Refresh_FadeIn` | gui/shared/animations.gui | name, alpha, duration, bezier |
| `Animation_Refresh_FadeOut` | gui/shared/animations.gui | alpha, next, using |
| `Animation_ShowHide_Quick` | gui/frontend/shared/animation.gui | state |
| `Animation_ShowHide_Standard` | gui/frontend/shared/animation.gui | state |
| `Animation_Tab_Switch` | gui/frontend/shared/animation.gui | state |
| `Animation_Transition_End` | gui/frontend/shared/animation.gui | bezier |
| `Animation_Transition_Start` | gui/frontend/shared/animation.gui | bezier |
| `Background_Area` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Area_Border` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Area_Border_Solid` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Area_Dark` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Area_Solid` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Area_With_Header` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Bottom_Fade` | gui/frontend/shared/backgrounds.gui | texture, color, alpha |
| `Background_DropDown` | gui/frontend/shared/backgrounds.gui | background |
| `Background_Frame` | gui/frontend/shared/backgrounds.gui | using |
| `Background_Full_Dim` | gui/frontend/shared/backgrounds.gui | background |
| `Color_Black` | gui/frontend/shared/colors.gui | color |
| `Color_Blue` | gui/frontend/shared/colors.gui | color |
| `Color_Blue_Transparent` | gui/frontend/shared/colors.gui | color |
| `Color_Bright_Yellow` | gui/frontend/shared/colors.gui | color |
| `Color_Bright_Yellow_Transparent` | gui/frontend/shared/colors.gui | color |
| `Color_Button_Background` | gui/frontend/shared/colors.gui | color |
| `Color_Green` | gui/frontend/shared/colors.gui | color |
| `Color_Green_Transparent` | gui/frontend/shared/colors.gui | color |
| `Color_Grey` | gui/frontend/shared/colors.gui | color |
| `Color_Orange` | gui/frontend/shared/colors.gui | color |
| `Color_Purple` | gui/frontend/shared/colors.gui | color |
| `Color_Red` | gui/frontend/shared/colors.gui | color |
| `Color_Red_Transparent` | gui/frontend/shared/colors.gui | color |
| `ConsoleBackground` | gui/console.gui | using, texture, spriteType, spriteborder, texture_density, modify_texture |
| `ConsoleEditbg` | gui/console.gui | spriteType, spriteborder, shaderfile, texture, texture_density |
| `Font_Size_Big` | gui/frontend/shared/fonts.gui | using, size |
| `Font_Size_Medium` | gui/frontend/shared/fonts.gui | using, size |
| `Font_Size_Small` | gui/frontend/shared/fonts.gui | size |
| `Font_Type_Flavor` | gui/frontend/shared/fonts.gui |  |
| `Font_Type_Script` | gui/frontend/shared/fonts.gui |  |
| `Font_Type_Standard` | gui/frontend/shared/fonts.gui |  |
| `GDP_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `Icon_Button_Frames_Grey` | gui/frontend/shared/buttons_icons.gui | upframe, uphoverframe, uppressedframe, downframe, downhoverframe, downpressedframe, disableframe |
| `JominiDefaultButtonProperties` | gui/multiplayer_types.gui |  |
| `JominiLobbyViewModuleBackground` | gui/multiplayer_types.gui |  |
| `Master_Button_Modify_Texture` | gui/frontend/shared/buttons_icons.gui | modify_texture |
| `SDKButtonStyle` | gui/pdx_account/base_types.gui |  |
| `SDKButtonTextStyle` | gui/pdx_account/base_types.gui |  |
| `SDKDropdownButtonStyle` | gui/pdx_account/base_types.gui |  |
| `SDKErrorTextStyle` | gui/pdx_account/base_types.gui |  |
| `SDKTextStyle` | gui/pdx_account/base_types.gui | using, align, default_format |
| `Scrollbar_Horizontal` | gui/frontend/shared/lists.gui | using |
| `Scrollbar_Vertical` | gui/frontend/shared/lists.gui | using |
| `Scrollbox_Margins` | gui/frontend/shared/windows.gui | margin_top, margin_bottom, margin_left, margin_right |
| `SettingsButtonStyle` | gui/settings/setting_types.gui |  |
| `SettingsValueDecButton` | gui/settings/setting_types.gui |  |
| `SettingsValueIncButton` | gui/settings/setting_types.gui |  |
| `SettingsValueSlider` | gui/settings/setting_types.gui |  |
| `SettingsValueTrack` | gui/settings/setting_types.gui |  |
| `Snapshot_Low_Pass_World` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_Mx_100` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_Mx_80` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_Veh_100` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_Vfx_War_100` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_World_100` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_World_100_Mx_100` | gui/shared/sounds.gui | sstart_sound, start_sound |
| `Snapshot_Mute_World_100_Mx_80` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_World_80` | gui/shared/sounds.gui | start_sound |
| `Snapshot_Mute_World_80_Mx_80` | gui/shared/sounds.gui | start_sound |
| `Sound_Default` | gui/shared/sounds.gui |  |
| `Sound_Kill_Siege_SFX` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowHide_Sidebar` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowHide_Small` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowHide_Standard` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowHide_Suggestion` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowShow_Sidebar` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowShow_Small` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowShow_Standard` | gui/frontend/shared/sounds.gui |  |
| `Sound_WindowShow_Suggestion` | gui/frontend/shared/sounds.gui |  |
| `Sound_Window_AmbienceMute_Snapshot` | gui/frontend/shared/sounds.gui |  |
| `Text_Light_Background_Overrides` | gui/frontend/shared/fonts.gui | format_override |
| `Window_Background` | gui/frontend/shared/windows.gui | background |
| `Window_Background_Popup` | gui/frontend/shared/windows.gui | background |
| `Window_Background_Sidebar` | gui/frontend/shared/windows.gui | background |
| `Window_Background_Sidebar_Multiplayer_Left` | gui/frontend/shared/windows.gui | background |
| `Window_Background_Sidebar_Multiplayer_Right` | gui/frontend/shared/windows.gui | background |
| `Window_Background_Subwindow` | gui/frontend/shared/windows.gui | background |
| `Window_Decoration` | gui/frontend/shared/windows.gui | using |
| `Window_Decoration_Frontend_Spike` | gui/frontend/shared/windows.gui | using |
| `Window_Decoration_Spike` | gui/frontend/shared/windows.gui | margin_widget |
| `Window_Margins` | gui/frontend/shared/windows.gui | margin_left, margin_right, margin_top, margin_bottom |
| `Window_Margins_Sidebar` | gui/frontend/shared/windows.gui | margin_right |
| `action_send_ship_to_retrofit` | gui/shared/sounds.gui | clicksound, using |
| `add_war_goal_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `additional_expenses_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `additional_income_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `alternating_dark_bg` | gui/companies_panel.gui | background |
| `article_input_fixed_bottom` | gui/right_click_menu.gui | flowcontainer |
| `article_input_fixed_top` | gui/right_click_menu.gui | default_header_clean_faded, flowcontainer, goods_filters |
| `article_input_items` | gui/right_click_menu.gui | margin_bottom, datacontext, article_input_state_list, article_input_country_list, article_input_strategic_region_list, article_input_goods_list, empty_state, article_input_company_monopoly, article_input_law_list, article_input_ship_list |
| `average_standard_of_living_lower_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `average_standard_of_living_middle_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `average_standard_of_living_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `average_standard_of_living_upper_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `back_button_sound` | gui/shared/sounds.gui | using |
| `battle_outcome_formatting` | gui/battle.gui | autoresize, parentanchor, using, fontsize_min, elide, max_width, align |
| `battle_outcome_status_formatting` | gui/battle.gui | margin, autoresize, multiline, maximumsize, minimumsize, align, parentanchor, using, background, max_width |
| `battle_outcome_status_formatting_frame` | gui/battle.gui | margin, autoresize, multiline, maximumsize, minimumsize, align, parentanchor, using, max_width, background |
| `bg_bronze_with_frame` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, shaderfile, texture_density, modify_texture |
| `bg_tiling_pattern` | gui/shared/textures.gui | texture, spriteType, spriteborder, blend_mode |
| `big_header_pattern` | gui/shared/textures.gui | texture, spriteType, texture_density, spriteborder, blend_mode, alpha |
| `black_screen_transition_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `bloc_member_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `bloc_member_leave_sound` | gui/shared/sounds.gui | clicksound, using |
| `blurry_dark_background` | gui/shared/backgrounds.gui | spriteType, spriteborder, shaderfile, texture, alpha |
| `bolster_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_coins_lvl_0_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_coins_lvl_1_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_coins_lvl_2_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_coins_lvl_3_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_coins_lvl_4_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_coins_lvl_5_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_pause_all_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `budget_resume_all_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `build_building_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `build_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `building_ownership_share_tooltip` | gui/custom_tooltip.gui | tooltip, tooltipwidget |
| `building_profitability_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `building_registry_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `building_size_choose_alpha` | gui/building_details_panel.gui | alpha |
| `building_size_tooltip_with_ownership` | gui/custom_tooltip.gui | tooltip, using, tooltipwidget |
| `building_world_profitability_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `button_animation_duration` | gui/shared/defaults.gui | duration |
| `button_animation_duration_slow` | gui/shared/defaults.gui | duration |
| `cash_reserves_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `change_level_flag_animation` | gui/shared/flags.gui | modify_texture, state |
| `check_button` | gui/shared/buttons.gui | gfxtype, shaderfile, texture, framesize, size |
| `check_button_sound` | gui/shared/sounds.gui | using |
| `circle_bg_simple` | gui/shared/backgrounds.gui | texture, texture_density |
| `circle_bg_simple_dark` | gui/shared/backgrounds.gui | texture, texture_density |
| `clean_button` | gui/shared/buttons.gui | using |
| `clean_button_sound` | gui/shared/sounds.gui | using |
| `clickthrough_blocker` | gui/shared/defaults.gui | alwaystransparent, filter_mouse |
| `close_button_sound` | gui/shared/sounds.gui | using |
| `clout_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `color_blue_negative` | gui/politics_panel_types.gui | color |
| `color_gold_positive` | gui/politics_panel_types.gui | color |
| `color_green_approval` | gui/politics_panel_types.gui | color |
| `color_grey_undecided` | gui/politics_panel_types.gui | color |
| `color_red_disapproval` | gui/politics_panel_types.gui | color |
| `colored_panel` | gui/map_markers.gui | texture, texture_density, spriteborder, spriteType, icon |
| `colored_panel_bright` | gui/map_markers.gui | using, texture |
| `colored_panel_dark` | gui/map_markers.gui | using, texture |
| `colored_panel_ui` | gui/map_markers.gui | using, alpha |
| `combat_unit_item_name` | gui/military_formation_panel.gui | parentanchor, autoresize, elide, align, tooltip |
| `commander_mobilize_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `commander_promote_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `commander_recruit_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `commander_retire_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `companies_header_texts` | gui/companies_panel.gui | minimumsize, maximumsize, autoresize, multiline, align, parentanchor |
| `company_building_disband_sound` | gui/shared/sounds.gui | clicksound, using |
| `company_building_establish_sound` | gui/shared/sounds.gui | clicksound, using |
| `company_charter_grant_sound` | gui/shared/sounds.gui | clicksound, using |
| `company_charter_revoke_sound` | gui/shared/sounds.gui | clicksound, using |
| `company_item_text` | gui/companies_panel.gui | align, autoresize, maximumsize, multiline |
| `competitiveness_building_type_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `competitiveness_world_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `condensed_table` | gui/tooltip.gui | margin, margin_right, minimumsize, maximumsize |
| `confirm_button_sound` | gui/shared/sounds.gui | using |
| `conscription_center_activate_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `console_frame` | gui/console.gui | texture, spriteType, spriteborder, texture_density |
| `construction_goods_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `consumption_tax_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `current_situation_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `dark_area` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha |
| `dark_area_rounded` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha |
| `debug_square` | gui/window_component_library.gui | background |
| `dec_pattern` | gui/shared/textures.gui | texture, blend_mode, spriteType, spriteborder, texture_density |
| `decrease_autonomy_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `decrease_button_sound` | gui/shared/sounds.gui | using |
| `default_background` | gui/shared/backgrounds.gui | spriteType, spriteborder, texture, texture_density, modify_texture |
| `default_bg` | gui/shared/backgrounds.gui | using, texture |
| `default_bg_nofade` | gui/shared/backgrounds.gui | using, texture |
| `default_bg_properties` | gui/shared/backgrounds.gui | using, spriteType, spriteborder, texture_density, modify_texture |
| `default_bg_sidebar` | gui/shared/backgrounds.gui | using, spriteborder_right, texture |
| `default_button` | gui/shared/buttons.gui | using, texture, gfxtype, upframe, uphoverframe, uppressedframe, downframe, downhoverframe, downpressedframe, disableframe, spriteborder, framesize ... |
| `default_button_action` | gui/shared/buttons.gui | using, texture |
| `default_button_alternate` | gui/shared/buttons.gui | using, texture |
| `default_button_animation` | gui/shared/animations.gui | state |
| `default_button_map_interaction` | gui/shared/buttons.gui | using, texture |
| `default_button_primary` | gui/shared/buttons.gui | using |
| `default_button_primary_action` | gui/shared/buttons.gui | using |
| `default_button_primary_big` | gui/shared/buttons.gui | using |
| `default_button_primary_big_action` | gui/shared/buttons.gui | using |
| `default_button_properties` | gui/shared/buttons.gui | effectname, spriteType, texture_density, modify_texture, using |
| `default_button_sound` | gui/shared/sounds.gui | using |
| `default_button_tertiary` | gui/shared/buttons.gui | using |
| `default_button_texture_alpha` | gui/shared/buttons.gui | alpha |
| `default_content_fade` | gui/shared/animations.gui | state |
| `default_dropdown` | gui/shared/dropdown.gui | alwaystransparent, active_item, item, list |
| `default_fade_in` | gui/shared/animations.gui | state |
| `default_fade_in_out` | gui/shared/animations.gui | state |
| `default_header_bg` | gui/shared/backgrounds.gui | using, modify_texture |
| `default_header_bg_faded` | gui/shared/backgrounds.gui | using |
| `default_hide_properties` | gui/shared/animations.gui | using, alpha |
| `default_hide_properties_fast` | gui/shared/animations.gui | duration, alpha, using |
| `default_list_position` | gui/shared/layout.gui | parentanchor, widgetanchor |
| `default_margin` | gui/shared/layout.gui | margin |
| `default_mouse_states_animation` | gui/shared/animations.gui | state |
| `default_show_properties` | gui/shared/animations.gui | duration, alpha, using |
| `default_show_properties_fast` | gui/shared/animations.gui | duration, alpha, using |
| `default_show_properties_slow` | gui/shared/animations.gui | duration, alpha, using |
| `diplo_action_triggers_and_effects_visibility` | gui/country_panel.gui | visible |
| `diplo_play_phases_scale` | gui/diplomatic_play_panel.gui | scale |
| `diplomatic_action_button_after_label` | gui/country_panel.gui | hbox |
| `diplomatic_action_button_properties` | gui/country_panel.gui | enabled, onclick, using, icon |
| `diplomatic_action_tooltip` | gui/country_panel.gui | tooltipwidget |
| `diplomatic_pacts_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `diplomatic_pacts_income_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `diplomatic_play_confirmation_sound` | gui/shared/sounds.gui | clicksound, using |
| `diplomatic_play_demobilize_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `diplomatic_play_mobilize_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `diplomatic_play_support_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `disabled_stripes` | gui/shared/buttons.gui | button |
| `dividends_tax_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `dropdown_background` | gui/shared/backgrounds.gui | spriteType, spriteborder, spriteborder_top, shaderfile, texture, texture_density, margin, modify_texture |
| `dropdown_background_settings` | gui/shared/backgrounds.gui | icon, background |
| `dropdown_button_sound` | gui/shared/sounds.gui | using |
| `dummy_color_picker_buttons` | gui/color_picker.gui | widget |
| `editor_text` | gui/console.gui | font, fontsize, fontcolor |
| `elide_fontsize_min` | gui/tooltip.gui | elide, fontsize_min |
| `empty_state_text_properties` | gui/empty_state.gui | alpha |
| `entry_bg` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, shaderfile, texture_density, modify_texture |
| `entry_bg_fancy` | gui/shared/backgrounds.gui | background |
| `entry_bg_fancy_dark` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, shaderfile, texture_density, modify_texture |
| `entry_bg_fancy_solid_bg` | gui/shared/backgrounds.gui | background |
| `entry_bg_mask_bottom` | gui/shared/backgrounds.gui | modify_texture |
| `entry_bg_mask_top` | gui/shared/backgrounds.gui | modify_texture |
| `entry_bg_simple` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `entry_bg_simple_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `entry_bg_simple_solid` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, modify_texture |
| `entry_bg_simple_with_header` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, spriteborder_top, texture_density, modify_texture |
| `entry_bg_top_mask` | gui/shared/backgrounds.gui | modify_texture |
| `entry_bg_unit` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `entry_bg_unit_dark` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `entry_fancy_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, using |
| `entry_header` | gui/shared/backgrounds.gui | using |
| `entry_header_dark` | gui/shared/backgrounds.gui | using |
| `exit_game_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `expand_arrow` | gui/shared/buttons.gui | texture, gfxtype, framesize, size |
| `expand_arrow_expanded` | gui/shared/buttons.gui | texture, gfxtype, framesize, size |
| `expand_button_bg` | gui/shared/buttons.gui | texture, spriteType, spriteborder, texture_density, using, gfxtype, effectname, modify_texture |
| `expand_button_bg_dropdown` | gui/shared/buttons.gui | using, texture |
| `expand_button_bg_left_fade` | gui/shared/buttons.gui | using |
| `expand_button_bg_no_fade` | gui/shared/buttons.gui | using |
| `expand_button_bg_right_fade` | gui/shared/buttons.gui | using |
| `expand_button_sound` | gui/shared/sounds.gui | using |
| `expanded_button_sound` | gui/shared/sounds.gui | using |
| `expanded_list_bg` | gui/shared/layout.gui | background |
| `fade_bottom_entry_fancy_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture, using |
| `fade_center_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_center_colored_black` | gui/shared/backgrounds.gui | using, color |
| `fade_center_colored_green` | gui/shared/backgrounds.gui | using, color |
| `fade_center_colored_grey` | gui/shared/backgrounds.gui | using, color |
| `fade_center_colored_red` | gui/shared/backgrounds.gui | using, color |
| `fade_center_simple` | gui/shared/backgrounds.gui | using, modify_texture |
| `fade_down_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_down_simple` | gui/shared/backgrounds.gui | modify_texture |
| `fade_horizontal_center_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_horizontal_center_inverted_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_horizontal_center_inverted_colored_green` | gui/shared/backgrounds.gui | using, color |
| `fade_horizontal_center_inverted_colored_red` | gui/shared/backgrounds.gui | using, color |
| `fade_left_and_right_simple` | gui/shared/backgrounds.gui | using, modify_texture |
| `fade_left_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_left_colored_green` | gui/shared/backgrounds.gui | using, color |
| `fade_left_colored_red` | gui/shared/backgrounds.gui | using, color |
| `fade_left_simple` | gui/shared/backgrounds.gui | using, modify_texture |
| `fade_left_simple_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_left_vertical_center_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_right_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_right_colored_green` | gui/shared/backgrounds.gui | using, color |
| `fade_right_colored_red` | gui/shared/backgrounds.gui | using, color |
| `fade_right_entry_fancy_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture, using |
| `fade_right_entry_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture, using |
| `fade_right_rounded_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_right_simple` | gui/shared/backgrounds.gui | using, modify_texture |
| `fade_right_simple_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_right_vertical_center_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_top_entry_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture, using |
| `fade_top_illus` | gui/shared/backgrounds.gui | modify_texture |
| `fade_up_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_up_colored_black` | gui/shared/backgrounds.gui | using, color |
| `fade_up_colored_green` | gui/shared/backgrounds.gui | using, color |
| `fade_up_colored_grey` | gui/shared/backgrounds.gui | using, color |
| `fade_up_colored_red` | gui/shared/backgrounds.gui | using, color |
| `fade_up_simple` | gui/shared/backgrounds.gui | modify_texture |
| `fade_vertical_center_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_vertical_center_inverted_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha, modify_texture |
| `fade_vertical_center_inverted_colored_green` | gui/shared/backgrounds.gui | using, color |
| `fade_vertical_center_inverted_colored_red` | gui/shared/backgrounds.gui | using, color |
| `fancy_frame_mask` | gui/shared/backgrounds.gui | modify_texture |
| `fancy_frame_solid_bg` | gui/shared/backgrounds.gui | background |
| `fancy_pattern` | gui/shared/textures.gui | texture, spriteType, texture_density, spriteborder, blend_mode, alpha |
| `fancy_pattern_2` | gui/shared/textures.gui | texture, spriteType, texture_density, spriteborder, blend_mode, alpha |
| `filter_button_sound` | gui/shared/sounds.gui | using |
| `filter_section_header_active_bg` | gui/building_browser_panel.gui | using, color, margin_bottom, margin_left, margin_top |
| `flag_button_glow` | gui/shared/buttons.gui | texture, spriteType, spriteborder, gfxtype, effectname, framesize, using |
| `flag_button_sound` | gui/shared/sounds.gui | using |
| `flag_overlay` | gui/shared/flags.gui | modify_texture |
| `fleet_panel_construction_template_build` | gui/shared/sounds.gui | clicksound, using |
| `fleet_panel_construction_template_build_cancel` | gui/shared/sounds.gui | clicksound, using |
| `fleet_panel_open` | gui/shared/sounds.gui | start_sound |
| `fleet_panel_set_ship_as_flagship` | gui/shared/sounds.gui | clicksound, using |
| `fleet_panel_ship_decommission` | gui/shared/sounds.gui | clicksound, using |
| `fontsize_large` | gui/shared/defaults.gui | fontsize |
| `fontsize_medium` | gui/shared/defaults.gui | fontsize, using |
| `fontsize_mega` | gui/shared/defaults.gui | fontsize |
| `fontsize_small` | gui/shared/defaults.gui | fontsize, using |
| `fontsize_xl` | gui/shared/defaults.gui | fontsize |
| `fontsize_xsmall` | gui/shared/defaults.gui | fontsize, using |
| `fontsize_xxl` | gui/shared/defaults.gui | fontsize |
| `formation_item_progressbar_size` | gui/military_formation_panel.gui | size |
| `frame_by_frame_default_duration` | gui/shared/animations_frame_by_frame.gui | duration |
| `frame_by_frame_envelope_duration` | gui/topfrontend.gui | duration |
| `frame_by_frame_medium_duration` | gui/shared/animations_frame_by_frame.gui | duration |
| `frame_by_frame_slow_duration` | gui/shared/animations_frame_by_frame.gui | duration |
| `frame_decorative_light_bg` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `frame_small` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `frame_small_mask` | gui/shared/backgrounds.gui | modify_texture |
| `frame_small_mask_top` | gui/shared/backgrounds.gui | modify_texture |
| `fullscreen_hide` | gui/block_windows.gui | visible |
| `game_speed_sound` | gui/shared/sounds.gui | clicksound, using |
| `generic_diplomatic_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `generic_highlight` | gui/shared/selections.gui | modify_texture |
| `glossary_properties` | gui/tooltip.gui | alwaystransparent, using, button, background |
| `glow_button` | gui/shared/buttons.gui | texture, spriteType, spriteborder, gfxtype, effectname, framesize, using |
| `glow_button_border` | gui/shared/buttons.gui | texture, spriteType, spriteborder, gfxtype, effectname, framesize, using |
| `glow_button_sound` | gui/shared/sounds.gui | using |
| `goods_filter_button` | gui/market_panel.gui | using, framesize, gfxtype, effectname, upframe, overframe, downframe |
| `goods_list_item` | gui/market_panel.gui | widget |
| `government_goods_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `government_share_dividends_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `government_share_losses_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `government_slaves_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `government_wages_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `half_and_fullscreen_hide` | gui/block_windows.gui | visible |
| `half_and_fullscreen_show` | gui/block_windows.gui | visible |
| `header_color` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder |
| `header_font` | gui/shared/defaults.gui | font |
| `header_font_fancy` | gui/shared/defaults.gui | font |
| `header_font_fancy_size` | gui/shared/defaults.gui | fontsize |
| `header_font_size` | gui/shared/defaults.gui | fontsize |
| `header_graphical_properties` | gui/shared/backgrounds.gui | using, modify_texture |
| `highlighted_active_square_selection` | gui/shared/selections.gui | spriteType, spriteborder, texture, size, parentanchor, shaderfile, texture_density, alpha, modify_texture, state |
| `highlighted_circle_selection_big` | gui/shared/selections.gui | texture, size, parentanchor, modify_texture, state |
| `highlighted_circle_selection_small` | gui/shared/selections.gui | texture, size, parentanchor, modify_texture, state |
| `highlighted_selected_square_selection` | gui/shared/selections.gui | spriteType, spriteborder, texture, size, parentanchor, shaderfile, texture_density, alpha, modify_texture, state |
| `highlighted_square_selection` | gui/shared/selections.gui | spriteType, spriteborder, texture, size, parentanchor, shaderfile, texture_density, alpha, modify_texture, state |
| `horizontal_scrollbar` | gui/core.gui | scrollbar |
| `hud_elements_alpha` | gui/topbar.gui | alpha |
| `hud_shiny_effect` | gui/shared/animations.gui | modify_texture, state |
| `hud_visibility` | gui/topbar.gui | visible |
| `icon_button_sound` | gui/shared/sounds.gui | using |
| `icon_toggle_all_off_sound` | gui/shared/sounds.gui | clicksound, using |
| `icon_toggle_all_on_sound` | gui/shared/sounds.gui | clicksound, using |
| `icon_toggle_single_off_sound` | gui/shared/sounds.gui | clicksound, using |
| `icon_toggle_single_on_sound` | gui/shared/sounds.gui | clicksound, using |
| `icon_toggle_single_onoff_sound` | gui/shared/sounds.gui | clicksound, using |
| `ig_clouts_tooltip_with_graph` | gui/graph_tooltips.gui | tooltipwidget |
| `ig_loyalists_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `ig_panel_section_background` | gui/interest_group_panel.gui | using, alpha, margin, modify_texture |
| `ig_panel_section_margins` | gui/interest_group_panel.gui | margin |
| `ig_radicals_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `illu_alpha` | gui/shared/backgrounds.gui | alpha |
| `illus_top_shadow_bottom_fade` | gui/shared/backgrounds.gui | modify_texture |
| `in_government_tooltip_with_graph` | gui/graph_tooltips.gui | tooltipwidget |
| `in_opposition_tooltip_with_graph` | gui/graph_tooltips.gui | tooltipwidget |
| `increase_autonomy_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `increase_button_sound` | gui/shared/sounds.gui | using |
| `independence_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `information_panels` | gui/ingame_hud.gui | add_wargoal_panel, battle_panel, building_details_panel, character_panel, military_formation_panel, ship_panel, country_panel, society_panel, culture_info_panel, decisions_panel, diplomatic_overview_panel, diplomatic_play_panel ... |
| `information_panels_fullscreens` | gui/ingame_hud.gui | politics_panel, politics_panel_change_law, tech_tree_panel, pop_browser_panel, building_browser_panel, treaty_draft_panel |
| `information_tab_visibility` | gui/country_panel.gui | visible |
| `information_tab_visibility_not` | gui/country_panel.gui | visible |
| `interest_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `investment_income_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `investment_pool_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `is_not_colonizable_and_has_either_relations_or_relationship_change` | gui/map_markers.gui | visible |
| `is_not_player_and_not_colonizable_country` | gui/country_panel.gui | visible |
| `law_header` | gui/politics_panel_types.gui | autoresize, position, align, parentanchor, widgetanchor, using |
| `lens_war_indicator_delay` | gui/lens_toolbar.gui | duration |
| `lens_war_indicator_duration` | gui/lens_toolbar.gui | duration |
| `lens_war_shimmer_duration` | gui/lens_toolbar.gui | duration |
| `lens_war_smoke_alpha` | gui/lens_toolbar.gui | alpha |
| `lens_war_smoke_duration` | gui/lens_toolbar.gui | duration |
| `light_bg` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, modify_texture |
| `literacy_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `lobby_hover_highlight` | gui/political_lobby_panel.gui | onmousehierarchyenter, onmousehierarchyleave |
| `logo_letter_delay` | gui/in_game_menu_logo.gui | duration |
| `logo_letter_duration` | gui/in_game_menu_logo.gui | duration |
| `logo_letter_properties` | gui/in_game_menu_logo.gui | position, alpha |
| `logo_letter_scale` | gui/in_game_menu_logo.gui | scale |
| `look_at_me_animation` | gui/shared/animations.gui | state |
| `look_at_me_animation_weak` | gui/shared/animations.gui | state |
| `look_at_me_text_animation` | gui/shared/animations.gui | state |
| `loyalists_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `loyalty_slice_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `main_bg` | gui/shared/backgrounds.gui | background |
| `main_bg_non_transparent` | gui/shared/backgrounds.gui | background |
| `main_menu_logo_shimmer` | gui/frontend/frontend_main.gui | modify_texture, state |
| `main_menu_shimmer` | gui/frontend/frontend_main.gui | modify_texture, state |
| `map_list_panels` | gui/ingame_hud.gui | empty_map_list_panel, default_map_list_panel, build_building_map_list_panel, colony_map_list_panel, cossack_host_map_list_panel, diplo_action_map_list_panel, diplo_action_rivalry_map_list_panel, treaty_article_map_list_panel, decree_map_list_panel, naval_mission_map_list_panel, markets_map_list_panel, power_blocs_map_list_panel ... |
| `map_modes_button_position` | gui/block_windows.gui | position |
| `maplens_diplomatic_sound` | gui/shared/sounds.gui | clicksound |
| `maplens_generic_sound` | gui/shared/sounds.gui | clicksound, using |
| `maplens_military_sound` | gui/shared/sounds.gui | clicksound |
| `maplens_political_sound` | gui/shared/sounds.gui | clicksound |
| `maplens_production_sound` | gui/shared/sounds.gui | clicksound |
| `maplens_trade_sound` | gui/shared/sounds.gui | clicksound |
| `marginalized_tooltip_with_graph` | gui/graph_tooltips.gui | tooltipwidget |
| `market_filter_industrial_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `market_filter_luxury_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `market_filter_military_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `market_filter_staple_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `market_goods_orders_with_table` | gui/table_tooltips.gui | tooltip, tooltipwidget |
| `market_price_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `maximap_activate_sound` | gui/shared/sounds.gui | start_sound |
| `maximap_deactivate_sound` | gui/shared/sounds.gui | start_sound |
| `military_goods_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `military_ship_maintenance_expense_tooltip` | gui/graph_tooltips.gui | tooltip |
| `military_slaves_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `military_total_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `military_wages_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `minting_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `money_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `multiplayer_lobby_selected_country_info` | gui/multiplayer_lobby_types.gui | visible, datacontext, margin_top, margin_bottom, scrollarea |
| `naval_battle_combat_log_close` | gui/shared/sounds.gui | start_sound |
| `naval_battle_combat_log_open` | gui/shared/sounds.gui | start_sound |
| `naval_battle_emergency_retreat` | gui/shared/sounds.gui | clicksound, using |
| `naval_battle_panel_open` | gui/shared/sounds.gui | start_sound |
| `naval_commander_color` | gui/shared/character.gui | modify_texture |
| `naval_mission_blockade` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_convoy_raiding` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_deploy_marines` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_escort` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_gunboat_diplomacy` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_hunt_pirates` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_intercept` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_privateer` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_project_power` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_settings_confirm` | gui/shared/sounds.gui | clicksound, using |
| `naval_mission_thwart_slave_trade` | gui/shared/sounds.gui | clicksound, using |
| `notification_appear_sound` | gui/shared/sounds.gui | start_sound |
| `notification_dismiss_button_sound` | gui/shared/sounds.gui | using |
| `notification_go_to_visibility` | gui/notifications.gui | visible |
| `notification_icon_go_to` | gui/notifications.gui | datacontext, hbox, message_feed_go_to_button |
| `notification_icon_go_to_text_area` | gui/notifications.gui | datacontext, message_feed_go_to_text_area_button, hbox, text_multi |
| `order_general_active_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `order_general_front_advance_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `order_general_front_defend_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `order_general_standby_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `overlord_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `paper_bg` | gui/shared/backgrounds.gui | spriteType, spriteborder, texture, texture_density, modify_texture |
| `paper_bg_dark` | gui/shared/backgrounds.gui | spriteType, spriteborder, texture, texture_density, modify_texture |
| `paper_bg_light` | gui/shared/backgrounds.gui | spriteType, spriteborder, texture, texture_density, modify_texture |
| `paused_effect_alpha` | gui/timemanip.gui | alpha |
| `paused_effect_duration_hide` | gui/timemanip.gui | duration |
| `paused_effect_duration_show` | gui/timemanip.gui | duration |
| `phase_glow` | gui/diplomatic_play_panel.gui | state |
| `phase_image_small_swap` | gui/diplomatic_play_panel.gui | modify_texture, state |
| `phase_image_swap` | gui/diplomatic_play_panel.gui | state |
| `play_continue_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `play_pause_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `plot_line` | gui/politics_panel_types.gui | gfxtype, effectname, line_type, line_cap, alpha, texture, uv_scale, mask, mask_uv_scale |
| `political_movement_radicalism_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `political_movement_support_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `pop_bg` | gui/shared/backgrounds.gui | texture |
| `pop_browser_filter_button` | gui/pop_browser_panel.gui | size, align, margin_left |
| `pop_browser_filter_button_icon` | gui/pop_browser_panel.gui | size, parentanchor, position |
| `pop_browser_filter_section` | gui/pop_browser_panel.gui | margin_top, margin_bottom, parentanchor, direction |
| `pop_browser_section_header_size` | gui/pop_browser_panel.gui | size |
| `pop_pol_str_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `pop_population_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `pop_sol_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `population_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `port_connection_expense_tooltip` | gui/graph_tooltips.gui | tooltip |
| `portrait_base` | gui/shared/character.gui | pop_out, gfxtype, shaderfile, intersectionmask, background_texture, texture |
| `power_bloc_list_item_bg` | gui/power_bloc_panel.gui | background |
| `principles_button_shimmer_click_sound` | gui/shared/sounds.gui | clicksound, using |
| `principles_button_submit_sound` | gui/shared/sounds.gui | clicksound, using |
| `productivity_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `progressbar_changed_animation` | gui/shared/progressbars.gui | state |
| `progressbar_changed_animation_with_curve` | gui/shared/progressbars.gui | progress_change_to_duration_curve, state |
| `progressbar_marker_indicator` | gui/shared/progressbars.gui | marker |
| `progressbar_texture_properties` | gui/shared/progressbars.gui | modify_texture |
| `radicals_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `red_button` | gui/shared/buttons.gui | using, texture |
| `regular_font` | gui/shared/defaults.gui | font, fontsize |
| `right_click_menu_title_margin_left` | gui/right_click_menu.gui | margin_left |
| `rotate_glow_animation` | gui/shared/animations.gui | texture, size, alwaystransparent, ignore_in_debug_draw, modify_texture, state |
| `rotate_glow_animation_02` | gui/shared/animations.gui | size, alwaystransparent, ignore_in_debug_draw, modify_texture, state |
| `rotate_glow_animation_02_with_sound` | gui/shared/animations.gui | size, alwaystransparent, ignore_in_debug_draw, modify_texture, state |
| `rotate_glow_animation_green` | gui/shared/animations.gui | size, alwaystransparent, ignore_in_debug_draw, modify_texture, state |
| `rotate_glow_animation_red` | gui/shared/animations.gui | size, alwaystransparent, ignore_in_debug_draw, modify_texture, state |
| `rotate_glow_blue` | gui/shared/animations.gui | texture, size, alwaystransparent, ignore_in_debug_draw, modify_texture, state |
| `rotate_glow_overlay_blue` | gui/shared/animations.gui | modify_texture, state |
| `rotate_glow_overlay_blue_stop` | gui/shared/animations.gui | modify_texture, state |
| `rotate_glow_red` | gui/shared/animations.gui | using, texture |
| `rotate_glow_red_02` | gui/shared/animations.gui | using, texture |
| `round_button_big_button_sound` | gui/shared/sounds.gui | using |
| `rounded_background_blue` | gui/shared/backgrounds.gui | spriteType, spriteborder, texture, texture_density, modify_texture |
| `scrollbar_slider` | gui/core.gui | name, texture, gfxtype, effectname, framesize, size, upframe, overframe, downframe, intersectionmask, spriteType, spriteborder ... |
| `sdk_dropdown_enum` | gui/pdx_account/base_types.gui |  |
| `sdk_horizontal_scrollbar` | gui/pdx_account/base_types.gui |  |
| `sdk_vertical_scrollbar` | gui/pdx_account/base_types.gui |  |
| `sea_node_framed_button_gfx` | gui/map_markers.gui | gfxtype, effectname, upframe, overframe, downframe |
| `select_button_sound` | gui/shared/sounds.gui | using |
| `selected_sidepanel_animation` | gui/information_panels_types.gui | widget, panel_button_animation_arrow |
| `selected_sidepanel_animation_small` | gui/information_panels_types.gui | widget, panel_button_animation_arrow_small |
| `selected_tabs` | gui/shared/tab_bars.gui | texture, spriteType, spriteborder, spriteborder_bottom |
| `set_level_bar_background` | gui/budget_panel.gui | background, margin_left, margin_right |
| `setting_bar_background` | gui/strait_panel.gui | margin, background |
| `sfx_expand_button_sound` | gui/shared/sounds.gui | using |
| `sfx_expanded_button_sound` | gui/shared/sounds.gui | using |
| `sfx_select_button_sound` | gui/shared/sounds.gui | using |
| `shimmer` | gui/shared/animations.gui | modify_texture, state |
| `shimmer_fade_in` | gui/shared/animations.gui | modify_texture, state |
| `shimmer_notification` | gui/shared/animations.gui | modify_texture, state |
| `ship_designer_modification_armor_heavy` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_armor_light` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_armor_medium` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_guns_heavy` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_guns_light` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_guns_medium` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_propulsion_heavy` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_propulsion_light` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_propulsion_medium` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_range_long` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_range_medium` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_range_short` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_modification_wildcard` | gui/shared/sounds.gui | clicksound, using |
| `ship_designer_panel_open` | gui/shared/sounds.gui | start_sound |
| `ship_designer_template_save` | gui/shared/sounds.gui | clicksound, using |
| `ship_panel_open` | gui/shared/sounds.gui | start_sound |
| `sidebar_button_animation_duration` | gui/information_panels_types.gui | duration |
| `sidebar_button_size` | gui/information_panel_bar.gui | size |
| `sidebar_button_size_small` | gui/information_panel_bar.gui | size |
| `sidebar_margin` | gui/block_windows.gui | margin_left |
| `sidepanel_filler_bg` | gui/block_windows.gui | widget |
| `sidepanel_label_background` | gui/information_panels_types.gui | background, divider_clean |
| `sidepanel_plus_sidebar_size` | gui/block_windows.gui | size |
| `sidepanel_top_header` | gui/shared/backgrounds.gui | background |
| `simple_frame` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density |
| `simple_frame_mask` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, blend_mode |
| `simple_header_colored` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, alpha |
| `situation_entry_parent_hover_states` | gui/notifications.gui | state |
| `small_battle_outcome_formatting` | gui/battle.gui | autoresize, fontsize_min, elide, max_width, align, using |
| `small_nib` | gui/map_markers.gui | container |
| `society_panel_tab_contents_properties` | gui/culture_panel.gui | parentanchor, minimumsize, maximumsize, direction, using |
| `sort_button_bg` | gui/shared/buttons.gui | texture, size, spriteType, spriteborder, texture_density, using, gfxtype, effectname, modify_texture |
| `sort_button_sound` | gui/shared/sounds.gui | using |
| `speed_button_1` | gui/timemanip.gui | texture, framesize, size, using, onclick, input_action, tooltip |
| `speed_button_2` | gui/timemanip.gui | texture, framesize, size, using, onclick, input_action, tooltip |
| `speed_button_3` | gui/timemanip.gui | texture, framesize, size, using, onclick, input_action, tooltip |
| `speed_button_4` | gui/timemanip.gui | texture, framesize, size, using, onclick, input_action, tooltip |
| `speed_button_5` | gui/timemanip.gui | texture, framesize, size, using, onclick, input_action, tooltip |
| `speedometer_set_speed_properties` | gui/timemanip.gui | gfxtype, effectname, upframe, overframe, downframe, enabled, using |
| `standard_formation_item_size` | gui/right_click_menu.gui | size |
| `start_diplo_play_table_header` | gui/popups.gui | margin_bottom, align, divider_clean |
| `start_game_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `state_government_expenses_with_table` | gui/table_tooltips.gui | tooltip, tooltipwidget |
| `state_taxation_revenue_with_table` | gui/table_tooltips.gui | tooltip, tooltipwidget |
| `straits_access_close_sound` | gui/shared/sounds.gui | clicksound, using |
| `straits_access_no_military_sound` | gui/shared/sounds.gui | clicksound, using |
| `straits_access_open_sound` | gui/shared/sounds.gui | clicksound, using |
| `straits_allowedcountries_allies_sound` | gui/shared/sounds.gui | clicksound, using |
| `straits_allowedcountries_no_enemies_sound` | gui/shared/sounds.gui | clicksound, using |
| `straits_allowedcountries_subjects_sound` | gui/shared/sounds.gui | clicksound, using |
| `straits_panel_open_sound` | gui/shared/sounds.gui | start_sound |
| `sub_tab_button_sound` | gui/shared/sounds.gui | using |
| `subject_action_sound` | gui/shared/sounds.gui | clicksound, using |
| `subsidies_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `subventions_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `supply_ship_maintenance_expense_tooltip` | gui/graph_tooltips.gui | tooltip |
| `suppress_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `tab_button_sound` | gui/shared/sounds.gui | using |
| `tab_text_properties` | gui/shared/tab_bars.gui | parentanchor, size, align, fontsize_min, elide, margin, multiline, alwaystransparent |
| `table_cell` | gui/tooltip.gui | layoutpolicy_horizontal, layoutpolicy_vertical, elide, fontsize_min, background |
| `table_column` | gui/tooltip.gui | layoutpolicy_horizontal, layoutpolicy_vertical |
| `table_header` | gui/tooltip.gui | layoutpolicy_horizontal, layoutpolicy_vertical, autoresize, minimumsize, maximumsize, margin_bottom, using, divider_clean |
| `tariffs_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `tax_income_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `tax_poll_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `tech_tree_divider` | gui/tech_tree.gui | using, alpha, parentanchor, modify_texture |
| `technology_confirm_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `text_edit_bg` | gui/shared/backgrounds.gui | spriteType, spriteborder, shaderfile, texture, texture_density, alpha |
| `texture_cloth` | gui/shared/textures.gui | texture, spriteType, texture_density, spriteborder, blend_mode |
| `texture_velvet` | gui/shared/textures.gui | texture, spriteType, texture_density, spriteborder, blend_mode |
| `tooltip_above` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_background` | gui/shared/backgrounds.gui | spriteType, spriteborder, shaderfile, texture |
| `tooltip_below` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_center` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_es` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_font` | gui/shared/defaults.gui | font, fontsize |
| `tooltip_ne` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_nw` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_properties` | gui/tooltip.gui | alwaystransparent, using, button, background, icon |
| `tooltip_se` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `tooltip_segment_background` | gui/custom_tooltip.gui | background |
| `tooltip_segment_margin` | gui/custom_tooltip.gui | margin |
| `tooltip_segment_margin_first` | gui/custom_tooltip.gui | margin, margin_top |
| `tooltip_ws` | gui/frontend/shared/defaults.gui | tooltip_type, tooltip_parentanchor, tooltip_widgetanchor, tooltip_verticalbehavior, tooltip_horizontalbehavior |
| `top_header_bg` | gui/shared/backgrounds.gui | using, modify_texture |
| `top_header_bg_shading` | gui/shared/textures.gui | texture, spriteType, spriteborder, blend_mode |
| `top_illu_properties` | gui/shared/backgrounds.gui | modify_texture |
| `topbar_bg` | gui/shared/backgrounds.gui | spriteType, spriteborder, spriteborder_left, spriteborder_bottom, texture, texture_density, modify_texture |
| `toplevel_envelope_animation` | gui/topfrontend.gui | state |
| `total_expenses_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `total_income_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `track_line` | gui/shared/backgrounds.gui | texture, texture_density, spriteType, spriteborder |
| `transparent_if_unmobilized_in_conflict` | gui/map_markers.gui | alpha |
| `treaties_flag_bg` | gui/shared/backgrounds.gui | texture, spriteType, spriteborder, texture_density, modify_texture |
| `treaty_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `treaty_income_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `treaty_slide_up_animation` | gui/block_windows.gui | position, alpha, state |
| `ui_back` | gui/shared/sounds.gui | clicksound |
| `ui_checkbox` | gui/shared/sounds.gui | clicksound |
| `ui_close` | gui/shared/sounds.gui | clicksound |
| `ui_confirm` | gui/shared/sounds.gui | clicksound |
| `ui_decrement` | gui/shared/sounds.gui | clicksound |
| `ui_event_glow` | gui/shared/selections.gui | size, spriteType, spriteborder, texture, texture_density |
| `ui_event_glow_animation` | gui/shared/selections.gui | state, icon |
| `ui_event_glow_animation_looping` | gui/shared/selections.gui | icon |
| `ui_flag` | gui/shared/sounds.gui | clicksound |
| `ui_increment` | gui/shared/sounds.gui | clicksound |
| `ui_item_add` | gui/shared/sounds.gui | clicksound |
| `ui_item_remove` | gui/shared/sounds.gui | clicksound |
| `ui_notification_dismiss` | gui/shared/sounds.gui | clicksound |
| `ui_pointer_over` | gui/shared/sounds.gui | oversound |
| `ui_select` | gui/shared/sounds.gui | clicksound |
| `ui_sfx_decrement` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_global_panel_show` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_global_popup` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_increment` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_pause_logo` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_play_continue` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_play_pause` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_pointer_over` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_select` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_victoria_logo` | gui/shared/sounds.gui | soundeffect |
| `ui_sfx_war_breaking_out_popup` | gui/shared/sounds.gui | soundeffect |
| `ui_sub_tab` | gui/shared/sounds.gui | clicksound |
| `ui_tab` | gui/shared/sounds.gui | clicksound |
| `unclickable_listentry` | gui/shared/backgrounds.gui | divider_clean |
| `unclickable_listentry_small` | gui/shared/backgrounds.gui | divider_clean |
| `vertical_scrollbar` | gui/core.gui | scrollbar |
| `viewport_sound_parameter_close` | gui/shared/sounds.gui | start_sound |
| `viewport_sound_parameter_open` | gui/shared/sounds.gui | start_sound |
| `visibility_countdown_to_war` | gui/diplomatic_play_panel.gui | visible |
| `visibility_diplomatic_maneuvers` | gui/diplomatic_play_panel.gui | visible |
| `visibility_opening_moves` | gui/diplomatic_play_panel.gui | visible |
| `visible_diplomatic_marker_show_extra_info` | gui/map_markers.gui | visible |
| `visible_if_cqe_foreign_government` | gui/construction_queue.gui | visible |
| `visible_if_cqe_player_government` | gui/construction_queue.gui | visible |
| `visible_if_cqe_private` | gui/construction_queue.gui | visible |
| `visible_if_either_current_or_next_order` | gui/shared/character.gui | visible |
| `visible_if_ownership_always_workforce` | gui/building_details_panel.gui | visible |
| `visible_if_ownership_can_be_split` | gui/building_details_panel.gui | visible |
| `visible_if_produces` | gui/building_details_panel.gui | visible |
| `war_to_arms_button_sound` | gui/shared/sounds.gui | clicksound, using |
| `welfare_payments_expense_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `window_hide_duration` | gui/shared/animations.gui | duration |
| `world_market_goods_filter_button` | gui/world_market_panel.gui | using, framesize, gfxtype, effectname, upframe, overframe, downframe |
| `world_market_goods_list_item` | gui/world_market_panel.gui | widget |
| `world_market_price_tooltip_with_graph` | gui/graph_tooltips.gui | tooltip, tooltipwidget |
| `zoom_button_sound` | gui/shared/sounds.gui | clicksound, using |
