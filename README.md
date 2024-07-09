<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- GOOGLE FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <!-- FIM DO GOOGLE FONTS -->
    <!-- BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <!-- FIM DO BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="style.css">
    <title>Portfólio</title>
</head>

<body>

    <header>
        <div class="interface">
            <div class="logo">
                <a href="#">
                    <img src="img/plat (1).png" alt="">
                </a>
            </div>
            <!--logo-->

            <nav class="menu-desktop">
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Sobre mim</a></li>
                    <li><a href="#">Especialidades</a></li>
                    <li><a href="#">Projetos</a></li>
                </ul>
            </nav>

            <div class="btn-contato">
                <a href="#">
                    <button>Contato</button>
                </a>
            </div>
            <!--btn-conato-->
        </div>
        <!--interface-->
    </header>

    <main>
        <section class="topo-do-site">
            <div class="interface">
                <div class="content-wrapper">
                    <div class="txt-topo-site">
                        <h1>Bem vindos ao portfólio da Ana Graziele. Espero que gostem. Fiz com todo carinho do mundo esse belo trabalho</h1>
                        <p>Lindes do meu coração. Saibam que vocês são muito importantes para o meu lindo coração.</p>

                        <div class="btn-contato">
                            <a href="#">
                                <button>Entre em contato</button>
                            </a>
                        </div>
                    </div>
                    <!--txt-topo-site-->
                    <div class="img-topo-site">
                        <img src="img/harri.potter.presta (1).png" alt="">
                    </div>
                    <!--img-topo-site-->
                </div>
                <!--content-wrapper-->
            </div>
            <!--interface-->
        </section>
        <!--topo-do-site-->

        <section class="Especialidades">
            <div class="interface">
                <h2 class="titulo">Minhas especialidades</h2>

                <div class="especialidades-flex">
                    <div class="especialidades-box">
                        <i class="bi bi-code-square"></i>
                        <h3>Website</h3>
                        <p>Aqui é onde ficará meu lindo website</p>
                    </div>
                    <!--especialidades-box-->
                    <div class="especialidades-box">
                        <i class="bi bi-cart2"></i>
                        <h3>Loja Online</h3>
                        <p>Aqui é onde ficará linda lojinha da Grazi</p>
                    </div>
                    <!--especialidades-box-->
                    <div class="especialidades-box">
                        <i class="bi bi-camera-reels"></i>
                        <h3>Blog</h3>
                        <p>Aqui será o meu maravilhoso blog</p>
                    </div>
                    <!--especialidades-box-->
                </div>
                <!--especialidades-flex-->
            </div>
            <!--interface-->
        </section>
        <!--Especialidades-->
        <section class="sobre">
            <div class="interface">
                <div class="flex">
                    <div class="img-sobre">
                        <img src="img/minha_linda_foto-removebg-preview.png" alt="">
                    </div>
                    <div class="txt-sobre">
                        <h2>Olá, belas pessoas. <span>Me chamo Ana Graziele.</span></h2>
                        <p>Sou aluna do IFMA, e...</p>
                        <p>hablarei horrores aqui dps</p>
                        <div class="btn-social">
                            <a href="https://wa.me/5599991613545" target="_blank"><button><i class="bi bi-whatsapp"></i></button></a>
                            <a href="#"><button><i class="bi bi-instagram"></i></button></a>
                            <a href=" https://x.com/ana_graziele_as?s=08 "><button><i class="bi bi-twitter-x"></i></button></a>
                            <a href="https://www.tiktok.com/@ana.graziele_?_t=8ngEnBw7rGA&_r=1"><button><i class="bi bi-tiktok"></i></i></button></a>
                        </div>
                        <!--btn-social-->
                    </div>
                    <!--flex-->
                </div>
                <!--interface-->
        </section>
        <!--sobre-->

        <section class="portfólio">
            <div class="interface">
                <h2 class="titulo">Meu portfólio</h2>
                <div class="flex">
                    <div class="img-port" style="background-image: url(img/medo-port.png);">
                        <div class="overlay">Projeto 1</div>
                    </div>
                    <div class="img-port" style="background-image: url(img/ansie.port.png);">
                        <div class="overlay">Projeto 2</div>
                    </div>
                    <div class="img-port" style="background-image: url(img/njo-por.png);">
                        <div class="overlay">Projeto 3</div>
                    </div>
                </div>
                <!--flex-->
            </div>
            <!--interface-->
        </section>
        <!--portfólio-->

        <section class="formulário">
            <div class="interface">
                <h2 class="título">FALA COMIGO</h2>

                <form action="https://api.staticforms.xyz/submit" method="post">
                    <label>Nome</label>
                    <input type="text" name="name" placeholder="Digite seu nome" autocomplete="off" required>
                    <label>Email</label>
                    <input type="email" name="email" placeholder="Digite seu email" autocapitalize="off" required>
                    <label>Mensagem</label>
                    <textarea name="message" cols="30" rows="10" placeholder="Digite sua mensagem" required></textarea>
                    <button type="submit" class="btn-enviar">Enviar</button>

                    <input type="hidden" name="accessKey" value="e2c63ca6-5eb9-49d7-ac8c-9879b60dba62">
                    <input type="hidden" name="redirectTo" value="http://127.0.0.1:5500/obrigado.html">
                </form>
            </div>
            <!--interface-->
        </section>
        <!--formulário-->

    </main>

    <footer>
        <div class="interface">
            <div class="line-footer flex">
                <div class="logo-footer">
                    <img src="img/plat (1).png" alt="">
                </div>
                <!--logo-fother-->
                <div class="btn-social">
                    <a href="https://wa.me/5599991613545" target="_blank"><button><i class="bi bi-whatsapp"></i></button></a>
                    <a href="#"><button><i class="bi bi-instagram"></i></button></a>
                    <a href=" https://x.com/ana_graziele_as?s=08 "><button><i class="bi bi-twitter-x"></i></button></a>
                    <a href="https://www.tiktok.com/@ana.graziele_?_t=8ngEnBw7rGA&_r=1"><button><i class="bi bi-tiktok"></i></i></button></a>
                </div>
                <!--btn-social-->
            </div>
            <!--line-footer-->

            <div class="line-footer borda">
                <p><i class="bi bi-envelope-at"></i>
                    <a href="mailto:anagraziele@acad.ifma.edu.br">anagraziele@acad.ifma.edu.br</a>
                </p>
            </div>
            <!--line-footer-->
        </div>
    </footer>

</body>

</html>
