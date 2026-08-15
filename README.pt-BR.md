<div align="center">
  <img src="banner.jpg" alt="Caio Gadotti, Desenvolvedor de Automação Industrial" width="100%"/>
</div>

# Caio G

**Desenvolvedor de Sistemas | Automação Industrial e Otimização de Processos**

[English](README.md) &nbsp;·&nbsp; **Português**

---

## Sobre

Desenvolvo sistemas integrados voltados a automação industrial, controle operacional e otimização de processos. Meu trabalho fica na fronteira entre desenvolvimento de software e operação física, construindo ferramentas que substituem rotinas manuais, reduzem erros e dão às equipes visibilidade em tempo real sobre a produção.

Atualmente na Descartee, onde projeto e mantenho sistemas internos de controle operacional e automação de fluxos de trabalho. Anteriormente na Systra, em projetos de infraestrutura para o Trem Intercidades de São Paulo (TIC), produzindo desenhos técnicos e esquemas de controle para sistemas de catenária em AutoCAD.

---

## Competências

**Linguagens e Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-867DB1)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

**Dados e Aprendizado de Máquina**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-4B8BBE?logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)

**Ferramentas e Integrações**

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white)
![Zebra ZPL](https://img.shields.io/badge/Zebra%20ZPL-000000?logo=zebratechnologies&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD-0696D7?logo=autodesk&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

**Domínios**
- Controle de processos industriais
- Integração hardware-software
- Modelagem de banco de dados
- Ferramentas internas e dashboards

---

## Estatísticas do GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=caiogadotti&show_icons=true&hide_rank=true&hide_border=true&bg_color=0a0a0b&title_color=f4f4f5&text_color=8b8b96&icon_color=8b8b96" alt="Estatísticas do GitHub" />
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=caiogadotti&layout=compact&hide_border=true&bg_color=0a0a0b&title_color=f4f4f5&text_color=8b8b96" alt="Linguagens mais usadas" />
</p>

---

## Projetos em Destaque

**Sistema de Otimização de Corte Industrial** &nbsp;·&nbsp; `otimização de processos`
Ferramenta de otimização para operações de corte de bobinas de TNT. Calcula sequências de corte para minimizar desperdício, acompanha o desempenho dos operadores em tempo real e envia alertas automáticos via Telegram. Feito com Python e Streamlit.

**Impressão Automatizada de Etiquetas** &nbsp;·&nbsp; `integração de hardware`
Aplicação para geração e impressão automatizada de etiquetas com integração direta a impressoras térmicas Zebra. Elimina a criação manual de etiquetas e reduz erros no fluxo de etiquetagem.

**Portal de Admissão de RH** &nbsp;·&nbsp; `ferramenta interna`
Aplicação web para gestão de admissão de funcionários. Trata envio de documentos, validação de formulários e persistência de dados com controle de acesso por perfil. Feito com Streamlit e Supabase.

**Automação de Processos no AutoCAD** &nbsp;·&nbsp; `automação de cad`
Scripts e ferramentas para automatizar tarefas repetitivas de CAD: geração dinâmica de layout, preenchimento automático de carimbos e exportação de desenhos em lote. Desenvolvido para ambientes industriais e de infraestrutura.

> Rodam em sistemas internos da empresa, por isso seus repositórios são privados.

---

## Projetos em Destaque &nbsp;·&nbsp; Graduação

Trabalhos do meu Laboratório de Aprendizado de Máquina (LCML), publicados como open source.

**[Reconhecedor de Dígitos Manuscritos](https://github.com/caiogadotti/reconhecimento-digitos-knn)** &nbsp;·&nbsp; `aprendizado de máquina` &nbsp;·&nbsp; `público` &nbsp;·&nbsp; [app online](https://reconhecimento-digitos-knn.streamlit.app/)
Classificador de aprendizado de máquina que lê dígitos manuscritos a partir de imagens 8×8, com interface Streamlit para desenhar um número e ver a previsão, a confiança entre as classes e os exemplos de treino que produziram a resposta. Alcança **93,4%** em 2.000 dígitos escritos por outras pessoas e nunca vistos durante o treino.

A parte interessante foi o diagnóstico: treinar apenas com o dataset clássico `digits` dava 98% no próprio conjunto de teste, mas 62,5% em caligrafia de outra origem. Nenhuma troca de modelo ou busca de hiperparâmetro fechou essa lacuna. Quem fechou foi acrescentar diversidade de escrita aos dados de treino, valendo +29 pontos. Feito com scikit-learn, NumPy e SciPy.

**[Detector de Posição por Cor](https://github.com/caiogadotti/deteccao-cor-cv)** &nbsp;·&nbsp; `visão computacional` &nbsp;·&nbsp; `público` &nbsp;·&nbsp; [app online](https://deteccao-cor.streamlit.app/)
Pipeline de visão computacional que localiza um objeto colorido numa imagem e classifica sua posição (esquerda, centro, direita) usando OpenCV clássico, sem aprendizado de máquina. Converte para HSV, isola a cor-alvo, encontra o maior contorno e seu centroide, e compara com o meio da imagem usando uma margem de tolerância. Interface Streamlit com captura de câmera pelo navegador, calibração manual de HSV por sliders e uma imagem sintética de fallback para testar sem webcam.

**[Monitoramento Preditivo de Catenária](https://github.com/caiogadotti/monitoramento-catenaria)** &nbsp;·&nbsp; `sistemas distribuídos` &nbsp;·&nbsp; `go` &nbsp;·&nbsp; `python` &nbsp;·&nbsp; `público`
Pipeline completo de manutenção preditiva para catenária ferroviária: gateway de ingestão concorrente em Go recebendo telemetria de milhares de sensores simulados, motor de análise em Python que estima dano por fadiga estrutural, persistência em Supabase e dashboard Streamlit. Domínio baseado em 6 meses na Systra fazendo desenhos técnicos e esquemas de controle de sistemas de catenária no Trem Intercidades de São Paulo (TIC). O gateway foi medido sob carga real, não estimado: **2.000 sensores simultâneos, zero falhas de conexão**, com uma ferramenta de teste de carga escrita para o projeto.

O motor estima o desgaste de duas formas independentes, contagem de ciclos pelas regras de Basquin e Palmgren-Miner, e análise espectral por FFT do sinal de vibração, ambas chegando a **0,002 de erro absoluto médio** contra o dano real. A parte interessante foi um erro de modelagem que só apareceu no pipeline completo: o estimador espectral ajustava uma reta entre potência e dano, quando potência é o quadrado de uma amplitude. Funcionava na faixa estreita da calibração e errava por 60x fora dela. Trocar a forma linear pela quadrática correta derrubou o erro de 0,13 para 0,002. Feito com Go, NumPy, Supabase e Streamlit.

---

## Contato

- **LinkedIn:** [linkedin.com/in/caiogadotti](https://linkedin.com/in/caiogadotti)
- **E-mail:** disponível no LinkedIn
