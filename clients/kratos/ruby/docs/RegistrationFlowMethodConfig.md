# OryHydraClient::RegistrationFlowMethodConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**action** | **String** | Action should be used as the form action URL &#x60;&lt;form action&#x3D;\&quot;{{ .Action }}\&quot; method&#x3D;\&quot;post\&quot;&gt;&#x60;. | 
**fields** | [**Array&lt;FormField&gt;**](FormField.md) | Fields contains multiple fields | 
**messages** | [**Array&lt;Message&gt;**](Message.md) |  | [optional] 
**method** | **String** | Method is the form method (e.g. POST) | 
**providers** | [**Array&lt;FormField&gt;**](FormField.md) | Providers is set for the \&quot;oidc\&quot; registration method. | [optional] 

## Code Sample

```ruby
require 'OryHydraClient'

instance = OryHydraClient::RegistrationFlowMethodConfig.new(action: null,
                                 fields: null,
                                 messages: null,
                                 method: null,
                                 providers: null)
```


