# csci3761-lab-1--server-and-client-solved
**TO GET THIS SOLUTION VISIT:** [CSCI3761 Lab 1- Server and Client Solved](https://www.ankitcodinghub.com/product/csci3761-lab-1-server-and-client-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100356&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI3761 Lab 1- Server and Client Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
=

</div>
</div>
<div class="layoutArea">
<div class="column">
We will learn the basic concurrent File Transfer Services that consists of a client and server. We will use the TCP protocol for this lab.

2. ProjectDescription:SFTS(SimpleFileTransferServices)

In this programming assignment, you are to build a simple file copy service that consists of a client and server. The server and client program MUST run on separate machines.

2.1 Server

<ul>
<li>A server does NOT have to handle multiple clients concurrently, but it must handle multiple clients consecutively.</li>
<li>The server will be started on a machine in a directory. That directory will be considered the HOME directory for the server.</li>
<li>A server should support the following requests from clients:</li>
</ul>
1. Show files at the server’s current directory: ‘catalog’ • Synopsis: catalog

– Display the all file names under current directory

<ul>
<li>A list of files should be sent from the server to the client
and displayed on the client’s screen.
</li>
<li>Hint: it is similar to ‘ls’ Unix/Linux service</li>
</ul>
2. Download files: ‘download’

• Synopsis: download source-filename

– When a server gets “download” request with “source- filename”, it checks first whether it has the requested file name under its current directory or not. If the server does not have the file, it sends an error message back to the client. Otherwise, it opens the requested file and sends it (“download”) to the client.

3. Upload files: ‘upload’

• Synopsis: upload source-filename

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
– When a server gets an “upload” request, it checks first whether it has already the same name of the requested file (dest-filename) in its current directory. If the server has already the same name of file which was sent with “upload” request from a client, it performs “upload” service and sends the following warning message to the client for display: “‘dest-filename’ file has been overwritten”. Otherwise, it receives the file from the client and creates “dest-filename” at the current directory.

4. Terminating the server: “bye”

<ul>
<li>Synopsis: bye [no-argument]</li>
<li>When a server receives “bye” request from a client, it
terminates itself with display message “File copy server is down!” and gracefully disconnect the connection with the client.
</li>
</ul>
<ul>
<li>A server should be able to handle exceptions (errors) for each command.</li>
<li>Any error message occurred at the server should be informative and sent to
and displayed to the client.

2.2 Client
</li>
<li>A client makes a connection to the server when it tries to download or upload files. You can specific the IP address for the server.</li>
<li>A client requests following services to the server:
<ul>
<li>catalog, ls, download, upload, bye.</li>
<li>Synopsis of each services refer to the description of the server</li>
</ul>
</li>
<li>A client also supports following requests from the user:</li>
</ul>
1. Show files at the server’s current directory: ‘catalog’ • Synopsis: catalog

– Get list the all file names under current directory from the server and display the received files.

2. Download files: ‘download’

• Synopsis: download source-filename dest-filename

– When a client gets “download” request, it sends its request to the server with two arguments (source- filename and dest-filename). If the client receives an error message from the server, it displays an error message to the user without performing “download” service. Otherwise, it receives the file from the server and copies to the dest-name. If the dest-name file is

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
already exists, the client should display the following message after the finish the ‘download’ request: “’dest- filename” has been overwritten”.

3. Upload files: ‘upload’

• Synopsis: upload source-filename dest-filename

– When a client gets “upload” request, it checks first whether it has the requested file(source-filename) under its current directory or not. If the client does not have the request file under current directory, it displays “error” message back to the user without performing “upload” service. Otherwise, it sends its request to the connected server and performs “upload” operation. If the client receives the message about the overwriting, it displays the received the message.

4. Terminating the server: “bye” • Synopsis: bye

– A client sends “bye” request to the connected server and terminates itself with display message “Internet copy client is down!”.

• A client should be able to handle exceptions (errors) for each command.

Hint: you don’t have to write entire code for the ‘catalog’ service. Your program (server or client) needs to just use (or call) a Unix/Linux service that provides the same result as your program is expected to produce such as ‘ls’.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2.3 Programming environment

<ul>
<li>All programs have to be written C or C++ and run on UNIX like platform.</li>
<li>All connections between a server and clients should be TCP/IP socket.
2.4 Required Skills

Everyone is expected to know following skills and knowledge in order to complete this programming assignment.

<ul>
<li>TCP/IP Socket programming</li>
<li>Understanding UNIX like Operating System</li>
<li>Creating/invoking processes in UNIX like environment</li>
<li>Makefile</li>
<li>C or C++
3. Deliverables

The deliverables for this assignment include the following files:
</li>
</ul>
</li>
</ul>
<ul>
<li>Written C or C++ Code for Server and Client program</li>
<li>Makefile</li>
<li>Readme: A short description of your programs includes: the names of created
executable images which will be created after run your makefile, how to run your programs.

4. Submission

Please do the followings when you submit your programming assignment.
</li>
</ul>
<ul>
<li>Create a zip file that contains your written source code, makefile and readme.
DO NOT INCLUDE EXECUTABLES AND COMPILED OBJECT FILES.
</li>
<li>Upload it to the class Canvas by deadline.
5. Grading

The maximum point for the assignment is 40. This programming assignment will be graded by following criteria.
</li>
</ul>
• Completeness: 40 points o Connection :

<ul>
<li>§ &nbsp;10 points – if your server and client get connected over TCP network: 15 points</li>
<li>§ &nbsp;If a server and client do not work over TCP, but they work within a machine: 5</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
o ConcurrentServer:

§ 6: if your server handle at least 3 clients consecutively § 0: Otherwise

o Completeness of the server: 12 points

§ Catalog, bye are worth 2 points each

§ “download” and “upload” service is 4 points each

o Completeness of the client: 12 points

§ Each service (bye, catalog ) is worth 2 points

§ “download” and “upload” service are 4 points each

6. IMPORTANT

• Your program will be tested on csegrid.ucdenver.pvt machine (linux

based) with another linux based machine. Please make sure your program runs without problem on both platform and test your program before submit it. If for some reason you can’t get it to work on those systems, but it works on YOUR systems, we will figure out a way to grade it. BUT it must work on 2 machines.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
