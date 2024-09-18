---
title: Realtime
nav_order: 5
---

# Realtime

```javascript
// Import the Refirebase class
import { db } from '@/config/firebase';

// Get ALL data from the 'users' collection
const users = db.realtime.get("users");
```