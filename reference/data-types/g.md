# Data-binding types: G

Back to the [index](README.md).

## GameConceptType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanStartTutorialLesson` |  | `bool` |  |
| `CanStartTutorialLessonDesc` |  | `CString` |  |
| `GetDesc` |  | `CString` |  |
| `GetDescNoFormatting` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTitle` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `HasTutorialLesson` |  | `bool` |  |
| `Self` |  |  |  |
| `StartTutorialLesson` |  | `void` |  |

## GameMpSetup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedSaveGame` |  | `SaveGameItem` |  |
| `AccessSelf` |  |  |  |
| `CanStart` |  | `bool` |  |
| `GetEnabledDLCs` |  |  |  |
| `GetEnabledMods` |  |  |  |
| `GetSaveGames` |  |  |  |
| `GetSelectedSaveGame` |  |  |  |
| `IsAutoAccept` |  | `bool` |  |
| `IsBookmarkSelected` |  | `bool` |  |
| `IsInvite` |  | `bool` |  |
| `IsPublicCrossplay` |  | `bool` |  |
| `IsPublicNoCrossplay` |  | `bool` |  |
| `IsSaveGameSelected` |  | `bool` |  |
| `OnBack` |  | `void` |  |
| `OnDelete` |  | `void` |  |
| `OnShowInvalidSavegames` |  | `void` |  |
| `OnStart` |  | `void` |  |
| `SelectBookmark` |  | `void` |  |
| `Self` |  |  |  |
| `SetVisibilityInvite` |  | `void` |  |
| `SetVisibilityPublicCrossplay` |  | `void` |  |
| `SetVisibilityPublicNoCrossplay` |  | `void` |  |
| `ShouldShowInvalidSavegames` |  | `bool` |  |
| `StartTooltip` |  | `CString` |  |
| `ToggleAutoAccept` |  | `void` |  |
| `ToggleVisibility` |  | `void` |  |

## GameOverScreen

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanContinueAsObserver` |  | `bool` |  |
| `CanGoToLobby` |  | `bool` |  |
| `CanLoadGame` |  | `bool` |  |
| `ContinueAsObserver` |  | `void` |  |
| `GetGameOverDateString` |  | `CString` |  |
| `GetGameOverSoundEvent` |  |  |  |
| `GetLoadGameDesc` |  | `CString` |  |
| `GetQuitName` |  | `CString` |  |
| `GoToLobby` |  | `void` |  |
| `OpenLoadView` |  | `void` |  |
| `Quit` |  | `void` |  |
| `Self` |  |  |  |

## GameRule

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetSettings` |  |  |  |
| `Self` |  |  |  |

## GameRuleSetting

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGameRule` |  | `GameRule` |  |
| `AccessSelf` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetDescriptionWithObjectiveRecommendation` |  | `CString` |  |
| `GetKey` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `HasFlag` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## GameSetup

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSelectedObjective` |  | `ObjectiveType` |  |
| `GetSelectedTag` |  | `CountryDefinition` |  |
| `AccessSelf` |  |  |  |
| `GetCustomRNGSeed` |  | `CString` |  |
| `GetObjectives` |  |  |  |
| `GetSelectedObjective` |  |  |  |
| `GetSelectedTag` |  |  |  |
| `HasSelectedObjective` |  | `bool` |  |
| `HasSelectedTag` |  | `bool` |  |
| `OnBack` |  | `void` |  |
| `OnEditRNGSeed` |  | `void` |  |
| `OnStart` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleObjective` | `Arg0` | `void` |  |
| `ToggleTag` | `Arg0` | `void` |  |

## GeneCategory

Portrait System - Gene Category

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `IsType` | `Arg0` | `bool` |  |
| `Self` |  |  |  |

## GeneItem

Portrait Editor - Gene Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## GeneralInformationWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetText` |  | `CString` |  |
| `GetTitle` |  | `CString` |  |
| `Self` |  |  |  |

## GenerationItem

Portrait Editor - Generation Item

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetChildPortraitItems` |  |  |  |
| `Self` |  |  |  |

## GeneTemplate

Portrait System - Gene Template

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `Self` |  |  |  |

## GeographicRegion

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `MakeScope` |  | `Scope` |  |
| `AccessSelf` |  |  |  |
| `GetCountryPagedList` |  | `CString` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetDescription` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNumCountries` |  | `int32` |  |
| `GetNumStates` |  | `int32` |  |
| `GetNumStrategicRegions` |  | `int32` |  |
| `GetStatePagedList` |  | `CString` |  |
| `GetStrategicRegionPagedList` |  | `CString` |  |
| `GetStrategicRegionTooltip` |  | `CString` |  |
| `GetTooltip` |  | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetUnlocks` |  | `CString` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `Self` |  |  |  |
| `ZoomToRegion` |  | `void` |  |

## GfxSkin

GFX Skin

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetFolders` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetPath` |  | `CString` |  |
| `GetTextures` |  |  |  |
| `Self` |  |  |  |

