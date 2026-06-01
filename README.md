<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uso Eficiente de Nutrientes e Redução da Poluição por Fertilizantes</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
        }
        
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.75)), url('https://images.unsplash.com/photo-1625246333195-78d9c38ad449?q=80&w=2070') center/cover no-repeat;
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
        
        .nav-link {
            position: relative;
        }
        
        .nav-link:after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: #4ade80;
            transition: width 0.3s ease;
        }
        
        .nav-link:hover:after {
            width: 100%;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- HEADER -->
    <header class="bg-green-700 text-white sticky top-0 z-50 shadow-lg">
        <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="w-12 h-12 bg-green-500 rounded-2xl flex items-center justify-center text-3xl">🌱</div>
                <div>
                    <h1 class="text-2xl font-bold tracking-tight">Agro Forte</h1>
                    <p class="text-xs text-green-200 -mt-1">Nutrição Inteligente</p>
                </div>
            </div>
            
            <nav class="hidden md:flex items-center gap-8 text-lg">
                <a href="#inicio" class="nav-link font-medium">Início</a>
                <a href="#importancia" class="nav-link font-medium">Importância</a>
                <a href="#desafios" class="nav-link font-medium">Desafios</a>
                <a href="#estrategias" class="nav-link font-medium">Estratégias</a>
                <a href="#conclusao" class="nav-link font-medium">Conclusão</a>
            </nav>
            
            <button onclick="window.scrollTo({top: document.getElementById('contato').offsetTop, behavior: 'smooth'})" 
                    class="bg-white text-green-700 px-6 py-2.5 rounded-full font-semibold hover:bg-green-100 transition">
                Saiba Mais
            </button>
        </div>
    </header>

    <!-- HERO -->
    <section id="inicio" class="hero-bg h-screen flex items-center text-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-2xl">
                <div class="inline-flex items-center gap-2 bg-white/20 backdrop-blur-md px-4 py-2 rounded-full mb-6">
                    <span class="text-green-300">🌍</span>
                    <span class="text-sm font-medium">Sustentabilidade Agrícola</span>
                </div>
                <h1 class="text-6xl md:text-7xl font-bold leading-tight mb-6">
                    Uso Eficiente de<br>Nutrientes e Redução<br>da Poluição por<br>Fertilizantes
                </h1>
                <p class="text-xl text-green-100 mb-10">
                    Equilíbrio entre produção agrícola e preservação do meio ambiente
                </p>
                <div class="flex gap-4">
                    <a href="#importancia" 
                       class="bg-green-600 hover:bg-green-500 transition px-8 py-4 rounded-2xl font-semibold text-lg flex items-center gap-3">
                        <span>Explorar agora</span>
                        <i class="fas fa-arrow-down"></i>
                    </a>
                    <a href="#estrategias" 
                       class="border border-white hover:bg-white/10 transition px-8 py-4 rounded-2xl font-semibold text-lg">
                        Ver Estratégias
                    </a>
                </div>
            </div>
        </div>
        
        <div class="absolute bottom-10 left-1/2 flex flex-col items-center">
            <div class="text-sm mb-2">Role para baixo</div>
            <i class="fas fa-chevron-down text-3xl animate-bounce"></i>
        </div>
    </section>

    <!-- INTRODUÇÃO -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid md:grid-cols-12 gap-12 items-center">
                <div class="md:col-span-7">
                    <h2 class="text-4xl font-bold text-green-800 mb-8">Por que este tema é importante?</h2>
                    <div class="prose prose-lg text-gray-700">
                        <p>Com a população mundial projetada para atingir <strong>10 bilhões de pessoas até 2050</strong>, a agricultura precisa aumentar a produção sem expandir áreas cultiváveis, evitando o desmatamento.</p>
                        <p>Os fertilizantes são essenciais para a produtividade, mas seu uso inadequado causa poluição, perda de nutrientes e impactos ambientais.</p>
                    </div>
                </div>
                <div class="md:col-span-5">
                    <div class="bg-green-50 p-8 rounded-3xl">
                        <div class="flex items-center gap-4 mb-6">
                            <div class="w-16 h-16 bg-green-600 rounded-2xl flex items-center justify-center text-4xl">📈</div>
                            <div>
                                <h3 class="font-bold text-xl">Produtividade + Sustentabilidade</h3>
                                <p class="text-green-700">É possível ter as duas coisas</p>
                            </div>
                        </div>
                        <ul class="space-y-4">
                            <li class="flex items-start gap-3"><span class="text-green-600 text-2xl">✓</span> Redução de custos</li>
                            <li class="flex items-start gap-3"><span class="text-green-600 text-2xl">✓</span> Menor impacto ambiental</li>
                            <li class="flex items-start gap-3"><span class="text-green-600 text-2xl">✓</span> Solo mais saudável</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- IMPORTÂNCIA -->
    <section id="importancia" class="py-20 bg-green-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <span class="bg-green-200 text-green-800 px-5 py-2 rounded-full text-sm font-medium">CAMPO FORTE FERTILIZANTES</span>
                <h2 class="text-4xl font-bold mt-6 text-green-900">Importância dos Fertilizantes na Agricultura Moderna</h2>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-3xl card-hover shadow-xl">
                    <div class="text-5xl mb-6">💰</div>
                    <h3 class="text-2xl font-semibold mb-4">Redução de Custos</h3>
                    <p class="text-gray-600">Aplicação correta reduz desperdícios e aumenta a eficiência do solo, gerando maior retorno econômico.</p>
                </div>
                <div class="bg-white p-8 rounded-3xl card-hover shadow-xl">
                    <div class="text-5xl mb-6">🌱</div>
                    <h3 class="text-2xl font-semibold mb-4">Sustentabilidade</h3>
                    <p class="text-gray-600">Manejo adequado preserva o solo, evita desmatamento e reduz a poluição por nutrientes.</p>
                </div>
                <div class="bg-white p-8 rounded-3xl card-hover shadow-xl">
                    <div class="text-5xl mb-6">🌍</div>
                    <h3 class="text-2xl font-semibold mb-4">Segurança Alimentar</h3>
                    <p class="text-gray-600">Permite aumentar a produção para alimentar uma população crescente sem expandir áreas agrícolas.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- DESAFIOS -->
    <section id="desafios" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-green-900">Principais Desafios</h2>
                <p class="text-xl text-gray-600 mt-4">N, P e K: os nutrientes mais críticos</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="border border-orange-200 bg-orange-50 p-8 rounded-3xl">
                    <h3 class="font-bold text-2xl text-orange-800 mb-2">Nitrogênio (N)</h3>
                    <p class="text-orange-700">Alta mobilidade, sujeito a volatilização e lixiviação. Maior risco de poluição.</p>
                </div>
                <div class="border border-amber-200 bg-amber-50 p-8 rounded-3xl">
                    <h3 class="font-bold text-2xl text-amber-800 mb-2">Fósforo (P)</h3>
                    <p class="text-amber-700">Baixa mobilidade e alta fixação em solos tropicais. Apenas 20-30% é absorvido.</p>
                </div>
                <div class="border border-blue-200 bg-blue-50 p-8 rounded-3xl">
                    <h3 class="font-bold text-2xl text-blue-800 mb-2">Potássio (K)</h3>
                    <p class="text-blue-700">Sujeito a lixiviação em solos arenosos e com irrigação intensa.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ESTRATÉGIAS -->
    <section id="estrategias" class="py-20 bg-green-900 text-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-5xl font-bold">Estratégias para Eficiência</h2>
                <p class="text-green-400 text-xl mt-4">Manejo 4R + Tecnologias Inovadoras</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-3xl">
                    <h4 class="text-green-400 font-medium mb-3">1. Manejo 4R</h4>
                    <p class="font-semibold text-xl mb-4">Fonte certa • Dose certa • Tempo certo • Lugar certo</p>
                    <p class="text-green-100">Reduz perdas e maximiza absorção pelas plantas.</p>
                </div>
                
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-3xl">
                    <h4 class="text-green-400 font-medium mb-3">2. Tecnologias Avançadas</h4>
                    <ul class="space-y-4 text-green-100">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-green-400"></i> Fertilizantes de liberação lenta</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-green-400"></i> Nanofertilizantes</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-green-400"></i> Fertirrigação</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-green-400"></i> Organominerais</li>
                    </ul>
                </div>
                
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-3xl">
                    <h4 class="text-green-400 font-medium mb-3">3. Correção do Solo</h4>
                    <p class="text-green-100">Calagem, gessagem, plantio direto e rotação de culturas são fundamentais para aumentar a eficiência dos fertilizantes.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CONCLUSÃO -->
    <section id="conclusao" class="py-24 bg-gradient-to-br from-green-50 to-emerald-100">
        <div class="max-w-4xl mx-auto text-center px-6">
            <h2 class="text-5xl font-bold text-green-900 mb-8">Conclusão</h2>
            <div class="prose prose-xl mx-auto text-gray-700">
                <p class="mb-8">Melhorar a eficiência no uso de fertilizantes é essencial para uma agricultura mais produtiva e sustentável. A integração entre tecnologia, manejo qualificado e diagnóstico agronômico permite ganhos reais de produtividade com menor risco de perdas e impactos ambientais.</p>
            </div>
            <div class="mt-12 bg-white rounded-3xl p-10 shadow-2xl">
                <p class="italic text-xl text-green-800">"O futuro da agricultura depende de nossa capacidade de produzir mais com menos impacto ambiental."</p>
                <p class="mt-6 text-green-600 font-medium">— Equipe Agro Forte</p>
            </div>
        </div>
    </section>

    <!-- FONTES -->
    <section class="py-16 bg-white border-t">
        <div class="max-w-7xl mx-auto px-6">
            <h3 class="text-center text-lg font-medium text-gray-500 mb-8">Fontes Consultadas</h3>
            <div class="grid md:grid-cols-2 gap-6 text-sm">
                <div class="bg-gray-50 p-6 rounded-2xl">
                    <p><strong>Campo Forte Fertilizantes</strong></p>
                    <a href="https://www.campoforte.com" target="_blank" class="text-green-600 hover:underline">www.campoforte.com</a>
                </div>
                <div class="bg-gray-50 p-6 rounded-2xl">
                    <p><strong>SolloAgro</strong></p>
                    <a href="https://solloagro.com.br" target="_blank" class="text-green-600 hover:underline">Eficiência no Uso de Fertilizantes</a>
                </div>
                <div class="bg-gray-50 p-6 rounded-2xl">
                    <p><strong>ANDA / IFA / UNEP</strong></p>
                    <p class="text-gray-600">O Uso de Fertilizantes Minerais e o Meio Ambiente</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-green-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <div class="flex justify-center gap-3 mb-6">
                <div class="text-4xl">🌾</div>
                <div class="text-4xl">🌍</div>
                <div class="text-4xl">🌱</div>
            </div>
            <p class="text-green-400">Desenvolvido para o Concurso de Programação - Núcleo Regional de Educação Curitiba</p>
            <p class="mt-8 text-sm text-green-500">Agro Forte, Futuro Sustentável • 2026</p>
        </div>
    </footer>

    <script>
        // Tailwind script already included via CDN
        
        // Smooth scrolling for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                if (this.getAttribute('href') !== '#') {
                    e.preventDefault();
                    const target = document.querySelector(this.getAttribute('href'));
                    if (target) {
                        target.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                }
            });
        });
        
        // Navbar background on scroll
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.classList.add('bg-green-800', 'shadow-md');
            } else {
                header.classList.remove('bg-green-800', 'shadow-md');
            }
        });
    </script>
</body>
</html>
