# fortune-generator


https://www.youtube.com/watch?v=Twi3gtYFDqk
![image](https://github.com/MahalaxmiSadula/fortune-generator/assets/139921242/40f28e68-856e-4eb6-8a93-2045e71f3da4)

restartedMain][0;39m [2m[0;39m[36mConfigServletWebServerApplicationContext[0;39m [2m:[0;39m Exception encountered during context initialization - cancelling refresh attempt: org.springframework.context.ApplicationContextException: Failed to start bean 'webServerStartStop'

![image](https://github.com/MahalaxmiSadula/fortune-generator/assets/139921242/439853bb-40b9-46d3-909c-ba623d905786)

![image](https://github.com/MahalaxmiSadula/fortune-generator/assets/139921242/eabe7cc2-9ac9-4d6e-adf2-3dead08415be)

![image](https://github.com/MahalaxmiSadula/fortune-generator/assets/139921242/9da49d28-0d1e-4c5e-80ba-d3f961dbd21f)

docker build --platform linux/amd64 -t sadulamahalaxmi9/fortune-generator:1.3 .
docker run -p 8080:8080 sadulamahalaxmi9/fortune-generator:1.3
docker push  sadulamahalaxmi9/fortune-generator:1.3  
kubectl expose deployment fortune-generator-deployment --type=LoadBalancer --port=80 --target-port=8080

https://waytohksharma.medium.com/exec-usr-local-openjdk-11-bin-java-exec-format-1b68effb2446
