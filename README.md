style.css
/* Configurações Gerais */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f4f7f4; 
    color: #2c3e2f; 
    line-height: 1.6;
}

/* Cabeçalho (Header) */
header {
    background-color: #2e5a36; 
    color: #ffffff;
    text-align: center;
    padding: 40px 20px;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

header p {
    font-style: italic;
    color: #a3e2a9; 
    margin-bottom: 20px;
}

/* Menu de Navegação */
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav a:hover {
    background-color: #1e3d24; 
}

/* Conteúdo Principal (Main) */
main {
    max-width: 800px;
    margin: 30px auto;
    padding: 20px;
}

/* Seções */
section {
    background-color: #ffffff; 
    padding: 25px;
    border-radius: 8px;
    margin-bottom: 25px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05); 
}

section h2 {
    color: #8b5a2b; 
    margin-bottom: 15px;
    border-bottom: 2px solid #e2ded0;
    padding-bottom: 5px;
}

section ul {
    list-style-position: inside;
    margin-top: 10px;
}

section li {
    margin-bottom: 10px;
}

/* Elementos da Calculadora Interativa */
.Abas-calculo {
    margin-top: 15px;
    display: flex;
    gap: 10px;
    align-items: center;
    flex-wrap: wrap;
}

#phSolo {
    padding: 8px;
    border-radius: 4px;
    border: 1px solid #ccc;
    max-width: 100px;
}

#btnCalcular {
    background-color: #2e5a36;
    color: white;
    border: none;
    padding: 8px 16px;
    border-radius: 4px;
    cursor: pointer;
    font-weight: bold;
    transition: background-color 0.2s;
}

#btnCalcular:hover {
    background-color: #1e3d24;
}

#resultado {
    margin-top: 20px;
    font-weight: bold;
    padding: 10px;
    border-radius: 4px;
}

/* Rodapé (Footer) */
footer {
    background-color: #1e3d24; 
    color: #ffffff;
    text-align: center;
    padding: 15px;
    font-size: 0.9rem;
    margin-top: 40px;
}
