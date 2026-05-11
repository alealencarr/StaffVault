DevPortal | Staff Vault (Ultimate Edition)

Um portal de referência técnica, arquitetura e engenharia de software focado em programadores de nível Sénior, Staff e Principal. Construído como uma Single Page Application (SPA) ultrarrápida, sem necessidade de build, com uma estética premium inspirada em plataformas como Vercel, Linear e OpenAI.

Sobre o Projeto

O Staff Vault atua como um "segundo cérebro" para engenheiros de software. Em vez de tutoriais extensos, foca-se em conceitos cirúrgicos, trade-offs, arquitetura, performance e troubleshooting. Foi desenhado para minimizar a carga cognitiva e maximizar a eficiência na procura de informações no dia a dia ou na preparação para entrevistas técnicas de alto nível.

Funcionalidades Principais

Estética Premium (Dark Mode): Interface Cyber-minimalista com Glassmorphism, brilhos subtis e tipografia focada na legibilidade.

Command Palette (Busca Global): Pressione ⌘ + K (ou Ctrl + K) para abrir a pesquisa semântica instantânea em todo o conteúdo do portal.

Zero-Build / 100% Client-Side: Não requer Node.js, Webpack ou processos de compilação. Basta abrir o ficheiro.

Progressive Disclosure: Uso intensivo de Accordions (<details>) para manter a interface limpa, revelando conteúdo denso apenas quando necessário.

Copy-to-Clipboard: Snippets de código com formatação e botões de cópia rápida (Zero-Allocation C#, YAML, Bash).

Conteúdo Abordado

O portal está dividido em módulos essenciais para a Engenharia de Software moderna:

RESTful & API Design: Padrões de nomenclatura, HTTP Status Codes de resiliência e contratos.

Arch Patterns & SOLID: Clean Architecture, Vertical Slice, Hexagonal, SOA e princípios SOLID aplicados.

Domain-Driven Design (DDD): Domínio Rico vs Anémico, Value Objects, Agregados, ACL e Domain Events.

C# & .NET Deep Dive: Foco em performance (Zero-Allocation, Span<T>, Memory<T>, StringBuilder) e integrações resilientes com Refit.

Bancos de Dados & Persistência: Dapper vs EF Core, Transações ACID, Locks (Otimista vs Pessimista), Teorema CAP e Índices.

Testing Pyramid: Testes Unitários, de Integração (com Testcontainers) e E2E, além de Mocks vs Stubs.

Cloud, K8s & Docker: Kubernetes 101, LocalStack, AWS VPC (Security Groups vs NACL) e estratégias de Branching no Git.

Linux & CLI Mastery: Comandos vitais (grep, awk, sed), troubleshooting de redes, permissões e análise de logs.

The 36 Q&A Vault: Um cofre com as 36 perguntas (e respostas) mais críticas de arquitetura e .NET para entrevistas de nível Sénior/Staff.

Tecnologias Utilizadas

HTML5 & CSS3

Tailwind CSS (via CDN para execução instantânea)

JavaScript Vanilla (Lógica de filtragem, pesquisa e interações)

Phosphor Icons (Ícones modernos e consistentes)

Fontes: Inter (UI) e Fira Code (Snippets de código)

Como Executar e Hospedar

Como a aplicação é estática e autocontida num único ficheiro (index.html), tem várias opções:

Opção 1: Uso Local
Basta dar um duplo clique no ficheiro index.html para abri-lo em qualquer navegador web moderno.

Opção 2: Hospedagem Gratuita (GitHub Pages)

Crie um repositório no seu GitHub.

Adicione os ficheiros index.html e README.md.

Vá a Settings > Pages.

Em Source, selecione a branch main e guarde. Em poucos minutos, o seu portal estará online e acessível de qualquer lugar.

Contribuição

Sinta-se à vontade para fazer fork deste repositório e expandir o seu "segundo cérebro". Adicione novos snippets, resoluções de problemas complexos que enfrentou no trabalho ou novos padrões arquiteturais que esteja a estudar.

Feito de um Developer para Developers.
