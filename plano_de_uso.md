# Plano de Uso Multiusuário - Condomínio CECH (Escala: 200 Usuários)

Este documento define as regras de partilha e gestão da infraestrutura tecnológica adquirida através do Edital 01/2026 para os laboratórios Viva Vox, GEMADELE, ELL, DC e Lab Técnico.

### 1. Modelo de Atendimento em Larga Escala
Considerando o público-alvo de 200 utilizadores, o condomínio opera num modelo híbrido:
* **Recursos Locais (25 Notebooks):** Destinados a atividades que exigem presença física ou mobilidade dentro do campus.
* **Recursos Remotos (Servidores HPC):** A infraestrutura principal corre em containers Docker, permitindo que a maioria dos utilizadores trabalhe de forma remota via BYOD (Bring Your Own Device).

### 2. Regras para os Notebooks
* **Empréstimo de Curta Duração:** Os 25 notebooks podem ser requisitados para aulas ou recolha de dados por um período máximo de 4 horas.
* **Pernoite:** É proibido levar os notebooks para fora do campus, salvo autorização especial do Coordenador (Alan Jônatas).
* **Armário de Carga:** Ao final de cada turno, os equipamentos devem ser devolvidos ao "Charge Cart" para recarga e integridade do hardware.

### 3. Gestão de Recursos dos Servidores
* **Quotas de Processamento:** Para garantir que todos os 200 utilizadores tenham acesso, o servidor Docker implementa limites de CPU e RAM por container.
* **Prioridade de Pesquisa:** Processamentos pesados (Big Data/IA) devem ser agendados com 48h de antecedência através do sistema de tickets do condomínio.

### 4. Sistema de Agendamento
* A reserva dos notebooks e das estações fixas é feita através de um calendário partilhado (Google Calendar).
* Cada laboratório parceiro tem direito a uma reserva prioritária de 5 equipamentos em horários fixos de reuniões de grupo.

### 5. Manutenção e Segurança
* **Backup:** Cada utilizador é responsável pelos seus dados. O servidor realizará limpezas automáticas de ficheiros temporários semanalmente.
* **Responsabilidade:** Danos causados por má utilização serão reportados ao Tesoureiro (Wagner Mota) para as devidas providências administrativas conforme as normas da UFS.
