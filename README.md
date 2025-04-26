# cs433-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS433 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs433-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92087&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS433 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This is the first of the programming and hands on networking assignment. Make sure to save the work and store the configuration, setup installations, source code that you do in this assignment. The subsequent set of assignments will build on the work you do in this assignment.

You are free to choose the programming language of your choice (C/C++, Python, Java, Go, or any other). I would recommend ‘C’ for rich programming experience and understanding the low-level system APIs.

Prerequisite: Tools and Data Preparation (0 points)

<ol>
<li>Wireshark/Tcpdump tools are necessary to analyze the traffic.</li>
<li>Choose around 5 of your favorite novels (text format) from ProjectGuttenberg or any reliable source.
<ol>
<li>Example: War and Peace:https://www.gutenberg.org/files/2600/2600-0.txt. You are going
to use these files for building the Socket programs.
</li>
<li>Prepare a test file (eg. Test.txt) of size=10KB. Refer “dd” or“truncate” command (man dd or man truncate) for more details. Try to populate contents from one of the downloaded text files. &lt; Necessary to verify the content.&gt;</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Client-Server Programming (TCP and UDP Sockets)

3. Implement as simple Server (Mini Library) and Client (Reader) Programs in the language of your choice. (10 points)

<ol>
<li>(a) &nbsp;TCP Server: The server program implemented as say &lt;tcp_server.c&gt; would listen on a port 12345. Upon request from a client, it will try to index to the corresponding file, read it from the system and transmit the contents of requested file to the client. Upon completion of transfer, it would close the connection. For simplicity, you can assume the files are locally accessible within the same directory as that of server program.</li>
<li>(b) &nbsp;TCP Client: Client program would accept the “book name” from user as input (can be hardcoded in CLI parameter) to be downloaded and request the server to download the book. The client will then save the book on the local filesystem with name “&lt;Name_of_Book&gt;+&lt;Protocol=TCP&gt;+&lt;ClientProcessPID&gt;.txt”.</li>
<li>(c) &nbsp;UDP Server: Also, implement the server with UDP protocol, say udp_server.c for same port 12345.</li>
<li>(d) &nbsp;UDP Client: Also, implement the same with UDP protocol, say udp_client.c. Here the Protocol would instead be UDP.</li>
</ol>
Now, evaluate the following aspects:

<ol>
<li>Compute the time taken by TCP client/server to download the file and the time taken by UDP Client/server to download the same file. List as a table, for: (5 points)
<ol>
<li>The largest of the 5 files you chose.</li>
<li>For 10KB file.</li>
</ol>
Note: you need to compute the time on the client side beginning from the first operation (connect in case of TCP) till the end of transfer (close) operations.
</li>
<li>What is the throughput achieved for TCP and UDP modes?</li>
<li>Diff/compare the files with the original files on the server. Do you observe any differences? (2.5 points)</li>
<li>Use“wc”tooltofindhighleveldifferencesintermsofline/word and character count and Use “diff” tool to list the differences if any. (2.5 points)</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Experimentation with socket configurations

For the subsequent experiments, fix the server buffer size to 1024 Bytes and choose any one file (10KB) and evaluate the following:

<ol>
<li>Now set the Client buffer size (TCP and UDP) to 2048 bytes. How many packets do you see are exchanged between client and server on Wireshark? Is there any impact on the downloaded file size, diff output for the TPC and UDP clients? In each case, please present the results as a table provide your analysis. (5 points)</li>
<li>Now set the Client buffer size (TCP and UDP) to 512 bytes. How many packets do you see are exchanged between client and server on Wireshark? Is there any impact on the downloaded file size, diff output for the TPC and UDP clients? In each case, please present the results as a table provide your analysis. (5 points)</li>
<li>Now set the Server size (TCP and UDP) buffer size to 512 bytes and Client buffer size (TCP and UDP) to 2048 bytes. How many packets do you see are exchanged between client and server on Wireshark? Is there any impact on the downloaded file size, diff output for the TPC and UDP clients? In each case, please present the results as a table provide your analysis. (5 points)</li>
<li>Reset all the buffer size to 1024 and modify the client programs (TCP and UDP) such that every time client receives data, it sleeps for about 10 milli seconds. Again, analyze the result for same parameters. (5 points)</li>
<li>Further, check if you can deploy both the TCP and UDP servers and run the TCP and UDP clients at the same time (concurrently). Possible? Not possible? IF yes why? and if not, why not? (5 points)</li>
</ol>
In the next iteration, you would be introduced with Mininet (a network emulator).

</div>
</div>
</div>
