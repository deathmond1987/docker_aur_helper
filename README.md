simple aur client in container.
   Usage:
   ```
   docker run -v ./out:"/out" container_name conky
   docker run -v ./out:"/out" container_name zsh conky -d -s
   ```
   Options:
   ```
       -d - download all package deps to /out dir
       -s - disable package signature check
   ```
   package will store in "/out" dir
