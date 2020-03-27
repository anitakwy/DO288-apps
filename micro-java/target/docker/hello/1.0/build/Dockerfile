FROM fabric8/s2i-java:2.3
ENV AB_PROMETHEUS_OFF=true JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Hello microservice using Thorntail" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2020-03-27T14:44:30.264 org.label-schema.name="Red Hat Training Hello Java app" org.label-schema.vcs-ref=d926a92454a24acfda4a012f93bde07afdd0f48a org.label-schema.vcs-url=https://github.com/anitakwy/DO288-apps
EXPOSE 8080 8778 9779
COPY maven /deployments/
