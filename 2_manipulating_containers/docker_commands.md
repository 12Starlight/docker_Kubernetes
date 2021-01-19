# **Docker Commands**

<kbd>docker ps</kbd> ~ Lists all `running` containers

<kbd>docker run busybox ping google.com</kbd> ~ Pings Google servers and measures amount of latency

<kbd>docker ps --all</kbd> ~ List all the containers ever created.

&nbsp;

### **Docker run is actually a composition of two separate commands**

![alt text](./assets/create_start.jpg "Two Commands That Make Up Run")

&nbsp;

![alt text](./assets/separate_example.jpg "Examples")

&nbsp;

Note: <kbd>-a</kbd> ~ Actually watches for output from the container and print it out
to the terminal. After a container has been exited, just use the id of the container
you want to run agian with the start command. 

&nbsp;

<kbd>docker system prune</kbd> ~ Deletes all stopped containers and caches.

&nbsp;

### **If we forgot to add the `-a` we can get around it with**

![alt text](./assets/logs.jpg "Logs")

&nbsp;

![alt text](./assets/logs_example.jpg "Logs example")

&nbsp;

Note: One thing to keep in mind is that the container does not get ran again, we
just get a list of all the logs that have been emitted from the container. 