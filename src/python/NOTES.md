To use GPU, fix .devcontainer/devcontainer.json as follows:


```diff
...
    "dockerComposeFile": [
        "docker-compose.yml",
-        // "docker-compose.gpu.yml" // Comment out
+        "docker-compose.gpu.yml"
    ],
    "service": "app", 
...
```
