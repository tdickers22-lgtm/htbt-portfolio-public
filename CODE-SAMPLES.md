# Code Samples (Sanitized)

These are representative snippets showing style and structure, not full production code.

## 1) Auth-state UI mode switching
```js
function applyAuthMode(user) {
  const signedIn = !!(user && !user.isAnonymous);
  document.body.classList.toggle('auth-signed-in', signedIn);
  document.body.classList.toggle('auth-signed-out', !signedIn);
}
```

## 2) Share link payload construction
```js
function buildShareLink(baseUrl, pingId) {
  const base = String(baseUrl || '').replace(/\/+$/, '');
  return `${base}/share/p/${encodeURIComponent(pingId)}?v=${Date.now().toString(36)}`;
}
```

## 3) Quota label formatting
```js
function quotaLabel(used, max) {
  const left = Math.max(0, max - used);
  return `${left}/${max} left today`;
}
```

## 4) Server-side redirect behavior for shared links
```js
if (canShow && !isPreviewBot) {
  res.set('Cache-Control', 'no-store');
  return res.redirect(302, appOpenUrl);
}
```
