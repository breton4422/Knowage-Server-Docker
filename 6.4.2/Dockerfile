FROM java:8

ENV KNOWAGE_VERSION 6_4_2
ENV KNOWAGE_EDITION CE
ENV KNOWAGE_RELEASE_DATE 20190619
ENV KNOWAGE_PACKAGE_SUFFIX -bin-${KNOWAGE_VERSION}-${KNOWAGE_EDITION}-${KNOWAGE_RELEASE_DATE}
ENV FILEEXTENSION .zip
ENV KNOWAGE_REPO_VERSION 6.4.2
ENV KNOWAGE_OW2_BASE_URL http://release.ow2.org/knowage/${KNOWAGE_REPO_VERSION}/Applications
ENV KNOWAGE_OW2_DDL_URL http://release.ow2.org/knowage/${KNOWAGE_REPO_VERSION}/Database%20scripts

ENV KNOWAGE_CORE_ENGINE knowage
ENV KNOWAGE_CORE_FILE ${KNOWAGE_CORE_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_CORE_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_CORE_FILE}

ENV KNOWAGE_BIRTREPORT_ENGINE ${KNOWAGE_CORE_ENGINE}birtreportengine
ENV KNOWAGE_BIRTREPORT_FILE ${KNOWAGE_BIRTREPORT_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_BIRTREPORT_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_BIRTREPORT_FILE}

ENV KNOWAGE_COCKPIT_ENGINE ${KNOWAGE_CORE_ENGINE}cockpitengine
ENV KNOWAGE_COCKPIT_FILE ${KNOWAGE_COCKPIT_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_COCKPIT_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_COCKPIT_FILE}

ENV KNOWAGE_COMMONJ_ENGINE ${KNOWAGE_CORE_ENGINE}commonjengine
ENV KNOWAGE_COMMONJ_FILE ${KNOWAGE_COMMONJ_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_COMMONJ_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_COMMONJ_FILE}

ENV KNOWAGE_DATAMINING_ENGINE ${KNOWAGE_CORE_ENGINE}dataminingengine
ENV KNOWAGE_DATAMINING_FILE ${KNOWAGE_DATAMINING_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_DATAMINING_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_DATAMINING_FILE}

ENV KNOWAGE_GEOREPORT_ENGINE ${KNOWAGE_CORE_ENGINE}georeportengine
ENV KNOWAGE_GEOREPORT_FILE ${KNOWAGE_GEOREPORT_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_GEOREPORT_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_GEOREPORT_FILE}

ENV KNOWAGE_JASPERREPORT_ENGINE ${KNOWAGE_CORE_ENGINE}jasperreportengine
ENV KNOWAGE_JASPERREPORT_FILE ${KNOWAGE_JASPERREPORT_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_JASPERREPORT_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_JASPERREPORT_FILE}

ENV KNOWAGE_KPI_ENGINE ${KNOWAGE_CORE_ENGINE}kpiengine
ENV KNOWAGE_KPI_FILE ${KNOWAGE_KPI_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_KPI_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_KPI_FILE}

ENV KNOWAGE_META_ENGINE ${KNOWAGE_CORE_ENGINE}meta
ENV KNOWAGE_META_FILE ${KNOWAGE_META_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_META_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_META_FILE}

ENV KNOWAGE_NETWORK_ENGINE ${KNOWAGE_CORE_ENGINE}networkengine
ENV KNOWAGE_NETWORK_FILE ${KNOWAGE_NETWORK_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_NETWORK_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_NETWORK_FILE}

ENV KNOWAGE_QBE_ENGINE ${KNOWAGE_CORE_ENGINE}qbeengine
ENV KNOWAGE_QBE_FILE ${KNOWAGE_QBE_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_QBE_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_QBE_FILE}

ENV KNOWAGE_SVGVIEWER_ENGINE ${KNOWAGE_CORE_ENGINE}svgviewerengine
ENV KNOWAGE_SVGVIEWER_FILE ${KNOWAGE_SVGVIEWER_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_SVGVIEWER_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_SVGVIEWER_FILE}

ENV KNOWAGE_TALEND_ENGINE ${KNOWAGE_CORE_ENGINE}talendengine
ENV KNOWAGE_TALEND_FILE ${KNOWAGE_TALEND_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_TALEND_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_TALEND_FILE}

ENV KNOWAGE_WHATIF_ENGINE ${KNOWAGE_CORE_ENGINE}whatifengine
ENV KNOWAGE_WHATIF_FILE ${KNOWAGE_WHATIF_ENGINE}${KNOWAGE_PACKAGE_SUFFIX}${FILEEXTENSION}
ENV KNOWAGE_WHATIF_URL ${KNOWAGE_OW2_BASE_URL}/${KNOWAGE_WHATIF_FILE}

ENV APACHE_TOMCAT_VERSION 8.5.37
ENV APACHE_TOMCAT_PACKAGE apache-tomcat-${APACHE_TOMCAT_VERSION}
ENV APACHE_TOMCAT_URL https://archive.apache.org/dist/tomcat/tomcat-8/v8.5.37/bin/${APACHE_TOMCAT_PACKAGE}.zip

