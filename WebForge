<!DOCTYPE html>
<html lang="pt-BR" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebForge | Desenvolvimento Digital & Automação</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: { 500: '#6366f1', 600: '#4f46e5', 700: '#4338ca' }
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen flex flex-col selection:bg-indigo-500 selection:text-white">

    <!-- Navegação -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-slate-950/80 border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-indigo-600 to-violet-500 flex items-center justify-center shadow-lg shadow-indigo-500/30">
                    <i class="fa-solid fa-cube text-white text-xl"></i>
                </div>
                <span class="text-2xl font-black tracking-tight bg-gradient-to-r from-white via-indigo-200 to-indigo-400 bg-clip-text text-transparent">WebForge</span>
            </div>
            
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-slate-300">
                <a href="#inicio" class="hover:text-indigo-400 transition-colors">Início</a>
                <a href="#servicos" class="hover:text-indigo-400 transition-colors">Serviços</a>
                <a href="#portfolio" class="hover:text-indigo-400 transition-colors">Portfólio</a>
                <a href="#automacao" class="hover:text-indigo-400 transition-colors">Automação</a>
            </nav>

            <div class="flex items-center space-x-4">
                <button onclick="abrirLogin()" class="px-4 py-2 text-sm font-semibold text-indigo-400 bg-indigo-500/10 hover:bg-indigo-500/20 border border-indigo-500/30 rounded-xl transition-all flex items-center space-x-2">
                    <i class="fa-solid fa-lock text-xs"></i>
                    <span>Área Admin</span>
                </button>
                <a href="#contato" class="hidden sm:inline-flex px-5 py-2.5 text-sm font-semibold text-white bg-gradient-to-r from-indigo-600 to-violet-600 hover:from-indigo-500 hover:to-violet-500 rounded-xl shadow-lg shadow-indigo-600/30 transition-all">
                    Orçamento
                </a>
            </div>
        </div>
    </header>

    <!-- Conteúdo Principal -->
    <main class="flex-grow">
        <!-- Hero Section -->
        <section id="inicio" class="relative overflow-hidden py-24 lg:py-32 border-b border-slate-900">
            <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-indigo-900/20 via-slate-950/0 to-slate-950/0 pointer-events-none"></div>
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
                <span class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-indigo-500/10 border border-indigo-500/20 text-indigo-400 text-xs font-semibold uppercase tracking-wider mb-6">
                    <i class="fa-solid fa-bolt"></i>
                    <span>Desenvolvimento Digital & Automação</span>
                </span>
                <h1 class="text-4xl sm:text-6xl lg:text-7xl font-black tracking-tight max-w-4xl mx-auto leading-tight mb-8">
                    Forjando o futuro digital da sua <span class="bg-gradient-to-r from-indigo-400 to-violet-400 bg-clip-text text-transparent">empresa</span>.
                </h1>
                <p class="text-lg sm:text-xl text-slate-400 max-w-2xl mx-auto mb-10">
                    Criamos sites profissionais, modernos e de alta performance para negócios de pequeno e grande porte, com automações avançadas e sistemas sob medida.
                </p>
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                    <a href="#servicos" class="w-full sm:w-auto px-8 py-4 rounded-xl font-bold bg-indigo-600 hover:bg-indigo-500 text-white shadow-xl shadow-indigo-600/30 transition-all text-center">
                        Conhecer Serviços
                    </a>
                    <a href="#contato" class="w-full sm:w-auto px-8 py-4 rounded-xl font-bold bg-slate-900 hover:bg-slate-800 text-slate-200 border border-slate-800 transition-all text-center">
                        Falar com Especialista
                    </a>
                </div>
            </div>
        </section>

        <!-- Seção Dinâmica / CMS (Exibe os itens adicionados pelo Admin) -->
        <section id="portfolio" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl sm:text-4xl font-black tracking-tight mb-4">Portfólio & Projetos em Destaque</h2>
                <p class="text-slate-400 max-w-xl mx-auto">Soluções reais entregues para empresas de todos os portes.</p>
            </div>
            
            <!-- Grid Dinâmico -->
            <div id="grid-projetos" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Projeto Padrão 1 -->
                <div class="bg-slate-900/60 border border-slate-800 rounded-2xl overflow-hidden group hover:border-indigo-500/50 transition-all">
                    <div class="h-48 bg-gradient-to-br from-indigo-900/50 to-slate-900 flex items-center justify-center relative overflow-hidden">
                        <i class="fa-solid fa-globe text-4xl text-indigo-400/60 group-hover:scale-110 transition-transform"></i>
                    </div>
                    <div class="p-6">
                        <span class="text-xs font-semibold text-indigo-400 uppercase tracking-wider">E-Commerce Corporativo</span>
                        <h3 class="text-xl font-bold text-white mt-1 mb-2">Portal Global Atacado</h3>
                        <p class="text-slate-400 text-sm">Plataforma completa de vendas B2B com automação de estoque e pagamentos.</p>
                    </div>
                </div>
                <!-- Projeto Padrão 2 -->
                <div class="bg-slate-900/60 border border-slate-800 rounded-2xl overflow-hidden group hover:border-indigo-500/50 transition-all">
                    <div class="h-48 bg-gradient-to-br from-violet-900/50 to-slate-900 flex items-center justify-center relative overflow-hidden">
                        <i class="fa-solid fa-laptop-code text-4xl text-violet-400/60 group-hover:scale-110 transition-transform"></i>
                    </div>
                    <div class="p-6">
                        <span class="text-xs font-semibold text-violet-400 uppercase tracking-wider">Landing Page</span>
                        <h3 class="text-xl font-bold text-white mt-1 mb-2">NovaEra Tech Solutions</h3>
                        <p class="text-slate-400 text-sm">Página institucional focada em alta conversão de leads para automação industrial.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção de Serviços -->
        <section id="servicos" class="py-20 bg-slate-900/30 border-t border-b border-slate-900">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16">
                    <h2 class="text-3xl sm:text-4xl font-black tracking-tight mb-4">Nossas Soluções</h2>
                    <p class="text-slate-400 max-w-xl mx-auto">Tecnologia avançada adaptada para o seu modelo de negócio.</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="p-8 rounded-2xl bg-slate-900/80 border border-slate-800">
                        <div class="w-12 h-12 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center mb-6 text-xl">
                            <i class="fa-solid fa-code"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Desenvolvimento Web</h3>
                        <p class="text-slate-400 text-sm">Sites institucionais, portais corporativos e e-commerces ultrarrápidos e responsivos.</p>
                    </div>
                    <div class="p-8 rounded-2xl bg-slate-900/80 border border-slate-800">
                        <div class="w-12 h-12 rounded-xl bg-violet-500/10 text-violet-400 flex items-center justify-center mb-6 text-xl">
                            <i class="fa-solid fa-robot"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Sistemas de Automação</h3>
                        <p class="text-slate-400 text-sm">Integração de processos, chatbots inteligentes e fluxos automatizados para otimizar operações.</p>
                    </div>
                    <div class="p-8 rounded-2xl bg-slate-900/80 border border-slate-800">
                        <div class="w-12 h-12 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center mb-6 text-xl">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Painel Administrativo</h3>
                        <p class="text-slate-400 text-sm">Gerenciamento completo e seguro do seu conteúdo com controle total em tempo real.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contato -->
        <section id="contato" class="py-20 max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-3xl sm:text-4xl font-black mb-4">Pronto para transformar sua empresa?</h2>
            <p class="text-slate-400 mb-8">Entre em contato hoje mesmo e descubra como o WebForge pode alavancar seus resultados.</p>
            <a href="mailto:contato@webforge.com" class="inline-block px-8 py-4 rounded-xl font-bold bg-indigo-600 hover:bg-indigo-500 text-white shadow-xl shadow-indigo-600/30 transition-all">
                Enviar E-mail de Contato
            </a>
        </section>
    </main>

    <!-- Rodapé -->
    <footer class="border-t border-slate-900 py-12 text-center text-sm text-slate-500">
        <p>&copy; 2026 WebForge. Todos os direitos reservados.</p>
    </footer>

    <!-- MODAL DE LOGIN ADMIN -->
    <div id="modal-login" class="fixed inset-0 z-50 bg-slate-950/80 backdrop-blur-sm hidden flex items-center justify-center p-4">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl p-8 max-w-md w-full relative shadow-2xl">
            <button onclick="fecharLogin()" class="absolute top-4 right-4 text-slate-400 hover:text-white">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            <div class="text-center mb-6">
                <div class="w-12 h-12 bg-indigo-600/20 text-indigo-400 rounded-xl flex items-center justify-center mx-auto mb-3 text-xl">
                    <i class="fa-solid fa-user-shield"></i>
                </div>
                <h3 class="text-2xl font-bold text-white">Painel Administrativo</h3>
                <p class="text-slate-400 text-sm mt-1">Acesso restrito ao administrador zayro</p>
            </div>
            <form onsubmit="fazerLogin(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Nome de Usuário</label>
                    <input type="text" id="user-input" required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-indigo-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Senha</label>
                    <input type="password" id="pass-input" required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-indigo-500">
                </div>
                <button type="submit" class="w-full py-3 bg-indigo-600 hover:bg-indigo-500 font-bold rounded-xl text-white shadow-lg shadow-indigo-600/30 transition-all">
                    Entrar no Sistema
                </button>
                <p id="login-erro" class="text-red-400 text-xs text-center hidden">Usuário ou senha incorretos!</p>
            </form>
        </div>
    </div>

    <!-- MODAL DO PAINEL ADMIN (Gerenciamento e Upload) -->
    <div id="modal-admin" class="fixed inset-0 z-50 bg-slate-950/90 backdrop-blur-md hidden overflow-y-auto p-4 sm:p-6">
        <div class="max-w-4xl mx-auto bg-slate-900 border border-slate-800 rounded-2xl p-6 sm:p-8 relative shadow-2xl my-8">
            <div class="flex items-center justify-between pb-6 border-b border-slate-800 mb-6">
                <div class="flex items-center space-x-4">
                    <!-- Emblema Oficial Personalizado -->
                    <div class="w-12 h-12 rounded-xl bg-gradient-to-tr from-amber-500 to-indigo-600 p-0.5 shadow-lg">
                        <div class="w-full h-full bg-slate-950 rounded-[10px] flex items-center justify-center text-amber-400 font-black">
                            <i class="fa-solid fa-crown"></i>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-white flex items-center gap-2">
                            <span>Zayro</span>
                            <span class="text-xs bg-amber-500/10 text-amber-400 border border-amber-500/30 px-2 py-0.5 rounded-full">Admin Oficial</span>
                        </h3>
                        <p class="text-slate-400 text-xs">Gerenciador de Conteúdo WebForge</p>
                    </div>
                </div>
                <button onclick="fecharAdmin()" class="px-4 py-2 bg-slate-800 hover:bg-slate-700 rounded-xl text-sm font-semibold text-white transition-all">
                    Sair / Fechar
                </button>
            </div>

            <!-- Adicionar Novo Projeto / Conteúdo -->
            <div class="bg-slate-950 p-6 rounded-xl border border-slate-800 mb-8">
                <h4 class="text-lg font-bold text-white mb-4 flex items-center gap-2">
                    <i class="fa-solid fa-plus-circle text-indigo-400"></i>
                    <span>Adicionar Novo Projeto / Item ao Site</span>
                </h4>
                <form onsubmit="adicionarProjeto(event)" class="space-y-4">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Título do Projeto</label>
                            <input type="text" id="novo-titulo" required placeholder="Ex: Sistema Logística" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white focus:outline-none focus:border-indigo-500">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Categoria</label>
                            <input type="text" id="nova-categoria" required placeholder="Ex: Automação / E-commerce" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white focus:outline-none focus:border-indigo-500">
                        </div>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Descrição</label>
                        <textarea id="nova-desc" required rows="2" placeholder="Breve descrição..." class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-2.5 text-white focus:outline-none focus:border-indigo-500"></textarea>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Upload de Imagem (Capa)</label>
                        <input type="file" id="novo-img" accept="image/*" class="w-full text-sm text-slate-400 file:mr-4 file:py-2 file:px-4 file:rounded-xl file:border-0 file:text-sm file:font-semibold file:bg-indigo-600 file:text-white hover:file:bg-indigo-500 cursor-pointer">
                    </div>
                    <button type="submit" class="w-full py-3 bg-indigo-600 hover:bg-indigo-500 font-bold rounded-xl text-white shadow-lg shadow-indigo-600/30 transition-all">
                        Publicar no Site
                    </button>
                </form>
            </div>

            <!-- Lista de Projetos Existentes para Gerenciar/Apagar -->
            <div>
                <h4 class="text-lg font-bold text-white mb-4">Gerenciar Projetos Atuais</h4>
                <div id="lista-gerenciamento" class="space-y-3">
                    <!-- Preenchido via JavaScript -->
                </div>
            </div>
        </div>
    </div>

    <!-- Scripts de Controle -->
    <script>
        let projetos = JSON.parse(localStorage.getItem('webforge_projetos')) || [
            { id: 1, titulo: "Portal Global Atacado", categoria: "E-Commerce Corporativo", desc: "Plataforma completa de vendas B2B com automação de estoque e pagamentos.", img: "" },
            { id: 2, titulo: "NovaEra Tech Solutions", categoria: "Landing Page", desc: "Página institucional focada em alta conversão de leads para automação industrial.", img: "" }
        ];

        function renderizarProjetos() {
            const grid = document.getElementById('grid-projetos');
            const gerenciamento = document.getElementById('lista-gerenciamento');
            
            if(!grid || !gerenciamento) return;

            grid.innerHTML = '';
            gerenciamento.innerHTML = '';

            projetos.forEach((p, index) => {
                // Renderiza no Site Público
                grid.innerHTML += `
                    <div class="bg-slate-900/60 border border-slate-800 rounded-2xl overflow-hidden group hover:border-indigo-500/50 transition-all">
                        <div class="h-48 bg-gradient-to-br from-indigo-900/50 to-slate-900 flex items-center justify-center relative overflow-hidden">
                            ${p.img ? `<img src="${p.img}" class="w-full h-full object-cover">` : `<i class="fa-solid fa-globe text-4xl text-indigo-400/60"></i>`}
                        </div>
                        <div class="p-6">
                            <span class="text-xs font-semibold text-indigo-400 uppercase tracking-wider">${p.categoria}</span>
                            <h3 class="text-xl font-bold text-white mt-1 mb-2">${p.titulo}</h3>
                            <p class="text-slate-400 text-sm">${p.desc}</p>
                        </div>
                    </div>
                `;

                // Renderiza na Área Admin para Apagar
                gerenciamento.innerHTML += `
                    <div class="flex items-center justify-between p-4 bg-slate-950 border border-slate-800 rounded-xl">
                        <div>
                            <h5 class="font-bold text-white">${p.titulo}</h5>
                            <span class="text-xs text-slate-400">${p.categoria}</span>
                        </div>
                        <button onclick="apagarProjeto(${index})" class="px-3 py-1.5 bg-red-500/10 hover:bg-red-500/20 text-red-400 border border-red-500/20 rounded-lg text-xs font-semibold transition-all">
                            <i class="fa-solid fa-trash mr-1"></i> Apagar
                        </button>
                    </div>
                `;
            });
        }

        function abrirLogin() {
            document.getElementById('modal-login').classList.remove('hidden');
        }

        function fecharLogin() {
            document.getElementById('modal-login').classList.add('hidden');
            document.getElementById('login-erro').classList.add('hidden');
        }

        function fazerLogin(e) {
            e.preventDefault();
            const u = document.getElementById('user-input').value;
            const p = document.getElementById('pass-input').value;

            if (u === 'zayro' && p === '2011') {
                fecharLogin();
                document.getElementById('modal-admin').classList.remove('hidden');
                renderizarProjetos();
            } else {
                document.getElementById('login-erro').classList.remove('hidden');
            }
        }

        function fecharAdmin() {
            document.getElementById('modal-admin').classList.add('hidden');
        }

        function adicionarProjeto(e) {
            e.preventDefault();
            const titulo = document.getElementById('novo-titulo').value;
            const categoria = document.getElementById('nova-categoria').value;
            const desc = document.getElementById('nova-desc').value;
            const fileInput = document.getElementById('novo-img');

            if (fileInput.files && fileInput.files[0]) {
                const reader = new FileReader();
                reader.onload = function(uploadEvent) {
                    projetos.push({ id: Date.now(), titulo, categoria, desc, img: uploadEvent.target.result });
                    localStorage.setItem('webforge_projetos', JSON.stringify(projetos));
                    renderizarProjetos();
                    e.target.reset();
                    alert('Projeto adicionado com sucesso!');
                };
                reader.readAsDataURL(fileInput.files[0]);
            } else {
                projetos.push({ id: Date.now(), titulo, categoria, desc, img: '' });
                localStorage.setItem('webforge_projetos', JSON.stringify(projetos));
                renderizarProjetos();
                e.target.reset();
                alert('Projeto adicionado com sucesso!');
            }
        }

        function apagarProjeto(index) {
            if(confirm('Tem certeza que deseja apagar este item?')) {
                projetos.splice(index, 1);
                localStorage.setItem('webforge_projetos', JSON.stringify(projetos));
                renderizarProjetos();
            }
        }

        // Inicializa os projetos ao carregar a página
        window.onload = renderizarProjetos;
    </script>
</body>
</html>
