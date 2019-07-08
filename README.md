# ![LOGO](logo.png) Just Eat UK **flow**ground Connector

## Description

A generated **flow**ground connector for the Just Eat UK API (version v1).

Generated from: https://api.apis.guru/v2/specs/just-eat.co.uk/v1/swagger.json<br/>
Generated at: 2019-07-08T14:13:34+03:00

## API Description

<h3>Delivery Service API</h3><p>Some calls require HTTPS and an Authorization Key which will be provided by Just Eat.<p><p>The key needs to be provided in the header as follows: <b>Authorization: JE-API-KEY {Your-Key-Here}</b></p>

## Authorization

This API does not require authorization.

## Actions

### Delivery_DeliverableRestaurants
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `toLat` - _optional_
* `toLon` - _optional_
* `toPostcode` - _optional_
* `Authorization` - _required_ - access token<br/>

### Delivery_Estimate
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `restaurantReference` - _required_
* `toLat` - _optional_
* `toLon` - _optional_
* `toPostcode` - _optional_
* `Authorization` - _required_ - access token<br/>

### get_health_check

*Tags:* `Health`

### get_health_validate

*Tags:* `Health`

### get_healthcheck

*Tags:* `Health`

### Delivery_BulkDriverLocations
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `Authorization` - _required_ - access token<br/>

### Delivery_AtDeliveryAddress
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `id` - _required_
* `Authorization` - _required_ - access token<br/>

### Delivery_AtRestaurant
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `id` - _required_
* `Authorization` - _required_ - access token<br/>

### Delivery_Delivered
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `id` - _required_
* `Authorization` - _required_ - access token<br/>

### Delivery_DriverAssigned
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `id` - _required_
* `Authorization` - _required_ - access token<br/>

### Delivery_DriverLocation
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `id` - _required_
* `Authorization` - _required_ - access token<br/>

### Delivery_OnItsWay
> - This method requires the use of an Authorization Key.<br/>

*Tags:* `Delivery`

#### Input Parameters
* `id` - _required_
* `Authorization` - _required_ - access token<br/>

## License

**flow**ground :- Telekom iPaaS / just-eat-co-uk-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
