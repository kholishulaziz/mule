**Mule training & exercise from MuleSoft.U Developer Essentials**

**Required:**
* JDK 8
* MySql 8
* mock http service (https://my-json-server.typicode.com)
* Mule ESB Runtime 3.9.4
* Anypoint Studio 6.6

**Starting apps with an environment variable on standalone runtime:**
```
mule -M-Denv=dev
```

**Service:**
```
http://localhost:8081/flights
http://localhost:8081/console
```
```
http://localhost:8081/united?code=SFO
http://localhost:8081/american?code=SFO
```

**Demo:**
http://aziz-mule.us-e2.cloudhub.io/flights