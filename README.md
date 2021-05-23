# task-manage
## 1. Clone the repository
```
git clone https://github.com/star-008/task-manage.git
cd task-manage
git submodule init
git submodule update
``` 
## 2. Run the backend
```
cd backend
bundle install
rails db:create
rails db:migrate
rails db:seed
rails server
```
## 2. Run the backend
```
cd frontend
yarn
yarn start
```
## Default user
> **Email**: admin@test.com <br> **Password**: password
