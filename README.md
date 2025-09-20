# yoga

## firebase

- Project ID: dlintwyoga
- Project Name: dlintwyoga
- [Firebase console](https://console.firebase.google.com/project/dlintwyoga/overview)
- [public web](https://dlintwyoga.web.app)

related commands:

```bash
firebase login
firebase use dlintwyoga
firebase deploy --only hosting
```

my steps:

- login firebase console
  - 建構/Authentication/開始使用
  - Sign-in-method
    - Google: dlintwyoga-482269555355

      ```txt
      apiKey: "AIzaSyAA49bwKhqAEWPAEAJia3uE8hgp1S2CEtY",  // You'll need to replace this
      authDomain: "dlintwyoga.firebaseapp.com",
      projectId: "dlintwyoga",
      storageBucket: "dlintwyoga.appspot.com",
      messagingSenderId: "123456789",  // You'll need to replace this
      appId: "1:123456789:web:your-app-id"  // You'll need to replace this
      ```

<https://developers.google.com/identity/protocols/oauth2/javascript-implicit-flow?hl=en>

## Q & A

### how to check log

In google cloud console, search 'log explorer' in the 'dlintwyoga' page.

### useragent_disallow

- through 'Line' app, it is not use the Google proved browser to open oauth
  page. So, require click the '...' button to open 'default browser' to open.
