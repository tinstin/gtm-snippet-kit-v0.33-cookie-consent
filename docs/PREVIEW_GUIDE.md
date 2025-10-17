# Preview & Testing Guide
1. Enter GTM Preview mode.
2. Open your site in Incognito window.
3. Banner appears automatically.
4. Click Yes → GA4 Config fires instantly.
5. Click No → no analytics fire.
6. Reset consent for testing:
```js
document.cookie='analytics_consent=; Max-Age=0; path=/';
localStorage.removeItem('analytics_consent');
location.reload();
```
