# docker-ubuntu-iozone

Dockerized IOzone app built on top of official Ubuntu images.

## Image tags

- threadx/iozone:14.04 (trusty)

## Installed packages

Base:

- [trusty (14.04) minimal](http://packages.ubuntu.com/trusty/ubuntu-minimal)

Image specific:

- [iozone](http://www.iozone.org)

## Run example

```bash
$ sudo docker run -it threadx/iozone

root@fe0b7b4a178b:/#  iozone -R -l 5 -u 5 -r 64k -s 100m -F f1 f2 f3 f4 f5
```

License:

  Copyright 1991, 1992, 1994, 1998, 1999, 2002   William D. Norcott

  License to freely use and distribute this software is hereby granted
  by the author, subject to the condition that this copyright notice
  remains intact.  The author retains the exclusive right to publish
  derivative works based on this work, including, but not limited to,
  revised versions of this work.

  THIS SOFTWARE IS PROVIDED BY DON CAPPS AND THE IOZONE CREW "AS IS"
  AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
  TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
  PARTICULAR PURPOSE ARE DISCLAIMED.                                 

  IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY
  DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
  DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE
  GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
  INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER
  IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE.
