#
# Copyright (c) 2012-2015 Codenvy, S.A.
# All rights reserved. This program and the accompanying materials
# are made available under the terms of the Eclipse Public License v1.0
# which accompanies this distribution, and is available at
# http://www.eclipse.org/legal/epl-v10.html
#
# Contributors:
#   Codenvy, S.A. - initial API and implementation
#

FROM codenvy/jdk7_vnc

EXPOSE 5901
ENV CODENVY_APP_PORT_5901_HTTP 5901

VOLUME ["/home/user/host"]
ENV CODENVY_APP_BIND_DIR /home/user/host

#RUN mkdir /home/user/app
#WORKDIR /home/user/app
#ADD $app$ /home/user/$app$
#RUN unzip -q /home/user/$app$ -d /home/user/app && \
#    rm /home/user/$app$
# expected to have all dependencies in lib directory and one single jar file application.jar in 'root' directory of archive.
#CMD java -jar application.jar $args$

CMD sleep 1h
