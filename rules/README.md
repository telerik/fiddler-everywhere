# Predefined Rules

The **Rules** functionality in Fiddler Everywhere is a powerful tool for tackling various web debugging tasks. The Fiddler team created rules presets that you can use directly or with minimal adjustments to fit your test cases.

>A rule in Fiddler contains a **matching condition** (or set of conditions) that determines the target HTTP sessions and an **action** (or set of actions) that applies to them.

All rules presets are available through the file in this folder called [all_rules_presets.farx](./all_rules_presets.farx). To use the file download it and use it in Fiddler Everywhere **Rules** tab. Alternatively, you can download only a specific rule through its corresponding folder in this repository.

The rules presets were conditionally separated into the following groups:

- Tooling &mdash; A set of rules that enables you to change different behaviors in the client or server. For example:
   * [Bypassing CORS](./bypass-cors/)
   * [Blocking cookies](./block-cookies/)
   * [Disabling the browser's cache](./no-caching/)
   * [Changing user-agent (Windows)](./changing-user-agent-chrome-windows/)
   * [Changing user-agent (macOS)](./changing-user-agent-chrome-macos/)

- Filters &mdash; A set of rules demonstrating how to show or hide targeted traffic. For example:
   * [Showing only localhost traffic](./show-only-localhost/)
   * [Showing only traffic from specific hosts](./show-only-specific-hosts/)
   * [Hiding traffic from specific hosts](./hide-specific-hosts/)
   * [Showing only traffic from specific processes](./show-only-specific-processes/)
   * [Hiding traffic from specific processes](./hide-specific-processes/)
   * [Hiding CONNECT Tunnels](./hide-connect-tunnels/)
   * [Hiding HTTP requests with resource content (like JS, CSS, images, fonts, etc.)](./hide-resource-requests/)

- Block Lists and Allow lists &mdash; A set of rules demonstrating how to block or allow target traffic. For example:
    * [Blocking traffic to specific hosts](./block-traffic-to-specific-hosts/)
    * [Allowing traffic only to specific hosts](./allow-traffic-only-from-specific-hosts/)
    * [Blocking traffic from specific processes](./block-traffic-to-specific-processes/)
    * [Allowing traffic only to specific processes](./allow-traffic-only-from-specific-processes/)

- Map Traffic &mdash; A set of rules that demonstrates how to redirect traffic and to mock HTTP requests and responses. For example:
    * [Mapping to remote URLs](./map-remote-utls/)
    * [Mapping to localhost addresses](./map-remote-localhost/)
    * [Mapping to a local file](./map-local-file/)
    * [Mapping to a manually created response](./map-local-manual/)
    * [Creating temporary redirect 307](./redirect-utl-307/)

- Modify Traffic &mdash; A set of rules demonstrating how to make custom modifications to sent HTTP requests and received HTTP responses. For example:
    * [Modifying the content of a response body](./modify-insert-html/)
    * [Modifying image URLs](./modify-image-endpoint-local/)

- UI Modifications &mdash; A set of rules demonstrating how to change the Fiddler's UI to fit your needs. For example:
    * [Highlighting long-living sessions](./mark-long-living-sessions/)
    * [Highlighting sessions that contain JavaScript or JSON](./mark-scripts-and-jsons/)
    * [Highlighting sessions that contain static resources (like images, text files, etc.,)](./mark-static-objects/)
