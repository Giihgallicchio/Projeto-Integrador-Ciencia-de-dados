# | PROJETO INTEGRADOR - CIÊNCIA DE DADOS

## | Tema do Projeto
<h1>Saúde Mental no Trabalho no Setor de Tecnologia</h1>



## | Autora
- Giovanna Galichio  


## | Descrição do Projeto

<p>Este projeto tem como foco a análise e o tratamento de dados relacionados à saúde mental no ambiente de trabalho, especialmente no setor de tecnologia. Com o aumento da pressão por produtividade e a constante necessidade de atualização profissional, questões como estresse, ansiedade e outros problemas psicológicos têm se tornado cada vez mais comuns.</p>

<p>A proposta do projeto é utilizar dados reais para compreender melhor esse cenário, aplicando técnicas de limpeza, padronização e organização dos dados para torná-los adequados para análise.</p>


## | Objetivo da Análise

<p>O objetivo principal é preparar e estruturar os dados para análise, permitindo:</p>

<ul>
    <li>Identificar padrões relacionados à saúde mental;</li>
    <li>Analisar o impacto no ambiente de trabalho;</li>
    <li>Relacionar fatores como idade, país e suporte organizacional;</li>
    <li>Facilitar futuras análises e visualizações.</li>
</ul>


## | Base de Dados

<p>Fonte: <a href="https://www.kaggle.com/code/chaitanya99/mental-health-in-tech-survey-eda" target="_blank">Kaggle</a></p>

<p>O dataset utilizado contém informações de profissionais da área de tecnologia, abordando temas como histórico de saúde mental, acesso a tratamento, ambiente de trabalho e suporte organizacional.</p>


## | Processamento de Dados (ETL)

<p>Os dados foram tratados utilizando Python e a biblioteca Pandas, seguindo o processo de ETL:</p>

<ul>
    <li><strong>Extração:</strong> Leitura do arquivo original <code>survey.csv</code>.</li>

    <li><strong>Transformação:</strong>
        <ul>
            <li><strong>Tradução completa:</strong> Todo o dataset foi traduzido para português (colunas e valores);</li>
            <li><strong>Padronização:</strong> Conversão de valores como "Yes/No" para "Sim/Não";</li>
            <li><strong>Tratamento de nulos:</strong> Preenchimento com "S/N" ou "Sem Informações";</li>
            <li><strong>Limpeza de dados:</strong> Correção de inconsistências (idade, estados inválidos, categorias incorretas);</li>
            <li><strong>Padronização geográfica:</strong> Organização de países e estados;</li>
            <li><strong>Formatação de datas:</strong> Ajuste da coluna de data;</li>
            <li><strong>Remoção de colunas irrelevantes:</strong> Exclusão de campos desnecessários como comentários;</li>
        </ul>
    </li>

    <li><strong>Carga:</strong> Exportação do dataset tratado para <code>survey_Dados_Tratados.csv</code>.</li>
</ul>


## | Ideia do Projeto

<p>O foco do projeto foi garantir a qualidade e organização dos dados para possibilitar análises futuras e criação de dashboards.</p>

<p>Com os dados tratados, torna-se possível identificar relações entre fatores como ambiente de trabalho, suporte organizacional e saúde mental dos profissionais.</p>


## | Estrutura do Projeto
├── Projeto_Integrador_Ciencia_de_dados.ipynb
├── survey_Dados_Tratados.csv
├── README.md
└── LICENSE


## | Resultado

<p>Ao final do projeto, foi gerado um dataset limpo, padronizado e totalmente traduzido, pronto para análise exploratória e criação de dashboards.</p>


## | Tecnologias utilizadas

- Python  
- Pandas  
- Google Colab  
