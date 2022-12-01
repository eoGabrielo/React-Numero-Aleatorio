# Gerador de números React (0 a 100)

Projeto desenvolvido em React com a plataforma da DevMedia, separado em um componente  toda a lógica da aplicação em JavaScript e a utilização da ferramenta useState do react.<br>
O useState é uma variável com estada, aonde podemos atribuir um evento a ela e conseguir alterá-la dependendo do evento e sua lógica, nesse caso foi utilizado uma lógica JavaScript para gerar um número aleatório que sera atribuído a variável de estado (useState).
## Lógica
Código desenvolvido com a lógica de ao aperta um botão sera chamado uma function JS que ira realizar um cálculo inteiro que retorna um valor entre 0 a 100, para gerar esse valor aleatório usamos um método nativo do JS -> Math.random(), porém esse método retorna somente números menores que 0, para ter um resultado desejado precisamos fazer um cálculo desse método random multiplicado por até quantos queremos <strong> Math.random() * 10 </strong>, lembrando que precisamos colocar +1, pois ele sorteia até um número antes do multiplicado.
Com isso atribuímos o valor ao useState que sera mostrado com o nome de sua variável no documento HTML.
