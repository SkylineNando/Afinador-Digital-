# Afinador Digital 🎸

Este é um afinador digital desenvolvido em HTML, CSS e JavaScript que utiliza o microfone do dispositivo para capturar o som e determinar a nota musical mais próxima. O projeto é minimalista, moderno e funcional, ideal para guitarristas, violinistas e outros músicos afinarem seus instrumentos de forma rápida e precisa.

## 📋 Índice

- [Recursos](#recursos)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Como funciona](#como-funciona)
- [Contribuição](#contribuição)
- [Licença](#licença)

---

## ✨ Recursos

- Interface minimalista e responsiva.
- Usa o microfone do dispositivo para capturar áudio.
- Mostra a nota musical capturada.
- Indica se a afinação está correta, acima ou abaixo da nota alvo.
- Design moderno e clean.

---

## 🛠 Pré-requisitos

Para executar este projeto, você precisará de:

- Um navegador moderno com suporte a APIs de áudio (ex.: Google Chrome ou Firefox).
- Permissão para acessar o microfone do dispositivo.

---

## 📦 Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/skylinenando/afinador-digital.git
   ```
2. Navegue para o diretório do projeto:
   ```bash
   cd afinador-digital
   ```
3. Abra o arquivo `index.html` em seu navegador.

---

## 💡 Uso

1. Abra o projeto no navegador.
2. Clique no botão **"Iniciar Microfone"**.
3. Toque ou cante uma nota musical.
4. O afinador mostrará a nota detectada, indicando se está afinada ou precisa ser ajustada.

---

## 🧠 Como funciona

### Estrutura do projeto

```plaintext
afinador-digital/
├── index.html      # Estrutura principal do projeto
├── README.md       # Documentação do projeto
└── assets/         # (Opcional) Recursos como imagens ou sons
```

### Componentes principais

1. **HTML**
   - Estrutura do afinador, incluindo o arco, ponteiro e botão para iniciar o microfone.

2. **CSS**
   - Estiliza o projeto com um design moderno, incluindo bordas arredondadas, animações suaves e uma paleta de cores minimalista.

3. **JavaScript**
   - Usa a API Web Audio para capturar o som do microfone.
   - Aplica algoritmos de análise de frequência para determinar a nota musical mais próxima.
   - Atualiza a interface com base na afinação detectada.

### Algoritmos utilizados

1. **Auto-correlação**
   - Processa o áudio capturado para identificar a frequência dominante.
   - Retorna a frequência detectada ou `-1` caso o som seja muito baixo.

2. **Detecção de notas**
   - Compara a frequência capturada com uma lista de notas musicais predefinidas.
   - Encontra a nota mais próxima e a exibe na interface.

3. **Status de afinação**
   - Determina se a frequência está:
     - **Afinada**: Dentro de uma margem de tolerância.
     - **Acima da nota alvo**: Necessita reduzir a frequência (grave).
     - **Abaixo da nota alvo**: Necessita aumentar a frequência (agudo).

---

## 🌟 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

### Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das alterações:
   ```bash
   git commit -m "Adicionei minha nova feature"
   ```
4. Envie as alterações para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um pull request.

---

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 📧 Contato

- **Autor:** Fernando Nando
- **GitHub:** [@skylinenando](https://github.com/skylinenando)
- **E-mail:** skylinenando@example.com

---

Pronto para usar o Afinador Digital? 🌟

```plaintext
git clone https://github.com/skylinenando/afinador-digital.git
```

---

### 🖼️ Melhorias futuras

- Adicionar suporte para modos de afinação diferentes.
- Incluir feedback visual adicional (ex.: vibrações para dispositivos móveis).
- Implementar detecção de várias oitavas e escalas customizáveis.

---

Basta salvar este conteúdo como `README.md` no repositório do GitHub. Se desejar, adicione imagens ou links úteis para demonstrar o projeto. 🚀
