# Task6
### The server waits for two connections on the same port.
    After they both have arrived, they send their names on one line.
    After that, they start exchanging messages in the following way.
    First, client 1 sends a message to the server, and the server sends this message on to client 2.
    Then, client 2 sends a message to the server, and the server sends this message on to client 1.
    The clients continue sending their messages in alternate steps.

    1. First, the server accepts n connections from clients, n being a fixed number.
       Once a client appears, he sends his name on a one line message.
       After all names have been collected, the server starts the following activity,
