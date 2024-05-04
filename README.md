### Hi there 👋

<!--<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CruzBarber7_</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #000000;
            /* Fundo vermelho brilhante */
            font-family: Arial, sans-serif;
            position: relative;
        }

        header {
            text-align: center;
            /* Centraliza o texto do cabeçalho */
            padding: 20px 0;
            /* Adiciona um espaçamento ao redor do cabeçalho */
            color: rgb(0, 0, 0);
            /* Cor do texto branca */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            /* Sombra no texto para destacá-lo */
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 10px;
        }

        nav ul li a {
            color: #f50000;
            text-decoration: none;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
            color: #ffffff
        }

        th,
        td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #ffffff;
        }

        th {
            background-color: #ff0000;
            color: #000000;
        }

        h3 {
            color: #ffffff
        }

        caption {
            color: #ffffff
        }

        li {
            color: #ffffff
        }

        td {
            color: rgb(255, 255, 255)
        }

        h1 {
            color: #ffffff;
            /* Cor do texto do cabeçalho branco */
        }

        p {
            color: #ffffff;
            /* Cor dos parágrafos branco */
        }

        .logo {
            position: absolute;
            top: 1%;
            /* Ajuste conforme necessário */
            right: 15%;
            /* Ajuste conforme necessário */
            z-index: 999;
            /* Certifica-se de que a logo esteja acima de outros elementos */
            width: 10%;
            /* Largura desejada da logo */
            border-radius: 50%;
            /* Deixa a logo redonda */
            overflow: hidden;
            /* Garante que a imagem não ultrapasse os limites do elemento */
        }

        #cortes-oferecidos {
            column-count: 2;
            /* Define duas colunas */
            column-gap: 20px;
            /* Espaçamento entre as colunas */
            padding: 0;
            /* Remove o padding padrão */
            list-style-type: none;
            /* Remove os marcadores de lista */
            text-align: left;
        }

        #cortes-oferecidos li:before {
            content: "\2022";
            /* Código do caractere Unicode para uma bolinha */
            color: #e40000e4;
            /* Cor da bolinha */
            display: inline-block;
            width: 1em;
            /* Tamanho da bolinha */
            margin-right: 0.5em;
            /* Espaçamento entre a bolinha e o texto */
        }

        /* Estilos para as formas de pagamento */
        #formas-pagamento {
            list-style-type: none;
            /* Remove os marcadores de lista */
        }

        #formas-pagamento li:before {
            content: "\2022";
            /* Código do caractere Unicode para uma bolinha */
            color: #ff0000;
            /* Cor da bolinha */
            display: inline-block;
            width: 1em;
            /* Tamanho da bolinha */
            margin-right: 0.5em;
            /* Espaçamento entre a bolinha e o texto */
        }

        #contato {
            list-style-type: none;
            /* Remove os marcadores de lista */
        }

        /* Estilos para os itens de contato */
        #contato li:before {
            content: "\2022";
            /* Código do caractere Unicode para uma bolinha */
            color: #ff0000;
            /* Cor da bolinha */
            display: inline-block;
            width: 1em;
            /* Tamanho da bolinha */
            margin-right: 0.5em;
            /* Espaçamento entre a bolinha e o texto */
        }

        .logo-responsive {
            max-width: 100%;
            height: auto;
        }


        @media only screen and (max-width: 600px) {
            #cortes-oferecidos {
                column-count: 1;
            }

            header,
            nav,
            main,
            footer {
                padding: 10px;
            }

            table {
                font-size: 12px;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>CruzBarber7_</h1>
    </header>

    <!-- Logo -->
    <img src="c:\Users\Kauã\Downloads\Logo Barbearia ilustrado Cinza.jpeg" alt=".Logo" class="logo 
    logo-responsive">
    <main>
        <section id="servicos">
            <h1>Serviços:</h1>
            <table>
                <tr>
                    <th>Serviço</th>
                    <th>Preço</th>
                </tr>
                <tr>
                    <td>Corte de Cabelo</td>
                    <td>R$ 10,00</td>
                </tr>
                <tr>
                    <td>Barba</td>
                    <td>R$ 10,00</td>
                </tr>
                <tr>
                    <td>Sobrancelha</td>
                    <td>R$ 5,00</td>
                </tr>
                <tr>
                    <td>Pezinho</td>
                    <td>R$ 5,00</td>
                </tr>
            </table>
            <h1>CORTES OFERECIDOS:</h1>
            <ul id="cortes-oferecidos">
                <li>Hair fade</li>
                <li>Low fade</li>
                <li>Degrade em v</li>
                <li>Corte Militar Navalhado</li>
                <li>Mid Fade</li>
                <li>Corte Militar</li>
                <li>Mid Fade na Shaver</li>
                <li>Social</li>
                <li>Low fade em v</li>
                <li>Moicano meio orelha</li>
                <li>Corte americano</li>
                <li>High fade</li>
                <li>Taper fade</li>
                <li>Corte moicano degrade</li>
                <li>Corte high fade marcado</li>
            </ul>
        </section>

        <section id="agenda">
            <table>
                <h1>Agenda:</h1>
                <caption>Horários de Atendimento:</caption>
                <tr>
                    <th>Dia</th>
                    <th>Horário</th>
                </tr>
                <tr>
                    <td>Segunda-feira</td>
                    <td>13h ás 18h</td>
                </tr>
                <tr>
                    <td>Terça-feira</td>
                    <td>13h ás 18h</td>
                </tr>
                <tr>
                    <td>Quarta-feira</td>
                    <td>13h ás 18h</td>
                </tr>
                <tr>
                    <td>Quinta-feira</td>
                    <td>13h ás 18h</td>
                </tr>
                <tr>
                    <td>Sexta-feira</td>
                    <td>13h ás 18h</td>
                </tr>
                <tr>
                    <td>Sábado</td>
                    <td>10h ás 18h</td>
                </tr>
            </table>

        </section>

        <section id="contato">
            <h1>Endereço:</h1>
            <li>Rua Billy Garmatter, 398- Xapinhal</li>
            <h1>Telefone:</h1>
            <li>(41) 9975-9557</li>
            <h1>Email:</h1>
            <li>cruzbarbeer7@gmail.com</li>
        </section>
        <section id="formas-pagamento">
            <h1>Formas De Pagamento:</h1>
            <li>DINHEIRO</li>
            <li>CARTÃO</li>
            <li>PIX</li>
        </section>
    </main>

    <footer>
        <p>© 2024 CruzBarber7_. Todos os direitos reservados.</p>
    </footer>
</body>

</html>
**1Kaua07/1Kaua07** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
