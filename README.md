# Docker Stack Develop

The following repository is to be used in a development environment for frontend / backend environments and exclusively for AyPhu.

## Software

| # | Name | Version | Description |
|:--------------|:-------------:|--------------:|--------------:|
| 1 | node | 18-buster-slim | Javascript Frontend |
| 2 | python | 3.9.16-alpine3.18 | Python Backend |
| 3 | postgresql | 13.11 | BD SQL |

## Clone Project front and Backend

### Frontend

```
git clone git@github.com:anarkopin/ayphu_rrhh_front.git app/next && cd app/next && npm install && cd ../../
```

> If you have problems installing the packages, keep in mind

> npm set audit false

### Backend

```
git clone git@github.com:anarkopin/ayphu_rrhh_back.git api/django && cd api/django && cd ../../
```

```
python -m venv env 
```

```
.\env\Scripts\activate or source env/bin/activate
```

```
pip install -r requirements.txt
```

> note: Review the README.md files for each repository so you can have separate instructions.
## Run


> Download images

```
docker-compose up --build
```


## Project structure

<pre class="language-shell">
  <code class=" language-shell">
  ├── docker-compose.yml
  ├── api
  │   ├── postgres
  │   └── django
  ├── app
  │   └── next
  └── .env
  
  </code>
</pre>

```bash
api/strapi # backend / api
```

```bash
app/next # frontend / client
```

## Repositories

| # | Repo | Description |
|:--------------|:-------------:|--------------:|
| 1 | https://github.com/anarkopin/ayphu_rrhh_front | Repo for Frontend App |
| 2 | https://github.com/anarkopin/ayphu_rrhh_back | Repo for Backend Api |

