# Client-server-multithread

This assignment, will write a multithreaded file server program in Java language (Netbeans version 12.5 was formally used). The server makes a collection of files available for transmission to clients.<br><br>
The file has a collection of <b>TEXT</b> files. The directory used in this example is:<br>
_"C:\\Users\\saraa\\OneDrive\\Desktop\\Distributed Systems"._
<br>
<p>Please specify your own directory with your text files, or the text files provided in "Distributed Systems" Folder. Edit the code in the areas with an X, with your preferred directory.</p> 
<p><i>Note: All of "Distributed Systems" folder content is taken from Wikipedia.</i></p>

<h3>Run</h3>
You can start the program by running the server, and then run one or more clients. Write the command that you want in the client, and you'll recieve the needed outcome specified. <br>In "Program" Folder, you can find the Server and Client programs, add as many clients as you'd like. <br>4 Clients are provided in the folder, if more is wanted just edit the IP address in the main method of each Client program.
<br>
<h3>Commands:</h3>
<ul>
          <li>
          "LIST":
          A list of names of all the files that are available on the server.
          </li>
          <li>
          "GET <filename>":
          The server checks whether the requested file exists. If so, it sends "OK" as a message to the client. Then it sends the contents of the file and <b>closes the               connection</b>. Otherwise, it sends a line beginning with the word "ERROR" to the client.<br>
          ex. "GET C.txt"
          </li>
          <li>
          The server can also respond with the message "UNKNOWN COMMAND" if the command it reads is not one of the two possible legal commands.
          </li>
</ul>     <br>  
<h3>Server Display:</h3>
                The server displays if the connection has been connnected and when it is disconnected, and the ThreadID for each client active in that moment.
          
