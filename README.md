# Ansible

## O que é o Ansible?

O Ansible é uma ferramenta que podemos usar para automatizar rotinas de infraestrutura, gosto muito de dizer que o Ansible se diferencia pela sua facilidade de uso, sua facilidade de aprendizado. Uma vez ouvi em um fórum uma definição que gostei muito **" o ansible é um 'framework' de SSH "** para usar automações de infraestrutura.

Um grande diferencial do Ansible é o fato que ele não requer qualquer tipo de agente, através da autenticação que ele estabelece com o ativo, ele executa os comandos que nós configuramos em nossas automações.

## Como o Ansible é usado?

Para usar o Ansible basta que tenhamos o binário do Ansible. As instruções do Ansible são escritas em arquivos que chamamos de **playbooks** que são escritos em **yaml**. 
Os módulos do Ansible são escritos em Python, quando instalamos o Ansible precisamos que o pythons esteja presente. 
Outro ponto, o Ansible não requer qualquer tipo de agente, ele usa apenas o SSH para autenticar e fazer a execução dos playbooks com as intruções.

O ansible usa um arquivo que chamamos de inventário que tem todos os hosts que vamos fazer a execução dos scripts 


## O que são os playbooks?
O playbook é o arquivo que recebe as instruções para execução das tarefas de automação.

