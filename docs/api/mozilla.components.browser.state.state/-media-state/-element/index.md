[android-components](../../../index.md) / [mozilla.components.browser.state.state](../../index.md) / [MediaState](../index.md) / [Element](./index.md)

# Element

`data class Element` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/state/src/main/java/mozilla/components/browser/state/state/MediaState.kt#L41)

Value type representing a media element on a website.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Element(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString(), state: `[`State`](../../../mozilla.components.concept.engine.media/-media/-state/index.md)`, playbackState: `[`PlaybackState`](../../../mozilla.components.concept.engine.media/-media/-playback-state/index.md)`, controller: `[`Controller`](../../../mozilla.components.concept.engine.media/-media/-controller/index.md)`, metadata: `[`Metadata`](../../../mozilla.components.concept.engine.media/-media/-metadata/index.md)`)`<br>Value type representing a media element on a website. |

### Properties

| Name | Summary |
|---|---|
| [controller](controller.md) | `val controller: `[`Controller`](../../../mozilla.components.concept.engine.media/-media/-controller/index.md)<br>The [Controller](../../../mozilla.components.concept.engine.media/-media/-controller/index.md) for controlling playback of this media element. |
| [id](id.md) | `val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Unique ID for this media element. |
| [metadata](metadata.md) | `val metadata: `[`Metadata`](../../../mozilla.components.concept.engine.media/-media/-metadata/index.md)<br>The [Metadata](#) for this media element. |
| [playbackState](playback-state.md) | `val playbackState: `[`PlaybackState`](../../../mozilla.components.concept.engine.media/-media/-playback-state/index.md)<br>The current [PlaybackState](../../../mozilla.components.concept.engine.media/-media/-playback-state/index.md) of this media element. |
| [state](state.md) | `val state: `[`State`](../../../mozilla.components.concept.engine.media/-media/-state/index.md)<br>The current simplified [State](../-state/index.md) of this media element (derived from [playbackState](playback-state.md) events). |
