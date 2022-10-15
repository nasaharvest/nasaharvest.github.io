---
name: Add profile picture to website
about: Instructions for adding profile picture to website.
title: Add profile picture to website
labels: ''
assignees: ''

---

**Context**: We are beginning to use our github.io website more actively: https://nasaharvest.github.io/
**Issue**: There's no profile picture for you
**To do**:
1. Clone repository locally
2. Create a new branch by running `git checkout -b <your-name>-profile`
3. Add a square image (under 200 KB) of yourself into `profiles/` the (image name should be your last name)
4. Update the code associated with your name in index.html from
```html
<img src="assets/logo.png" class="emptyprofile"/>
```
to
```html
<img src="profiles/<your-last-name>.jpg" class="profile">
```
5. Check that it worked by opening index.html in a web browser
6. Push the code to your branch
```bash
git add . 
git commit -m'Added profile picture for <your name>'
git push
```

7. Create a new Pull request and add me as a reviewer
