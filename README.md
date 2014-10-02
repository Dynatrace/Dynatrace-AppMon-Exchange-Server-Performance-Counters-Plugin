<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Exchange Server Performance Counters Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Exchange Server Performance Counters Plugin</h1>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/73400866/icon.png" alt="images_community/download/attachments/73400866/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
These plugins <strong class=" ">extend the out-of-the-box Windows Performance Monitor Plugin</strong> allowing you to <strong class=" ">monitor key counters for your Exchange Server</strong> that may have the Client Access, Hub Service, Mailbox, Unified Messaging, or Edge Transport roles installed.    </p>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_73334961_1_com.dynatrace.diagnostics.plugin.PerfMonExchangeClient_3.5.2.3.jar">Exchange Client 3.5.2.3</a> (compatible with dynaTrace 3.5.2+)<br/><a href="attachments_73334962_1_com.dynatrace.diagnostics.plugin.PerfMonExchangeHub_3.5.2.1.jar">Exchange Hub 3.5.2.1</a> (compatible with dynaTrace 3.5.2+)<br/><a href="attachments_73334963_1_com.dynatrace.diagnostics.plugin.PerfMonExchangeMailbox_3.5.2.2.jar">Exchange Mailbox 3.5.2.2</a> (compatible with dynaTrace 3.5.2+)<br/><a href="attachments_73335020_1_com.dynatrace.diagnostics.plugin.PerfMonExchangeUnifiedMessaging_3.5.2.4.jar">Exchange Unified Messaging 3.5.2.4</a> (compatible with dynaTrace 3.5.2+)<br/><a href="attachments_73335021_1_com.dynatrace.diagnostics.plugin.PerfMonExchangeEdge_3.5.2.5.jar">Exchange Edge Transport Role 3.5.2.5</a> (compatible with dynaTrace 3.5.2+)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Derek Abing    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a><br/>If you have any questions or suggestions for these plugins, please add a comment to this page, use our <a href="https://community.dynatrace.com/community/pages/viewpage.action?pageId=46628918">forum</a>, or drop us an email at <a href="mailto:community@dynatrace.com">community@dynatrace.com</a>!    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2012-02-27 Initial Release    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
<ul class="toc-indentation "><li class=" ">    <p>
<a href="Exchange_Server_Performance_Counters_Plugin.html#73400866_ExchangeServerPerformanceCountersPlugin-ExchangeServerClientAccessPerformanceMonitor">Exchange Server Client Access Performance Monitor</a>    </p>
</li><li class=" ">    <p>
<a href="Exchange_Server_Performance_Counters_Plugin.html#73400866_ExchangeServerPerformanceCountersPlugin-ExchangeServerHubPerformanceMonitor">Exchange Server Hub Performance Monitor</a>    </p>
</li><li class=" ">    <p>
<a href="Exchange_Server_Performance_Counters_Plugin.html#73400866_ExchangeServerPerformanceCountersPlugin-ExchangeServerMailboxPerformanceMonitor">Exchange Server Mailbox Performance Monitor</a>    </p>
</li><li class=" ">    <p>
<a href="Exchange_Server_Performance_Counters_Plugin.html#73400866_ExchangeServerPerformanceCountersPlugin-ExchangeUnifiedMessagingPerformanceMonitor">Exchange Unified Messaging Performance Monitor</a>    </p>
</li><li class=" ">    <p>
<a href="Exchange_Server_Performance_Counters_Plugin.html#73400866_ExchangeServerPerformanceCountersPlugin-ExchangeEdgeTransportRolePerformanceMonitor">Exchange Edge Transport Role Performance Monitor</a>    </p>
</li></ul>    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-ExchangeServerClientAccessPerformanceMonitor"  >
        <h2>Exchange Server Client Access Performance Monitor</h2>
    <div class="section-3"  id="73400866_ExchangeServerPerformanceCountersPlugin-ProvidedMeasures"  >
        <h3>Provided Measures</h3>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Application Restarts    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of times the application has been restarted during the Web server's lifetime.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Availability Requests (sec)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of requests serviced per second. The request can be only for free/busy or include suggestions. One request may contain multiple mailboxes.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Request Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average time that elapsed while waiting for a request to complete.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Response Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average time (in milliseconds) that elapsed between the beginning and end of an OEH or ASPX request.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Search Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average time that elapsed while waiting for a search to complete.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Time to Process a Free Busy Request    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average time to process a free/busy request in seconds. One request may contain multiple mailboxes. Free/busy responses do not have meeting suggestions.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Current Unique Users    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of unique users currently logged on to Outlook Web Access. This value monitors the number of unique active user sessions, so that users are only removed from this counter after they log off or their session times out.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download Task Queued    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows a value of 1 if the task is queued for execution, otherwise shows 0.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download Tasks Completed    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of OAB download tasks completed since the File Distribution service started. The default value is every 480 minutes or 8 hours.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Ping Commands Pending    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of ping commands that are currently pending in the queue.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Request Wait Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of milliseconds the most recent request was waiting in the queue.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Requests Current    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the current number of requests, including those that are queued, currently executing, or waiting to be written to the client. Under the ASP.NET process model, when this counter exceeds the requestQueueLimit defined in the processModel configuration section, ASP.NET will begin rejecting requests.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Requests In Application Queue    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of requests in the application request queue.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Requests/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of HTTP requests that are received from the client via ASP.NET per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Sync Commands/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of Sync commands that are processed per second. Clients use this command to synchronize items within a folder.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Worker Process RestartsMyMetric3    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of times a worker process has restarted on the computer.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-ExchangeServerHubPerformanceMonitor"  >
        <h2>Exchange Server Hub Performance Monitor</h2>
    <div class="section-3"  id="73400866_ExchangeServerPerformanceCountersPlugin-ProvidedMeasures.1"  >
        <h3>Provided Measures</h3>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Agent Processing Time (sec)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average agent processing time in seconds per event.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Dumpster Size    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total size (in bytes) of mail items that are currently in the transport dumpster on this server.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Dumpster Item Count    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of mail items that are currently in the transport dumpster on this server.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Dumpster Inserts/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate at which items are inserted into the transport dumpster on this server.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Dumpster Deletes/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate at which items are deleted from the transport dumpster on this server.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Unreachable Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the Unreachable queue.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Largest Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the largest delivery queues.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Poison Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the poison message queue.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Aggregate Delivery Queue Length (All Queues)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages queued for delivery in all queues.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Active Remote Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the active remote delivery queues.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Active Mailbox Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the active mailbox queues.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Submission Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the submission queue.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Active Non-Smtp Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in the Drop directory that is used by a Foreign connector.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Retry Mailbox Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in a retry state attempting to deliver a message to a remote mailbox.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Retry Non-Smtp Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in a retry state in the non-Simple Mail Transfer Protocol (SMTP) gateway delivery queues.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Retry Remote Delivery Queue Length    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages in a retry state in the remote delivery queues.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Submitted Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages that have been queued in the Submission queue per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Queued for Delivery Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages that have been queued for delivery per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Completed Delivery Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages that are delivered per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Inbound: LocalDeliveryCallsPerSecond    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of local delivery attempts per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Outbound: Submitted Mail Items Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of mail items per second being submitted.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Inbound: MessageDeliveryAttemptsPerSecond    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of attempts for delivering transport mail items per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Inbound: Recipients Delivered Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of inbound recipients delivered per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average bytes/message    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average number of message bytes per inbound message received.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Received/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages received by the SMTP server each second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Sent/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages sent by the SMTP send connector each second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
