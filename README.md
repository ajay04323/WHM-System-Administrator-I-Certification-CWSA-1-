In which WHM interface can you configure the forwarders for the root, cpanel, and nobody mail accounts?
WHM Home » Server Contacts » Edit System Mail Preferences
José sends an email message to Maria. If the system cannot deliver the message, José will get a notification from which of the following sources?
The mailer daemon.
Given the following options, which describe an actual reason that the system may place a message into the Exim queue?
There are DNS issues preventing Exim from finding the remote mail server.
Which of the following options accurately describes the behavior of an open relay server?

An open relay server does not require you to authenticate. -
If there is a long delay indicated when an email is being sent, the Mailer Daemon will send a warning message to which of the following destinations?
The email's sender.
Which of the following options best indicate a legitimate reason that would describe why you would want to configure the forwarder address fields within the WHM Home » Server Contacts » Edit System Mail Preferences interface?
To prevent emails destined for "root" from getting frozen within the mail queue.
Which of the following options accurately describes the behavior of an open relay server?
An open relay server does not require you to authenticate. -
Justine's boss just told her that the authentication daemon for the mail server is broken.  Which of the following options best indicates the component of the mail system that is affected by this?
The component that validates user credentials.
Which of the following actions can you perform in the WHM Home » Email » Mail Queue Manager interface?
Delete a particular message permanently so that is not delivered.
Given the following options, which describe an actual reason that the system may place a message into the Exim queue?
The load average on the server is above the delivery threshold.
Which of the following options describe an actual value that can be adjusted within the WHM Home » Service Configuration » Mailserver Configuration interface?
Controlling the maximum and spare quantities of authentication daemon processes.

Which of the following methods best indicate the recommended approach for backing up, restoring or resetting the system's Exim configuration?
Use the corresponding functions found within the Exim Configuration Manager interface, in WHM.
Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as the option that allows you to edit the list of IP addresses that the system excludes ONLY from SMTP sender verification checks?
 
Sender verification bypass IP addresses
You can use the Exim Configuration Manager - Basic Editor to configure Exim to deliver mail without scanning messages based on which of the following criteria?
When the message is over a certain size.
Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as enabling the checking of DNS resolution to see if the sender's domain exists?
Sender Verification
Which of the following options best describes the type of SpamAssassin options that appear in the Exim Configuration Manager - Basic Editor interface, found in WHM?  
Options that affect if and how Exim passes messages to SpamAssassin.
Which of the following items from the WHM Home » Service Configuration » Exim Configuration Manager - Basic Editor interface would allow you to exclude mail sent from specific remote IP addresses or hostnames from being subjected to recipient verification checks, sender checks, spam checks, and relay checks?
Trusted SMTP IP Addresses
Within which of the following WHM interfaces can you enable additional ports for Exim to listen for SMTP connections on?

WHM Home » Service Configuration » Service Manager
Which of the following options best describes the term email reputation?
It is a calculation of the likelihood of a message being spam based on other messages sent from the same server. -
Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as enabling the contacting of the sender's mail server to see if the sender exists?
Sender Verification Callouts

Which of the following tools may help you to resolve issues indicated by the time moved backwards warning?

The "ntp" tool.
Which of the following Mail interfaces in WHM can provide you with a historical snapshot of the mail queue?

Mail Delivery Reports
Given the following options, which accurately describes the behavior of the Mail Troubleshooter interface, found in WHM?
It does not send an actual test message, but simulates sending one.
Given the following options, which best describes something about an email address that can be determined by using the WHM Home » Email » Mail Troubleshooter interface, found in WHM?
It will indicate whether the destination address forwards mail to a remote server.

If you suspect that mail has not been delivered because the user is over their quota, in which of the following WHM interfaces might you look to confirm why the message was not delivered?
WHM Home » Email » Mail Delivery Reports
Which of the following options best indicate the typical delivery failure rate that a spamming email account will report, if examining from the Mail Delivery Reports interface found in WHM?
The account will have a high failure rate.
Given the following options, which of these accurately describe the behavior of the Mail Troubleshooter interface, found in WHM?
It can report the remote or local server that Exim uses to hand off messages for a specific email address.

If the mail server defers a message, what did it actually do to the message?
Delayed it.
Rejected it.
Classified it as spam.
All mail from a specific user is neither delivered to the inbox nor bounced. When you check the WHM Home » Email » Mail Delivery Reports interface, you see a funnel-shaped icon next to the message.
Which of the following options best describes what this probably indicates?
The message was likely rejected at SMTP-time due to spam-like characteristics.
The message was likely caught in a user-level filter and deleted.
The message was likely delivered successfully, but to the user's "Spam" folder.
All mail from a specific user is neither delivered to the inbox nor bounced.
When you check the WHM Home » Email » Mail Delivery Reports interface, you see a green checkmark icon next to the message. Which of the following options best describes what this indicates? 
That the message was rejected at SMTP time due to spam-like characteristics.
That the message was delivered successfully to a folder other than the inbox.
That the message has been caught in a routing loop.
Which of the following options indicates what the abbreviation TTL stands for, in the context of DNS?
Time To Live; indicating how long a resource record should be cached.
Given the selection of nameserver software options available in a cPanel & WHM interface, which of the choices below have a major weakness that can be described as having a considerably extended initial zone loading time, if the server contains a very large quantity of zones?
BIND/named
Which of the following options best describes the term recursive, in the context of DNS?
A recursive nameserver can resolve non-local domains.
Which of the following options accurately indicate a task that can be performed from within the WHM interface?
Change an MX record.
Which of the following options best describes the behavior that occurs when a zone contains no MX records?
You cannot send mail from the domain.
The zone is considered invalid.
The A record is used to determine where mail should be sent.
Which of the following statements best describes the term resolver?
A nameserver that can resolve non-local domains.
A root nameserver.
A nameserver that can only resolve local domains.
Of the following nameserver software options available in a cPanel & WHM environment, which is described as having the following major strengths?
Very high performance.
Low memory footprint.
PowerDNS
Which of the following statements most accurately describes the term clustering, in the context of a server hosting environment?
Two or more servers that all serve the same purpose configured in a distributed, connected environment.
Which of the following most accurately describes what happens when a domain with two NS records in its zone is queried?
Both records are returned.
Which of the following options indicates what the abbreviation TTL stands for, in the context of DNS?
Time To Live; indicating how long a resource record should be cached.
Which of the following most accurately describes what happens when a zone contains two CNAME records with the same name?
The zone is considered invalid.
Which of the following options best describes the term recursive, in the context of DNS?
A recursive nameserver can resolve non-local domains.
Which of the following options best describes the behavior that occurs when a zone contains no MX records?
The A record is used to determine where mail should be sent.
Which of the following statements best describes the term resolver?
A nameserver that can resolve non-local domains.
Which of the following described situations would utilize DNS resolution as a key component of its handling?
To determine where to send mail for a domain.
SPF and DKIM are resource records that help reduce which of the following?
Spoofing and unauthorized senders.
When you use the supported 1:1 NAT setup in WHM, the List Accounts interface in WHM will display which of the following values in each accounts' listed IP address column?
The public IP address.
Which of the following statements accurately describe a situation in which DNS zone templates would be useful, in a cPanel & WHM environment?
Any time that similar customizations are needed across all hosted accounts.
Which of the following types of DNS cluster synchronization found in WHM can be best described as the copying of one updated zone file to the current server, based on the value you provide as the domain you wish to synchronize?

