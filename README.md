# exemplo-aulaHtml

# HTML  
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Exemplo</title>
    <link rel="stylesheet" href="./css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>

<body>
    <header>
        <p class="logo">LOGO</p>
        <nav>
            <a href="#">Início</a>
            <a href="#">Sobre</a>
            <a href="#">Galeria</a>
            <a href="#">Contato</a>
        </nav>
    </header>

    <main>
        <section id="sobre">
            <img src="https://picsum.photos/240/240" alt="Imagem aleatória">
            <iframe width="400" height="225"
                src="https://www.youtube-nocookie.com/embed/NuY76URXaMk?si=JjQmLe3iz5WibDJz"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At harum inventore aliquid...</p>
        </section>

        <section id="galeria">
            <div class="card">
                <h1>TÍTULO</h1>
                <div class="caixa">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
                    <img src="https://picsum.photos/100/100" alt="img">
                </div>
            </div>
            <div class="card">
                <img src="https://picsum.photos/100/100" alt="img">
            </div>
            <div class="card">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
                 <a href="./">Pagina 2</a>
            </div>
        </section>

        <section id="contato">
            <p>Entre em contato conosco!</p>
        </section>

       
    </main>
    
    </body>
       </html>

# HTML 2
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <a href="./indewx.html">Perfil do Robo</a>
      <img src="https://picsum.photos/100/100" alt="img">
</body>
    </html>

# CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background-color: #fdf5e6;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 40px;
    height: 100px;
    background-color: #BC8F8F;
}

.logo {
    font-size: 30pt;
    border: 2px solid black;
    width: 120px;
    height: 120px;
    border-radius: 50%;
    background-color: #F5DEB3;
    color: #8B4513;
    text-align: center;
    line-height: 120px;
}

header nav {
    display: flex;
    gap: 15px;
}

header nav a {
    text-decoration: none;
    padding: 10px 15px;
    background-color: #A0522D;
    color: #FFDEAD;
    border-radius: 5px;
    transition: 0.3s;
}

header nav a:hover {
    background: #DEB887;
    color: #FFC0CB;
}

main {
    max-width: 1200px;
    margin: 40px auto;
    padding: 20px;
}

/* SOBRE */
#sobre {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    align-items: center;
    margin-bottom: 60px;
    text-align: center;
}

#sobre img,
#sobre iframe {
    border-radius: 10px;
}

/* GALERIA */
#galeria {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    margin-bottom: 60px;
}

.card {
    background-color: #fffaf0;
    border: 1px solid #ccc;
    padding: 20px;
    width: 280px;
    border-radius: 10px;
    text-align: center;
}

.card h1 {
    margin-bottom: 10px;
}

.card img {
    margin-top: 10px;
    border-radius: 5px;
}

/* CONTATO */
#contato {
    text-align: center;
    padding: 40px;
    background-color: #FFDEAD;
    border-radius: 10px;
}
