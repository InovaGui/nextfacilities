# Next Facilities

Portal oficial de apresentação e distribuição do aplicativo móvel **Next Facilities** para Android (Colaboradores, Terceirizados e Supervisores).

- 🌐 **URL de Produção:** [https://nextfacilities.inovagui.com.br/](https://nextfacilities.inovagui.com.br/)
- 📥 **Download Direto do APK:** [https://nextfacilities.inovagui.com.br/next-facilities-operacional-v1.0.0.apk](https://nextfacilities.inovagui.com.br/next-facilities-operacional-v1.0.0.apk)

---

## 📱 Aplicativo Operacional

- **Identificador do Pacote:** `com.inovagui.nextfacilities`
- **Versão:** `1.0.0` (Build 1)
- **Arquivo Instalador:** `next-facilities-operacional-v1.0.0.apk`
- **Compatibilidade Mínima:** Android 8.0 (API 26) ou superior
- **Tamanho:** ~97.5 MB

### Principais Vantagens e Módulos em Campo:
1. **Postos de Trabalho & Geofencing (A Maior Vantagem):** Cerca virtual de segurança configurada por GPS em volta de cada posto de atendimento. O registro de ponto e as rondas só são liberados se o colaborador estiver fisicamente dentro do raio autorizado, eliminando fraudes e garantindo segurança jurídica.
2. **Tarefas Recorrentes & Extras (Segunda Maior Vantagem):** Geração automática de toda a rotina diária ao registrar o ponto de entrada no posto, além do recebimento e execução instantânea de demandas extras e emergenciais enviadas pela supervisão em tempo real.
3. **Rondas e Postos de Controle:** Conferência de postos físicos mapeados nas unidades com leitura de QR Code, verificação de satélite e horário.
4. **Evidências Fotográficas Auditáveis:** Registro comprobatório de até 3 fotos por tarefa ou ronda diretamente pelo app com dados de satélite e horário gravados.
5. **Assistente Next IA Operacional:** Suporte por áudio e texto para consulta de escalas, regras operacionais e orientações do contrato.

---

## 🔑 Fluxo de Primeiro Acesso

Todos os colaboradores são previamente cadastrados no sistema pela coordenação ou pelos supervisores:
1. Abra o aplicativo na tela inicial de login.
2. Toque no link: **"É seu primeiro acesso? Clique aqui para entrar."**
3. Digite seu **CPF** cadastrado e clique em **Continuar**.
4. Preencha o **e-mail da conta** e defina a sua **senha** de acesso.
5. Sua conta estará ativada para acesso imediato.

---

## 📂 Estrutura do Projeto

```text
nextfacilities/
├── index.html                                 # Landing page responsiva oficial de download
├── package.json                               # Configuração, versionamento e metadados
├── next-facilities-operacional-v1.0.0.apk     # Instalador oficial Android v1.0.0 (97.5 MB)
├── README.md                                  # Documentação do repositório
└── assets/                                    # Recursos estáticos organizados
    ├── icons/
    │   └── logo-icon.png                      # Ícone da marca Next Facilities (Favicon e avatares)
    └── images/
        └── logo-vertical.png                  # Logotipo vertical oficial
```

---

## 🌐 Como Rodar a Landing Page Localmente

Você pode abrir diretamente o arquivo `index.html` em qualquer navegador ou iniciar um servidor local:

```bash
# Com Python
python -m http.server 8080

# Ou com Node.js
npx serve .
```

Acesse: `http://localhost:8080`