Synchronize one zone to this server only.
Which of the following types of authentication is used to establish DNS clustering, in a cPanel & WHM environment?
API Tokens
cPanel offers a DNSOnly installation specifically for the purpose of using with a standard cPanel & WHM environment in a DNS cluster configuration. Which of the following is the standard license cost associated with DNSOnly?

Free.
After performing an installation of cPanel & WHM on a fresh environment, what is the initial, default state of DNS clustering?
DNS clustering is initially disabled, and must be manually enabled.
Which of the following best describes one of the primary, intended purposes of a DNSOnly server?

Providing a means of establishing DNS redundancy in a cluster configuration.
Which of the following DNS clustering synchronization types, found in the WHM interface, can be best described as the copying of all updated versions of local zone files to all servers in the cluster?
Synchronize all zones to all servers.
Which of the following types of DNS cluster synchronization found in the WHM interface can be accurately described as the copying of all updated versions of local zone files from other servers in the cluster to this server?

Synchronize all zones to this server only.
If you have one DNSONLY server and three full cPanel & WHM servers, which of the following is recommended as the optimal cluster configuration, given this scenario?
The cPanel & WHM servers should be set to push to the DNS Only server, which should not send updates back to the cPanel & WHM Servers.
Within which of the following WHM interfaces would you be able to add SPF and DKIM records to an account?

WHM Home >> Account Functions >> Modify Account
By default, cPanel creates SPF records in which of the following modes?
Testing mode (non-production)
Yudith runs a small web-hosting company. She has added and removed several zones manually but has accidentally deleted a zone belonging to a cPanel account. Fortunately, this zone did not contain any custom records.
Given the situation, which of the following WHM interfaces should she utilize to re-create the zone?
 

WHM » DNS Functions » Add a DNS Zone.
If, because of incorrect customization, you cannot edit a zone in the WHM editor, which of the following WHM interfaces can you use to re-apply the zone template and remove any customizations?
WHM » DNS Functions » Reset a DNS Zone.
Which of the following definitions best describes InnoDB's data dictionary component?
A part of the InnoDB storage engine that uses metadata to map structural information to the file it’s stored in.
By default, what kind of remote MySQL access is allowed, given the correct user and password?

No remote access is provided by default.
Which of the following database-related term can be defined as the marking of a table or row so that only one process can access it a time?
Locking
Which of the following MySQL/MariaDB-related terms can be accurately described as the language used to add, remove, and view data in a database?
SQL
Which of the following actions can you perform directly from within the WHM interface, without using phpMyAdmin?

Change a database user's password.
Which of the following MySQL/MariaDB-related terms can be accurately described as a data structure that improves the speed of operations in a table?

Index
In a cPanel & WHM environment, which of the following MySQL storage engines is set as the default?
MyISAM
Which of the following best describes the role of the MySQL root password in a cPanel & WHM environment?

A password that is primarily handled via automated means by cPanel & WHM back-end services, and can be reset as needed.
Given the following options, which accurately describe a feature specific to the MyISAM storage engine?

MyISAM has repair capabilities that allow you to perform the REPAIR query, either directly or from the WHM interface, on tables that may have corrupted data or indexes.
Which of the following MySQL storage engines is the native default (native to MySQL - not necessarily in cPanel & WHM) engine used by MySQL versions 5.5.5 and above?
InnoDB
Which of the following terms can be described as the way that permissions are handled inside a MySQL or MariaDB database?

Grants
Which of the following describes a term that indicates a trait of the object described by the table, or can be otherwise referenced as a table column?
Field
Which of the following actions can you perform directly from within the WHM interface, without using phpMyAdmin?

Change a database user's password.
The WHM Home >> SQL Services >> Manage Databases interface allows you to do which of the following operations?
Automated renaming of a MySQL/MariaDB database.
WHM contains an interface feature that allows you to attempt an automatic repair on which of the following types of tables? 
MyISAM
The WHM Home >> SQL Services >> Manage Database Users interface in WHM can be used for which of the following purposes?
Rename existing database users.
Which of the following details about the remote server would you need to know, if you wanted to set up a new remote MySQL profile in WHM?
Remote SSH port
Using the Manage MySQL Profiles interface in WHM, what is the recommended maximum number of cPanel & WHM servers should be connected to each configured remote MySQL server?
1
Which of the following WHM interfaces would you use to configure a cPanel & WHM server to utilize a remote MySQL® server environment to handle its database operations?
Manage MySQL® Profiles
As of cPanel & WHM 60, what is the minimum version of MySQL that can be running on a remote server, in order for it to be used in a Remote MySQL Profile?

5.5
When using a cPanel & WHM environment, remote MySQL capabilities should be set up via the MySQL Profiles interface in WHM at which of the following stages of a server's operations?
After installation, but before beginning to create production accounts on the server.
In modern versions of cPanel & WHM, what benefits can database prefixing, enabled from the SQL tab of the Tweak Settings interface in WHM, provide?

