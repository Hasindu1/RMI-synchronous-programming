9)Here the thread safety of the increment() method has been achived by putting the synchronized method to the method declaration,so it will ensure that only one thread will be 
access the method at a time.

10)In here one Server object will handle multiple clients,because of that when a client is connecting to the server always increment() method will be invoke in the client side 
and will be increment by one in the server side variable called count.So it proves that server object's instantion is Singelton.So this per call  instantiation.We can achive per client
instantiation by creating several remote objects . 