# Learn how to use Ansible Docker

### Start the Ansible container
* Open new Terminal in VSCode
* Run the docker run to start the Ansible container.

```
docker run -it ansible
```

* Verify ansible is runnint ``` ansible -version ```

### Open a second Terminal

1. Verify the name of the docker and information 
2. RUn ``` docker ps ``` 
3. The output will look similar to this:
```
CONTAINER ID   IMAGE     COMMAND       CREATED          STATUS          PORTS     NAMES
709e9b7a1de1   ansible   "/bin/bash"   15 minutes ago   Up 15 minutes             brave_bhabha
```
4. Remeber the NAMES

### Copy the Ansible Playbook to the container
1. Execute the following command. Note: Replace brave_bhabha with your names
```
docker cp .\playbook.yml brave_bhabha:/work
```
2. This will copy your playbook to your docker container.

### Jump back to Ansible Docker
Switch back to your ansible docker terminal you opened at the begining
1. If you do an ```ls``` you will see the file
2. Execute the ansible-playbook to make sure things work
``` ansible-playbook playbook.yml ```




### Notes
If you have made any changes to your repo make sure to add the tracked files, commit and push to your repo so you do not lose your code.

```
git add ..
git commit -m "updates"
git push
```