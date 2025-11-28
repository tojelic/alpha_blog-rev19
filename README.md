# 1. Napravi Rails app (ovo kreira folder alpha_blog)
rails new alpha_blog

# 2. Uđi u projekt
cd alpha_blog

# 3. Pokreni server (opcionalno, samo da vidiš da radi)
rails server

# 4. Git inicijalizacija
git init
git add .
git commit -m "Initial commit"

# 5. Postavi GitHub remote (ispravljen typo: remote)
git remote add origin https://github.com/tojelic/alpha_blog-rev19.git

# 6. Prebaci se na main (ako nije već)
git branch -M main

# 7. Pushaj na GitHub
git push -u origin main
