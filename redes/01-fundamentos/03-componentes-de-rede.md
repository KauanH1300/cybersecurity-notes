# Componentes de Rede

Os componentes de rede são os dispositivos e tecnologias responsáveis pela comunicação entre equipamentos dentro de uma rede.

Cada componente possui uma função específica para permitir o envio, recebimento e controle de dados.

---

# Clientes

Um cliente é um dispositivo que acessa serviços ou recursos disponibilizados por outro dispositivo na rede.

Clientes normalmente realizam requisições para servidores.

## Exemplos

- Computadores
- Celulares
- Tablets
- Smart TVs

## Observações

- Qualquer cliente pode se tornar um servidor dependendo da situação.
- Um computador pode atuar como cliente e servidor ao mesmo tempo.

### Exemplo prático

Quando um usuário acessa um site:
- O navegador funciona como cliente
- O servidor web responde com os dados da página

---

# Servidores

Um servidor é um dispositivo responsável por fornecer serviços, recursos ou dados para outros dispositivos da rede.

Os servidores ficam aguardando conexões e requisições de clientes.

## Exemplos de servidores

- Servidor Web
- Servidor DNS
- Servidor DHCP
- Servidor de Arquivos
- Servidor de E-mail

### Exemplo prático

Ao acessar o YouTube:
- Seu dispositivo envia uma requisição
- Os servidores do YouTube respondem enviando os vídeos e informações do site

---

# Switches

Um switch é um dispositivo utilizado para conectar dispositivos dentro de uma rede local (LAN).

Ele encaminha os dados para o dispositivo correto utilizando endereços MAC.

## Funções do switch

- Conectar dispositivos
- Organizar a comunicação da rede
- Reduzir tráfego desnecessário

## Exemplos de dispositivos conectados ao switch

- Computadores
- Impressoras
- Access Points
- Servidores

### Observação

Switches normalmente operam na Camada 2 do modelo OSI.

---

# Roteadores (Routers)

Um roteador é um dispositivo responsável por conectar diferentes redes.

Ele encaminha pacotes utilizando endereços IP.

## Funções do roteador

- Conectar redes diferentes
- Compartilhar acesso à internet
- Definir rotas para os pacotes

### Exemplo prático

O roteador da sua casa:
- Conecta sua rede doméstica à internet
- Permite que vários dispositivos utilizem a mesma conexão

---

# Firewalls

Um firewall é um dispositivo ou software responsável por monitorar e controlar o tráfego da rede com base em regras de segurança.

Seu objetivo é proteger dispositivos e redes contra acessos não autorizados.

## Funções do firewall

- Filtrar tráfego
- Bloquear conexões maliciosas
- Permitir ou negar acessos
- Monitorar comunicações

## Tipos de firewall:

### Firewall de software

É um firewall instalado diretamente em um sistema operacional.

Ele monitora e controla as conexões do próprio dispositivo.

#### Exemplo

- Windows Defender Firewall
- UFW no Linux

---

### Firewall de hardware

É um dispositivo físico dedicado à proteção da rede.

Normalmente fica localizado entre a rede interna e a internet.

#### Características

- Protege múltiplos dispositivos ao mesmo tempo
- Muito utilizado em empresas

---

### Stateful Firewall

Monitora o estado das conexões da rede.

Ele consegue identificar:
- conexões legítimas
- sessões ativas
- tráfego suspeito

Isso permite decisões mais inteligentes do que apenas analisar pacotes isolados.

---

### Next-Generation Firewall (NGFW)

É um firewall mais avançado que combina funções tradicionais com recursos extras de segurança.

#### Pode incluir

- IDS/IPS
- inspeção profunda de pacotes (DPI)
- filtragem de aplicações
- controle de usuários
- detecção de ameaças

### Observação

Firewalls podem ser posicionados:
- Entre redes internas e externas
- Dentro da própria rede para segmentação

---