## Goods

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessMarket` |  | `Market` |  |
| `AccessState` |  | `State` |  |
| `GetBaseGoods` |  | `Goods` |  |
| `GetMarket` |  | `Market` |  |
| `GetMarketWithLargestExportShare` |  | `Market` |  |
| `GetMarketWithLargestImportShare` |  | `Market` |  |
| `GetState` |  | `State` |  |
| `MakeScope` |  | `Scope` |  |
| `WithMarketContext` | `Arg0` | `Goods` |  |
| `WithStateContext` | `Arg0` | `Goods` |  |
| `AccessBuildingsProducingThis` |  |  |  |
| `AccessBuildingsUsingThis` |  |  |  |
| `AccessMarket` |  |  |  |
| `AccessProductionMethodsProducingThis` |  |  |  |
| `AccessProductionMethodsUsingThis` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessState` |  |  |  |
| `CalcConsumptionTaxAmount` | `Arg0` | `CFixedPoint` |  |
| `CalcConsumptionTaxAuthorityCost` | `Arg0` | `CFixedPoint` |  |
| `CalcPotentialConsumptionTaxAmount` | `Arg0` | `CFixedPoint` |  |
| `CanEditName` |  | `bool` |  |
| `GetAccessAdjustedStateBuy` |  | `CFixedPoint` |  |
| `GetAccessAdjustedStateSell` |  | `CFixedPoint` |  |
| `GetBaseGoods` |  |  |  |
| `GetBasePrice` |  | `CFixedPoint` |  |
| `GetBasePricePlotPoints` |  |  |  |
| `GetBreakdownOfBuildingsAffectedByShortageInMarket` |  | `CString` |  |
| `GetBreakdownOfBuildingsAffectedByShortageInState` |  | `CString` |  |
| `GetBuildingsProducingThisDesc` |  | `CString` |  |
| `GetBuildingsUsingThisDesc` |  | `CString` |  |
| `GetCategoryColor` |  | `CVector4f` |  |
| `GetCategoryName` |  | `CString` |  |
| `GetColor` |  | `CVector4f` |  |
| `GetCompareDescAgainstBasePrice` | `Arg0` | `CString` |  |
| `GetCompareIconAgainstBasePrice` | `Arg0` | `CString` |  |
| `GetCompareIconAgainstBasePriceNoFormatting` | `Arg0` | `CString` |  |
| `GetCompareIconAgainstBasePriceNoTooltip` | `Arg0` | `CString` |  |
| `GetConsumptionPercentage` |  | `CFixedPoint` |  |
| `GetCustom` | `Arg0` | `CString` |  |
| `GetExportersToMarket` |  |  |  |
| `GetExportersToState` |  |  |  |
| `GetGoodsShortageDesc` |  | `CString` |  |
| `GetImportersFromMarket` |  |  |  |
| `GetImportersFromState` |  |  |  |
| `GetKey` |  | `CString` |  |
| `GetLeaderboardDesc` |  | `CString` |  |
| `GetLeaderboardSpot` | `Arg0` | `int32` |  |
| `GetLeaderboardSpotDesc` | `Arg0` | `CString` |  |
| `GetLocalPriceShare` |  | `CFixedPoint` |  |
| `GetLocalPricesDesc` |  | `CString` |  |
| `GetMarket` |  |  |  |
| `GetMarketAverageSubventionRate` |  | `CFixedPoint` |  |
| `GetMarketAverageTariffRate` |  | `CFixedPoint` |  |
| `GetMarketBalanceLabel` |  | `CString` |  |
| `GetMarketBuildingTypeBuyOrdersBreakdown` | `Arg0` | `CString` |  |
| `GetMarketBuildingTypeSellOrdersBreakdown` | `Arg0` | `CString` |  |
| `GetMarketBuyAndSellOrdersBalance` |  | `CFixedPoint` |  |
| `GetMarketBuyOrders` |  | `CFixedPoint` |  |
| `GetMarketBuyOrdersBreakdown` |  | `CString` |  |
| `GetMarketBuyOrdersWithTooltip` |  | `CString` |  |
| `GetMarketConsumption` |  | `CFixedPoint` |  |
| `GetMarketConsumptionBreakdown` |  | `CString` |  |
| `GetMarketConsumptionWithTooltip` |  | `CString` |  |
| `GetMarketExportAdvantage` |  | `CFixedPoint` |  |
| `GetMarketExports` |  | `CFixedPoint` |  |
| `GetMarketGoodsShortageDesc` |  | `CString` |  |
| `GetMarketImportAdvantage` |  | `CFixedPoint` |  |
| `GetMarketImports` |  | `CFixedPoint` |  |
| `GetMarketMonopolyFraction` |  | `CFixedPoint` |  |
| `GetMarketMonopolyPriceImpact` |  | `CFixedPoint` |  |
| `GetMarketPopConsumptionBreakdown` |  | `CString` |  |
| `GetMarketPrestigeGoods` |  |  |  |
| `GetMarketPrestigeGoodsBought` |  |  |  |
| `GetMarketPrestigeGoodsSold` |  |  |  |
| `GetMarketPrice` |  | `CFixedPoint` |  |
| `GetMarketPriceDesc` |  | `CString` |  |
| `GetMarketPriceLabel` |  | `CString` |  |
| `GetMarketPriceShare` |  | `CFixedPoint` |  |
| `GetMarketPriceShareDesc` |  | `CString` |  |
| `GetMarketPriceWithTooltip` |  | `CString` |  |
| `GetMarketProduction` |  | `CFixedPoint` |  |
| `GetMarketProductionAndConsumptionDiff` |  | `CFixedPoint` |  |
| `GetMarketProductionBreakdown` |  | `CString` |  |
| `GetMarketProductionWithTooltip` |  | `CString` |  |
| `GetMarketRelativeExportAdvantage` |  | `CFixedPoint` |  |
| `GetMarketRelativeExportAdvantageDesc` |  | `CString` |  |
| `GetMarketRelativeImportAdvantage` |  | `CFixedPoint` |  |
| `GetMarketRelativeImportAdvantageDesc` |  | `CString` |  |
| `GetMarketSellOrders` |  | `CFixedPoint` |  |
| `GetMarketSellOrdersBreakdown` |  | `CString` |  |
| `GetMarketSellOrdersWithTooltip` |  | `CString` |  |
| `GetMarketTariffsSubventionsBalance` |  | `CFixedPoint` |  |
| `GetMarketTariffsSubventionsBalanceDesc` |  | `CString` |  |
| `GetMarketWithLargestExportShare` |  |  |  |
| `GetMarketWithLargestImportShare` |  |  |  |
| `GetMaxImbalance` |  | `CFixedPoint` |  |
| `GetMaxPrice` |  | `CFixedPoint` |  |
| `GetMinPrice` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetNameNoFormatting` |  | `CString` |  |
| `GetNameNoIcon` |  | `CString` |  |
| `GetNeedLevelsContainingThisDesc` |  | `CString` |  |
| `GetNonPrestigeGoodsMarketBuyOrders` |  | `CFixedPoint` |  |
| `GetNonPrestigeGoodsMarketSellOrders` |  | `CFixedPoint` |  |
| `GetNonPrestigeGoodsStateConsumption` |  | `CFixedPoint` |  |
| `GetNonPrestigeGoodsStateProduction` |  | `CFixedPoint` |  |
| `GetNonPrestigeGoodsWorldMarketExports` |  | `CFixedPoint` |  |
| `GetNonPrestigeGoodsWorldMarketImports` |  | `CFixedPoint` |  |
| `GetNumBuildingsAffectedByShortageInMarket` |  | `int32` |  |
| `GetNumBuildingsAffectedByShortageInState` |  | `int32` |  |
| `GetPercentageDeltaAgainstBasePrice` | `Arg0` | `CFixedPoint` |  |
| `GetPrestigeAwardForPrestigeGoodSpot` | `Arg0` | `int32` |  |
| `GetPrestigeAwardForPrestigeGoodSpotDesc` | `Arg0` | `CString` |  |
| `GetPrestigeAwardForSpot` | `Arg0` | `int32` |  |
| `GetPrestigeAwardForSpotDesc` | `Arg0` | `CString` |  |
| `GetPrestigeGoodCombatUnitEffectDesc` |  | `CString` |  |
| `GetPrestigeGoodLeaderboardDesc` |  | `CString` |  |
| `GetPrestigeGoodLeaderboardSpot` | `Arg0` | `int32` |  |
| `GetPrestigeGoodLeaderboardSpotDesc` | `Arg0` | `CString` |  |
| `GetPrestigeGoodSoLEffectDesc` |  | `CString` |  |
| `GetPrestigeGoodThroughputEffectDesc` |  | `CString` |  |
| `GetPrestigeGoodTradeAdvantageEffectDesc` |  | `CString` |  |
| `GetPriceTrend` |  | `DataTrend` |  |
| `GetProductionPercentage` |  | `CFixedPoint` |  |
| `GetShippingConvoyCostMultiplier` |  | `CFixedPoint` |  |
| `GetShortCompareDescAgainstBasePrice` | `Arg0` | `CString` |  |
| `GetShortageRatioInMarket` |  | `CFixedPoint` |  |
| `GetShortageRatioInState` |  | `CFixedPoint` |  |
| `GetState` |  |  |  |
| `GetStateBalanceLabel` |  | `CString` |  |
| `GetStateConsumption` |  | `CFixedPoint` |  |
| `GetStateConsumptionBreakdown` |  | `CString` |  |
| `GetStateConsumptionLabel` |  | `CString` |  |
| `GetStateConsumptionWithTooltip` |  | `CString` |  |
| `GetStateExportAdvantage` |  | `CFixedPoint` |  |
| `GetStateExportAdvantageDesc` |  | `CString` |  |
| `GetStateExportPrice` |  | `CFixedPoint` |  |
| `GetStateExportPriceDesc` |  | `CString` |  |
| `GetStateExportSubventionRate` |  | `CFixedPoint` |  |
| `GetStateExportSubventionRateDesc` |  | `CString` |  |
| `GetStateExportTariffRate` |  | `CFixedPoint` |  |
| `GetStateExportTariffRateDesc` |  | `CString` |  |
| `GetStateExports` |  | `CFixedPoint` |  |
| `GetStateExportsDesc` |  | `CString` |  |
| `GetStateGoodsShortageDesc` |  | `CString` |  |
| `GetStateImportAdvantage` |  | `CFixedPoint` |  |
| `GetStateImportAdvantageDesc` |  | `CString` |  |
| `GetStateImportPrice` |  | `CFixedPoint` |  |
| `GetStateImportPriceDesc` |  | `CString` |  |
| `GetStateImportSubventionRate` |  | `CFixedPoint` |  |
| `GetStateImportSubventionRateDesc` |  | `CString` |  |
| `GetStateImportTariffRate` |  | `CFixedPoint` |  |
| `GetStateImportTariffRateDesc` |  | `CString` |  |
| `GetStateImports` |  | `CFixedPoint` |  |
| `GetStateImportsDesc` |  | `CString` |  |
| `GetStateMonopolyFraction` |  | `CFixedPoint` |  |
| `GetStateMonopolyPriceImpact` |  | `CFixedPoint` |  |
| `GetStatePopDemandBreakdown` | `Arg0, Arg1` | `CString` |  |
| `GetStatePopProductionBreakdown` | `Arg0, Arg1` | `CString` |  |
| `GetStatePopTypeDemandBreakdown` | `Arg0` | `CString` |  |
| `GetStatePopTypeProductionBreakdown` | `Arg0` | `CString` |  |
| `GetStatePrestigeGoods` |  |  |  |
| `GetStatePrestigeGoodsBought` |  |  |  |
| `GetStatePrestigeGoodsSold` |  |  |  |
| `GetStatePrice` |  | `CFixedPoint` |  |
| `GetStatePriceDesc` |  | `CString` |  |
| `GetStatePriceLabel` |  | `CString` |  |
| `GetStatePriceWithTooltip` |  | `CString` |  |
| `GetStateProduction` |  | `CFixedPoint` |  |
| `GetStateProductionBreakdown` |  | `CString` |  |
| `GetStateProductionConsumptionDiff` |  | `CFixedPoint` |  |
| `GetStateProductionLabel` |  | `CString` |  |
| `GetStateProductionWithTooltip` |  | `CString` |  |
| `GetStateRelativeExportAdvantage` |  | `CFixedPoint` |  |
| `GetStateRelativeExportAdvantageDesc` |  | `CString` |  |
| `GetStateRelativeImportAdvantage` |  | `CFixedPoint` |  |
| `GetStateRelativeImportAdvantageDesc` |  | `CString` |  |
| `GetStateTariffsSubventionsBalance` |  | `CFixedPoint` |  |
| `GetStateTariffsSubventionsBalanceDesc` |  | `CString` |  |
| `GetStateToMarketPriceDiff` |  | `CFixedPoint` |  |
| `GetSupplyDemandRatio` |  | `CFixedPoint` |  |
| `GetTaxDesc` | `Arg0` | `CString` |  |
| `GetTextIcon` |  | `CString` |  |
| `GetTexture` |  |  |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTotalImportExport` |  | `CFixedPoint` |  |
| `GetTradedQuantity` |  | `CFixedPoint` |  |
| `GetWorldMarketAdditionalExportsFromMarket` |  | `CFixedPoint` |  |
| `GetWorldMarketAdditionalImportsToMarket` |  | `CFixedPoint` |  |
| `GetWorldMarketBasePrice` |  | `CFixedPoint` |  |
| `GetWorldMarketBasePriceDesc` |  | `CString` |  |
| `GetWorldMarketExporters` |  |  |  |
| `GetWorldMarketExports` |  | `CFixedPoint` |  |
| `GetWorldMarketExportsAndImportsBalance` |  | `CFixedPoint` |  |
| `GetWorldMarketExportsBreakdown` |  | `CString` |  |
| `GetWorldMarketExportsWithTooltip` |  | `CString` |  |
| `GetWorldMarketImporters` |  |  |  |
| `GetWorldMarketImports` |  | `CFixedPoint` |  |
| `GetWorldMarketImportsBreakdown` |  | `CString` |  |
| `GetWorldMarketImportsWithTooltip` |  | `CString` |  |
| `GetWorldMarketMonopolyFraction` |  | `CFixedPoint` |  |
| `GetWorldMarketMonopolyPriceImpact` |  | `CFixedPoint` |  |
| `GetWorldMarketPrestigeGoods` |  |  |  |
| `GetWorldMarketPrestigeGoodsExported` |  |  |  |
| `GetWorldMarketPrestigeGoodsImported` |  |  |  |
| `GetWorldPriceTrend` |  | `DataTrend` |  |
| `HasGoodsShortage` |  | `bool` |  |
| `HasImportExportControl` |  | `bool` |  |
| `HasMarketContext` |  | `bool` |  |
| `HasPriceTrend` |  | `bool` |  |
| `HasShortageInMarket` |  | `bool` |  |
| `HasShortageInState` |  | `bool` |  |
| `HasStateContext` |  | `bool` |  |
| `IsBeingHighlighted` |  | `bool` |  |
| `IsGoodsMarketTabOpen` |  | `bool` |  |
| `IsLocal` |  | `bool` |  |
| `IsPinnedInOutliner` |  | `bool` |  |
| `IsPrestigeGoods` |  | `bool` |  |
| `IsTaxed` | `Arg0` | `bool` |  |
| `IsTradeable` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `TogglePinInOutliner` |  | `void` |  |
| `ToggleTaxation` | `Arg0` | `Command` |  |
| `WithMarketContext` | `Arg0` |  |  |
| `WithStateContext` | `Arg0` |  |  |

