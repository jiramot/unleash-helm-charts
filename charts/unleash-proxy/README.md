# unleash-proxy

## Install
```
helm install unleash-proxy \
    --set environments.UNLEASH_PROXY_CLIENT_KEYS=some-secret \
    --set environments.UNLEASH_URL=https://app.unleash-hosted.com/demo/api/ \
    --set environments.UNLEASH_API_TOKEN="56907a2fa53c1d16101d509a10b78e36190b0f918d9f122d" \
    .
```

## Test
```
curl http://localhost:3000/proxy -H "Authorization: some-secret"
```

## Uninstall
```
helm uninstall unleash-proxy
```