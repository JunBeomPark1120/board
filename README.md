- 프로젝트 생성/앱 생성
```bash
django-admin startproject <pjt-name>
django-admin startapp <app-name>
```

- 나머지
```bash
python manage.py <command>
```

## HTTP status code

- 200 : OK
- 30X : redirect
- 4XX : client error
    - 401 : Uhauthorized
    - 403 : fobidden
    - 404 : Not Found
- 500 : server error