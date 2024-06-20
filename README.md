# open-api-client-sdk-python

Python SDK 应用于 open-API-client-sdk-python. 提供获取用户名信息的 GET 和 POST 方法

## 安装

使用 pip 安装

```bash
pip install open_api_client_sdk
```

## **快速使用**

```python
from open_api_client_sdk import OpenClient

client = OpenClient('yourAppKey', 'yourAppSecret')

# Example of GET request
client.get_name_by_get('exampleName')

# Example of POST request
client.get_name_by_post('exampleName')
```

