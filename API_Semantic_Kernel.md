## API do Azure OpenAI e SEMANTIC KERNEL

**Endpoint** - É o ponto de acesso único para interagir com os serviços da API do Azure OpenAI, especificando a operação desejada.

**Completar (Completions)** - Permite enviar um prompt de texto para um modelo de linguagem e receber uma ou mais conclusões geradas. Os parâmetros controlam o comportamento do modelo: temperatura, número máximo de tokens e top-p.

**Chat (Chat Completions)** - Interface otimizada para conversas interativas entre a máquina e o usuário, sendo a base para a criação de chatbots e assistentes virtuais.

**Imagem (Images)** - Funcionalidade para criar imagens a partir de descrições textuais (prompts) utilizando modelos como o DALL-E.

**Control Plane** - Camada de gerenciamento onde se realizam operações de configuração, gerenciamento de recursos e segurança do serviço Azure OpenAI.

**Data Plane** - Camada onde as aplicações interagem diretamente com os modelos de IA para executar tarefas específicas, como:
* Envio de prompts para completar texto.
* Envio de mensagens para conversas e assistentes.
* Geração de imagens.
* Geração de embeddings.

**Authentication** - Mecanismos para verificar a identidade e conceder acesso aos recursos. Permite atribuir permissões a identidades gerenciadas ou entidades de serviço, eliminando a necessidade de gerenciar chaves diretamente no código.

**Embeddings** - Representação vetorial de dados textuais que captura o significado semântico e as relações entre os textos, auxiliando na assimilação e na geração de respostas relevantes aos prompts.

**Segurança e Governança** - Conjunto de recursos e políticas oferecidas pelo Azure para garantir a proteção dos dados, o gerenciamento de permissões, a criptografia das informações e o monitoramento das atividades relacionadas ao uso da API do Azure OpenAI.
