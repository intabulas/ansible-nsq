NSQ
========

Ansible role that installs Bitly's NSQ (http://bitly.github.io/nsq/). The latest stable release that has been compiled for x86 64-bit Linux systems is installed by default, and different platforms and versions are supported by modifying the role variables.

Role Variables
--------------

All of these variables are optional and should only be changed if you need to install a different version of NSQ or if you need to use an earlier release).

nsq_tarball: The tarball that you want to install. A list of options can be found on the [NSQ Installing Document](http://bitly.github.io/nsq/deployment/installing.html). The default is the official x86 64-bit Linux tarball for the latest stable release.

nsq_tarball_checksum: The SHA256 checksum for the tarball that you want to install. This can be calculated using `sha256sum` if necessary. The default is the SHA256 checksum of the official x86 64-bit tarball for the latest stable release.

nsq_download_location: The full download URL. This variable simply appends the go_tarball variable onto the Go Download URL. This should not need to be modified.

License
-------

The MIT License (MIT)

Copyright (c) 2013 Mark Lussier

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

You can find me on [Twitter](https://twitter.com/intabulas), and on [GitHub](https://github.com/intabulas/)
