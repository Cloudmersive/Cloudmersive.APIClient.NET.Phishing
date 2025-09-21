# Cloudmersive.APIClient.NET.Phishing.Model.AdvancedEmailDetectionRequest
Request to detect phishing from an email

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromEmailAddress** | **string** | Email address of the sender | [optional] 
**ToEmailAddress** | **string** | Email address of the recipient | [optional] 
**Subject** | **string** | Subject of the email | [optional] 
**HtmlBody** | **string** | Body of the email in HTML, or text | [optional] 
**AllowLowReputationSenders** | **bool** | Allow email from low reputation senders and domains | [optional] 
**AllowSanctioned** | **bool** | True to allow sanctioned countries and certain known sanctioned entities, false otherwise (default) | [optional] 
**InputEmailFile** | **byte[]** |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

