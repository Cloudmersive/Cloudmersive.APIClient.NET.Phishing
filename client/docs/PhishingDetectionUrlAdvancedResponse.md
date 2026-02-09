# Cloudmersive.APIClient.NET.Phishing.Model.PhishingDetectionUrlAdvancedResponse
Result of detecting phishing from a URL using AI

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CleanResult** | **bool** | True if the result is not phishing (clean), and false otherwise | [optional] 
**PhishingRiskLevel** | **double** | Overall phishing risk level between 0.0 and 1.0 | [optional] 
**IsSsrfThreat** | **bool** | True if the URL is an SSRF threat | [optional] 
**ContainsPhishing** | **bool** | True if the URL contains phishing threat risks, false otherwise | [optional] 
**ContainsUnsolicitedSales** | **bool** | True if the URL contains unsolicited sales, false otherwise | [optional] 
**ContainsPromotionalContent** | **bool** | True if the URL contains promotional content, false otherwise | [optional] 
**ContainsPhishingAttempt** | **bool** | True if the URL contains a phishing attempt, false otherwise | [optional] 
**AnalysisRationale** | **string** | Rationale for why the conclusion was formed | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

