quota-4.x-srpm
==============

This is straight from the upstream SRPM for quota on CentOS 8

Unfortunately, Red Hat elected not to publish the "devel" poackages
for select packages except in a distinct subscription only
channel. CentOS emulates this channel with the "Devel" channel, but
this channel does not exist for CentOS 8 Stream, so it has to be
compiled locally because Red Hat doesn't want to support the "devel"
component that they built along with the othet components of quota and
which they rely on, internally, to build tools like Samba.

Suffice to say that this is extra work on their part, and ours, work
that serves no good purpose.

Nico Kadel-Garcia <nkadel@gmail.com>
