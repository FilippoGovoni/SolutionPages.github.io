---
layout: default
title: "Automation"
permalink: /automation
---

<h1>Ticket by mail</h1>
<p>
<code>Updated: 13/09/2016</code><br>
The feature is designed to enable all customers, covered by the service, send an e-mail to generate a ticket, instead of making a phone call or access a software to do it. Every master account in Fastservice has an e-mail assigned address for managing this feature.
</p>

<h2>Mapping e-mails into tickets</h2>
<p>
When an e-mail is sent to your support address is converted into a new ticket. The field mapping follow these rules:
<ul>
<li>From. If properly recognized by the system is saved in the Requester field.</li>
<li>Subject. Is saved in the Subject field of the ticket.</li>
<li>Body. Is saved in the ticket description field.</li>
</ul>
</p>
<h2>Enabling ticket by mail feature</h2>
<p>
By activating this function, Fastservice converts to tickets, all emails received at the address assigned. Note that, only registered e-mail addresses can create a valid ticket. E-mails received from unknown contacts, are classified as unmanaged and requests a personal check to be managed. To enable ticket by mail feature follow these steps:
<ol>
<li>Select Settings menu and then select ticket.</li>
<li>Select the checkbox Enable ticket by mail.</li>
<li>Select Save button.</li>
</ol>
</p>
<h2>Enable ticket by mail for Remote Monitoring Systems</h2>
<p>
Convert an alarm , signaled by a remote management software, into a ticket is very simple activity, It's need only to just record the signal sender in a Fastservice contact. To enable this feature, follow these steps:
<ol>
<li>In the setting menu, select account.</li>
<li>In the account list search the Remote Monitoring System account, then select it.</li>
<li>In the account form select the contact tab and the button Add new contact.</li>
<li>In the contact form create a new contact with the name of the Remote Monitoring Software.</li>
<li>Insert, in the e-mail field, the e-mail address of remote monitoring software that will send the e-mail alert.</li>
<li>Select save button.</li>
</ol>
</p>
<h2>Advanced settings for Remote Monitoring Systems</h2>
<p>
To provide additional information that allows a clear classification of the ticket, can be used more advanced settings. You can insert parameters in brackets in the e-mail subject, these are processed as ticket parameters and are inserted in the ticket. You can add more than one parameter, as well as a brief description.

The correct syntax to use parameters in e-mail subject is: square bracket, parameter, colon, value, square bracket. E.g. [ACCOUNT: Mario Rossi Spa].

Supported parameters are:
<ul>
<li>[ACCOUNT:] is written in the Customer field.</li>
<li>[SERVICE:] is written in the Service field.</li>
<li>[SERVICEDETAIL:] is written in the Service detail field.</li>
<li>[PRIORITY:] is written in the Priority field.</li>
<li>[DEVICEID] is written in the Asset name field.</li>
</ul>
</p>