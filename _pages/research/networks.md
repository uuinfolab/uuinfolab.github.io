---
layout: infolab-toplevel
title: Feature-rich networks
permalink: /research/networks
header:
  overlay_image: /assets/images/banner_small.jpg
  overlay_filter: "0.4"
toc: true
---
             
## Social network analysis

<figure style="width:40%">
<img src="/assets/images/ttn.png"
         alt="A temporal text network" />
    <figcaption>A communication network, with actors (A) exchanging messages (M), with timestamps (Vega and Magnani, 2020).</figcaption>
</figure>

Networks have been a popular model to study social systems for longer than one century, and their applicability has increased in the last decades thanks to increased accessibility to social data, for example from online social networks. However, contemporary social data can very heterogeneous, consisting of different types of actors and social ties, multimedia content, and temporal information. In addition, relevant social connections are often not directly available in the data, which implies that we cannot always be certain about which connections exist. Therefore, at the Infolab we study extended network models (also known as *feature-rich*) that can be used to represent the complexity of contemporary social data.

One model we have extensively studied since 2011[^ml-model] are **multilayer networks**. In addition to original research articles, we have also produced material to organise some of the vast knowledge in this area: a [book](http://www.cambridge.org/ge/academic/subjects/computer-science/computing-and-society/multilayer-social-networks?format=PB) on multilayer social networks, [software libraries](/software)[^library] for multilayer network analysis, and survey articles on preprocessing[^simplification], layer comparison[^comparison], community detection[^detection], and diffusion processes[^diffusion]. We have also introduced multilayer network models including textual and temporal information, called **temporal text networks**, and studied measures and algorithms for **probabilistic networks** where edge existence is uncertain.

[^ml-model]: Matteo Magnani and Luca Rossi (2011). <a href="papers/11asonam.pdf" target="_blank">The ML-Model for Multi-Layer Social Networks</a>. International conference on social network analysis and mining (ASONAM). IEEE.

[^library]: Matteo Magnani, Luca Rossi and Davide Vega. <a href="papers/jss.pdf" target="_blank">Multiplex network analysis with R</a>. Journal of Statistical Software.

[^simplification]: Roberto Interdonato, Matteo Magnani, Diego Perna, Andrea Tagarelli and Davide Vega. <a href="http://arxiv.org/abs/2004.14808" target="_blank">Multilayer network simplification: approaches, models and methods</a>. Computer Science Review, Elsevier.

[^comparison]: Piotr Brodka, Anna Chmiel, Matteo Magnani and Giancarlo Ragozini (2018). <a href="papers/18rsos.pdf" target="_blank">Quantifying layer similarity in multiplex networks: a systematic study</a>. Royal Society Open Science, 5(8).

[^detection]: Obaida Hanteer, Roberto Interdonato, Matteo Magnani, Luca Rossi and Andrea Tagarelli. <a href="https://arxiv.org/abs/1910.07646" target="_blank">Community Detection in Multiplex Networks</a>, and C&eacute;cile Bothorel, Juan David Cruz, Matteo Magnani, and Barbora Micenkova (2015). <a href="papers/15NetworkScience.pdf" target="_blank">Clustering Attributed Graphs: Models, Measures and Methods</a>. Network Science 3 (3). Cambridge University Press: 408–44.

[^diffusion]: Mostafa Salehi, Rajesh Sharma, Moreno Marzolla, Matteo Magnani, Payam Siyari, and Danilo Montesi (2015). <a href="papers/15TNSE.pdf" target="_blank">Spreading Processes in Multilayer Networks</a>. IEEE Transactions on Network Science and Engineering 2 (2): 65–83.

