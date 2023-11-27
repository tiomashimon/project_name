project/
├── backend/
│   ├── core_apps/
│   │   ├── app1/
│   │   └── app2/
│   ├── requirements/
│   │   ├── base.txt
│   │   ├── local.txt
│   │   └── production.txt
│   ├── django_project_name/
│   ├── Docker/
│   │   ├── local/
│   │   │   └── Dockerfile.backend
│   │   └── production/
│   │       └── Dockerfile.backend
│   └── manage.py  
├── frontend/
│   ├── src/
│   ├── Docker/
│   │   ├── local/
│   │   │   └── Dockerfile.frontend
│   │   └── production/
│   │       └── Dockerfile.frontend
│   ├── requirements/
│   │   ├── base.txt
│   │   ├── local.txt
│   │   └── production.txt
├── .gitignore 
└── docker-compose.yml



 Сервер
 Плюси:
-удобний
-не потрібно запускати локально все іншим користувачам
-кожну зміну в коді не потрібно добавляти фронту
Мінуси:
- ціна

Локально:
Плюси:
-Ціна
Мінуси:
- налаштування докеру та ознайомлення з ним
- кожну зміну в коді потрібно кожен раз фетчити 


























