# readme-widgets

## Environment Variables

`AM_DEV_TOKEN`: MusicKit Developer Token  
`AM_USER_TOKEN`: MusicKit Music User Token

## Endpoints

### Apple Music Recently Played Widget

[<img src="https://coupy-readme-widg-24.deno.dev/recently-played" height="150" />](https://coupy-readme-widg-24.deno.dev/redirect?to=recently-played)  

**URL** `/recently-played`  
**Query Parameters**:
|Name|Type|Default|Description|
|---|---|---|---|
|artwork_size|String|708|Size of the artwork|
|language|String|en-US|Language of Apple Music|

### Redirect API

Set this address as where users will be redirected when they click on widgets

**URL** `/redirect`  
**Query Parameters**:
|Name|Type|Default|Description|
|---|---|---|---|
|to|"recently-played"|-|The endpoint of the widget the user clicked|
