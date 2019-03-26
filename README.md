# hexo-asset-image


Give asset image in hexo a absolutely path automatically

# Usege

```shell
npm install hexo-asset-image --save
```

# Example

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](logo.jpg)` to insert `logo.jpg`.

# config with lazyload
```
asset_image:
  lazyload : true
  loading_img : /images/loading2.svg
  lazy_attr: data-original
```