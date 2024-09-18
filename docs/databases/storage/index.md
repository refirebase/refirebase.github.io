---
title: Storage
parent: Databases
nav_order: 7
---

# Storage

```javascript
// Import the Refirebase class
import { db } from '@/config/firebase';

// Get a file from the storage
const file = db.storage.get("path/to/file");
```