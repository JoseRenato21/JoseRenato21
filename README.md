<h1 align="center">José Renato Araújo Pereira</h1>

<p align="center">
  Engenharia de Computação · CEFET/RJ<br>
  <b>Inteligência artificial aplicada</b> · Dados · Redes e segurança
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jose-renato-araujo-pereira-1862912bcc3"><img src="https://img.shields.io/badge/LinkedIn-jose--renato--araujo--pereira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://joserenato21.github.io/portfolio/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-joserenato21.github.io-0f6b5c?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfólio"></a>
  <a href="mailto:jsernt21@gmail.com"><img src="https://img.shields.io/badge/E--mail-jsernt21@gmail.com-1a2330?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

<br>

Estudo e construo sistemas que colocam modelos de linguagem para trabalhar de verdade: servir e comparar modelos locais, avaliá-los contra adversários e sustentá-los com dados confiáveis e infraestrutura segura. Procuro estágio em inteligência artificial.

## Em destaque: iniciação científica

**Honeypots adaptativos contra atacantes de IA.** Um honeypot SSH cujas respostas são geradas por LLMs e que aprende sozinho o que o denuncia. Duas IAs trabalham em ciclo fechado: o **Catatau** controla o honeypot nas camadas de protocolo e de shell, e a **Zé ComeIA** analisa os logs e devolve correções.

```mermaid
flowchart LR
    A["Atacante de IA<br/>(Rouxii)"] --> B["Honeypot<br/>Cowrie"]
    B --> C[("Logs")]
    C --> D["Zé ComeIA<br/>supervisora"]
    D -->|"correções"| E["Catatau<br/>LLM do honeypot"]
    E -->|"protocolo e shell"| B
```

- **Modelos locais** servidos com Ollama, comparando Llama 3.2 3B, Qwen3 e modelos de 7 a 14 bilhões de parâmetros quantizados
- **Fine-tuning com QLoRA** para especializar um modelo pequeno, e uma família de Catatau, um por protocolo
- **Avaliação** com atacantes de IA publicados em pesquisa, medindo a taxa de detecção ao longo dos ciclos

<br>

## Projetos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/JoseRenato21/movie-etl-pipeline">movie-etl-pipeline</a></h3>
      Pipeline ELT em arquitetura medalhão (Bronze, Silver e Gold), com transformações em dbt e testes de qualidade dos dados.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
      <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/JoseRenato21/Projeto_Portal_Academico">Projeto_Portal_Academico</a></h3>
      Gestão de cursos, turmas, inscrições e notas, com as regras de negócio em triggers do banco, API em camadas e interface em React.<br><br>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
      <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/JoseRenato21/booking-ddd-clean-arch-python">booking-ddd-clean-arch-python</a></h3>
      Reservas de hotel com Domain-Driven Design e Clean Architecture, com regras protegidas no domínio e 75 testes.<br><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
      <img src="https://img.shields.io/badge/DDD-1a2330?style=flat-square" alt="DDD">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/JoseRenato21/Jogo_Arkanoid_Assembly_Simp3">Jogo_Arkanoid_Assembly_Simp3</a></h3>
      Jogo de quebrar blocos inteiro em assembly, com interrupções, colisão e controle de memória em baixo nível.<br><br>
      <img src="https://img.shields.io/badge/Assembly-P3-1a2330?style=flat-square" alt="Assembly P3">
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/JoseRenato21/Puro-Malte-Estudos">Puro-Malte-Estudos</a></h3>
      Caderno de estudos de C, de variáveis a ponteiros, recursão e arquivos, com um exemplo compilável para cada tópico.<br><br>
      <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://raw.githubusercontent.com/JoseRenato21/Projeto_Portal_Academico/main/docs/screenshots/03-turmas-disponiveis.png" width="49%" alt="Portal Acadêmico: turmas disponíveis">
  <img src="https://raw.githubusercontent.com/JoseRenato21/Projeto_Portal_Academico/main/docs/screenshots/07-admin-usuarios.png" width="49%" alt="Portal Acadêmico: administração de usuários">
</p>

## Tecnologias

<p>
  <img src="https://skillicons.dev/icons?i=python,c,js,nodejs,react,postgres,mysql,docker,linux,aws,azure,git&perline=12" alt="Tecnologias">
</p>

| Área | O que uso |
|------|-----------|
| **IA** | LLMs, Ollama, fine-tuning com QLoRA, agentes, avaliação de modelos |
| **Dados** | SQL, dbt, ELT e arquitetura medalhão, data lake (S3 e Athena) |
| **Redes** | Roteamento (OSPF, BGP), VLANs, SSH e túneis, OpenVPN, pfSense, Zabbix, Cisco IOS |
| **Segurança** | Suricata, iptables, honeypots, Kali Linux, Nmap, PKI e Zero Trust |

## Experiência e formação

**BTG Pactual · Summer Job em Tecnologia** (fev a jun de 2025). Automação da coleta de dados da B3, ingestão em data lake na AWS com consulta em SQL pelo Athena, aplicações em Python e React publicadas na Azure.

**CEFET/RJ · Engenharia de Computação** (2024.1 a 2028.2). Participação no CTF do CEFET/RJ.

**Certificações:** Fortinet NSE 1 e NSE 2 · Cisco CCNA em preparação (prova prevista para fevereiro de 2027)
