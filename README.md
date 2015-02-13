# dockerfile-to-shell-script
Converts a Dockerfile to a shell script, using a series of shoddy sed commands.

Caveats: Only tested with our relatively limited Dockerfiles, and the output 
will *definitely* need examining.

There are some parameters at the top - 
    HOME_DIRECTORY Specify a home directory here for the environment you will be deploying to
    CONVERT_HOME_DIRECTORY If you want to convert the home directory statements to tilde's, set this to 1.
    
Usage ./docker_to_sh.sh

Software as is, used for Good, not Evil. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, &c &c. I am not proud of this.
