FROM goodrainapps/alpine:3.4

ENV PORT 7070

ADD rainbond-webcli /run/rainbond-webcli
ADD entrypoint.sh /run/entrypoint.sh
RUN mkdir /root/.kube

ENV RELEASE_DESC=__RELEASE_DESC__
ENTRYPOINT ["/run/entrypoint.sh"]