I/O Log Writes/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of log file write operations completed.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
I/O Log Reads/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of log file read operations completed.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Log Generation Checkpoint Depth    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Represents the amount of work, in count of log files, that need to be redone or undone to the database files if the process fails.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version buckets allocated    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Total number of version buckets allocated.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
I/O Database Reads/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of database read operations completed.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
I/O Database Writes/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of database write operations completed.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Log Record Stalls/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of log records that cannot be added to the log buffers per second because they are full. If this counter is non-zero most of the time, the log buffer size may be a bottleneck.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Log Threads Waiting    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of threads waiting for their data to be written to the log to complete an update of the database. If this number is too high, the log may be a bottleneck.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-ExchangeServerMailboxPerformanceMonitor"  >
        <h2>Exchange Server Mailbox Performance Monitor</h2>
    <div class="section-3"  id="73400866_ExchangeServerPerformanceCountersPlugin-ProvidedMeasures.2"  >
        <h3>Provided Measures</h3>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Requests    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Indicates the overall RPC requests that are currently executing within the information store process.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Averaged Latency    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Indicates the RPC latency, in milliseconds, averaged for all operations in the last 1,024 packets.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Operations/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Indicates the current number of RPC operations that are occurring per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Num. of Slow Packets    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of RPC packets in the past 1,024 packets that have latencies longer than 2 seconds.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Average Latency    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows a server RPC latency, in milliseconds, averaged for the past 1,024 packets for a particular client protocol.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
