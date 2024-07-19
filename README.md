# NLW Expert (Python/Flask)

This application was developed during **[Rocketseat](https://www.rocketseat.com.br/)'s NLW Experts** course.


### How to run
1. Create a virtual environment and activate it:
    ```bash
    $ python -m venv venv

    $ cd venv/bin/activate
    ```

1. Install all the dependencies:
    ```bash
    $ pip install -r requirements.txt
    ```

1. Run the project:
    ```bash
    $ python run.py
    ``` 
---

### Endpoints:
```http
  POST /create_tag
```
|     Param   | Type       | Description                         |
| :---------- | :--------- | :---------------------------------- |
| `product_code` | `string` | **Required**. Barcode number       |

```curl
curl -X POST http://localhost:3000/create_tag \
-H "Content-Type: application/json" \
-d '{"product_code": "0123456789"}'
```
---

