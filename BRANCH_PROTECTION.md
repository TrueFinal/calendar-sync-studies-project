# Branch Protection Rules (GitHub)

To configure branch protection for this repository:

---

## 🔐 Protecting the `main` Branch

1. Open **Settings** of the repository  
2. Go to **Branches**  
3. Click **Add Rule**  
4. Set the branch pattern to:  

main

---

## ✔️ Recommended Settings

### Enable:
- [x] Require pull request before merging  
- [x] Require at least 1 approving review  
- [x] Require status checks to pass  
- [x] Require linear history  
- [x] Do not allow direct pushes  
- [x] Block force pushes  
- [x] Block branch deletion  

### Optional:
- [ ] Require signed commits  
- [ ] Require deployments to succeed before merging  

---

## 🧪 Status Checks (optional)
When CI is configured, enable:

- `tests`
- `lint`
- `type-check`

---

## 🔧 Additional Recommendation
Create a `dev` branch:

git checkout -b dev
git push -u origin dev

And apply a lighter protection rule to it.