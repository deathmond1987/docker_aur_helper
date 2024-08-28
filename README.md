simple aur client in container.
   Usage:
   ```
   docker run -v ./out:/out deathmond1987/aur_helper conky
   docker run -v ./out:/out deathmond1987/aur_helper zsh conky -d -s
   ```
   Options:
   ```
       -d - download all package deps to /out dir
       -s - disable package signature check
   ```
   package will store in "/out" dir
