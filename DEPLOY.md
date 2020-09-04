rm -rf ./docs && jekyll b && mkdir ./docs && cp -R ./_site/ ./docs && touch ./docs/.nojekyll

jekyll b -d ./docs
