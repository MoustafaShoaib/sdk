# OryHydraClient::RecoveryLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expires_at** | **DateTime** | Recovery Link Expires At  The timestamp when the recovery link expires. | [optional] 
**recovery_link** | **String** | Recovery Link  This link can be used to recover the account. | 

## Code Sample

```ruby
require 'OryHydraClient'

instance = OryHydraClient::RecoveryLink.new(expires_at: null,
                                 recovery_link: null)
```

