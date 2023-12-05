# CyberSec Phishing Challenge

# Phishing para captura de senhas do Facebook

Este documento fornece as instruções necessárias para conduzir um ataque de phishing para captura de email/senhas utilizando a ferramenta Setoolkit do Kali Linux. O desafio é parte do Santander Cybersecurity Bootcamp, desenvolvido pela DIO (Digital Innovation One).

**NOTA:** Este repositório e suas instruções são fornecidos exclusivamente para propósitos educacionais, sendo assim, utilizá-lo para atividades maliciosas é ilegal. O autor não se responsabiliza pelo mau uso das informações fornecidas.

## Ferramentas

- [Kali Linux](https://www.kali.org/)
- [setoolkit](https://github.com/trustedsec/social-engineer-toolkit)


## Preparando o Phishing no Kali Linux

1. **Obtendo Privilégios de Root:**
   - Abra o terminal e utilize o seguinte comando:

     ```bash
     sudo su
     ```

2. **Inicializando o Setoolkit:**
   - Execute o seguinte comando para inicializar o Setoolkit:

     ```bash
     setoolkit
     ```

3. **Selecionando o "Attack Type" (Tipo de Ataque):**
   - Selecione a partir do menu: **"1) Social-Engineering Attacks"**.


4. **Selecionando o "Attack Vector" (Vetor de Ataque):**
   - Selecione a partir do menu  **"2) Web Site Attack Vectors"**.


5. **Selecionando o "Attack Method" (Método de Ataque):**
   - Selecione a partir do menu **"3) Credential Harvester Attack Method"**.


6. **Selecionando o "Attack Method" (Método de Ataque):**
   - Selecione a partir do menu **"2) Site Cloner"**.


7. **Obtendo o endereço de máquina atacante:**
   - O endereço IP da máquina atacante aparece no prompt de comando, bastando apenas pressionar a tacla **"Enter"** para continuar.


8. **Endereço a ser clonado:**
   - No prompt de comando vai aparecer a fase: **"Enter the URL to clone:**
   - Digete http://www.facebook.com (Não esquece que tem que ser "HTTP" sem o "S".)

### Resutado

![credentials](https://github.com/Blind4rch3r/cybersecurity-desafio-phishing/assets/3162513/4de7e52a-9b67-44a5-bf40-e2bb4e6e794a)





