# TIKTOK X-Bogus API

## How To Use

### API Request

```py
import requests

url = 'https://bogus-ca85243f8e84.herokuapp.com/signer' # API url

data = {
    'param': '', # url param
    'userAgent': '', # browser userAgent
    'data': '', # request data
    'token': 'a7c9b-c8o3f-xxxxx', # API Token
}

response = requests.post(url=url,data=data).json()

print(response)
```

### Response

```json
{
    "X-Bogus": "DFSzswVL0IJANHuxtBTAgxJ92UI0"
}
```

## Token

content for Token: https://t.me/CPO_DEV
