# Journey

Everything that took me way too long to figure out

## Send CSRF authenticity token with JavaScript fetch POST call

```javascript
fetch(url, {
      credentials: 'include',
      method: method,
      headers: {
        'X-CSRF-Token': csrfToken
      }
    })
```
