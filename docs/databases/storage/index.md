---
title: Storage
nav_order: 6
---

# Storage

```javascript
// Import the Refirebase class
import { db } from '@/config/firebase';

// Get a file from the storage
const file = db.storage.get("path/to/file");
```