<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    
    <title>Formulario</title>
    <style>
      body{
        font-family: Arial, Helvetica, sans-serif;
        background-image: linear-gradient(to right,rgb(10, 167, 10), black  );
      }
      .box{
        color: white;
        position: absolute; 
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
        background-color: rgba(0, 0, 0, 0.8);
        padding: 15px;
        border-radius: 15px;
       
      }
      fieldset {
        border: 3px solid white;
      }
      legend{
        border: 1px solid white;
        padding: 10px;
        text-align: center;
        background-color:green;
        border-radius: 5px;
      }
      .inputBox {
        position: relative;
      }
      .inputuser {
        background: none;
        border: none;
        border-bottom: 1px solid white;
        outline: none;
        color:white;
        font-size: 15px;
        width: 100%;
        letter-spacing: 2px;
      }
     .labeLInput {
      position: absolute;
      top: 0px;
      left: 0px;
      pointer-events: none;
      transition: .5s;
         }
      </style>
</head>
<body>
    <div class="box">
      <form action="">
        <fieldset>
            <legend><b>Ficha de Cadastro</b></legend>
            <br><br>
            <div class="inputbox">
               <input type="text" name="nome" id="nome" class="inputuser" required>
               <label for="nome" class="LabelInput">Nome Completo</label>
            </div>
            <br><br>

            <div class="inputbox">
              <input type="email" name="nome" id="email" class="inputuser" required>
              <label for="nome" class="LabelInput">Email</label>
           </div>
           <br><br>

           <div class="inputbox">
            <input type="tel" name="telefone" id="telefone" class="inputuser" required>
            <label for="telefone" class="LabelInput">Telefone</label>
         </div>
         <br><br>    

         <p>Sexo:</p>
          <input type="radio" id=feminino name="genero" value="Feminino" required>
          <label for="feminino">Feminino</label>
          <input type="radio" id=masculino name="genero" value="masculino" required>
          <label for="masculino">Masculino</label>
          <input type="radio" id=outro name="genero" value="outro" required>
          <label for="outro">outro</label>
          <br><br>

          <div class="inputbox">
            <label for="data_nasc"><b>Data de Nascimento:</b></label>
            <input type="date" name="data_nasc" id="data_nasc" class="inputuser" required>
          </div>
          <br><br> 
          
          <div class="inputbox">
            <input type="text" name="cidade" id="cidade" class="inputuser" required>
            <label for="Cidade" class="LabelInput">Cidade:</label>
          </div>
          <br><br>

          <div class="inputbox">
            <input type="text" name="estado" id="estado" class="inputuser" required>
            <label for="estado" class="LabelInput">Estado:</label>
          </div>
          <br><br>

          <div class="inputbox">
            <input type="text" name="endereco" id="endereco" class="inputuser" required>
            <label for="endereco" class="LabelInput">Endereço:</label>
          </div>
          <br><br>

          <input type="submit" name="submit" id="submit">


            
        </fieldset>
      </form>

    </div>
</body>
</html>