JET Pages Read/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate that database pages are read from disk while processing requests for the client.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Directory Access: LDAP Reads/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the current rate that the Lightweight Directory Access Protocol (LDAP) reads occur while processing requests for the client.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Directory Access: LDAP Searches/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the current rate that the LDAP searches occur while processing requests for the client.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
JET Log Records/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate that database log records are generated while processing requests for the client.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Queued for Submission    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the current number of submitted messages that are not yet processed by the transport layer.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Calendar Attendant Processing time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average time to process an event in the Calendar Attendant.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Requests Failed    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of failures that occurred while the Calendar Attendant was processing events.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Latency average (msec)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average latency, in milliseconds, of RPC requests. The average is calculated over all RPCs since exrpc32 was loaded.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Requests outstanding    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the current number of outstanding RPC requests.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
ROP Requests outstanding    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of outstanding remote operations (ROP) requests.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Requests Outstanding    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of outstanding RPC requests.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Requests failed (%)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the percentage of failed requests in the total number of RPC requests. Here, failed means the sum of failed with error code plus failed with exception.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Requests Sent/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the current rate of initiated RPC requests per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Slow Requests (%)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the percentage of slow RPC requests among all RPC requests.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
RPC Slow Requests latency average (msec)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average latency, in milliseconds, of slow requests.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Hub Servers In Retry    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of Hub Transport servers in retry mode.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Successful Submissions Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Determines current mail submission rate.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Temporary Submission Failures/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of temporary submission failures per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average ResourceBooking Processing Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average time to process an event in the Resource Booking Attendant.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Slow Findrow Rate    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate at which the slower FindRow needs to be used in the mailbox store.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Search Task Rate    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of search tasks created per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Slow QP Threads    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of query processor threads currently running queries that are not optimized.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Slow Search Threads    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of search threads currently running queries that are not optimized.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Categorization Count    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the categorization count in the number of categorizations that exist in the mailbox store. Categorizations are created when a user creates a filtered view or performs a search. When the information store must maintain an excessive number of categorizations, performance can be affected.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Full Crawl Mode Status    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Indicates whether this .mdb file is going through a full crawl (value=1) or not (value=0). Used to determine if a full crawl is occurring for any specified database.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Average Document Indexing Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average, in milliseconds, of how long it takes to index documents.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Throttling Delay Value    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total time, in milliseconds, a worker thread sleeps before it retrieves a document from the Microsoft Exchange Information Store service. This is set by the throttling monitor thread.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Recent Average Latency of RPCs Used to Obtain Content    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the average latency, in milliseconds, of the most recent RPCs to the Microsoft Exchange Information Store service. These RPCs are used to get content for the filter daemon for the specified database.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Mailboxes Processed/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of mailboxes processed by time-based assistants per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Events Polled/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of events polled per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Events in queue    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of events in the in-memory queue waiting to be processed by the assistants.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-ExchangeUnifiedMessagingPerformanceMonitor"  >
        <h2>Exchange Unified Messaging Performance Monitor</h2>
    <div class="section-3"  id="73400866_ExchangeServerPerformanceCountersPlugin-ProvidedMeasures.3"  >
        <h3>Provided Measures</h3>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Call Answer Queued Messages    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages created and not yet submitted for delivery.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Direct Access Failures    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of times that attempts to access Active Directory failed.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Hub Transport Access Failures    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of times that attempts to access a Hub Transport server failed. This number is only incremented if all Hub Transport servers were unavailable.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Unhandled Exceptions/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of calls that were disconnected after an internal system error occurred in the last second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Queued OCS User Event Notifications    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Represents the number of missed call notifications that have been generated in the Office Communications Server environment and have not been submitted for delivery.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Operations over Six Seconds    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of all Unified Messaging operations that took more than six seconds to complete. This is the time during which a caller was waiting for Unified Messaging to respond.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Mailbox Server Access Failures    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of times the system did not access a Mailbox server.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Calls Disconnected by Callers During UM Audio Hourglass    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of calls during which the caller disconnected while Unified Messaging was playing the audio hourglass tones.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-ExchangeEdgeTransportRolePerformanceMonitor"  >
        <h2>Exchange Edge Transport Role Performance Monitor</h2>
    <div class="section-3"  id="73400866_ExchangeServerPerformanceCountersPlugin-ProvidedMeasures.4"  >
        <h3>Provided Measures</h3>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Recipients Rejected by Recipient Validation/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Show the number of recipients rejected by recipient validation per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Recipients Rejected by Block List/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Show the number of recipients rejected by block list per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Filtered by Sender Filter/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Show the number of messages filtered by the Sender Filter agent per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
