# url-shortener
 Url Shortener with Flask & Heroku
 
 demo : https://baxsm-shortener.herokuapp.com/
 
 `.env` file consists of
 
```
DATABASE_URL=sqlite:///shorty.db
SECRET_KEY=mysecretkey
APP_SETTINGS=config.ProductionConfig
FLASK_APP=core
```

change `APP_SETTINGS` to `config.DevelopmentConfig` or `config.ProductionConfig` per need
