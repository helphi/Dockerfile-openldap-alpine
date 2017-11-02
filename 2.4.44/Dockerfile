FROM alpine:3.6

RUN apk --no-cache add openldap=2.4.44-r5 openldap-client=2.4.44-r5

EXPOSE 389 636

CMD ["slapd", "-d", "32768"]