#location of mysql script to init knowage db
ENV KNOWAGE_MYSQL_SCRIPT_URL ${KNOWAGE_OW2_DDL_URL}/mysql-dbscripts-${KNOWAGE_VERSION}-${KNOWAGE_RELEASE_DATE}.zip

ENV LIB_COMMONS_LOGGING_URL https://search.maven.org/remotecontent?filepath=commons-logging/commons-logging/1.1.1/commons-logging-1.1.1.jar
ENV LIB_COMMONS_LOGGING_API_URL https://search.maven.org/remotecontent?filepath=commons-logging/commons-logging-api/1.1/commons-logging-api-1.1.jar
ENV LIB_CONCURRENT_URL https://search.maven.org/remotecontent?filepath=org/lucee/oswego-concurrent/1.3.4/oswego-concurrent-1.3.4.jar
ENV LIB_MYSQL_CONNECTOR_URL https://search.maven.org/remotecontent?filepath=mysql/mysql-connector-java/5.1.33/mysql-connector-java-5.1.33.jar
ENV LIB_GERONIMO_COMMONJ_URL https://search.maven.org/remotecontent?filepath=org/apache/geronimo/specs/geronimo-commonj_1.1_spec/1.0/geronimo-commonj_1.1_spec-1.0.jar
ENV LIB_MYFOO_COMMONJ_URL https://github.com/SpagoBILabs/SpagoBI/blob/mvn-repo/releases/de/myfoo/commonj/1.0/commonj-1.0.jar?raw=true

ENV LIB_POSTGRESQL_CONNECTOR_URL https://jdbc.postgresql.org/download/postgresql-42.2.4.jar

ENV LIB_CASSANDRA_CONNECTOR_URL https://github.com/adejanovski/cassandra-jdbc-wrapper/releases/download/3.1.0/cassandra-jdbc-wrapper-3.1.0.jar

#knowage directory
ENV KNOWAGE_DIRECTORY /home/knowage
#mysql script directory
ENV MYSQL_SCRIPT_DIRECTORY ${KNOWAGE_DIRECTORY}/mysql

#go to knowage home directory
WORKDIR ${KNOWAGE_DIRECTORY}

