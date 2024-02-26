# Cloudflare Gravatar Proxy for CHN users

> API: https://cloudflare-gravatar.eallion.workers.dev/avatar/

### Deploy

```bash
git clone https://github.com/eallion/cloudflare-gravatar.git

cd cloudflare-gravatar
npm install

### Login
# wrangle login

### Deploy
wrangle deploy

```

### Demo

- https://cravatar.eallion.com/avatar/171e4c30959e8c077a6c58b958624b31 # Custom Domain
- https://cloudflare-gravatar.eallion.workers.dev/avatar/171e4c30959e8c077a6c58b958624b31

### CORS Header

`src/index.js`

```js
    new_response_headers.set('access-control-allow-origin', '*');
```
