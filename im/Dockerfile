# CentOS 7 + IBM Installation Manager

FROM mithrandar/docker-centos7-base

MAINTAINER Eric Weber

ADD installim.sh /opt/installim.sh

RUN /opt/installim.sh

CMD ["/opt/IBM/InstallationManager/eclipse/tools/imcl","-c"]