#install required packages and clean up to save space
#note: Refer to tip @ https://superuser.com/questions/1423486/issue-with-fetching-http-deb-debian-org-debian-dists-jessie-updates-inrelease & https://unix.stackexchange.com/questions/508724/failed-to-fetch-jessie-backports-repository
RUN rm /etc/apt/sources.list.d/jessie-backports.list
RUN printf "deb http://cdn-fastly.deb.debian.org/debian/ jessie main\ndeb-src http://cdn-fastly.deb.debian.org/debian/ jessie main\ndeb http://security.debian.org jessie/updates main\ndeb-src http://security.debian.org jessie/updates main\ndeb http://archive.debian.org/debian jessie-backports main\ndeb-src http://archive.debian.org/debian jessie-backports main" > /etc/apt/sources.list
RUN printf "Acquire::Check-Valid-Until \"false\";\n" >> /etc/apt/apt.conf
RUN apt-get update && apt-get install -y wget coreutils unzip mysql-client  && rm -rf /var/lib/apt/lists/*

#download mysql scripts
RUN wget "${KNOWAGE_MYSQL_SCRIPT_URL}" -O mysql.zip && \
        unzip mysql.zip && \
        rm mysql.zip

#download apache tomcat and extract it
RUN wget "${APACHE_TOMCAT_URL}" && \
       unzip ${APACHE_TOMCAT_PACKAGE}.zip && \
       rm ${APACHE_TOMCAT_PACKAGE}.zip

#go to apache tomcat webapps directory
WORKDIR ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/webapps

#download knowage engines and extract them
RUN wget "${KNOWAGE_CORE_URL}" && \
       unzip ${KNOWAGE_CORE_FILE} -d ${KNOWAGE_CORE_ENGINE} && \
       rm ${KNOWAGE_CORE_FILE}

WORKDIR ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/webapps/${KNOWAGE_CORE_ENGINE}
RUN unzip -n ${KNOWAGE_CORE_ENGINE}.war && \
       rm ${KNOWAGE_CORE_ENGINE}.war

WORKDIR ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/webapps

RUN wget "${KNOWAGE_BIRTREPORT_URL}" && \
       unzip ${KNOWAGE_BIRTREPORT_FILE} -d ${KNOWAGE_BIRTREPORT_ENGINE} && \
       rm ${KNOWAGE_BIRTREPORT_FILE}
       
RUN wget "${KNOWAGE_COCKPIT_URL}" && \
       unzip ${KNOWAGE_COCKPIT_FILE} -d ${KNOWAGE_COCKPIT_ENGINE} && \
       rm ${KNOWAGE_COCKPIT_FILE}
       
RUN wget "${KNOWAGE_COMMONJ_URL}" && \
       unzip ${KNOWAGE_COMMONJ_FILE} -d ${KNOWAGE_COMMONJ_ENGINE} && \
       rm ${KNOWAGE_COMMONJ_FILE}
       
RUN wget "${KNOWAGE_DATAMINING_URL}" && \
       unzip ${KNOWAGE_DATAMINING_FILE} -d ${KNOWAGE_DATAMINING_ENGINE} && \
       rm ${KNOWAGE_DATAMINING_FILE}
       
RUN wget "${KNOWAGE_GEOREPORT_URL}" && \
       unzip ${KNOWAGE_GEOREPORT_FILE} -d ${KNOWAGE_GEOREPORT_ENGINE} && \
       rm ${KNOWAGE_GEOREPORT_FILE}
       
RUN wget "${KNOWAGE_JASPERREPORT_URL}" && \
       unzip ${KNOWAGE_JASPERREPORT_FILE} -d ${KNOWAGE_JASPERREPORT_ENGINE} && \
       rm ${KNOWAGE_JASPERREPORT_FILE}
       
RUN wget "${KNOWAGE_KPI_URL}" && \
       unzip ${KNOWAGE_KPI_FILE} -d ${KNOWAGE_KPI_ENGINE} && \
       rm ${KNOWAGE_KPI_FILE}
       
RUN wget "${KNOWAGE_META_URL}" && \
       unzip ${KNOWAGE_META_FILE} -d ${KNOWAGE_META_ENGINE} && \
       rm ${KNOWAGE_META_FILE}
       
RUN wget "${KNOWAGE_NETWORK_URL}" && \
       unzip ${KNOWAGE_NETWORK_FILE} -d ${KNOWAGE_NETWORK_ENGINE} && \
       rm ${KNOWAGE_NETWORK_FILE}
       
RUN wget "${KNOWAGE_QBE_URL}" && \
       unzip ${KNOWAGE_QBE_FILE} -d ${KNOWAGE_QBE_ENGINE} && \
       rm ${KNOWAGE_QBE_FILE}
       
RUN wget "${KNOWAGE_SVGVIEWER_URL}" && \
       unzip ${KNOWAGE_SVGVIEWER_FILE} -d ${KNOWAGE_SVGVIEWER_ENGINE} && \
       rm ${KNOWAGE_SVGVIEWER_FILE}
       
RUN wget "${KNOWAGE_TALEND_URL}" && \
       unzip ${KNOWAGE_TALEND_FILE} -d ${KNOWAGE_TALEND_ENGINE} && \
       rm ${KNOWAGE_TALEND_FILE}
       
RUN wget "${KNOWAGE_WHATIF_URL}" && \
       unzip ${KNOWAGE_WHATIF_FILE} -d ${KNOWAGE_WHATIF_ENGINE} && \
       rm ${KNOWAGE_WHATIF_FILE}

#go to apache tomcat lib directory
WORKDIR ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/lib

#download knowage libs and put them into apache tomcat lib
RUN wget "${LIB_COMMONS_LOGGING_URL}"
RUN wget "${LIB_COMMONS_LOGGING_API_URL}"
RUN wget "${LIB_CONCURRENT_URL}"
RUN wget "${LIB_MYSQL_CONNECTOR_URL}"
RUN wget "${LIB_GERONIMO_COMMONJ_URL}"
RUN wget "${LIB_MYFOO_COMMONJ_URL}"

#dowload DBs libraries and put them into apache tomcat lib
RUN wget "${LIB_POSTGRESQL_CONNECTOR_URL}"
RUN wget "${LIB_CASSANDRA_CONNECTOR_URL}"

#create setenv.sh file
#increase Java Heap memory to 4GB - JAVA_OPTS
RUN touch ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/bin/setenv.sh
RUN echo "JAVA_OPTS=\"${JAVA_OPTS} -Xmx4g\"" >> ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/bin/setenv.sh

#go to apache tomcat configuration directory
WORKDIR ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/conf

#override apache tomcat server configuration
COPY ./server.xml ./

#go to binary folder in order to execute tomcat startup
WORKDIR ${KNOWAGE_DIRECTORY}/${APACHE_TOMCAT_PACKAGE}/bin

#make the script executable by bash (not only sh) and
#make knowage running forever without exiting when running the container
RUN sed -i "s/bin\/sh/bin\/bash/" startup.sh && \
	sed -i "s/EXECUTABLE\" start/EXECUTABLE\" run/" startup.sh

#copy entrypoint to be used at runtime
COPY ./entrypoint.sh ./

#make all scripts executable
RUN chmod +x *.sh

#expose common tomcat port
#this can be used by the host to expose the application
#you can use it while running image with the param '-p 8080:8080'
EXPOSE 8080

#-d option is passed to run knowage forever without exiting from container
ENTRYPOINT ["./entrypoint.sh"]

#this will start knowage just after the previous entrypoint
CMD ["./startup.sh"]