DNS queries/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of DNS queries per second performed by the Sender Id agent.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Attachment Filtered    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages that were blocked, stripped of attachments, or silently deleted (as per configuration) by the attachment filtering agent.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Filtered/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages per second that the attachment filtering agent blocked, stripped of attachments, or silently deleted. If this rate rises greatly beyond what is &ldquo;normal&rdquo; for the Exchange server, it may indicate that the organization is being flooded with malicious e-mail.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Deleted    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages that were deleted by Content Filter Agent.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Quarantined    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages that were quarantined by Content Filter Agent.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Rejected    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages that were rejected by Content Filter Agent.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages that Bypassed Scanning    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages that bypass scanning.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Scanned Per Second    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages scanned per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 0    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 0 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 1    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 1 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 2    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 2 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 3    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 3 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 4    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 4 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 5    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 5 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 6    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 6 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 7    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 7 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 8    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 8 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages with SCL 9    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of messages assigned to SCL 9 level.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Block Senders    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of blocked senders.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Edge objects added/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of Edge objects added per second by EdgeSync.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Edge objects deleted/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of Edge objects deleted per second by EdgeSync.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Edge objects updated/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of Edge objects updated per second by EdgeSync.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Scan jobs completed successfully total    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of scan jobs completed successfully by EdgeSync.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Scan jobs failed because could not extend lock total    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of EdgeSync scan jobs that failed because EdgeSync could not extend its lease of an Edge Transport server.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Scan jobs failed because of directory error total    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the total number of EdgeSync directory errors.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Scan jobs failed because could not lock total    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
My metric description ...    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Source objects scanned/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of Active Directory objects scanned per second by EdgeSync.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Target objects scanned/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate of Edge objects scanned per second by EdgeSync.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Searches/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate at which LDAP clients perfom search operations.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Writes/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the rate at which LDAP clients perform write operations.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Messages Evaluated/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages the rule has evaluated per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Message Processed/sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of messages the rule has processed per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Searches/Sec    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of Lightweight Directory Access Protocol (LDAP) search requests issued per second.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Read Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the time in milliseconds (ms) to send an LDAP read request to the specified domain controller and receive a response.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Search Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the time (in ms) to send an LDAP search request and receive a response.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Searches timed out per minute    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of LDAP searches that have returned LDAP_Timeout during the last minute.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Long running LDAP operations/Min    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the number of LDAP operations on this domain controller that took longer than the specified threshold per minute.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Read Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the time (in ms) to send an LDAP read request to the specified domain controller and receive a response.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
LDAP Search Time    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shows the time (in ms) to send an LDAP search request and receive a response.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-Configuration"  >
        <h2>Configuration</h2>
    <p>
As these measures are access via the Windows Performance Monitor, please refer to the documentation for <a href="https://community.dynatrace.com/community/display/DOCDT41/How+To+Retrieve+Performance+Metrics+with+Windows+Performance+Monitor">best practices on authentication</a>.    </p>
    </div>
    <div class="section-2"  id="73400866_ExchangeServerPerformanceCountersPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server. For details how to do this please refer to the <a href="https://community.dynatrace.com/community/display/DOCDT41/Manage+and+Develop+Plugins#ManageandDevelopPlugins-ManageandDevelopPlugins">dynaTrace  documentation</a>.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
