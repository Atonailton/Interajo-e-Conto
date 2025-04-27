# História Interativa por Voz

Este projeto é uma aplicação interativa em HTML e JavaScript, que usa reconhecimento de voz para permitir que um usuário converse com uma IA que conta histórias. O projeto utiliza as APIs `SpeechRecognition` e `SpeechSynthesis` para capturar e sintetizar voz. A história é contada de forma interativa, e a IA faz perguntas ao usuário para que ele possa responder por voz.

## Funcionalidades

- **Reconhecimento de voz**: O usuário fala seu nome, e a IA grava e utiliza para personalizar a história.
- **História interativa**: A IA conta uma história e faz perguntas ao usuário, utilizando a voz.
- **Respostas por voz**: O usuário pode responder com a voz, e a IA continua a história com base na resposta.

## Como Funciona

1. **Entrada de nome**: Quando o usuário clica no botão "Falar meu nome", ele pode falar seu nome, e a IA o grava.
2. **Contação da história**: A história é contada em partes. Após cada parte, a IA faz uma pergunta ao usuário.
3. **Interação**: O usuário responde por voz, e a IA responde de forma personalizada e continua a história.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **JavaScript**: Lógica para o reconhecimento e síntese de voz.
- **SpeechRecognition API**: Para reconhecer o que o usuário fala.
- **SpeechSynthesis API**: Para a IA falar a história e as perguntas.

## Como Usar

1. Clone o repositório ou faça o download do código fonte.
2. Abra o arquivo `index.html` em um navegador que suporte as APIs `SpeechRecognition` e `SpeechSynthesis` (como o Google Chrome).
3. Clique no botão "Falar meu nome" e fale seu nome.
4. A IA começará a contar uma história, e você poderá interagir por voz.

## Exemplo de Interação

- A IA pergunta: "Você gostou da história até agora? Fale sim ou não."
- O usuário responde, e a IA continua contando a história com base na resposta.

## Como Hospedar no GitHub Pages

1. Crie um novo repositório no GitHub.
2. Faça o upload do código para o repositório.
3. Vá até as **Configurações (Settings)** do repositório e habilite o **GitHub Pages** no branch `main` ou `master`.
4. O link gerado pelo GitHub Pages será o endereço público para acessar a aplicação.

## Contribuições

Sinta-se à vontade para contribuir com melhorias e correções para este projeto. Para contribuir, faça um fork do repositório e envie suas alterações por meio de pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

