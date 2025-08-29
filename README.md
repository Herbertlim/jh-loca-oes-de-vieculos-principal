  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jh locacoes de veiculos </title>
  </head>
  <body>
    
  </body>
  </html>


  <h1>JH LOCAÇÕES DE VEICULOS </h1>



  <img src="im11.png" alt="Logo da Empresa" class="img-canto">
  
 <header class="banner-cover">
  
</header>



  
<div class="top-buttons">
  <button onclick="location.href='#home'">🏠 Home</button>
  <button onclick="location.href='#sobre'">ℹ️ Sobre</button>
  <button onclick="location.href='#contato'">📞 Contato</button>
  <button onclick="location.href='#servicos'">🛠 Serviços</button>
  <button onclick="location.href='#produtos'">📦 Produtos</button>
  <button onclick="location.href='#localização'">🖼 localizacão</button>

  
</div>
  
  
  <!-- WhatsApp fixo -->
  <div class="whatsapp-fixo">
    <a href="https://wa.me/5511910453395" target="_blank">
      <img src="whatsapp.png" alt="WhatsApp">
    </a>
  </div>


    <nav>
    <div class="slider-nav">
      <div class="slides" id="slides">
        <div class="slide">
          <img src="https://i.postimg.cc/Rh7fBxVH/carro-jh.png" alt="Carro 1">
          <div class="info-carro">hyundai creta 200,00 dia </div>
          
        </div>
        <div class="slide">
          <img src="https://i.postimg.cc/MK8VY5zF/hb20.jpg" alt="Carro 2">
          <script src="script.js" defer></script>
          <div class="info-carro">hb 20 130,00 dia</div>
        </div>
      </div>

    </div>
  </nav>

  <script>
    const slides = document.getElementById('slides');
    const slideCount = document.querySelectorAll('.slide').length;
    let index = 0;

    function nextSlide() {
      index = (index + 1) % slideCount;
      slides.style.transform = `translateX(${-index * 100}%)`;
    }

    setInterval(nextSlide, 3000); // troca automática a cada 3s
  </script>

 

  <div class="container">
    <h1>JH Locações de Veículos</h1>

   <section class="documentos">
  <h2>📑 Documentos Necessários para Alugar um Veículo</h2>

  <h3>Pessoa Física (PF)</h3>
  <ul>
    <li>CNH válida (categoria B ou superior, conforme o veículo)</li>
    <li>Documento de identidade (RG ou CNH com foto válida)</li>
    <li>CPF (caso não conste no RG)</li>
    <li>Comprovante de residência atualizado (últimos 3 meses)</li>
    <li>Cartão de crédito em nome do locatário (para caução/garantia)</li>
  </ul>

 
  


<img src="cartao.png" alt="" width="250px"height="170px"
    !-- Redes sociais -->
    <div class="redes-sociais">
      <a href="#"><img src="facebook.png" alt="Facebook"></a>
      <a href="#"><img src="instagram.png" alt="Instagram"></a>
      <a href="https://wa.me/5511910453395"><img src="whatsapp.png" alt="WhatsApp"></a>
      <a href=" www.linkedin.com/in/seunome."><img src="linkedin.png" alt="linkedin"></a>
    </div>

    
 

    <!-- Dados da empresa -->
    <ul class="dados-empresa">
      <li><span>Nome da Empresa:</span> JH Locações de Veículos</li>
      <li><span>Endereço:</span> Av. Domenico Perella, 62 – Bairro Lavras, Guarulhos – SP, CEP 07161-401</li>
      <li><span>Telefone:</span> (11) 92091-5218</li>
      <li><span>WhatsApp:</span> (11) 91045-3395</li>
      <li><span>E-mail:</span> braskorportariaelimpeza@gmail.com</li>
      <li><span>Horário de Funcionamento:</span> Seg a Sex: 08:00 – 18:00 | Sáb: 08:00 – 12:00</li>
      <li><span>Responsável:</span> Herbert Lima Cuenca</li>
    </ul>
  </div>




  <h2>PLANOS BASICOS</h2>

<div class="cards-container">
  <div class="card">
    <img src="https://i.postimg.cc/Rh7fBxVH/carro-jh.png" alt="Carro A">
    <div class="card-info">
      <h3>hyundai Creta</h3>
      <p>Modelo: Suv<br>Ano: 2025<br>Cor: Prata</p>
      <span class="price">R$ 200,00 dia</span>
      <button onclick="alugar('creta?')">Alugar</button> 
    </div>
  </div>

  <div class="card">
    <img src="https://i.postimg.cc/MK8VY5zF/hb20.jpg" alt="Carro B">
    <div class="card-info">
      <h3>Hyundai HB20</h3>
      <p>Modelo: hatch<br>Ano: 2024<br>Cor: Azul</p>
      <span class="price">R$ 130,00 dia</span>
       <button onclick="alugar('hb 20?')">Alugar</button> 
    </div>
  </div>

  <div class="card">
 <img src="https://i.postimg.cc/0yy6tHFc/ONIXX.webp" alt="Carro c">
  <div class="card-info">
      <h3>chevrolet onix</h3>
      <p>Modelo: hatch<br>Ano: 2024<br>Cor: Azul</p>
      <span class="price">R$ 130,00 dia</span>
        <button onclick="alugar('onix?')">Alugar</button> 

   
        
    </div>
  </div>
