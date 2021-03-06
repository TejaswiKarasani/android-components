[android-components](../../index.md) / [mozilla.components.concept.fetch](../index.md) / [Client](index.md) / [fetchDataUri](./fetch-data-uri.md)

# fetchDataUri

`protected fun fetchDataUri(request: `[`Request`](../-request/index.md)`): `[`Response`](../-response/index.md) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/concept/fetch/src/main/java/mozilla/components/concept/fetch/Client.kt#L54)

Generates a [Response](../-response/index.md) by decoding a base64 encoded data URI.

### Parameters

`request` - The [Request](../-request/index.md) for the data URI.

**Return**
The generated [Response](../-response/index.md) including the decoded bytes as body.

