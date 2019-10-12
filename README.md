# Jenkins Challenge

Hey guys :) We have a nice Challenge for you.

Here is the situation: Our Jenkins box on AWS (Amazon Web Services) isn't working.

But no fear! You already built your own Jenkins!

#### The weekend Challenge is:

Create your own Jenkins Box locally (with your vagrant up)
Set up a Webhooks from GitHub to trigger a build in Jenkins

#### The Challenge will include:

generating SSH keys to autheticate Webhooks

Opening up your laptop & virtual Machine to receive said Webhook

Allow access (firewall)

Make sure you set

{ GitHub }

    |
    |  [SSH, firewall, fixed IP address]
    |
    |
  \   /
    \/
[ My computer ] | [[ Jenkins 192]]

We want Jenkins to trigger a build(we are not actually going to build anything) when a change happen in GitHub repo

# Create a instance of Jenkins ( done - vagrant up)
  # make sure it has plugin for GitHub

# generate keys so it can communicate securely with GitHub
# Figure out how GitHub will communicate with the machine that is INSIDE you machine
  # fire walls, IP addresses

Environment Variable
setting: creating one: MY_VAR=hello

Calling:

echo $MY_VAR

hello

Running programs to be saved as variables:

FPaiva@lt-rich-w133 MINGW64 ~ $ DIR=$(pwd)

FPaiva@lt-rich-w133 MINGW64 ~ $ echo $DIR /c/Users/FPaiva

FPaiva@lt-rich-w133 MINGW64 ~ $ ANOTHER_VAR=$(ls dat)

FPaiva@lt-rich-w133 MINGW64 ~ $ echo $ANOTHER_VAR ntuser.dat.LOG1 ntuser.dat.LOG2
