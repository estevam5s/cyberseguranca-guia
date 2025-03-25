# Documentação Linux e Cybersegurança

Este projeto contém uma documentação interativa completa sobre comandos Linux e ferramentas de cybersegurança, com foco especial em ferramentas do Kali Linux.

## 📋 Conteúdo

A documentação está dividida em várias seções principais:

1. **Gerenciamento de Discos no Linux**
   - Partições e sistemas de arquivos
   - Formatação e montagem
   - Ferramentas como fdisk, parted, LVM
   - RAID e recuperação de dados

2. **Comandos Linux**
   - Comandos básicos (navegação, manipulação de arquivos)
   - Gerenciamento de usuários e permissões
   - Processos e rede
   - Comandos avançados (processamento de texto, compressão)

3. **Shell Scripting**
   - Bash scripting
   - Variáveis e condicionais
   - Loops e funções
   - Exemplos práticos

4. **Ferramentas de Cybersegurança**
   - Reconhecimento e scanners
   - Frameworks de exploits
   - Cracking de senhas
   - Análise de tráfego
   - Segurança wireless
   - Engenharia social

5. **Ferramentas Avançadas (Detalhadas)**
   - Metasploit Framework
   - Nmap avançado
   - Wireshark
   - Hydra

## 🚀 Características

- **Interface web interativa** com design moderno e responsivo
- **Tema claro/escuro** persistente usando localStorage
- **Barra de progresso** para acompanhar a leitura
- **Busca em tempo real** para encontrar comandos e ferramentas rapidamente
- **Comandos copiáveis** com um clique
- **Navegação intuitiva** com menu lateral e botão "voltar ao topo"
- **Exemplos práticos** de uso para cada ferramenta
- **Visualizações e tabelas comparativas** para facilitar o entendimento
- **Compatibilidade mobile** com menu adaptável

## 🛠️ Estrutura de Arquivos

```
.
├── README.md                       # Este arquivo
├── index.html                      # Página principal com gerenciamento de discos Linux
├── index2.html                     # Continuação do gerenciamento de discos 
├── index3.html                     # Seção final de gerenciamento de discos
├── linux-commands.html             # Documentação de comandos Linux (básicos e avançados)
├── linux-commands-continuation.html # Continuação de comandos Linux
├── linux-commands-cybersec.html    # Ferramentas de cybersegurança e scripts
├── linux-commands-cybersec-final.html # Metasploit, Nmap e outras ferramentas avançadas
├── linux-commands-final-end.html   # Wireshark, Hydra e finalização
├── assets/
│   ├── css/
│   │   └── styles.css              # Estilos CSS para todas as páginas
│   └── js/
│       └── scripts.js              # Código JavaScript para funcionalidades interativas
└── images/                         # Imagens e ícones utilizados na documentação
```

## 🔧 Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/linux-cybersec-docs.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd linux-cybersec-docs
   ```

3. Abra qualquer um dos arquivos HTML em seu navegador:
   ```bash
   # Linux/macOS
   open index.html
   
   # Windows
   start index.html
   ```

Alternativamente, você pode usar qualquer servidor web para servir os arquivos:

```bash
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve
```

## 📚 Utilização

### Navegação

- Use o menu lateral para navegar entre as diferentes seções
- A barra de pesquisa permite filtrar conteúdo rapidamente
- Em dispositivos móveis, toque no ícone de menu (☰) para abrir a navegação
- Use o botão "↑" no canto inferior direito para voltar ao topo

### Temas

- Alterne entre o tema claro e escuro usando o switch no cabeçalho
- Sua preferência de tema será lembrada para visitas futuras

### Comandos

- Clique no botão "Copiar" ao lado de qualquer comando para copiá-lo para a área de transferência
- Os comandos são formatados para fácil leitura com syntax highlighting

### Exemplos Práticos

- Cada ferramenta inclui exemplos práticos de uso
- Siga os exemplos passo a passo para aprendizado efetivo

## ⚠️ Aviso de Segurança

Esta documentação contém informações sobre ferramentas de segurança que podem ser usadas para testes de penetração e outras atividades de segurança. Lembre-se:

- Use estas ferramentas apenas em sistemas para os quais você tem autorização explícita para testar
- A utilização destas ferramentas em sistemas sem permissão pode ser ilegal
- Esta documentação foi criada para fins educacionais e de aprendizado ético
- Os autores não são responsáveis pelo uso indevido das informações contidas aqui

## 🔄 Mantendo Atualizado

As ferramentas e comandos do Linux e Kali Linux estão em constante evolução. Para manter esta documentação atualizada:

1. Verifique periodicamente as páginas dos projetos oficiais:
   - [Kali Linux](https://www.kali.org/)
   - [Linux Documentation Project](https://tldp.org/)
   - [Offensive Security](https://www.offensive-security.com/)

2. Para contribuir com atualizações:
   - Faça um fork deste repositório
   - Crie uma branch para sua atualização (`git checkout -b feature/nova-ferramenta`)
   - Faça commit das alterações (`git commit -m 'Adiciona documentação para nova ferramenta'`)
   - Envie para o branch (`git push origin feature/nova-ferramenta`)
   - Abra um Pull Request

## 📝 Personalização

### Adicionando Novas Ferramentas

Para adicionar uma nova ferramenta à documentação:

1. Identifique a seção apropriada no arquivo HTML relevante
2. Use a estrutura de cards existente como template:
   ```html
   <div class="card">
       <div class="card-header">Nome da Ferramenta <span class="tool-category">CATEGORIA</span></div>
       <p>Breve descrição da ferramenta.</p>
       <div class="command">
           <code>comando de exemplo</code>
           <button class="copy-btn" data-command="comando de exemplo">Copiar</button>
       </div>
       <p>Características principais:</p>
       <ul>
           <li>Característica 1</li>
           <li>Característica 2</li>
           <li>Característica 3</li>
       </ul>
   </div>
   ```

3. Adicione a ferramenta ao menu de navegação no arquivo HTML

### Modificando o Estilo

Os estilos estão definidos no arquivo CSS e podem ser personalizados conforme necessário:

- Variáveis de cor para temas claro/escuro
- Tamanho de fonte e espaçamento
- Esquema de cores para categorias de ferramentas
- Layout responsivo para diferentes dispositivos

## 📄 Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👥 Contribuidores

- [Seu Nome](https://github.com/seu-usuario) - Criador e mantenedor principal

## 🙏 Agradecimentos

- O Projeto foi inspirado nas documentações oficiais do Kali Linux e ferramentas de código aberto
- Agradecimentos especiais à comunidade de segurança de código aberto pelo desenvolvimento das ferramentas documentadas

---

Se você encontrar algum problema ou tiver sugestões para melhorar esta documentação, por favor, abra uma issue no repositório do GitHub.
