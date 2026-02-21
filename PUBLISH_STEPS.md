# Publish Steps (Do This In Order)

## 1) Make production repo private
1. Open: https://github.com/HadToBeThere/app_code/settings
2. Scroll to **Danger Zone**
3. Click **Change repository visibility**
4. Select **Make private** and confirm repo name

## 2) Create public portfolio repo
1. In GitHub, create new repo: `htbt-portfolio-public`
2. Set visibility: **Public**
3. Do NOT initialize with README (already local)

## 3) Push this local portfolio folder
From terminal:
```bash
cd /Users/tobiasdicker/htbt-portfolio-public
git add .
git commit -m "Public portfolio: architecture, impact, and code samples"
git branch -M main
git remote add origin https://github.com/HadToBeThere/htbt-portfolio-public.git
git push -u origin main
```

## 4) Add proof assets
- Add screenshots to `assets/screenshots/`
- Update `README.md` with:
  - short demo gif
  - key metrics once available
  - TestFlight/App Store link later

## 5) Internship usage
Use this public repo on resume/LinkedIn. Keep private repo for production velocity.
