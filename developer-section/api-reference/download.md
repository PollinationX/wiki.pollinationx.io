---
description: >-
  This API allows you to download a file from the decentralized storage using
  its Content Identifier (CID)
---

# Download

{% hint style="info" %}
**Good to know:** Consider the size of the file you are downloading and the network conditions. Larger files may take longer to download, so ensure that your application handles file downloads efficiently and provides progress indications if needed.
{% endhint %}

## Download file

## Download file

<mark style="color:green;">`POST`</mark> `/api/v1/get`

API endpoint and JWT token is available in [Authenticate user](download.md#authenticate-user) api response.&#x20;

#### Query Parameters

| Name                                  | Type   | Description                                                                                         |
| ------------------------------------- | ------ | --------------------------------------------------------------------------------------------------- |
| arg<mark style="color:red;">\*</mark> | String | The Content Identifier (CID) of the file you want to download from the decentralized storage system |

#### Headers

| Name                                            | Type                | Description                                         |
| ----------------------------------------------- | ------------------- | --------------------------------------------------- |
| Authorization<mark style="color:red;">\*</mark> | Bearer \<jwt token> | he authentication token required to access the API. |

{% tabs %}
{% tab title="200 The request was successful" %}
```
Binary image
```
{% endtab %}

{% tab title="500: Internal Server Error An error occurred while processing the request" %}


```json
{ error: Error message }
```
{% endtab %}

{% tab title="401: Unauthorized The request lacks valid authentication credentials or the provided token is invalid" %}

{% endtab %}
{% endtabs %}

{% hint style="info" %}
The provided CID (`"Hash"`) in api response can be used to interact with the decentralized storage system to retrieve or manipulate the file as needed.
{% endhint %}
