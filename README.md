How to run the project?
=======================


##1. Preliminary step

First, you need to create and install Vagrant box
named `symfony-v0.4.4`. You will find the instruction
in the post titled
(Generating symfony-v0.4.4 box)[http://by-examples.net/2014/12/23/generating-symfony-0-4-4-box.html].

##2. Running the tests

    $ vagrant ssh
    $ bin/behat

##3. Running the example

    $ git clone https://github.com/by-examples/symfony-bdd-example-01-hello-world.git
    $ cd symfony-bdd-example-01-hello-world
    $ vagrant up

Now, you can run the web browser and visit:

    http://localhost:8880/
    http://localhost:8880/app_dev.php/

