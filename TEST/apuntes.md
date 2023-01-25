## Lanzar y ejecutar pruebas en un contenedor

$ docker push santidisturvios/dotnet:v1
$ docker run -it --name WpfApp1 santidisturvios/dotnet:v1 bash
root@dc5141d37ee7:/app/WpfApp2# dotnet build WpfApp2.sln
root@036ca8aa7c06:/app/WpfApp2# dotnet test Test1 
