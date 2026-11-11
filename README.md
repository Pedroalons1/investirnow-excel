# --investirnow-excel
Ferramenta em Excel para simular investimentos, dividendos e metas por perfil (VF, PGTO, NPER, PROCV e validação de dados).
Investirnow: Ferramenta de Controle de Investimentos em Excel

Projeto prático do Bootcamp DIO "Reclame AQUI: Dados e IA na Prática".


O PROBLEMA

Muita gente quer começar a investir, mas não sabe quanto vai juntar com o tempo, quanto renderia em dividendos ou como dividir o dinheiro entre tipos de fundos. Criei uma ferramenta simples em Excel que responde essas perguntas em poucos cliques.


O QUE A FERRAMENTA FAZ

• Calcula o patrimônio acumulado e os dividendos mensais a partir do aporte, do prazo e da rentabilidade.

• Projeta cenários de 2, 5, 10, 20 e 30 anos.

• Sugere um aporte de 30% do salário e compara com o valor informado.

• Divide o aporte entre tipos de FII (Papel, Tijolo, Híbridos, FOFs, Desenvolvimento e Hotelaria) conforme o perfil escolhido: Conservador, Moderado ou Agressivo.

• Mostra a divisão em gráficos de pizza que mudam junto com o perfil.

• Calcula metas: quanto investir por mês para chegar a um valor e em quanto tempo os dividendos chegam a uma renda desejada.

FERRAMENTAS E TÉCNICAS

• Excel

• Funções financeiras VF, PGTO e NPER

• PROCV com chave composta (perfil + tipo de fundo) buscando em uma aba de apoio

• Validação de dados (lista suspensa de perfis)

• Intervalos nomeados (aporte, meta, meta_dividendos, patrimonio, taxa_mensal, qdt_anos, rendimento_carteira, salario, sugestao_investimento)

• Referências absolutas

• Gráficos dinâmicos e formatação personalizada (oculta fatias de 0%)

• Layout de painel: células de entrada em branco e cálculos em cinza


EXEMPLO DE RESULTADO

Investindo R$ 200 por mês por 5 anos, com rentabilidade de 1,08% ao mês:

• Patrimônio acumulado: R$ 16.760,80

• Dividendos mensais: R$ 134,09

• Em 30 anos: R$ 866.780,96

• Para juntar R$ 100.000 em 5 anos: R$ 1.193,26 por mês

• Para ter R$ 1.000 de dividendos por mês investindo R$ 200: cerca de 191 meses (15,9 anos)


IMAGENS
<img width="886" height="623" alt="image" src="https://github.com/user-attachments/assets/0cfc6b3d-6096-4532-a0a2-ee35f38a979e" />
<img width="886" height="611" alt="image" src="https://github.com/user-attachments/assets/66997eb0-7bd0-4f16-b9f4-6f577969ee3a" />
<img width="808" height="564" alt="image" src="https://github.com/user-attachments/assets/2f5a3610-7184-48f6-9492-14a6e51d43fd" />
<img width="799" height="547" alt="image" src="https://github.com/user-attachments/assets/c7e595f4-09c6-4fb0-9f6c-8c3dc627d699" />


COMO USAR

1. Baixe o arquivo Investirnow.xlsx.

2. Preencha as células brancas: salário, aporte, prazo e taxas.

3. Escolha o perfil na lista suspensa.

4. Veja os resultados, os cenários e os gráficos se atualizarem.


O QUE APRENDI

Organizar uma planilha como ferramenta para outra pessoa usar: separar entradas de cálculos, usar nomes no lugar de endereços de célula e buscar dados em uma tabela de apoio, para que tudo mude automaticamente.


AVISO

Simulação para fins de estudo. Os percentuais por perfil são exemplos e não são recomendação de investimento.


AUTOR

Pedro Alonso, analista de dados em formação

LinkedIn: https://www.linkedin.com/in/pedro-alonso-301202255/
