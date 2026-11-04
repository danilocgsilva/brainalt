# Project structure:

```
my-fullstack-app/
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── api/
│   │   │   ├── v1/
│   │   │   │   ├── __init__.py
│   │   │   │   ├── dependencies.py
│   │   │   │   └── endpoints/
│   │   │   │       ├── __init__.py
│   │   │   │       ├── users.py
│   │   │   │       └── items.py
│   │   ├── core/                  
│   │   │   ├── __init__.py
│   │   │   ├── config.py          
│   │   │   ├── security.py        
│   │   │   └── exceptions.py      
│   │   ├── crud/                  
│   │   │   ├── __init__.py
│   │   │   ├── base.py
│   │   │   ├── user.py
│   │   │   └── item.py
│   │   ├── models/                
│   │   │   ├── __init__.py
│   │   │   ├── base.py
│   │   │   ├── user.py
│   │   │   └── item.py
│   │   ├── schemas/               
│   │   │   ├── __init__.py
│   │   │   ├── user.py
│   │   │   └── item.py
│   │   ├── services/              
│   │   │   ├── __init__.py
│   │   │   ├── base.py            
│   │   │   ├── user_service.py    
│   │   │   └── item_service.py
│   │   ├── tests/                 
│   │   │   ├── __init__.py
│   │   │   ├── conftest.py        
│   │   │   ├── test_users.py      
│   │   │   └── test_items.py
│   │   ├── main.py                
│   │   └── utils/                 
│   │       ├── __init__.py
│   │       ├── logging_config.py
│   │       └── validators.py
│   ├── alembic/
│   │   ├── versions/
│   │   ├── env.py
│   │   ├── script.py.mako
│   │   └── README
│   ├── alembic.ini
│   ├── pyproject.toml
│   └── poetry.lock
│
├── frontend/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── api/                 
│   │   │   ├── client.ts        
│   │   │   ├── endpoints.ts     
│   │   │   └── types.ts         
│   │   ├── assets/
│   │   │   ├── logo.svg
│   │   │   └── main.css
│   │   ├── components/          
│   │   │   ├── layout/
│   │   │   └── ui/              
│   │   ├── composables/         
│   │   │   ├── useAuth.ts       
│   │   │   └── useForm.ts        
│   │   ├── router/
│   │   │   └── index.ts
│   │   ├── store/                
│   │   │   ├── user.store.ts     
│   │   │   └── item.store.ts
│   │   ├── types/                
│   │   │   ├── index.ts
│   │   │   └── global.d.ts       
│   │   ├── utils/
│   │   │   ├── formatters.ts     
│   │   │   └── validators.ts     
│   │   ├── views/                
│   │   │   ├── Home.vue
│   │   │   ├── Users.vue
│   │   │   └── Items.vue
│   │   ├── App.vue
│   │   └── main.ts              
│   ├── src/__tests__/           
│   │   ├── composables/
│   │   ├── components/
│   │   └── store/
│   ├── tailwind.config.js
│   ├── vite.config.ts
│   ├── tsconfig.json
│   └── package.json               
│
├── .dockerignore                  
├── .env.example                   
├── .gitignore                     
├── Makefile                       
├── docker-compose.yml             
└── docker-compose.dev.yml         
```


