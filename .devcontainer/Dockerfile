FROM rust:1.80.1-alpine

ARG USER_NAME=rustuser
ARG USER_ID=1000
ARG GROUP_ID=1000

RUN addgroup -S -g ${GROUP_ID} ${USER_NAME} \
    && adduser -u ${USER_ID} -G ${USER_NAME} -D ${USER_NAME}
