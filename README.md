# yamdb_final
yamdb_final
![example event parameter](https://github.com/github/docs/actions/workflows/main.yml/badge.svg?event=push)

### Description
The YaMDb project collects user feedback on works

### Used technologies
Django 2.2.16
djangorestframework 3.12.4
Simplejwt 5.2.1
gunicorn==20.0.4

### Installation
1. Create a project folder. Go to this folder.
2. Clone the project to this folder:
```bash
git clone git@github.com:afoninsb/api_yamdb.git
```
3. Create a virtual environment and activate it:
```bash
python3 -m venv venv
source venv/bin/activate
```
4. Install required packages from requirements.txt file:
```bash
pip install -r requirements.txt
```

## Request examples
### Getting a list of all titles
```bash
http://127.0.0.1:8000/api/v1/titles/
```
Response
```bash
[
{
"count": 0,
"next": "string",
"previous": "string",
"results": []
}
]
```
### Get review by id
```bash
http://127.0.0.1:8000/api/v1/titles/{title_id}/reviews/{review_id}/

```
Response
```bash
{
"id": 0,
"text": "string",
"author": "string",
"score": 1,
"pub_date": "2019-08-24T14:15:22Z"
}
```

## ip address/domain
51.250.13.249/tsurik.ddns.net

## Developers
[Sergey Afonin](https://github.com/afoninsb)
[Vadim Kovalev](https://github.com/Parker-ink)
[Evgeniy Tsuran](https://github.com/tsurik1)

## License
[MIT](https://choosealicense.com/licenses/mit/)
