# IA4ES

Notas sobre uso de IA em Engenharia de Software, em um estilo mais opinativo e sobre temas ainda não maduros.

## Código Morreu?

# Código Morreu?

Com o avanço dos modelos de linguagem e dos agentes de codificação,
tornou-se comum ouvir que **código morreu**. Consequentemente, não
precisaremos mais escrever e le5 código. É comum ouvir também que vai
ocorrer com código o mesmo que aconteceu com assembly. 

Mas essa comparação com assembly não é boa, na nossa visão. Claro, é verdade que
não programamos mais em assembly, há muito tempo. Mas isso somente aconteceu
porque assembly foi substituído por linguagens de programação que
sempre tiveram uma semântica definida. Essa característica permitiu
o desenvolvimento de compiladores que traduzem
deterministicamente programas escritos nessas linguagens para o nível
mais baixo. 

Porém, essa capacidade de tradução entre níveis de
abstração é perdida quando se usa modelos de IA no desenvolvimento
de software. No caso de LLMs, o nível mais alto são os prompts,
escritos em linguagem natural. E historicamente sabemos que uma
linguagem natural é uma notação verbosa, incompleta e ambígua para
especificar software. Para complicar, LLMs são ferramentas
não-determinísticas, ou seja, sujeitas a erros de tradução, os quais
não acontecem com compiladores.

Por isso, se quisermos decretar a morte de código, precisamos eleger um
substituto, assim como ocorreu com assembly. E, conforme afirmamos,
esse substituto, pelo menos de uma forma ubíqua, não serão textos
em linguagem natural.

Concluindo, considerando que será difícil eleger um substituto universal para
código, devemos caminhar para uma realidade de
desenvolvimento de software fragmentada:

- Com um pouco mais de documentação textual, mas sempre ainda parcial.

- Claro, com muito mais código gerado por LLMs.

- Com níveis de revisão de código, desde nenhuma revisão (para código
  menos crítico) até uma revisão humana e detalhada, para as partes mais
  sensíveis e com mais risco.

Uma nova responsabilidade de engenheiros de software será então 
saber "dosar" cada um dos itens acima. Isto é, tomar as decisões sobre 
o que vale documentar e qual o nível de revisão será preciso em cada 
parte de um sistema.
