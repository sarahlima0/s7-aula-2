

# Define os estágios do pipeline
stages:
  - build
  - test
  - deploy

# Configuração dos jobs
build:
  stage: build
  script:
  - echo "Compilando o código..."

test:
  stage: test
  script:
    - echo "Executando os testes automatizados..."

deploy:
  stage: deploy
  script:
    - echo "Implantando o projeto em um ambiente de produção..."
