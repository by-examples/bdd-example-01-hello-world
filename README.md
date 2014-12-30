How to run the project?
=======================

This example is explained in
the post
[Symfony/BDD example: Hello, world!](http://by-examples.net/2014/12/24/bdd-example-hello-world-symfony.html).

##1. Preliminary step

First, you need to create and install Vagrant box
named `symfony-v0.4.4`. You will find the instruction
in the post titled
[Generating symfony-v0.4.4 box](http://by-examples.net/2014/12/23/generating-symfony-0-4-4-box.html).

##2. Running the example

    $ git clone https://github.com/by-examples/symfony-bdd-example-01-hello-world.git
    $ cd symfony-bdd-example-01-hello-world
    $ vagrant up

##3. Running the tests

    $ vagrant up
    $ vagrant ssh
    $ composer install -o
    $ bin/behat

##4. Visit the app with the browser

Now, you can run the web browser and visit:

    http://localhost:8880/
    http://localhost:8880/app_dev.php/
