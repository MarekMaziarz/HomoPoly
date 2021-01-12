# Homonymy-polysemy-in-dictionaries
The data set comprises distances between nominal senses in polysemy networks made for 57 nouns picked up from WordNet and two English dictionaries, namely Oxford Lexico (LEX), www.lexico.com, and Merriam-Webster (MW), www.merriam-webster.com.

Polysemy networks were made manually on the basis of each dictionary entry. Then meanings of Princeton WordNet nouns were mapped onto dictionary senses. The mapping was done independently by two lexicographers with Cohen's kappa greater than 0.80. For all possible pairs of senses we calculated Dijkstra's distances (distMW, distLEX).

The last measure distOpti comprises the minimum value of two standardised distance measures (distMW', distLEX'). Here distMW' stands for (distMW-mean(distMW))/st.dev(distMW), similarly distLEX' = (distLEX-mean(distLEX))/st.dev(distLEX). Please note that in the case of senses belonging to disjoint parts of a polysemy networks, instead of infinity maximal values were chosen (max+1).


