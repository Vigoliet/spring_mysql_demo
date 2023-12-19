# spring_mysql_demo

## REST API

CRUD = Create, Read, Update, Delete

BASE_URL= http://localhost:8080/api/

- **Create** POST: {BASE_URL}/{resource}
- **Read (All)** GET: {BASE_URL}/{resource}/{id}
- **Update (one)** GET: {BASE_URL}/{resource}/{id}
- **DELETE (one)** PUT: {BASE_URL}/{resource}/{id}

### Example: Users

BASE_URL= http://localhost:8080/

- **Create** POST: http://localhost:8080/users/5
- **Read (one)** GET: http://localhost:8080/users/5
- **Read (All)** GET: http://localhost:8080/users/
- **Update (one)** GET: http://localhost:8080/users/5
- **DELETE (one)** PUT: http://localhost:8080/users/5

### Example: Cars

BASE_URL= http://localhost:8080/

- **Create** POST: http://localhost:8080/cars/5
- **Read (one)** GET: http://localhost:8080/cars/5
- **Read (All)** GET: http://localhost:8080/cars/
- **Update (one)** GET: http://localhost:8080/cars/5
- **DELETE (one)** PUT: http://localhost:8080/cars/5