ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="20hrs"
ARG topics="Docker&K8S"
ENV topics=$topics
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, topics are: ${topics}, version: ${version}"
CMD ["sleep", "1000"]