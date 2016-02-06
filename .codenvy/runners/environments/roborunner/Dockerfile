FROM codenvy/jdk7_vnc

VOLUME ["/home/user/robocode"]
ENV CODENVY_APP_BIND_DIR /home/user/robocode

USER root
RUN echo -e "[program:robocode]\npriority=50\ncommand=/bin/sh robocode.sh\nenvironment=DISPLAY=\":0\"\ndirectory=/home/user/robocode" >> /opt/supervisord.conf


