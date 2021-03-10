<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/app](./app.md) &gt; [FirebaseApp](./app.firebaseapp.md) &gt; [name](./app.firebaseapp.name.md)

## FirebaseApp.name property

The (read-only) name for this app.

The default app's name is `"[DEFAULT]"`<!-- -->.

<b>Signature:</b>

```typescript
readonly name: string;
```

## Example 1


```javascript
// The default app's name is "[DEFAULT]"
const app = initializeApp(defaultAppConfig);
console.log(app.name);  // "[DEFAULT]"

```

## Example 2


```javascript
// A named app's name is what you provide to initializeApp()
const otherApp = initializeApp(otherAppConfig, "other");
console.log(otherApp.name);  // "other"

```
