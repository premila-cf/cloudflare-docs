---
_build:
  publishResources: false
  render: never
  list: never
---

If you want to use a [Universal SSL certificate](/ssl/edge-certificates/universal-ssl/enable-universal-ssl/), you will need to edit the `validation_method` [via the API](https://developers.cloudflare.com/api/operations/ssl-verification-edit-ssl-certificate-pack-validation-method) and specify your chosen validation method.

Alternatively, you could [order an advanced certificate](/ssl/edge-certificates/advanced-certificate-manager/manage-certificates/#create-a-certificate) via the API.