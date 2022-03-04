# Iniciando 
## npm install

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Avaliação de codigo
```

class CampoDeBusca extends React.Component{

    // inicializando objeto "state" para armazenar os valores da propriedade "entry" do componente.
    state = {entry: ''}
    // esse metodo é chamado sempre que ouver uma alteração no input 
pegaAlteracaoNoElemento(event){
    console.log(event.target.value);
}

    render(){
        return(
            <div className='ui segment'>
                {/* ClassName adicionado ao fomulário */}
                <form className='ui form'>
                    <div className='field'>
                        <div className='ui massive icon input'>

                            {/* referencia ao objeto evento */}
                            <input type="text" placeholder='pesquisa...' onChange={(event)=>console.log(event.target.value)}/>
                            
                            <i className='search icon'></i>
                        </div>
                    </div>
                </form>
            </div>
        )
    }
}
export default CampoDeBusca;
```

No diretorio do projeto rode o comando:

### `npm start`

Rode em modo desenvolvedor

Abra [http://localhost:3000](http://localhost:3000) para visualizar no Brownser

## Link do CDN
## `https://cdnjs.com/libraries/semantic-ui`

### Oque foi estudado
 - Objeto state para armazenar os valores da propriedade
 - Componente de Classe
 - Componente funcional sem estado
 - Componente controlado
 - Função CallBack
## Descrição

- Controlando o compunente "Input",  foi criado uma função que é chamada a cada inserção de dado no elemento.



