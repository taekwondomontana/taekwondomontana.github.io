# taekwondomontana.github.io
taekwondomontana website

docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" -it --env JEKYLL_ENV=production jekyll/jekyll:latest jekyll build
