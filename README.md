<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTATO COM A TERRA MÉDIA</title>
    <link rel="stylesheet" href="/Ola-mundo-main/MAIS/styles.css">
</head>
<body>
    <div id="titulo_principal">
            <h1>O Senhor dos Anéis</h1>
            <h2>Uma das maiores trilogias da história do cinema</h2>
            <nav>
              <a href="index.html">Home</a>
              <a href="sinopse.html">Sinopse</a>
              <a href="imagem.html">Imagem do filme</a>
              <a href="personagensprincipais.html">Personagens principais</a>
              <a href="informacoes.html">Informacões</a>
              <a href="ordemdosfilmes.html" >Ordem dos filmes da triologia</a>
              <a href="Curiosidades.html">Curiosidades</a>
              <a href="Impacto.html ">Impancto Cultural</a>
              <a href="contato.html">Contato</a>
              <a href="contato com a terra média.html">contato com a terra média</a>
            </nav>
        </div>

        <h2 class="titulo_secundario">CONTATO COM A TERRA MÉDIA</h2>
       <p>Envie uma mensagem diretamente para o conselho de Elrond</p>
        <form autocomplete="off"> 

        <label for="nome pessoa">Seu nome na terra média</label>
            <input type="text" name="nome pessoa"
            id="nome pessoa" minlength="3" maxlength="15"
            required placeholder="Ex:Aragorn"><br><br> 

            <label for="email">corvo eletrônico</label>
            <input type="email" name="email" id="email" required>
            <button type="submit">Enviar</button><br><br>

             <label for="ano"> Ano de nascimento</label>
            <input type="number" id="ano" name="ano" max="2026" min="1000"><br><br>

             <fieldset>
                    <legend>Qual é a sua raça?</legend>

                    <label>
                        <input type="radio" name="Raça" value="Humano"> Humano
                    </label>

                    <label>
                        <input type="radio" name="Raça" value="Elfo"> Elfo
                        
                    </label>

                    <label>
                        <input type="radio" name="Raça" value="Anao"> Anão
                    </label>

                    <label>
                        <input type="radio" name="Raça" value="Hobbit"> Hobbit
                    </label>

                </fieldset><br>
                
                <legend>Qual é o seu filme favorido?
                     <select>
                <option value="Filme 1"> A sociedade do Anél</option>
                <option value="Filme 2"> As duas Torres</option>
                <option value="Filme 3"> O Retorno do Rei</option>
                     </select>
                </legend><br>

                <legend>Escolha um local da terra média:
                     <select id="local">
                        <optgroup label="Reino dos homens">
                                   <option value="Gondor">Gondor</option>
                                   <option value="Rohan">Rohan</option>
                        </optgroup>
                        <optgroup label="Terras Elficas">
                                  <option value="Valfenda">Valfenda</option>
                                  <option value="Lothlórien">Lothlórien</option>
                        </optgroup>
                        <optgroup label="Outros">
                                  <option value="Mordor">Mordor</option>
                                  <option value="Condado">Condado</option>
                        </optgroup>
                     </select>
                </legend><br>

                 
        <fieldset><legend>Suas habilidades:</legend>
            <label> <input type="checkbox" name="Espada">Espada</label>
            <label> <input type="checkbox" name="Arco e Flecha">Arco e Flecha</label>
            <label> <input type="checkbox" name="Magia">Magia</label>
            <label> <input type="checkbox" name="Furtividade Hobbit">Furtividade Hobbit</label>
        </fieldset><br>

         
        <label for="nivel">Nivel de coragem (1 a 10):</label>
        <input type="range" max="10" min="1" id="nivel" name="nivel"><br><br>


        <label for="Test">Seu reino de Origem:</label>
        <input type="text" id="busca_datalist" list="local" >
        <datalist id="local">
            <option>Gondor</option>
            <option>Rohan</option>
            <option>Valfenda</option>
            <option>Lothlórien</option>
            <option>Mordor</option>
            <option>Condado</option>
        </datalist><br><br>

         <label for="cor">Escolha a cor do seu Manto:</label>
            <input type="color" id="cor" name="cor"><br><br>

         <label for="data">Data da sua jornada:</label>
            <input type="date" name="data"  id="data"><br><br>

         <label for="file">Anexe uma Reliquia:</label>
            <input type="file" id="arquivo" name="arquivo"><br><br>

         
            <label for="descrição">Envie uma Mensagem ao Conselho:</label> <br> <br>
            <textarea cols="30" rows="5" name="descricao" id="descricao">
            </textarea><br><br>

            <button type="submit">Enviar Para Valfenda</button><button type="reset">Apagar Pergaminho</button>
            
         </form>
                
             




























        </body>
