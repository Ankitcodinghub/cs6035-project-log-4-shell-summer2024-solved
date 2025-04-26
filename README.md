# cs6035-project-log-4-shell-summer2024-solved
**TO GET THIS SOLUTION VISIT:** [CS6035 Project Log 4 Shell Summer2024 Solved](https://www.ankitcodinghub.com/product/cs6035-project-log4shell-summer2024-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123624&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6035 Project Log 4 Shell Summer2024 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<h3><strong>SPRING2025 SOLUTION<a href="https://www.ankitcodinghub.com/product/cs6035-log4shell-2025-spring-solved/"><span style="color: #0000ff;"> VIEW HERE</span></a></strong></h3>
<h3><strong>FALL2024 SOLUTION<a href="http://ankitcodinghub.com/product/cs6035-project-log4shell-fall24-command-steps-flag-1-6-solved/"><span style="color: #0000ff;"> VIEW HERE</span></a></strong></h3>
<h1>Setup</h1>
To get setup for the flags, follow the steps carefully below, and be sure you are running each in a separate terminal window as noted.

<strong>&nbsp;</strong>

<strong>The VM username and password is log4j and Donald-Knuth</strong> You will need switch users to login to log4j user via:

Credentials can be found in Canvas on the Log4Shell Assignment page

In the home directory of log4j user, start the container with the start script:

./StartContainer.sh

Open a new terminal window and go to “Desktop/log4shell/logs”:

cd Desktop/log4shell/logs

Run the following command to view the logs:

tail -f cs6035.log

OR to view System.out.println messages:

tail -f console.log

You should now see the tail of the log file from the application running.

&nbsp;

<strong>**<em>If the logs stop populating, then just stop and restart the tail. This is happening because the data logged gets too large so the log “rolls over” to another file.</em></strong><em>**</em>

<ol>
<li>Run the LDAP Server:</li>
</ol>
Open a new terminal window and run the following command to set the current directory to “Desktop/log4shell/target”:

You can get the ip address of the vm by running the block below in a terminal (Not necessary, just for informational purposes)

ip addr show

This outputs the vm’s IP

127.0.0.1

<strong>It is very important that this matches the port specified in the Malicious server. If your exploit is not working because it is not connecting to the malicious server, your ports likely do not match OR the vm’s IP is not correct.</strong>

<table>
<tbody>
<tr>
<td width="96"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
You should see the following output:

<ol start="2">
<li>Run the Malicious Server:</li>
</ol>
Open a new terminal and make sure the active directory is the directory that contains your malicious .class file. For simplicity, we have created “Desktop/log4shell/{flag_no}” for you to work in. <strong>Do not leave this directory</strong>. Run the server in “Desktop/log4shell/{flag_no}” by the following command: &nbsp;&nbsp;python3 -m http.server 4242

<strong>It is very important that this matches the port specified in the LDAP server. If your exploit is not working because it is not connecting to the malicious server, your ports likely do not match OR the vm’s IP is not correct</strong> You should see the following output:

&nbsp;

<ol start="3">
<li>Read data that is flowing on the network (This step is required for Flag 2 but is optional for the rest):</li>
</ol>
<strong>To print debug statements from your Java code, tail the </strong>

<strong>~/Desktop/log4shell/logs/console.log file and add System.out.println statements to your Exploit.java.</strong>

&nbsp;

&nbsp;

<h1>Intro Flag</h1>
Now that we are set up, let’s do a quick rundown of Log4j, how it works at a high level, and test that we are able to successfully call and exploit the application.

As you should know from the background and resource’s section, Log4j is an application logging library that outputs user defined program information. An example log statement would look like the following:

static Logger log = LogManager.getLogger(RestServlet.class.getName()); log.debug(“ApplicationId: {}”, applicationId);

The log statement above as you can see, defines the class, log level of the message and the actual message. Notice that we are injecting user input into the log message. This is where our vulnerability is.

To be more specific, here is what the output of the message actually will look like:

&nbsp;

&nbsp;

Now we can map the code above to the logged message. The date/time is defined in configuration files which are out of the scope of this project. Next is where our code starts to map. We have [Classname.java:LineNumber]. This is helpful to know exactly what part of your code is executing and where.

Next, we see DEBUG. This is what is called the log level. Log levels are used for the amount of output you want your application to log, or even to classify errors different from informative messages. The typical log levels are DEBUG, INFO, WARN, ERROR, FATAL. To further explain, if a log level is set to say ERROR, your application will not log anything on WARN, INFO, or DEBUG level. This application is set to DEBUG.

Finally, we get to the actual logged message. As you can see, we log the constant text as well as the injected variable applicationId, which is our applicationId. This is the most important part you will want to pay attention to. Throughout this project, you will try to find messages that log user defined input and inject your malicious string into it.

Now, let’s have some fun and get familiar with the application. To do so, we will call the application normally and then lookup the java version on the application server.

To start we can run a simple inquiry to the services /isAlive endpoint and see what we get back from the logs and see if we can find anything that is exploitable.

<strong><em>GATECH_ID IS A REQUIRED HEADER</em></strong>

Open a new terminal and run:

curl ‘http://localhost:8080/rest/products/isAlive’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

You should see your logs log some messages in the log tailing terminal window. Let’s inspect it.

Go back to the terminal window you are tailing the logs in. When the server intercepts a request, it logs “Request intercepted” to alert the user where the request starts. As we can see, there is not much going on in terms of useful information, but we can see the service did log a message that could be exploitable.

&nbsp;

&nbsp;

Voila! In the highlighted message, we see that it is logging the Method Type: GET, the URL: /rest/products/isAlive, and some headers that are null. This is a good indicator that we can exploit this service by sending lookups through a header.

Let’s call one more endpoint to see how headers work and what the application does when we request user data.

In your curl terminal, run the following command:

curl ‘http://localhost:8080/rest/products/productlist’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

Your output should be similar to:

&nbsp;

&nbsp;

**Note: You can zoom in by using ctrl + scroll

Take some time to inspect the logged messages and try to understand what the program is doing and the flow of it.

Lets try to get the java version on the server now.

The checked headers for this application are content-type, accept, and XNetworkUserId, although not all are always checked/exploitable.

Construct a malicious payload using one of the logged headers that will return the java version of the host of the web application. You should see something like the screenshot below if successful:

&nbsp;

&nbsp;

**Note: You might need to scroll up to see this output.

Do you see the same output? LIGHTWEIGHT BABY! Muahaha! If not, try to research the log4shell exploit more and learn how to exploit the lookup.

Our hunch was correct and we have successfully exploited the vulnerability. You can play around with this if you like and see what other lookups you can perform. It is possible to lookup system settings, environment variables and much more just with this.

<strong><em>Be sure to save your work outside of the VM in case the VM crashes or some other unforeseen issue arises. This will ensure you are not losing your work.</em></strong>

&nbsp;

<h1>Flag 1: Environment Echo (10 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

The endpoint for this exploit can be called and inspected via:

curl ‘http://localhost:8080/rest/products/isAlive’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

<table width="96">
<tbody>
<tr>
<td width="96">ADMIN_PASSWORD</td>
</tr>
</tbody>
</table>
Now that you have seen how to check environment variables, run a lookup for&nbsp; which stores your flag for this exercise. If successful, you should see the below output:

&nbsp;

&nbsp;

&nbsp;

Add this flag (Congratulations! Your flag1 is: <strong>__</strong><em>__</em>) to your project_log4shell.json file.

NOTE: You do not need to use Java code, ldap, python server, etc to get this flag.

&nbsp;

&nbsp;

<h1>Flag 2: Get a Shell (15 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

The endpoint for this exploit can be called and inspected via:

curl ‘http://localhost:8080/rest/products/isAlive’ -H ‘GATECH_ID:123456789’ -H ‘Accept:application/json’

Now that we have proven this service is vulnerable and that we can exploit it in at least one place, let’s try to do more damage and do something more malicious. If you have not already, you NEED to read through the suggested readings and learn how/why it is possible to send jndi lookups.

Open the “Exploit.java” file and construct a malicious payload to execute such that when the jndi/ldap lookup happens, it gives you root access on the vulnerable application server.

You should have a total of 4 terminal windows open which are the 3 from the SETUP section and one terminal window to run your curl command.

Once you are ready to run the exploit, ensure that the java version you are running the command is “java version 1.8.0_20” by running:

To compile your .java file into a class file, move the the directory the .java file is stored in and run:

javac Exploit.java

<strong><em>NOTE: THIS PROJECT IS WRITTEN USING THE VULNERABLE VERSION OF 1.8.0_20. </em></strong>

<strong><em>NOT ALL VERSIONS OF JAVA ALLOW LOOKUPS AND YOU COULD SPIN YOUR WHEELS FOR AWHILE NOT KNOWING WHY YOUR EXPLOIT IS NOT RUNNING IF YOU DO NOT FOLLOW THIS DIRECTION.</em></strong>

We have added the ability to log from your Exploit.java file so that you can log useful debugging information while you are developing your exploit. <strong>To log messages from your Java class, tail the ~Desktop/log4shell/logs/console.log file and add System.out.println statements to your Exploit.java.</strong>

<table width="155">
<tbody>
<tr>
<td width="155"></td>
</tr>
<tr>
<td width="155">Desktop/log4shell/Flagx</td>
</tr>
</tbody>
</table>
Make sure you are running this command from

&nbsp;

&nbsp;

This should create Exploit.class. <strong>Run your “python3 -m http.server 4242” command in this directory.</strong>

<strong>Hint: Pay close attention to the ports you are using in this exercise.</strong>

If successful, you should see similar console output as the screenshot below:

&nbsp;

&nbsp;

With success, you should see this in the console output of the nc command. Now type “whoami” and you should see “root”.

&nbsp;

&nbsp;

Did you get the screenshot above? Congratulations!

If not, keep trying and ensure all of your hosts/ports match. Analyze the screenshots and make sure yours matches. If you are not getting the ldap/python server output, you likely did not set up your hosts/ports correctly OR your Exploit.java file isn’t correct.

You now have root access to the vulnerable application’s server. YIKES! This is a great example why this exploit is so dangerous. You can perform any task on this server now. For now, go back 2 directories using “cd ..” and then run “java -jar Flag2.jar” to get your

flag and add it to the json under “Flag2”.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1>FLAG 3: Config.Properties Surprise (25 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag we will use the /products/ resource. There are 4 total endpoints for this resource. Only the following 2 are relevant for this flag.

Call the following endpoint to fetch all the records. Save one of the ids. GET All – Fetch all product records:

curl ‘http://localhost:8080/rest/products/productlist’ -H ‘GATECH_ID:123456789’

Call the following endpoint to GET by ID and inspect the logged output.

GET By ID – Fetch a single product record by ID: curl ‘http://localhost:8080/rest/products/product/&lt;id&gt;’ -H ‘GATECH_ID:123456789’

You have caught wind that there is a properties file that this application uses to inject configurable data during runtime.

<table>
<tbody>
<tr>
<td width="96"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
For this exploit, you will use the log4j exploit to overwrite the “config.properties” file saved in the root directory of the application. This properties file contains a property that will set the customer service email for all of the products.

See if you can find anything that gives you a hint about how to exploit it/what you need to do, to update the property.

This application links the properties’ customer service email address to all products in its response. You have a good friend who has been bothering you so you want to spam his email inbox with customer complaints about these products. First, you need to make sure that this is even possible.

For this flag, you will need to overwrite the properties file so that when the application builds the product response, it sets the email address to your gatechId. *i.e. 123456789, not user@gatech.edu or 123456789@gatech.edu

If successful, you should get your flag in the email field of the response:

<strong>Hint: Someone might have tried to roll their own patch and tried to deny requests containing malicious string patterns.</strong>

<strong>*** **IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

&nbsp;

&nbsp;

&nbsp;

<h1>FLAG 4: Command and Concat (25 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag, we will exploit an endpoint that adds a new user:

curl -X PUT ‘http://localhost:8080/rest/users/user’ -H ‘GATECH_ID:903449128’ -H ‘Content-

Type:application/json’ –data-raw

‘{“id”:8,”userId”:”2134″,”userName”:”RSANCHEZ1″,”userRole”:”R&amp;D”,”adminYN”:”Y”}’

Take some time to inspect this output and see what you need to exploit. Yes the exception is expected, and maybe there is even a clue above it 😉

For this flag, you will construct a malicious file (Exploit.java) and compile it, so that when deserialized it will create a simple “.txt” file on the server to get the flag. Using the log4shell exploit, create a file named “Ronnie.txt” on the server and add ONE line that says “LightWeightBaby!” (You do not need the quote). If you do not follow this exactly, you will not get this flag.

Upon success, you will see the output below. (You might have to scroll for this)

&nbsp;

<strong>Hint: The name of this flag is a huge hint as to what you need to do. Pay close attention to the logged messages and their format.</strong> <strong>*** **IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

&nbsp;

&nbsp;

<h1>FLAG 5: PubSub Override (25 pts)</h1>
Make sure you have gone through the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/setup.html">Setup</a> and <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Log4Shell/introflag.html">Intro</a> sections.

If you haven’t already, run the start script in the home directory of log4j user, start the container with the start script:

./StartContainer.sh

For this flag, we will exploit a previous endpoint that publishes updates to a topic on the server:

curl -X PUT ‘http://localhost:8080/rest/users/user’ -H ‘GATECH_ID:903449128’ -H ‘Content-

Type:application/json’ –data-raw

‘{“id”:8,”userId”:”2134″,”userName”:”RSANCHEZ1″,”userRole”:”R&amp;D”,”adminYN”:”Y”}’

You remember that properties file? Good! We are going to play with it yet again.

For this exploit, you will use the log4j exploit to overwrite the “config.properties” file saved in the root directory of the application. This properties file contains a topic that the application will publish a message to when updateUser call is made (the application is also subscribed to this topic as you can see in the logs).

You will need to trick the application into publishing a message to a different topic with your GATECH_ID as the account number in order to generate a valid flag.

Upon success, you should see your output similar to that below:

&nbsp;

<strong>Hint: Look through the cs6035.log to find clues about what this other topic could be.</strong> <strong><em>Your flag could be invalid if you have not sent your GATECH_ID appropriately in the published message.</em></strong> <strong>*** **IF THIS FLAG COMES OUT BLANK, Restart container by running the stopContainer and startContainer scripts in the home directory of the log4j user.</strong> <strong>**</strong>***

File submission instructions:

This project needs to be submitted via Gradescope. Navigate to the course in Canvas, click ‘Gradescope’, click ‘Project Log4Shell’ and submit there.

This is an autograded project. You will have unlimited submissions with instant feedback. Your Gradescope grade will be your final grade. Be aware that your most recent submission is activated by default and will be used for your grade unless you activate another submission before the deadline.

The contents of the submission file should be the following. There is

<table width="281">
<tbody>
<tr>
<td width="281">~/Desktop/log4shell/project_log4shell.json</td>
</tr>
</tbody>
</table>
a&nbsp; file in your vm with a template set up, or you

<table width="149">
<tbody>
<tr>
<td width="149">project_log4shell.json</td>
</tr>
</tbody>
</table>
can copy-paste this to your newly created&nbsp; file elsewhere and replace the placeholders with the flags you retrieve from each relevant task.

<em>Note: You can use Featherpad or Vim to create and edit this file. Do not use LibreOffice or any Word Document editor. It must be in proper JSON format with no special characters in order to pass the autograder and these Word Document editors are likely to introduce special characters.</em>

&nbsp;

&nbsp;

&nbsp;
