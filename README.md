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
### Running tests
1. In order to run all available tests, just run:    
    ```bash
    $ pytest src
    ```
[Supplementary material used at the NLW 14 event for Python technology.](https://efficient-sloth-d85.notion.site/Python-56021db9158c4c969720648c612c8204#c644efdd2fc7496ab80c0825dd7853b7)
