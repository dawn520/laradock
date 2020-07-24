FROM hyperf/hyperf:7.4-alpine-v3.11-cli

LABEL maintainer="yongfeng <yongfeng@lm.com>"

RUN wget https://github.com/composer/composer/releases/download/1.8.6/composer.phar
RUN chmod u+x composer.phar
RUN mv composer.phar /usr/local/bin/composer
RUN composer config -g repo.packagist composer https://mirrors.aliyun.com/composer


#/bin/sh -c “while true; do echo hello world; sleep 1; done”
CMD ["/bin/sh","-c","while true; do echo hello world; sleep 1; done"]
