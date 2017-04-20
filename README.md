# Flavio's Blog

Built a PostgreSQL relational database scheme to store the results of a game tournament. Also provided a number of queries to efficiently report the results of the tournament and determine the winner.

### Requirements

* VirtualBox installation (https://www.virtualbox.org/wiki/Downloads)
* Vagrant installation (https://www.vagrantup.com/downloads)
* Clone of Vagrant VM for ud197 (git clone http://github.com/udacity/fullstack-nanodegree-vm fullstack)
* To run the test suite (exercising all of the Python functions for the tournament database):
* PostgreSQL
* and Python

From a GitHub shell:

```
$ cd fullstack/vagrant
$ vagrant up (you can turn off the VM with 'vagrant halt')
$ vagrant ssh (from here you can type 'exit' to log out)
$ cd /vagrant/tournament
$ psql -f tournament.sql
$ python tournament_results.py
```

### Running the project
1. Clone the project
2. Run the sql queries from tournament.sql
3. Run the following unit tests code:

```python
    $ python tournament_test.py
```

Tadaa! You have the tournament working according to the unit tests

### References
[1] https://en.wikipedia.org/wiki/Swiss-system_tournament

