<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Biblioteca Virtual</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            text-align: center;
            margin: 1rem 0;
        }
        nav a {
            margin: 0 1rem;
            text-decoration: none;
            color: #4CAF50;
        }
        main {
            padding: 1rem;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Mobile first styles */
        @media (min-width: 600px) {
            main {
                padding: 2rem;
            }
            nav a {
                margin: 0 2rem;
            }
        }

        @media (min-width: 768px) {
            header {
                padding: 2rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Biblioteca Virtual</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#catalogo">Catálogo</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
    <main>
        <section id="home">
            <h2>Bem-vindo à Minha Biblioteca Virtual!</h2>
            <p>Aqui você pode
