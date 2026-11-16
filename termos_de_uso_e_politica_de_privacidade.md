# TERMOS DE USO E POLÍTICA DE PRIVACIDADE
**CUIDA — Controle Unificado Inteligente de Autocuidado**

**Versão:** 2026-11-12 · **Última atualização:** 12/11/2026 · Aplicável ao aplicativo CUIDA para Android.

> **Resumo em linguagem simples:** O CUIDA ajuda você a lembrar de tomar seus medicamentos. Seus medicamentos, horários, histórico, fotos e informações de saúde ficam **somente no seu celular**. No servidor (Google Firebase) ficam apenas os dados da sua conta: nome, CPF, e-mail e o registro de que você aceitou estes termos. O CUIDA não exibe anúncios, não vende dados e não usa seus dados de saúde para publicidade. Você pode excluir sua conta e seus dados pelo próprio aplicativo. O CUIDA **não substitui** orientação médica nem serviços de emergência.

---

## PARTE I — TERMOS DE USO

### 1. Sobre o CUIDA
O CUIDA — Controle Unificado Inteligente de Autocuidado é um aplicativo de apoio à organização da rotina de medicamentos e autocuidado. Na versão atual, o aplicativo oferece:

* Cadastro de medicamentos com nome, dosagem, horário inicial, frequência (a cada 6, 8, 12 ou 24 horas), duração (5, 7, 14 ou 30 dias ou uso contínuo), cor, foto e som de alerta;
* Alarmes sonoros no horário de cada dose, com tela de alarme, notificação e opção de adiar por 10 minutos;
* Registro de dose tomada pelo alarme, pela notificação, pela tela Início ou com uma foto;
* Agenda com o calendário dos tratamentos e histórico recente de doses;
* Ficha de informações de saúde e de emergência e exportação da Ficha Médica em PDF;
* Cadastro de um contato de confiança (Anjo da Guarda), com alertas automáticos previstos para o plano CUIDA PRO (seção 8).

### 2. Finalidade e limites
O CUIDA é uma ferramenta de apoio. Ele **não** substitui consultas, diagnóstico, prescrição, tratamento, acompanhamento profissional ou serviços de emergência, e não é um dispositivo médico.

O aplicativo não prescreve medicamentos nem define doses ou horários: ele apenas lembra o que o próprio usuário cadastrou. Siga sempre as orientações do seu médico, farmacêutico ou outro profissional de saúde.

> ⚠️ **Em caso de emergência, ligue 192 (SAMU) ou procure atendimento médico imediatamente.**

### 3. Conta do usuário
Para usar o CUIDA é necessário criar uma conta com nome completo, CPF, e-mail e senha (mínimo de 6 caracteres). O CPF é validado pelos dígitos verificadores. A senha é processada pelo Firebase Authentication (Google) e **não** é armazenada pelo CUIDA. A recuperação de senha é feita por um link enviado ao e-mail cadastrado.

O usuário deve fornecer informações verdadeiras, proteger sua senha e não compartilhar suas credenciais. O usuário é responsável pelo uso feito com sua conta, salvo falha atribuível ao CUIDA.

Se mais de uma pessoa usar o CUIDA no mesmo celular, os dados de cada conta ficam separados: ao entrar com outra conta, os medicamentos, o histórico e os dados de saúde da conta anterior não são exibidos. Ao sair da conta, os alarmes dela são cancelados naquele aparelho e voltam a ser agendados quando a mesma conta entrar novamente.

### 4. Cadastro de medicamentos
O usuário é responsável por conferir os dados cadastrados com a receita ou orientação profissional. O CUIDA não verifica nem garante a correção das informações inseridas.

Os horários do dia são calculados a partir do horário inicial e da frequência escolhida. Um tratamento com duração definida começa no dia do cadastro e termina ao fim do último dia. Depois disso, deixa de aparecer na tela Início e os alarmes param. O uso contínuo não tem data de término.

