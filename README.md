# socktest
test prog for elm-sockets communicating with a rust server.  

You'll need to git clone 'elm-sockets' into the same parent directory into which you clone this socktest project.  If you put it somewhere else, be sure to update the elm-package.json with the location.  

```
for the rust server:
compile with "cargo build"
run with "./target/debug/socktest"
```
```
for elm:
run "elm-reactor" in the ./elm dir.  
Then connect to localhost:8000 using a browser (chromium).  
```

Keystrokes are broken for firefox right now, with ff you'll get \0 for all keys except return and tab. 
