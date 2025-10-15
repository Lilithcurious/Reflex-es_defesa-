# Reflexoes defesa

# Simulação de Malwares em Python

Este repositório contém uma simulação educacional de malwares (Ransomware e Keylogger) desenvolvida com Python, criada para fins de aprendizado em um ambiente controlado. O projeto visa compreender o funcionamento dessas ameaças digitais, suas vulnerabilidades e estratégias de defesa, conforme proposto no curso.

## Objetivos de Aprendizado
- Compreender o funcionamento prático de Ransomware e Keylogger.
- Identificar como esses malwares exploram vulnerabilidades e erros humanos.
- Aprender a programar scripts simples em Python para simular ataques em ambiente controlado.
- Refletir sobre estratégias de prevenção e defesa contra malwares.
- Documentar os experimentos e utilizar o GitHub como portfólio técnico.

## Descrição do Projeto
O projeto simula dois tipos de malwares:
- **Ransomware Simulado**: Criaria arquivos de teste, implementaria um script para criptografar e descriptografar dados, e geraria uma mensagem de resgate. O estudo focou em como o Ransomware sequestra dados e como a criptografia (usando a biblioteca Fernet) pode ser revertida.
- **Keylogger Simulado**: Envolveria a captura de teclas em um arquivo .txt, com foco em torná-lo furtivo e enviar logs por e-mail (usando smtplib). O aprendizado incluiu como esses malwares monitoram atividades do usuário.
- **Reflexão sobre Defesa**: Documenta medidas como antivírus, firewall, sandboxing e conscientização do usuário para mitigar riscos.

## Progresso e Reflexões
- **Estudos**: Revisei os slides do curso e a documentação oficial de Python, Cryptography (Fernet), pynput e smtplib. Entendi que o Ransomware usa criptografia simétrica para bloquear dados, enquanto o Keylogger captura entradas do teclado.
- **Reflexões**: Percebi que vulnerabilidades humanas (ex.: phishing) e técnicas (ex.: sistemas desatualizados) são exploradas por esses malwares. Medidas como backups regulares e uso de antivírus são cruciais para prevenção.
- **Dificuldades**: Sem implementar, imaginei que configurar o envio de e-mails no Keylogger poderia ser complexo devido à autenticação SMTP.

## Estrutura do Repositório
- `README.md`: Este arquivo com a documentação do projeto.
- `reflexoes_defesa.md`: Documento com reflexões sobre defesa (a ser criado).
- `/images` (opcional): Pasta para capturas de tela de estudos ou simulações futuras.

## Como Usar
Este projeto é atualmente uma documentação. Para implementação futura, seria necessário:
- Instalar dependências: `pip install cryptography pynput`.
- Executar scripts: `python3 ransomware_simulado.py` ou `python3 keylogger_simulado.py`.

## Disclaimer
Este é um projeto educacional. Não utilize os códigos ou conceitos para fins maliciosos.

## Referências
- [Documentação Oficial do Python](https://docs.python.org/3/)
- [Cryptography (Fernet)](https://cryptography.io/en/latest/fernet/)
- [pynput](https://pynput.readthedocs.io/)
- [smtplib](https://docs.python.org/3/library/smtplib.html)
- Slides do curso: Simulando um Malware de Captura de Dados Simples em Python e Aprendendo a se Proteger
