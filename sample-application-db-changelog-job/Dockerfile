# Run
FROM openjdk:11-jre

EXPOSE 5432
COPY target/sample-application-db-changelog-job.jar .
ENTRYPOINT java -jar sample-application-db-changelog-job.jar