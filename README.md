# 🌦️ Controle Meteorológico — Coleta de Pontos e Coordenadas

Interface web estática desenvolvida para agilizar o registro georreferenciado de pontos de monitoramento meteorológico, integrando captura automática de coordenadas GPS diretamente com uma base de dados no Google Forms / Google Sheets.

🔗 **Acesse a aplicação:** [https://guilhermeviana2001.github.io/controle-metereologico/](https://guilhermeviana2001.github.io/controle-metereologico/)

---

## 📋 Sobre o Projeto

O objetivo desta aplicação é eliminar erros de digitação e agilizar o levantamento de dados em campo. A página utiliza a **Geolocation API** do navegador para obter latitude e longitude com precisão e realiza o envio assíncrono das informações para a planilha vinculada ao formulário, sem necessidade de backend dedicado.

### Principais Funcionalidades
- **Captura Automática de GPS:** Preenchimento rápido de latitude e longitude com exibição da margem de precisão em metros.
- **Padronização Numérica:** Conversão automática de vírgulas para pontos decimais antes do envio, garantindo compatibilidade com ferramentas de análise de dados e SIG (QGIS, GeoPandas, etc.).
- **Envio Assíncrono:** Submissão direta para o endpoint do Google Forms via `fetch` (`no-cors`), mantendo o usuário na mesma interface.
- **Design Responsivo:** Layout otimizado para uso tanto em dispositivos móveis (em campo) quanto em desktop.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** (Semântica e Geolocation API)
- **CSS3** (Variáveis CSS, Flexbox, Grid e Design Responsivo)
- **JavaScript (Vanilla)** (Manipulação de DOM, validação de dados e requisições assíncronas)
- **GitHub Pages** (Hospedagem estática via HTTPS)
- **Google Forms / Sheets** (Armazenamento e estruturação dos registros)