Primarily cosmetic; helps server administrators identify database ownership, as well as providing auto-grouping in the phpMyAdmin interface.
Which of the following options describes the best way to import a SQL dump into a PostgreSQL databases via the WHM interface?

There are no features in WHM that provide this capability; it must be performed from the command-line.
Which of the following is one of the most common causes of MySQL upgrade failures?
The my.cnf file contains a number of non-default customizations that have not been verified prior to upgrading.
Which of the following is one of the most common causes of MySQL upgrade failures?
Aborting the upgrade, intentionally or otherwise, part-way through the procedure.
Ananya has a website that writes data into a MySQL database. She was mail-bombed, and as a result, has gone over the quota that was set for her account by the WHM server administrator. Which of the following best describes what happens to her website now?
It continues operating normally, and no production impact is seen.
MySQL Profiles can be used to set up what kind of relationship between servers?
1-to-1 (1:1) only
Which of the following columns, found in the WHM Home >> SQL Services >> Show MySQL Processes interface, indicate the actual query being executed by the indicated process?

info
Given the following options, which of these indicate the correct amount of characters that a MySQL 4.1 password hash is composed of, before being updated to the current standard of 41 character-hashes?
16 characters.
Which of the following options accurately describes an action that can be performed from within WHM's EasyApache 4 interface?

Install new PHP extensions for use in your active Apache/PHP environment.
When operating in a cPanel & WHM environment running EasyApache 4, within which of the following WHM interfaces can you adjust the server's default PHP version?
This can be adjusted from within WHM's MultiPHP Manager interface.
Which of the following types of packages does EasyApache 4 rely on to install modules and extensions, when provisioning an EasyApache 4 profile?
RPM packages.
In modern installations of cPanel & WHM, EasyApache 4 will allow you to install which of the following versions of Apache?

Apache 2.4
In addition to increasing the speed of the build process, which of the following options describes another reason that EasyApache 4 provides an improvement over EasyApache 3?
Reduced chances of critical Apache failures.
Which of the following options accurately indicates the file syntax that can be seen within downloaded EasyApache 4 profiles?
JSON
Which of the following options best describes one of the most notable behaviors that separate the DSO handler from other PHP handlers available in a cPanel & WHM environment?
DSO does not create new "php" processes to handle requests, but instead works internally with Apache, spawning from the parent httpd process.
Which of the following EasyApache 4 profile actions can you perform from WHM's EasyApache 4 interface, in modern installations of cPanel & WHM?
Upload a profile file from your file system or via a URL.
Which of the following accurately indicates the user that processes created for the DSO handler are owned by?

nobody user
In a cPanel & WHM environment operating with EasyApache 4, an EasyApache profile is defined as which of the following?
A collection of packages that can be provisioned.
You're operating in a PHP 5.6 environment and using DSO as your PHP handler. You've created a .user.ini file in your website's public_html folder, but are not seeing your changes reflected.
Of the following choices, which of these most accurately describes the issue that is occurring here?

An .htaccess file stored in public_html should be used instead, containing the appropriate syntax for declaring PHP values.
Which type of user can select the version of PHP that can be used within a particular cPanel account, using the cPanel & WHM interfaces?

Both the cPanel account user and the WHM root user.
Which of the following options describes an action that can be performed from within WHM's MultiPHP Manager interface?
You can turn on PHP-FPM, per-virtual host, from this interface.
When operating in a cPanel & WHM environment running EasyApache 4, within which of the following WHM interfaces can you adjust the server's default PHP version?
This can be adjusted from within WHM's MultiPHP Manager interface.
In a cPanel & WHM environment running EasyApache 4, which of the following RPMs would provide PHP 5.6 to the account?
ea-php56
Of the following options, which of these handlers operate in a non-persistent state, requiring the creation of new PHP processes each time something is executed?
suPHP
Which of the following statements accurately describes how processes are handled during PHP requests when DSO is in use as the PHP handler?
PHP handling operates internally by Apache's own processes.
In modern installations of cPanel & WHM, when selecting DSO from the EasyApache 4 interface without mod_ruid2 or mpm_itk, what recommendation will be displayed to you automatically, directly from within the EasyApache 4 interface?
PHP DSO runs as the nobody user by default. In a shared hosting environment, this is a security issue.
Which of the following options describes the appropriate method needed to enable PHP-FPM from within the WHM interface?

PHP-FPM is enabled via WHM's MultiPHP Manager interface.
When operating in a cPanel & WHM environment, which of the following files are used by the system to define the PHP configuration?

/etc/apache2/conf.d/php.conf
In modern installations of cPanel & WHM, which of the following PHP configuration values are set automatically during the Initial Setup Assistant steps?

memory_limit
In a cPanel & WHM environment, which of the following options accurately describe what the system default PHP version setting defined in WHM's MultiPHP Manager interface represents?
The version that is used if a domain does not already have a specific version selected for it.
Which of the following options best describes the procedure needed to enable the BlueHost SymLink Protection Patch?
Toggle the corresponding option found in WHM's Apache Configuration's Global Configuration interface.
Which of the following options is NOT a real Multi-Processing Module (MPM) available for installation within WHM's EasyApache 4 interface?
Postfork
Which of the following Apache modules are core to Apache and can be disabled, but cannot be removed using the EasyApache 4 interface?

mod_userdir
Which of the following options best describes the method you would use to install the PHP-FPM software, within a cPanel & WHM environment?
PHP-FPM appears under the PHP Extensions stage of the EasyApache 4 profile customization walkthrough.
Which of the following PHP handlers can only be used on one PHP version at a time?

DSO
If a user wants to utilize the system default version of PHP, which of the following selections would they enable for their account?
inherit
Given the following options, select the components or component combinations that would provide standard per-user process ownership for handling PHP content.
suPHP (mod_suphp) OR Ruid2 (mod_ruid2) OR PHP-FPM
What does cPHulk access to determine whether a login attempt is a brute force attack or not?
authd
BLT
cpsrvd
PAM
None of these
cPHulk allows you to set blocks to which of the following durations? (Select all that apply.)
One day
One week
What option does IP Address-based protection possess that Username-based protection does not?
Brute Force Protection Period
Command to Run (when brute force protection is triggered)
Which of the following options exist on the Configuration Settings tab within the WHM Home » Security Center » cPHulk Brute Force Protection interface in WHM?
Minimum Failures by IP Address
One-week Blocks
Notifications
Flush Blacklists
None of these
When a WHM login fails because cPHulk has blocked access, what do you see?
"The login is invalid" in a red banner above the login box
You are taken to a page with a cpatcha and the notification that cPHulk requires proof that you are a real person

