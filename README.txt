Ex



curl -X POST -H "Content-Type: application/json" -d '{"shutdown": true}' http://192.168.99.2:31002/control
curl -X POST -H "Content-Type: application/json" -d '{"set_ready": false}' http://192.168.99.2:31000/control
curl -X POST -H "Content-Type: application/json" -d '{"set_alive": false}' http://192.168.99.2:31000/control  
curl -X POST -H "Content-Type: application/json" -d '{"set_high_cpu": true}' http://192.168.99.2:31000/control

