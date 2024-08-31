# Formulários Dinâmicos com PHP e Enum Encapsulado em Classe

Este repositório contém exemplos de formulários dinâmicos em PHP que utilizam um `enum` encapsulado em uma classe para representar estados brasileiros. Dependendo do exemplo, o formulário pode retornar a sigla ou o nome completo do estado selecionado.

## Estrutura do Projeto

```plaintext
.
├── classes
│   └── EstadoEnum.php        # Classe que encapsula o enum Estado.
├── exemplo_sigla.php         # Página que retorna a sigla do estado.
└── exemplo_nome_completo.php # Página que retorna o nome completo do estado.
```

**Pré-requisitos**

- PHP 8.1 ou superior (necessário para o uso de enum).

- Servidor web para hospedar e executar os arquivos PHP.

**Instruções**

1. Clone o repositório:
```bash
git clone https://github.com/fasmedeiros/PHP/tree/main/php-dynamic-forms-enum
```

2. Navegue até o diretório do projeto:

```bash
cd seu-repositorio
```

3. Execute o servidor PHP embutido:
```bash
php -S localhost:8000
```

4. Acesse os exemplos pelo navegador:
- Para retornar a sigla do estado, acesse http://localhost:8000/exemplo_sigla.php.
- Para retornar o nome completo do estado, acesse http://localhost:8000/exemplo_nome_completo.php.

## Implementação

### 1. Classe EstadoEnum

A classe EstadoEnum encapsula o enum Estado e fornece métodos auxiliares para trabalhar com os estados brasileiros.

- getSigla(Estado $estado): string — Retorna a sigla do estado.
- getNomeCompleto(Estado $estado): string — Retorna o nome completo do estado.
- getAllEstados(): array — Retorna todos os casos do enum Estado.

### 2. Exemplo 1: Retornando a Sigla do Estado

Arquivo: exemplo_sigla.php

Esse exemplo exibe um formulário que permite ao usuário selecionar um estado brasileiro e, ao enviar o formulário, retorna a sigla do estado selecionado.

### 3. Exemplo 2: Retornando o Nome Completo do Estado

Arquivo: exemplo_nome_completo.php

Esse exemplo exibe um formulário que permite ao usuário selecionar um estado brasileiro e, ao enviar o formulário, retorna o nome completo do estado selecionado.

## Licença

Este projeto é licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais informações.
Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, sinta-se à vontade para abrir uma issue ou enviar um pull request.
Contato

Se você tiver dúvidas ou sugestões, entre em contato em gannba@hotmail.com.