What option does IP Address-based protection possess that Username-based protection does not?
Command to Run (when brute force protection is triggered)
Which type of attack does cPHulk help to protect against?
Keylogging
Brute Force
Shark
True/False: You can enable/disable cPHulk during the Initial Setup Wizard after a fresh cPanel & WHM installation.

True
cPHulk allows you to set blocks to which of the following durations? (Select all that apply.)

One day
An arbitrary number of minutes
True/False: cPHulk is disabled by default on new installations.

False
Which of the following can you try if you have been locked out? (Select all that apply.)
Log in from a different location and whitelist your primary IP
Wait for 15 minutes before trying again with the correct password
Log in via SSH using a public key
Log in via SSH using the correct password
Which of the following are real types of certificates? (Select all that apply)
Domain Validated
Extended Validation
When you cannot decrypt using the same key you encrypted with, but instead with its unique counterpart, it's referred to as what type of encryption?
Asymmetric
Which of the following does a self-signed certificate put you at risk of?
Man-in-the-middle attack

In computing terms, the "root" of something is:
the start of something
When using an Organization Validated Certificate, which of the following statements accurately describes how the browser will indicate this in its address bar? 

Only a padlock indicating a valid SSL certificate.

Encryption is
Disguising data using mathematical functions
Which of the following demonstrates trust in SSL?
a chain of signed certificates leading back to an authoritative source
In computing terms, a service is:
software that runs in the background and provides specific functionality
The first time you install a newly signed certificate purchased from a third party, you should install it by
copy/pasting the certificate from the vendor to the certificate box on WHM Home » SSL/TLS » Install an SSL Certificate on a Domain.
True/False: A larger key is more secure, but takes more resources to process each new SSL request.
True
Which of the following indicates the maximum number of APNs that should be used per-server, in a cPanel & WHM environment?
1
True/False: You should always use a shared secret when creating a certificate, key, and CSR.
False
When SNI is in use, which items are used to determine which virtual host to return? (Select all that apply)
requested hostname
the IP address the client connected to
Of the following options, which accurately indicates the maximum length of the commonName field, found in SSL certificates?

64 bytes
Which of the following services are NOT usable with WHM's Service SNI feature?

mysql
Within which of the following cPanel & WHM user interfaces can you manage Domain TLS?
None of these.
Domain TLS Manager
SSL Storage Manager
The Tweak Setting "Always Redirect to SSL" redirects which method of logging in?
/cpanel, /webmail, /whm URLs
Which services can use SNI?
Exim
Dovecot
In a cPanel & WHM environment, which of the following indicates the frequency that AutoSSL polls for pending certificates?
Every 5 minutes the first day, every hour the second day, and once a day after that.
You can add or remove SNI from the mail services on which page?

WHM Home » SSL/TLS » Manage SSL Hosts
Which actions can be performed from the Manage Service SSL Certificates page? (Select all that apply)
install a new certificate on any of the SSL-capable services
install a self-signed certificate for the server's hostname on any of the SSL-capable services
view the issuer, key size, and expiration data for the certificate installed on any of the SSL-capable services
Which services are SSL-capable? (Select all that apply)

FTP
webmail
WebDisk
True/False: The Tweak Setting "Require SSL" will redirect proxy subdomain entries to their secure counterparts.
True
True/False: Because they require your private key to check the SSL certificate on your website, you should avoid using third party SSL checking tools.

False
Why might a site look different when viewed with HTTPS rather than with HTTP?

the site does not have its own SSL certificate, so Apache displays a different site on that IP address that does have a certificate.
Which of the following causes a hostname mismatch warning? (Select all that apply)
visiting www.domain.com for a site whose certificate is for domain.com

The most common cause of the self-signed warning is
a missing or incomplete CA bundle
True/False: By default, AutoSSL will not change or impact any certificates that were manually installed outside of AutoSSL.
True

The default provider, cPanel (Powered by Comodo), can secure how a maximum of how many domains per-certificate (or per-VirtualHost)?

200
True/False: By default, AutoSSL will not change or impact any certificates that were manually installed outside of AutoSSL.
True
When using WHM links that direct you to the cPanel Store for purchases (such as for SSL certificates or KernelCare), issues with the store or cart system that are handled server-side are often logged to which of the following log files?
/usr/local/cpanel/logs/error_log
With AutoSSL enabled, what type of certificate are your websites automatically secured with?

Domain-Validated (DV)
True/False: Setting a user to "Enable AutoSSL" does not override feature list settings applied for that user account.
False

When do SSL-capable services have self-signed certificates automatically installed? (Select all that apply)
during the initial installation of cPanel & WHM
the night before the certificate expires
Which of the following can cause an expired certificate warning?

the wrong date on the client computer
Which of the following are parts of a certificate? (Select all that apply)
CRT
key
CA Bundle
True/False: We recommend that you always have the generated certificate, key, and CSR emailed to you to serve as a backup.
False
Which of the following does a web client check when receiving a certificate from a webserver? (Select all that apply)
the expiration date is after the current date
the connected hostname is covered by the certificate
the certificate was issued by an authority that the browser trusts
When SNI is in use, which items are used to determine which virtual host to return? (Select all that apply)
requested hostname
the IP address the client connected to
When a certificate issued by AutoSSL is going to imminently expire, which of the following does AutoSSL do?
Automatically replaces them with an updated certificate, when AutoSSL runs its certificate checks.
Which of the following causes an insecure content on a secure page warning?
visiting a site with some images loaded with http instead of https
In modern installations of cPanel & WHM, you are able to purchase Extended Validation Certificates through which of the following cPanel Interfaces?

