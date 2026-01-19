#   🏥 VIVA-BEM - Plataforma de Voluntariado para Saúde

O **VIVA-BEM** é uma Landing Page responsiva desenvolvida para conectar médicos e dentistas a projetos de voluntariado. O foco principal deste projeto foi aplicar conceitos avançados de **React**, **SASS** e **UX/UI**, garantindo uma experiência fluida para o utilizador final.

---

## ⚖️ Transição de Carreira: Do Direito à Tecnologia
Este projeto representa um marco na minha transição de carreira da advocacia para o desenvolvimento frontend. A minha bagagem jurídica contribui diretamente para a qualidade deste código através de:
- **Rigor Analítico:** Atenção minuciosa à sintaxe e lógica, minimizando erros e comportamentos inesperados.
- **Foco em Normas e Padrões:** Aplicação de boas práticas de semântica HTML e hierarquia de estilos (especificidade do CSS).
- **Resolução de Problemas:** Capacidade de interpretar documentações complexas e transformá-las em soluções lógicas.

---

## 🛠️ Tecnologias Utilizadas
- **React.js**: Modularização de componentes e gestão de estado.
- **SASS (SCSS Modules)**: Estilização isolada, escalável e uso de variáveis.
- **Lucide-React**: Biblioteca de ícones modernos e leves.
- **Git/GitHub**: Controlo de versão e gestão de deploy.

---

## 🚀 Desafios Técnicos e Soluções Práticas

### 1. Responsividade Fluida (Mobile-First)
**Desafio:** Adaptar um layout complexo de desktop para dispositivos móveis sem perder a hierarquia visual, especialmente no rodapé e no formulário.
**Solução:** Implementação de **Flexbox** com pontos de interrupção (`breakpoints`) estratégicos a partir de 900px.

**Resultado:** Interface 100% funcional em smartphones, tablets e desktops.

### 2. Gestão de Estado no Formulário
**Desafio:** Dar um feedback imediato ao utilizador após o envio do formulário para evitar envios duplicados.
**Solução:** Utilização do hook `useState` para criar um "Estado de Sucesso". Assim que o formulário é enviado, a interface é alterada condicionalmente para uma mensagem de agradecimento.
**Resultado:** Melhoria na experiência do utilizador (UX) e prevenção de redundância de dados.

### 3. Especificidade e Cascata no CSS
**Desafio:** Conflitos de estilos que impediam a exibição correta do menu hambúrguer no mobile.
**Solução:** Refatoração da lógica de seletores no SASS e aplicação de hierarquia de estilos, garantindo que as "leis" do CSS fossem aplicadas corretamente conforme o dispositivo.

---

## 📦 Como Executar o Projeto
1. Clone este repositório: `git clone https://github.com/GabrielaDiniiz/VIVA-BEM.git`
2. Instale as dependências: `npm install`
3. Inicie o servidor: `npm run start`

---

## 📬 Contacto
Desenvolvido por **Gabriela Diniz** [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriela-diniz-b94098360)
