FROM docker:stable

LABEL "name"="Build Environment"
LABEL "maintainer"="WoLfulus <wolfulus@gmail.com>"
LABEL "version"="1.0.0"

LABEL "com.github.actions.name"="Build Environment"
LABEL "com.github.actions.description"="Build Environment Tools"
LABEL "com.github.actions.icon"="package"
LABEL "com.github.actions.color"="blue"

RUN apk update && apk add bash jq curl

ENTRYPOINT ["bash", "-c"]
