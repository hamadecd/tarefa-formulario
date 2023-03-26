# Tarefa Individual - Formulário

Crie um formulário que possua os seguintes dados:
<ol>
<li>Nome completo
<li>E-mail
<li>Telefone
<li>Tipo de telefone
<ul>
<li>casa
<li>trabalho
<li>celular
</ul>
<li>Endereço
<ul>
<li>logradouro
<li>cidade
<li>estado
<li>cep
<li>país
</ul>
</ol>

O formulário deve ser preenchido com os valores padrões abaixo, via JavaScript:
```
const dados = {
    nome: "Ada Lovelace",
    email: "ada@email.com,
    telefones: [
        { 
            numero: "(11) 99123-4567",
            tipo: "casa"
        }
    ],
    endereco: {
        logradouro: "Rua das programadoras",
        cidade: "Vale do silício",
        estado: "Codefornia",
        cep: "10100-100",
        pais: "Programaland"
    }
}
```
Ao ser digitado um novo nome, o valor padrão (dados) deve ser alterado e retornado no console.
