# Audio-Noise-reduction
Bandpass + Spectral Gating based Audio Noise Reduction in Python
# 1️⃣ Go to your project folder
cd /path/to/your/project

# 2️⃣ Initialize Git
git init

# 3️⃣ Add all files and commit
git add .
git commit -m "Initial commit"

# 4️⃣ Add GitHub remote (replace username and repo name)
git remote add origin https://github.com/vaishnaviuh/Audio-Noise-Reduction.git

# 5️⃣ Rename branch to main
git branch -M main

# 6️⃣ Pull remote in case it has a README or existing files
git pull origin main --allow-unrelated-histories

# 7️⃣ Push your local repo to GitHub (will ask for username + PAT)
git push -u origin main

# Optional: cache credentials so you don’t enter PAT every time
git config --global credential.helper store
