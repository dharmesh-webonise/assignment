# Shopping Cart API 
User add a prodct to his cart and remove product from cart 
## Installation

Requirements 
 
```bash
PHP 
Apache2
mysql-server
docker 
docker-compose
```

```
steps for installation
 - name folder as develop-webonise.com
 - Clone the repository 
 - import database.sql file
 - install php-bcmath library

```

```bash
docker setup 
  - install docker 
  - install docker-compose
  - run command : docker-compose build
  - run command : docker-compose up

use Basic auth for authrization 
    username  - test-webonise
    password  - Test1234


```

## Routes

```
http://www.develop-webonise.com
http://www.develop-webonise.com/product
http://www.develop-webonise.com/product/add
http://www.develop-webonise.com/product/$id/edit
http://www.develop-webonise.com/product/$id (Method GET- "Read one product") (Method Delete- "Delete prodcut from Database") 

http://www.develop-webonise.com/category
http://www.develop-webonise.com/category/add
http://www.develop-webonise.com/category/$id/edit
http://www.develop-webonise.com/category/$id (Method GET- "Read one Category") (Method Delete- "Delete prodcut from Database") 

http://www.develop-webonise.com/cart
http://www.develop-webonise.com/cart/add
http://www.develop-webonise.com/cart/$id (Method Delete- "Delete cart prodcut from cart")

```
