NOTE: this is only shown to display the skyline webpage at port 1500.  I'm still working to confirm that it can accept data from graphite.

Install Docker at http://docker.io

Build and run with:

    docker build -t="carver/skyline" .
    docker run -d carver/skyline
    curl localhost:1500
