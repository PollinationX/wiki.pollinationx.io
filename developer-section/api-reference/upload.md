---
description: This API endpoint allows you to add a file to the decentralized storage.
---

# Upload

{% hint style="info" %}
**Good to know:** Upload API automatically checks the NFT holder storage quota.&#x20;
{% endhint %}

{% hint style="warning" %}
If using API for uploading, files are not encrypted. Do not store any private or sensitive information in an unencrypted way. If you want encryption out of the box consider using our [PollinationX SDK](../pollinationx-sdk/).
{% endhint %}

## Upload file

## Upload file

<mark style="color:green;">`POST`</mark> `/api/v1/add`

API endpoint and JWT token is available in [Authenticate user](upload.md#authenticate-user) api response.&#x20;

#### Headers

| Name                                            | Type                | Description                                         |
| ----------------------------------------------- | ------------------- | --------------------------------------------------- |
| Authorization<mark style="color:red;">\*</mark> | Bearer \<jwt token> | he authentication token required to access the API. |

#### Request Body

| Name                                   | Type                | Description                        |
| -------------------------------------- | ------------------- | ---------------------------------- |
| file<mark style="color:red;">\*</mark> | multipart/form-data | The file to be added to the system |

{% tabs %}
{% tab title="200 The request was successful" %}
```json
{
	"Name": "The name of the uploaded file",
	"Hash": "The Content Identifier (CID) of the file on the decentralized storage. It uniquely identifies the file and can be used to retrieve or reference it.",
	"Size": "The size of the uploaded file in bytes"
}
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