### 5. Alarmes e notificações
* **Recorrência:** cada horário toca todos os dias enquanto o tratamento estiver ativo e é reagendado automaticamente depois de tocar, após reiniciar o celular, após atualizar o aplicativo ou ao mudar a data, a hora ou o fuso horário.
* **Som:** o alerta toca pelo **volume de alarme** do celular, como um despertador, e não pelo volume de notificações. O usuário pode escolher entre os sons do aplicativo ou um áudio próprio.
* **Vários medicamentos no mesmo horário:** os alertas entram em uma fila e tocam um de cada vez. A tela informa quantos estão aguardando.
* **Tomei / Adiar:** “Tomei” registra a dose daquele horário. “Adiar” silencia e repete o alerta após 10 minutos.
* **Sem resposta:** se nenhuma opção for escolhida em 10 minutos, o som para e fica uma notificação de “dose não confirmada”.
* **Registro antecipado:** registrar uma dose com mais de 30 minutos de antecedência pede confirmação, porque o alarme daquele horário não tocará no dia.

O funcionamento dos alertas depende de fatores fora do controle do CUIDA, como permissões concedidas, volume de alarme, modo “Não perturbe”, economia de bateria, restrições do fabricante do aparelho e o celular estar ligado. Se a permissão de alarmes exatos for negada, o alerta pode tocar com alguns minutos de atraso. O CUIDA não garante que todo alerta será ouvido ou visto.

### 6. Registro fotográfico da dose
O usuário pode registrar uma dose com uma foto (câmera ou galeria) e escolher a qual medicamento e horário do dia ela corresponde. A foto fica salva no aparelho, vinculada àquela dose. A foto não comprova, por si só, que o medicamento foi ingerido, e o CUIDA não faz nenhuma interpretação médica da imagem.

### 7. Ficha Médica em PDF
A Ficha Médica reúne nome, CPF, e-mail, contato do Anjo da Guarda, informações de saúde e medicamentos. O arquivo é gerado no próprio aparelho e salvo no local escolhido pelo usuário. Como contém dados sensíveis, o usuário é responsável por onde guardar o arquivo e com quem compartilhá-lo.

### 8. Anjo da Guarda
**Versão gratuita (atual):** o usuário pode cadastrar o nome, o parentesco e o telefone de uma pessoa de confiança. Esses dados ficam **somente no aparelho**, aparecem no Perfil e na Ficha Médica exportada e **não são enviados** automaticamente a ninguém. O CUIDA não envia SMS, e-mail ou notificação ao Anjo da Guarda na versão gratuita.

> ⭐ **CUIDA PRO (recurso futuro, ainda não disponível):** Quando lançado, o plano CUIDA PRO prevê:
> * Aviso ao Anjo da Guarda quando uma dose não for confirmada em até 10 minutos após o alarme;
> * Aviso quando a mesma dose for adiada 3 vezes seguidas;
> * Resumo diário de doses tomadas e pendentes;
> * Pedido de ajuda (SOS) acionado pelo usuário, com envio de localização somente se autorizado naquele momento;
> * Convite por código ou link, com conta própria para o Anjo da Guarda, que **nunca** recebe a senha do usuário;
> * Escolha do que cada Anjo pode ver (apenas alertas, histórico de doses e/ou ficha de saúde), até 3 Anjos por conta, com revogação a qualquer momento;
> * Avisos por notificação no aplicativo do Anjo da Guarda e por e-mail. Os avisos dependem de internet e, sem conexão, são enviados quando a conexão voltar.
>
> O preço, as condições de contratação e os fornecedores envolvidos serão informados antes da contratação, e esta Política será atualizada. Nenhum dado será compartilhado com o Anjo da Guarda sem o consentimento específico do usuário. Um aviso ao Anjo da Guarda não é um serviço de emergência.

### 9. Responsabilidades do usuário
* Fornecer informações verdadeiras e conferir medicamentos, doses e horários cadastrados;
* Permitir notificações e alarmes, manter o volume de alarme audível e o aparelho em condições de uso;
* Proteger o celular (bloqueio de tela) e as credenciais da conta;
* Avaliar com cuidado com quem compartilha a Ficha Médica e quem cadastra como Anjo da Guarda;
* Procurar orientação profissional sempre que necessário.

### 10. Limitações de responsabilidade
Nos limites da lei, o CUIDA não garante que o usuário tomará o medicamento, que um alarme será ouvido, que uma notificação será entregue ou que uma foto comprove a ingestão. O CUIDA também não detecta emergências médicas. O aplicativo deve ser usado como complemento da rotina de cuidados.

### 11. Propriedade intelectual e condutas proibidas
O nome CUIDA, a identidade visual, a interface, o código e os textos pertencem ao responsável pelo aplicativo ou a seus titulares. É proibido acessar contas de terceiros, burlar mecanismos de segurança, introduzir código malicioso, explorar vulnerabilidades, falsificar registros ou usar o CUIDA para fins ilícitos.

