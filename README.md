This is a simple go app which outputs the container ID (host name) and the counter for accessing it.

1- you can run the `Docker file`. It will build the image and containerize the go application. 

2- Run the container and you can access the go app on `http://<containerIP>:8888`.

3- you can compile the go file by running `RUN CGO_ENABLED=0 GOOS=linux go build -o simple-webpage .` in the current directory in your local machine. After that you can run the compiled by `./simple-webpage` command.\
    a- check `http://localhost:8888`

