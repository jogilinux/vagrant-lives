# vagrant-lives


## Guia de instalação do vagrant com o wsl


Este guia tem por finalidade configurar uma instalação do vagrant em conjunto com o wsl2.

Segue os passos s2:

1. Realizar instalação do wsl2 na sua maquina. [Instruções](https://learn.microsoft.com/pt-br/windows/wsl/install)
2. Instalar o virtualbox.  [Instruções](https://www.virtualbox.org/wiki/Downloads)
3. instalação do vagrant no ubuntu wsl. [Instruções](https://developer.hashicorp.com/vagrant/downloads)

```
wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install vagrant
```


## Configurar integração com o vagrant no wsl2

Precisamos criar uma pasta no windowns para salvar os projetos do vagrant.



Agora vamos criar as envs para o vagrant no ubuntu wsl.


Vamos exportar as envs para o nosso bash ou qualquer outro shell que estiver usando.

No caso o .bashrc ou arquivo .zshrc .

```
nano .bashrc

```

Dentro do arquivo vamos adicionar as seguintes variaveis.

```


```