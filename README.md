# Displaced-UDP-Max-MSP-Patch
This MaxMSP patch is an example of creating a dynamic Synth working remotely thanks to OSC and UDP sockets, empowering electronic musicians to interact remotely on Max (with the use of ZeroTier One)

The entire repo is a space in which I am going to store the steps of my research and tests in this subject

THIS README IS WIP

Requirements: 
* [Open Sound Control](https://cnmat.berkeley.edu/downloads) (AKA you need the CNMAT externals package from Max's Package Manager) 
* [ZeroTier One](https://www.zerotier.com/)

Keep in mind:
Zerotier helps computers connect over the internet avoinding port forwarding (does even more than that).
That aside, users should make sure firewalls on their devices are properly allowing incoming data from the chosen port or application. In this particular case this would mean to make sure to allow Max to have incoming connections or allow UDP port 12777.



_______________________________________________________________________________________________________________________________

Copyright (c) 2020 Enrico Pietrocola

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
