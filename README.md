# vk-ad-prune
These are the filters for AdBlock Chrome extension (https://getadblock.com/).

![vk-pruner](https://drive.google.com/uc?export=view&id=1AA3rtoMfN87DnSK_rc7XA3-_jmnImzmu)

Go to `Customize` => `Manually edit your filters` and copy-paste filters for your needs.

Left panel ads:
```
vk.com##div[id="ads_left"]
```
Targeted ads in groups / news feed:
```
vk.com##div[class*="ads_promoted_post"]
```
Group posts tagged by group admins as `Advertisement`:
```
vk.com#?#div[class^="_post"]:-abp-has(> div > div > div > div > div.wall_marked_as_ads)
```