WHM's Purchase and Install an SSL Certificate interface.
The first time you install a newly signed certificate purchased from a third party, you should install it by
copy/pasting the certificate from the vendor to the certificate box on WHM Home » SSL/TLS » Install an SSL Certificate on a Domain.
True/False: The Logging phase of an HTTP transaction still allows ModSecurity to perform connection filtering/blocking changes instructed by rules.
False
What needs to be appended to a URL in order to retrieve the Public Contact information JSON data?
cgi-sys/contact_details.cgi
TRUE/FALSE: When a Company Logo image is provided, it will be displayed along with the text defined in the Company Name field, within the top bar of the cPanel account interface.

False
TRUE/FALSE: Only the Company Name value defined in the Public Contact tab of the Customization interface will be accessible to the public - not the Company Name value defined in the Customize Branding tab.
True
What is the interface path where you can find the Customization section within WHM?
Home >> cPanel >> Customization
Do you remember what file format is used for custom styles, when uploading or downloading them from the Customize Style tab of the Customizationinterface?
gzipped tar
When the Help Link field is defined, roughly where in the cPanel account interface does a "Help" link appear?
In the footer.
TRUE/FALSE: When you define value in the Company Name field of the Customization interface, it will display the value as header text in the top bar of the cPanel account interface.
True
Which of the following Exim log entries would indicate that mail was deleted due to a filter?

1YO6bD-000871-1j => /dev/null <test@cptest.test> R=virtual_user_filter T=**bypassed**
Which of the following can be discerned from the Exim log entry shown below?
1YOv2S-0005IY-7r == test@cptest.test R=virtual_user T=virtual_userdelivery


The message was deferred.
Given two cPanel servers exchanging email, which of the following would appear in both messages' headers, but would not appear in the Exim logs on either the sending or the receiving server?

Subject
Exim ID --
Delivery Date
Message ID


Which of the following describes what is indicated by the use of the localuser router during a message's delivery, as seen in the Exim logs?


The message was delivered to a default (cPanel) account.

In an Exim log entry, the cwd value indicates which of the following?


The user executing the command.

Which of the following can be discerned from the Exim log entry shown below?
1YO6bD-000871-1j => /dev/null R=virtual_user_filter T=**bypassed**

The message was deleted

The highlighted part of the message below indicates which of the following values? 
2015-02-18 09:25:42 1Y06VR-0000Iw-7C= test@cptest.test H=localhost ([10.5.2.154]) [::1]:38793 P=esmtpa A=dovecot_login:test@cptest.test S=724 id=afc7s4294172a42cd5ce527636d7b74c.squrrel@10.6.2.152 T="test discard filter" for filters@cptest.test

The Exim ID

A particular type of email filter is stored in the /etc/vfilters/ directory. Which of the following types of filters are these?

Account-level email filters.

Which of the following describes what is indicated by the use of the virtual_user router during a message's delivery, as seen in the exim logs?

The message was delivered to an email account created in the cPanel interface.
Which of the following Actions in a cPanel email filter will result in an incoming message being rejected without sending any notifications?


Discard Message
Which of the following best describes the role of the exim -bt command?

Prints the path that the message will take when Exim attempts delivery to a specified address.
Which of the following commands will remove all messages sent by the spammer@example.tld user within the last 30 minutes?

exiqgrep -f spammer@example.tld -y 1800 -i | xargs exim -Mrm
What is the role of the -f flag when used with the exiqgrep utility?

Select messages by sender address.
Which of the following best describes the role of the exim -Mrm command?


Deletes the message based on a given the Exim ID.

When using Maildir, the "cur" folder contains which of the following items?

Mail that HAS been read.
Mail that has NOT been read. --
Drafts of unsent messages.
Messages that were flagged as spam.

The line in the Exim log that contains the SpamAssassin warning indicates which of the following?

The cPanel account that the message was scanned by.
The email account that the message was headed to.
The individual score positives and negatives caused by each spam test that was run during the scan. --
Given the following options, which one would be descriptive of behavior most likely to indicate that a spam problem is occurring?

A large number of failed messages reported. --
None of these options indicate a spam issue.
A sudden spike arriving in the mail queue due to a scheduled mailing list task.
A steady stream of mail originating from a script located within a directory on the file system that contains an active discussion forum.

Of the following mailbox formats, which of these are supported for use in cPanel & WHM environments?
MailDir
mdbox
What is the role of the -y flag when used with the exiqgrep utility?
Messages older than the number of seconds given.
Which of the following can be discerned from the Exim log entry shown below?
1YO6VR-00081w-7C => test <test@cpanel.net> R=virtual_user T=virtual_userdelivery
The message was delivered. --
The message was deleted.
The message was rejected.

Which of the following describes the primary role of the exim -Mvb command?
Prints the message body when given the Exim ID.

On cPanel & WHM environments, inbound mail is stored within a subfolder structure that exists in which of the following directories?


/home/$USER/mail/
Which of the following exim commands would provide you with the same functionality found within WHM's Mail Troubleshooter interface?


exim -bt
Which of the following best describes the role of the exim -bpc command?


Prints the number of messages in the mail queue.


Which of the following nameserver applications does not load all of its DNS zones upon startup?
MyDNS
Which of the following are utilities that you can use to try and repair a MySQL database while MySQL is running?


The "mysqlcheck" command.


To ensure that the internet sees the changes that you make DNS zone file manually, which of the following components of a DNS zoneshould you update?


The serial number.
Which of the following situations can cause very extended start-up and load times, when running the BIND/named nameserver software?
Using a very large quantity of zone files.
When a remote mail exchanger handles a domain's mail, which of the following files must include the domain?

/etc/remotedomains

On a cPanel & WHM environment, the system stores the private/public keys for DKIM in which of the following paths?


/var/cpanel/domain_keys
In a cPanel & WHM environment, you will find zone files stored in /var/named when using which of the following namesever software?


All of these.

Which of the following command-line tools can be used to list running processes in a Linux environment?


ps
Which of the following is the default path for the BIND/named configuration file?


/etc/named.conf
Which section of the named.conf file controls BIND/named's listening port?


options
Which of the following commands can you use to set up SPF from the command-line, in a cPanel & WHM environment?

