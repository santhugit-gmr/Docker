FROM almalinux:8
RUN yum install nginx -y && yum clean all
LABEL TRAINING="DevOps"\
      TRAINER="Santhosh"\
      DURATION="120Hrs"
CMD ["nginx", "-g", "daemon off;"]
