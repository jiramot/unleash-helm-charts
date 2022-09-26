# unleash-proxy

## Install
```
helm install unleash-proxy \
    --set unleashProxy.clientKey=some-secret \
    --set unleashProxy.url=https://app.unleash-hosted.com/demo/api/ \
    --set unleashProxy.apiToken="56907a2fa53c1d16101d509a10b78e36190b0f918d9f122d" \
    .
```

## Uninstall
```
helm uninstall unleash-proxy
```