/usr/local/cpanel/bin/spf_installer
In which of the following configuration files would you enable debug logging for BIND/named?


/etc/named.conf
In a cPanel & WHM environment, DNS zone files can be found in which of the following folders?

/var/named

On a cPanel & WHM environment, the system stores DNS zone template files within which of the following paths?

/var/cpanel/zonetemplates
To force the local system to resolve a domain to a specific IP address, which of the following files would you modify to accomplish this?

/etc/hosts

In a cPanel & WHM server, which of the following would allow you to select another DNS server application from the command line?


setupnameserver
To perform a reload on a cPanel & WHM server running the NSD software, which of the following commands would you run?


rndc reload
Which of the following DNS-related command-line utilities would provide you with similar results to those given by the dig utility, and is used for essentially the same purposes?


nslookup
Which of the following file names follows the naming convention for a BIND/named zone file?


domain.net.db
If named fails to start due to a configuration error, which of the following commands would be the most helpful for you to run?

named-checkconf
A default cPanel & WHM environment configures a custom logging channel, default_log, to log to which of the following paths?


/var/log/named/named.log


In a cPanel & WHM environment, DNS zone templates can be used to ensure which of the following?


To standardize a set of zone records and structure that will be used for a large number of DNS zones.
After you make a number of zone file changes in different zones, if you want to ensure that caching nameservers know to load the new information from your server, which of the following, single procedures can you perform to accomplish this?

Batch Zone Update
By default, which of these logging categories are routed into the default_log channel, in a BIND/named DNS server configuration?
general
If you create a customized DNS zone template from the command-line, which of the following would be a correctly-named custom template file name?
root_templatename

In a BIND/named configuration, you can modify the level of detail that is provided to remote servers regarding which of the following types of information?

Host application details indicating version and server data regarding your BIND/named installation.

Which of the following is one method that you can use, within the WHM interface, to repair a malformed DNS zone using a zone template?

Reset a DNS Zone
Which of the following utilities can be used to administer a BIND/named server remotely?


rndc
On a server that does not need to facilitate zone transfers, which of the following configuration variables found in the named.conf file should be set to none to disable them?


allow-transfer
By default in a cPanel & WHM environment, the system logs cluster-related messages into which of the following log files?
/usr/local/cpanel/logs/dnsadmin_log


What does the Error logging severity imply, when referring to BIND/named logs?
A problem has been encountered during BIND/named operations that may allow further operations to continue.


At which of the following stages of BIND/named DNS server operations might you encounter a zone or configuration syntax error?


During startup.
In a BIND/named configuration file, which of these logging categories encompasses all categories that have not already been explicitly configured to use another channel?


default


By default, which of the following sections appear first in the named.conf file?


key
What does the acronym ACL represent, in the context of a BIND/named configuration (among other contexts)?


Access Control List
What does the acronym TLD represent, as in for a "TLD nameserver"?

Top-level Domain
When you see a "rndc reload: connection refused" error, which of the following commands should you run first?

/scripts/fixrndc
What is the path of the DNS client configuration file?

/etc/resolv.conf
In a cPanel & WHM environment, in order to define a range or subnet of IP addresses for the system to re-use in the named.conf file, you should create which of the following kinds of configuration objects?


ACLs
Registrant information associated with domain names is maintained in an online database accessible with what service?


WHOIS
A banking website wants to prevent inappropriate certificate authorities from issuing certificates for their domain. Which of the following record types would best be used to assist in accomplishing this?
CAA
When operating within a cPanel & WHM server, which of the following indicates the best method to restart the DNS server from the command line?

/scripts/restartsrv_named
After a domain is updated at the registrar, where does the registrar then send that domain's record data?

To the TLD nameserver.
In a cPanel & WHM environment, within which of the following paths would you be able to find the Apache modules stored?


/etc/apache2/modules/
In a server running cPanel & WHM, which of the following options describes a method for changing the system's default PHP version via the command-line?


Use the /usr/local/cpanel/bin/rebuild_phpconf command.

Which of the following items can be described as any of the three things listed below?
A command line program for installing software.
A file format used to package software.
The individual packages created in that format.

RPM
In a cPanel & WHM environment, which of the following paths contain each installed version's PHP configuration files (php.ini), used by MultiPHP? ("##" representing the PHP version, in the options below)

/opt/cpanel/ea-php##
In a cPanel & WHM environment, which of the following utilities can you execute from the command-line to save the current set of Apache & PHP components defined in EasyApache into an EasyApache 4 profile? 

/usr/local/bin/ea_current_to_profile
In a cPanel & WHM environment, which of the following options describes a method you can use to change Apache's MPM from the command-line?

The "yum shell" command should be used to perform a batch transaction so that your web content does not produce errors.
If, from the command line of a server running cPanel & WHM, you run the rebuild_phpconf command with an appropriate action, then include the --errors option, which of the following will happen?


It outputs any errors in the rebuild process to the screen (sends to STDERR and log file).

Referencing the Apache error log entry shown below, which of the following options best describes the yellow-highlighted portion of the log entry (take note of the specifically-highlighted word)?
[Fri Sep 09 10:42:29.902022 2011] [core:error] [pid 35708:tid 4328636416] [client 72.15.99.187] File does not exist: /usr/local/apache2/htdocs/favicon.ico

The name of the Apache module that triggered the error.

Which of the following components can be described as a specific SAPI that provides functionality in a module that behaves as if it had been compiled into Apache itself, handling appropriate requests without producing new, non-Apache processes?

DSO

When operating within a cPanel & WHM environment, which of these commands would display all available EasyApache 4 packages from within the server's command line?


yum list "ea-*"
Which of the following options best describes the yellow-highlighted portion of the Apache access log entry shown below?
127.0.0.1 - frank [10/Oct/2000:13:55:36 -0700] "GET /apache_pb.gif HTTP/1.0" 200 2326


The IP address of the requestor.

Which of the following options could be described as a repository for PHP extensions?


pecl

