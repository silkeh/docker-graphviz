FROM debian:stretch

RUN apt-get -qq update; \
    apt-get install -qqy \
        graphviz ruby-graphviz \
        python-pydot python3-pydot python-pygraphviz python3-pygraphviz; \
    rm -rf /var/lib/apt/lists/*
