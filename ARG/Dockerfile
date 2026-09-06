ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="Docker" \
    TRAINER="Balu"
ENV COURSE:"${COURSE}"    

RUN echo "Trainer:${TRAINER},course:${COURSE},Version:${VERSION}"

CMD ["sleep","1000"]