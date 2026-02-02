# yode

deploy to render:

1. push this folder to github (create a new repo, then `git init`, `git add .`, `git commit -m "init"`, `git remote add origin <url>`, `git push -u origin main`)

2. go to [render.com](https://render.com) and sign in

3. click **new** → **static site**

4. connect your github repo (yode)

5. render will detect the `render.yaml` - or set:
   - **build command:** `echo "No build needed"`
   - **publish directory:** `.`

6. click **create static site**

7. wait for deploy - your site will be at `https://yode.onrender.com` (or whatever name you chose)
