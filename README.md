# Portainer templates repository

Contains the various stuff to be used by the Portainer while building the application or displaying the application on the Portainer Templates page.

Includes:

-- templates.json - the file with application description in Portainer's format
-- logo file      - PortaOne logo
-- app dir        - contains the application stack files and app logo for templates.json

The structure example:

```
portainer/
├── apps
│   ├── PortaBI
│   │   ├── docker-stack.yml
│   │   └── porta_bi_logo.png
│   └── PortaSomeApp
│       ├── docker-stack.yml
│       └── some_app_logo.png
├── portaone_logo.png
└── templates.json
```