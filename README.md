## Welcome to MailScanner!

 ## Version
 Current version: 5.0.4-4 release

## Email:
 Jerry Benton - 10 November 2016
 <mailto:mailscanner@mailborder.com>

## About MailScanner
MailScanner is an open source email gateway that processes email for
spam, viruses, phishing, and other malicious content. MailScanner 
leverages other open source software such as ClamAV and 
Spamassassin. MailScanner will run on any NIX platform and includes
install packages for popular distributions such as Redhat, Debian, and
SUSE in addition to any generic NIX package.


Info: 		http://www.mailscanner.info
Release: 	https://www.mailscanner.info/downloads
Github: 	https://github.com/MailScanner/v5
Manual: 	https://s3.amazonaws.com/msv5/docs/ms-admin-guide.pdf
Support: 	http://lists.mailscanner.info/mailman/listinfo/mailscanner

## Installation:
<pre>		tar -xvzf MailScanner-5.x.x-x.distro.tar.gz
		cd MailScanner-5.x.x-x
		./install.sh </pre>

## MTA Guides:
		[sendmail](https://www.mailscanner.info/sendmail)
		[postfix](https://www.mailscanner.info/postfix)
		[exim](https://www.mailscanner.info/exim)

## Setup:
 	 Edit /etc/MailScanner/defaults and set options
	 Edit /etc/MailScanner/MailScanner.conf and set options
	 service mailscanner start

## NIX:
		For generic NIX systems, create a symlink for controlling the 
		start/stop/restart of the program to:

		/usr/lib/MailScanner/init/ms-init

		* This is not required for RHEL, CentOS, Debian, Ubuntu, SUSE	

## File Locations:
	/etc/MailScanner
  	/usr/share/MailScanner
 	 /usr/lib/MailScanner






