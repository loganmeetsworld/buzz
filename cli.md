### `cp` trick
`cp foo{-bar,}.json` - copies a file named foo-bar.json to a file named
foo.json, can easily parse file naming this way

### `top`
display and update sorted information about processes

### `ps/pstree`
process status
shows running processes as a tree

### `free`
This structure describes the interface a threading library uses for locking.

### chmod +x
Change. File. Mode. Bits. `chmod +x` on a file (script) means that you'll make it executable.

### pbpaste  
What ever you have copied will get pasted. Just running the command `cat`s it, but you can quickly paste to file: 
`pbpaste > myfile.txt`

### lsof  
list all open files

### chown
Change owner. switch between unprivledged and privledged users.

### chmod
Change mode. Change access permissions to file system objects. Allow files to be executed.

### adduser
Low-level utility for adding users to system. 

### -rw-r----- owner and group permissions
A user can read and write to that file, but the group is read only

### ssh configs
Can make life easier. Your ssh options will be read from the configuration file.

### docker ps

Lists all docker images running and can be piped to lots of other commands like `docker rm $(docker ps -aq)` or `docker stop $(docker ps -aq)`. This only removes stopped containers, doesn't delete data volumes.

### docker inspect

`docker inspect -f "{{ .HostConfig.Links }}" <name_of_your_container>`

Get all links for the primary container.

`docker inspect --format="{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}`

Get the IP for eth0 inside the container.

### docker rmi

`docker rmi $(docker images -q -f "dangling=true")`

Remove all images, doesn't remove images in use by containers.

`docker rmi $(docker images -q)`

Remove all images, doesn't remove images in use by containers.

### docker-machine

`eval "$(docker-machine env default)"`

Set docker cli to use the default VM.

### docker exec

`docker exec -it`

Execute interactive command in running container.
