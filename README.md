# About this repository

The [Service Name and Transport Protocol Port Number Registry](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml) is available as a 12-column table in CSV, XML, HTML and plain text.

The current repository provides a convenient 5-column Markdown table (around 1.5MiB): [Service Name and Transport Protocol Port Number Registry in Markdown format](service-names-port-numbers-formatted.md).

# Preview

Here's a preview (the complete file has more than 14,000 lines):

| Port Number | Transport Protocol | Service Name | Description | Notes |
| :---------- | :----------------- | :------------| :---------- | :---- |
| 0 | tcp | | Reserved | assignee: Jon Postel | contact: Jon Postel |
| 0 | udp | | Reserved | assignee: Jon Postel | contact: Jon Postel |
| 1 | tcp | tcpmux | TCP Port Service Multiplexer | assignee: Mark Lottor | contact: Mark Lottor |
| 1 | udp | tcpmux | TCP Port Service Multiplexer | assignee: Mark Lottor | contact: Mark Lottor |
| 2 | tcp | compressnet | Management Utility | |
| 2 | udp | compressnet | Management Utility | |
| 3 | tcp | compressnet | Compression Process | assignee: Bernie Volz | contact: Bernie Volz |
| 3 | udp | compressnet | Compression Process | assignee: Bernie Volz | contact: Bernie Volz |
| 4 | tcp | | Unassigned | |
| 4 | udp | | Unassigned | |
| 5 | tcp | rje | Remote Job Entry | assignee: Jon Postel | contact: Jon Postel |
| 5 | udp | rje | Remote Job Entry | assignee: Jon Postel | contact: Jon Postel |
| 6 | tcp | | Unassigned | |
| 6 | udp | | Unassigned | |
| 7 | tcp | echo | Echo | assignee: Jon Postel | contact: Jon Postel |
| 7 | udp | echo | Echo | assignee: Jon Postel | contact: Jon Postel |
| 8 | tcp | | Unassigned | |
| 8 | udp | | Unassigned | |
| 9 | tcp | discard | Discard | assignee: Jon Postel | contact: Jon Postel |
| 9 | udp | discard | Discard | assignee: Jon Postel | contact: Jon Postel |
| 9 | sctp | discard | Discard | assignee: Randall Stewart | contact: Randall Stewart | modification date: 2022-02-07 | reference: RFC9260 |
| 9 | dccp | discard | Discard | assignee: Eddie Kohler | contact: Eddie Kohler | reference: RFC4340 | service code: 1145656131 |
| 10 | tcp | | Unassigned | |
| 10 | udp | | Unassigned | |
| 11 | tcp | systat | Active Users | assignee: Jon Postel | contact: Jon Postel |
| 11 | udp | systat | Active Users | assignee: Jon Postel | contact: Jon Postel |
| 12 | tcp | | Unassigned | |
| 12 | udp | | Unassigned | |
| 13 | tcp | daytime | Daytime | assignee: Jon Postel | contact: Jon Postel | reference: RFC867 |
| 13 | udp | daytime | Daytime | assignee: Jon Postel | contact: Jon Postel | reference: RFC867 |
| 14 | tcp | | Unassigned | |
| 14 | udp | | Unassigned | |
| 15 | tcp | | Unassigned [was netstat] | |
| 15 | udp | | Unassigned | |
| 16 | tcp | | Unassigned | |
| 16 | udp | | Unassigned | |
| 17 | tcp | qotd | Quote of the Day | assignee: Jon Postel | contact: Jon Postel |
| 17 | udp | qotd | Quote of the Day | assignee: Jon Postel | contact: Jon Postel |
| 18 | tcp | msp | Message Send Protocol (historic) | assignee: Rina Nethaniel | contact: Rina Nethaniel |
| 18 | udp | msp | Message Send Protocol (historic) | assignee: Rina Nethaniel | contact: Rina Nethaniel |
| 19 | tcp | chargen | Character Generator | |
| 19 | udp | chargen | Character Generator | |
| 20 | tcp | ftp-data | File Transfer [Default Data] | assignee: Jon Postel | contact: Jon Postel |
| 20 | udp | ftp-data | File Transfer [Default Data] | assignee: Jon Postel | contact: Jon Postel |
| 20 | sctp | ftp-data | FTP | assignee: Randall Stewart | contact: Randall Stewart | modification date: 2022-02-07 | reference: RFC9260 |
| 21 | tcp | ftp | File Transfer Protocol [Control] | assignee: Jon Postel | contact: Jon Postel | reference: RFC959 | assignment notes: Defined TXT keys: u=<username> p=<password> path=<path> |
| 21 | udp | ftp | File Transfer Protocol [Control] | assignee: Jon Postel | contact: Jon Postel | reference: RFC959 | assignment notes: Defined TXT keys: u=<username> p=<password> path=<path> |
| 21 | sctp | ftp | FTP | assignee: Randall Stewart | contact: Randall Stewart | modification date: 2022-02-07 | reference: RFC9260 | assignment notes: Defined TXT keys: u=<username> p=<password> path=<path> |
| 22 | tcp | ssh | The Secure Shell (SSH) Protocol | reference: RFC4251 | assignment notes: Defined TXT keys: u=<username> p=<password> |
| 22 | udp | ssh | The Secure Shell (SSH) Protocol | reference: RFC4251 | assignment notes: Defined TXT keys: u=<username> p=<password> |
| 22 | sctp | ssh | SSH | assignee: Randall Stewart | contact: Randall Stewart | modification date: 2022-02-07 | reference: RFC9260 | assignment notes: Defined TXT keys: u=<username> p=<password> |

# License

The Internet Corporation for Assigned Names and Numbers (ICANN) and the Internet Engineering Task Force (IETF) Trust state in the [licensing terms](https://www.iana.org/help/licensing-terms) that the registry is subject to the [Creative Commons CC0 1.0 public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/legalcode). See the file [COPYING](COPYING).