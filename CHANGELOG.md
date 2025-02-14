# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [5.0.0](https://github.com/box/box-windows-sdk-v2/compare/v4.6.0...v5.0.0) (2023-01-12)


### ⚠ BREAKING CHANGES

* upgrade .net framework to 4.6.2 (#881)
* remove deprecated methods (#881)
* remove `use_index` references (#881)
* return proper object from `GetFileVersionsUnderRetentionForAssignmentAsync`(#881)

### **New Features and Enhancements:**

* upgrade .net framework to 4.6.2 ([#881](https://github.com/box/box-windows-sdk-v2/issues/881)) ([f1989aa](https://github.com/box/box-windows-sdk-v2/commit/f1989aa94cd085ad4bec04b4ebedb04f40455569)), closes [#863](https://github.com/box/box-windows-sdk-v2/issues/863) 
* remove deprecated methods ([#881](https://github.com/box/box-windows-sdk-v2/issues/881)) ([f1989aa](https://github.com/box/box-windows-sdk-v2/commit/f1989aa94cd085ad4bec04b4ebedb04f40455569)), closes [#874](https://github.com/box/box-windows-sdk-v2/issues/874)
* remove `use_index` references ([#881](https://github.com/box/box-windows-sdk-v2/issues/881)) ([f1989aa](https://github.com/box/box-windows-sdk-v2/commit/f1989aa94cd085ad4bec04b4ebedb04f40455569)), closes [#870](https://github.com/box/box-windows-sdk-v2/issues/870)

### **Bug Fixes:**

* Added pagination option to `IBoxFilesManager#ViewVersionsAsync` ([#869](https://github.com/box/box-windows-sdk-v2/issues/869)) ([2324495](https://github.com/box/box-windows-sdk-v2/commit/232449531440227a0c8b3489ceda813fe4f4a73f)), closes [#866](https://github.com/box/box-windows-sdk-v2/issues/866)
* return proper object from `GetFileVersionsUnderRetentionForAssignmentAsync` ([#881](https://github.com/box/box-windows-sdk-v2/issues/881)) ([f1989aa](https://github.com/box/box-windows-sdk-v2/commit/f1989aa94cd085ad4bec04b4ebedb04f40455569)), closes [#875](https://github.com/box/box-windows-sdk-v2/issues/875)

## [4.6.0](https://github.com/box/box-windows-sdk-v2/compare/v4.5.0...v4.6.0) (2022-10-18)


### **New Features and Enhancements:**

* Add `redirect_url` and `declined_redirect_url` to Sign Request ([#853](https://github.com/box/box-windows-sdk-v2/issues/853)) ([5ef2f18](https://github.com/box/box-windows-sdk-v2/commit/5ef2f18985d8c3b8e7c0cdba5709785bfb1d5f34))
* Add support for modifiable retention policies & enable deleting retention policy assignment ([#856](https://github.com/box/box-windows-sdk-v2/issues/856)) ([564904f](https://github.com/box/box-windows-sdk-v2/commit/564904fa2ce0b1881a2f07b80cc3bb3e648310d0))

## [4.5.0](https://github.com/box/box-windows-sdk-v2/compare/v4.4.0...v4.5.0) (2022-08-24)


### **New Features and Enhancements:**

* Add `content-type` field to sign request ([#850](https://github.com/box/box-windows-sdk-v2/issues/850)) ([054d3e1](https://github.com/box/box-windows-sdk-v2/commit/054d3e1a5f44b6a4a0292e8f9444266b2de0fff0))
* expose `effective_access` in `BoxSharedLink` [#843](https://github.com/box/box-windows-sdk-v2/issues/843) ([d84ddd4](https://github.com/box/box-windows-sdk-v2/commit/d84ddd48aac489ecdd1d9dc740a7672cb064b0ca))


### **Bug Fixes:**

* fix null reference exception when it's not possible to get `runtime` version from the assembly ([#851](https://github.com/box/box-windows-sdk-v2/issues/851)) ([77046fb](https://github.com/box/box-windows-sdk-v2/commit/77046fb0c1ce80b6e7e2dc30058ed275e46e990c))
* replace infinite retries with exponential backoff strategy in file representations ([#835](https://github.com/box/box-windows-sdk-v2/issues/835)) ([f2a5713](https://github.com/box/box-windows-sdk-v2/commit/f2a57136078de8b1fc59ec2c4a9e98c062d9d19b))

## [4.4.0](https://github.com/box/box-windows-sdk-v2/compare/v4.3.1...v4.4.0) (2022-06-14)


### **New Features and Enhancements:**

* add `can_edit` field to `SharedLink` ([#831](https://github.com/box/box-windows-sdk-v2/issues/831)) ([e0d4197](https://github.com/box/box-windows-sdk-v2/commit/e0d4197070db0dbd947f4a51a6bbb1e01c0b0cdf))
* add `version_number` to `BoxFileVersion` ([#820](https://github.com/box/box-windows-sdk-v2/issues/820)) ([f174358](https://github.com/box/box-windows-sdk-v2/commit/f174358973caefc9262df480208341fd8233dc7f))
* add upload and delete support for Avatar API ([#829](https://github.com/box/box-windows-sdk-v2/issues/829)) ([4dcb84a](https://github.com/box/box-windows-sdk-v2/commit/4dcb84ade78d6bd0bc621ff2ed7f5f886486858a))

### **Bug Fixes:**

* Fix initialization of `BoxAPIException` object ([#828](https://github.com/box/box-windows-sdk-v2/issues/828)) ([a298f01](https://github.com/box/box-windows-sdk-v2/commit/a298f01187f84200825ec6ed4748fe8bbd717d11))
* properly dispose response on exception ([#819](https://github.com/box/box-windows-sdk-v2/issues/819)) ([8415bd3](https://github.com/box/box-windows-sdk-v2/commit/8415bd3dbe42910b99f99535247a26f8d8e645c1))


### [4.3.1](https://github.com/box/box-windows-sdk-v2/compare/v4.3.0...v4.3.1) (2022-04-19)


### **Bug Fixes:**

* simplify base `urls` usage ([#815](https://github.com/box/box-windows-sdk-v2/issues/815)) ([f8e7344](https://github.com/box/box-windows-sdk-v2/commit/f8e73447afa5c0a893c3c4ace922fc360a376f66))

## [4.3.0](https://github.com/box/box-windows-sdk-v2/compare/v4.2.0...v4.3.0) (2022-04-01)


### **New Features and Enhancements:**

* add `SourceLink` support for Core project ([#795](https://github.com/box/box-windows-sdk-v2/issues/795)) ([a9cbede](https://github.com/box/box-windows-sdk-v2/commit/a9cbedece2ffb4f832be880bebf35b715c9cb28b))


### **Bug Fixes:**

* add missing enum to string parsing in several places ([#813](https://github.com/box/box-windows-sdk-v2/issues/813)) ([e370282](https://github.com/box/box-windows-sdk-v2/commit/e3702826216132dfe1fb061af95a8d9700f114d4))
* properly cast response when uploading a new file version using session ([#810](https://github.com/box/box-windows-sdk-v2/issues/810)) ([73d877f](https://github.com/box/box-windows-sdk-v2/commit/73d877ff679b5999ea50cdfa68f14b0e2169ea65))

## [4.2.0](https://github.com/box/box-windows-sdk-v2/compare/v4.1.0...v4.2.0) (2022-02-10)


### **Bug Fixes:**

* correctly pass null when rolling out user from the enterprise ([#792](https://github.com/box/box-windows-sdk-v2/issues/792)) ([c85c573](https://github.com/box/box-windows-sdk-v2/commit/c85c5735865b7dd97ffa1428a8f57d2edff6811b))
* Creating BoxAuthenticationFailedException no longer throws an exception ([#790](https://github.com/box/box-windows-sdk-v2/issues/790)) ([55a706e](https://github.com/box/box-windows-sdk-v2/commit/55a706e4091271aa55208a260b2f4f96e1527698))
* Null Argument Exception in AutoPaginate ([#666](https://github.com/box/box-windows-sdk-v2/issues/666)) ([c61f08c](https://github.com/box/box-windows-sdk-v2/commit/c61f08cc02d5c95ff71ef700e97393a0dc3dc890))


### **New Features and Enhancements:**

* add admin_logs_streaming support ([#797](https://github.com/box/box-windows-sdk-v2/issues/797)) ([a775e1e](https://github.com/box/box-windows-sdk-v2/commit/a775e1e5c7696a1e5f82b5dc7edbed8eb09f640d))
* add Client Credentials Grant auth support ([#799](https://github.com/box/box-windows-sdk-v2/issues/799)) ([b8a64ca](https://github.com/box/box-windows-sdk-v2/commit/b8a64ca3887298feccef5185f6bfec4c3771b5a9))
* add disposition_at field to the File object ([#793](https://github.com/box/box-windows-sdk-v2/issues/793)) ([2766a91](https://github.com/box/box-windows-sdk-v2/commit/2766a914fad1eb40371cd4430b3450360088b331))
* add possibility to set auth token uri in BoxConfig ([#794](https://github.com/box/box-windows-sdk-v2/issues/794)) ([ae8cd8b](https://github.com/box/box-windows-sdk-v2/commit/ae8cd8b91dd91b8a786e53ff5b3501d2700686a4))
* deprecate index_name in ExecuteMetadataQuery ([#800](https://github.com/box/box-windows-sdk-v2/issues/800)) ([6a6a0e4](https://github.com/box/box-windows-sdk-v2/commit/6a6a0e4a0e41ec70ec33acacba00bee6c7ee881f))

## [4.1.0](https://github.com/box/box-windows-sdk-v2/compare/v4.0.0...v4.1.0) (2021-12-14)


### **Bug Fixes:**

* add missing configureAwait(false) when awaiting to prevent deadlocks ([#775](https://github.com/box/box-windows-sdk-v2/issues/775)) ([b16267e](https://github.com/box/box-windows-sdk-v2/commit/b16267e8f3dca5396e87be660e30a1e9405d8139))


### **New Features and Enhancements:**

* add configurable Timeout for BoxClient ([#779](https://github.com/box/box-windows-sdk-v2/issues/779)) ([ac842ed](https://github.com/box/box-windows-sdk-v2/commit/ac842ed4ba1a2dfe499706524441bc6ae3b3c192))
* add file request api ([#777](https://github.com/box/box-windows-sdk-v2/issues/777)) ([1098f75](https://github.com/box/box-windows-sdk-v2/commit/1098f75983e2d784521f13b8d53df0e55d03203b))
* add vanity_name to SharedLink ([#782](https://github.com/box/box-windows-sdk-v2/issues/782)) ([00a1e26](https://github.com/box/box-windows-sdk-v2/commit/00a1e265569d76c2c9593aa259202d7febef629c))

## [4.0.0](https://github.com/box/box-windows-sdk-v2/compare/v3.26.0...v4.0.0) (2021-11-02)


### **Breaking changes:**

* Extract interfaces for BoxClient and Managers to improve testability ([#603](https://github.com/box/box-windows-sdk-v2/pull/603))
* Add BoxConfigBuilder and make BoxConfig immutable ([#737](https://github.com/box/box-windows-sdk-v2/pull/737))
* Expose tasks from async methods ([#742](https://github.com/box/box-windows-sdk-v2/pull/742))
* Use DateTimeOffset instead of DateTime ([#749](https://github.com/box/box-windows-sdk-v2/pull/749))
* Rework returned exceptions ([#753](https://github.com/box/box-windows-sdk-v2/pull/753))
* Upgrade .NET Standard to 2.0 ([#755](https://github.com/box/box-windows-sdk-v2/pull/755))

### **New Features and Enhancements:**

* Add ability to get files under retention for assignment and file versions under retention for assignment ([#734](https://github.com/box/box-windows-sdk-v2/pull/734))
* Add `is_collaboration_restricted_to_enterprise` flag support for `Folder` update ([#732](https://github.com/box/box-windows-sdk-v2/pull/732))
* Replace insensitive language ([#738](https://github.com/box/box-windows-sdk-v2/pull/738))
* Add new, easier to use method for create terms of service user status ([#740](https://github.com/box/box-windows-sdk-v2/pull/740))
* Allow sort and direction parameter to be passed in when getting trashed items ([#754](https://github.com/box/box-windows-sdk-v2/pull/754))
* Add support for Task completion_rule field ([#758](https://github.com/box/box-windows-sdk-v2/pull/758))
* Add BoxSign API support ([#765](https://github.com/box/box-windows-sdk-v2/pull/765))

### **Bug Fixes:**
* Fix `Cannot access a closed Stream.Request` exception during upload ([#739](https://github.com/box/box-windows-sdk-v2/pull/739)) ([#757](https://github.com/box/box-windows-sdk-v2/pull/757))

## 3.26.0 [2021-04-01]

**New Features and Enhancements:**

- Add filter fields to get file version retentions ([#717](https://github.com/box/box-windows-sdk-v2/pull/717))
- Add support for search param to get shared link items ([#721](https://github.com/box/box-windows-sdk-v2/pull/721))
- Add folder lock functionality ([#725](https://github.com/box/box-windows-sdk-v2/pull/725))

## 3.25.0 [2020-10-19]

**New Features and Enhancements:**

- Add support for filtering when getting Groups (#703)
- Add zip functionality (#700)
- Deprecate one of the overloaded `ExecuteMetadataQueryAsync()` methods (#699)
- Add support for `copyInstanceOnItemCopy` field for metadata templates  (#698) 

**Bug Fixes:**

- Fix bug with JWT Authentication automatic retry (#697)

## 3.24.0 [2020-07-21]
- Add path parameter sanitization
- Add support for the classification field for Files and Folders
- Fix bug with notification email field deserializing for `BoxUser` 
- Add `fields` parameter for metadata query
- Add ability to set a request timeout for `FoldersManager.UpdateInformationAsync()` and `UsersManager.MoverUserFolderAsync()`

## 3.23.0 [2020-05-12]
- Add ability to get and set a notification email address for a user
- Fix deadlock issue for JWT authentication in UI elements
- Add support for the uploader display name field for Files and File Versions

## 3.22.0 [2020-02-25]
- Fixed Authentication Request Retries
- Added the ability to query Box items based on their metadata. The method to do so is `MetadataManager.ExecuteMetadataQueryAsync()`.
- Added `TrashedAt` field to `BoxItem` objects (file, folder, weblink).
- Added marker based pagination for get users methods
- Updated retry logic to retry on 503 status codes returned by the API
- Provide better details for debugging, if the HttpClient used to make API requests times out

## 3.21.0 [2019-12-05]
- Added `fields` parameter to `UsersManager.GetUserInformationAsync()`
- Added `ExternalAppUserId` property to `BoxUser` model
- Added the ability to set the `TrackingCodes` property when updating or creating a user (thanks @Cpcrook!)

## 3.20.0 [2019-09-19]
- Added missing fields for File Version object.

## 3.19.0 [2019-08-29]
- Added `FILE_VERSION_RESTORE` constant to Admin Event.
- Added action_by field to Enterprise Event.
- Audited missing fields on BoxFile and BoxFolder objects.
- Better error handling and messaging for errors pertaining to OAuth2 error responses.

## 3.18.0 [2019-06-20]

- Added `sort` and `direction` parameters to `FoldersManager.GetFolderItemsAsync()` to enable
  sorting the folder items returned
- Added a new `SearchManager.QueryAsync()` method with correct types for file size filter parameters
- Deprecated the `SearchManager.SearchAsync()` method, which is superseded by `SearchManager.QueryAsync()`
- Added support for setting the `IsExternalCollabRestricted` parameter when creating and updating Users
- Added a `WebProxy` property to `BoxConfig` instances, which can be used to manually set the network proxy
  used by the SDK

## 3.17.0 [2019-05-09]

- Fixed the encoding of dates in the query parameters for Events and Search endpoints
- Deprecated `FilesManager.DownloadStreamAsync()` and introduced a replacement method with correct parameter types for byte offsets: `FilesManager.DownloadAsync()`

## 3.16.0 [2019-04-29]

- Added `sort` and `direction` parameters to `client.SearchManager.SearchAsync()` to  control sort order
- Added `extension` parameter to `client.FilesManager.GetThumbnailAsync()` to control which thumbnail format is returned (thanks @guilmori!)
- Fixed a bug where query string parameters were not correctly encoded
- Added `SetFileMetadataAsync()` and `SetFolderMetadataAsync()` methods to `client.MetadataManager` to set metadata
  keys and values, overwriting existing values for the provided keys.
- Automatically retry most API calls when the API responds with a transient error status code

## 3.15.0 [2019-03-28]

- Added support for passing custom IBoxService to BoxJWTAuth constructor.

## 3.14.1 [2019-03-07]

- Removed unnecessary package.config from sample files.

## 3.14.0 [2019-02-28]

- Added trace ID to API response exception message.
- Fix deserialization of translated task assignment status.

## 3.13.1 [2019-02-21]

- Fixed an issue where some objects related to Events did not have their `.Id` property correctly deserialized from JSON

## 3.13.0 [2019-02-14]

- Added the `.InviteEmail` property to `BoxCollaboration` objects, which displays the email address for the invited
  user in a pending collaboration
- Added `.Timezone`, `.IsExternalCollabRestricted`, `.Tags`, and `.Hostname` properties to `BoxUser` objects

## 3.12.0 [2019-02-07]

- Added `client.FilesManager.GetCollaborationsCollectionAsync()` and deprecated
  `client.FilesManager.GetCollaborationsAsync()` to enable paging through the entire
  collection of collaborations on a file
- Added `client.WebLinksManager.CopyAsync()`, `client.WebLinksManager.CreateSharedLinkAsync()`,
  and `client.WebLinksManager.DeleteSharedLinkAsync()`
- Added `client.UsersManager.GetUserAvatarAsync()` for retrieving a user's avatar image

## 3.11.0 [2019-01-17]

- Added support for reading and writing more Group fields
- Fixed an issue where the `UnsharedAt` field of a shared link could not be set to `null`
- Fixed renaming a file on new version upload
- Added the ability to set the content modification timestamp on file version upload
- Fixed issues around reading the source of an event when the source item is a web link

## 3.10.0 [2018-12-14]

- Added support for Metadata Cascade Policies

## 3.9.3 [2018-09-04]

- Strong named the assembly.

## 3.9.2 [2018-06-14]

- Added support for [setting flag](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Models/Request/BoxFolderRequest.cs#L39) allowing non owners of a folder to invite collaborators.

## 3.9.1 [2018-06-07]

- Fixed bug where Xamarin applications would run out of connections

## 3.9.0 [2018-05-10]

- Added support for Storage Policies

## 3.8.0 [2018-04-30]

- Fixed an issue where users could not create `BoxClient` on Xamarin
- Added `File` property to `BoxLock` objects in events
- Added `MetadataManager.DeleteMetadataTemplate(string scope, string template)` for deleting a Metadata template 
- Made API URLs modifiable in `BoxConfig`
- Improved API response error objects/messages

## 3.7.0 [2018-04-10]

- Added support for assigning a Retention Policy to a metadata template
- Added `CONTENT_ACCESS` event type to enum

## 3.6.0 [2018-03-27]

- Fixed an issue where a "Security protocol not supported" exception could be thrown on MacOS
- Added `client.FilesManager.GetRepresentationContentAsync()` for fetching a stream over representation contents
- Fixed parsing of some `Source` objects on `BoxEvent` objects

## 3.5.2 [2018-03-21]

- Switched to exponential backoff when the SDK receives a rate limit or server error response. 
- Force support for TLSv1.1 or higher when available to improve the security of connections to the Box API.
- Perform modified retry on JWT auth for when the local clock and the Box Server clock are not aligned as well as if the JWT ID has already been consumed.
- Made `name` parameter optional on `RestoreTrashedAsync()`.

## 3.4.2 [2018-01-31]

- Deprecated `uploadFileVersionUsingSessionAsync()`(which returned just a Box File Version) in favor of `uploadNewVersionUsingSessionAsync()`(which returns the entire Box File object containing the Box File Version).
- Added support for OAuth2 access token creation type to the AdminEventTypesEnum 
- Added `ExpiresAt` param to `BoxCollaborationRequest`. 

## 3.4.1 [2018-01-09]

- Added support for [Collaboration Whitelist](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxCollaborationWhitelistManager.cs) endpoint
- Added [Event Types Enum](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Config/Constants.cs#L287)
- Fixed deserialization issue with BoxRepresentationStatus (#429)

## 3.3.0 [2017-11-22]

- Added support for [Terms of Service](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxTermsOfServiceManager.cs) endpoint
- Added support for [Metadata Template ID](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxMetadataManager.cs#L175) endpoint
- Added missing fields for Folder Model (#414) 

## 3.2.0 [2017-10-04]

- Added support for [Representations](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxFilesManager.cs#L1216) endpoint
- Added support for [Chunked Upload New File Version](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxFilesManager.cs#L423)
- Fixed BoxEventsManager DateTime formatter (#400)

## 3.1.0 [2017-08-18]

- Added Unified Metadata Support (#379)

## 3.0.0 [2017-07-28]

- Major version bump to 3, targeting net45
- Upgrading the whole sln to vs2017
- Added support for [Recents](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxRecentItemsManager.cs#L1) endpoint
- New operation on [Metadata](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxMetadataManager.cs#L1) endpoint
- Progress on [Chunked Upload New File](https://github.com/box/box-windows-sdk-v2/blob/main/Box.V2/Managers/BoxFilesManager.cs#L463)
- Minor bug fixes






