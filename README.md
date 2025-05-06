@import "tailwindcss";


body {
  background-color: rgb(64, 60, 60);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
}
.bloco{
  display: flex;
  background-color: rgba(11, 5, 16, 0.851);
  border-radius: 8px;
}

.Valor {
  color: darkgreen;
}

.Saida {
  color: crimson;
}

.item{
  justify-content: space-between;
}

export default function home(){
  return(
    <div className="bloco">
    <div className="item">
       <h3>entradas</h3>
       <p className="Valor">R$ 7.840,56</p>
       <span>Somada todas as entradas do período</span>
       </div>
    <div className="item">
    <h3>Saída</h3>
       <p className="Saida">R$ 7.840,56</p>
       <span>Somada todas as saídas do período</span>
    </div>
    <div className="item">
    <h3>Balanços</h3>
       <p className="Valor">R$ 7.840,56</p>
       <span>Somada todas as entradas e saídas do período</span>
    </div>
</div>
  )
}

