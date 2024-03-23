<script>
  function copiarTexto() {
    // Define o texto a ser copiado
    var texto = "rafachaffin";

    // Cria um elemento de texto temporário
    var tempInput = document.createElement("input");

    // Define o valor do elemento de texto como o texto desejado
    tempInput.value = texto;

    // Adiciona o elemento de texto temporário ao corpo do documento
    document.body.appendChild(tempInput);

    // Seleciona o texto no elemento de texto temporário
    tempInput.select();

    // Copia o texto selecionado para a área de transferência
    document.execCommand("copy");

    // Remove o elemento de texto temporário
    document.body.removeChild(tempInput);

    // Alerta o usuário que o texto foi copiado
    alert("Texto copiado: " + texto);
  }
</script>

## Olá! Eu sou o Rafa Chaffin. 🖐🏻
### Seja bem-vindo ao meu perfil!
Sou um estudande de Ciência da Computação na UFRJ e tenho interesse na área Data Science e IA. 

### Contato
<div style="display: inline_block"></br>
    <img align="center" alt="discord" src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white
    "onclick="copiarTexto()" style="cursor:pointer;"/>
</div>
