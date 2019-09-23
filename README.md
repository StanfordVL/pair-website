# Stanford People, AI & Robots Website

This repo contains the Jekyll files for the [Stanford People, AI & Robots (PAIR) Group website](https://pair.stanford.edu). Please submit pull requests when updating the website.

To locally build and browse, just [install Jekyll](https://jekyllrb.com/docs/installation/) and run ./serve_jekyll in terminal, then go to appropriate url in browser based on what you see in terminal.

To compile site for release, exec following in  terminal:
1. `export JEKYLL_ENV=production`
2. `bundle exec jekyll clean`
3. `bundle exec jekyll build --future`

To update site, run above commands, then 'octopress deploy' (or checkout static, copy contents of _site into root of repo, and commit everything), and then cd to dir where site is hosted (/afs/.cs/group/pair/www)  (you can ssh throught capri13) and just run 'git pull' (this is just the steps getting compiled html, syncing it to master branch, and then pulling master branch at the appropriate location).

To add new publications, follow examples in publications directory. To update people or robot list, update appropriate file in \_data. To update look or layout, edit the appropriate md files in \_includes, or \_pages. To update news or publications on home page, edit the index.md in root folder directly.

Maintainers: [Yuke Zhu](https://web.stanford.edu/~yukez/), [Ajay Mandlekar](http://web.stanford.edu/~amandlek/), [Andrey Kurenkov](http://www.andreykurenkov.com/)
