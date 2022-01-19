# Learn how to use Ansible Docker


## Fork the repo

1. Fork the following repo to your own github account https://github.com/TELE36058-Software-Defined-Networks/exercise-01-week-02-ansible.git


### Start the Ansible container
Run the docker run to start the Ansible container.

```
docker run -it ansible
```

### Fork the Repo

1. Clone the repo you forked from your personal repo

```
git clone https://github.com/<personal repo>/exercise-01-week-02-ansible.git
```
2. Make sure you login using your github credentials
3. cd into the ```cd exercise-01-week-02-ansible```
4. execute your first helloworld playbook ``` ansible-playbook helloworld.yml ```

### Notes
If you have made any changes to your repo make sure to add the tracked files, commit and push to your repo so you do not lose your code.

```
git add ..
git commit -m "updates"
git push
```