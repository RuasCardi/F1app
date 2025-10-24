# 🏎️ F1 360 - App Completo de Fórmula 1 2025

Aplicação web moderna e interativa sobre a Fórmula 1 com dados reais, visualização 3D e design oficial.

![Version](https://img.shields.io/badge/version-2.0-red?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

## ✨ Funcionalidades

### 🏁 6 Telas Completas

1. **🏆 Equipes** - Cards com logos oficiais de todas as 10 equipes 2025
2. **🏎️ Visualizador 3D** - Carros em 3D com rotação 360° interativa
3. **👨‍✈️ Pilotos** - Galeria completa dos 20 pilotos com fotos oficiais
4. **📊 Classificações** - Standings em tempo real de pilotos e construtores
5. **📅 Calendário** - Todas as corridas da temporada com status
6. **🏁 Pistas** - Informações detalhadas de todos os circuitos

### 🎯 Recursos Principais

- ✅ **Logos Oficiais Formula1.com** - Escudos autênticos de todas as equipes
- ✅ **Fotos Oficiais dos Pilotos** - Imagens reais da Formula1.com
- ✅ **Estatísticas Completas** - Clique em qualquer piloto para ver:
  - 🏆 Campeonatos mundiais
  - 🏁 Total de vitórias
  - 🥇 Pódios conquistados
  - ⚡ Pole positions
  - ⭐ Pontos acumulados
  - 📅 Corridas disputadas
- ✅ **Carros 3D Interativos** - Arraste para girar 360° com o mouse
- ✅ **API Gratuita Jolpica F1** - Dados reais e atualizados
- ✅ **Design Profissional** - Interface limpa e moderna
- ✅ **100% Responsivo** - Funciona em mobile, tablet e desktop

## 🚀 Como Usar

### Passo 1: Clone ou baixe o projeto

### Passo 2: Abra o terminal na pasta do projeto

### Passo 3: Inicie o servidor local
```bash
python -m http.server 8080
```

### Passo 4: Abra no navegador
```
http://localhost:8080
```

Pronto! 🎉 O app estará rodando!

## 📋 Equipes e Pilotos (Temporada 2025)

### 🔵 Red Bull Racing (#3671C6)
- **Max Verstappen** (#1) 🇳🇱
- **Liam Lawson** (#30) 🇳🇿

### 🔴 Ferrari (#E8002D)
- **Charles Leclerc** (#16) 🇲🇨
- **Lewis Hamilton** (#44) 🇬🇧

### 🟠 McLaren (#FF8000)
- **Lando Norris** (#4) 🇬🇧
- **Oscar Piastri** (#81) 🇦🇺

### 🩵 Mercedes (#27F4D2)
- **George Russell** (#63) 🇬🇧
- **Andrea Kimi Antonelli** (#12) 🇮🇹

### 🟢 Aston Martin (#229971)
- **Fernando Alonso** (#14) 🇪🇸
- **Lance Stroll** (#18) 🇨🇦

### 🩷 Alpine (#FF87BC)
- **Pierre Gasly** (#10) 🇫🇷
- **Jack Doohan** (#7) 🇦🇺

### ⚪ Haas F1 Team (#B6BABD)
- **Esteban Ocon** (#31) 🇫🇷
- **Oliver Bearman** (#87) 🇬🇧

### 🟢 Kick Sauber (#52E252)
- **Nico Hulkenberg** (#27) 🇩🇪
- **Gabriel Bortoleto** (#5) 🇧🇷

### 🔵 Williams (#64C4FF)
- **Alexander Albon** (#23) 🇹🇭
- **Carlos Sainz** (#55) 🇪🇸

### 🔵 RB F1 Team / Racing Bulls (#6692FF)
- **Yuki Tsunoda** (#22) 🇯🇵
- **Liam Lawson** (#30) 🇳🇿

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica e moderna
- **CSS3** - Design responsivo com animações
- **JavaScript ES6+** - Lógica assíncrona e eventos

### Bibliotecas
- **Three.js r128** - Renderização 3D WebGL
- **OrbitControls** - Interação com modelos 3D
- **Font Awesome 6.4** - Ícones modernos

### APIs
- **Jolpica F1 API** - Dados oficiais da F1 (gratuita)
- **OpenF1 API** - Telemetria e dados complementares

### Fontes
- **Rajdhani** (900) - Títulos impactantes
- **Inter** (400-700) - Corpo de texto

## 📡 APIs Integradas

### 1️⃣ Jolpica F1 API (Principal)
```javascript
https://api.jolpi.ca/ergast/f1/
```

**Endpoints utilizados:**
- `/current/driverStandings.json` - Classificação de pilotos
- `/current/constructorStandings.json` - Classificação de equipes
- `/current.json` - Calendário de corridas
- `/drivers/{code}.json` - Dados do piloto
- `/drivers/{id}/results.json` - Resultados históricos

**Funcionalidades:**
- ✅ Dados históricos completos desde 1950
- ✅ Classificações atualizadas
- ✅ Estatísticas de pilotos e equipes
- ✅ Calendário de corridas
- ✅ Gratuita e sem necessidade de API key

### 2️⃣ OpenF1 API (Complementar)
```javascript
https://api.openf1.org/v1/
```

**Funcionalidades futuras:**
- Telemetria em tempo real
- Dados de voltas
- Posicionamento ao vivo

### 3️⃣ Formula1.com CDN
```javascript
https://www.formula1.com/content/dam/fom-website/
```

**Recursos:**
- Logos oficiais das equipes
- Fotos oficiais dos pilotos
- Imagens de alta qualidade

## 🎮 Interatividade

### Navegação Principal
1. **Home** - Scroll horizontal pelos cards das equipes
2. **Clique na equipe** - Abre visualizador 3D do carro
3. **"Ver Pilotos"** - Mostra galeria de pilotos da equipe
4. **Clique no piloto** - Abre modal com estatísticas completas
5. **Menu superior** - Acesso direto a todas as telas

### Modal de Estatísticas do Piloto
- 📸 Foto oficial do piloto
- 🔢 Número e nacionalidade
- 🏆 Grid com 6 estatísticas principais
- 🎨 Design personalizado com cores da equipe
- ❌ Feche clicando no X ou fora do modal

### Visualizador 3D
- **🖱️ Arraste** - Gire o carro 360° em qualquer direção
- **🔍 Scroll** - Zoom in/out
- **🎨 Cores** - Cada carro usa a cor oficial da equipe
- **💡 Iluminação** - Sistema de luzes realista
- **⚙️ Modelos** - Carros placeholder (prontos para .glb)

### Classificações
- 🔄 Abas alternando entre Pilotos e Construtores
- 🏆 Posição, nome, equipe e pontos
- 🎨 Logos das equipes em cada linha
- 📊 Dados atualizados da API

### Calendário
- 🔄 Filtros: **Todas** / **Passadas** / **Futuras**
- 🏁 Nome do GP, circuito e data
- ✅ Status visual (completada/futura)
- 🌍 Informações completas de cada corrida

## 📱 Responsividade

### Desktop (> 768px)
- Layout completo com todas as funcionalidades
- Grid de 3 estatísticas por linha no modal
- Visualizador 3D em alta resolução

### Tablet (480px - 768px)
- Cards de equipes otimizados
- Grid de 2 estatísticas por linha
- Interface touch-friendly

### Mobile (< 480px)
- Scroll horizontal aprimorado
- Modal em tela cheia
- Botões maiores para toque
- Visualizador 3D responsivo

## 🎨 Paleta de Cores Oficial

| Equipe | Cor | Hex | RGB |
|--------|-----|-----|-----|
| Red Bull Racing | Azul Racing | #3671C6 | 54, 113, 198 |
| Ferrari | Vermelho Rosso | #E8002D | 232, 0, 45 |
| McLaren | Laranja Papaia | #FF8000 | 255, 128, 0 |
| Mercedes | Verde Petronas | #27F4D2 | 39, 244, 210 |
| Aston Martin | Verde Racing | #229971 | 34, 153, 113 |
| Alpine | Rosa | #FF87BC | 255, 135, 188 |
| Haas F1 | Prata | #B6BABD | 182, 186, 189 |
| Kick Sauber | Verde | #52E252 | 82, 226, 82 |
| Williams | Azul | #64C4FF | 100, 196, 255 |

## 📊 Estrutura de Arquivos

```
f1/
├── index.html          # Estrutura HTML com 5 telas
├── style.css           # Estilos modernos (~1800 linhas)
├── script.js           # Lógica JavaScript (~1000 linhas)
├── README.md           # Este arquivo
├── package.json        # Metadados do projeto
└── .gitignore          # Arquivos ignorados pelo Git
```

### Principais Componentes

**index.html:**
- Header com logo e título
- Menu de navegação
- 5 screens (teams, car, pilots, standings, calendar)
- Modal de estatísticas do piloto
- CDNs do Three.js e Font Awesome

**style.css:**
- Variáveis CSS para cores das equipes
- Sistema de grid responsivo
- Animações e transições
- Estilos do modal
- Media queries

**script.js:**
- Array `teams2025` com todos os dados
- Funções de renderização
- Sistema de navegação
- Integração com APIs
- Visualizador 3D Three.js
- Modal de estatísticas

## 🔮 Roadmap - Próximas Melhorias

### Curto Prazo
- [ ] Modelos 3D reais (.glb) dos carros
- [ ] Animação de comemoração de vitórias
- [ ] Loading spinner durante chamadas de API
- [ ] Cache de dados da API no localStorage

### Médio Prazo
- [ ] Comparação lado a lado entre 2 pilotos
- [ ] Gráficos de evolução temporal (Chart.js)
- [ ] Modo escuro/claro toggle
- [ ] Filtros avançados no calendário

### Longo Prazo
- [ ] Notificações de corridas ao vivo
- [ ] Integração com telemetria em tempo real
- [ ] Sistema de favoritos
- [ ] PWA (Progressive Web App)
- [ ] Compartilhamento social
- [ ] Multi-idioma (PT/EN/ES)

## 🐛 Problemas Conhecidos

- ⚠️ Alguns pilotos novatos podem não ter estatísticas completas na API
- ⚠️ Carros 3D são placeholders (aguardando modelos .glb reais)
- ⚠️ API pode ter delay de alguns minutos após corridas
- ⚠️ Logos da F1.com podem mudar URLs (cache recomendado)

## 💡 Como Contribuir

1. Fork o projeto
2. Crie uma branch (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Add: Nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📄 Licença

Este é um projeto educacional criado para fins de aprendizado.

**Aviso Legal:**
- Logos, fotos e marcas são propriedade da Formula 1, FIA e equipes respectivas
- Este projeto não é afiliado oficialmente à Formula 1
- Use apenas para fins educacionais e não comerciais

## 👨‍💻 Autor

Desenvolvido com ❤️ e ☕ por um fã de Fórmula 1!

---

## 🎯 Demonstração

### Tela de Equipes
![Equipes](https://img.shields.io/badge/Tela-Equipes-red)
- Scroll horizontal com 9 cards
- Logos oficiais de alta qualidade
- Cores personalizadas por equipe

### Visualizador 3D
![3D Viewer](https://img.shields.io/badge/Tela-3D_Viewer-blue)
- Carro 3D interativo
- Rotação 360° com mouse
- Zoom in/out

### Modal de Piloto
![Modal Piloto](https://img.shields.io/badge/Tela-Estatísticas-green)
- Foto oficial
- 6 estatísticas principais
- Design com cores da equipe

---

**⚡ Dica:** Para melhor experiência, use navegadores modernos como Chrome, Firefox ou Edge!

**🏁 Aproveite o F1 360 e boa corrida!**
