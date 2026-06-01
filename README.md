# Tch-Laboratorium-11

$ docker compose up -d

 ✔ Network lab11net Created                                                                                        0.0s
 ✔ Container web3   Created                                                                                        0.1s
 ✔ Container web1   Created                                                                                        0.1s
 ✔ Container web2   Created

$ curl -I http://localhost:8081
HTTP/1.1 200 OK
Server: nginx/1.31.1
Date: Mon, 01 Jun 2026 01:04:45 GMT
Content-Type: text/html
Content-Length: 610
Last-Modified: Mon, 01 Jun 2026 00:55:58 GMT
Connection: keep-alive
ETag: "6a1cd89e-262"
Accept-Ranges: bytes


$ curl http://localhost:8081
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Laboratorium 11</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; background-color: #f0f2f5; }
        .card { background: white; padding: 30px; display: inline-block; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        h1 { color: #1a73e8; }
    </style>
</head>
<body>
    <div class="card">
        <h1>Laboratorium nr 11</h1>
        <h2>Student: Andrzej Iwanicki</h2>
        <p>Status wolumenu: Read-Only</p>
    </div>
</body>
</html>
$ curl -I http://localhost:8082
HTTP/1.1 200 OK
Server: nginx/1.31.1
Date: Mon, 01 Jun 2026 01:06:47 GMT
Content-Type: text/html
Content-Length: 610
Last-Modified: Mon, 01 Jun 2026 00:55:58 GMT
Connection: keep-alive
ETag: "6a1cd89e-262"
Accept-Ranges: bytes
$ curl http://localhost:8082
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Laboratorium 11</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; background-color: #f0f2f5; }
        .card { background: white; padding: 30px; display: inline-block; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        h1 { color: #1a73e8; }
    </style>
</head>
<body>
    <div class="card">
        <h1>Laboratorium nr 11</h1>
        <h2>Student: Andrzej Iwanicki</h2>
        <p>Status wolumenu: Read-Only</p>
    </div>
</body>
</html>
$ curl -I http://localhost:8083
HTTP/1.1 200 OK
Server: nginx/1.31.1
Date: Mon, 01 Jun 2026 01:05:28 GMT
Content-Type: text/html
Content-Length: 610
Last-Modified: Mon, 01 Jun 2026 00:55:58 GMT
Connection: keep-alive
ETag: "6a1cd89e-262"
Accept-Ranges: bytes

$ curl http://localhost:8083
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Laboratorium 11</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; background-color: #f0f2f5; }
        .card { background: white; padding: 30px; display: inline-block; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        h1 { color: #1a73e8; }
    </style>
</head>
<body>
    <div class="card">
        <h1>Laboratorium nr 11</h1>
        <h2>Student: Andrzej Iwanicki</h2>
        <p>Status wolumenu: Read-Only</p>
    </div>
</body>
</html>
