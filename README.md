Build `war` command:

```
gradle war
```

Command to start Tomcat in debug (on port 8000)

```
JPDA_OPTS="-agentlib:jdwp=transport=dt_socket,address=8000,server=y,suspend=n" ./catalina.sh jpda start
```