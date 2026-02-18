# Cloudmersive.APIClient.NET.Phishing.Model.UnsafeUrlResult
Result of analyzing an individual URL found in text

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The URL that was detected and analyzed | [optional] 
**CleanResult** | **bool** | True if the result is not phishing (clean), and false otherwise | [optional] 
**IsSsrfThreat** | **bool** | True if the URL is an SSRF threat | [optional] 
**ContainsPhishing** | **bool** | True if the URL contains phishing threat risks, false otherwise | [optional] 
**ContainsPhishingAttempt** | **bool** | True if the URL contains a phishing attempt, false otherwise | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

