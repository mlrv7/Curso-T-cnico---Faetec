<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    
    <title>Formulário</title>
    
</head>
<body>
    <style>
        body{font-family: 'Times New Roman', Times, serif}
        label {display: inline-block;  width: 200px;}
 
    </style>


    <form action="">
     
        <p><div style="text-align: center;"><b><u>Formulário de Pesquisa</u></b>
        </div></p>
<br>


<div>
    <label for="nome">Digite seu Nome:</label>
    <input type="text" nome="nome" id="nome" class="inputUser" size="40" required>
</div>
<div>
    <label for="endereço">Digite seu End.:</label>
    <input type="text" nome="endereço" id="endereço" class="inputUser" size="40" required>
</div>
<div>
    <label for="bairro">Bairro:</label>
    <input type="text" nome="bairro" id="bairro" class="inputUser" size="20" required>
</div>
<div>
    <label for="cidade">Cidade:</label>
    <input type="text" nome="cidade" id="cidade" class="inputUser" size="20" required>
</div>

<div>
    <label for="estado">Estado:</label>
    <select>
        <option>Escolha um Estado</option>
    </select>
</div>
 
<div>
    <label for="cep">CEP:</label>
    <input type="text" nome="cep" id="cep" class="inputUser" size="10" required>
</div>
<div>
    <label for="telefone">Telefone:</label>
    <input type="text" nome="telefone" id="telefone" class="inputUser" size="20" required>
</div>
<div>
    <label for="email">Email:</label>
    <input type="text" nome="email" id="email" class="inputUser" size="20" required>
</div>

<br>

<p><div style="text-align: center;">Para facilitar suas futuras compras, Iremos gravar o<br>
    seu cadastro em nosso Banco de Dados.<br>
    Para isso, basta criar sua Identificação e uma Senha e usá-las em suas<br>
    próximas visitas ao site.<br>
    </div> 

<br>

<b><div>
    <li><b><label for="user">Identificação:</label></b>
    <input type="text" nome="user" id="user" class="inputUser" size="10" required></li>
</div>
<div>
    <li><label for="password">Senha:</label>
    <input type="password" nome="password" id="password" class="inputUser" size="3" required></li>
</div>
<div>
    <li> <label for="password">Para confirmar, digite novamente <br> a sua senha aqui:</label>
    <input type="password" nome="password" id="password" class="inputUser" size="3" required></li>
</div>
<div>
    <li><label for="nickname">Como você gostaria de ser chamado?</label>
    <input type="nickname" nome="nickname" id="nickname" class="inputUser" size="10" required></li>
</div></b>

<br>

<div style="text-align: center;">
<button type='submit'>Enviar Formulário</button>
<button type='reset'>Limpar Campos</button>
</div>
  
</form>
  </form>
    </body>
      </html>
