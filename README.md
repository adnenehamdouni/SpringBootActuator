# SpringBootActuator

http://localhost:8081//actuator-app/manage


## Info 
http://localhost:8081//actuator-app/manage/info

info.app.version=1.0-Beta

{
"app": {
"version": "1.0-Beta"
},
"example": {
"key": "value"
}
}

## metrics 
http://localhost:8081//actuator-app/manage/metrics

<!--{
  "names": [
    "jvm.gc.pause",
    "jvm.buffer.memory.used",
    "jvm.memory.used",
    "jvm.buffer.count",
    // ...
  ]
}-->

http://localhost:8081//actuator-app/manage/metrics/jvm.gc.pause
http://localhost:8081//actuator-app/manage/metrics/http.server.requests
http://localhost:8081//actuator-app/manage/env

