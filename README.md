script.js
const botaoCalcular = document.getElementById("btnCalcular");
const inputPh = document.getElementById("phSolo");
const divResultado = document.getElementById("resultado");

botaoCalcular.addEventListener("click", () => {
    const ph = parseFloat(inputPh.value);

    // Validação de entrada
    if (isNaN(ph) || ph < 0 || ph > 14) {
        divResultado.innerHTML = "❌ Por favor, digite um valor de pH válido entre 0 e 14.";
        divResultado.style.color = "#d32f2f";
        divResultado.style.backgroundColor = "#ffebee";
        return;
    }

    // Lógica de análise do solo
    if (ph < 5.5) {
        divResultado.innerHTML = "⚠️ Solo Ácido! Seu solo precisa de calagem (calcário) para elevar o pH e liberar os nutrientes para a plantação.";
        divResultado.style.color = "#b71c1c"; 
        divResultado.style.backgroundColor = "#fff3e0"; 
    } else if (ph <= 6.5) { 
        // Não precisa de 'ph >= 5.5' porque se chegou aqui, com certeza é maior ou igual a 5.5
        divResultado.innerHTML = "✅ pH Ideal! O solo está na faixa excelente para o cultivo da maioria das plantas (soja, milho, feijão).";
        divResultado.style.color = "#1b5e20"; 
        divResultado.style.backgroundColor = "#e8f5e9"; 
    } else {
        divResultado.innerHTML = "ℹ️ Solo Alcalino! O pH está alto. Monitore de perto, pois isso pode dificultar a absorção de micronutrientes como o ferro.";
        divResultado.style.color = "#0d47a1"; 
        divResultado.style.backgroundColor = "#e3f2fd"; 
    }
});
