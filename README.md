# mtempmail
api for mtempmail.com temp email site
# Example
```nim
import asyncdispatch, mtempmail, json
waitFor init_cookie()
let data = waitFor get_messages()
echo data
let messages = waitFor get_messages()
echo messages
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
