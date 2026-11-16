# CUIDA — Controle Unificado Inteligente de Autocuidado

Aplicativo Android nativo desenvolvido para ajudar na organização da rotina de medicamentos e autocuidado, com foco em privacidade local, funcionamento offline dos lembretes e suporte para situações de emergência.

---

## 📱 Download (Somente Android)

> **Disponível exclusivamente para dispositivos Android.**

O instalador oficial (`.apk`) está hospedado diretamente na aba de Releases deste repositório.

[![Baixar APK para Android](https://img.shields.io/badge/Download-APK%20Android-1F5A96?style=for-the-badge&logo=android&logoColor=white)](https://github.com/VitorRodrig15/App-Cuida-Controle-Unificado-Inteligente-de-Autocuidado/releases/latest)

### Como instalar no celular:
1. Clique no botão acima (ou acesse a seção **[Releases](https://github.com/VitorRodrig15/App-Cuida-Controle-Unificado-Inteligente-de-Autocuidado/releases)** na lateral direita desta página) e baixe o arquivo `.apk` mais recente.
2. Ao abrir o arquivo baixado no celular, o Android solicitará permissão para **instalar apps de fontes desconhecidas** (ou do navegador utilizado). Autorize para prosseguir.
3. Conclua a instalação e abra o **CUIDA**.

*Nota: Para que os alertas funcionem no minuto exato mesmo com a tela bloqueada, conceda as permissões de **Notificações** e **Alarmes e lembretes** solicitadas no primeiro acesso[cite: 2].*

---

## ✨ Funcionalidades Principais

* **Gestão de Medicamentos:** Cadastro com nome, dosagem, horário inicial, frequência (6h, 8h, 12h ou 24h), duração (5, 7, 14, 30 dias ou uso contínuo), cor de identificação, foto e som personalizado[cite: 2].
* **Alarmes Dedicados:** Alertas sonoros que utilizam o volume de alarme do aparelho (como um despertador), funcionam com a tela bloqueada, entram em fila quando há doses simultâneas e permitem confirmar (*Tomei*) ou adiar por 10 minutos[cite: 2].
* **Registro Fotográfico:** Possibilidade de anexar uma foto (câmera ou galeria) para registrar a tomada de uma dose específica[cite: 2].
* **Agenda e Histórico:** Visualização do calendário de tratamentos ativos e histórico recente de doses confirmadas ou não respondidas[cite: 2].
* **Ficha Médica e Exportação em PDF:** Armazenamento de dados de saúde (tipo sanguíneo, alergias, condições médicas, peso, altura e doação de órgãos) com geração de **Ficha Médica em PDF** diretamente no aparelho para compartilhamento rápido[cite: 2].
* **Anjo da Guarda:** Cadastro de um contato de confiança com telefone e parentesco exibido no perfil e na Ficha Médica[cite: 2]. *(Recursos de alertas automáticos e SOS previstos para a versão CUIDA PRO)[cite: 2].*
* **Multiusuário Isolado:** Suporte para mais de uma conta no mesmo aparelho, mantendo os dados locais e os agendamentos de alarme separados por usuário[cite: 2].

---

## 🔒 Privacidade e Arquitetura de Dados

O CUIDA foi projetado sob o conceito **Local-First** para dados sensíveis, em conformidade com a LGPD (Lei nº 13.709/2018)[cite: 2]:

* **Armazenamento 100% Local:** Medicamentos, histórico de doses, fotos, áudios personalizados, informações de saúde e o contato do Anjo da Guarda ficam gravados **exclusivamente na área privada do aparelho** (fora do backup automático na nuvem)[cite: 2].
* **Funcionamento Offline:** O agendamento e o disparo dos alarmes funcionam sem conexão com a internet[cite: 2].
* **Autenticação Segura:** Apenas os dados cadastrais básicos (nome, CPF, e-mail e registro de aceite dos termos) são sincronizados via **Google Firebase (Authentication e Cloud Firestore)** para login, recuperação de senha e exclusão de conta[cite: 2].
* **Zero Rastreamento:** O aplicativo não exibe anúncios, não coleta localização em segundo plano e não utiliza ferramentas de analytics ou venda de dados[cite: 2].

📄 **Documentação Legal:** Os termos completos podem ser consultados no arquivo [`termos.html`](./termos.html) ou dentro do próprio aplicativo em *Perfil → Termos de uso*[cite: 2].

---

## ⚠️ Aviso Importante

O CUIDA é uma ferramenta de apoio à organização pessoal e **não substitui** consultas, diagnósticos, prescrições médicas ou serviços de emergência[cite: 2]. Em caso de urgência médica, ligue **192 (SAMU)**[cite: 2].

---

## 🛠️ Tecnologias Utilizadas

* **Plataforma:** Android Nativo (Kotlin / Android Studio)
* **Backend e Autenticação:** Firebase Authentication & Cloud Firestore[cite: 2]
* **Recursos Nativos:** AlarmManager (alarmes exatos), Foreground Services, CameraX / Galeria e geração nativa de PDF[cite: 2].
