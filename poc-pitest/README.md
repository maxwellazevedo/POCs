# O Pitest

O Pitest faz uma mutação no seu projeto, ele permite que você verifique a cobertura real dos testes do seu projeto.

Dentro dos seus testes ele atua fazendo uma “cópia” do projeto e inserindo mais cenários de erros para avaliar se os os testes desenvolvidos irão falhar após a mutação. Quando o teste falha o mutante é morto. 

Caso algum mutante sobreviva isso significa que você precisa aumentar a cobertura dos testes do seu projeto, os mutantes sobreviventes servem de input para criação de mais testes.