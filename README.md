# space.forge

A mobile-first PWA for image upscaling and background removal, powered by the [image-upscaling.net](https://image-upscaling.net) API. Part of the space.cs studio ecosystem.

## Features

- Image Upscaling (1x, 2x, 4x) with General, Plus, and Diffuser models
- Background Removal with transparency preview
- Face Enhancement toggle for portrait upscaling
- Account dashboard showing balance and quota
- Installable PWA that works like a native app on your phone

## CORS Note

The image-upscaling.net API is designed for server-side use. If you encounter CORS errors, edit `index.html` and change:

```javascript
const API = 'https://image-upscaling.net';
```

to use a proxy like:

```javascript
const API = 'https://corsproxy.io/?https://image-upscaling.net';
```

## License

Personal-use tool wrapping a third-party API provided by image-upscaling.net.
