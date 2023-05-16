# FNF build
[source](https://github.com/tpguy825/FNF-webbuild)

## Note
When you go onto it, it will show the HaxeFlixel logo with a loading bar. After a few seconds, the screen goes black - don't worry, it's supposed to do that (it's still loading)

## Errors

### haxe.ValueException
This means that it's being stupid. Try replacing the `/index.html` in the URL to `/`
If that doesn't work, then idk (help)

### Aw, snap!
Your browser has run out of memory. Don't worry, it loads a lot of stuff.
Solution (windows):
1. Press the windows key
2. Paste in this command:
```cmd
cmd /c "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" http://tpguy825.github.io/website/fnf/ --max-old-space-size=8192
```
3. Chrome should open to the webpage and it should (fingers crossed) work alright

seriously this is really annoying the website is only 330MB but it still runs out of memory 
