# Next Facilities

Portal oficial de apresentação e distribuição dos aplicativos móveis corporativos **Next Facilities** para Android.

- 🌐 **URL de Produção:** [https://nextfacilities.inovagui.com.br/](https://nextfacilities.inovagui.com.br/)
- 📥 **Download APK Operacional:** [https://nextfacilities.inovagui.com.br/next-facilities-operacional-v1.0.0.apk](https://nextfacilities.inovagui.com.br/next-facilities-operacional-v1.0.0.apk) (97.5 MB)
- 📥 **Download APK Gestão:** [https://nextfacilities.inovagui.com.br/next-facilities-gestao-v1.0.0.apk](https://nextfacilities.inovagui.com.br/next-facilities-gestao-v1.0.0.apk) (101.8 MB)

---

## 📱 Aplicativos Disponíveis

### 1. Next Facilities Operacional (Colaborador & Supervisor)
- **Identificador:** `com.inovagui.nextfacilities`
- **Versão:** `1.0.0` (Build 1)
- **Arquivo:** `next-facilities-operacional-v1.0.0.apk` (~97.5 MB)
- **Público:** Colaboradores, Terceirizados e Supervisores de Campo
- **Módulos Principais:**
  - **Postos & Geofencing (A Maior Vantagem):** Cerca virtual inteligente por GPS ao redor de cada posto. O ponto e as rondas só são liberados dentro do raio autorizado, eliminando divergências e garantindo segurança jurídica.
  - **Tarefas Recorrentes & Extras (Segunda Maior Vantagem):** Rotinas geradas automaticamente ao bater o ponto de entrada no posto, com suporte ao recebimento de chamados e demandas extras em tempo real.
  - **Rondas Auditadas por Posto:** Roteiro físico de postos com validação por leitura de QR Code e satélite.
  - **Evidências Fotográficas:** Anexo de até 3 fotos por tarefa com metadados de data, hora e posto na nuvem.
  - **Assistente Next IA Operacional:** Suporte por comando de voz e texto para tirar dúvidas de escalas e rotinas.

### 2. Next Facilities Gestão & Coordenação (Coordenador, Gestor & Admin)
- **Identificador:** `com.inovagui.nextfacilities.gestao`
- **Versão:** `1.0.0` (Build 1)
- **Arquivo:** `next-facilities-gestao-v1.0.0.apk` (~101.8 MB)
- **Público:** Coordenadores de Área, Gestores de Contratos e Administradores
- **Módulos Principais:**
  - **Painel de Indicadores & Dashboards em Tempo Real:** Monitoramento macro e micro de turnos, faltas, postos em atendimento e status de tarefas.
  - **Parametrização de Postos & Geofencing:** Mapeamento geográfico de unidades e definição dos perímetros de segurança em metros.
  - **Gestão de Contratos e Alocação de Efetivo:** Controle de múltiplos clientes, filiais e escalas operacionais.
  - **Aprovação de Tarefas Extras:** Workflow ágil de autorização e despacho de demandas extras solicitadas pelos clientes.
  - **Auditoria de Evidências Fotográficas:** Visualização centralizada das fotos comprobatórias para prestação de contas.

---

## 🔑 Fluxo de Primeiro Acesso (Colaborador)

1. Abra o aplicativo na tela inicial de login.
2. Toque no link: **"É seu primeiro acesso? Clique aqui para entrar."**
3. Digite seu **CPF** previamente cadastrado pela coordenação/supervisão e clique em **Continuar**.
4. Preencha o **e-mail da conta** e defina a sua **senha** de acesso.
5. Sua conta estará ativada para acesso imediato.

---

## 📂 Estrutura do Projeto

```text
nextfacilities/
├── index.html                                 # Landing page oficial responsiva (Bootstrap Icons & Tailwind)
├── package.json                               # Configurações, versionamento e metadados dos pacotes
├── README.md                                  # Documentação completa
├── next-facilities-operacional-v1.0.0.apk     # APK Operacional v1.0.0 (97.5 MB)
├── next-facilities-gestao-v1.0.0.apk          # APK Gestão v1.0.0 (101.8 MB - hospedado na VPS)
└── assets/                                    # Recursos estáticos
    ├── icons/
    │   └── logo-icon.png                      # Ícone oficial / Favicon
    └── images/
        └── logo-vertical.png                  # Logotipo vertical da marca
```

---

## 🌐 Como Rodar Localmente

```bash
# Com Python
python -m http.server 8080

# Ou com Node.js
npx serve .
```

Acesse no navegador: `http://localhost:8080`