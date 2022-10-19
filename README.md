# micro-auth
Small API server with Azure AD authentication in FastAPI framework

## Requirements
- Python>=3.8.x
- poetry>=1.1.7
- docker>=20.10.16
- docker-compose>=1.29.2

## Azure AD setup
To check how authentication flow is implemented refer to [fastapi-azure-auth docs](https://intility.github.io/fastapi-azure-auth/)

## Development setup
1. Prepopulate your own `.env.dev` file in repo's root with variables required by Azure AD system (see previous paragraph)
2. Run `docker-compose -f ./docker/docker-compose.dev.yml up`