Referencing the Apache error log entry shown below, which of the following options best describes the yellow-highlighted portion of the log entry?
[Fri Sep 09 10:42:29.902022 2011] [core:error] [pid 35708:tid 4328636416] [client 72.15.99.187] File does not exist: /usr/local/apache2/htdocs/favicon.ico
The inbound IP address of the node that requested the item that caused the error message.
In a cPanel & WHM environment, which of the following paths are used to store Apache's primary PHP configuration file ( php.conf) ?
/etc/apache2/conf.d/
If a file or directory in a path being served by Apache contains incorrect permissions or uses improper user/group ownership values, which of the following HTTP status codes might you see in the Apache logs if a client were to request one of the affected paths?
403
Which of the following terms can best be described as the destination where a process can write normal output to, usually being to the terminal, server console ("screen"), unless redirected?


STDOUT

Which of the following terms can be described as the destination where a process can write error messages, which can often either be to the "screen", or to a log file?

STDERR

Which of the following options describes the best way for you to enable the experimental repository for EasyApache 4, when operating within a cPanel & WHM environment?

Perform the following command from the command-line, as root or equivalent: yum install ea4-experimental
Which of the following options indicates the HTTP status code that produces the error shown below?
Unauthorized. A password is needed to see this page. The browser should prompt for a username and password.

401
In a server running cPanel & WHM, how can you create a new EasyApache 4 profile from within the server's command-line?

In the file system, make a copy of an existing profile's file, edit it with any desired changes, then save the new file.

When administering a server running cPanel & WHM, which of the following commands contains the appropriate paths and arguments needed to install an EasyApache 4 profile from the command-line?


/usr/local/bin/ea_install_profile --install /etc/cpanel/ea4/profiles/cpanel/default.json

Assume the host environment is a default cPanel & WHM installation. Based on the log entry shown below, identify - from the options available - which log file that this entry would be found in:
spam acl condition: error reading from spamd socket: Connection timed out

/var/log/maillog
/var/log/exim_paniclog --
/var/log/messages
Assume the host environment is a default cPanel & WHM installation. Based on the log entry shown below, identify from the options available which log file that this entry would be found in:
Warning: "SpamAssassin as cars detected message as spam (108.6)"
/var/log/messages
/var/log/maillog
/var/log/exim_mainlog


If the Scan outgoing messages for spam and reject based on defined Apache SpamAssassin™ score setting (formerly known as Apache SpamAssassin reject spam score threshold), within the Exim Configuration Manager - Basic Editor interface in WHM, contains a value, at what point during an email transaction is the message actually scanned to enforce this threshold?

Immediately before forwarders and filters are processed.
After forwarders and filters have been processed.
During the SMTP transaction with the message's origin server.
Given the following options, which of these indicate one of the paths within which you can find SpamAssassin rulesets stored?


~/.spamassassin/
Which of the following terms is used, particularly in spam-training applications, to describe the opposite of spam, meaning legitimate, solicited messages that are not considered spam?
Ham
SpamAssassin obtains its final probability score for a message through which of the following methods?
It adds together the score results from each triggered rule.

Assume the host environment is a default cPanel & WHM installation. Based on the log entry shown below, identify from the options available which log file that this entry would be found in:
spamd: identified spam (108.6/5.0) for cars:501 in 1.4 seconds, 407 bytes

The /usr/local/cpanel/logs/error_log file.
Which options must you pass to the sa-learn program if you want it to update the Bayesian database with information from a mailbox?
--spam/--ham

Which of the following options best defines a poisoned bayesian database?
It has been populated with an excessive amount of false positives.
Which of the following applications can be described as a program used during service checks to ensure that spamd is operational?
spamc

Which of the following applications can be described as a tool used to batch update Bayesian databases?

sa-learn
Which of the following values are provided in the output of the exim -bp command?

Exim ID

How many messages does SpamAssassin's Bayesian filter need to process before it can start scoring mail?

200 good samples, and 200 bad samples.
Which of the following exim commands would output the number of messages that currently exist in the Exim mail queue?


exim -bp
Of the following options, which would be the optimal way to resolve the issue that causes email notifications containing content similar that shown below?
dbindex cache file is out of date

Run /scripts/fix-dbindex.
Manually edit the file to correct the corrupted data.
Delete the file and allow it to be recreated automatically.
Restore the file from an available backup.
Which of the following describes one of the important steps discussed when describing how a full MySQL data directory can be manually restored from a cPanel-created backup?

Ensure ownership of the restored files is mysql:mysql, after being copied into the data directory.
In the context of MySQL databases, which of the following is best described as "plaintext" output containing a re-usable set of MySQL data?

MySQL dump
When should you make backups of your configuration files (or the my.cnf file in particular)?

Never. There’s no reason to make backups of configuration files because you can rebuild them.
Weekly.
Extremely often.
When changes are made to the configuration. --
The following text shows an example of which type of syntax, also visible in some mapping-related files stored by cPanel within the file system?
{"version":1,"MYSQL":{"noprefix":{},"owner":"animals","dbusers":{"cpses_anQnAmWDcX":{"server":"172.16.0.40","dbs":{}}},"server":"172.16.0.40","dbs":{"birds":"172.16.0.40","animals_fish":"172.16.0.40"}}}

JSON


In MySQL version 5.6, what happens if an entry in /etc/my.cnf is an unrecognized variable?


MySQL refuses to start and logs an error message.

In a cPanel & WHM environment, which of the following describes the purpose of the files that exist within the /var/cpanel/databases directory?


To store mapping information to help store data regarding association between cPanel accounts and databases.

Which of the following file extensions are associated specifically with MyISAM tables?

.MYD
Which of the following file extensions are associated specifically with InnoDB tables?

.ibd
Which of the following is the standard wildcard character used in SQL queries?


%
Which of the following is closest described as the structural metadata used to track objects like tables, indexes, and columns when using the InnoDB storage engine?

Data dictionary
In a cPanel & WHM environment, the /var/cpanel/databases directory contains which of the following?

The files created and used by cPanel for database mapping.

Error messages in your database error logs that indicate invalid, missing or unexpected system tables can frequently be the result of which of the following issues?

An incomplete (partial) upgrade.
You must stop the MySQL service in order to perform which of the following actions? 


Relocate or rename the data directory file in the MySQL data directory.

Within which of the following locations could you check if you wanted to confirm whether a cPanel & WHM server has "old (pre-4.1) passwords" enabled?


