# CDN
Use jsDelivr to speed up front-end static resource access and save netflow.

# How to Use

```
https://cdn.jsdelivr.net/gh/{user-name}/{repository-name}@{version}/{file-path}
```

`{version}` can be `v1.0.0`, `1.0.0`, `main`, or nothing (to get the latest version).

Such as:
```
https://cdn.jsdelivr.net/gh/TerryYoung518/cdn@1.0.0/fonts/HarmonyOSHans-Light.woff2
https://cdn.jsdelivr.net/gh/TerryYoung518/cdn@main/fonts/HarmonyOSHans-Regular.woff2
https://cdn.jsdelivr.net/gh/TerryYoung518/cdn/fonts/HarmonyOSHans-Regular.woff2
```

# What's More

Add `.min` to js/css file name to get min version, which will be generated automatically if it does not exist.
