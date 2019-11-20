# GoLang

Sample testing app for extracting system users.

##Usage

[your_host]$ go run main.go -format=json
[
 {
  "id": 1000,
  "name": "some_user_1",
  "home": "/home/some_user_1",
  "shell": "/bin/bash"
 },
 {
  "id": 1002,
  "name": "some_user_2",
  "home": "/home/some_user_2",
  "shell": "/bin/bash"
 }
]
[your_host src]$ vi main.go
[your_host src]$ go run main.go -format=csv
name,id,home,shell
some_user_1,1000,/home/some_user_2,/bin/bash
some_user_2,1002,/home/some_user_2,/bin/bash
