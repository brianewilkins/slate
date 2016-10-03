# ![alt tag](images/guide_icon.png) DBaaS Security

## Cloudant DBaaS Data Protection & Security

Protecting application data for large-scale web and mobile apps can be complex; especially with distributed and NoSQL databases.

Just as it removes the overhead of keeping your database running and growing non-stop, the Cloudant DBaaS also ensures your data stays secure and protected.

## Customer-Proven

Customers have been using the Cloudant DBaaS in production environments since 2009. Today Cloudant is used as the back-end data layer for hundreds of mission-critical applications in financial services, government, e-commerce, telecommunications, healthcare, and other security-minded industries.

## Innovative, Distributed Database Protection

Can you imagine backing up a live, 100-node database cluster that spans multiple data centers? Or how about setting access permissions for specific fields in a NoSQL JSON database? Cloudant automates tough big-data security challenges like these, and continues to lead the way in NoSQL and DBaaS security innovation.

## Top-Tier Physical Platforms

The Cloudant DBaaS is physically hosted on Tier-1 cloud infrastructure providers such as IBM (SoftLayer) and Amazon. Therefore your data is protected by the physical and network security measures employed by our hosting partners, including (but not limited to):

-	Certifications: Compliance with SSAE16, SOC1, ISAE 3402, ISO 27001, CSA, and other standards
-	Identity and access management
-	24/7 physical security of data centers and network operations center monitoring
-	Server hardening
-	Full-system virus scanning and systems patching
-	Cloudant gives you the flexibility to choose or switch among the different providers as your SLA and cost requirements change.

## Secure Access Control

There are a multitude of security features built into Cloudant that allow you to control access to data:

-	**Authentication** – Cloudant is accessed via a RESTful API; the user is authenticated for every HTTPS or HTTP request Cloudant receives.
-	**Authorization** – Grant read, write, admin permissions to specific databases.
-	**"In-flight"** Encryption – all access to Cloudant is encrypted via HTTPS. Enterprise customers can use custom SSL certifications.
-	**At-rest Encryption** – data stored on disk in Cloudant can be encrypted
-	**API Access** – Cloudant is accessed programmatically via a RESTful API over secure HTTP (HTTPS). API keys can be generated via the Cloudant dashboard.
-	**Access Logs** – All access to Cloudant is logged for auditing purposes
-	**IP Whitelisting** – Cloudant Enterprise customers can whitelist IP addresses to restrict access to only specified servers and users.
-	**CORS** – Enable CORS support for specific domains via the Cloudant Dashboard.
-	**[Shared Databases](https://cloudant.com/blog/shared-databases-faq/)** – Share databases with other Cloudant users in your organization and configure authorization privileges for each via the Cloudant Dashboard.

## Protection Against Data Loss or Corruption

Cloudant has a number of features to help you maintain data quality and availability:

-	**Redundant and durable data storage** – By default Cloudant saves to disk three copies of every document to three different physical nodes in a cluster. This ensures that a working failover copy of your data is always available, regardless of failures.
-	**Data Replication & Export** – You can continuously replicate your databases between clusters in different data centers, or to an on-premise Cloudant Local cluster or Apache CouchDB. Another option is to export data from Cloudant (in JSON or CSV format) to other locations or sources (such as your own data center) for added data redundancy.
-	**[Backup](backup-guide.html)** – Cloudant Enterprise users can request that their databases be incrementally backed up to a cluster of their choice to protect against data corruption or deletion. Backup will allow for database restores from a previous time, and document level compare and restore via the Dashboard.
