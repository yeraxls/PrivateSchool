1. dotnet restore
2. dotnet publish -c Release -o out
3. dotnet out/PrivateSchool.dll
4. docker build -t privatescholl .
5. docker images
6. docker run -d -p 5024:5024 --name webapp privatescholl


#  pasos:
1. Create project  	✔️
2. Docker           ✔️
3. Create CRUD teacher
4. Create CRUD student
5. Create CRUD subjects
6. Create, delete, managment schedule
7. managment test score