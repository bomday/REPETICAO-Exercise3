<h2>PROBLEM STATEMENT: O lugar ideal</h2>
---
<p>Finalmente, férias! Depois de tanto estudo, você e seus amigos decidem que merecem descansar e relaxar. Ou talvez viajar. Quem sabe vocês devessem ir ao museu? Ou seria melhor pegar um cinema?</p>
<p>Foi tanta indecisão que após uma semana de férias, vocês ainda não fizeram nada!
<br/>
Decididos a escolher um lugar de uma vez por todas, vocês resolvem colocar seu conhecimento de programação em prática para escrever um código que lhe dirá onde aproveitar esse tempinho livre.
<br/>
Ficou estabelecido que decisão acontecerá em forma de votação. O melhor lugar será aquele que possuir o maior total de pontos, enquanto o pior lugar, o que possuir o menor total.</p>
<h3>Input</h3>
---
<p>A primeira entrada é um inteiro N ≥ 2 que representa o total de lugares que serão sugeridos.</p>
- N
<br/><br/>
<p>Em seguida, o programa receberá uma string contendo o nome do lugar sugerido.</p>
- nome_lugar
<br/><br/>
<p>A sugestão então receberá um número indefinido de notas, parando quando uma das notas tiver um valor menor que 0 (o valor negativo não deve contar para o total de pontos que uma sugestão recebeu).</p>
- notaX 
<br/><br/>
<p>Esse processo se repetirá N vezes.</p>
<h3>Output</h3>
---
<p>Se não ocorrer empate para o melhor_lugar</p>
-> {melhor_lugar} ganhou de lavada de {pior_lugar}, com {maior_nota} vs {pior_nota}
<br/><br/>
<p>Se ocorrer empate para melhor_lugar</p>
-> {melhor_lugar1}, {melhor_lugar2}, (…) , {melhor_lugarN} \n Tantas opções
<br/><br/>
<p>OBS: Não existem casos onde seja preciso imprimir mais que um pior_lugar</p>
<p>OBS2: Em caso de empate, os lugares vão ser mostrados separados por vírgula e em ordem de entrada. Lembrem-se que vocês ainda não podem usar listas, pensem em uma outra maneira de armazenar a informação dos melhores lugares</p>