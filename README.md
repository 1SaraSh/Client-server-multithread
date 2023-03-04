# Client-server-multithread

This assignment, will write a multithreaded file server program. The server makes a collection of files available for transmission to clients.
The file has a collection of TEXT files. The directory used in this example is:
"C:\\Users\\saraa\\OneDrive\\Desktop\\Distributed Systems". 
Please specify your own directory with your text files, or the text files provided in "Distributed Systems" Folder. Edit the code in the areas with an X, with your directory.

You can start the program by running the server, and then run one or both clients. Write the command that you want in the client, and you'll recieve the needed outcome specified.

<h3>Commands:</h3>
<ul>
          <li>
          "LIST"
          A list of names of all the files that are available on the server.
          </li>
          <li>
          "GET <filename>":
          The server checks whether the requested file exists. If so, it sends "OK" as a message to the client. Then it sends the contents of the file and closes the               connection. Otherwise, it sends a line beginning with the word "ERROR" to the client.
          </li>
          <li>
          The server can also respond with the message "unknown command" if the command it reads is not one of the two possible legal commands.
          </li>
</ul>       
<h3>Server Display:</h3>
                The server displays if the connection has been connnected and when it is disconnected, and the ThreadID for each client active in that moment.
          
