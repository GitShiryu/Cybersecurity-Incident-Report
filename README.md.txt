# DNS Incident Analysis - Google Cybersecurity Certificate

## 🚀 About the Project
This report documents the investigation of a security incident where users were unable to access the website `www.yummyrecipesforme.com` due to DNS resolution failures. The analysis was performed using `tcpdump` to capture and interpret network traffic, identifying UDP and ICMP packets with the error **"destination port unreachable"**.

## 🔍 Technical Context
- **Protocols analyzed:** UDP (DNS) and ICMP.
- **Tool:** `tcpdump` for traffic capture.
- **Evidence:** DNS server (`203.0.113.2`) not responding on port 53.
- **Causes investigated:** Service outage, misconfiguration, or DoS attack.

## 📂 Repository Structure
- `relatorio_incidente_dns.pdf`: Full report in PDF.
- `README.md`: Project documentation (this file).

## 🛠 Demonstrated Skills
- Network traffic analysis with `tcpdump`.
- Interpretation of DNS and ICMP logs.
- Technical documentation of incidents.
- Incident response following structured frameworks.

## 📝 Methodology
1. **Traffic capture:** Using `tcpdump` to collect packets during website access attempts.
2. **Log analysis:** Identification of UDP packets (DNS queries) and ICMP responses with errors.
3. **Diagnosis:** Determining that the DNS server was not responding on port 53.
4. **Report:** Documentation of findings and possible causes.

## 🌐 References
- Activity from Module 3 (**"Connect and Protect: Networks and Network Security") of the [Google Cybersecurity Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity).

## 👨‍💻 Author
Eli Romulo de Araujo Martins - Cybersecurity Student | Google Career Certificates.

---


# Análise de Incidente de DNS - Google Cybersecurity Certificate

## 🚀 Sobre o Projeto
Este relatório documenta a investigação de um incidente de segurança onde usuários não conseguiam acessar o site `www.yummyrecipesforme.com` devido a falhas na resolução DNS. A análise foi realizada usando `tcpdump` para capturar e interpretar tráfego de rede, identificando pacotes UDP e ICMP com erro **"destination port unreachable"**.

## 🔍 Contexto Técnico
- **Protocolos analisados:** UDP (DNS) e ICMP.
- **Ferramenta:** `tcpdump` para captura de tráfego.
- **Evidência:** Servidor DNS (`203.0.113.2`) não respondendo na porta 53.
- **Causas investigadas:** Outage de serviço, misconfiguração ou ataque DoS.

## 📂 Estrutura do Repositório
- `relatorio_incidente_dns.pdf`: Relatório completo em PDF.
- `README.md`: Documentação do projeto (este arquivo).

## 🛠 Habilidades Demonstradas
- Análise de tráfego de rede com `tcpdump`.
- Interpretação de logs DNS e ICMP.
- Documentação técnica de incidentes.
- Resposta a incidentes seguindo frameworks estruturados.

## 📝 Metodologia
1. **Captura de tráfego:** Uso de `tcpdump` para coletar pacotes durante tentativas de acesso ao site.
2. **Análise de logs:** Identificação de pacotes UDP (consultas DNS) e respostas ICMP com erro.
3. **Diagnóstico:** Determinação de que o servidor DNS não estava respondendo na porta 53.
4. **Relatório:** Documentação das findings e causas possíveis.

## 🌐 Referências
- Atividade do Módulo 3 (**"Connect and Protect: Networks and Network Security"**) do [Google Cybersecurity Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity).

## 👨‍💻 Autor
Eli Romulo de Araujo Martins - Estudante de Cybersecurity | Google Career Certificates.

---