### 12. Disponibilidade, encerramento e exclusão da conta
Lembretes, histórico e cadastro de medicamentos funcionam sem internet. Login, criação de conta, recuperação de senha e exclusão de conta exigem conexão.

O usuário pode excluir a conta a qualquer momento em **Perfil → Excluir minha conta e meus dados**, confirmando com a senha. A exclusão é imediata e irreversível (detalhes na Parte II, seção 7). Contas usadas de forma indevida poderão ser suspensas, conforme a lei aplicável.

### 13. Público e menores de idade
O CUIDA é destinado a maiores de 18 anos. O uso por adolescentes deve ocorrer com a participação e a autorização do responsável legal, que pode criar e gerenciar a conta. O CUIDA não é direcionado a crianças.

### 14. Alterações e aceite
Estes Termos podem ser atualizados por razões legais, técnicas ou funcionais. A versão vigente fica sempre disponível no aplicativo (Cadastro e Perfil → Termos de uso). Alterações relevantes serão informadas no aplicativo. No cadastro, o CUIDA registra a data e a versão dos Termos aceitos.

Estes Termos são regidos pelas leis da República Federativa do Brasil.

---

## PARTE II — POLÍTICA DE PRIVACIDADE

Esta Política explica quais dados o CUIDA trata, onde ficam armazenados e quais são os seus direitos, de acordo com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018 — LGPD).

### 1. Controlador e contato
| Campo | Informação |
| :--- | :--- |
| **Controlador** | `[NOME / RAZÃO SOCIAL]` |
| **CPF/CNPJ** | `[CPF OU CNPJ]` |
| **Endereço** | `[ENDEREÇO]` |
| **Encarregado (DPO)** | `[NOME DO ENCARREGADO]` |
| **E-mail para assuntos de privacidade** | `[E-MAIL DE PRIVACIDADE]` |

### 2. Quais dados tratamos e onde ficam
| Dado | Onde fica | Para quê |
| :--- | :--- | :--- |
| Nome, CPF, e-mail, data e versão do aceite dos Termos | Servidor — Google Firebase (Cloud Firestore) | Identificar o titular da conta e comprovar o aceite |
| E-mail e senha | Servidor — Google Firebase Authentication. A senha é guardada de forma protegida pelo Google e não é acessível ao CUIDA. | Login, segurança e recuperação de senha |
| Medicamentos (nome, dosagem, horários, frequência, duração, cor, som) | Somente no aparelho | Agendar alarmes e exibir o tratamento |
| Registro de doses (data, horário previsto, horário registrado) e histórico | Somente no aparelho | Histórico, tela Início, Agenda e lembretes do dia |
| Fotos de medicamentos, fotos de doses e foto de perfil | Somente no aparelho (área privada do aplicativo) | Identificação visual e registro da dose |
| Áudio de alerta personalizado | Somente no aparelho | Tocar o alarme escolhido |
| Informações de saúde: tipo sanguíneo, alergias, doenças/condições, peso, altura, doação de órgãos e outras informações | Somente no aparelho | Ficha de emergência e Ficha Médica em PDF |
| Anjo da Guarda: nome, parentesco e telefone | Somente no aparelho | Exibir o contato no Perfil e na Ficha Médica |

Os dados mantidos **somente no aparelho** não são enviados a servidores do CUIDA. Eles ficam na área privada do aplicativo, separados por conta, e são excluídos do backup automático do Android. Isso significa que **não são recuperados** ao reinstalar o aplicativo ou trocar de celular.

O CUIDA **não** coleta localização, contatos da agenda, identificadores de publicidade nem dados de navegação, e **não** utiliza ferramentas de analytics, de publicidade ou de relatórios de falhas de terceiros.

### 3. Dados sensíveis e bases legais
Informações de saúde são dados pessoais sensíveis (art. 5º, II, LGPD). O CUIDA trata esses dados com base no **consentimento** específico e destacado do titular (art. 11, I), manifestado ao aceitar estes Termos e ao inserir voluntariamente cada informação. O preenchimento das informações de saúde é opcional.

Os dados da conta (nome, CPF e e-mail) são tratados para a **execução do contrato** de uso do aplicativo (art. 7º, V). O registro do aceite é guardado para cumprir obrigação legal e para o exercício regular de direitos (art. 7º, II e VI).

