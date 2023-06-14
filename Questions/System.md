# System

### **What is a web server?**
> - A web server can be described as a computer that stores web pages and distributes them. When you enter a URL into a browser, the browser contacts a web server to request the page. The page is then sent back to the browser by the web server which is displayed on the screen, such as Nginx and Apache.

<br/>

### **What Is Difference Between Concurrency And Parallelism?**
> - **Concurrency**: Multiple tasks making progress at the same timem, such as multithreaded.
> - **Parallelism**: The tasks are divided into smaller sub-tasks that are processing simultaneously or parallel, such as load balancing.

<br/>

### **What Is Microservice Architecture?**
<p align="center">
<img src="img/microservices.png" alt="data_type" title="data_type" width="60%">
</p>

> - `Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs`. These services are owned by small, self-contained teams.
> - Related Reference : [What are Microservices?](https://aws.amazon.com/microservices/)

<br/>


### **What Is ACID?**
> - **A (Atomicity)**: Atomicity means that you guarantee that either all the transaction succeeds or failure, we commit when transaction succeeds, and we roll back when the transaction failure.
> - **C (Consistency)**: This ensures that all data will be consistent when execute transaction.
> - **I (Isolation)**: All transactions will occur in isolation.
> - **D (Durability)**: Durability means that, once a transaction is committed, it will remain in the system – even if there’s a system crash.

<br/>