# alpine-ssh

A minimal Docker image based on Alpine Linux with a complete package index and only 5 MB in size!

I have prepared this Dockerfile to enable SSH on the alpine docker container.
That is completely working good. 
The above Dockerfile has root enabled in the ssh server as well as run ssh on the time of docker 
container creation.

# How to run the docker container with ssh ?

I have exposed the port 22 in the Dockerfile. You can use the below command to run the docker container.

<pre>
$ docker run -d -p 2222:22 arvindr226/alpine-ssh
</pre>

To connect the docker container via ssh.

<pre>
ssh root@localhost -p 2222
</pre>
Use Password: <b> root </b>

<img src="https://media.giphy.com/media/3o7buaZCmo40ZzIQ00/giphy.gif" width="480" height="260.9059233449477"><p><a href="https://gotechnies.com">via Gotechnies</a></p>
