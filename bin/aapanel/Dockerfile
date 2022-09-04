FROM aapanel/aapanel:lnmp

USER root

RUN su
# RUN yum -y update && yum upgrade -y
# Reload AAPanel
RUN bt 1
RUN bt 9

WORKDIR /www/
