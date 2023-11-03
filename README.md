<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MYRECIPES</title>
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />
    <link href="style.css" rel="stylesheet" />
    <script src="crud.js" defer></script>
  </head>

  <body>
    <div id="mensagem">Salvo</div>
    <header>
      <h1>Minhas Receitas</h1>
    </header>

  <div id="btn-create">
      <h2>Adicionar nova receita</h2>
      <img src="css/add-circle-outline.svg" alt="">
    </div>

   <div id="lista-modal">
      <ul id="lista">
        <li id="vazio">
          <h2>Nenhuma receita adicionada.</h2>
        </li>
      </ul>

 <div id="modal">
        <div id="add-receita">
          <header id="modal-title">
            <h1 id="modal-modo">Nova receita</h1>
            <i id="x" class="bx bx-x"></i>
          </header>

   <form id="myform">
            <div id="myform-pai">
              <div id="div-nome">
                <input
                  type="text"
                  id="nome"
                  class="book-field"
                  placeholder="Nome da receita"
                  required
                />
              </div>
              <div id="myform-row">
                <div id="div-tempo">
                  <input
                    type="text"
                    id="tempo"
                    class="book-field"
                    placeholder="Tempo de preparo"
                    required
                  />
                </div>
                <div id="div-rend">
                  <input
                    type="text"
                    id="rendimento"
                    class="book-field"
                    placeholder="Rendimento"
                    required
                  />
                </div>
              </div>
              <div id="form-column">
                <div id="div-ingre">
                  <textarea name="ingredientes" id="ingredientes"  class="book-field" rows="5" placeholder="Ingredientes"></textarea>
                  <!-- <input
                    type="text"
                    id="ingredientes"
                    class="book-field"
                    placeholder="Ingredientes"
                    required
                  /> -->
                </div>
                <div id="div-preparo">
                  <textarea name="preparo" id="preparo" class="book-field" rows="5" placeholder="Modo de preparo"></textarea>
                  <!-- <input
                    type="text"
                    id="preparo"
                    class="book-field"
                    placeholder="Modo de preparo"
                    required
                  /> -->
                </div>
              </div>
            </div>
          </form>

<footer id="modal-footer">
            <button id="salvar" class="btn-save">Salvar</button>
            <button id="cancelar" class="btn-cancel">Cancelar</button>
          </footer>
        </div>
      </div>


      
<div id="view">
        <div class="fechar">
          <div id="btn">
            <div id="edit-btn">
              <p>Editar</p>
            </div>
            <div id="delete-btn">
              <p>Excluir</p>
            </div>
          </div>
          <i class="bx bx-x" id="x2"></i>
        </div>
        <div id="view2">
          <div class="nome">
            <h2 id="nome"></h2>
          </div>
          <div class="info">
            <div class="tempo">
              <h3>Tempo:</h3>
              <p id="tempo"></p>
            </div>
            <div class="rend">
              <h3>Rendimento:</h3>
              <p id="rend"></p>
            </div>
          </div>
          <div class="ingred">
            <h3>Ingredientes:</h3>
            <p id="ingred">ddddds</p>
          </div>
          <div class="preparo">
            <h3>Modo de preparo:</h3>
            <p id="preparo"></p>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
