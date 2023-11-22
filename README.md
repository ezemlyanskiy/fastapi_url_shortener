# URL Shortener with Python and FastAPI

It's a fully functional API-driven web app that creates shortened URLs that forward to target URLs.  
When you post a target URL to the URL shortener app, you get a shortened URL and a secret key back.  
The shortened URL contains a random key that forwards to the target URL. You can use the secret key  
to see the shortened URL’s statistics or delete the forwarding.

## Quick start

```
git clone git@github.com:sava9ecode/fastapi_url_shortener.git
cat .env_sample > .env (and fill it out)
uvicorn shortener_app.main:app
```

Next, go to 127.0.0.1:8000/docs and try it out.
