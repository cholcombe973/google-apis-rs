<!---
DO NOT EDIT !
This file was generated automatically from 'src/mako/api/README.md.mako'
DO NOT EDIT !
-->
The `google-dfareporting2d6` library allows access to all features of the *Google dfareporting* service.

This documentation was generated from *dfareporting* crate version *1.0.0+20160803*, where *20160803* is the exact revision of the *dfareporting:v2.6* schema built by the [mako](http://www.makotemplates.org/) code generator *v1.0.0*.

Everything else about the *dfareporting* *v2d6* API can be found at the
[official documentation site](https://developers.google.com/doubleclick-advertisers/).
# Features

Handle the following *Resources* with ease from the central [hub](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Dfareporting.html) ... 

* [account active ad summaries](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountActiveAdSummary.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountActiveAdSummaryGetCall.html)
* [account permission groups](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPermissionGroup.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPermissionGroupGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPermissionGroupListCall.html)
* [account permissions](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPermission.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPermissionGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPermissionListCall.html)
* [account user profiles](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUserProfile.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUserProfileGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUserProfileInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUserProfileListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUserProfilePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUserProfileUpdateCall.html)
* [accounts](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Account.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountGetCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AccountUpdateCall.html)
* [ads](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Ad.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdUpdateCall.html)
* [advertiser groups](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroup.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroupDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroupGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroupInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroupListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroupPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGroupUpdateCall.html)
* [advertisers](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Advertiser.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.AdvertiserUpdateCall.html)
* [browsers](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Browser.html)
 * [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.BrowserListCall.html)
* [campaign creative associations](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignCreativeAssociation.html)
 * [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignCreativeAssociationInsertCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignCreativeAssociationListCall.html)
* [campaigns](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Campaign.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CampaignUpdateCall.html)
* [change logs](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ChangeLog.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ChangeLogGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ChangeLogListCall.html)
* [cities](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.City.html)
 * [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CityListCall.html)
* [connection types](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ConnectionType.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ConnectionTypeGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ConnectionTypeListCall.html)
* [content categories](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategory.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategoryDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategoryGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategoryInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategoryListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategoryPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ContentCategoryUpdateCall.html)
* [conversions](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Conversion.html)
 * [*batchinsert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ConversionBatchinsertCall.html)
* [countries](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Country.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CountryGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CountryListCall.html)
* [creative assets](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeAsset.html)
 * [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeAssetInsertCall.html)
* [creative field values](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValue.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValueDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValueGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValueInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValueListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValuePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldValueUpdateCall.html)
* [creative fields](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeField.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeFieldUpdateCall.html)
* [creative groups](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGroup.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGroupGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGroupInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGroupListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGroupPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGroupUpdateCall.html)
* [creatives](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Creative.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeUpdateCall.html)
* [dimension values](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DimensionValue.html)
 * [*query*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DimensionValueQueryCall.html)
* [directory site contacts](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySiteContact.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySiteContactGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySiteContactListCall.html)
* [directory sites](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySite.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySiteGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySiteInsertCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DirectorySiteListCall.html)
* [dynamic targeting keys](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DynamicTargetingKey.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DynamicTargetingKeyDeleteCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DynamicTargetingKeyInsertCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.DynamicTargetingKeyListCall.html)
* [event tags](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTag.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTagDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTagGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTagInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTagListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTagPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.EventTagUpdateCall.html)
* [files](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.File.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FileGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FileListCall.html)
* [floodlight activities](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivity.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityDeleteCall.html), [*generatetag*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGeneratetagCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityUpdateCall.html)
* [floodlight activity groups](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGroup.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGroupGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGroupInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGroupListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGroupPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightActivityGroupUpdateCall.html)
* [floodlight configurations](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightConfiguration.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightConfigurationGetCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightConfigurationListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightConfigurationPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FloodlightConfigurationUpdateCall.html)
* [inventory items](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.InventoryItem.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.InventoryItemGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.InventoryItemListCall.html)
* [landing pages](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPage.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPageDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPageGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPageInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPageListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPagePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LandingPageUpdateCall.html)
* [languages](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Language.html)
 * [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.LanguageListCall.html)
* [metros](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Metro.html)
 * [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.MetroListCall.html)
* [mobile carriers](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.MobileCarrier.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.MobileCarrierGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.MobileCarrierListCall.html)
* [operating system versions](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OperatingSystemVersion.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OperatingSystemVersionGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OperatingSystemVersionListCall.html)
* [operating systems](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OperatingSystem.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OperatingSystemGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OperatingSystemListCall.html)
* [order documents](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OrderDocument.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OrderDocumentGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OrderDocumentListCall.html)
* [orders](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Order.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OrderGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.OrderListCall.html)
* [placement groups](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGroup.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGroupGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGroupInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGroupListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGroupPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGroupUpdateCall.html)
* [placement strategies](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategy.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategyDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategyGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategyInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategyListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategyPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementStrategyUpdateCall.html)
* [placements](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Placement.html)
 * [*generatetags*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGeneratetagCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlacementUpdateCall.html)
* [platform types](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlatformType.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlatformTypeGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PlatformTypeListCall.html)
* [postal codes](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PostalCode.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PostalCodeGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.PostalCodeListCall.html)
* [projects](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Project.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ProjectGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ProjectListCall.html)
* [regions](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Region.html)
 * [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RegionListCall.html)
* [remarketing list shares](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListShare.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListShareGetCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListSharePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListShareUpdateCall.html)
* [remarketing lists](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingList.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.RemarketingListUpdateCall.html)
* [reports](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Report.html)
 * [*compatible fields query*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportCompatibleFieldQueryCall.html), [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportDeleteCall.html), [*files get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportFileGetCall.html), [*files list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportFileListCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportPatchCall.html), [*run*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportRunCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportUpdateCall.html)
* [sites](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Site.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SiteGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SiteInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SiteListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SitePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SiteUpdateCall.html)
* [sizes](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Size.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SizeGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SizeInsertCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SizeListCall.html)
* [subaccounts](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Subaccount.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SubaccountGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SubaccountInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SubaccountListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SubaccountPatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.SubaccountUpdateCall.html)
* [targetable remarketing lists](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetableRemarketingList.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetableRemarketingListGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetableRemarketingListListCall.html)
* [targeting templates](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetingTemplate.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetingTemplateGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetingTemplateInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetingTemplateListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetingTemplatePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.TargetingTemplateUpdateCall.html)
* [user profiles](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserProfile.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserProfileGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserProfileListCall.html)
* [user role permission groups](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePermissionGroup.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePermissionGroupGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePermissionGroupListCall.html)
* [user role permissions](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePermission.html)
 * [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePermissionGetCall.html) and [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePermissionListCall.html)
* [user roles](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRole.html)
 * [*delete*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRoleDeleteCall.html), [*get*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRoleGetCall.html), [*insert*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRoleInsertCall.html), [*list*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRoleListCall.html), [*patch*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRolePatchCall.html) and [*update*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.UserRoleUpdateCall.html)


Upload supported by ...

* [*insert creative assets*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.CreativeAssetInsertCall.html)

Download supported by ...

* [*get files*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.FileGetCall.html)
* [*files get reports*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.ReportFileGetCall.html)



# Structure of this Library

The API is structured into the following primary items:

* **[Hub](http://byron.github.io/google-apis-rs/google_dfareporting2d6/struct.Dfareporting.html)**
    * a central object to maintain state and allow accessing all *Activities*
    * creates [*Method Builders*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.MethodsBuilder.html) which in turn
      allow access to individual [*Call Builders*](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.CallBuilder.html)
* **[Resources](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.Resource.html)**
    * primary types that you can apply *Activities* to
    * a collection of properties and *Parts*
    * **[Parts](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.Part.html)**
        * a collection of properties
        * never directly used in *Activities*
* **[Activities](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.CallBuilder.html)**
    * operations to apply to *Resources*

All *structures* are marked with applicable traits to further categorize them and ease browsing.

Generally speaking, you can invoke *Activities* like this:

```Rust,ignore
let r = hub.resource().activity(...).doit()
```

Or specifically ...

```ignore
let r = hub.reports().run(...).doit()
let r = hub.reports().get(...).doit()
let r = hub.reports().list(...).doit()
let r = hub.reports().delete(...).doit()
let r = hub.reports().files_list(...).doit()
let r = hub.reports().insert(...).doit()
let r = hub.reports().patch(...).doit()
let r = hub.reports().compatible_fields_query(...).doit()
let r = hub.reports().update(...).doit()
let r = hub.reports().files_get(...).doit()
```

The `resource()` and `activity(...)` calls create [builders][builder-pattern]. The second one dealing with `Activities` 
supports various methods to configure the impending operation (not shown here). It is made such that all required arguments have to be 
specified right away (i.e. `(...)`), whereas all optional ones can be [build up][builder-pattern] as desired.
The `doit()` method performs the actual communication with the server and returns the respective result.

# Usage

## Setting up your Project

To use this library, you would put the following lines into your `Cargo.toml` file:

```toml
[dependencies]
google-dfareporting2d6 = "*"
```

## A complete example

```Rust
extern crate hyper;
extern crate yup_oauth2 as oauth2;
extern crate google_dfareporting2d6 as dfareporting2d6;
use dfareporting2d6::{Result, Error};
use std::default::Default;
use oauth2::{Authenticator, DefaultAuthenticatorDelegate, ApplicationSecret, MemoryStorage};
use dfareporting2d6::Dfareporting;

// Get an ApplicationSecret instance by some means. It contains the `client_id` and 
// `client_secret`, among other things.
let secret: ApplicationSecret = Default::default();
// Instantiate the authenticator. It will choose a suitable authentication flow for you, 
// unless you replace  `None` with the desired Flow.
// Provide your own `AuthenticatorDelegate` to adjust the way it operates and get feedback about 
// what's going on. You probably want to bring in your own `TokenStorage` to persist tokens and
// retrieve them from storage.
let auth = Authenticator::new(&secret, DefaultAuthenticatorDelegate,
                              hyper::Client::new(),
                              <MemoryStorage as Default>::default(), None);
let mut hub = Dfareporting::new(hyper::Client::new(), auth);
// You can configure optional parameters by calling the respective setters at will, and
// execute the final call using `doit()`.
// Values shown here are possibly random and not representative !
let result = hub.reports().list("profileId")
             .sort_order("sit")
             .sort_field("Stet")
             .scope("sed")
             .page_token("et")
             .max_results(-18)
             .doit();

match result {
    Err(e) => match e {
        // The Error enum provides details about what exactly happened.
        // You can also just use its `Debug`, `Display` or `Error` traits
         Error::HttpError(_)
        |Error::MissingAPIKey
        |Error::MissingToken(_)
        |Error::Cancelled
        |Error::UploadSizeLimitExceeded(_, _)
        |Error::Failure(_)
        |Error::BadRequest(_)
        |Error::FieldClash(_)
        |Error::JsonDecodeError(_, _) => println!("{}", e),
    },
    Ok(res) => println!("Success: {:?}", res),
}

```
## Handling Errors

All errors produced by the system are provided either as [Result](http://byron.github.io/google-apis-rs/google_dfareporting2d6/enum.Result.html) enumeration as return value of 
the doit() methods, or handed as possibly intermediate results to either the 
[Hub Delegate](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.Delegate.html), or the [Authenticator Delegate](http://byron.github.io/google-apis-rs/google_dfareporting2d6/../yup-oauth2/trait.AuthenticatorDelegate.html).

When delegates handle errors or intermediate values, they may have a chance to instruct the system to retry. This 
makes the system potentially resilient to all kinds of errors.

## Uploads and Downloads
If a method supports downloads, the response body, which is part of the [Result](http://byron.github.io/google-apis-rs/google_dfareporting2d6/enum.Result.html), should be
read by you to obtain the media.
If such a method also supports a [Response Result](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.ResponseResult.html), it will return that by default.
You can see it as meta-data for the actual media. To trigger a media download, you will have to set up the builder by making
this call: `.param("alt", "media")`.

Methods supporting uploads can do so using up to 2 different protocols: 
*simple* and *resumable*. The distinctiveness of each is represented by customized 
`doit(...)` methods, which are then named `upload(...)` and `upload_resumable(...)` respectively.

## Customization and Callbacks

You may alter the way an `doit()` method is called by providing a [delegate](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.Delegate.html) to the 
[Method Builder](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.CallBuilder.html) before making the final `doit()` call. 
Respective methods will be called to provide progress information, as well as determine whether the system should 
retry on failure.

The [delegate trait](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.Delegate.html) is default-implemented, allowing you to customize it with minimal effort.

## Optional Parts in Server-Requests

All structures provided by this library are made to be [enocodable](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.RequestValue.html) and 
[decodable](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.ResponseResult.html) via *json*. Optionals are used to indicate that partial requests are responses 
are valid.
Most optionals are are considered [Parts](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.Part.html) which are identifiable by name, which will be sent to 
the server to indicate either the set parts of the request or the desired parts in the response.

## Builder Arguments

Using [method builders](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.CallBuilder.html), you are able to prepare an action call by repeatedly calling it's methods.
These will always take a single argument, for which the following statements are true.

* [PODs][wiki-pod] are handed by copy
* strings are passed as `&str`
* [request values](http://byron.github.io/google-apis-rs/google_dfareporting2d6/trait.RequestValue.html) are moved

Arguments will always be copied or cloned into the builder, to make them independent of their original life times.

[wiki-pod]: http://en.wikipedia.org/wiki/Plain_old_data_structure
[builder-pattern]: http://en.wikipedia.org/wiki/Builder_pattern
[google-go-api]: https://github.com/google/google-api-go-client

# License
The **dfareporting2d6** library was generated by Sebastian Thiel, and is placed 
under the *MIT* license.
You can read the full text at the repository's [license file][repo-license].

[repo-license]: https://github.com/Byron/google-apis-rs/LICENSE.md
