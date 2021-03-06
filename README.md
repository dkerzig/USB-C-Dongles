# USB-C-Dongles

A gathered list of buyable USB-C Dongles (esp. for the MacBook)

Chat with me on Twitter: [@wottpal](https://twitter.com/wottpal)

## Format
`dongles.json` contains an array of `dongles` where an item is specified by the following properties:

| Property | Data-Type | Required | Description |
|:--|:--|:--|:--|
| `name` | String | ✅ | The official product name (prefer short names). |
| `company` | String | ✅ | The name of the manufacturer. |
| `url` | String (URL) | ✅ | Links to the product-page of the manufacturer or directly to shopping-page (always prefer the first). |
| `image` | String (Filename) | ✅ | Is the name of the product-image stored under `images/` (see section *Images*). |
| `image_credit` | String | ✅ | Where the image-credit belongs to. (see section *Images*). |
| `properties` | Object | ✅ | A set of key-value pairs describing the capabilities of the dongle (i.e. availability of ports) |
| `properties.usb_c` | Int |  | ∑ ports |
| `properties.usb3` | Int |  | ∑ ports |
| `properties.micro_usb` | Int |  | ∑ ports |
| `properties.ethernet` | Int |  | ∑ ports |
| `properties.hdmi` | Int |  | ∑ ports |
| `properties.vga` | Int |  | ∑ ports |
| `properties.sd_card` | Int |  | ∑ ports |
| `properties.micro_sd_card` | Int |  | ∑ ports |
| `properties.audio_jack` | Int |  | ∑ ports |
| `properties.externalPowerNeeded` | Int |  | ∑ ports |
| `properties.shipsNow` | Int |  | ∑ ports |
| `properties.canLoad` | Int |  | ∑ ports |



## Images
For bad-link- and performance-reasons (some sites are only having ridiculously large images) a copy of the image should be made, resized (max leading dimension 1000px), optimized and stored under `images/`.

The file-name (with extension) which is stored in the `image`-property should be pointing to that file.

## To-Do

- [ ]  Find more dongles
- [ ]  Add internationalized shopping-links & availability reports
