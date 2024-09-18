---
title: Installation
nav_order: 3
---

# Installation

You can install the package via your favorite package manager:

```bash
npm install refirebase
```

or

```bash
yarn i refirebase
```

or

```bash
pnpm i refirebase
```

or

```bash
bun i refirebase
```

And that's it! You're ready to start using Refirebase. 🎉

# Next Steps

## Usage

Import the `Refirebase` class:

```javascript
import { Refirebase } from 'refirebase';
```

You can use the `Refirebase` class to get the Firebase objects:

```javascript
const refirebase = new Refirebase({
  apiKey: 'YOUR_API_KEY',
  authDomain: 'YOUR_AUTH_DOMAIN',
  databaseURL: 'YOUR_DATABASE_URL',
  projectId: 'YOUR_PROJECT_ID',
  storageBucket: 'YOUR_STORAGE_BUCKET',
  messagingSenderId: 'YOUR_MESSAGING_SENDER_ID',
  appId: 'YOUR_APP_ID',
  measurementId: 'YOUR_MEASUREMENT_ID',
});
```

Or you can use destructuring to get other objects:

```javascript
const { db, auth } = new Refirebase({
  apiKey: 'YOUR_API_KEY',
  authDomain: 'YOUR_AUTH_DOMAIN',
  databaseURL: 'YOUR_DATABASE_URL',
  projectId: 'YOUR_PROJECT_ID',
  storageBucket: 'YOUR_STORAGE_BUCKET',
  messagingSenderId: 'YOUR_MESSAGING_SENDER_ID',
  appId: 'YOUR_APP_ID',
  measurementId: 'YOUR_MEASUREMENT_ID',
});
```

> If you prefer to copy empty strings to the `Refirebase` class:

```javascript
const refirebase = new Refirebase({
  apiKey: '',
  authDomain: '',
  databaseURL: '',
  projectId: '',
  storageBucket: '',
  messagingSenderId: '',
  appId: '',
  measurementId: '',
});
```