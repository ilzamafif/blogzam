---
title: "Membuat Image Dengan Dockerfile"
date: 2021-09-24T11:48:18Z
draft: false
---

pertaama buat folder contoh `docker-app` 
lalu buat file disini saya menggunakan go 
```go
package main

import (
	"fmt"
	"net/http"
)

func main() {
	http.HandleFunc("/", func(w http.ResponseWriter, r *http.Request) {
		fmt.Fprintf(w, "Hello World!")
	})

	http.ListenAndServe(":8080", nil)
}
```
Dockerfile adalah ...

buat file `Dockerfile`
```
#membuat image dengam imaage yang sudah ada (golang)
FROM golang:11.11.4

#copy namafile ke image
COPY main.go /app/main.go

#jalankan aplikasi
CMD ['go', 'run', '/app/main.go']
```

build image dengan docker file
```
docker build --tag app-golang:1.0 .
```

cek docker image apakah sudah ada 
`docker images`

membuat containernya "app golang" 
```
docker container create --name app1 -p 8080:8080 app-golang:1.0
```

cek apakah sudah berhasil 
```
docker container ls --all
```

jalankan 
```
docker container start app1
``` 

cek apakah jalan
```
docker container ls
```