## GoodsExpenseItem

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `AccessSelf` |  |  |  |
| `GetExpenseRatio` |  | `CFixedPoint` |  |
| `GetGoods` |  |  |  |
| `GetPrice` |  | `CFixedPoint` |  |
| `GetRelativePriceDiff` |  | `CFixedPoint` |  |
| `GetTotalCost` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## GoodsList

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetGoods` |  |  |  |
| `GetPopConsumptionRatio` | `Arg0` | `CFixedPoint` |  |
| `GetPrice` | `Arg0` | `CFixedPoint` |  |
| `HasMarketContext` |  | `bool` |  |
| `HasStateContext` |  | `bool` |  |
| `RestoreSort` |  | `void` |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## GoodsLocalPricesPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessGoods` |  | `Goods` |  |
| `GetGoods` |  | `Goods` |  |
| `AccessGoods` |  |  |  |
| `AccessLocalPrices` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetGoods` |  |  |  |
| `Self` |  |  |  |
| `Sort` | `Arg0` | `void` |  |

## GoodsPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `GetMarketGoods` |  | `MarketGoods` |  |
| `AccessSelf` |  |  |  |
| `GetInputValues` |  |  |  |
| `GetInputValuesTotal` |  | `CFixedPoint` |  |
| `GetOutputValues` |  |  |  |
| `GetOutputValuesTotal` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## GoodsPanelChildValue

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetValue` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## GoodsPanelValue

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBuilding` |  | `Building` |  |
| `GetBuildingType` |  | `BuildingType` |  |
| `GetMarket` |  | `Market` |  |
| `GetState` |  | `State` |  |
| `AccessSelf` |  |  |  |
| `GetBuilding` |  |  |  |
| `GetBuildingType` |  |  |  |
| `GetChildren` |  |  |  |
| `GetMarket` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetState` |  |  |  |
| `GetValue` |  | `CFixedPoint` |  |
| `HasBuildingInfo` |  | `bool` |  |
| `HasBuildingTypeInfo` |  | `bool` |  |
| `HasMarketContext` |  | `bool` |  |
| `IsPiracy` |  | `bool` |  |
| `IsPiracyLoss` |  | `bool` |  |
| `Self` |  |  |  |
| `ShowChildValues` |  | `bool` |  |

