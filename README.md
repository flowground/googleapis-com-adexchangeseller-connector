# ![LOGO](logo.png) Ad Exchange Seller **flow**ground Connector

## Description

A generated **flow**ground connector for the Ad Exchange Seller API (version v2.0).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/adexchangeseller/v2.0/swagger.json<br/>
Generated at: 2019-05-23T12:12:54+03:00

## API Description

Accesses the inventory of Ad Exchange seller users and generates reports.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List all accounts available to this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of accounts to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through accounts. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get information about the selected Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to get information about. Tip: 'myaccount' is a valid ID.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all ad clients in this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `maxResults` - _optional_ - The maximum number of ad clients to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through ad clients. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all custom channels in the specified ad client for this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client for which to list custom channels.
* `maxResults` - _optional_ - The maximum number of custom channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through custom channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get the specified custom channel from the specified ad client.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client which contains the custom channel.
* `customChannelId` - _required_ - Custom channel to retrieve.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List all URL channels in the specified ad client for this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account to which the ad client belongs.
* `adClientId` - _required_ - Ad client for which to list URL channels.
* `maxResults` - _optional_ - The maximum number of URL channels to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through URL channels. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the alerts for this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account owning the alerts.
* `locale` - _optional_ - The locale to use for translating alert messages. The account locale will be used if this is not supplied. The AdSense default (English) will be used if the supplied locale is invalid or unsupported.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the metadata for the dimensions available to this AdExchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account with visibility to the dimensions.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the metadata for the metrics available to this AdExchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account with visibility to the metrics.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### List the preferred deals for this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account owning the deals.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Get information about the selected Ad Exchange Preferred Deal.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account owning the deal.
* `dealId` - _required_ - Preferred deal to get information about.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an Ad Exchange report based on the report request sent in the query parameters. Returns the result as JSON; to retrieve output in CSV format specify "alt=csv" as a query parameter.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account which owns the generated report.
* `dimension` - _optional_ - Dimensions to base the report on.
* `endDate` - _required_ - End of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `filter` - _optional_ - Filters to be run on the report.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `metric` - _optional_ - Numeric columns to include in the report.
* `sort` - _optional_ - The name of a dimension or metric to sort the resulting report on, optionally prefixed with "+" to sort ascending or "-" to sort descending. If no prefix is specified, the column is sorted ascending.
* `startDate` - _required_ - Start of the date range to report on in "YYYY-MM-DD" format, inclusive.
* `startIndex` - _optional_ - Index of the first row of report data to return.

### List all saved reports in this Ad Exchange account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account owning the saved reports.
* `maxResults` - _optional_ - The maximum number of saved reports to include in the response, used for paging.
* `pageToken` - _optional_ - A continuation token, used to page through saved reports. To retrieve the next page, set this parameter to the value of "nextPageToken" from the previous response.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Generate an Ad Exchange report based on the saved report ID sent in the query parameters.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - Account owning the saved report.
* `locale` - _optional_ - Optional locale to use for translating report output to a local language. Defaults to "en_US" if not specified.
* `maxResults` - _optional_ - The maximum number of rows of report data to return.
* `savedReportId` - _required_ - The saved report to retrieve.
* `startIndex` - _optional_ - Index of the first row of report data to return.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-adexchangeseller-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
