# Portfolio

This is a portfolio of me and my work. Hopefully it will get me jobs.

# Deploy

This is hosted by github pages, and changes to the master branch will automatically update the site. Changes should be live within 5 minutes (I believe).

# Build

This site is built in vanilla HTML, so there really isn't anything to build. You'll need to process the CSS if you make any changes to it, though:

1. Make and save your edits in `css/styles.css`
1. Copy the whole file and paste the contents at [this post processor](https://madlittlemods.github.io/postcss-css-variables/playground/)
1. Copy the post processing result, and paste that into this [auto prefixer](http://autoprefixer.github.io/)
1. This result is then pasted into `css/styles.production.css`
1. Add this to the top of the production css: `/* stylelint-disable */`
1. Commit both files changes
