# Automação de Processos em primeiro plano com Phyton.

![Untitled](Automac%CC%A7a%CC%83o%20de%20Processos%20em%20primeiro%20plano%20com%20Phy%20922dbafb3ed54cb8841be27ecdb24328/Untitled.png)

O desafio da primeira aula do curso intensivo de Phyton, foi desenvolver uma automação para enviar relatórios do sistema de uma empresa para o e-mail da diretoria diariamente.

### Intro

Usamos a plataforma Jupyter Notebooks, que é uma ferramenta gratuita dentro do Anaconda. 

Para desenvolver nossa autoamação, usamos algumas bibliotecas e as importamos: [pyautogui](https://pyautogui.readthedocs.io/en/latest/) (ferramenta de automação, controle do mouse, teclado e etc) , time (ferramenta que facilita no desenvolvimento de códigos que precisam de tempo de espera), [pyperclip](https://pyperclip.readthedocs.io/en/latest/) (ferramenta que permite copiar e colar via Phyton) e [pandas](https://pandas.pydata.org/docs/user_guide/index.html#user-guide) (biblioteca para trabalhar com analise de dados, planinlhas com diversos formatos, excel, sql e etc). 

### Conteúdo

Para desenvolver nossa automação, fizemos um passo a passo (lógica para a automação), após isso importamos as bibliotecas necessárias.

No primeiro bloco fizemos a automação com o [pyautogui](https://pyautogui.readthedocs.io/en/latest/) para o computador entrar no sistema da empresa e baixar o relatório de vendas. Usando o [pyautogui](https://pyautogui.readthedocs.io/en/latest/).position você consegue obter a posição para o mouse clicar e para cada monitor/resolução será uma posição diferente. 

No segundo bloco nós importamos e lemos o relatório salvo usando o [pandas](https://pandas.pydata.org/docs/user_guide/index.html#user-guide) para no terceiro bloco calcularmos o faturamento e quantidade de produtos vendidos para enviarmos o e-mail.

No quarto bloco usamos novamente o [pyautogui](https://pyautogui.readthedocs.io/en/latest/) para enviarmos o e-mail com os dados atualizados.