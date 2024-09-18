---
title: Authentication
parent: Features
nav_order: 9
---

# Authentication

```javascript
// Import the Refirebase class
import { auth } from '@/config/firebase';

// Sign in with Google
const result = await auth.handleProviderSignIn("google");

if (!result) {
  // Handle error
}

const user = result.user;
```