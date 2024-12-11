# Quirks Mode 
*Antes das implementações de padronização web, cada serviço wweb ou navegador possuia seus próprios padrões, cada um específico. O modo quirks existe para dar suporte a sites criados antes da padronização do W3C, com o layout emulando o comportamento do Navigator 4 e Internet Explorer 5*

* Mode limited-quirks : Existe um número muito pequeno de quirks implementadas;

* Mode no-quirks : Dá suporte seguindo as padronizações web estabelecidos pelo W3C;

# CSS Box Model 

* Margin : Espaço externo ao redor do elemento, ou seja, cria espaço entre o elemento e os seus vizinhos; (entre borda e margem da página)

* Border : Linha que envolve o conteúdo e o padding do elemento, ou seja, define a aparência da borda, como largura, estilo e cor; (entre a margin e o padding)

* Padding : Espaço interno entre o conteúdo do elemento e sua borda, ou seja, dá "respiro" ao conteúdo dentro do elemento; (entre a borda e o conteúdo)

# Box Sizing 

* box-sizing : content-box --> Nesse caso, se você definir a largura de um elemento para 100 pixels, a caixa de conteúdo do elemento terá 100 pixels de largura, e a largura de qualquer borda ou preenchimento será adicionada à largura renderizada final, tornando o elemento mais largo do que 100px.

* box-sizing : border-box (Padrão)--> Diz ao navegador para considerar qualquer borda e preenchimento nos valores que você especificar para a largura e altura de um elemento. Se você definir a largura de um elemento para 100 pixels, esses 100 pixels incluirão qualquer borda ou preenchimento que você adicionou, e a caixa de conteúdo encolherá para absorver essa largura extra. Isso normalmente torna muito mais fácil dimensionar elementos.

# Flexbox (Layout flexível)
*Dar ao contêiner a capacidade de alterar largura/altura/ordem de seus itens para melhor preencher o espaço disponível. Organização e disposição dos itens no layout*

# Uso do div 
*A tag div define uma divisão em um documento HTML, costuma ser usado como um contêiner para outros elementos. Permitindo a criação e uso da Flexbox*

# Variáveis em CSS 

* Escopo Global (:root) = Variáveis que podem ser utilizadas em todo o código do CSS, pois seu escopo sobre todo o documento : 

* Escopo Local : Variáveis declaradasa em um seletor específico, portanto, só podem ser acessadas pelo seletor e seus filhos

```
:root{
    --nome-da-variavel: atribuicao;         escopo global
}

.tag/class{
    --nome-da-variavel: atribuicao;         escopo local
}
```
