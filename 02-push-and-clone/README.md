# 2. Pushing and Cloning a Repository

## Push (local -> GitHub)
1. GitHub par naya empty repository banayein.
2. Terminal me:
```bash
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```
Baad me sirf `git push` kaafi hai.

## Clone (GitHub -> local)
```bash
git clone https://github.com/<username>/<repo>.git
cd <repo>
```

## Roz ka flow
```bash
git pull                 # latest changes lao
# ... code likho ...
git add .
git commit -m "Describe change"
git push
```
