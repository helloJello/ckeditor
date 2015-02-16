# Ckeditor

This is a forked version of the original CKEditor Gem but only contains, English, French and Spanish language support.  I was having terribly long asset compilation times on Heroku do to the fact that (in my case) unnecessary language pack files were included.  I choose not to go down the route of pre-compiling my assets locally so I've fork this project and have slimmed down this project to include only the languages that I need.

Detailed installation instructions of this gem can be found here. [ckeditor.com](https://github.com/galetahub/ckeditor) 

```
gem 'ckeditor', github: 'galetahub/ckeditor'
```

Mad Props to the original creator of this gem.

This project rocks and uses the MIT-LICENSE.
