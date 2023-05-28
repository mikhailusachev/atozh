# electric-xtdb-starter

* Adapted from [xtdb-in-a-box](https://github.com/xtdb/xtdb-in-a-box)
* Requires env var `XTDB_ENABLE_BYTEUTILS_SHA1=true`

```
$ XTDB_ENABLE_BYTEUTILS_SHA1=true clj -A:dev -X user/main

Starting Electric compiler and server...
shadow-cljs - server version: 2.20.1 running at http://localhost:9630
shadow-cljs - nREPL server started on port 9001
[:app] Configuring build.
[:app] Compiling ...
[:app] Build completed. (224 files, 0 compiled, 0 warnings, 1.93s)

docker run --rm -p 7070:8080 -e XTDB_ENABLE_BYTEUTILS_SHA1=true mikhailusachev/atozh .

👉 App server available at http://0.0.0.0:8080
```
