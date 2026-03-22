mkdir C:\dream-merge-policy
Copy-Item "C:\Users\yusuf\OneDrive\Masaüstü\eşleştirme oyunu\deram merge\privacy.html" "C:\dream-merge-policy\index.html"
Copy-Item "C:\Users\yusuf\OneDrive\Masaüstü\eşleştirme oyunu\deram merge\PRIVACY_REPO_README.md" "C:\dream-merge-policy\README.md"
cd C:\dream-merge-policy
git init
git add .
git commit -m "Add privacy policy site"
git branch -M main
git remote add origin https://github.com/Ragnarok55/dream-merge-policy.git
git push -u origin main
