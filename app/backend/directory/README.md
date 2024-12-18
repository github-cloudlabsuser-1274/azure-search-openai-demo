# Backend Application

## Overview
This backend application is part of the larger project and is responsible for handling the server-side logic, database interactions, and API endpoints.

## Requirements
The backend application has the following dependencies listed in the `requirements.txt` file:

\```plaintext
aiofiles==23.2.1
aiohttp==3.9.3
aiosignal==1.3.1
annotated-types==0.6.0
anyio==4.2.0
asgiref==3.7.2
attrs==23.2.0
azure-common==1.1.28
azure-core==1.29.7
azure-core-tracing-opentelemetry==1.0.0b11
azure-identity==1.15.0
azure-keyvault-secrets==4.7.0
azure-monitor-opentelemetry==1.2.0
azure-monitor-opentelemetry-exporter==1.0.0b21
azure-search-documents==11.6.0b1
azure-storage-blob==12.19.0
blinker==1.7.0
certifi==2023.11.17
cffi==1.16.0
charset-normalizer==3.3.2
click==8.1.7
cryptography==42.0.1
deprecated==1.2.14
distro==1.9.0
ecdsa==0.18.0
fixedint==0.1.6
flask==3.0.1
frozenlist==1.4.1
h11==0.14.0
h2==4.1.0
hpack==4.0.0
httpcore==1.0.2
httpx==0.26.0
hypercorn==0.16.0
hyperframe==6.0.1
idna==3.6
importlib-metadata==6.11.0
isodate==0.6.1
itsdangerous==2.1.2
jinja2==3.1.3
markupsafe==2.1.4
msal==1.26.0
msal-extensions==1.1.0
msrest==0.7.1
multidict==6.0.4
numpy==1.26.3
oauthlib==3.2.2
openai[datalib]==1.10.0
opentelemetry-api==1.22.0
opentelemetry-instrumentation==0.43b0
opentelemetry-instrumentation-aiohttp-client==0.43b0
opentelemetry-instrumentation-asgi==0.43b0
opentelemetry-instrumentation-dbapi==0.43b0
opentelemetry-instrumentation-django==0.43b0
opentelemetry-instrumentation-fastapi==0.43b0
opentelemetry-instrumentation-flask==0.43b0
opentelemetry-instrumentation-httpx==0.43b0
opentelemetry-instrumentation-psycopg2==0.43b0
opentelemetry-instrumentation-requests==0.43b0
opentelemetry-instrumentation-urllib==0.43b0
opentelemetry-instrumentation-urllib3==0.43b0
opentelemetry-instrumentation-wsgi==0.43b0
opentelemetry-resource-detector-azure==0.1.3
opentelemetry-sdk==1.22.0
opentelemetry-semantic-conventions==0.43b0
opentelemetry-util-http==0.43b0
packaging==23.2
pandas==2.2.0
pandas-stubs==2.1.4.231227
pillow==10.2.0
portalocker==2.8.2
priority==2.0.0
pyasn1==0.5.1
pycparser==2.21
pydantic==2.6.0
pydantic-core==2.16.1
pyjwt[crypto]==2.8.0
python-dateutil==2.8.2
python-jose[cryptography]==3.3.0
pytz==2023.4
quart==0.19.4
quart-cors==0.7.0
regex==2023.12.25
requests==2.31.0
requests-oauthlib==1.3.1
rsa==4.9
six==1.16.0
sniffio==1.3.0
tenacity==8.2.3
tiktoken==0.5.2
tqdm==4.66.1
types-pillow==10.2.0.20240206
types-pytz==2023.4.0.20240130
typing-extensions==4.9.0
tzdata==2023.4
urllib3==2.1.0
uvicorn==0.27.0.post1
werkzeug==3.0.1
wrapt==1.16.0
wsproto==1.2.0
yarl==1.9.4
zipp==3.17.0
\```

## Setup
To set up the backend application, follow these steps:

1. Clone the repository.
2. Navigate to the `app/backend` directory.
3. Install the dependencies using `pip`:
   ```sh
   pip install -r requirements.txt