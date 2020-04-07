# Simple Social
Available online at: http://galin23.pythonanywhere.com/

This project is powered by Docker. To run it follow the instructions bellow:

```
## Run the containers
docker-compose up -d

## Execute migrations
docker-compose exec web python manage.py migrate
```

Web site should be accessible at: http://localhost:8000/
