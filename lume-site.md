1. install Deno `curl -fsSL https://deno.land/x/install/install.sh | sh` (Mac or Linux), `iwr https://deno.land/x/install/install.ps1 -useb | iex` (Windows
2. Follow the output instructions
  ```Manually add the directory to your $HOME/.bash_profile (or similar)
  export DENO_INSTALL="/root/.deno"  
  export PATH="$DENO_INSTALL/bin:$PATH"
  ```
3. install lume `deno run -A https://deno.land/x/lume/install.ts`


ALso share Fresh 

Ideally, I need: 
build-time rendering of html 
no client-side imports (css, js)

assets and application logic served from client runtime 
on GET, user receives app, limited need for further requests 
