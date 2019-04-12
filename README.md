# django-settings
This project is how to separate settings for dev, production.

## How to
[[Django] settings.py 분리하기](https://hyunalee.tistory.com/52?category=578325)를 참고해주세요.

## Run Server
```
// python3 manage.py runserver --settings={settings 파일 경로}
python3 manage.py runserver --settings=base.settings.local_settings
```

[localhost:8000](http://localhost:8000)

`local_settings.py`는 자신의 로컬 환경에서 바라보고자 하는 DB를 설정한 파일이다.
`.gitignore` 파일로 인해 `git`에는 올라가지 않으므로 자신이 직접 만들어 실행하면 된다. 
