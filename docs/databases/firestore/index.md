---
title: Firestore
nav_order: 4
---

# Firestore

```javascript
// Import the Refirebase class
import { db } from '@/config/firebase';

// Get ALL data from the 'users' collection
const users = db.firestore.get("users");
```