</div>



  <h1>Contrato de Locação de Veículo</h1>
  

  <h2>Cláusula Primeira – Do Objeto, Prazo e Uso</h2>
  <div class="clausula">
    <p>1.1. O LOCADOR declara ser o legítimo possuidor e/ou proprietário do veículo de modelo xxxxx, marca xxxxx, ano xxxxxxx, cor xxxxx, placa xxxxxx, licenciado no Estado de xxxxxx, chassi xxxxxxxxxx, em perfeito estado e que resolveu dá-lo em locação ao LOCATÁRIO, pelo prazo de xxxxxxxxxx dias/anos/meses, contados a partir da assinatura do presente contrato.</p>

    <p>1.1.1. Findo prazo acima estipulado, o mesmo poderá ser renovado através de aditivo ou outro instrumento contratual ou o veículo deverá ser devolvido ao LOCADOR nas mesmas condições em que estava quando o recebeu, respondendo pelos danos ou prejuízos causados.</p>

    <p>1.1.3. Caso o LOCATÁRIO não restituir o automóvel na data estipulada, deverá pagar, enquanto detiver em seu poder, o valor da locação que o LOCADOR arbitrar, e responderá pelo dano que o automóvel venha a sofrer mesmo se proveniente de caso fortuito.</p>

    <p>1.1.4. O bem locado somente será destinado a uso exclusivo no Sistema de Transporte Intermunicipal de Passageiros do Estado de Alagoas.</p>

    <p>1.1.5. O bem locado apenas poderá ser dirigido pelo LOCATÁRIO ou por seu motorista substituto cadastrado na ARSAL.</p>
  </div>

  <h2>Cláusula Segunda – Do Valor</h2>
  <div class="clausula">
    <p>2.1. O LOCATÁRIO pagará ao LOCADOR a título de locação o valor mensal de <span class="valor">R$ ...</span>.</p>
    <p>2.1.1. O atraso no pagamento enseja multa de 5% (cinco por cento) e juros de 1% (um por cento) ao dia.</p>
  </div>

  <h2>Cláusula Terceira – Das Obrigações</h2>
  <div class="clausula">
    <p>3.1. O LOCATÁRIO deverá manter o veículo em perfeito estado de conservação, mecânica, tapeçaria, funilaria e pneus, devendo entregar, com o término do contrato, o veículo e sua documentação ao LOCADOR nas mesmas condições em que recebeu.</p>
    <p>3.2. É de inteira responsabilidade do LOCATÁRIO os débitos de qualquer natureza, com data posterior à assinatura do contrato, incluindo multas, licenciamento, seguro obrigatório, IPVA e outros relacionados ao veículo.</p>
  </div>

  <h2>Cláusula Quarta – Da Autorização</h2>
  <div class="clausula">
    <p>4.1. O LOCADOR autoriza o LOCATÁRIO à implantação da identificação visual e do sistema de monitoramento instituído pela ARSAL.</p>
  </div>

  <h2>Cláusula Quinta – Da Rescisão</h2>
  <div class="clausula">
    <p>5.1. A rescisão antes do vencimento, por qualquer das partes, deverá ser precedida de notificação expressa com antecedência mínima de 60 dias.</p>
    <p>5.2. O LOCATÁRIO deve comunicar à ARSAL a intenção de rescisão com antecedência mínima de 15 dias.</p>
    <p>5.3. Descumprimento de qualquer cláusula enseja rescisão e pagamento de multa de 3% do valor contratual.</p>
  </div>

  <h2>Cláusula Sexta – Disposições Gerais</h2>
  <div class="clausula">
    <p>6.1. O veículo está sendo entregue em perfeitas condições de uso, mediante vistoria.</p>
    <p>6.2. As partes elegem o foro de Maceió-AL para dirimir quaisquer ações oriundas deste contrato.</p>
  </div>

</div>


 <!-- Logos da empresa -->
  <div class="logos">
    <img src="hb20.jpg" alt="Logo 1">
    <img src="ka or.jpg" alt="Logo 2">
    <img src="ONIXX.webp" alt="Logo 3">
    <img src="creta.webp" alt="Logo 1">
    <img src="carro pjh.png" alt="Logo 2">
  


  </div>
