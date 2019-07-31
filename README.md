# TestRepository

https://340104922532.signin.aws.amazon.com/console

-------------------------------------
/var/log/httpd/elasticbeanstalk-access_log
-------------------------------------
203.192.246.135 (-) - - [31/Jul/2019:11:04:32 +0000] "GET / HTTP/1.1" 404 1074 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36"
203.192.246.135 (-) - - [31/Jul/2019:11:04:33 +0000] "GET /favicon.ico HTTP/1.1" 404 1085 "http://discovery-server.yzg3afhakx.us-east-2.elasticbeanstalk.com/" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36"
203.192.246.135 (-) - - [31/Jul/2019:11:06:10 +0000] "GET / HTTP/1.1" 404 1074 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36"
203.192.246.135 (-) - - [31/Jul/2019:11:09:02 +0000] "GET / HTTP/1.1" 404 1074 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36"
203.192.246.135 (-) - - [31/Jul/2019:11:10:55 +0000] "GET / HTTP/1.1" 404 1074 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36"
203.192.246.135 (-) - - [31/Jul/2019:11:37:45 +0000] "GET / HTTP/1.1" 404 1074 "-" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36"



-------------------------------------
/var/log/tomcat8/catalina.2019-07-31.log
-------------------------------------
31-Jul-2019 10:57:54.073 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Server version:        Apache Tomcat/8.5.40
31-Jul-2019 10:57:54.079 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Server built:          May 2 2019 18:02:51 UTC
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Server number:         8.5.40.0
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log OS Name:               Linux
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log OS Version:            4.14.123-86.109.amzn1.x86_64
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Architecture:          amd64
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log Java Home:             /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.201.b09-0.43.amzn1.x86_64/jre
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log JVM Version:           1.8.0_201-b09
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log JVM Vendor:            Oracle Corporation
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log CATALINA_BASE:         /usr/share/tomcat8
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.startup.VersionLoggerListener.log CATALINA_HOME:         /usr/share/tomcat8
31-Jul-2019 10:57:54.080 INFO [main] org.apache.catalina.core.AprLifecycleListener.lifecycleEvent The APR based Apache Tomcat Native library which allows optimal performance in production environments was not found on the java.library.path: [/usr/java/packages/lib/amd64:/usr/lib64:/lib64:/lib:/usr/lib]
31-Jul-2019 10:57:54.323 INFO [main] org.apache.coyote.AbstractProtocol.init Initializing ProtocolHandler ["http-nio-8080"]
31-Jul-2019 10:57:54.353 INFO [main] org.apache.tomcat.util.net.NioSelectorPool.getSharedSelector Using a shared selector for servlet write/read
31-Jul-2019 10:57:54.390 INFO [main] org.apache.coyote.AbstractProtocol.init Initializing ProtocolHandler ["ajp-nio-8009"]
31-Jul-2019 10:57:54.392 INFO [main] org.apache.tomcat.util.net.NioSelectorPool.getSharedSelector Using a shared selector for servlet write/read
31-Jul-2019 10:57:54.398 INFO [main] org.apache.catalina.startup.Catalina.load Initialization processed in 1209 ms
31-Jul-2019 10:57:54.440 INFO [main] org.apache.catalina.core.StandardService.startInternal Starting service [Catalina]
31-Jul-2019 10:57:54.442 INFO [main] org.apache.catalina.core.StandardEngine.startInternal Starting Servlet Engine: Apache Tomcat/8.5.40
31-Jul-2019 10:57:54.470 INFO [localhost-startStop-1] org.apache.catalina.startup.HostConfig.deployDirectory Deploying web application directory [/var/lib/tomcat8/webapps/ROOT]
31-Jul-2019 10:57:55.711 INFO [localhost-startStop-1] org.apache.jasper.servlet.TldScanner.scanJars At least one JAR was scanned for TLDs yet contained no TLDs. Enable debug logging for this logger for a complete list of JARs that were scanned but no TLDs were found in them. Skipping unneeded JARs during scanning can improve startup time and JSP compilation time.
31-Jul-2019 10:57:55.934 INFO [localhost-startStop-1] org.apache.catalina.startup.HostConfig.deployDirectory Deployment of web application directory [/var/lib/tomcat8/webapps/ROOT] has finished in [1,450] ms
31-Jul-2019 10:57:55.943 INFO [main] org.apache.coyote.AbstractProtocol.start Starting ProtocolHandler ["http-nio-8080"]
31-Jul-2019 10:57:55.995 INFO [main] org.apache.coyote.AbstractProtocol.start Starting ProtocolHandler ["ajp-nio-8009"]
31-Jul-2019 10:57:56.034 INFO [main] org.apache.catalina.startup.Catalina.start Server startup in 1635 ms

