# SMTP Relay Testing

This project can be used as a template for new GitHub Codepsace projects.

```bash

az login -t $TENANT_ID

docker run --rm --name postfix \
--env-file smtp.env \
-p 587:587 boky/postfix

```
