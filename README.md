When running this container, you will be able to load the skyline webpage at port 1500.

NOTE: I haven't yet confirmed that horizon and the analyzer are working, other than that their logs don't complain about anything.  (except about starving for data)

Build and run with:

    # Install Docker, using instructions at http://docker.io/gettingstarted/
    
    # download Docker build files
    git clone https://github.com/carver/docker-skyline
    cd docker-skyline
    
    # build
    docker build -t="carver/skyline" .
    
    # run
    docker run -d carver/skyline
    
    # behold
    curl localhost:1500
