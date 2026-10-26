# Data-binding types

These **885 types** are what `[ ... ]` expressions can reach. A data context (see `datacontext`) determines which type an expression starts from; every member below can then be chained with a dot, for example `Country.GetCapital.GetName`.

The **Layer** column says which part of the engine publishes the type: `gui` for the interface layer, `common` for shared value types, `script` for gameplay scopes, and `uncategorized` for the rest of the game's data objects. Type and member names are reproduced exactly as the game publishes them.

## By initial

- [A](a.md) — 25 types
- [B](b.md) — 28 types
- [C](c.md) — 80 types
- [D](d.md) — 35 types
- [E](e.md) — 35 types
- [F](f.md) — 23 types
- [G](g.md) — 55 types
- [H](h.md) — 15 types
- [I](i.md) — 31 types
- [J](j.md) — 13 types
- [K](k.md) — 3 types
- [L](l.md) — 26 types
- [M](m.md) — 114 types
- [N](n.md) — 29 types
- [O](o.md) — 18 types
- [P](p.md) — 87 types
- [R](r.md) — 12 types
- [S](s.md) — 114 types
- [T](t.md) — 109 types
- [U](u.md) — 7 types
- [V](v.md) — 16 types
- [W](w.md) — 10 types

## All types

| Type | Description | Members | Layer |
|---|---|---|---|
| [`AcceptanceStatus`](a.md#acceptancestatus) |  | 22 | uncategorized |
| [`AcceptanceStatusSegment`](a.md#acceptancestatussegment) |  | 8 | uncategorized |
| [`AccountInventory`](a.md#accountinventory) |  | 4 | gui |
| [`Achievement`](a.md#achievement) | Jomini Achievement | 3 | gui |
| [`AchievementPopup`](a.md#achievementpopup) |  | 4 | gui |
| [`AchievementWindow`](a.md#achievementwindow) | Jomini Achievement Window | 14 | gui |
| [`AddFriendWindow`](a.md#addfriendwindow) | Jomini Friends - Add Friends Window | 5 | gui |
| [`AddWarGoalPanel`](a.md#addwargoalpanel) |  | 15 | uncategorized |
| [`AgitatorSlot`](a.md#agitatorslot) |  | 5 | uncategorized |
| [`AIAttitude`](a.md#aiattitude) |  | 16 | uncategorized |
| [`AIStrategicRegionStanceType`](a.md#aistrategicregionstancetype) |  | 7 | uncategorized |
| [`AIStrategy`](a.md#aistrategy) |  | 7 | uncategorized |
| [`Alert`](a.md#alert) |  | 27 | uncategorized |
| [`AlertGroup`](a.md#alertgroup) |  | 3 | uncategorized |
| [`AlertOptionItem`](a.md#alertoptionitem) |  | 5 | uncategorized |
| [`AlertSettingsItem`](a.md#alertsettingsitem) |  | 7 | uncategorized |
| [`Amendment`](a.md#amendment) |  | 38 | uncategorized |
| [`AmendmentType`](a.md#amendmenttype) |  | 23 | uncategorized |
| [`AnchorItem`](a.md#anchoritem) | Map Editor - Spline Network Tool - Anchor | 11 | internalclausewitzgui |
| [`Application`](a.md#application) |  | 3 | common |
| [`Article`](a.md#article) |  | 67 | uncategorized |
| [`ArticleDraft`](a.md#articledraft) |  | 96 | uncategorized |
| [`ArticleType`](a.md#articletype) |  | 28 | uncategorized |
| [`Attribute`](a.md#attribute) | Portrait Editor - Attribute | 5 | internalclausewitzgui |
| [`AvailabilityEntry`](a.md#availabilityentry) | Jomini Friend List - Availibility Entry | 3 | gui |
| [`Battle`](b.md#battle) |  | 132 | uncategorized |
| [`BattleBuildingEntry`](b.md#battlebuildingentry) |  | 9 | uncategorized |
| [`BattleCondition`](b.md#battlecondition) |  | 9 | uncategorized |
| [`BattleLogEntry`](b.md#battlelogentry) |  | 45 | uncategorized |
| [`BattleMarker`](b.md#battlemarker) |  | 5 | uncategorized |
| [`BattleMilitaryFormation`](b.md#battlemilitaryformation) |  | 8 | uncategorized |
| [`BattlePanel`](b.md#battlepanel) |  | 4 | uncategorized |
| [`BattleParticipant`](b.md#battleparticipant) |  | 8 | uncategorized |
| [`BattleSide`](b.md#battleside) |  | 18 | uncategorized |
| [`BattleUnitType`](b.md#battleunittype) |  | 9 | uncategorized |
| [`BlurThreshold`](b.md#blurthreshold) | Map Editor - Blur Threshold | 5 | internalclausewitzgui |
| [`bool`](b.md#bool) |  | 2 | common |
| [`BrushBool`](b.md#brushbool) | Map Editor - Brush bool settings. | 5 | internalclausewitzgui |
| [`BrushFloat`](b.md#brushfloat) | Map Editor - Brush float settings. | 19 | internalclausewitzgui |
| [`BrushSettings`](b.md#brushsettings) | Map Editor - Brush settings. | 14 | internalclausewitzgui |
| [`BrushSettingsDropdown`](b.md#brushsettingsdropdown) | Map Editor - Brush settings dropdown. | 7 | internalclausewitzgui |
| [`BrushSettingsGlobal`](b.md#brushsettingsglobal) | Map Editor - Global Brush settings. | 5 | internalclausewitzgui |
| [`BudgetPanel`](b.md#budgetpanel) |  | 11 | uncategorized |
| [`Building`](b.md#building) |  | 296 | uncategorized |
| [`BuildingBrowserBuildingTypeItem`](b.md#buildingbrowserbuildingtypeitem) |  | 34 | uncategorized |
| [`BuildingBrowserPanel`](b.md#buildingbrowserpanel) |  | 42 | uncategorized |
| [`BuildingDetailsPanel`](b.md#buildingdetailspanel) |  | 10 | uncategorized |
| [`BuildingGroup`](b.md#buildinggroup) |  | 9 | uncategorized |
| [`BuildingMarker`](b.md#buildingmarker) |  | 7 | uncategorized |
| [`BuildingOwnership`](b.md#buildingownership) |  | 15 | uncategorized |
| [`BuildingPotentialMarker`](b.md#buildingpotentialmarker) |  | 9 | uncategorized |
| [`BuildingProductionMethodsEntry`](b.md#buildingproductionmethodsentry) |  | 20 | uncategorized |
| [`BuildingType`](b.md#buildingtype) |  | 88 | uncategorized |
| [`CFixedPoint`](c.md#cfixedpoint) | Number stored with 6 digits of precision. | 3 | common |
| [`ChangeLawPanel`](c.md#changelawpanel) |  | 7 | uncategorized |
| [`ChangeProductionMethodMenuItem`](c.md#changeproductionmethodmenuitem) |  | 11 | uncategorized |
| [`ChangeProductionMethodsMenuItems`](c.md#changeproductionmethodsmenuitems) |  | 3 | uncategorized |
| [`Character`](c.md#character) |  | 193 | uncategorized |
| [`CharacterFilter`](c.md#characterfilter) |  | 23 | uncategorized |
| [`CharacterInteraction`](c.md#characterinteraction) |  | 20 | uncategorized |
| [`CharacterPanel`](c.md#characterpanel) |  | 6 | uncategorized |
| [`CharacterRole`](c.md#characterrole) |  | 14 | uncategorized |
| [`CharacterTrait`](c.md#charactertrait) |  | 13 | uncategorized |
| [`Chat`](c.md#chat) | Jomini Chat - Chat | 9 | gui |
| [`ChatMessage`](c.md#chatmessage) | Jomini Chat - Message | 4 | gui |
| [`ChatNotificationMessage`](c.md#chatnotificationmessage) | Jomini Chat - Notification message | 6 | gui |
| [`ChatTab`](c.md#chattab) | Jomini Chat - Tab | 8 | gui |
| [`ChatWindow`](c.md#chatwindow) | Jomini Chat - Window | 8 | gui |
| [`ChildGenerator`](c.md#childgenerator) | Portrait Editor - Child Generator | 6 | internalclausewitzgui |
| [`ChildItem`](c.md#childitem) | Portrait Editor - Child Item | 7 | internalclausewitzgui |
| [`Cities`](c.md#cities) |  | 25 | uncategorized |
| [`CityMarker`](c.md#citymarker) |  | 9 | uncategorized |
| [`CivilWar`](c.md#civilwar) |  | 44 | uncategorized |
| [`CloudSaveData`](c.md#cloudsavedata) |  | 6 | uncategorized |
| [`CoatOfArms`](c.md#coatofarms) | Coat of Arms Sprite | 30 | gui |
| [`CoatOfArmsPreviewWindow`](c.md#coatofarmspreviewwindow) |  | 6 | uncategorized |
| [`CohesionLevel`](c.md#cohesionlevel) |  | 12 | uncategorized |
| [`ColonyMarker`](c.md#colonymarker) |  | 7 | uncategorized |
| [`ColorPicker`](c.md#colorpicker) |  | 4 | internalclausewitzgui |
| [`CombatShip`](c.md#combatship) |  | 15 | uncategorized |
| [`CombatUnit`](c.md#combatunit) |  | 55 | uncategorized |
| [`CombatUnitGroup`](c.md#combatunitgroup) |  | 8 | uncategorized |
| [`CombatUnitType`](c.md#combatunittype) |  | 24 | uncategorized |
| [`Command`](c.md#command) |  | 9 | uncategorized |
| [`CommanderOrderType`](c.md#commanderordertype) |  | 19 | uncategorized |
| [`CommanderRank`](c.md#commanderrank) |  | 7 | uncategorized |
| [`CompaniesPanel`](c.md#companiespanel) |  | 21 | uncategorized |
| [`Company`](c.md#company) |  | 77 | uncategorized |
| [`CompanyChangeNamePopup`](c.md#companychangenamepopup) |  | 6 | uncategorized |
| [`CompanyCharter`](c.md#companycharter) |  | 15 | uncategorized |
| [`CompanyCharterType`](c.md#companychartertype) |  | 19 | uncategorized |
| [`CompanyPanel`](c.md#companypanel) |  | 4 | uncategorized |
| [`CompanyType`](c.md#companytype) |  | 27 | uncategorized |
| [`ConfirmationWindow`](c.md#confirmationwindow) |  | 3 | uncategorized |
| [`ConsoleMenuItem`](c.md#consolemenuitem) | Console Menu Item | 6 | internalclausewitzgui |
| [`ConsoleWindow`](c.md#consolewindow) | Console Window | 4 | internalclausewitzgui |
| [`ConstructionPanel`](c.md#constructionpanel) |  | 39 | uncategorized |
| [`ConstructionQueueElement`](c.md#constructionqueueelement) |  | 38 | uncategorized |
| [`Container`](c.md#container) |  | 2 | script |
| [`ContextMenuItem`](c.md#contextmenuitem) | Tools Context Menu Item | 5 | internalclausewitzgui |
| [`ContextualDiplomaticActionType`](c.md#contextualdiplomaticactiontype) |  | 9 | uncategorized |
| [`ContextualDiplomaticPact`](c.md#contextualdiplomaticpact) |  | 16 | uncategorized |
| [`CountriesPanel`](c.md#countriespanel) |  | 5 | uncategorized |
| [`Country`](c.md#country) |  | 1137 | uncategorized |
| [`CountryCreation`](c.md#countrycreation) |  | 28 | uncategorized |
| [`CountryDefinition`](c.md#countrydefinition) |  | 17 | uncategorized |
| [`CountryEntry`](c.md#countryentry) | Country Entry | 3 | gui |
| [`CountryFormation`](c.md#countryformation) |  | 41 | uncategorized |
| [`CountryFormationPanel`](c.md#countryformationpanel) |  | 6 | uncategorized |
| [`CountryMarker`](c.md#countrymarker) |  | 3 | uncategorized |
| [`CountryPanel`](c.md#countrypanel) |  | 4 | uncategorized |
| [`CountryTrendPair`](c.md#countrytrendpair) |  | 5 | uncategorized |
| [`CPdxEnumValue`](c.md#cpdxenumvalue) |  | 7 | internalclausewitzgui |
| [`CPdxFloatRect`](c.md#cpdxfloatrect) | Rectangle within an 2D float space. | 3 | common |
| [`CPdxInputBindingSetting`](c.md#cpdxinputbindingsetting) | Jomini Settings - Rebindable Input Binding Setting | 2 | gui |
| [`CPdxIntRect`](c.md#cpdxintrect) | Rectangle within an 2D integer space. | 3 | common |
| [`CreateAccount`](c.md#createaccount) | Create Account View | 26 | gui |
| [`CreateSocialProfileWindow`](c.md#createsocialprofilewindow) | Jomini Social Profile - Create window | 11 | gui |
| [`CreditsWindow`](c.md#creditswindow) | Jomini Credits Window | 11 | gui |
| [`CString`](c.md#cstring) |  | 3 | common |
| [`CulturalCommunity`](c.md#culturalcommunity) |  | 14 | uncategorized |
| [`Culture`](c.md#culture) |  | 72 | uncategorized |
| [`CultureCasualtyStatistics`](c.md#culturecasualtystatistics) |  | 6 | uncategorized |
| [`CultureInfoPanel`](c.md#cultureinfopanel) |  | 11 | uncategorized |
| [`CurveEditor`](c.md#curveeditor) | Curve Editor | 4 | internalclausewitzgui |
| [`CurvePoint`](c.md#curvepoint) | Curve Editor - Curve Point | 3 | internalclausewitzgui |
| [`CUTF8String`](c.md#cutf8string) |  | 3 | common |
| [`CVector2f`](c.md#cvector2f) | Type containing two float numbers. | 3 | common |
| [`CVector2i`](c.md#cvector2i) | Type containing two integer numbers. | 3 | common |
| [`CVector3f`](c.md#cvector3f) | Type containing three float numbers. | 3 | common |
| [`CVector3i`](c.md#cvector3i) | Type containing three integer numbers. | 3 | common |
| [`CVector4f`](c.md#cvector4f) | Type containing four float numbers. | 3 | common |
| [`CVector4i`](c.md#cvector4i) | Type containing four integer numbers. | 3 | common |
| [`DataColorPicker`](d.md#datacolorpicker) |  | 5 | uncategorized |
| [`DataDynamicTrend`](d.md#datadynamictrend) |  | 2 | uncategorized |
| [`DataTrend`](d.md#datatrend) |  | 2 | uncategorized |
| [`DatatypesExplorer`](d.md#datatypesexplorer) |  | 15 | internalclausewitzgui |
| [`Date`](d.md#date) | Jomini Historical Date | 4 | common |
| [`Decision`](d.md#decision) |  | 10 | uncategorized |
| [`DecommissionSupplyShipsWindow`](d.md#decommissionsupplyshipswindow) |  | 7 | uncategorized |
| [`Decree`](d.md#decree) |  | 18 | uncategorized |
| [`DecreeMarker`](d.md#decreemarker) |  | 7 | uncategorized |
| [`DecreeType`](d.md#decreetype) |  | 15 | uncategorized |
| [`DefineProxyNodeWindow`](d.md#defineproxynodewindow) | Define proxy node window | 4 | internalclausewitzgui |
| [`DetailData`](d.md#detaildata) | Map Editor - Map texture details | 11 | internalclausewitzgui |
| [`DiplomaticAction`](d.md#diplomaticaction) |  | 121 | uncategorized |
| [`DiplomaticActionType`](d.md#diplomaticactiontype) |  | 40 | uncategorized |
| [`DiplomaticActionWindow`](d.md#diplomaticactionwindow) |  | 36 | uncategorized |
| [`DiplomaticCatalyst`](d.md#diplomaticcatalyst) |  | 17 | uncategorized |
| [`DiplomaticCatalystCategory`](d.md#diplomaticcatalystcategory) |  | 7 | uncategorized |
| [`DiplomaticCatalystType`](d.md#diplomaticcatalysttype) |  | 9 | uncategorized |
| [`DiplomaticDemand`](d.md#diplomaticdemand) |  | 17 | uncategorized |
| [`DiplomaticOverviewPanel`](d.md#diplomaticoverviewpanel) |  | 8 | uncategorized |
| [`DiplomaticPact`](d.md#diplomaticpact) |  | 26 | uncategorized |
| [`DiplomaticPlay`](d.md#diplomaticplay) |  | 181 | uncategorized |
| [`DiplomaticPlayConfirmation`](d.md#diplomaticplayconfirmation) |  | 42 | uncategorized |
| [`DiplomaticPlayPanel`](d.md#diplomaticplaypanel) |  | 6 | uncategorized |
| [`DiplomaticPlayType`](d.md#diplomaticplaytype) |  | 25 | uncategorized |
| [`DiplomaticRelations`](d.md#diplomaticrelations) |  | 15 | uncategorized |
| [`DiscriminationTrait`](d.md#discriminationtrait) |  | 12 | uncategorized |
| [`DiscriminationTraitGroup`](d.md#discriminationtraitgroup) |  | 9 | uncategorized |
| [`Dlc`](d.md#dlc) |  | 13 | uncategorized |
| [`DockableLayout`](d.md#dockablelayout) | Dockable Layout Manager - Layout | 3 | internalclausewitzgui |
| [`DockableLayoutManager`](d.md#dockablelayoutmanager) | Dockable Layout Manager Window | 13 | internalclausewitzgui |
| [`DockableWindow`](d.md#dockablewindow) | Dockable Window | 11 | internalclausewitzgui |
| [`double`](d.md#double) | Number stored with `double float` precision. | 2 | common |
| [`DrawCmdsList`](d.md#drawcmdslist) | Draw Commands List | 10 | internalclausewitzgui |
| [`DrawCmdsViewer`](d.md#drawcmdsviewer) | Draw Commands Viewer | 14 | internalclausewitzgui |
| [`EditorSettingCategory`](e.md#editorsettingcategory) | Editor Settings - Category | 3 | gui |
| [`EditorSettingsPage`](e.md#editorsettingspage) | Editor Settings - Settings Page | 6 | gui |
| [`EditorSettingsWindow`](e.md#editorsettingswindow) | Editor Settings Window | 17 | gui |
| [`Election`](e.md#election) |  | 21 | uncategorized |
| [`ElectionPanel`](e.md#electionpanel) |  | 4 | uncategorized |
| [`EmitterNodeWindow`](e.md#emitternodewindow) |  | 10 | uncategorized |
| [`EmployeeTransfer`](e.md#employeetransfer) |  | 10 | uncategorized |
| [`Encyclopedia`](e.md#encyclopedia) | Jomini Encyclopedia | 19 | gui |
| [`EncyclopediaEntry`](e.md#encyclopediaentry) | Jomini Encyclopedia - Entry | 8 | gui |
| [`EncyclopediaEntryView`](e.md#encyclopediaentryview) | Jomini Encyclopedia - Entry View | 4 | gui |
| [`EncyclopediaPage`](e.md#encyclopediapage) | Jomini Encyclopedia - Page | 6 | gui |
| [`EndPrepConfirm`](e.md#endprepconfirm) | Jomini Multiplayer - End preparation confirm | 4 | gui |
| [`EntityEditor`](e.md#entityeditor) | Entity Editor | 42 | internalclausewitzgui |
| [`EntityEditorAudioEventHandler`](e.md#entityeditoraudioeventhandler) | Entity Editor - Audio Event Handler | 4 | internalclausewitzgui |
| [`EntityEditorEventLayer`](e.md#entityeditoreventlayer) | Entity Editor - Entity Event Layer | 10 | internalclausewitzgui |
| [`EntityEditorKeyframe`](e.md#entityeditorkeyframe) | Entity Editor - Entity Key Frame | 11 | internalclausewitzgui |
| [`EntityEditorTimelineState`](e.md#entityeditortimelinestate) | Entity Editor - Timeline State | 5 | internalclausewitzgui |
| [`EntityViewerProperties`](e.md#entityviewerproperties) | Entity Editor - Properties | 15 | internalclausewitzgui |
| [`EnumSettingEntry`](e.md#enumsettingentry) | Jomini Settings - Enum Setting | 9 | gui |
| [`Era`](e.md#era) |  | 6 | uncategorized |
| [`ErrorDeer`](e.md#errordeer) |  | 7 | uncategorized |
| [`Ethnicity`](e.md#ethnicity) | Portrait System - Ethnicity | 4 | gui |
| [`EthnicityItem`](e.md#ethnicityitem) | Portrait Editor - Ethnicity Item | 3 | internalclausewitzgui |
| [`Event`](e.md#event) |  | 30 | uncategorized |
| [`EventIcon`](e.md#eventicon) |  | 9 | uncategorized |
| [`EventLayerForEntityEditor`](e.md#eventlayerforentityeditor) | Entity Editor - Entity Event Layer Keyframe | 6 | internalclausewitzgui |
| [`EventMarker`](e.md#eventmarker) |  | 8 | uncategorized |
| [`EventMarkerListItem`](e.md#eventmarkerlistitem) |  | 3 | uncategorized |
| [`EventOption`](e.md#eventoption) |  | 8 | uncategorized |
| [`EventTargetSetupContext`](e.md#eventtargetsetupcontext) |  | 4 | internalclausewitzgui |
| [`EventWindow`](e.md#eventwindow) |  | 11 | uncategorized |
| [`ExilePool`](e.md#exilepool) |  | 11 | uncategorized |
| [`ExportTool`](e.md#exporttool) | Map Editor - Export Tool Dockable | 18 | internalclausewitzgui |
| [`EyeDropper`](e.md#eyedropper) | Map Editor - Eye Dropper | 7 | internalclausewitzgui |
| [`EyeDropperPackedSample`](e.md#eyedropperpackedsample) | Map Editor - Packed Sample data for Eye Dropper | 4 | internalclausewitzgui |
| [`FeedMessageItem`](f.md#feedmessageitem) |  | 20 | uncategorized |
| [`FilterablePropertyList`](f.md#filterablepropertylist) |  | 7 | internalclausewitzgui |
| [`FleetFormationMarker`](f.md#fleetformationmarker) |  | 25 | uncategorized |
| [`float`](f.md#float) | Number stored with `float` precision. | 2 | common |
| [`FoodSecurity`](f.md#foodsecurity) |  | 15 | uncategorized |
| [`FoodSecurityFilter`](f.md#foodsecurityfilter) |  | 16 | uncategorized |
| [`FormationMarker`](f.md#formationmarker) |  | 28 | uncategorized |
| [`FormationPanel`](f.md#formationpanel) |  | 10 | uncategorized |
| [`Friend`](f.md#friend) | Jomini Friend List - Friend | 9 | gui |
| [`FriendListWindow`](f.md#friendlistwindow) | Jomini Friend List - Friendlist window | 6 | gui |
| [`FriendRequest`](f.md#friendrequest) | Jomini Friend List - FriendRequest | 5 | gui |
| [`Friends`](f.md#friends) | Jomini Friend List - Friends manager | 18 | gui |
| [`FriendSearchResult`](f.md#friendsearchresult) | Jomini Friends - Search Result | 4 | gui |
| [`Front`](f.md#front) |  | 43 | uncategorized |
| [`FrontEndCreditsView`](f.md#frontendcreditsview) | Jomini Frontend Credits View | 3 | gui |
| [`FrontEndLoadConfirmationWindow`](f.md#frontendloadconfirmationwindow) |  | 5 | uncategorized |
| [`FrontEndLoadView`](f.md#frontendloadview) |  | 21 | uncategorized |
| [`FrontEndMainView`](f.md#frontendmainview) |  | 13 | uncategorized |
| [`FrontEndMultiplayerView`](f.md#frontendmultiplayerview) | Jomini Multiplayer - Frontendview | 6 | gui |
| [`FrontMarker`](f.md#frontmarker) |  | 5 | uncategorized |
| [`FrontMovementMarker`](f.md#frontmovementmarker) |  | 17 | uncategorized |
| [`FrontPanel`](f.md#frontpanel) |  | 8 | uncategorized |
| [`FrontSide`](f.md#frontside) |  | 30 | uncategorized |
| [`GameConceptType`](g.md#gameconcepttype) |  | 13 | uncategorized |
| [`GameMpSetup`](g.md#gamempsetup) |  | 26 | uncategorized |
| [`GameOverScreen`](g.md#gameoverscreen) |  | 13 | uncategorized |
| [`GameRule`](g.md#gamerule) |  | 4 | uncategorized |
| [`GameRuleSetting`](g.md#gamerulesetting) |  | 8 | uncategorized |
| [`GameSetup`](g.md#gamesetup) |  | 15 | uncategorized |
| [`GeneCategory`](g.md#genecategory) | Portrait System - Gene Category | 4 | gui |
| [`GeneItem`](g.md#geneitem) | Portrait Editor - Gene Item | 3 | internalclausewitzgui |
| [`GeneralInformationWindow`](g.md#generalinformationwindow) |  | 4 | uncategorized |
| [`GenerationItem`](g.md#generationitem) | Portrait Editor - Generation Item | 3 | internalclausewitzgui |
| [`GeneTemplate`](g.md#genetemplate) | Portrait System - Gene Template | 3 | gui |
| [`GeographicRegion`](g.md#geographicregion) |  | 19 | uncategorized |
| [`GfxSkin`](g.md#gfxskin) | GFX Skin | 6 | internalclausewitzgui |
| [`Goods`](g.md#goods) |  | 226 | uncategorized |
| [`GoodsExpenseItem`](g.md#goodsexpenseitem) |  | 8 | uncategorized |
| [`GoodsList`](g.md#goodslist) |  | 10 | uncategorized |
| [`GoodsLocalPricesPanel`](g.md#goodslocalpricespanel) |  | 8 | uncategorized |
| [`GoodsPanel`](g.md#goodspanel) |  | 9 | uncategorized |
| [`GoodsPanelChildValue`](g.md#goodspanelchildvalue) |  | 4 | uncategorized |
| [`GoodsPanelValue`](g.md#goodspanelvalue) |  | 19 | uncategorized |
| [`GoodsProductionInfo`](g.md#goodsproductioninfo) |  | 10 | uncategorized |
| [`GoodsStatePanel`](g.md#goodsstatepanel) |  | 8 | uncategorized |
| [`GoodsUsagePanel`](g.md#goodsusagepanel) |  | 7 | uncategorized |
| [`GoodsWorldMarketPanel`](g.md#goodsworldmarketpanel) |  | 9 | uncategorized |
| [`GovernmentType`](g.md#governmenttype) |  | 8 | uncategorized |
| [`Graph`](g.md#graph) | Node Editor - Graph | 4 | internalclausewitzgui |
| [`GraphInterfaceNodeWindow`](g.md#graphinterfacenodewindow) |  | 3 | uncategorized |
| [`GraphPanel`](g.md#graphpanel) | Node Editor - Graph Panel | 49 | internalclausewitzgui |
| [`Group`](g.md#group) | Jomini Achievement Window - Group | 8 | gui |
| [`GUIAchievement`](g.md#guiachievement) | Jomini Achievement GUI | 12 | gui |
| [`GuiAnimationCurveEditor`](g.md#guianimationcurveeditor) | Dockable tool for editing gui animations as a curve graphs. | 4 | internalclausewitzgui |
| [`GuiAnimationCurveEditorControlPoint`](g.md#guianimationcurveeditorcontrolpoint) | A control point of a given curve editor line. | 5 | internalclausewitzgui |
| [`GuiAnimationCurveEditorLine`](g.md#guianimationcurveeditorline) | A single curve editor line instance. | 5 | internalclausewitzgui |
| [`GuiAnimationCurveEditorViewport`](g.md#guianimationcurveeditorviewport) | Gui Animation Curve Editor Viewport instance. | 3 | internalclausewitzgui |
| [`GuiAnimationEditor`](g.md#guianimationeditor) | Dockable tool for editing gui animations. | 29 | internalclausewitzgui |
| [`GuiAnimationEditorAnimationEntry`](g.md#guianimationeditoranimationentry) | An entry representing an animation for a given anim-set in the Gui Animation Editor. | 8 | internalclausewitzgui |
| [`GuiAnimationEditorAnimSetEntry`](g.md#guianimationeditoranimsetentry) | Animation-set list entry in the Gui Animation Editor tool. | 5 | internalclausewitzgui |
| [`GuiAnimationEditorAvailableTrack`](g.md#guianimationeditoravailabletrack) | An entry representing a track that is available to add to the given animation in the Gui Animation Editor tool. | 7 | internalclausewitzgui |
| [`GuiAnimationEditorKeyframe`](g.md#guianimationeditorkeyframe) | An entry representing a single keyframe on the track in the Gui Animation Editor. | 11 | internalclausewitzgui |
| [`GuiAnimationEditorMetadataCtx`](g.md#guianimationeditormetadatactx) | Tool metadata context of Gui Animation Editor. | 9 | internalclausewitzgui |
| [`GuiAnimationEditorPlayer`](g.md#guianimationeditorplayer) | Instance for managing the playback in Gui Animation Editor. | 22 | internalclausewitzgui |
| [`GuiAnimationEditorPlayerSpeedMultiplierEntry`](g.md#guianimationeditorplayerspeedmultiplierentry) | Playback Speed Multiplier Entry in Gui Animation Editor. | 4 | internalclausewitzgui |
| [`GuiAnimationEditorRuler`](g.md#guianimationeditorruler) | Viewport ruler in the Gui Animation Editor tool. | 4 | internalclausewitzgui |
| [`GuiAnimationEditorRulerResolutionEntry`](g.md#guianimationeditorrulerresolutionentry) | An entry representing a ruler resolution step in the Gui Animation Editor tool. | 5 | internalclausewitzgui |
| [`GuiAnimationEditorUniversalTrack`](g.md#guianimationeditoruniversaltrack) | An entry representing an animation for a given anim-set in the Gui Animation Editor. | 29 | internalclausewitzgui |
| [`GuiAnimationEditorViewportBase`](g.md#guianimationeditorviewportbase) | Base class for the different types of viewports in the GUI Animation Editor dockables | 3 | internalclausewitzgui |
| [`GuiAnimationEditorViewportUserInput`](g.md#guianimationeditorviewportuserinput) | Keeps track of the user input over viewports in the GUI Animation Editor dockables | 5 | internalclausewitzgui |
| [`GuiAnimationTimelineViewport`](g.md#guianimationtimelineviewport) | Gui Animation Editor Timeline Viewport instance. | 5 | internalclausewitzgui |
| [`GuiContext`](g.md#guicontext) | GUI Context | 3 | gui |
| [`GuiCurrentDrag`](g.md#guicurrentdrag) | For use in drag_widget, inside of draggable_behavior. Contains data regarding current ongoing drag, such as mouse positions | 4 | gui |
| [`GuiDataProfiler`](g.md#guidataprofiler) | Gui Data Profiler Window | 31 | internalclausewitzgui |
| [`GuiDataProfilerEntryNode`](g.md#guidataprofilerentrynode) | Gui Data Profiler tree entry node | 9 | internalclausewitzgui |
| [`GuiEditorTooltip`](g.md#guieditortooltip) | GUI Editor - Tooltip | 7 | internalclausewitzgui |
| [`GuiGameRule`](g.md#guigamerule) |  | 8 | uncategorized |
| [`GuiGameRulePreset`](g.md#guigamerulepreset) |  | 7 | uncategorized |
| [`HarvestCondition`](h.md#harvestcondition) |  | 19 | uncategorized |
| [`HarvestConditionArea`](h.md#harvestconditionarea) |  | 23 | uncategorized |
| [`HarvestConditionList`](h.md#harvestconditionlist) |  | 5 | uncategorized |
| [`HarvestConditionRegionMarker`](h.md#harvestconditionregionmarker) |  | 4 | uncategorized |
| [`HarvestConditionType`](h.md#harvestconditiontype) |  | 13 | uncategorized |
| [`Heightmap`](h.md#heightmap) | Map Editor - Heightmap | 3 | internalclausewitzgui |
| [`HeightmapPainter`](h.md#heightmappainter) | Map Editor - Heightmap Painter options panel | 6 | internalclausewitzgui |
| [`HeightmapPainterMode`](h.md#heightmappaintermode) | Map Editor - Heightmap Painter Mode | 3 | internalclausewitzgui |
| [`HeightmapResolution`](h.md#heightmapresolution) | Map Editor - Heightmap resolution tool | 14 | internalclausewitzgui |
| [`HighlightManager`](h.md#highlightmanager) |  | 36 | uncategorized |
| [`HistoryViewer`](h.md#historyviewer) |  | 7 | uncategorized |
| [`HomelandMarker`](h.md#homelandmarker) |  | 7 | uncategorized |
| [`Hq`](h.md#hq) |  | 21 | uncategorized |
| [`HQMarker`](h.md#hqmarker) |  | 3 | uncategorized |
| [`HQMovementMarker`](h.md#hqmovementmarker) |  | 16 | uncategorized |
| [`Ideology`](i.md#ideology) |  | 17 | uncategorized |
| [`Importable`](i.md#importable) | Map Editor - Importable items within a ImportableGroup | 5 | internalclausewitzgui |
| [`ImportableGroup`](i.md#importablegroup) | Map Editor - Importable Group | 12 | internalclausewitzgui |
| [`ImportantAlert`](i.md#importantalert) |  | 17 | uncategorized |
| [`ImportTool`](i.md#importtool) | Map Editor - Import Tool Window | 16 | internalclausewitzgui |
| [`InfoboxNodeWindow`](i.md#infoboxnodewindow) | Node Editor - Infobox Node Window | 3 | internalclausewitzgui |
| [`InformationPanel`](i.md#informationpanel) |  | 4 | uncategorized |
| [`InformationPanelBar`](i.md#informationpanelbar) |  | 81 | uncategorized |
| [`IngameHud`](i.md#ingamehud) |  | 2 | uncategorized |
| [`InputActionBinding`](i.md#inputactionbinding) | Input Context Manager - Input Action | 2 | gui |
| [`InspectorPanel`](i.md#inspectorpanel) | Map Editor - Spline Network Tool - Anchor Inspector Panel | 5 | internalclausewitzgui |
| [`Institution`](i.md#institution) |  | 40 | uncategorized |
| [`InstitutionInvestmentLevel`](i.md#institutioninvestmentlevel) |  | 9 | uncategorized |
| [`InstitutionType`](i.md#institutiontype) |  | 13 | uncategorized |
| [`int16`](i.md#int16) |  | 3 | common |
| [`int32`](i.md#int32) |  | 3 | common |
| [`int64`](i.md#int64) |  | 3 | common |
| [`int8`](i.md#int8) |  | 3 | common |
| [`Interest`](i.md#interest) |  | 14 | uncategorized |
| [`InterestGroup`](i.md#interestgroup) |  | 122 | uncategorized |
| [`InterestGroupAndTraitPair`](i.md#interestgroupandtraitpair) |  | 8 | uncategorized |
| [`InterestGroupMarker`](i.md#interestgroupmarker) |  | 7 | uncategorized |
| [`InterestGroupPanel`](i.md#interestgrouppanel) |  | 9 | uncategorized |
| [`InterestGroupTrait`](i.md#interestgrouptrait) |  | 16 | uncategorized |
| [`InterestingCountryItem`](i.md#interestingcountryitem) |  | 7 | uncategorized |
| [`InterestingCountrySetting`](i.md#interestingcountrysetting) |  | 4 | uncategorized |
| [`InterestTierType`](i.md#interesttiertype) |  | 25 | uncategorized |
| [`Invasion`](i.md#invasion) |  | 90 | uncategorized |
| [`InvasionMarker`](i.md#invasionmarker) |  | 5 | uncategorized |
| [`InvasionPanel`](i.md#invasionpanel) |  | 3 | uncategorized |
| [`InvasionPlannerPopup`](i.md#invasionplannerpopup) |  | 44 | uncategorized |
| [`JominiGameRules`](j.md#jominigamerules) |  | 29 | uncategorized |
| [`JominiGUISetting`](j.md#jominiguisetting) | Jomini Setting | 6 | gui |
| [`JominiNotification`](j.md#jomininotification) | Jomini Notification Item | 17 | gui |
| [`JominiNotificationOverlay`](j.md#jomininotificationoverlay) |  | 10 | gui |
| [`JominiPasswordPopup`](j.md#jominipasswordpopup) | Jomini Multiplayer - Password Popup | 4 | gui |
| [`JominiServer`](j.md#jominiserver) | Jomini Multiplayer - Server | 10 | gui |
| [`JominiServerBrowserGui`](j.md#jominiserverbrowsergui) | Jomini Multiplayer - Server Browser | 26 | gui |
| [`JominiSettingsWindow`](j.md#jominisettingswindow) | Jomini Settings Window | 35 | gui |
| [`JournalEntry`](j.md#journalentry) |  | 77 | uncategorized |
| [`JournalEntryGroup`](j.md#journalentrygroup) |  | 7 | uncategorized |
| [`JournalEntryPanel`](j.md#journalentrypanel) |  | 6 | uncategorized |
| [`JournalEntryType`](j.md#journalentrytype) |  | 9 | uncategorized |
| [`JournalPanel`](j.md#journalpanel) |  | 2 | uncategorized |
| [`KeyframeEditor`](k.md#keyframeeditor) | GUI Editor - Keyframe Editor | 3 | internalclausewitzgui |
| [`KeyframeEventEditor`](k.md#keyframeeventeditor) | Entity Editor - Event Editor | 9 | internalclausewitzgui |
| [`KeyframeWidget`](k.md#keyframewidget) | GUI Editor - Keyframe | 3 | internalclausewitzgui |
| [`Label`](l.md#label) |  | 6 | uncategorized |
| [`LabelingHelper`](l.md#labelinghelper) |  | 38 | uncategorized |
| [`Law`](l.md#law) |  | 122 | uncategorized |
| [`LawGroup`](l.md#lawgroup) |  | 16 | uncategorized |
| [`LawType`](l.md#lawtype) |  | 22 | uncategorized |
| [`Layer`](l.md#layer) | Map Editor - Map Object Layer | 2 | internalclausewitzgui |
| [`LayerTreeItem`](l.md#layertreeitem) | Map Editor - Map Object Layer Tree Item | 16 | internalclausewitzgui |
| [`LegalDocsViewer`](l.md#legaldocsviewer) | Legal Documents Viewer | 6 | gui |
| [`LegitimacyLevel`](l.md#legitimacylevel) |  | 13 | uncategorized |
| [`LensOption`](l.md#lensoption) |  | 23 | uncategorized |
| [`LensTab`](l.md#lenstab) |  | 9 | uncategorized |
| [`LensToolbar`](l.md#lenstoolbar) |  | 15 | uncategorized |
| [`LibertyDesireLevel`](l.md#libertydesirelevel) |  | 12 | uncategorized |
| [`LoadIngameWindow`](l.md#loadingamewindow) |  | 13 | uncategorized |
| [`LoadingScreenManager`](l.md#loadingscreenmanager) |  | 8 | uncategorized |
| [`LobbyPlayer`](l.md#lobbyplayer) | Jomini Multiplayer - Lobby Player | 17 | gui |
| [`LobbyView`](l.md#lobbyview) | Multiplayer GUI - Lobby View | 62 | gui |
| [`Location`](l.md#location) |  | 6 | uncategorized |
| [`LocationFinder`](l.md#locationfinder) |  | 4 | uncategorized |
| [`LogEntry`](l.md#logentry) | Texture Importer - Log Entry | 5 | internalclausewitzgui |
| [`LoginView`](l.md#loginview) | Login View | 26 | gui |
| [`LogViewer`](l.md#logviewer) | Log Viewer Window | 23 | internalclausewitzgui |
| [`LogViewerCategory`](l.md#logviewercategory) | Log Viewer - Log Category | 7 | internalclausewitzgui |
| [`LogViewerEntry`](l.md#logviewerentry) | Log Viewer - Log Entry | 16 | internalclausewitzgui |
| [`LogViewerType`](l.md#logviewertype) | Log Viewer - Log Entry Type | 8 | internalclausewitzgui |
| [`LoyaltyType`](l.md#loyaltytype) |  | 10 | uncategorized |
| [`MapContentEditorMode`](m.md#mapcontenteditormode) | Map Editor - Map Content Editor Mode | 3 | internalclausewitzgui |
| [`MapContentEditorOptions`](m.md#mapcontenteditoroptions) | Map Editor - Map Content Options Window | 31 | internalclausewitzgui |
| [`MapContentEditorViewport`](m.md#mapcontenteditorviewport) | Map Editor - Map Content Viewport | 6 | internalclausewitzgui |
| [`MapContentEntryDesc`](m.md#mapcontententrydesc) | Map Editor - Map Content Layer Entry | 8 | internalclausewitzgui |
| [`MapContentLayerDesc`](m.md#mapcontentlayerdesc) | Map Editor - Map Content Layer | 3 | internalclausewitzgui |
| [`MapContentPanel`](m.md#mapcontentpanel) | Map Editor - Map Content Layer List | 8 | internalclausewitzgui |
| [`MapContentPropertyGroup`](m.md#mapcontentpropertygroup) | Map Editor - Map Content Property Group | 5 | internalclausewitzgui |
| [`MapContentPropertyGroupsGui`](m.md#mapcontentpropertygroupsgui) |  | 21 | uncategorized |
| [`MapContentSelector`](m.md#mapcontentselector) | Map Editor - Map Content Selection | 9 | internalclausewitzgui |
| [`MapContentSelectorGui`](m.md#mapcontentselectorgui) | Map Editor - Map Content Selection Interface | 17 | internalclausewitzgui |
| [`MapEditor`](m.md#mapeditor) | Map Editor - Main | 24 | internalclausewitzgui |
| [`MapEditorGui`](m.md#mapeditorgui) | Map Editor - Main GUI | 9 | internalclausewitzgui |
| [`MapEditorLayerBorder`](m.md#mapeditorlayerborder) | Map Editor - Map Editor Layer Border | 5 | internalclausewitzgui |
| [`MapEditorLayerBorderDockable`](m.md#mapeditorlayerborderdockable) | Map Editor - Map Editor Layer Border Settings Window | 3 | internalclausewitzgui |
| [`MapInteraction`](m.md#mapinteraction) |  | 2 | uncategorized |
| [`MapInteractionManager`](m.md#mapinteractionmanager) |  | 6 | uncategorized |
| [`MapListActivateConscriptionCenterOption`](m.md#maplistactivateconscriptioncenteroption) |  | 10 | uncategorized |
| [`MapListActivateConscriptionCenterPanel`](m.md#maplistactivateconscriptioncenterpanel) |  | 2 | uncategorized |
| [`MapListBuildingOption`](m.md#maplistbuildingoption) |  | 17 | uncategorized |
| [`MapListBuildingPanel`](m.md#maplistbuildingpanel) |  | 6 | uncategorized |
| [`MapListColonyOption`](m.md#maplistcolonyoption) |  | 6 | uncategorized |
| [`MapListCountriesPanel`](m.md#maplistcountriespanel) |  | 2 | uncategorized |
| [`MapListCountryOption`](m.md#maplistcountryoption) |  | 3 | uncategorized |
| [`MapListDecreeOption`](m.md#maplistdecreeoption) |  | 5 | uncategorized |
| [`MapListDecreePanel`](m.md#maplistdecreepanel) |  | 4 | uncategorized |
| [`MapListDeployMilitaryFormationToFrontOption`](m.md#maplistdeploymilitaryformationtofrontoption) |  | 4 | uncategorized |
| [`MapListDeployMilitaryFormationToFrontPanel`](m.md#maplistdeploymilitaryformationtofrontpanel) |  | 2 | uncategorized |
| [`MapListDiploActionOption`](m.md#maplistdiploactionoption) |  | 6 | uncategorized |
| [`MapListHarvestConditionAreasPanel`](m.md#maplistharvestconditionareaspanel) |  | 2 | uncategorized |
| [`MapListHarvestConditionOption`](m.md#maplistharvestconditionoption) |  | 4 | uncategorized |
| [`MapListInterestGroupOption`](m.md#maplistinterestgroupoption) |  | 6 | uncategorized |
| [`MapListInterestGroupsPanel`](m.md#maplistinterestgroupspanel) |  | 2 | uncategorized |
| [`MapListMarketOption`](m.md#maplistmarketoption) |  | 6 | uncategorized |
| [`MapListMarketsPanel`](m.md#maplistmarketspanel) |  | 2 | uncategorized |
| [`MapListMilitaryFormationOption`](m.md#maplistmilitaryformationoption) |  | 9 | uncategorized |
| [`MapListMilitaryFormationPanel`](m.md#maplistmilitaryformationpanel) |  | 2 | uncategorized |
| [`MapListNavalMissionOption`](m.md#maplistnavalmissionoption) |  | 9 | uncategorized |
| [`MapListNavalMissionPanel`](m.md#maplistnavalmissionpanel) |  | 2 | uncategorized |
| [`MapListOption`](m.md#maplistoption) |  | 36 | uncategorized |
| [`MapListPanel`](m.md#maplistpanel) |  | 8 | uncategorized |
| [`MapListPanelManager`](m.md#maplistpanelmanager) |  | 13 | uncategorized |
| [`MapListPowerBlocInvitationPanel`](m.md#maplistpowerblocinvitationpanel) |  | 6 | uncategorized |
| [`MapListPowerBlocOption`](m.md#maplistpowerblocoption) |  | 6 | uncategorized |
| [`MapListPowerBlocsPanel`](m.md#maplistpowerblocspanel) |  | 4 | uncategorized |
| [`MapListStateOption`](m.md#mapliststateoption) |  | 6 | uncategorized |
| [`MapListStatePanel`](m.md#mapliststatepanel) |  | 2 | uncategorized |
| [`MapListStrategicRegionOption`](m.md#mapliststrategicregionoption) |  | 6 | uncategorized |
| [`MapListStrategicRegionsPanel`](m.md#mapliststrategicregionspanel) |  | 2 | uncategorized |
| [`MapMode`](m.md#mapmode) |  | 5 | uncategorized |
| [`MapModeList`](m.md#mapmodelist) |  | 10 | uncategorized |
| [`MapNotification`](m.md#mapnotification) |  | 3 | uncategorized |
| [`MapObjectMask`](m.md#mapobjectmask) | Map Editor - Map Object Mask | 12 | internalclausewitzgui |
| [`MapObjectPainter`](m.md#mapobjectpainter) | Map Editor - Map Object Painter | 5 | internalclausewitzgui |
| [`MapObjectPainterMode`](m.md#mapobjectpaintermode) | Map Editor - Map Object Painter Mode | 3 | internalclausewitzgui |
| [`MapObjectPainterOptions`](m.md#mapobjectpainteroptions) | Map Editor - Map Object Painter Options | 9 | internalclausewitzgui |
| [`MapObjectTool`](m.md#mapobjecttool) | Map Editor - Map Object Tool | 18 | internalclausewitzgui |
| [`Market`](m.md#market) |  | 78 | uncategorized |
| [`MarketGoods`](m.md#marketgoods) |  | 12 | uncategorized |
| [`MarketPanel`](m.md#marketpanel) |  | 11 | uncategorized |
| [`MarketsMarker`](m.md#marketsmarker) |  | 8 | uncategorized |
| [`MarketsMarkerListItem`](m.md#marketsmarkerlistitem) |  | 4 | uncategorized |
| [`MaskEntry`](m.md#maskentry) | Map Editor - Texture Mask | 3 | internalclausewitzgui |
| [`MaskManagerEntry`](m.md#maskmanagerentry) | Map Editor - Mask Painter - Mask Entry | 7 | internalclausewitzgui |
| [`MaskPainterDynamicTerrain`](m.md#maskpainterdynamicterrain) |  | 9 | uncategorized |
| [`MaskPainterManager`](m.md#maskpaintermanager) | Map Editor - Mask Painter Manager | 18 | internalclausewitzgui |
| [`MaskPainterMapContentPanel`](m.md#maskpaintermapcontentpanel) | Map Editor - Mask Painter Map Content Window | 2 | internalclausewitzgui |
| [`MaskPainterMode`](m.md#maskpaintermode) | Map Editor - Mask Painter mode | 3 | internalclausewitzgui |
| [`MaskPainterTool`](m.md#maskpaintertool) | Map Editor - Mask Painter Tool | 10 | internalclausewitzgui |
| [`MaskPainterViewport`](m.md#maskpainterviewport) | Map Editor - Mask Painter Viewport | 3 | internalclausewitzgui |
| [`Material`](m.md#material) | Map Editor - Material Painter - Material | 11 | internalclausewitzgui |
| [`MaterialBrowser`](m.md#materialbrowser) | Map Editor - Material Browser | 12 | internalclausewitzgui |
| [`MaterialEntry`](m.md#materialentry) | Map Editor - Material Entry | 6 | internalclausewitzgui |
| [`MaterialMix`](m.md#materialmix) | Map Editor - Material Mix | 10 | internalclausewitzgui |
| [`MaterialMixBrush`](m.md#materialmixbrush) | Map Editor - Material Mix Brush | 15 | internalclausewitzgui |
| [`MaterialMixEntry`](m.md#materialmixentry) | Map Editor - Material Mix | 10 | internalclausewitzgui |
| [`MaterialPaintingMode`](m.md#materialpaintingmode) | Map Editor - Map texture material painting mode | 22 | internalclausewitzgui |
| [`Materials`](m.md#materials) | Map Editor - Material Painter - Materials | 10 | internalclausewitzgui |
| [`MaterialsSample`](m.md#materialssample) | Map Editor - Materials Sample | 5 | internalclausewitzgui |
| [`MeshImporter`](m.md#meshimporter) | Mesh Importer Window | 25 | internalclausewitzgui |
| [`MeshImporterBrowser`](m.md#meshimporterbrowser) | Mesh Importer Browser Window | 9 | internalclausewitzgui |
| [`MeshImporterBrowserEntry`](m.md#meshimporterbrowserentry) | Mesh Importer Browser File Entry | 11 | internalclausewitzgui |
| [`MeshImporterMaterialEntry`](m.md#meshimportermaterialentry) |  | 9 | gui |
| [`MeshImporterMaterials`](m.md#meshimportermaterials) |  | 4 | gui |
| [`MessageFeedHandler`](m.md#messagefeedhandler) |  | 7 | uncategorized |
| [`MessageSettingsWindow`](m.md#messagesettingswindow) |  | 18 | uncategorized |
| [`MetadataWindow`](m.md#metadatawindow) | Window to edit metadata of selected nodes. | 8 | internalclausewitzgui |
| [`MilitaryFormation`](m.md#militaryformation) |  | 385 | uncategorized |
| [`MilitaryFormationBorrowSetting`](m.md#militaryformationborrowsetting) |  | 7 | uncategorized |
| [`MilitaryFormationChangeNamePopup`](m.md#militaryformationchangenamepopup) |  | 20 | uncategorized |
| [`MilitaryFormationColor`](m.md#militaryformationcolor) |  | 3 | uncategorized |
| [`MilitaryFormationFlag`](m.md#militaryformationflag) |  | 6 | uncategorized |
| [`MilitaryFormationUnitEntry`](m.md#militaryformationunitentry) |  | 18 | uncategorized |
| [`MilitaryFormationWrapped`](m.md#militaryformationwrapped) |  | 8 | uncategorized |
| [`MilitaryPanelBuildingEntry`](m.md#militarypanelbuildingentry) |  | 6 | uncategorized |
| [`MixBrushMode`](m.md#mixbrushmode) | Map Editor - Material painter mix brush mode | 3 | internalclausewitzgui |
| [`MobilizationOption`](m.md#mobilizationoption) |  | 35 | uncategorized |
| [`MobilizationOptionGroup`](m.md#mobilizationoptiongroup) |  | 11 | uncategorized |
| [`Modifier`](m.md#modifier) |  | 60 | uncategorized |
| [`ModifierBreakdown`](m.md#modifierbreakdown) |  | 14 | uncategorized |
| [`ModifierEntry`](m.md#modifierentry) |  | 9 | uncategorized |
| [`ModifierNodeData`](m.md#modifiernodedata) |  | 7 | uncategorized |
| [`ModifierNodeDebuggerView`](m.md#modifiernodedebuggerview) |  | 4 | uncategorized |
| [`ModifierNodeDetailsView`](m.md#modifiernodedetailsview) |  | 4 | uncategorized |
| [`ModifierNodeGraphItem`](m.md#modifiernodegraphitem) |  | 7 | uncategorized |
| [`ModifierNodeGraphLine`](m.md#modifiernodegraphline) |  | 12 | uncategorized |
| [`ModifierNodeListView`](m.md#modifiernodelistview) |  | 4 | uncategorized |
| [`ModifiersPanel`](m.md#modifierspanel) |  | 5 | uncategorized |
| [`MoveTool`](m.md#movetool) | Map Editor - Map Object - Move Tool | 2 | internalclausewitzgui |
| [`MPConfig`](m.md#mpconfig) | Jomini Multiplayer - Configuration | 15 | gui |
| [`MultiplayerSetupWindow`](m.md#multiplayersetupwindow) | Jomini Multiplayer - Setup window | 11 | gui |
| [`MultiplayerSynchronizationInfo`](m.md#multiplayersynchronizationinfo) |  | 3 | uncategorized |
| [`MusicPlayer`](m.md#musicplayer) |  | 30 | gui |
| [`MusicPlayerCategory`](m.md#musicplayercategory) |  | 9 | gui |
| [`MusicTrack`](m.md#musictrack) |  | 6 | gui |
| [`NationalAwakeningMarker`](n.md#nationalawakeningmarker) |  | 4 | uncategorized |
| [`NationalizeBuildingGroup`](n.md#nationalizebuildinggroup) |  | 19 | uncategorized |
| [`NationalizeBuildingTypeGroup`](n.md#nationalizebuildingtypegroup) |  | 7 | uncategorized |
| [`NationalizeBuildingWindow`](n.md#nationalizebuildingwindow) |  | 24 | uncategorized |
| [`NavalBattle`](n.md#navalbattle) |  | 82 | uncategorized |
| [`NavalBattleCondition`](n.md#navalbattlecondition) |  | 10 | uncategorized |
| [`NavalBattleMarker`](n.md#navalbattlemarker) |  | 5 | uncategorized |
| [`NavalBattlePanel`](n.md#navalbattlepanel) |  | 12 | uncategorized |
| [`NavalBattleParticipant`](n.md#navalbattleparticipant) |  | 5 | uncategorized |
| [`NavalBattleShipTemplateGroup`](n.md#navalbattleshiptemplategroup) |  | 9 | uncategorized |
| [`NavalBattleSide`](n.md#navalbattleside) |  | 80 | uncategorized |
| [`NavalMission`](n.md#navalmission) |  | 15 | uncategorized |
| [`NavalMissionMarker`](n.md#navalmissionmarker) |  | 24 | uncategorized |
| [`NavalMissionType`](n.md#navalmissiontype) |  | 17 | uncategorized |
| [`Node`](n.md#node) | Node Editor - Node | 16 | internalclausewitzgui |
| [`NodeEditorSearch`](n.md#nodeeditorsearch) |  | 12 | uncategorized |
| [`NodeError`](n.md#nodeerror) | Node Editor - Node Error | 5 | internalclausewitzgui |
| [`NodeLine`](n.md#nodeline) | Node Editor - Node Line | 13 | internalclausewitzgui |
| [`NodePin`](n.md#nodepin) | Node Editor - Node Pin | 10 | internalclausewitzgui |
| [`NodeWindow`](n.md#nodewindow) | Node Editor - Node Window | 6 | internalclausewitzgui |
| [`NonRegisteredDockable`](n.md#nonregistereddockable) | NonRegistered Dockable Window | 3 | internalclausewitzgui |
| [`NotificationDummyContext`](n.md#notificationdummycontext) | Jomini Notification Dummy Context | 2 | gui |
| [`NotificationOptionItem`](n.md#notificationoptionitem) |  | 5 | uncategorized |
| [`NotificationSettingsItem`](n.md#notificationsettingsitem) |  | 10 | uncategorized |
| [`Nudger`](n.md#nudger) | Map Editor - Map Object Manager (Nudger) | 24 | internalclausewitzgui |
| [`NudgerLayerEntryMapObjectDesc`](n.md#nudgerlayerentrymapobjectdesc) | Map Editor - Map Object - Map Content Entry | 8 | internalclausewitzgui |
| [`NudgerMapContentGui`](n.md#nudgermapcontentgui) | Map Editor - Map Object - Map Content Window | 10 | internalclausewitzgui |
| [`NudgerMapObjectPropertyListDockable`](n.md#nudgermapobjectpropertylistdockable) | Map Editor - Map Object | 5 | internalclausewitzgui |
| [`NudgerMode`](n.md#nudgermode) | Map Editor - Map Object Mode | 3 | internalclausewitzgui |
| [`ObjectBrowser`](o.md#objectbrowser) | Object Explorer - Browser | 29 | internalclausewitzgui |
| [`ObjectBrowserView`](o.md#objectbrowserview) | Object Explorer - View | 3 | internalclausewitzgui |
| [`ObjectInspector`](o.md#objectinspector) | Object Explorer - Inspector | 5 | internalclausewitzgui |
| [`ObjectInspectorDockable`](o.md#objectinspectordockable) | Object Explorer - Inspector Window | 4 | internalclausewitzgui |
| [`ObjectInspectorPlugin`](o.md#objectinspectorplugin) | Object Explorer - Inspector Plugin | 5 | internalclausewitzgui |
| [`Objective`](o.md#objective) |  | 14 | uncategorized |
| [`ObjectiveType`](o.md#objectivetype) |  | 19 | uncategorized |
| [`ObjectPreset`](o.md#objectpreset) | Object Explorer - Preset | 4 | internalclausewitzgui |
| [`ObjectProvider`](o.md#objectprovider) | Object Explorer - Provider | 4 | internalclausewitzgui |
| [`ObstinanceMarker`](o.md#obstinancemarker) |  | 4 | uncategorized |
| [`OccupationPiechartData`](o.md#occupationpiechartdata) |  | 6 | uncategorized |
| [`OosData`](o.md#oosdata) | Jomini Multiplayer - Out-of-sync data | 9 | gui |
| [`OosWindow`](o.md#ooswindow) | Jomini Multiplayer - Out-of-sync window | 9 | gui |
| [`OpinionMarker`](o.md#opinionmarker) |  | 5 | uncategorized |
| [`OutgoingFriendRequest`](o.md#outgoingfriendrequest) | Jomini Friend List - Outgoing friend request | 4 | gui |
| [`Outliner`](o.md#outliner) |  | 4 | uncategorized |
| [`OutlinerEntry`](o.md#outlinerentry) |  | 20 | uncategorized |
| [`OutputEntry`](o.md#outputentry) | Texture Importer - Output Entry | 7 | internalclausewitzgui |
| [`PanelMilitary`](p.md#panelmilitary) |  | 11 | uncategorized |
| [`ParametricSelect`](p.md#parametricselect) | Map Editor - Heightmap Parameter Window | 10 | internalclausewitzgui |
| [`ParticleUserData`](p.md#particleuserdata) |  | 9 | uncategorized |
| [`Party`](p.md#party) |  | 35 | uncategorized |
| [`PartyPanel`](p.md#partypanel) |  | 6 | uncategorized |
| [`PastBattleMarker`](p.md#pastbattlemarker) |  | 5 | uncategorized |
| [`PastNavalBattleMarker`](p.md#pastnavalbattlemarker) |  | 5 | uncategorized |
| [`PauseMenu`](p.md#pausemenu) |  | 13 | uncategorized |
| [`PdxAccount`](p.md#pdxaccount) |  | 9 | gui |
| [`PdxCoreSetting`](p.md#pdxcoresetting) | Settings Window - Core Setting | 4 | internalclausewitzgui |
| [`PdxEnumSetting`](p.md#pdxenumsetting) | Settings Window - Enum Setting | 3 | internalclausewitzgui |
| [`PdxGuiFoldOut`](p.md#pdxguifoldout) | Foldable Item | 8 | gui |
| [`PdxGuiGfxVideoControl`](p.md#pdxguigfxvideocontrol) |  | 9 | gui |
| [`PdxGuiTableRow`](p.md#pdxguitablerow) | Generic Tree Table - Row | 3 | gui |
| [`PdxGuiTreeTable`](p.md#pdxguitreetable) | Generic Tree-Table | 10 | gui |
| [`PdxGuiWidget`](p.md#pdxguiwidget) | GUI Widget | 28 | gui |
| [`PdxSetting`](p.md#pdxsetting) | Settings Window - Setting | 8 | internalclausewitzgui |
| [`PdxSettingsWindow`](p.md#pdxsettingswindow) | Settings Window | 10 | internalclausewitzgui |
| [`PdxSettingsWindowCategory`](p.md#pdxsettingswindowcategory) | Settings Window - Category | 3 | internalclausewitzgui |
| [`PdxValueSetting`](p.md#pdxvaluesetting) | Settings Window - Value Setting | 5 | internalclausewitzgui |
| [`PieTimer`](p.md#pietimer) |  | 4 | uncategorized |
| [`PieTimerSlice`](p.md#pietimerslice) |  | 4 | uncategorized |
| [`Playable`](p.md#playable) | Jomini Playable | 4 | common |
| [`Player`](p.md#player) |  | 12 | uncategorized |
| [`PlayerJoinRequest`](p.md#playerjoinrequest) | Jomini Multiplayer - Player Join Request | 7 | gui |
| [`PlayerMessageItem`](p.md#playermessageitem) |  | 32 | uncategorized |
| [`PlotLine`](p.md#plotline) |  | 8 | gui |
| [`PoliticalLobby`](p.md#politicallobby) |  | 32 | uncategorized |
| [`PoliticalLobbyAppeasementFactor`](p.md#politicallobbyappeasementfactor) |  | 7 | uncategorized |
| [`PoliticalLobbyMarker`](p.md#politicallobbymarker) |  | 7 | uncategorized |
| [`PoliticalLobbyPanel`](p.md#politicallobbypanel) |  | 4 | uncategorized |
| [`PoliticalLobbyType`](p.md#politicallobbytype) |  | 10 | uncategorized |
| [`PoliticalMovement`](p.md#politicalmovement) |  | 72 | uncategorized |
| [`PoliticalMovementCategory`](p.md#politicalmovementcategory) |  | 9 | uncategorized |
| [`PoliticalMovementPanel`](p.md#politicalmovementpanel) |  | 4 | uncategorized |
| [`PoliticalMovementPopSupportFactor`](p.md#politicalmovementpopsupportfactor) |  | 4 | uncategorized |
| [`PoliticalMovementType`](p.md#politicalmovementtype) |  | 13 | uncategorized |
| [`PoliticsPanel`](p.md#politicspanel) |  | 17 | uncategorized |
| [`Pop`](p.md#pop) |  | 154 | uncategorized |
| [`PopBrowserPanel`](p.md#popbrowserpanel) |  | 66 | uncategorized |
| [`PopConsumptionGoods`](p.md#popconsumptiongoods) |  | 10 | uncategorized |
| [`PopDetailsPanel`](p.md#popdetailspanel) |  | 4 | uncategorized |
| [`PopList`](p.md#poplist) |  | 25 | uncategorized |
| [`PopListItem`](p.md#poplistitem) |  | 26 | uncategorized |
| [`PopNeed`](p.md#popneed) |  | 18 | uncategorized |
| [`PopsOverviewPanel`](p.md#popsoverviewpanel) |  | 29 | uncategorized |
| [`PopType`](p.md#poptype) |  | 42 | uncategorized |
| [`PopulationGrouping`](p.md#populationgrouping) |  | 9 | uncategorized |
| [`PopupManager`](p.md#popupmanager) |  | 68 | uncategorized |
| [`PopWithIG`](p.md#popwithig) |  | 9 | uncategorized |
| [`Portrait3dView`](p.md#portrait3dview) | Portrait Editor - 3D view window | 6 | internalclausewitzgui |
| [`PortraitDataContext`](p.md#portraitdatacontext) | Portrait Editor - Portrait Data | 3 | internalclausewitzgui |
| [`PortraitEditorAnimationItem`](p.md#portraiteditoranimationitem) | Portrait Editor - Animation Item | 3 | internalclausewitzgui |
| [`PortraitEditorWindow`](p.md#portraiteditorwindow) | Portrait Editor Window | 75 | internalclausewitzgui |
| [`PortraitTooltip`](p.md#portraittooltip) | Portrait Tooltip | 2 | gui |
| [`PotentialLeaderIdeology`](p.md#potentialleaderideology) |  | 8 | uncategorized |
| [`PowerBloc`](p.md#powerbloc) |  | 113 | uncategorized |
| [`PowerBlocCoaPiece`](p.md#powerbloccoapiece) |  | 9 | uncategorized |
| [`PowerBlocCoaPieceSelector`](p.md#powerbloccoapieceselector) |  | 8 | uncategorized |
| [`PowerBlocCustomizationPopup`](p.md#powerbloccustomizationpopup) |  | 37 | uncategorized |
| [`PowerBlocFormation`](p.md#powerblocformation) |  | 28 | uncategorized |
| [`PowerBlocFormationPanel`](p.md#powerblocformationpanel) |  | 6 | uncategorized |
| [`PowerBlocFormationPrincipleSlot`](p.md#powerblocformationprincipleslot) |  | 11 | uncategorized |
| [`PowerBlocIdentity`](p.md#powerblocidentity) |  | 21 | uncategorized |
| [`PowerBlocMapTexture`](p.md#powerblocmaptexture) |  | 10 | uncategorized |
| [`PowerBlocMapTextureSelector`](p.md#powerblocmaptextureselector) |  | 7 | uncategorized |
| [`PowerBlocPanel`](p.md#powerblocpanel) |  | 14 | uncategorized |
| [`PowerBlocPrinciple`](p.md#powerblocprinciple) |  | 26 | uncategorized |
| [`PowerBlocPrincipleData`](p.md#powerblocprincipledata) |  | 7 | uncategorized |
| [`PowerBlocPrincipleGroup`](p.md#powerblocprinciplegroup) |  | 11 | uncategorized |
| [`PowerBlocPrincipleSelectionWindow`](p.md#powerblocprincipleselectionwindow) |  | 30 | uncategorized |
| [`PowerBlocPrincipleSlot`](p.md#powerblocprincipleslot) |  | 10 | uncategorized |
| [`PowerBlocStatue`](p.md#powerblocstatue) |  | 4 | uncategorized |
| [`PowerBlocStatueAccessoryType`](p.md#powerblocstatueaccessorytype) |  | 5 | uncategorized |
| [`PowerBlocStatueAccessoryTypeSelector`](p.md#powerblocstatueaccessorytypeselector) |  | 8 | uncategorized |
| [`PowerBlocStatueHeroType`](p.md#powerblocstatueherotype) |  | 5 | uncategorized |
| [`PowerBlocStatuePedestalType`](p.md#powerblocstatuepedestaltype) |  | 5 | uncategorized |
| [`PrestigeGoodChangeNamePopup`](p.md#prestigegoodchangenamepopup) |  | 6 | uncategorized |
| [`PreviewMaskTexture`](p.md#previewmasktexture) | Map Editor - Preview Mask | 5 | internalclausewitzgui |
| [`ProductionMarker`](p.md#productionmarker) |  | 6 | uncategorized |
| [`ProductionMethod`](p.md#productionmethod) |  | 16 | uncategorized |
| [`ProductionMethodConfirmationPopup`](p.md#productionmethodconfirmationpopup) |  | 9 | uncategorized |
| [`ProductionMethodGroup`](p.md#productionmethodgroup) |  | 10 | uncategorized |
| [`ProgressInterface`](p.md#progressinterface) |  | 3 | uncategorized |
| [`PropertyListCategory`](p.md#propertylistcategory) | A category in a property list | 9 | internalclausewitzgui |
| [`Proposal`](p.md#proposal) |  | 26 | uncategorized |
| [`Province`](p.md#province) |  | 30 | uncategorized |
| [`RandomizableValueFloat`](r.md#randomizablevaluefloat) |  | 5 | internalclausewitzgui |
| [`RandomizableValueInt`](r.md#randomizablevalueint) |  | 5 | internalclausewitzgui |
| [`ReformGovernment`](r.md#reformgovernment) |  | 45 | uncategorized |
| [`ReleaseCountryWindow`](r.md#releasecountrywindow) |  | 25 | uncategorized |
| [`Religion`](r.md#religion) |  | 41 | uncategorized |
| [`ReligionInfoPanel`](r.md#religioninfopanel) |  | 11 | uncategorized |
| [`RemoveFriendConfirmWindow`](r.md#removefriendconfirmwindow) | Jomini Friend List - Remove friend confirm window | 6 | gui |
| [`RepackWindow`](r.md#repackwindow) | Map Editor - Repack Window | 8 | internalclausewitzgui |
| [`ResignConfirmationWindow`](r.md#resignconfirmationwindow) |  | 11 | uncategorized |
| [`RevolutionaryMovementMarker`](r.md#revolutionarymovementmarker) |  | 5 | uncategorized |
| [`RightClickMenuManager`](r.md#rightclickmenumanager) |  | 76 | uncategorized |
| [`RulerSelectionPopup`](r.md#rulerselectionpopup) |  | 5 | uncategorized |
| [`Savable`](s.md#savable) | Save Dialog - Savable | 20 | internalclausewitzgui |
| [`SavableGroup`](s.md#savablegroup) | Save Dialog - Savable Group | 15 | internalclausewitzgui |
| [`SaveDialog`](s.md#savedialog) | Save Dialog | 9 | internalclausewitzgui |
| [`SaveGame`](s.md#savegame) |  | 4 | uncategorized |
| [`SaveGameAnalysisView`](s.md#savegameanalysisview) |  | 12 | internalclausewitzgui |
| [`SaveGameAnalyzer`](s.md#savegameanalyzer) |  | 7 | uncategorized |
| [`SaveGameBlockData`](s.md#savegameblockdata) |  | 13 | uncategorized |
| [`SaveGameConfigView`](s.md#savegameconfigview) |  | 6 | uncategorized |
| [`SaveGameItem`](s.md#savegameitem) |  | 32 | uncategorized |
| [`SaveGameListView`](s.md#savegamelistview) |  | 9 | uncategorized |
| [`SaveGameWindow`](s.md#savegamewindow) |  | 15 | uncategorized |
| [`Scope`](s.md#scope) |  | 203 | script |
| [`ScopeDebugData`](s.md#scopedebugdata) |  | 9 | internalclausewitzgui |
| [`ScopeDebugInspectorPlugin`](s.md#scopedebuginspectorplugin) |  | 3 | internalclausewitzgui |
| [`ScopedEditorSettingsCategory`](s.md#scopededitorsettingscategory) |  | 4 | gui |
| [`ScopeObjectEditor`](s.md#scopeobjecteditor) |  | 18 | internalclausewitzgui |
| [`ScopeObjectProvider`](s.md#scopeobjectprovider) |  | 9 | internalclausewitzgui |
| [`ScopeObjectType`](s.md#scopeobjecttype) |  | 3 | internalclausewitzgui |
| [`ScriptContainer`](s.md#scriptcontainer) |  | 17 | uncategorized |
| [`ScriptedButton`](s.md#scriptedbutton) |  | 16 | uncategorized |
| [`ScriptedGui`](s.md#scriptedgui) |  | 9 | script |
| [`ScriptedProgressBar`](s.md#scriptedprogressbar) |  | 17 | uncategorized |
| [`ScriptProfilerEntry`](s.md#scriptprofilerentry) |  | 31 | uncategorized |
| [`ScriptProfilerFileLine`](s.md#scriptprofilerfileline) |  | 24 | uncategorized |
| [`ScriptProfilerGui`](s.md#scriptprofilergui) |  | 30 | uncategorized |
| [`ScriptRunnerInspector`](s.md#scriptrunnerinspector) |  | 14 | internalclausewitzgui |
| [`ScriptRunnerResult`](s.md#scriptrunnerresult) |  | 9 | internalclausewitzgui |
| [`SeaNodeMarker`](s.md#seanodemarker) |  | 21 | uncategorized |
| [`SeaNodeMovementMarker`](s.md#seanodemovementmarker) |  | 33 | uncategorized |
| [`SearchBar`](s.md#searchbar) |  | 11 | uncategorized |
| [`SearchListNodeWindow`](s.md#searchlistnodewindow) |  | 6 | uncategorized |
| [`SearchResult`](s.md#searchresult) |  | 9 | uncategorized |
| [`SeaRegionInfraMarker`](s.md#searegioninframarker) |  | 6 | uncategorized |
| [`SeaRegionPanel`](s.md#searegionpanel) |  | 19 | uncategorized |
| [`SeaRegionWar`](s.md#searegionwar) |  | 9 | uncategorized |
| [`SelectFromInputNodeWindow`](s.md#selectfrominputnodewindow) |  | 6 | uncategorized |
| [`SelectParticleUserDataDialog`](s.md#selectparticleuserdatadialog) |  | 3 | uncategorized |
| [`SelectTool`](s.md#selecttool) | Map Editor - Map Object - Select Tool | 4 | internalclausewitzgui |
| [`ServerInformation`](s.md#serverinformation) |  | 10 | gui |
| [`SettingCategory`](s.md#settingcategory) | Jomini Settings - Category | 6 | gui |
| [`SettingsPage`](s.md#settingspage) | Jomini Settings - Settings Page | 6 | gui |
| [`Ship`](s.md#ship) |  | 117 | uncategorized |
| [`ShipChangeNamePopup`](s.md#shipchangenamepopup) |  | 6 | uncategorized |
| [`ShipConstruction`](s.md#shipconstruction) |  | 27 | uncategorized |
| [`ShipConstructionQueue`](s.md#shipconstructionqueue) |  | 3 | uncategorized |
| [`ShipCostPoint`](s.md#shipcostpoint) |  | 6 | uncategorized |
| [`ShipDesignerModSlot`](s.md#shipdesignermodslot) |  | 15 | uncategorized |
| [`ShipDesignerPopup`](s.md#shipdesignerpopup) |  | 39 | uncategorized |
| [`ShipFilter`](s.md#shipfilter) |  | 7 | uncategorized |
| [`ShipGraphicsType`](s.md#shipgraphicstype) |  | 4 | uncategorized |
| [`ShipGroup`](s.md#shipgroup) |  | 13 | uncategorized |
| [`ShipList`](s.md#shiplist) |  | 72 | uncategorized |
| [`ShipModificationSlotType`](s.md#shipmodificationslottype) |  | 7 | uncategorized |
| [`ShipModificationType`](s.md#shipmodificationtype) |  | 19 | uncategorized |
| [`ShipPanel`](s.md#shippanel) |  | 6 | uncategorized |
| [`ShippingLane`](s.md#shippinglane) |  | 26 | uncategorized |
| [`ShipSelection`](s.md#shipselection) |  | 20 | uncategorized |
| [`ShipTemplate`](s.md#shiptemplate) |  | 73 | uncategorized |
| [`ShipTemplateList`](s.md#shiptemplatelist) |  | 8 | uncategorized |
| [`ShipTemplateVersion`](s.md#shiptemplateversion) |  | 3 | uncategorized |
| [`ShipType`](s.md#shiptype) |  | 21 | uncategorized |
| [`ShipVeterancyLevel`](s.md#shipveterancylevel) |  | 14 | uncategorized |
| [`ShipViewer`](s.md#shipviewer) |  | 7 | uncategorized |
| [`SkinEditor`](s.md#skineditor) | GFX Skin Editor | 2 | internalclausewitzgui |
| [`SmartBrushHeightRange`](s.md#smartbrushheightrange) | Map Editor - Smart Material Painter - Brush Height | 7 | internalclausewitzgui |
| [`SmartBrushPattern`](s.md#smartbrushpattern) | Map Editor - Smart Material Painter - Brush Patter | 12 | internalclausewitzgui |
| [`SmartBrushPresetManager`](s.md#smartbrushpresetmanager) | Map Editor - Smart Material Painter - Brush Preset Manager | 4 | internalclausewitzgui |
| [`SmartMaterialPaintingMode`](s.md#smartmaterialpaintingmode) | Map Editor - Smart Material Painter Mode | 92 | internalclausewitzgui |
| [`Social`](s.md#social) | Jomini Social Manager | 3 | gui |
| [`SocialClass`](s.md#socialclass) |  | 21 | uncategorized |
| [`SocialHierarchy`](s.md#socialhierarchy) |  | 20 | uncategorized |
| [`SocialNotificationWindow`](s.md#socialnotificationwindow) | Jomini Friend List - Notification window | 7 | gui |
| [`SocialUI`](s.md#socialui) | Jomini Friend List - Social UI | 7 | gui |
| [`SocialWidget`](s.md#socialwidget) | Jomini Social Widget | 2 | gui |
| [`SocietyPanel`](s.md#societypanel) |  | 12 | uncategorized |
| [`SplineAdjustmentTool`](s.md#splineadjustmenttool) | Map Editor - Spline Network Adjustment Tool | 20 | internalclausewitzgui |
| [`SplineAdjustmentToolMode`](s.md#splineadjustmenttoolmode) | Map Editor - Spline Network Adjustment Tool - Mode | 3 | internalclausewitzgui |
| [`SplineRiverInteractionMode`](s.md#splineriverinteractionmode) | Map Editor - Spline Ruler Interaction Mode | 3 | internalclausewitzgui |
| [`SplineRiverTool`](s.md#splinerivertool) | Map Editor - Spline River Tool | 6 | internalclausewitzgui |
| [`SplineStripTool`](s.md#splinestriptool) | Map Editor - Spline Strip Tool | 27 | internalclausewitzgui |
| [`SplineStripToolMode`](s.md#splinestriptoolmode) | Map Editor - Spline Strip Tool - Mode | 3 | internalclausewitzgui |
| [`SplineToolsMapContentPanel`](s.md#splinetoolsmapcontentpanel) | Map Editor - Spline Strip Tool - Map Content Panel | 4 | internalclausewitzgui |
| [`SplineTypeCreateSelectionDropdown`](s.md#splinetypecreateselectiondropdown) | Map Editor - Spline Strip Tool - Create Dropdown | 6 | internalclausewitzgui |
| [`SplineTypeItem`](s.md#splinetypeitem) | Map Editor - Spline Strip Tool - Spline Type | 4 | internalclausewitzgui |
| [`SplineTypeSwitchSelectionDropdown`](s.md#splinetypeswitchselectiondropdown) | Map Editor - Spline Strip Tool - Type switch dropdown | 6 | internalclausewitzgui |
| [`SplineVisibilityDropdown`](s.md#splinevisibilitydropdown) | Map Editor - Spline Visibility Dropdown | 9 | internalclausewitzgui |
| [`StagedFormation`](s.md#stagedformation) |  | 29 | uncategorized |
| [`StagedShipsWithType`](s.md#stagedshipswithtype) |  | 12 | uncategorized |
| [`StagedUnitsWithType`](s.md#stagedunitswithtype) |  | 32 | uncategorized |
| [`StarvationType`](s.md#starvationtype) |  | 7 | uncategorized |
| [`State`](s.md#state) |  | 368 | uncategorized |
| [`StateGoods`](s.md#stategoods) |  | 12 | uncategorized |
| [`StateInfraMarker`](s.md#stateinframarker) |  | 7 | uncategorized |
| [`StateMarker`](s.md#statemarker) |  | 6 | uncategorized |
| [`StateNameChangePopup`](s.md#statenamechangepopup) |  | 16 | uncategorized |
| [`StatePopulationPanel`](s.md#statepopulationpanel) |  | 6 | uncategorized |
| [`StateRegion`](s.md#stateregion) |  | 41 | uncategorized |
| [`StatesPanel`](s.md#statespanel) |  | 31 | uncategorized |
| [`StateTrait`](s.md#statetrait) |  | 10 | uncategorized |
| [`StatusWidget`](s.md#statuswidget) | Status Widget | 13 | gui |
| [`Strait`](s.md#strait) |  | 146 | uncategorized |
| [`StraitDefinition`](s.md#straitdefinition) |  | 18 | uncategorized |
| [`StraitMarker`](s.md#straitmarker) |  | 5 | uncategorized |
| [`StraitPanel`](s.md#straitpanel) |  | 10 | uncategorized |
| [`StrategicRegion`](s.md#strategicregion) |  | 43 | uncategorized |
| [`StrategicRegionMarker`](s.md#strategicregionmarker) |  | 7 | uncategorized |
| [`StrategicRegionPanel`](s.md#strategicregionpanel) |  | 5 | uncategorized |
| [`SubjectType`](s.md#subjecttype) |  | 25 | uncategorized |
| [`SupplyNetworkEntry`](s.md#supplynetworkentry) |  | 6 | uncategorized |
| [`SupplyShipConstruction`](s.md#supplyshipconstruction) |  | 13 | uncategorized |
| [`Sway`](s.md#sway) |  | 14 | uncategorized |
| [`SwayCountryPanel`](s.md#swaycountrypanel) |  | 24 | uncategorized |
| [`SwayOffer`](s.md#swayoffer) |  | 28 | uncategorized |
| [`SwayOfferType`](s.md#swayoffertype) |  | 5 | uncategorized |
| [`TaxBurdenItem`](t.md#taxburdenitem) |  | 4 | uncategorized |
| [`Technology`](t.md#technology) |  | 38 | uncategorized |
| [`TechnologyUnlock`](t.md#technologyunlock) |  | 6 | uncategorized |
| [`TechTreeItem`](t.md#techtreeitem) |  | 7 | uncategorized |
| [`TechTreeLine`](t.md#techtreeline) |  | 16 | uncategorized |
| [`TechTreePanel`](t.md#techtreepanel) |  | 15 | uncategorized |
| [`TerrainToolButton`](t.md#terraintoolbutton) | Map Editor - Terrain Tool Button | 3 | internalclausewitzgui |
| [`TextureEntry`](t.md#textureentry) | Texture Importer - Texture Entry | 7 | internalclausewitzgui |
| [`TextureImporter`](t.md#textureimporter) | Texture Importer Window | 15 | internalclausewitzgui |
| [`TextureList`](t.md#texturelist) | Texture List - In-memory texture list | 21 | internalclausewitzgui |
| [`TextureListDirectory`](t.md#texturelistdirectory) | Texture Viewer - Directory | 8 | internalclausewitzgui |
| [`TextureListTexture`](t.md#texturelisttexture) | Texture Viewer - Texture | 8 | internalclausewitzgui |
| [`TextureNodeWindow`](t.md#texturenodewindow) | Node Editor - Texture Node Window | 5 | internalclausewitzgui |
| [`TextureViewer`](t.md#textureviewer) | Texture Viewer - In-memory texture viewer | 27 | internalclausewitzgui |
| [`Theater`](t.md#theater) |  | 12 | uncategorized |
| [`Theme`](t.md#theme) |  | 18 | uncategorized |
| [`ThemeBulkSelectionGroup`](t.md#themebulkselectiongroup) |  | 15 | uncategorized |
| [`ThemeCategory`](t.md#themecategory) |  | 9 | uncategorized |
| [`ThemeWindow`](t.md#themewindow) |  | 30 | uncategorized |
| [`TickTaskData`](t.md#ticktaskdata) |  | 13 | uncategorized |
| [`TickTaskDebuggerView`](t.md#ticktaskdebuggerview) |  | 4 | uncategorized |
| [`TickTaskDetailsView`](t.md#ticktaskdetailsview) |  | 4 | uncategorized |
| [`TickTaskGraphItem`](t.md#ticktaskgraphitem) |  | 7 | uncategorized |
| [`TickTaskGraphLine`](t.md#ticktaskgraphline) |  | 12 | uncategorized |
| [`TickTaskListView`](t.md#ticktasklistview) |  | 4 | uncategorized |
| [`TimedModifier`](t.md#timedmodifier) |  | 17 | uncategorized |
| [`TimeKeeper`](t.md#timekeeper) |  | 27 | uncategorized |
| [`TimelineKeyframe`](t.md#timelinekeyframe) | Timeline Widget - Keyframe | 9 | internalclausewitzgui |
| [`ToastMessageHandler`](t.md#toastmessagehandler) |  | 8 | uncategorized |
| [`ToolDialog`](t.md#tooldialog) | Tool Dialog | 7 | internalclausewitzgui |
| [`ToolDialogButton`](t.md#tooldialogbutton) | Tool Dialog - Button | 4 | internalclausewitzgui |
| [`ToolMessageDialog`](t.md#toolmessagedialog) | Tool Message Dialog | 6 | internalclausewitzgui |
| [`ToolProgressDialog`](t.md#toolprogressdialog) | Tool Progress Dialog | 3 | internalclausewitzgui |
| [`ToolProperty`](t.md#toolproperty) | Tool Property | 16 | internalclausewitzgui |
| [`ToolProperty2SearchList`](t.md#toolproperty2searchlist) |  | 12 | internalclausewitzgui |
| [`ToolPropertyAction`](t.md#toolpropertyaction) | Additional Action available on a given ToolProperty. | 8 | internalclausewitzgui |
| [`ToolPropertyBool`](t.md#toolpropertybool) |  | 4 | internalclausewitzgui |
| [`ToolPropertyCColor`](t.md#toolpropertyccolor) | Tool Property Color - CColor | 4 | internalclausewitzgui |
| [`ToolPropertyColor`](t.md#toolpropertycolor) | Tool Property Color - Vector4f | 4 | internalclausewitzgui |
| [`ToolPropertyCString`](t.md#toolpropertycstring) |  | 4 | internalclausewitzgui |
| [`ToolPropertyCurve`](t.md#toolpropertycurve) |  | 8 | internalclausewitzgui |
| [`ToolPropertyFloat`](t.md#toolpropertyfloat) |  | 5 | internalclausewitzgui |
| [`ToolPropertyInt`](t.md#toolpropertyint) |  | 5 | internalclausewitzgui |
| [`ToolPropertyInt16`](t.md#toolpropertyint16) |  | 5 | internalclausewitzgui |
| [`ToolPropertyInt8`](t.md#toolpropertyint8) |  | 5 | internalclausewitzgui |
| [`ToolPropertyList`](t.md#toolpropertylist) | Tool Property List | 6 | internalclausewitzgui |
| [`ToolPropertySearchList`](t.md#toolpropertysearchlist) |  | 5 | internalclausewitzgui |
| [`ToolPropertyString`](t.md#toolpropertystring) | Tool Property UTF8 String | 4 | internalclausewitzgui |
| [`ToolPropertyUint`](t.md#toolpropertyuint) |  | 5 | internalclausewitzgui |
| [`ToolPropertyUint16`](t.md#toolpropertyuint16) |  | 5 | internalclausewitzgui |
| [`ToolPropertyUint8`](t.md#toolpropertyuint8) |  | 5 | internalclausewitzgui |
| [`ToolPropertyUndoableSearchList`](t.md#toolpropertyundoablesearchlist) |  | 12 | internalclausewitzgui |
| [`ToolPropertyVec1fPercent`](t.md#toolpropertyvec1fpercent) |  | 5 | internalclausewitzgui |
| [`ToolPropertyVec2f`](t.md#toolpropertyvec2f) |  | 7 | internalclausewitzgui |
| [`ToolPropertyVec2fPercent`](t.md#toolpropertyvec2fpercent) |  | 7 | internalclausewitzgui |
| [`ToolPropertyVec2i`](t.md#toolpropertyvec2i) |  | 7 | internalclausewitzgui |
| [`ToolPropertyVec3f`](t.md#toolpropertyvec3f) |  | 11 | internalclausewitzgui |
| [`ToolPropertyVec3i`](t.md#toolpropertyvec3i) |  | 11 | internalclausewitzgui |
| [`ToolPropertyVec4i`](t.md#toolpropertyvec4i) |  | 13 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueFloat`](t.md#toolspropertydraggablevaluefloat) | Tools Property Draggable Float | 8 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueInt`](t.md#toolspropertydraggablevalueint) | Tools Property Draggable Int | 8 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueVector2f`](t.md#toolspropertydraggablevaluevector2f) | Tools Property Draggable Vector2 Float | 14 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueVector2i`](t.md#toolspropertydraggablevaluevector2i) | Tools Property Draggable Vector2 Integer | 14 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueVector3f`](t.md#toolspropertydraggablevaluevector3f) | Tools Property Draggable Vector3 Float | 20 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueVector3i`](t.md#toolspropertydraggablevaluevector3i) | Tools Property Draggable Vector3 Integer | 20 | internalclausewitzgui |
| [`ToolsPropertyDraggableValueVector4i`](t.md#toolspropertydraggablevaluevector4i) | Tools Property Draggable Vector4 Integer | 26 | internalclausewitzgui |
| [`ToolsPropertyPath`](t.md#toolspropertypath) | Tools Property Path | 7 | internalclausewitzgui |
| [`ToolsPropertyRangedValueFloat`](t.md#toolspropertyrangedvaluefloat) | Tools Property Ranged Float | 11 | internalclausewitzgui |
| [`ToolsPropertyRangedValueInt`](t.md#toolspropertyrangedvalueint) | Tools Property Ranged Int | 11 | internalclausewitzgui |
| [`ToolsPropertyTextureStringValue`](t.md#toolspropertytexturestringvalue) | Tools Property Texture Value | 6 | internalclausewitzgui |
| [`ToolsPropertyTextureValue`](t.md#toolspropertytexturevalue) | Tools Property Texture | 6 | internalclausewitzgui |
| [`ToolsPropertyValueList`](t.md#toolspropertyvaluelist) | Tools property representing a list of elements | 5 | internalclausewitzgui |
| [`ToolsPropertyValueListEntry`](t.md#toolspropertyvaluelistentry) | Single element in the datamodel provided by a ToolsPropertyValueList | 6 | internalclausewitzgui |
| [`ToolsPropertyVfsMountPath`](t.md#toolspropertyvfsmountpath) | Tools Property for Vfs-Mount-Path | 17 | internalclausewitzgui |
| [`ToolsSearch`](t.md#toolssearch) | Tools Search (OmniSearch) | 4 | internalclausewitzgui |
| [`ToolsSearchResult`](t.md#toolssearchresult) | Tools Search - Result | 8 | internalclausewitzgui |
| [`ToolsUndoableValueBundleBool`](t.md#toolsundoablevaluebundlebool) |  | 3 | internalclausewitzgui |
| [`ToolsUndoableValueBundleCColor`](t.md#toolsundoablevaluebundleccolor) |  | 3 | internalclausewitzgui |
| [`ToolsUndoableValueBundleColor`](t.md#toolsundoablevaluebundlecolor) |  | 3 | internalclausewitzgui |
| [`ToolsUndoableValueBundleCString`](t.md#toolsundoablevaluebundlecstring) |  | 6 | internalclausewitzgui |
| [`ToolsUndoableValueBundleFloat`](t.md#toolsundoablevaluebundlefloat) |  | 6 | internalclausewitzgui |
| [`ToolsUndoableValueBundleInt`](t.md#toolsundoablevaluebundleint) |  | 6 | internalclausewitzgui |
| [`ToolsUndoableValueBundleString`](t.md#toolsundoablevaluebundlestring) |  | 6 | internalclausewitzgui |
| [`ToolsUndoableValueBundleUint`](t.md#toolsundoablevaluebundleuint) |  | 6 | internalclausewitzgui |
| [`ToolsUndoableValueBundleUint16`](t.md#toolsundoablevaluebundleuint16) |  | 6 | internalclausewitzgui |
| [`ToolsUndoableValueBundleVec2f`](t.md#toolsundoablevaluebundlevec2f) |  | 7 | internalclausewitzgui |
| [`ToolsUndoableValueBundleVec2i`](t.md#toolsundoablevaluebundlevec2i) |  | 7 | internalclausewitzgui |
| [`ToolsUndoableValueBundleVec3f`](t.md#toolsundoablevaluebundlevec3f) |  | 9 | internalclausewitzgui |
| [`ToolsUndoableValueBundleVec3i`](t.md#toolsundoablevaluebundlevec3i) |  | 7 | internalclausewitzgui |
| [`ToolsUndoableValueBundleVec4i`](t.md#toolsundoablevaluebundlevec4i) |  | 7 | internalclausewitzgui |
| [`TooltipInfo`](t.md#tooltipinfo) |  | 3 | uncategorized |
| [`TopFrontend`](t.md#topfrontend) |  | 13 | uncategorized |
| [`TopScope`](t.md#topscope) |  | 238 | script |
| [`TransferFormationPopup`](t.md#transferformationpopup) |  | 42 | uncategorized |
| [`TransportPlannerPopup`](t.md#transportplannerpopup) |  | 19 | uncategorized |
| [`Treaty`](t.md#treaty) |  | 71 | uncategorized |
| [`TreatyDraft`](t.md#treatydraft) |  | 105 | uncategorized |
| [`TreatyDraftPanel`](t.md#treatydraftpanel) |  | 4 | uncategorized |
| [`TreatyPanel`](t.md#treatypanel) |  | 4 | uncategorized |
| [`TreatyShipFilter`](t.md#treatyshipfilter) |  | 6 | uncategorized |
| [`TreatyShipFilterList`](t.md#treatyshipfilterlist) |  | 5 | uncategorized |
| [`Truce`](t.md#truce) |  | 13 | uncategorized |
| [`Tutorial`](t.md#tutorial) |  | 16 | uncategorized |
| [`Tweakable`](t.md#tweakable) | Tweakable field in the Tweaker tool | 12 | internalclausewitzgui |
| [`TweakableCategory`](t.md#tweakablecategory) | A single Tweakable category in the Tweaker Tool | 7 | internalclausewitzgui |
| [`TweakablesSnapshot`](t.md#tweakablessnapshot) | A snapshot of tweakable values represented in the Tweaker tool | 3 | internalclausewitzgui |
| [`TweakableUiEntry`](t.md#tweakableuientry) | A single Tweakable Entry in the Tweaker Tool | 4 | internalclausewitzgui |
| [`Tweaker`](t.md#tweaker) | Tweaker Tool Window | 24 | internalclausewitzgui |
| [`Type`](t.md#type) | Map Editor - Map Object Type | 23 | internalclausewitzgui |
| [`uint16`](u.md#uint16) |  | 3 | common |
| [`uint32`](u.md#uint32) |  | 3 | common |
| [`uint64`](u.md#uint64) |  | 3 | common |
| [`uint8`](u.md#uint8) |  | 3 | common |
| [`UndoHistoryViewerClient`](u.md#undohistoryviewerclient) |  | 3 | uncategorized |
| [`UndoStack`](u.md#undostack) |  | 8 | uncategorized |
| [`UserDataNode`](u.md#userdatanode) | Particle Editor - User Data Node | 6 | internalclausewitzgui |
| [`VariableEntry`](v.md#variableentry) |  | 6 | internalclausewitzgui |
| [`VariableInspectorEntry`](v.md#variableinspectorentry) |  | 4 | internalclausewitzgui |
| [`VariableInspectorPlugin`](v.md#variableinspectorplugin) |  | 6 | internalclausewitzgui |
| [`VariableInspectorVariable`](v.md#variableinspectorvariable) |  | 7 | internalclausewitzgui |
| [`VariableList`](v.md#variablelist) |  | 6 | internalclausewitzgui |
| [`VariableListEntry`](v.md#variablelistentry) |  | 6 | internalclausewitzgui |
| [`VariableListInspectorPlugin`](v.md#variablelistinspectorplugin) |  | 3 | internalclausewitzgui |
| [`VariableListStore`](v.md#variableliststore) |  | 10 | internalclausewitzgui |
| [`VariableStore`](v.md#variablestore) |  | 8 | internalclausewitzgui |
| [`VariableSystem`](v.md#variablesystem) |  | 12 | common |
| [`VfsMountPathBrowser`](v.md#vfsmountpathbrowser) | Gui Data Profiler Window | 16 | internalclausewitzgui |
| [`VfsMountPathBrowserEntryNode`](v.md#vfsmountpathbrowserentrynode) | Gui Data Profiler tree entry node | 6 | internalclausewitzgui |
| [`ViewerEntity`](v.md#viewerentity) | Entity Editor - Entity | 23 | internalclausewitzgui |
| [`ViewerEntityLodInfo`](v.md#viewerentitylodinfo) | Entity Editor - Entity LodInfo | 5 | internalclausewitzgui |
| [`ViewerEntityState`](v.md#viewerentitystate) | Entity Editor - Entity State | 7 | internalclausewitzgui |
| [`void`](v.md#void) | Unspecified type / empty type. | 2 | common |
| [`War`](w.md#war) |  | 83 | uncategorized |
| [`WarGoal`](w.md#wargoal) |  | 70 | uncategorized |
| [`WarGoalDraft`](w.md#wargoaldraft) |  | 48 | uncategorized |
| [`WarGoalMarker`](w.md#wargoalmarker) |  | 6 | uncategorized |
| [`WarGoalPanelPair`](w.md#wargoalpanelpair) |  | 8 | uncategorized |
| [`WarGoalType`](w.md#wargoaltype) |  | 13 | uncategorized |
| [`WarManager`](w.md#warmanager) |  | 3 | uncategorized |
| [`WarPanel`](w.md#warpanel) |  | 62 | uncategorized |
| [`WarParticipant`](w.md#warparticipant) |  | 26 | uncategorized |
| [`WorldMarketPanel`](w.md#worldmarketpanel) |  | 13 | uncategorized |
