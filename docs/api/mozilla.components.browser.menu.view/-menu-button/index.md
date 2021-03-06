[android-components](../../index.md) / [mozilla.components.browser.menu.view](../index.md) / [MenuButton](./index.md)

# MenuButton

`class MenuButton` [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/menu/src/main/java/mozilla/components/browser/menu/view/MenuButton.kt#L27)

A `three-dot` button used for expanding menus.

If you are using a browser toolbar, do not use this class directly.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MenuButton(context: <ERROR CLASS>, attrs: <ERROR CLASS>? = null, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0)`<br>A `three-dot` button used for expanding menus. |

### Properties

| Name | Summary |
|---|---|
| [getOrientation](get-orientation.md) | `var getOrientation: () -> `[`Orientation`](../../mozilla.components.browser.menu/-browser-menu/-orientation/index.md)<br>Callback to get the orientation for the menu. This is called every time the menu should be displayed. |
| [menuBuilder](menu-builder.md) | `var menuBuilder: `[`BrowserMenuBuilder`](../../mozilla.components.browser.menu/-browser-menu-builder/index.md)`?` |
| [onDismiss](on-dismiss.md) | `var onDismiss: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Listener called when the menu is dismissed. |
| [onShow](on-show.md) | `var onShow: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Listener called when the menu is shown. |

### Functions

| Name | Summary |
|---|---|
| [dismissMenu](dismiss-menu.md) | `fun dismissMenu(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Dismiss the menu, if open. |
| [invalidateBrowserMenu](invalidate-browser-menu.md) | `fun invalidateBrowserMenu(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Invalidates the [BrowserMenu](../../mozilla.components.browser.menu/-browser-menu/index.md), if open. |
| [onClick](on-click.md) | `fun onClick(v: <ERROR CLASS>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Shows the menu, or dismisses it if already open. |
| [setColorFilter](set-color-filter.md) | `fun setColorFilter(color: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets the tint of the 3-dot menu icon. |
| [setHighlight](set-highlight.md) | `fun setHighlight(highlight: `[`BrowserMenuHighlight`](../../mozilla.components.browser.menu/-browser-menu-highlight/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Show the indicator for a browser menu highlight. |

### Extension Functions

| Name | Summary |
|---|---|
| [loadResourceAsString](../../mozilla.components.support.test.file/kotlin.-any/load-resource-as-string.md) | `fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.loadResourceAsString(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Loads a file from the resources folder and returns its content as a string object. |