</div>

<div class="cards-container">
    <div class="card">
    <img src="https://i.postimg.cc/sfpxcR6p/ka.jpg" alt="Carro d">
    <div class="card-info">
      <h3>FORD KA</h3>
      <p>Modelo: hatch<br>Ano: 2024<br>Cor: Cinza</p>
      <span class="price">R$ 130,00 dia</span>
       <button onclick="alugar('argo?')">Alugar</button> 
    </div>
  </div>



      <div class="card">
    <img src="https://i.postimg.cc/WpFKFfqB/gol.jpg" alt="Carro d">
    <div class="card-info">
      <h3>GOL</h3>
      <p>Modelo: hatch<br>Ano: 2024<br>Cor: Vermelho</p>
      <span class="price">R$ 130,00 dia</span>
       <button onclick="alugar('fiat up?')">Alugar</button> 
    </div>
  </div>


      <div class="card">
    <img src="https://i.postimg.cc/XNPbtC9b/logan.jpg" alt="Carro d">
    <div class="card-info">
      <h3>RENALT LOGAN</h3>
      <p>Modelo: Sedan<br>Ano: 2024<br>Cor: Branco</p>
      <span class="price">R$ 170,00 dia</span>
       <button onclick="alugar('fiat up?')">Alugar</button> 
    </div>
  </div>

  
      <div class="card">
    <img src="https://i.postimg.cc/pXRTc143/c-3.jpg" alt="Carro d">
    <div class="card-info">
      <h3>CITROEN C-3</h3>
      <p>Modelo: Sedan<br>Ano: 2025<br>Cor: Preto chumbo</p>
      <span class="price">R$ 200,00 dia</span>
       <button onclick="alugar('fiat up?')">Alugar</button> 
    </div>
  </div>
  </div>


<script>
  function alugar(modelo) {
    // Aqui você pode decidir a ação
    // Exemplo 1: abrir WhatsApp
    let mensagem = `Olá, tenho interesse em alugar o ${modelo}`;
    let telefone = "5511920028194"; // coloque seu número com DDI e DDD
    let url = `https://wa.me/${telefone}?text=${encodeURIComponent(mensagem)}`;
    window.open(url, "_blank");

    // Exemplo 2 (se preferir apenas um alerta):
    // alert("Você escolheu alugar: " + modelo);
  }
</script>














<style>


    /* Barra de navegação */
    nav {
      background:transparent;
      overflow: hidden;
      height: 450px; /* maior altura pra caber preço */
      position: relative;
    }

    /* Slider ocupa toda a nav */
    .slider-nav {
      width: 100%;
      height: 100%;
      overflow: hidden;
      position: relative;
    }

    .slides {
      display: flex;
      width: 100%;
      height: 100%;
      transition: transform 0.2s ease-in-out;
    }

    .slide {
      min-width: 100%;
      height: 100%;
      flex-shrink: 0;
      position: relative;
    }

    .slide img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    /* Informações do carro (nome + preço) */
    .info-carro {
      position: absolute;
      bottom: 10px;
      left: 20px;
      background: rgba(0,0,0,0.5);
      color: rgb(247, 3, 3);
      padding: 5px 10px;
      border-radius: 50px;
      font-size: 25px;
      font-weight: bold;
    }
   


/*imagem canto superior direito*/
.img-canto {
  position: fixed;     /* fixa na tela */
  top: 60px;           /* distância do topo */
  right: 10px;         /* distância da direita */
  width: 80px;         /* tamanho da imagem */
  height: auto;
  z-index: 1000;       /* garante que fica por cima */
}


/*logos embaixo do texto*/
.logos {
  margin-top: 10px;
  display: flex;
  gap: 10px; /* espaço entre os logos */
  justify-content: center; /* centraliza */
}

.logos img {
  width: 70px; /* tamanho pequeno */
  height: auto;
  cursor: pointer; /* mãozinha ao passar */
  transition: transform 0.2s ease-in-out;
}

.logos img:hover {
  transform: scale(1.2); /* aumenta ao passar o mouse */
}


.button-onclick {
  color: #1d4ed8;
}



/*corpo do site*/
 body {
      margin: 0;
      font-family: Arial, sans-serif;
        /* Imagem no body */
      background: url("https://i.postimg.cc/v8pbKndV/logao.jpg") no-repeat center center fixed;
      background-size: cover;
    }
    

    /* Banner */
   
    .banner-cover{
  /* caminho da sua imagem */
  background: url("https://i.postimg.cc/Rh7fBxVH/carro-jh.png") center/cover no-repeat;
  min-height: 150px;            /* ajuste a altura do banner */
  width: 100%;
  display: grid;
  place-items: center;
  color: #47fe05;                  /* opcional: texto claro */
  padding: 180px;                /* respiro */
}


