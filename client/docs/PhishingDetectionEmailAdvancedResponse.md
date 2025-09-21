# Cloudmersive.APIClient.NET.Phishing.Model.PhishingDetectionEmailAdvancedResponse
Result of detecting phishing using AI

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CleanResult** | **bool** | True if the result is not phishing (clean), and false otherwise | [optional] 
**PhishingRiskLevel** | **double** | Overall phishing risk level between 0.0 and 1.0 | [optional] 
**SpamRiskLevel** | **double** | Overall phishing spam level between 0.0 and 1.0 | [optional] 
**ContainsLowReputationSender** | **bool** | True if the input email is from a low reputation sender | [optional] 
**ContainsPhishing** | **bool** | True if the input email contains phishing threat risks, false otherwise | [optional] 
**ContainsSpam** | **bool** | True if the email contains phishing threat risks, false otherwise | [optional] 
**ContainsUnsolicitedSales** | **bool** | True if the input email contains unsolicited sales, false otherwise | [optional] 
**ContainsPromotionalContent** | **bool** | True if the input email contains promotional content, false otherwise | [optional] 
**ContainsPhishingAttempt** | **bool** | True if the input email contains a phishing attempt, false otherwise | [optional] 
**AnalysisRationale** | **string** | Rationale for why the conclusion was formed | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

