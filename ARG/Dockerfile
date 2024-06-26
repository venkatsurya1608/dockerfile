ARG version
FROM almalinux:${version}
RUN cat /etc/*release
ARG course
ARG TRAINER
RUN echo "course is: ${course}, Trainer is: ${TRAINER}}"
CMD [ "sleep","60" ]

# ARG version
# FROM almalinux:${version:-8}
# #RUN cat /etc/*release
# ARG course=Docker
# ARG TRAINER=Siva
# RUN echo "course is: ${course}, Trainer is: ${TRAINER}}"
# CMD [ "sleep","60" ]
# = default value--command lo arg evvaledu ante automatically taking default value
# FROM kuda default value pettam (:-) use chesam other instruction lo (:-)