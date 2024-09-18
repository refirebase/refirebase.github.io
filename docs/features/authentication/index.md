---
title: Authentication
nav_order: 7
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