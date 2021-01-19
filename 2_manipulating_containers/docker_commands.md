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