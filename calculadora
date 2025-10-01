import { useState } from "react";
import Button from "./button";

const Contador = () =>{
    const [contador,setContador]=useState(0);
    function Aumentar(){
            setContador(contador +1);
    }
    function Disminuir(){
            setContador(contador -1);
    }
    const ImputNumber = (num) => setContador(num);
    return(
        <div>
            <label>contador {contador}</label>
            <br/>
            <button onClick={Aumentar}>Aumentar</button>
            <button onClick={Disminuir}>Disminuir</button>
            <br/>
            <Button onClick={()=>ImputNumber(1)}>1</Button>
            <Button onClick={()=>ImputNumber(2)}>2</Button>
            <Button onClick={()=>ImputNumber(3)}>3</Button><br/>
            <Button onClick={()=>ImputNumber(4)}>4</Button>
            <Button onClick={()=>ImputNumber(5)}>5</Button>
            <Button onClick={()=>ImputNumber(6)}>6</Button><br/>
            <Button onClick={()=>ImputNumber(7)}>7</Button>
            <Button onClick={()=>ImputNumber(8)}>8</Button>
            <Button onClick={()=>ImputNumber(9)}>9</Button><br/>
            <Button onClick={()=>ImputNumber(0)}>0</Button>
        </div>
    );
};

export default Contador;