## GoodsProductionInfo

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessGoods` |  | `Goods` |  |
| `AccessGoods` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetAmount` |  | `CFixedPoint` |  |
| `GetMP` |  | `CFixedPoint` |  |
| `GetName` |  | `CString` |  |
| `GetPrice` |  | `CFixedPoint` |  |
| `GetSoldFor` |  | `CFixedPoint` |  |
| `GetTexture` |  |  |  |
| `Self` |  |  |  |

## GoodsStatePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetGoods` |  | `Goods` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `AccessSelf` |  |  |  |
| `GetInputValues` |  |  |  |
| `GetInputValuesTotal` |  | `CFixedPoint` |  |
| `GetOutputValues` |  |  |  |
| `GetOutputValuesTotal` |  | `CFixedPoint` |  |
| `Self` |  |  |  |

## GoodsUsagePanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessGoods` |  | `Goods` |  |
| `GetGoods` |  | `Goods` |  |
| `AccessGoods` |  |  |  |
| `AccessProductionValues` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetGoods` |  |  |  |
| `Self` |  |  |  |

## GoodsWorldMarketPanel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetBaseGoods` |  | `Goods` |  |
| `GetGoods` |  | `Goods` |  |
| `GetMapModeList` |  | `MapModeList` |  |
| `AccessSelf` |  |  |  |
| `GetBaseGoods` |  |  |  |
| `GetGoods` |  |  |  |
| `GetMarkets` |  |  |  |
| `Self` |  |  |  |
| `SortMarkets` | `Arg0` | `void` |  |

