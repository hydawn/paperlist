# paperlist

manage papers

# run

```
git clone --recurse-submodules https://github.com/hydawn/paperlist.git
cd paperlist
docker compose up
```

now the website is at `localhost:8040`

create an empty sqlite3 database using `sqlite3 db.sqlite3 '.databases'`

migrate tables using `docker exec -it paperlist-backend-1 python manage.py migrate`
