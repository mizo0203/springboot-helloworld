# springboot-helloworld

Spring Boot 2 で `Hello, World!` を出力する Web アプリ

## How to Run

```bash
$ ./gradlew bootRun
```

```bash
$ curl -i http://localhost:8080/context-path/
HTTP/1.1 200 
Content-Type: text/plain;charset=UTF-8
Content-Length: 14
Date: Mon, 15 Jun 2020 23:21:28 GMT

Hello, World!
```

## License

    Copyright 2020 Satoki Mizoguchi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
