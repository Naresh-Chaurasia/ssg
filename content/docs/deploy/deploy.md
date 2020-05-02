---
title: "Deploying the site"
weight: 10
description: ""
---
# Site deployment

## Building the site
#### Prerequisites
Check out the "master" branch.

#### Procedure
1. Open the Terminal by pressing **`CTRL` + `SHIFT` + `T`**.
2. Navigate to the root folder of the repository.
3. Enter `hugo`  
**Result:** The static site is built in the `docs` directory.
4. In the file explorer, open the `docs` directory.
5. Double click **index.html**.  
**Result:** The site opens in the browser.
6. Verify that the content was generated properly.
7. Commit the changes in the `docs` directory.
8. Push to the "origin/master" branch.
9. **First deployment only:** Enable GitHub Pages by performing the following actions:
   1. On GitHub, open the homepage of the repository.
   2. Select the **Settings** tab.
   3. On the **Settings** tab, scroll down to the **GitHub Pages0** section.
   4. In the **Source** drop-down list, select the **master branch /docs folder** option.