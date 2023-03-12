### Hexlet tests and linter status:
[![Actions Status](https://github.com/zhenevskiys/ansible-project-76/workflows/hexlet-check/badge.svg)](https://github.com/zhenevskiys/ansible-project-76/actions)

# Запуск плейбука

```bash
make docker
```

# Troubleshooting

```bash
#Если видим ошибку
#Conflicting values set for option Signed-By regarding source https://download.docker.com/linux/ubuntu/ ...

sudo rm /etc/apt/keyrings/docker.gpg
sudo rm /etc/apt/sources.list.d/docker.list

# и заново запускаем джобу
```