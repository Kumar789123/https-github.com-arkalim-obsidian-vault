---
created: 2022-05-25T17:57:36+05:30
updated: 2022-05-25T18:03:06+05:30
---
[[100 Notes|Notes]]

---
# Portfolio
- Built using [[Hugo]]
- [Hugo PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)

## Setup
Create a new site
```
hugo new site portfolio -f yaml
```
```
cd portfolio
```
Initialize Git and install [Hugo PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)
```
git init
```
```
git submodule add https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --depth=1
```

## Updating Theme
```
git submodule update --remote --merge
```