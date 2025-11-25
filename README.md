# 🔲 Gerador de QR Code

Um gerador de QR Code moderno e intuitivo, desenvolvido com HTML, CSS e JavaScript puro. Crie QR codes personalizados em segundos!

![image](https://github.com/eumatoliveira/Gerador-de-QR-Code/blob/main/Screenshot_3.png)

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/CSS-3-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)

## ✨ Funcionalidades

- ✅ **Geração Instantânea**: Crie QR codes em tempo real
- 🎨 **Personalização de Cores**: Escolha entre 5 cores diferentes
- 📐 **Múltiplos Tamanhos**: Pequeno (128px), Médio (256px) e Grande (512px)
- 💾 **Download em PNG**: Baixe seus QR codes em alta qualidade
- ⌨️ **Atalho de Teclado**: Pressione Enter para gerar rapidamente
- 📱 **Design Responsivo**: Funciona perfeitamente em dispositivos móveis
- 🎭 **Interface Moderna**: Visual clean com gradientes e animações suaves

## 🚀 Como Usar

1. **Clone ou baixe o projeto**
   ```bash
   git clone https://github.com/seu-usuario/gerador-qrcode.git
   ```

2. **Abra o arquivo HTML**
   - Navegue até a pasta do projeto
   - Abra o arquivo `index.html` em seu navegador preferido
   - Não requer instalação ou servidor local!

3. **Gere seu QR Code**
   - Digite o texto ou URL no campo de entrada
   - Selecione o tamanho desejado
   - Escolha a cor
   - Clique em "Gerar QR Code" ou pressione Enter
   - Baixe o resultado clicando no botão verde

## 📋 Exemplos de Uso

### URLs
```
https://www.exemplo.com.br
```

### Texto
```
Olá! Este é meu QR Code personalizado
```

### E-mail
```
mailto:seuemail@exemplo.com
```

### Telefone
```
tel:+5511999999999
```

### Wi-Fi
```
WIFI:T:WPA;S:NomeDaRede;P:SenhaWiFi;;
```

### vCard (Contato)
```
BEGIN:VCARD
VERSION:3.0
FN:Seu Nome
TEL:+5511999999999
EMAIL:email@exemplo.com
END:VCARD
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com gradientes e animações
- **JavaScript (ES6)**: Lógica de geração e interatividade
- **QRCode.js**: Biblioteca para geração de QR codes ([CDN](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js))

## 📦 Estrutura do Projeto

```
gerador-qrcode/
│
├── index.html          # Arquivo principal (standalone)
├── README.md           # Documentação
└── screenshots/        # Capturas de tela (opcional)
```

## 🎨 Paleta de Cores

| Cor | Hex Code | Uso |
|-----|----------|-----|
| Preto | `#000000` | Padrão clássico |
| Roxo | `#667eea` | Moderno e vibrante |
| Verde | `#11998e` | Fresh e clean |
| Vermelho | `#e74c3c` | Destaque importante |
| Azul | `#3498db` | Profissional |

## 🔧 Personalização

### Adicionar Novas Cores

Edite o elemento `<select id="color">` no HTML:

```html
<option value="HEXCODE">Nome da Cor</option>
```

### Adicionar Novos Tamanhos

Edite o elemento `<select id="size">` no HTML:

```html
<option value="PIXELS">Descrição (PXpx)</option>
```

### Modificar o Tema

Ajuste as variáveis CSS no bloco `<style>`:

```css
background: linear-gradient(135deg, #SUA_COR1 0%, #SUA_COR2 100%);
```

## 📱 Compatibilidade

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+
- ✅ Navegadores móveis (iOS Safari, Chrome Mobile)

## 🐛 Resolução de Problemas

### QR Code não está sendo gerado
- Verifique se você digitou algum conteúdo
- Certifique-se de que o JavaScript está habilitado
- Verifique a conexão com a CDN do QRCode.js

### Download não funciona
- Alguns navegadores podem bloquear downloads automáticos
- Verifique as configurações de permissão do seu navegador

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ por [Seu Nome]

## 🌟 Agradecimentos

- [QRCode.js](https://github.com/davidshimjs/qrcodejs) pela excelente biblioteca
- Comunidade open source por inspirações e feedback

## 📞 Contato

- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [Seu Nome](https://linkedin.com/in/seu-perfil)
- Email: seuemail@exemplo.com

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
