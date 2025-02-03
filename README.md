# 🎯 Jogo do Número Secreto
https://jogo-seven-drab.vercel.app/
## 📌 Sobre o Projeto
O **Jogo do Número Secreto** é um jogo interativo desenvolvido com **HTML, CSS e JavaScript**. O objetivo é simples: adivinhar um número aleatório dentro de um intervalo definido. Um passatempo divertido e desafiador!


## 🚀 Funcionalidades
- 🔢 Geração aleatória do número secreto.
- 🎯 Entrada para palpites do jogador.
- 📈 Dicas indicando se o número é maior ou menor.
- 🔄 Contador de tentativas para acompanhar o progresso.
- 🎉 Mensagem de sucesso ao acertar.
- 🔁 Botão para reiniciar o jogo.
- 🗣 Feedback de áudio com a **Web Speech API**.

## 🛠 Tecnologias Utilizadas
- **HTML5** → Estrutura do jogo.
- **CSS3** → Estilização e design responsivo.
- **JavaScript** → Lógica do jogo.
- **Web Speech API** → Leitura das mensagens em voz.
- **ResponsiveVoice.js** (opcional) → Suporte aprimorado para áudio.

## 🎮 Como Jogar
1. Escolha um número dentro do intervalo definido (exemplo: 1 a 10).
2. Clique em "Chutar" para verificar se acertou.
3. O jogo informará se o número secreto é maior ou menor.
4. Continue tentando até acertar.
5. Ao acertar, o jogo exibe a quantidade de tentativas usadas.
6. Para recomeçar, clique em "Novo Jogo".

## 📁 Estrutura do Projeto
```
📂 jogo-numero-secreto
├── 📄 index.html  (Código principal)
├── 📄 style.css   (Estilos e responsividade)
├── 📄 app.js      (Lógica do jogo)
├── 📂 img         (Imagens do jogo)
```

## 🖥 Requisitos para Execução
- ✔ Um navegador moderno (Chrome, Firefox, Edge, etc.).
- ✔ Para suporte completo à leitura de mensagens em voz, é necessário uma **API Key** para o `ResponsiveVoice.js`.

## 🎙 Configuração do ResponsiveVoice.js
Se desejar ativar a leitura de voz com o **ResponsiveVoice.js**, siga estes passos:
1. Cadastre-se em: [https://responsivevoice.org/register](https://responsivevoice.org/register)
2. Obtenha sua **API Key**.
3. No **index.html**, adicione:
   ```html
   <script src="https://code.responsivevoice.org/responsivevoice.js?key=SUA_API_KEY_AQUI"></script>
   ```

## 🔥 Melhorias Futuras
- 🔧 Permitir que o usuário escolha um intervalo de números maior.
- 🏆 Implementar níveis de dificuldade.
- 🎯 Criar um sistema de pontuação baseado nas tentativas.
- ✨ Melhorar efeitos visuais e adicionar animações.
- 📱 Tornar o jogo mais amigável para dispositivos móveis.

## 👨‍💻 Autor
Criado por **Bruno Pinto Nascimento**. 


