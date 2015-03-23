This is a template application for starting a Ruby on Rails project

Some items included:
- Bootstrap-sass
- A default pages controller with home action which is root
- Gem's grouped by dev and prod, ready for deploy to heroku
- Navigation, footer partials
- Messages partial to enable flash display
- Gitignore file updated to exclude cloud env specific files along with db files

To use:
- Clone the repo to your local dev env
- Set origin to your own repo
- Bundle update
- Bundle install --without production (to avoid installing prod gems locally)