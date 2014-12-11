# Exchange Server Performance Counters Plugin

## Overview

![images_community/download/attachments/73400866/icon.png](images_community/download/attachments/73400866/icon.png)

These plugins **extend the out-of-the-box Windows Performance Monitor Plugin** allowing you to **monitor key counters for your Exchange Server** that may have the Client Access, Hub Service, Mailbox,
Unified Messaging, or Edge Transport roles installed.

## Plugin Details

| Name | Exchange Server Performance Counters Plugin
| :--- | :---
| Author | Derek Abing
| License | [dynaTrace BSD](dynaTraceBSD.txt)
| Support | [Not Supported ](https://community.compuwareapm.com/community/display/DL/Support+Levels#SupportLevels-Community) If you have any questions or suggestions for these plugins, please add a comment to this page, use our [forum](https://community.dynatrace.com/community/pages/viewpage.action?pageId=46628918), or drop us an email at [community@dynatrace.com](mailto:community@dynatrace.com)!
| Release History | 2012-02-27 Initial Release
| Downloads | [Exchange Client 3.5.2.3](com.dynatrace.diagnostics.plugin.PerfMonExchangeClient_3.5.2.3.jar) 
| | [Exchange Hub 3.5.2.1](com.dynatrace.diagnostics.plugin.PerfMonExchangeHub_3.5.2.1.jar)
| | [Exchange Mailbox 3.5.2.2](com.dynatrace.diagnostics.plugin.PerfMonExchangeMailbox_3.5.2.2.jar) 
| | [Exchange Unified Messaging 3.5.2.4](com.dynatrace.diagnostics.plugin.PerfMonExchangeUnifiedMessaging_3.5.2.4.jar) 
| | [Exchange Edge Transport Role 3.5.2.5](com.dynatrace.diagnostics.plugin.PerfMonExchangeEdge_3.5.2.5.jar) 



  * [Exchange Server Client Access Performance Monitor](#exchange-server-client-access-performance-monitor)

  * [Exchange Server Hub Performance Monitor](#exchange_server_hub_performance_monitor)

  * [Exchange Server Mailbox Performance Monitor](#exchange_server_mailbox_performance_monitor)

  * [Exchange Unified Messaging Performance Monitor](#exchange_unified_messaging_performance_monitor)

  * [Exchange Edge Transport Role Performance Monitor](#exchange_edge_transport_role_performance_monitor)

## Exchange Server Client Access Performance Monitor

### Provided Measures

Measure Name

Description

Application Restarts

Shows the number of times the application has been restarted during the Web server's lifetime.

Availability Requests (sec)

Shows the number of requests serviced per second. The request can be only for free/busy or include suggestions. One request may contain multiple mailboxes.

Average Request Time

Shows the average time that elapsed while waiting for a request to complete.

Average Response Time

Shows the average time (in milliseconds) that elapsed between the beginning and end of an OEH or ASPX request.

Average Search Time

Shows the average time that elapsed while waiting for a search to complete.

Average Time to Process a Free Busy Request

Shows the average time to process a free/busy request in seconds. One request may contain multiple mailboxes. Free/busy responses do not have meeting suggestions.

Current Unique Users

Shows the number of unique users currently logged on to Outlook Web Access. This value monitors the number of unique active user sessions, so that users are only removed from this counter after they
log off or their session times out.

Download Task Queued

Shows a value of 1 if the task is queued for execution, otherwise shows 0.

Download Tasks Completed

Shows the number of OAB download tasks completed since the File Distribution service started. The default value is every 480 minutes or 8 hours.

Ping Commands Pending

Shows the number of ping commands that are currently pending in the queue.

Request Wait Time

Shows the number of milliseconds the most recent request was waiting in the queue.

Requests Current

Shows the current number of requests, including those that are queued, currently executing, or waiting to be written to the client. Under the ASP.NET process model, when this counter exceeds the
requestQueueLimit defined in the processModel configuration section, ASP.NET will begin rejecting requests.

Requests In Application Queue

Shows the number of requests in the application request queue.

Requests/sec

Shows the number of HTTP requests that are received from the client via ASP.NET per second.

Sync Commands/sec

Shows the number of Sync commands that are processed per second. Clients use this command to synchronize items within a folder.

Worker Process RestartsMyMetric3

Shows the number of times a worker process has restarted on the computer.

## Exchange Server Hub Performance Monitor

### Provided Measures

Measure Name

Description

Average Agent Processing Time (sec)

Shows the average agent processing time in seconds per event.

Dumpster Size

Shows the total size (in bytes) of mail items that are currently in the transport dumpster on this server.

Dumpster Item Count

Shows the total number of mail items that are currently in the transport dumpster on this server.

Dumpster Inserts/sec

Shows the rate at which items are inserted into the transport dumpster on this server.

Dumpster Deletes/sec

Shows the rate at which items are deleted from the transport dumpster on this server.

Unreachable Queue Length

Shows the number of messages in the Unreachable queue.

Largest Delivery Queue Length

Shows the number of messages in the largest delivery queues.

Poison Queue Length

Shows the number of messages in the poison message queue.

Aggregate Delivery Queue Length (All Queues)

Shows the number of messages queued for delivery in all queues.

Active Remote Delivery Queue Length

Shows the number of messages in the active remote delivery queues.

Active Mailbox Delivery Queue Length

Shows the number of messages in the active mailbox queues.

Submission Queue Length

Shows the number of messages in the submission queue.

Active Non-Smtp Delivery Queue Length

Shows the number of messages in the Drop directory that is used by a Foreign connector.

Retry Mailbox Delivery Queue Length

Shows the number of messages in a retry state attempting to deliver a message to a remote mailbox.

Retry Non-Smtp Delivery Queue Length

Shows the number of messages in a retry state in the non-Simple Mail Transfer Protocol (SMTP) gateway delivery queues.

Retry Remote Delivery Queue Length

Shows the number of messages in a retry state in the remote delivery queues.

Messages Submitted Per Second

Shows the number of messages that have been queued in the Submission queue per second.

Messages Queued for Delivery Per Second

Shows the number of messages that have been queued for delivery per second.

Messages Completed Delivery Per Second

Shows the number of messages that are delivered per second.

Inbound: LocalDeliveryCallsPerSecond

Shows the number of local delivery attempts per second.

Outbound: Submitted Mail Items Per Second

Shows the number of mail items per second being submitted.

Inbound: MessageDeliveryAttemptsPerSecond

Shows the number of attempts for delivering transport mail items per second.

Inbound: Recipients Delivered Per Second

Shows the number of inbound recipients delivered per second.

Average bytes/message

Shows the average number of message bytes per inbound message received.

Messages Received/sec

Shows the number of messages received by the SMTP server each second.

Messages Sent/sec

Shows the number of messages sent by the SMTP send connector each second.

I/O Log Writes/sec

Shows the rate of log file write operations completed.

I/O Log Reads/sec

Shows the rate of log file read operations completed.

Log Generation Checkpoint Depth

Represents the amount of work, in count of log files, that need to be redone or undone to the database files if the process fails.

Version buckets allocated

Total number of version buckets allocated.

I/O Database Reads/sec

Shows the rate of database read operations completed.

I/O Database Writes/sec

Shows the rate of database write operations completed.

Log Record Stalls/sec

Shows the number of log records that cannot be added to the log buffers per second because they are full. If this counter is non-zero most of the time, the log buffer size may be a bottleneck.

Log Threads Waiting

Shows the number of threads waiting for their data to be written to the log to complete an update of the database. If this number is too high, the log may be a bottleneck.

## Exchange Server Mailbox Performance Monitor

### Provided Measures

Measure Name

Description

RPC Requests

Indicates the overall RPC requests that are currently executing within the information store process.

RPC Averaged Latency

Indicates the RPC latency, in milliseconds, averaged for all operations in the last 1,024 packets.

RPC Operations/sec

Indicates the current number of RPC operations that are occurring per second.

RPC Num. of Slow Packets

Shows the number of RPC packets in the past 1,024 packets that have latencies longer than 2 seconds.

RPC Average Latency

Shows a server RPC latency, in milliseconds, averaged for the past 1,024 packets for a particular client protocol.

JET Pages Read/sec

Shows the rate that database pages are read from disk while processing requests for the client.

Directory Access: LDAP Reads/sec

Shows the current rate that the Lightweight Directory Access Protocol (LDAP) reads occur while processing requests for the client.

Directory Access: LDAP Searches/sec

Shows the current rate that the LDAP searches occur while processing requests for the client.

JET Log Records/sec

Shows the rate that database log records are generated while processing requests for the client.

Messages Queued for Submission

Shows the current number of submitted messages that are not yet processed by the transport layer.

Average Calendar Attendant Processing time

Shows the average time to process an event in the Calendar Attendant.

Requests Failed

Shows the total number of failures that occurred while the Calendar Attendant was processing events.

RPC Latency average (msec)

Shows the average latency, in milliseconds, of RPC requests. The average is calculated over all RPCs since exrpc32 was loaded.

RPC Requests outstanding

Shows the current number of outstanding RPC requests.

ROP Requests outstanding

Shows the total number of outstanding remote operations (ROP) requests.

RPC Requests Outstanding

Shows the total number of outstanding RPC requests.

RPC Requests failed (%)

Shows the percentage of failed requests in the total number of RPC requests. Here, failed means the sum of failed with error code plus failed with exception.

RPC Requests Sent/sec

Shows the current rate of initiated RPC requests per second.

RPC Slow Requests (%)

Shows the percentage of slow RPC requests among all RPC requests.

RPC Slow Requests latency average (msec)

Shows the average latency, in milliseconds, of slow requests.

Hub Servers In Retry

Shows the number of Hub Transport servers in retry mode.

Successful Submissions Per Second

Determines current mail submission rate.

Temporary Submission Failures/sec

Shows the number of temporary submission failures per second.

Average ResourceBooking Processing Time

Shows the average time to process an event in the Resource Booking Attendant.

Slow Findrow Rate

Shows the rate at which the slower FindRow needs to be used in the mailbox store.

Search Task Rate

Shows the number of search tasks created per second.

Slow QP Threads

Shows the number of query processor threads currently running queries that are not optimized.

Slow Search Threads

Shows the number of search threads currently running queries that are not optimized.

Categorization Count

Shows the categorization count in the number of categorizations that exist in the mailbox store. Categorizations are created when a user creates a filtered view or performs a search. When the
information store must maintain an excessive number of categorizations, performance can be affected.

Full Crawl Mode Status

Indicates whether this .mdb file is going through a full crawl (value=1) or not (value=0). Used to determine if a full crawl is occurring for any specified database.

Average Document Indexing Time

Shows the average, in milliseconds, of how long it takes to index documents.

Throttling Delay Value

Shows the total time, in milliseconds, a worker thread sleeps before it retrieves a document from the Microsoft Exchange Information Store service. This is set by the throttling monitor thread.

Recent Average Latency of RPCs Used to Obtain Content

Shows the average latency, in milliseconds, of the most recent RPCs to the Microsoft Exchange Information Store service. These RPCs are used to get content for the filter daemon for the specified
database.

Mailboxes Processed/sec

Shows the rate of mailboxes processed by time-based assistants per second.

Events Polled/sec

Shows the number of events polled per second.

Events in queue

Shows the number of events in the in-memory queue waiting to be processed by the assistants.

## Exchange Unified Messaging Performance Monitor

### Provided Measures

Measure Name

Description

Call Answer Queued Messages

Shows the number of messages created and not yet submitted for delivery.

Direct Access Failures

Shows the number of times that attempts to access Active Directory failed.

Hub Transport Access Failures

Shows the number of times that attempts to access a Hub Transport server failed. This number is only incremented if all Hub Transport servers were unavailable.

Unhandled Exceptions/sec

Shows the number of calls that were disconnected after an internal system error occurred in the last second.

Queued OCS User Event Notifications

Represents the number of missed call notifications that have been generated in the Office Communications Server environment and have not been submitted for delivery.

Operations over Six Seconds

Shows the number of all Unified Messaging operations that took more than six seconds to complete. This is the time during which a caller was waiting for Unified Messaging to respond.

Mailbox Server Access Failures

Shows the number of times the system did not access a Mailbox server.

Calls Disconnected by Callers During UM Audio Hourglass

Shows the number of calls during which the caller disconnected while Unified Messaging was playing the audio hourglass tones.

## Exchange Edge Transport Role Performance Monitor

### Provided Measures

Measure Name

Description

Recipients Rejected by Recipient Validation/sec

Show the number of recipients rejected by recipient validation per second.

Recipients Rejected by Block List/sec

Show the number of recipients rejected by block list per second.

Messages Filtered by Sender Filter/sec

Show the number of messages filtered by the Sender Filter agent per second.

DNS queries/sec

Shows the number of DNS queries per second performed by the Sender Id agent.

Messages Attachment Filtered

Shows the number of messages that were blocked, stripped of attachments, or silently deleted (as per configuration) by the attachment filtering agent.

Messages Filtered/sec

Shows the number of messages per second that the attachment filtering agent blocked, stripped of attachments, or silently deleted. If this rate rises greatly beyond what is "normal" for the Exchange
server, it may indicate that the organization is being flooded with malicious e-mail.

Messages Deleted

Shows the total number of messages that were deleted by Content Filter Agent.

Messages Quarantined

Shows the total number of messages that were quarantined by Content Filter Agent.

Messages Rejected

Shows the total number of messages that were rejected by Content Filter Agent.

Messages that Bypassed Scanning

Shows the total number of messages that bypass scanning.

Messages Scanned Per Second

Shows the number of messages scanned per second.

Messages with SCL 0

Shows the total number of messages assigned to SCL 0 level.

Messages with SCL 1

Shows the total number of messages assigned to SCL 1 level.

Messages with SCL 2

Shows the total number of messages assigned to SCL 2 level.

Messages with SCL 3

Shows the total number of messages assigned to SCL 3 level.

Messages with SCL 4

Shows the total number of messages assigned to SCL 4 level.

Messages with SCL 5

Shows the total number of messages assigned to SCL 5 level.

Messages with SCL 6

Shows the total number of messages assigned to SCL 6 level.

Messages with SCL 7

Shows the total number of messages assigned to SCL 7 level.

Messages with SCL 8

Shows the total number of messages assigned to SCL 8 level.

Messages with SCL 9

Shows the total number of messages assigned to SCL 9 level.

Block Senders

Shows the total number of blocked senders.

Edge objects added/sec

Shows the rate of Edge objects added per second by EdgeSync.

Edge objects deleted/sec

Shows the rate of Edge objects deleted per second by EdgeSync.

Edge objects updated/sec

Shows the rate of Edge objects updated per second by EdgeSync.

Scan jobs completed successfully total

Shows the total number of scan jobs completed successfully by EdgeSync.

Scan jobs failed because could not extend lock total

Shows the total number of EdgeSync scan jobs that failed because EdgeSync could not extend its lease of an Edge Transport server.

Scan jobs failed because of directory error total

Shows the total number of EdgeSync directory errors.

Scan jobs failed because could not lock total

My metric description ...

Source objects scanned/sec

Shows the rate of Active Directory objects scanned per second by EdgeSync.

Target objects scanned/sec

Shows the rate of Edge objects scanned per second by EdgeSync.

LDAP Searches/sec

Shows the rate at which LDAP clients perfom search operations.

LDAP Writes/sec

Shows the rate at which LDAP clients perform write operations.

Messages Evaluated/sec

Shows the number of messages the rule has evaluated per second.

Message Processed/sec

Shows the number of messages the rule has processed per second.

LDAP Searches/Sec

Shows the number of Lightweight Directory Access Protocol (LDAP) search requests issued per second.

LDAP Read Time

Shows the time in milliseconds (ms) to send an LDAP read request to the specified domain controller and receive a response.

LDAP Search Time

Shows the time (in ms) to send an LDAP search request and receive a response.

LDAP Searches timed out per minute

Shows the number of LDAP searches that have returned LDAP_Timeout during the last minute.

Long running LDAP operations/Min

Shows the number of LDAP operations on this domain controller that took longer than the specified threshold per minute.

LDAP Read Time

Shows the time (in ms) to send an LDAP read request to the specified domain controller and receive a response.

LDAP Search Time

Shows the time (in ms) to send an LDAP search request and receive a response.

## Configuration

As these measures are access via the Windows Performance Monitor, please refer to the documentation for [best practices on
authentication](https://community.dynatrace.com/community/display/DOCDT41/How+To+Retrieve+Performance+Metrics+with+Windows+Performance+Monitor).

## Installation

Import the Plugin into the dynaTrace Server. For details how to do this please refer to the [dynaTrace
documentation](https://community.dynatrace.com/community/display/DOCDT41/Manage+and+Develop+Plugins#ManageandDevelopPlugins-ManageandDevelopPlugins).