/*botoes superiores do site*/
.top-buttons {
  position: fixed;      /* sempre fixo na tela */
  top: 0;
  left: 0;
  width: 100%;
  background: #20f704;  /* cor de fundo */
  padding: 10px;
  display: flex;
  justify-content: center; /* centraliza */
  gap: 12px;               /* espaço entre botões */
  z-index: 9999;           /* fica por cima de tudo */
}

.top-buttons button {
  background: #2563eb;    /* azul */
  color: #fff;
  border: none;
  padding: 8px 16px;
  border-radius: 8px;
  font-size: 14px;
  cursor: pointer;
  transition: background 0.3s;
}

.top-buttons button:hover {
  background: #1d4ed8;   /* azul mais escuro ao passar o mouse */
}
   

    

    /* WhatsApp fixo */
    .whatsapp-fixo {
      position: fixed;
      top: 55px;
      left: 15px;
      z-index: 1000;
    }
    .whatsapp-fixo img {
      width: 55px;
      height: 55px;
      border-radius: 50%;
      box-shadow: 0 3px 6px rgba(0,0,0,0.3);
      transition: transform 0.2s;
    }
    .whatsapp-fixo img:hover {
      transform: scale(1.1);
    }

    /* Container */
    .container {
      max-width: 1100px;
      margin: 30px auto;
      background: #3fef20;
      padding: 30px;
      border-radius: 100px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    
    /*titulo*/
    h1 {
      text-align: center;
      margin: 20px 0 10px;
      color: #1904fa;
      margin-top: 100px;
    }


     /*titulos menores*/
    h2{
      text-align: center;
      color: #1d4ed8;


    }
    /* paragrafos*/
    p{
      text-align: justify;
      text-align: center;
      color: red;
    }


    /* Redes sociais */
    .redes-sociais {
      text-align: center;
      margin-bottom: 20px;
    }



    .redes-sociais a {
      margin: 0 8px;
      display: inline-block;
    }
    .redes-sociais img {
      width: 40px;
      height: 40px;
      transition: transform 0.2s;
    }
    .redes-sociais img:hover {
      transform: scale(1.1);
    }



    /* Slider de carros */
    .slider {
      position: relative;
      max-width: 100%;
      margin: 20px auto;
      overflow: hidden;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    .slides {
      display: flex;
      transition: transform 0.5s ease-in-out;
      width: 100%; /* 6 imagens */
    }
    .slides img {
      width: 100%;
      height: 100%;
      object-fit: contain;
      display: block;
      margin: 0 auto;
    }
    .slide {
      min-width: 100%;
    }



    /* Botões do slider */
    .prev, .next {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      background: rgba(0,0,0,0.5);
      color: white;
      border: none;
      padding: 10px;
      cursor: pointer;
      border-radius: 50%;
    }
    .prev { left: 10px; }
    .next { right: 10px; }

  


    /* Dados da empresa */
    .dados-empresa {
      list-style: none;
      padding: 0;
      margin: 20px 0 0;
    }
    .dados-empresa li {
      padding: 8px 0;
      border-bottom: 1px solid #eee;
    }
    .dados-empresa span {
      font-weight: bold;
      color: #444;
    }




.cards-container {
  display: flex;
  gap: 20px;               /* espaço entre os cards */
  justify-content: center;  /* centraliza os cards */
  flex-wrap: wrap;          /* quebra em linha se não couber na tela */
  padding: 20px;
}

.card {
  position: relative;
  width: 300px;             /* cada card lado a lado */
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  transition: transform 0.3s, box-shadow 0.3s;
}

.card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
}

.card:hover {
  transform: translateY(-10px) scale(1.05); /* sobe e aumenta levemente */
   box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08); /* sombra mais transparente */
  transition: transform 0.3s, box-shadow 0.3s;
}

.card-info {
  position: absolute;
  bottom: 0;
  width: 100%;
  background: rgba(0,0,0,0.6);
  color: #fff;
  padding: 15px;
  text-align: center;
}

.card-info h3 {
  margin: 0 0 5px 0;
}

.card-info p {
  font-size: 14px;
  margin: 0 0 10px 0;
  line-height: 1.4;
}

.card-info .price {
  display: block;
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 10px;
  color: #ffd700;
}

.card-info button {
  background: #2563eb;
  border: none;
  color: #fff;
  padding: 8px 16px;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s;
}

.card-info button:hover {
  background: #1d4ed8;
}

/* Responsivo: em telas menores, deixa um card por linha */
@media (max-width: 960px) {
  .cards-container {
    justify-content: center;
  }
}

@media (max-width: 640px) {
  .cards-container {
    flex-direction: column;
    align-items: center;
  }
}


</style>


</body>
</html>
