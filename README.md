# Code editor plugin for TinyMCE 5
Free analogue advcode plugin. Based on codemirror. Made specifically for work in chrome extension. Works fine as an external plugin.

## Install
1. Place the plugin files in the tinymce/plugins directory.
2. Activate plugin and set button to the toolbar:
```
plugins: ['code_edtitor']
toolbar: 'code_edtitor'
```

## Manifest correction for work in chrome extension
```
"content_security_policy": "script-src 'self' https://cdnjs.cloudflare.com; object-src 'self'"
```
