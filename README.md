# basic firebase for nextjs
Just add these two files and fill in your details into the .env file.
Example:

```typescript
import auth from "./firebase"

...

const submit = ()=>{
  auth.signInWithEmailAndPassword(email, password);
}

...

```

I also included firestore, but one can remove it.
