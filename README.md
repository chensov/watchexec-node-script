# watchexec-node-script
A simple tool for automating the execution of Node.js scripts upon file changes, providing a better alternative to console.log.


## Update run_on_save.sh to match your js file.


```
watchexec --no-meta --exts js "clear; node script.js"
```

## Run the script.

```
./run_on_save.sh
```
