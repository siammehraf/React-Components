# For Better Visibility

In App.js write below code :

```
<AnimatedCursor
        innerSize={15}
        outerSize={15}
        color="255, 0 ,0"
        outerAlpha={0.4}
        innerScale={0.7}
        outerScale={5}
/>
```

---

# If Mouse is Still Showing with Cursor, Then Override the CSS/Universal CSS File

```
body,
html,

- {
  cursor: none !important;
  }
```

---

# If Cursor Underlapping, Then Try Fixing Z-Index

```
  z-index: 1000;
```
