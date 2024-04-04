- HTML

 *Tags*

    <h1>Titulo</h1>

    <a href="">Link</a>

    <table>
      <thead>
        <tr>
          <th>
            Tabela - Cabeçalho - Linhas/Colunas - Conteúdo
          </th>
        </tr>
      </thead>
      <tbody id=""></tbody>
    </table>

 *Atributos*

    <thead width="100%></table>
    
    <tbody id=""></tbody>

- CSS




- JS

 *Variaveis*

  - Quando o valor não vai ser alterado se usa:
        
        const mensagem = "Hello"
  
  - Quando o valor precisar ser alterado se usa:
  
        let mensagem = "Olá"

 *Tipo de Dados*

    - Number
    - String

 *Função*

      alert("ERRO")

      document.getElementById()
    
      document.querySelector('tbody')

 *Extenções*

    <script src="https://cdn.jsdelivr.net/npm/dayjs@1/dayjs.min.js"></script> 
    <script src="https://cdn.jsdelivr.net/npm/dayjs@1/plugin/relativeTime.js"></script>
    <script>dayjs.extend(window.dayjs_plugin_relativeTime)</script>

  - Dois jeitos de usar:
  
        const dataInscricao = dayjs(participante.dataInscricao).format("DD/MM/YYYY HH:mm)
                              dayjs(Date.now()).to(participante.dataInscricao)