### 4. Permissões do aparelho
| Permissão | Uso |
| :--- | :--- |
| **Notificações** | Mostrar o alarme e os avisos de dose não confirmada |
| **Alarmes e lembretes exatos** | Tocar no minuto exato da dose |
| **Tela cheia / exibir sobre a tela de bloqueio** | Abrir a tela do alarme com o celular bloqueado |
| **Serviço em primeiro plano, manter ativo e vibrar** | Tocar e vibrar o alarme até a resposta do usuário |
| **Iniciar após reiniciar** | Reagendar os alarmes depois que o celular é ligado |
| **Câmera (opcional)** | Fotografar medicamentos e doses. Só é solicitada quando o usuário toca em “tirar foto”. |
| **Internet** | Login, cadastro e comunicação com o Firebase |

### 5. Compartilhamento e fornecedores
O CUIDA não vende nem aluga dados pessoais e não os usa para publicidade. O único fornecedor que recebe dados é o **Google (Firebase Authentication e Cloud Firestore)**, que atua como operador e recebe apenas os dados da conta descritos na seção 2. Os servidores do Google podem estar localizados fora do Brasil, o que caracteriza transferência internacional de dados (art. 33, LGPD), realizada com as garantias contratuais oferecidas pelo fornecedor.

Na versão gratuita, nenhum dado é enviado ao Anjo da Guarda. Dados também podem ser fornecidos a autoridades quando houver ordem judicial ou obrigação legal.

### 6. Segurança
* Comunicação com o Firebase por conexão criptografada (HTTPS/TLS);
* Regras de acesso no servidor: cada usuário só consegue ler e alterar o próprio cadastro;
* Dados locais na área privada do aplicativo, separados por conta e fora do backup automático;
* Componentes internos de alarme protegidos contra acionamento por outros aplicativos;
* Confirmação da senha para excluir a conta.

Nenhum sistema é totalmente imune a falhas. Recomendamos manter o bloqueio de tela ativo, já que os dados de saúde ficam no aparelho. Em caso de incidente de segurança que possa causar risco ou dano relevante, os titulares e a Autoridade Nacional de Proteção de Dados (ANPD) serão comunicados, conforme a lei.

### 7. Retenção e exclusão
| Dado | Por quanto tempo |
| :--- | :--- |
| **Cadastro no servidor (nome, CPF, e-mail, aceite)** | Enquanto a conta existir. É apagado na exclusão da conta. |
| **Conta no Firebase Authentication** | Enquanto a conta existir. É apagada na exclusão da conta. |
| **Medicamentos, histórico, fotos, áudios e informações de saúde** | Até o usuário apagá-los, excluir a conta ou desinstalar o aplicativo. A foto e o áudio de um medicamento são apagados junto com ele. |
| **Ficha Médica em PDF exportada** | Fica sob controle do usuário, no local onde ele a salvou. |

**Como excluir:** em **Perfil → Excluir minha conta e meus dados**, informe a senha. O CUIDA cancela os alarmes, apaga o cadastro no servidor, remove a conta de login e apaga os dados da conta guardados no aparelho. O processo exige internet. Também é possível pedir a exclusão pelo e-mail de privacidade indicado na seção 1.

### 8. Seus direitos
Conforme o art. 18 da LGPD, você pode solicitar: confirmação de que tratamos seus dados, acesso, correção, anonimização, bloqueio ou eliminação de dados desnecessários, portabilidade, informações sobre compartilhamento, eliminação dos dados tratados com consentimento e revogação do consentimento. Muitos desses direitos podem ser exercidos diretamente no aplicativo: editar ou apagar dados, exportar a Ficha Médica ou excluir a conta. Os demais podem ser solicitados pelo e-mail de privacidade. Você também pode apresentar reclamação à ANPD.

### 9. Alterações desta Política
Esta Política será atualizada sempre que o funcionamento do aplicativo mudar, por exemplo com o lançamento do CUIDA PRO. A versão e a data estão no início do documento.

### Declaração de aceite
Ao marcar a caixa de aceite no cadastro, o usuário declara que:

- [ ] Leu e concorda com os Termos de Uso do CUIDA;
- [ ] Leu e está ciente da Política de Privacidade, inclusive de que seus dados de saúde ficam armazenados no próprio aparelho;
- [ ] Consente com o tratamento dos dados de saúde que inserir no aplicativo, para as finalidades aqui descritas;
- [ ] Está ciente de que o CUIDA é uma ferramenta de apoio e não substitui orientação profissional nem atendimento de emergência.