## Starting in Inspect Mode

inspect mode enabled with the --inspect flag
```
node --inspect app.js
```

but you can also start in inspect mode with the --inspect-brk flag

it is better to cause the process to start with an active breakpoint at the very beginning of the program using this flag

```javascript
node --inspect-brk app.js
```

remote debugging protocol uses WebSockets which is why a ws:// protocol address is printed

## Set a Chrome Browser Tab's Address Bar 

```
chrome://inspect
```
For more information on using Chrome Devtools, see Google Developer's Documentation. 

o learn more, read "Debugging Guide" by nodejs.org.

[Debugging Guide](https://nodejs.org/en/learn/getting-started/debugging)