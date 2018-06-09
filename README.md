# vk-ad-prune
These are the filters for AdBlock Chrome extension (https://getadblock.com/).

![vk-pruner](https://drive.google.com/uc?export=view&id=1AA3rtoMfN87DnSK_rc7XA3-_jmnImzmu)

Go to `Customize` => `Manually edit your filters` and copy-paste filters for your needs:

Left panel ads:
```
vk.com##DIV[class="ads_ads_box ver repeat_ver size_site"]
vk.com##DIV[class="trg-b-list trg-b-list_vk-left"]
vk.com##DIV[class="trg-b-banner-block"]
vk.com##.ads_ad_text_box
```
Targeted ads in groups / news feed:
```
vk.com##._ads_promoted_post_data_w
vk.com##._ads_promoted_post
vk.com##.own_ads_promoted_post
```
Group posts tagged by group admins as `Advert`:
```
vk.com#?#div[class^="_post"]:-abp-has(> div > div > div > div > div.wall_marked_as_ads)
```