## GovernmentType

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDesc` |  | `CString` |  |
| `GetName` |  | `CString` |  |
| `GetPossibleTriggerDesc` | `Arg0` | `CString` |  |
| `GetTooltipTag` |  | `CString` |  |
| `GetTransferOfPowerDesc` |  | `CString` |  |
| `GetTransferOfPowerName` |  | `CString` |  |
| `Self` |  |  |  |

## Graph

Node Editor - Graph

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `Errors` |  |  |  |
| `HasErrors` |  | `bool` |  |
| `Self` |  |  |  |

## GraphInterfaceNodeWindow

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddPin` | `Arg0` | `void` |  |
| `Self` |  |  |  |

## GraphPanel

Node Editor - Graph Panel

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAnimationEditorSearch` |  | `NodeEditorSearch` |  |
| `AccessMetadataWindow` |  | `MetadataWindow` |  |
| `GetMetadataWindow` |  | `MetadataWindow` |  |
| `AccessAnimationEditorSearch` |  |  |  |
| `AccessMetadataWindow` |  |  |  |
| `AccessSelf` |  |  |  |
| `ClearSelection` |  | `void` |  |
| `CompoundNodeUpdated` | `Arg0` | `void` |  |
| `Copy` |  | `void` |  |
| `CreateInfoBoxNode` |  | `int32` |  |
| `CreateNodeByName` | `Arg0` | `int32` |  |
| `Cut` |  | `void` |  |
| `Delete` |  | `void` |  |
| `Fit` |  | `void` |  |
| `GetMetadataWindow` |  |  |  |
| `GetNodeLineMaskTexture` | `Arg0` |  |  |
| `GetNodeLineTexture` | `Arg0` |  |  |
| `GetViewportHotkeysDescription` |  | `CString` |  |
| `HasExportButton` |  | `bool` |  |
| `HasImportButton` |  | `bool` |  |
| `HasPreviewer` |  | `bool` |  |
| `HasRenamingCapability` |  | `bool` |  |
| `InvertSelection` |  | `void` |  |
| `IsButtonEnabled` | `Arg0` | `bool` |  |
| `IsNodeEditorSearchVisible` |  | `bool` |  |
| `IsPasteable` |  | `bool` |  |
| `IsSaveable` |  | `bool` |  |
| `IsViewportHoteysDescriptionShown` |  | `bool` |  |
| `LayoutNodes` |  | `void` |  |
| `Load` |  | `void` |  |
| `New` |  | `void` |  |
| `OnEditorPreferencesClicked` |  | `void` |  |
| `OnExportButton` |  | `void` |  |
| `OnImportButton` |  | `void` |  |
| `OpenPreviewer` |  | `void` |  |
| `Paste` |  | `void` |  |
| `PasteConnectedToExisting` |  | `void` |  |
| `Properties` |  | `void` |  |
| `RenameGraph` |  | `void` |  |
| `Save` |  | `void` |  |
| `SaveAs` |  | `void` |  |
| `SelectAllNodes` |  | `void` |  |
| `SelectionToCompoundNode` |  | `void` |  |
| `SelectionToGroupNode` |  | `void` |  |
| `Self` |  |  |  |
| `SetZoom` | `Arg0` | `void` |  |
| `ShatterSelectedGroup` |  | `void` |  |
| `ShowNodeEditorSearch` |  | `void` |  |
| `ShowNodeSearch` |  | `void` |  |

## Group

Jomini Achievement Window - Group

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AccessVisibleAchievements` |  |  |  |
| `CalcNumberOfUnlockedVisibleAchievements` |  | `int32` |  |
| `GetName` |  | `CUTF8String` |  |
| `GetNumberOfVisibleAchievements` |  | `int32` |  |
| `IsCollapsed` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleCollapsed` |  | `void` |  |

## GUIAchievement

Jomini Achievement GUI

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetAchievement` |  | `Achievement` |  |
| `AccessLockedTexture` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessTexture` |  |  |  |
| `GetAchievement` |  |  |  |
| `GetDescription` |  | `CUTF8String` |  |
| `GetHappenedDescription` |  | `CUTF8String` |  |
| `GetName` |  | `CUTF8String` |  |
| `IsPossible` |  | `bool` |  |
| `OnClick` |  | `void` |  |
| `Remove` |  | `void` |  |
| `Self` |  |  |  |

## GuiAnimationCurveEditor

Dockable tool for editing gui animations as a curve graphs.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetGraphLines` |  |  |  |
| `IsAnyEditorOpen` |  | `bool` |  |
| `Self` |  |  |  |