Tweak Settings interface in WHM.
In a cPanel & WHM environment, which of the following tools can best be described as the executable that creates grants_[cpuser].yaml files from existing MySQL grants, as found within the existing mysql.user database?


restoregrants
Which of the following describes one of the important steps involved in the process of relocating your MySQL data directory to a new partition?

Turn off MySQL and MySQL monitoring before performing filesystem changes.
The .frm and db.opt files will appear in database folders when using which of the following MySQL storage engines?


Any storage engine.
Which of the following statements about InnoDB tablespaces are true?


They can be stored individually within a database folder, or lumped together into the ibdata1 file.
Which of the following files should you check if you receive an unknown variable error message during MySQL operation or service start-up?

/etc/my.cnf
From the command line in a cPanel & WHM environment, how could you determine whether a server is utilizing a remote MySQL server?

Check the process list. If mysqld is not listed, the server is set up for remote mysql.
Check /root/.my.cnf for a “host” line.
Check the MySQL RPMs to see if mysql-client is installed instead of mysql-server.
Which of the following statements is not a legitimate SQL statement?


UPDATE
INSERT
COPY --

Which of the following SQL queries would be the most effective in identifying MySQL users that still have pre-4.1 passwords in use?

SELECT DISTINCT user FROM user WHERE length(password) < 41;


Which of the following SQL statements can be used to provide descriptive information about databases, tables, columns, variables, or status information about the server?

SHOW
When looking at the following excerpt from the beginning of a SHOW GRANTS result, what does the term USAGE ON indicate on the *.* value that follows?
GRANT USAGE ON *.*

That no privileges are given.

Which of the following WHM interfaces updates the files in the /var/cpanel/databases directory?

Database Map Tool

When looking at the following excerpt from the beginning of a SHOW GRANTS result, what do the wildcard asterisks represent in the *.*shown below?
GRANT USAGE ON *.*

[database].[table]
Which of the following statements about ~/.my.cnf files can be considered to be true?

.my.cnf files can be used by any user.

In a cPanel & WHM environment, which of the following tools is best described as the command-line equivalent of WHM’s Database Map Tool interface? 


dbmaptool
How should you enable the slow query log on a cPanel & WHM server?

Add "slow_query_log=1" to the mysqld section of the /etc/my.cnf configuration file.

Which of the following MySQL/MariaDB-related variables can be controlled via an option found within WHM's Tweak Setting interface?
open_files_limit
If the MySQL processes are stopped using the kill -9 command, what can you expect to happen?
An increased security risk of compromised authentication.
The severed writes on the databases will increase risk of database corruption.
A DROP is automatically triggered by MySQL on the last table that was being written to at the time, to prevent damage to the system.
Which of the following pieces of information can you find in both the slow query log and the general query log?
The user who executed the query.

Which of the following variables in a cPanel & WHM server’s /etc/my.cnf file are set by default?

default-storage-engine=MyISAM
How can you prevent cPanel & WHM from performing automated updates on the MySQL® or MariaDB server software?

By using the update_local_rpm_version script.
If the backup directory is /backup, where would you find the compressed backup file of the full MySQL data directory?


/backup/[date]/system/dirs/_var_lib_mysql.tar.gz




Which of the following MySQL logs are not recommended to leave enabled on a production server?
General query log: /var/lib/mysql/hostname.log
In a cPanel & WHM environment, which of the following tools can be best described as the executable that reads the grants_cpuser.yaml file, then adds the corresponding grants to MySQL.

restoregrants
Which of the following describes one of the important steps that should be taken after restoring a single database from a full cPanel backup, into a new database instance?


Associate the database and the database user with the cPanel user using the Database Map Tool.
By default, on a cPanel & WHM environment, you can find the MySQL logs in which of the following locations?

/var/lib/mysql
The following text is an example of which type of syntax, also found in some mapping-related files stored by cPanel in the file system?
MYSQL: 
  animals: 
    animals: 
      - GRANT USAGE ON *.* TO 'animals'@'localhost' IDENTIFIED BY PASSWORD '*75FE48658430441870C524D7ECB8F71EADFAEFD1'
      - GRANT ALL PRIVILEGES ON `birds`.* TO 'animals'@'localhost'
      - GRANT ALL PRIVILEGES ON `animals\_fish`.* TO 'animals'@'localhost'
PGSQL: {}

YAML
XML
JSON
After you update a zone's serial number (or any other record), which of the following commands can you execute to ensure that your local nameserver has been updated to use the new zone data?

rndc reload
Which of the following utilities included with BIND/named can be used to troubleshoot malformed zone files?

named-checkzone

When looking at the following excerpt from the beginning of a SHOW GRANTS result, what do the wildcard asterisks represent in the *.* shown below?
GRANT USAGE ON *.*

[database].[table]
Which of the following terms can best be described as an input stream where data is sent to and read by a program?
STDIN
Which of the following command-line utilities can best be described as a tool that allows you to concurrently install multiple versions of the same component (software collections) onto your system, and is often used with EasyApache 4/MultiPHP operations?
scl
Which of the following options indicates the HTTP status code that produces an error like the one shown below?
Forbidden. Access was denied to at least one relevant file.

403
When an EasyApache 4 profile is uploaded through the WHM interface, where within the file system is it stored?


/etc/cpanel/ea4/profiles/custom

Of the following, which of these options describe information that can be obtained by using the yum info command?

The plugins currently being loaded by the yum application.
Which of the following terms can be described as a special part of a process that shares resources with others in the same process, and can execute commands?

Thread
Which of the following options indicates the HTTP status code that results in the status message shown below?
OK. The request was successful.

200
Which of the following terms can be described as a special text string syntax used for describing a search pattern?


Regular Expression
Which of the following yum commands will install the EasyApache 4 mod_speling RPM?


yum install ea-apache24-mod_speling

How does the scl command know which version of PHP it should use?


You provide the PHP version as a command-line argument.

In a cPanel & WHM environment, if you select PHP 5.6 as the default PHP version, then from which of the following paths will the php.ini file be loaded?

/opt/cpanel/ea-php56/root/etc/php.ini
Which of the following best describes the difference between a process and a thread?
