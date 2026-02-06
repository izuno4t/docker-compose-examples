FROM amazoncorretto:17
RUN yum install -y mariadb maven \
    && rm -rf /var/cache/yum/* \
    && yum clean all
# USER root
# COPY ./dev-ott.crt /root/dev-ott.crt
# RUN /usr/bin/keytool -import -noprompt -storepass changeit -alias ncl_intra_ca -keystore $JAVA_HOME/lib/security/cacerts -file /root/dev-ott.crt