## GuiAnimationCurveEditorControlPoint

A control point of a given curve editor line.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetCoords` |  | `CVector2f` |  |
| `IsSelected` | `Arg0` | `bool` |  |
| `IsUnderMousePointer` |  | `bool` |  |
| `Self` |  |  |  |

## GuiAnimationCurveEditorLine

A single curve editor line instance.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetColor` |  | `CVector4f` |  |
| `GetControlPoints` |  |  |  |
| `GetLineVertices` |  |  |  |
| `Self` |  |  |  |

## GuiAnimationCurveEditorViewport

Gui Animation Curve Editor Viewport instance.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetNeedlePosition` | `Arg0, Arg1, Arg2` | `CVector2f` |  |
| `Self` |  |  |  |

## GuiAnimationEditor

Dockable tool for editing gui animations.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessAnimSets` |  |  |  |
| `AccessAnimations` |  |  |  |
| `AccessAvailableTracks` |  |  |  |
| `AccessSelf` |  |  |  |
| `AccessUniversalTracks` |  |  |  |
| `AddKeyframesAtCurrentTime` |  | `void` |  |
| `CanChangeSelectedAnimSetParent` |  | `bool` |  |
| `CanCreateNewAnimation` |  | `bool` |  |
| `CanDeleteSelectedAnimSet` |  | `bool` |  |
| `CanDeleteSelectedAnimations` |  | `bool` |  |
| `CanRenameSelectedAnimSet` |  | `bool` |  |
| `CanRenameSelectedAnimation` |  | `bool` |  |
| `ChangeSelectedAnimSetParent` |  | `void` |  |
| `CreateNewAnimSet` |  | `void` |  |
| `CreateNewAnimation` |  | `void` |  |
| `DeleteSelectedAnimSet` |  | `void` |  |
| `DeleteSelectedAnimations` |  | `void` |  |
| `DeleteSelectedKeyframes` |  | `void` |  |
| `GetAnimSets` |  |  |  |
| `GetAnimations` |  |  |  |
| `GetAvailableTracks` |  |  |  |
| `GetUniversalTracks` |  |  |  |
| `IsAnyCurveEditorOpen` |  | `bool` |  |
| `IsKeyframeSelectionValidForCurvePreset` |  | `bool` |  |
| `OnSave` |  | `void` |  |
| `OnSaveAs` |  | `void` |  |
| `RenameSelectedAnimSet` |  | `void` |  |
| `RenameSelectedAnimation` |  | `void` |  |
| `Self` |  |  |  |

## GuiAnimationEditorAnimationEntry

An entry representing an animation for a given anim-set in the Gui Animation Editor.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDisplayName` |  | `CString` |  |
| `GetTooltipMessage` |  | `CString` |  |
| `IsAnimationInherited` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `OverrideInheritedAnimation` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleSelected` |  | `void` |  |

