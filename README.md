# estatistica
Trabalho de estatística

## Sobre o trabalho

Escrever sobre (definição, exemplos, provas e etc) sobre o princípio fundamental da 
contagem, permutações simples, arranjos, combinações, permutações com elementos 
repetidos.

Fazer, para cada tópico, duas questões e provar as fórmulas de arranjo e combinação.

Lembrando: +1 ponto extra na média (da unidade)

## Olá, Andressa, bem vinda ao nosso planeta

Eu sei que é meio loucura entrar em um novo ambiente e tudo mais, mas é
bom para você ir se acostumando aqui, sou seu guia local e espero que possa
te fazer ter uma boa experiência.

### Inicialmente o que você vai precisar é instalar:

- O git (gerenciador de pacotes para o github)
- O texstudio (editor de texto latex)
- O pacote latex (Miktex, acho que esse só pra windows, mas não tenho certeza)

### Usando o git

- `git clone https://github.com/itepifanio/estatistica.git` irá baixar esse
 repositório na sua máquina.
- `git checkout -b branch_andressa` o git ele ramifica em várias versões o nosso documento.
você irá criar uma versão sua e escrever nela, esse comando cria uma branch nova chamada
branch_andressa.
- `git add .` esse comando irá adicionar todas as suas modificações locais para o github
- `git commit -m "Fiz isso e isso e isso"` um commit é uma instrução do que você fez 
nas suas modificações, ele orienta as outras pessoas que veem suas modificações.
- `git push origin branch_andressa` finalmente, com esse comando você envia suas alterações 
para o github. Git add e git commit servem apenas para você gerenciar os arquivos que você
quer mandar e a mensagem, respectivamente, o git push armazena no site tudo que você fez.

### Usando Latex

Eu criei um repositório organizado. Todas as configurações dos documentos ficam em document.tex
que você pode ver na raiz do projeto, acredito que você não vá precisar modificar nada ali. 

Para você não mexer com nada demais de configurações bestas eu separei as pastas: esqueleto, 
imagens e anexo. O esqueleto contém todas as seções do trabalho, basta apenas escrever o que você
tem que escrever ali.

#### Sections

O latex divide o tamanho dos títulos das seções através de \section, \subsection, \subsubsection e 
\paragraph. Todas as seções do esqueleto estão dentro de uma \section por exemplo. Acho que você
pega isso melhor depois de eu mostrar alguns exemplos.

#### Figures

Para inserir figuras use: 

```
\begin{figure}[H]
	\centering
	\caption{Legenda que fica por cima da imagem}
	\includegraphics[width=7cm]{imagens/caminhoParaAImagemEscolhida.png}
	\legend{Fonte: Aqui você coloca uma fonte bonitinha tal qual "Elaborado pelo autor"}
	\label{issoAquiUsamosParaReferênciasFuturas}
\end{figure}

```

Tá vendo esse [H]? Ele fixa a imagem depois do texto que você escreveu. Existem vários tipos de
configurações para usar ai, além do [H] pode-se utilizar [!htb] que mescla meio que automático
os campos das imagens

#### Equations 

Existem várias formas de definir equações em latex. No meio de um texto você usa: "Energia é dado 
por $E=mc^2$

Para criar uma quebra de linha centralizada na equação você utiliza:

```
\begin{equation}
	x^2 + y^n = z^n
\end{equation}
```

### Orientações gerais

Tenha um pouco de paciência pra usar. Eu acho isso aqui maravilhoso e geralmente só faço trabalhos 
por aqui, é bem prático depois que se pega no tranco.

### Qualquer dúvida

Email: italoepifaniols@gmail.com

Telefone: (84) 99815-3219

Alternativamente: Usar sinal de fumaça
