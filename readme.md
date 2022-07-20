# Comandos básicos git

<h4>clonar repositório do gitHub para seu computador</h4> 

`git clone https:/____link_do_seu_repositorio_.git`

<h4>clonar o repositório para uma pasta específica</h4>

`git clone <repositorio> <meu-projeto-clone>`

<h4>clonar o repositório a partir de uma branch específica</h4>

`git clone -branch new_feature <repositorio>`

<h4>ver alterações feitas em detalhes</h4>

`git log`

<h4>ver alterações feitas resumidamente</h4>

`git log --oneline`

<h4>mostra em detalhes as linhas alteradas</h4>

`git log -p`

<h4>ver alterações feitas por outra pessoa que também está no projeto</h4>

`git log --author="user_name"`

<h4>ver alterações feitas em determinado período</h4>

`git log --since=1.month.ago --until=1.day.ago`

<h4>ver alterações feitas em determinada data</h4>

`git log --pretty="format:%h %s"`

<h4>restaurar alterações</h4>

`git restore --source 000000 (código da alteração) .`
