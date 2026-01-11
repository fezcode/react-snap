# Customization

```diff
 "reactSnap": {
   "inlineCss": true,
+  "puppeteer": {
+    "timeout": 120000
+  }
 }
```

### puppeteer.timeout

Wait timeout for `page.goto` in milliseconds. Default: `120000`.