# Desafios FullCycle Turma 7
## Curso: Desenvolvimento de Aplicações Modernas e Escaláveis com Microsserviços

### Pré requisitos
- Instalação docker.

### Build da imagem
```docker
docker build . -t go-hpa
```

### Executar a imagem
```docker
docker run -p 8000:8000 --rm go-hpa
```

### Endereço imagem dockerhub

https://hub.docker.com/repository/docker/urameshe/go-hpa