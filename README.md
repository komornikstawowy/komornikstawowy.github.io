Site hosted on github pages and under custom domain komornik-stawowy.pl
Created with hugo
Menu configured in config.toml and menu entry in content/[entry].md
After making changes just create a commit and push to github this will trigger github actions which will copy process content to gh-pages branch
AFTER MAKING CHANGE THE SITE WILL NOT BE AVAILABLE UNDER CUSTOM DOMAIN (komornik-stawowy.pl) because github action removes CNAME file. SO AFTER EACH DEPLOYMENT ADD CNAME FILE to gh-pages branch similar to: https://github.com/komornikstawowy/komornikstawowy.github.io/commit/0b5aa8c059b3fb240a4d334d8fa883a222eddcce
