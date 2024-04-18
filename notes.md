### Docs on the API server
https://cal.com/docs/introduction/quick-start/self-hosting/installation/platform/api-submodule#running-api-server

The docs say to do this, but they miss the /v1 /v2 folders

```cp apps/api/.env.example apps/api/.env```
```cp .env.example .env```

So the correct command is

```cp apps/api/v1/.env.example apps/api/v1/.env```
or 
```cp apps/api/v2/.env.example apps/api/v2/.env```
then
```cp .env.example .env```


