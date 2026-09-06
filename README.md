<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Blog da Silvia 💜</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Poppins", Arial, sans-serif;
            background: linear-gradient(135deg, #f9d9ec, #d9ccff);
            min-height: 100vh;
            color: #4d3b55;
            overflow-x: hidden;
        }

        /* Estrelas e decoração */
        .estrela {
            position: fixed;
            color: white;
            font-size: 25px;
            animation: flutuar 4s infinite ease-in-out;
            opacity: 0.8;
        }

        .e1 { top: 10%; left: 8%; }
        .e2 { top: 20%; right: 10%; animation-delay: 1s; }
        .e3 { bottom: 15%; left: 15%; animation-delay: 2s; }
        .e4 { bottom: 10%; right: 15%; animation-delay: 3s; }

        @keyframes flutuar {
            0%, 100% {
                transform: translateY(0);
            }

            50% {
                transform: translateY(-15px);
            }
        }

        /* Página principal */
        .container {
            width: 90%;
            max-width: 1100px;
            margin: 50px auto;
            background: rgba(255, 255, 255, 0.92);
            border-radius: 30px;
            padding: 50px;
            box-shadow: 0 20px 50px rgba(100, 60, 120, 0.2);
            animation: aparecer 1s ease;
        }

        @keyframes aparecer {
            from {
                opacity: 0;
                transform: translateY(30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Cabeçalho */
        header {
            text-align: center;
            margin-bottom: 40px;
        }

        header h1 {
            font-size: 55px;
            color: #a65391;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
            color: #806681;
        }

        .linha {
            width: 100px;
            height: 5px;
            background: linear-gradient(90deg, #d77fbd, #9274d6);
            border-radius: 10px;
            margin: 20px auto;
        }

        /* Apresentação */
        .sobre {
            display: flex;
            align-items: center;
            gap: 50px;
            margin-bottom: 50px;
        }

        /* Foto */
        .foto {
            min-width: 250px;
            height: 250px;
            border-radius: 50%;
            background: linear-gradient(135deg, #d786bc, #9475d1);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 90px;
            font-weight: bold;
            border: 8px solid white;
            box-shadow: 0 10px 30px rgba(100, 60, 120, 0.25);
        }

        .texto h2 {
            color: #a65391;
            font-size: 32px;
            margin-bottom: 15px;
        }

        .texto p {
            font-size: 18px;
            line-height: 1.8;
            color: #66556d;
        }

        .destaque {
            color: #a65391;
            font-weight: bold;
        }

        /* Cards */
        .cards {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: linear-gradient(145deg, #fff5fb, #f2edff);
            padding: 25px;
            border-radius: 20px;
            text-align: center;
            transition: 0.3s;
            border: 1px solid #f0d9ec;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 12px 25px rgba(120, 70, 130, 0.15);
        }

        .card .icone {
            font-size: 40px;
            margin-bottom: 12px;
        }

        .card h3 {
            color: #9b568d;
            margin-bottom: 10px;
            font-size: 22px;
        }

        .card p {
            color: #716174;
            line-height: 1.6;
        }

        /* Seção de sonhos */
        .sonhos {
            margin-top: 50px;
            padding: 35px;
            border-radius: 25px;
            background: linear-gradient(135deg, #fce5f4, #ebe3ff);
            text-align: center;
        }

        .sonhos h2 {
            color: #a65391;
            font-size: 30px;
            margin-bottom: 15px;
        }

        .sonhos p {
            max-width: 750px;
            margin: auto;
            line-height: 1.8;
            color: #66556d;
            font-size: 18px;
        }

        .frase {
            margin-top: 25px;
            font-size: 20px;
            font-style: italic;
            color: #925c91;
            font-weight: bold;
        }

        /* Rodapé */
        footer {
            text-align: center;
            margin-top: 40px;
            color: #8b6d91;
            font-size: 16px;
        }

        /* Responsividade */
        @media (max-width: 800px) {

            .container {
                padding: 30px;
            }

            header h1 {
                font-size: 42px;
            }

            .sobre {
                flex-direction: column;
                text-align: center;
            }

            .cards {
                grid-template-columns: 1fr;
            }

            .foto {
                min-width: 200px;
                width: 200px;
                height: 200px;
                font-size: 70px;
            }
        }
    </style>
</head>

<body>

    <!-- Decoração -->
    <div class="estrela e1">✦</div>
    <div class="estrela e2">♡</div>
    <div class="estrela e3">✧</div>
    <div class="estrela e4">♡</div>

    <main class="container">

        <!-- Cabeçalho -->
        <header>
            <h1>Olá, eu sou a Silvia! 💜</h1>

            <div class="linha"></div>

            <p>Bem-vindos ao meu pequeno cantinho ✨</p>
        </header>


        <!-- Sobre mim -->
        <section class="sobre">

            <!--
                Para colocar sua foto:
                substitua a div abaixo por:

                <img src="sua-foto.jpg" class="foto" alt="Foto da Silvia">
            -->

            <div class="foto">
                S
            </div>

            <div class="texto">

                <h2>🌷 Um pouquinho sobre mim</h2>

                <p>
                    Meu nome é <span class="destaque">Silvia</span>,
                    tenho <span class="destaque">16 anos</span> e este
                    é o meu cantinho na internet. 💕
                </p>

                <br>

                <p>
                    Estou vivendo uma fase cheia de descobertas,
                    aprendizados e novos sonhos. Gosto de aproveitar
                    os momentos especiais, aprender coisas novas e
                    descobrir cada vez mais sobre o mundo e sobre mim mesma.
                </p>

            </div>

        </section>


        <!-- Informações -->
        <section>

            <div class="cards">

                <div class="card">
                    <div class="icone">🎀</div>
                    <h3>Sobre mim</h3>

                    <p>
                        Sou uma garota curiosa, sonhadora e carinhosa,
                        sempre tentando aprender e evoluir.
                    </p>
                </div>


                <div class="card">
                    <div class="icone">🎧</div>
                    <h3>Meus interesses</h3>

                    <p>
                        Gosto de ouvir música, assistir filmes e séries,
                        conhecer assuntos novos e aproveitar meu tempo livre.
                    </p>
                </div>


                <div class="card">
                    <div class="icone">📚</div>
                    <h3>Estudos</h3>

                    <p>
                        Sou estudante e acredito que o conhecimento
                        pode abrir portas para o futuro.
                    </p>
                </div>

            </div>

        </section>


        <!-- Sonhos -->
        <section class="sonhos">

            <h2>🌙 Meus sonhos</h2>

            <p>
                Tenho muitos sonhos para o futuro e quero aproveitar
                cada oportunidade para aprender e crescer.
                Acredito que cada pequeno passo pode me aproximar
                da pessoa que quero me tornar.
            </p>

            <div class="frase">
                "Cada dia é uma nova página da história que estou escrevendo." ✨
            </div>

        </section>


        <!-- Rodapé -->
        <footer>
            💜 Seja bem-vindo(a) ao Blog da Silvia!
            <br><br>
            Feito com carinho ✨
        </footer>

    </main>

</body>
</html>
