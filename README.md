# Analisi Statistica dell’Espressione Genica Differenziale tra Pazienti Affetti da Autismo Macroencefalico e i loro Familiari non Affetti

Progetto per trovare i geni differenzialmente espressi in pazienti che soffrono di autismo macroencefalico, usando come controlli i loro pazienti non affetti. Lo studio di riferimento è "*Mariani J, Coppola G, Zhang P, Abyzov A et al. FOXG1-Dependent Dys-regulation of GABA/Glutamate Neuron Differentiation in Autism Spectrum Disorders*" (https://escholarship.org/uc/item/5f29t1rd).

La repository comprende 3 file:
- final_SE è relativo al dataset "finale", ovvero dopo tutte le fasi di preprocessing (eliminazione dei geni non espressi, corretto per il batch effect giornaliero normalizzazione TMM)
- Progetto_ASD.Rmd è un file R markdown in cui sono state operate le fasi di preprocessing, normalizzazione, inferenza (tramite inferenza bayesiana empirica) e interpretazione dei risultati.
- Progetto_ASD.pdf contiene l'output di Progetto_ASD.Rmd
