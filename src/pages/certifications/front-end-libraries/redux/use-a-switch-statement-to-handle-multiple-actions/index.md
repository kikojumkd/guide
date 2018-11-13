---
title: Use a Switch Statement to Handle Multiple Actions
---
## Use a Switch Statement to Handle Multiple Actions

Tip: Make sure you don't use "break" commands after return statements within the switch cases.

```react.js
switch(action.type) {
    case 'LOGIN': 
      return {authenticated: true};
    case 'LOGOUT': 
      return {authenticated: false};
    default: 
      return state;
    }
```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
