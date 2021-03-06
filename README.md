### One Month Rails with Philly Startup Leaders

This is a code repository for the One Month Rails course through Philly Startup Leaders.

The code is organized by branches with the name of each lesson.  To see the finished code for a lesson click on the branch button above, and select the lesson you're looking for.

If you would like to clone this repo (git a copy of it on your own machine), open your command line
and naviate to the directory you want to download the code to.

Once you're there just run:
```
$ git clone https://github.com/cnorm35/one_month_rails_psl.git
```
Once you have a local copy, go into the directory for the example applicaiton with

```
cd one_month_rails_psl
```
Currently, this application is running Rails 4.1.8.  That seemed to be the version most people had installed.  To see which version you're currently running, just type the following into your command line

```
$ rails -v
```
If you need to install the specific version. run:

```
gem install rails -v 4.1.8 --no-ri --no-rdoc
```

The extra flags at the end skip some of the documentation and will speed up the download and install

Once your in the example applications directory, run:

```
$ bundle install
```
to make sure you have all the needed gems for the applicaiton.
You may also need to run
```
$ rake db:migrate
```
to make sure the database schema is up to date.

If anyone has anything they'd like me to add or something I missed, submit a pull request.