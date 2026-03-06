# ansible-galaxy-hosting-test

In `requirements.yml`:

```yml
collections:
  - name: containers.podman
    type: url
    source: https://raw.githubusercontent.com/EndzeitBegins/ansible-galaxy-hosting-test/main/collections/containers/podman/containers-podman-1.19.0.tar.gz
```

Usual install command:

`ansible-galaxy install -r requirements.yml`

