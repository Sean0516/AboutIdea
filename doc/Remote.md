JVM 远程调试

1. 在 Debug Configurations  开启 Remote JVM Debug 
2. 运行 jar 的时候，使用参数 java -jar  -agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005 Demo.jar
3. IDEA 中 ，Debug 运行 remote Debug 
4. 通过断点进行断点调试
