FROM amazoncorretto:11
USER root
COPY ./dev-ott.crt /root/dev-ott.crt
RUN /usr/bin/keytool -import -noprompt -storepass changeit -alias ncl_intra_ca -keystore $JAVA_HOME/lib/security/cacerts -file /root/dev-ott.crt