# Hegweard-Tsulalgis-Blog

A personal blog made for fun and for the love of blogging 

# Testing

The site can be built and deployed locally by running the following command and accessing the site at `http://127.0.0.1:4000/` or `http://localhost:4000/`:

```
bundle exec jekyll serve --baseurl "" --livereload
```

If you need to test the site on another device, such as a phone or tablet, use this command instead, which will allow you to access it from `http://<your-local-ip>:4000`:

```
bundle exec jekyll serve --host 0.0.0.0 --baseurl "" --livereload
```

Note: You may have to refresh on other devices even if you pass in `--livereload`.