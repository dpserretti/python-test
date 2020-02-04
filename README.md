# Teste para estágio em Python

Olá,

Obrigado pelo interesse em participar do nosso processo seletivo para Estagiário Python!

O próximo passo é fazer um pequeno teste para mostrar seus conhecimentos para que possamos alinhar com as expectativas da vaga.

Faça um fork do projeto https://github.com/dpserretti/python-test

Iremos avaliar:
1. Organização do código (pep8)
2. Documentação de como: instalar, testar, executar
3. Criatividade e tecnologias utilizadas na implementação
3. Diferenciais: testes e coverage

Caso tenha alguma dúvida sobre o teste sinta-se à vontade para nos enviar um e-mail

Instruções do teste
------

Desenvolva uma aplicação em linguagem Python que seja acessível localmente e verifique se um determinado número de CPF está em uma        *Blacklist*.

A aplicação deve:
 
1. Ser acessível como um serviço através de uma URL do tipo `http://IP:PORT/<cpf>`, por exemplo:
`http://127.0.0.1:5000/00000000000`

2. Ser `FREE` se o CPF não estiver na *Blacklist* e `BLOCK` se o CPF estiver na black list.
 
3. Retornar `RUNNING` caso seja acessada sem um CPF.

4. Ter a opção de incluir, alterar e/ou deletar um CPF no arquivo `blacklist.txt`.

Para este teste você pode usar qualquer framework de sua escolha. De preferência o framework Flask e Python 3 pra cima.

Os CPFs a serem testados estão no arquivo `blacklist.txt`.

Todas as instruções de como rodar o projeto devem estar no README (comando para instalar dependencias, comando para rodar o projeto, etc...).

Como entregar este teste
-----

Você deve forkar este projeto em sua própria conta do GitHub e fazer os commits em seu próprio repositório.
Mandar email para danielserretti.mg@diariosassociados.com.br e julianamartins.mg@diariosassociados.com.br com o link do repositório avisando que acabou.

Boa sorte!
