git_diet
========

Sometimes you just don't want git to keep absolutely everything that has ever been committed to a repo.  Maybe you need to trim down your repo size to put it on github or push it to heroku, or maybe you are just a little OCD.  Either way, here's hoping some of the scripts in here can help you.

find\_largest_objects.sh
--------------------
Shows the largest objects in the git repo of the current directory

    find_largest_objects.sh [-n <number_of_objects] [-d] [-f]
    
      OPTIONS
        -n  Show the n largest files in the repo (default 10)
        -d  Filter out files that are currently in the project
        -f  Show file paths only (useful for piping into other scripts)