## GuiAnimationEditorAnimSetEntry

Animation-set list entry in the Gui Animation Editor tool.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDisplayName` |  | `CString` |  |
| `IsSelected` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleSelected` |  | `void` |  |

## GuiAnimationEditorAvailableTrack

An entry representing a track that is available to add to the given animation in the Gui Animation Editor tool.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `AddTrack` |  | `void` |  |
| `GetDescription` |  |  |  |
| `GetDisplayName` |  |  |  |
| `GetExcludedDisplayName` |  |  |  |
| `IsExcluded` |  | `bool` |  |
| `Self` |  |  |  |

## GuiAnimationEditorKeyframe

An entry representing a single keyframe on the track in the Gui Animation Editor.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetPosition` |  | `CVector2f` |  |
| `GetTimeInSeconds` |  | `float` |  |
| `IsDataFlowButton` |  | `bool` |  |
| `IsDataFlowToWidget` |  | `bool` |  |
| `IsDragged` |  | `bool` |  |
| `IsSelected` |  | `bool` |  |
| `IsUnderMousePointer` |  | `bool` |  |
| `IsValid` |  | `bool` |  |
| `Self` |  |  |  |
| `ToggleDataFlow` |  | `void` |  |

## GuiAnimationEditorMetadataCtx

Tool metadata context of Gui Animation Editor.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `DeselectAllKeyframes` |  | `void` |  |
| `HasSelectedAnyKeyframes` |  | `bool` |  |
| `IsAnimationsTabCollapsed` |  | `bool` |  |
| `IsKeyframeSnapping` |  | `bool` |  |
| `SelectAllKeyframes` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleAnimationsTabCollapsed` |  | `void` |  |
| `ToggleKeyframeSnapping` |  | `void` |  |

## GuiAnimationEditorPlayer

Instance for managing the playback in Gui Animation Editor.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanPlay` |  | `bool` |  |
| `GetCurrentSpeedMultiplierOptionIndex` |  | `CVector2i` |  |
| `GetCurrentTime` |  | `float` |  |
| `GetMaxDuration` |  | `float` |  |
| `GetSpeedMultiplier` |  | `float` |  |
| `GetSpeedMultiplierOptions` |  |  |  |
| `IsDraggingTime` |  | `bool` |  |
| `IsLoopEnabled` |  | `bool` |  |
| `IsPlaying` |  | `bool` |  |
| `Self` |  |  |  |
| `SetCurrentTime` | `Arg0` | `void` |  |
| `SetIsPlaying` | `Arg0` | `void` |  |
| `SetLoopEnabled` | `Arg0` | `void` |  |
| `SetSpeedMultiplier` | `Arg0` | `void` |  |
| `SetSpeedMultiplierOptionIndex` |  | `void` |  |
| `ShouldMoveNeedleWithKeyframe` |  | `bool` |  |
| `StepBackwards` |  | `void` |  |
| `StepForward` |  | `void` |  |
| `ToggleIsPlaying` |  | `void` |  |
| `ToggleLoopEnabled` |  | `void` |  |
| `ToggleMoveNeedleWithKeyframe` |  | `void` |  |

## GuiAnimationEditorPlayerSpeedMultiplierEntry

Playback Speed Multiplier Entry in Gui Animation Editor.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDisplayName` |  | `CString` |  |
| `GetMultiplier` |  | `float` |  |
| `Self` |  |  |  |

## GuiAnimationEditorRuler

Viewport ruler in the Gui Animation Editor tool.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessRulerResolutionEntries` |  |  |  |
| `AccessSelf` |  |  |  |
| `GetRulerResolutionEntries` |  |  |  |
| `Self` |  |  |  |

## GuiAnimationEditorRulerResolutionEntry

An entry representing a ruler resolution step in the Gui Animation Editor tool.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDisplayValue` |  | `CString` |  |
| `GetPosition` |  | `CVector2f` |  |
| `IsSubdivision` |  | `bool` |  |
| `Self` |  |  |  |

## GuiAnimationEditorUniversalTrack

An entry representing an animation for a given anim-set in the Gui Animation Editor.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessKeyframes` |  |  |  |
| `AccessSelf` |  |  |  |
| `AddKeyframeAtMousePointer` |  | `void` |  |
| `CleanAssignedWidgets` |  | `void` |  |
| `GetAssignedWidgetsCount` |  | `int32` |  |
| `GetDisplayName` |  | `CString` |  |
| `GetDuration` |  | `float` |  |
| `GetIndentationDepth` |  | `int32` |  |
| `GetKeyframes` |  |  |  |
| `GetTimelineViewRightCornerPosition` |  | `CVector2f` |  |
| `GetTimelineViewSize` |  | `CVector2f` |  |
| `HasDataToAnimate` |  | `bool` |  |
| `IsCollapsable` |  | `bool` |  |
| `IsCollapsed` |  | `bool` |  |
| `IsInWidgetAssignmentMode` |  | `bool` |  |
| `IsRemovable` |  | `bool` |  |
| `IsTimeAtKeyframe` |  | `bool` |  |
| `IsTimeWithinAnimation` |  | `bool` |  |
| `IsTrackTypeAnimation` |  | `bool` |  |
| `IsTrackTypeProperty` |  | `bool` |  |
| `IsUnderMousePointer` |  | `bool` |  |
| `NextKeyframe` |  | `void` |  |
| `OpenTrackSelection` |  | `void` |  |
| `PreviousKeyframe` |  | `void` |  |
| `Remove` |  | `void` |  |
| `Self` |  |  |  |
| `ToggleCollapsed` |  | `void` |  |
| `ToggleKeyframe` |  | `void` |  |
| `ToggleWidgetAssignmentMode` |  | `void` |  |

## GuiAnimationEditorViewportBase

Base class for the different types of viewports in the GUI Animation Editor dockables

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetNeedlePosition` | `Arg0, Arg1, Arg2` | `CVector2f` |  |
| `Self` |  |  |  |

