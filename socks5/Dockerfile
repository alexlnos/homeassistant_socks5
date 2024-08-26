ARG BUILD_FROM
FROM $BUILD_FROM

ENV LANG C.UTF-8

# Установка дополнительных компонентов, если это необходимо
#RUN apk add --no-cache <your-package>

# Копирование скрипта запуска
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
