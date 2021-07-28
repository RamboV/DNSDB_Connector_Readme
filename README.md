# Farsight DNSDB Connector

Increase Incident Response Speed and Accuracy with Farsight Security DNSDB®.

Farsight Security DNSDB® is the world’s largest DNS intelligence database that provides a unique, fact-based, multifaceted view of the configuration of the global Internet infrastructure. DNSDB leverages the richness of Farsight’s Security Information Exchange (SIE) data-sharing platform and is engineered and operated by leading DNS experts. Farsight collects Passive DNS data from its global sensor array. It then filters and verifies the DNS transactions before inserting them into the DNSDB, along with ICANN-sponsored zone file access download data.

## Pre-requisites
You will need the following to proceed:
* A Microsoft Power Apps or Power Automate plan with custom connector feature
* An Azure subscription
* Farsight DNSDB API Key

## Supported Operations
The connector supports the following operations:
* `RRSet Lookup`: The “rrset” lookup queries DNSDB’s RRset index, which supports “forward” lookups based on the owner name of an RRset.

* `RData Lookup`: The “rdata” lookup queries DNSDB’s Rdata index, which supports “inverse” lookups based on Rdata record values.

* `Flex Search`: Flexible Search adds both Regular Expressions and Globbing support to the DNSDB API to expand the types of search queries and add more control to searches.

* `Rate Limit`: Retrieve service limits

## Access Your API Key
Register for a free API key at https://www.farsightsecurity.com/solutions/dnsdb/ .

## Support and documentation: 
For all the support requests and general queries you can contact support@farsightsecurity.com or [contact us](https://www.farsightsecurity.com/about-farsight-security/contacts/)