## GuiAnimationEditorViewportUserInput

Keeps track of the user input over viewports in the GUI Animation Editor dockables

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetSelectionDragRectPosition` | `Arg0` | `CVector2f` |  |
| `GetSelectionDragRectSize` |  | `CVector2f` |  |
| `IsDraggingSelectionRect` |  | `bool` |  |
| `Self` |  |  |  |

## GuiAnimationTimelineViewport

Gui Animation Editor Timeline Viewport instance.

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `BeginDragDuration` | `Arg0` | `void` |  |
| `CanBeginDragDuration` |  | `bool` |  |
| `GetNeedlePosition` | `Arg0, Arg1, Arg2` | `CVector2f` |  |
| `Self` |  |  |  |

## GuiContext

GUI Context

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetScreenResolution` |  | `CVector2f` |  |
| `Self` |  |  |  |

## GuiCurrentDrag

For use in drag_widget, inside of draggable_behavior. Contains data regarding current ongoing drag, such as mouse positions

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CurrentPosition` |  | `CVector2f` |  |
| `Self` |  |  |  |
| `StartPosition` |  | `CVector2f` |  |

## GuiDataProfiler

Gui Data Profiler Window

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `BeginRecording` |  | `void` |  |
| `CanBeginRecording` |  | `bool` |  |
| `GetCurrentDurationTypeDescription` |  | `CString` |  |
| `GetCurrentFrame` |  | `uint32` |  |
| `GetDurationTypeIndex` |  | `CVector2i` |  |
| `GetDurationTypeNames` |  |  |  |
| `GetDurationValueTypeIndex` |  | `CVector2i` |  |
| `GetDurationValueTypeNames` |  |  |  |
| `GetNodeDuration` | `Arg0` | `CString` |  |
| `GetNodeTree` |  |  |  |
| `GetNumFramesToCapture` |  | `uint32` |  |
| `GetSortingMethodIndex` |  | `CVector2i` |  |
| `GetSortingMethodNames` |  |  |  |
| `GetTotalCapturedWidgets` |  | `uint32` |  |
| `GetViewTypeIndex` |  | `CVector2i` |  |
| `GetViewTypeNames` |  |  |  |
| `IsCallsListView` |  | `bool` |  |
| `IsLocationColumnShown` |  | `bool` |  |
| `IsNodeExpanded` | `Arg0` | `bool` |  |
| `IsRecording` |  | `bool` |  |
| `NextFrame` | `Arg0` | `void` |  |
| `Self` |  |  |  |
| `SetCurrentFrame` |  | `void` |  |
| `SetDurationTypeIndex` |  | `void` |  |
| `SetDurationValueTypeIndex` |  | `void` |  |
| `SetNumFramesToCapture` |  | `void` |  |
| `SetSortingMethodIndex` |  | `void` |  |
| `SetViewTypeIndex` |  | `void` |  |
| `ToggleLocationColumnShown` |  | `void` |  |
| `ToggleNodeExpanded` | `Arg0` | `void` |  |

## GuiDataProfilerEntryNode

Gui Data Profiler tree entry node

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `CanOpenFileLocation` |  | `bool` |  |
| `GetBranchDepth` | `Arg0, Arg1` | `CVector2f` |  |
| `GetLocation` |  | `CString` |  |
| `GetName` |  |  |  |
| `GetNumCalls` |  | `uint32` |  |
| `HasChildren` |  | `bool` |  |
| `OpenFileLocation` |  | `void` |  |
| `Self` |  |  |  |

## GuiEditorTooltip

GUI Editor - Tooltip

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `AccessSelf` |  |  |  |
| `GetDescription` |  | `CString` |  |
| `GetTitle` |  | `CString` |  |
| `HasDescription` |  | `bool` |  |
| `HasTitle` |  | `bool` |  |
| `IsVisible` |  | `bool` |  |
| `Self` |  |  |  |

## GuiGameRule

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetRule` |  | `GameRule` |  |
| `GetSetting` |  | `GameRuleSetting` |  |
| `AccessSelf` |  |  |  |
| `GetRule` |  |  |  |
| `GetSetting` |  |  |  |
| `Next` |  | `void` |  |
| `Prev` |  | `void` |  |
| `Self` |  |  |  |

## GuiGameRulePreset

| Member | Arguments | Returns | Description |
|---|---|---|---|
| `GetSettingForRule` | `Arg0` | `GameRuleSetting` |  |
| `AccessSelf` |  |  |  |
| `GetName` |  | `CString` |  |
| `GetSettingForRule` | `Arg0` |  |  |
| `HasRuleWithFlag` | `Arg0` | `bool` |  |
| `IsIronmanEnabled` |  | `bool` |  |
| `Self` |  |  |  |
