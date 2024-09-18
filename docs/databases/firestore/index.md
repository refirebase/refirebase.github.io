---
title: Firestore
parent: Databases
nav_order: 5
---

# Firestore

```javascript
// Import the Refirebase class
import { db } from '@/config/firebase';

// Get ALL data from the 'users' collection
const users = db.firestore.get("users");
```