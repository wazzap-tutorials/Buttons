![WAZZAP](https://assets.cdn.filesafe.space/HZSeCeo66qW2JN9HroQv/media/d9739e2b-f7c8-485c-8567-ecd39dbb9688.png)

# 🎉 Novo Comando para Botões e Listas no Sistema de Chat

Olá! 🎉 Eu criei dois novos comandos para o nosso sistema de chat que permitirão enviar **botões** e **listas** de maneira fácil. Abaixo, explico como usá-los de forma clara e simples:

---

## 📌 **Comandos Disponíveis**

### 1. 🔘 **Comando de Botões**

**📄 Sintaxe:**


```#Button|Texto da Mensagem|Opção1*id1/Opção2*id2/Opção3*id3```

**💡 Exemplo:**

```#Button|Olá, como você está?|Bem*id_bem/Mal*id_mal/Péssimo*id_pessimo```

**🔍 Explicação:**
- **#Button**: Indica que você está criando uma mensagem com botões.
- **Texto da Mensagem**: A mensagem que os usuários verão.
- **Opções**: As opções dos botões são definidas no formato `Texto*id` e separadas por `/` se houver várias.

**📲 Resultado:**
Quando o usuário escolhe uma opção, no GHL aparecerá algo assim:

```Button: id_bem```

```Bem```

Isso mostra o **tipo de botão**, o **ID** selecionado e o **texto** do botão.

---

### 2. 📋 **Comando de Listas**

**📄 Sintaxe:**

```#List|Título|Descrição|Rodapé|Opção1*Subtítulo1*id1/Opção2*Subtítulo2*id2/Opção3*Subtítulo3*id3```

**💡 Exemplo:**

```#List|Olá, como você está?|Diga a verdade|Não seja tímido|Bem*Perfeito*id_bem/Mal*Muito*id_mal/Péssimo*Chorando*id_pessimo```

**🔍 Explicação:**
- **#List**: Indica que você está criando uma mensagem com uma lista.
- **Título**: O título da lista.
- **Descrição**: Uma breve descrição ou instrução.
- **Rodapé**: Informação adicional no final da mensagem.
- **Opções**: As opções da lista são definidas no formato `Texto*Subtítulo*id` e separadas por `/` se houver várias.

**📲 Resultado:**
Quando o usuário seleciona uma opção, no GHL aparecerá algo assim:

```List: id_bem ```

```Bem```

Isso mostra o **tipo de lista**, o **ID** selecionado e o **texto** da opção.

---

## 📝 **Resumo Rápido**

- **🔘 #Button**: Cria uma mensagem com botões.
  - **Formato da opção**: `Texto*id`
  
- **📋 #List**: Cria uma mensagem com uma lista.
  - **Formato da opção**: `Texto*Subtítulo*id`

**✨ Dicas:**
- Você pode adicionar múltiplas opções separando-as com `/`.
- Certifique-se de seguir o formato correto para que o sistema reconheça e processe seus comandos adequadamente.

---

Espero que este guia seja de grande ajuda! 🚀 Se tiver alguma dúvida ou precisar de mais assistência, não hesite em me contatar. Feliz desenvolvimento! 😊
