# Analisi-econometrica-in-R-di-Indici-Nasdaq
Analisi tramite software R di rendimenti, rischio e proprietà econometriche di sette indici relativi al Nasdaq (Asia, EMEA, Eurozone, Global, Latin America, UK, US), comprendente:
- Calcolo di media, deviazione standard e varianza dei rendimenti, selezione di portafoglio mediante il criterio media-varianza e calcolo dell'Indice di Sharpe per singolo indice e per portafogli costituti da combinazioni di essi;
- stima di un modello di regressione lineare multipla dei rendimenti dell'indice Nasdaq Global sugli altri indici Nasdaq presi in esame, con test di significatività dei coefficienti (test t) e test F di Fisher;
- verifica della corretta specificazione del modello tramite test RESET e della presenza di eteroschedasticità tramite test di White;
- stima di sei regressioni CAPM per la classificazione degli indici (test t sul beta), confronto tra rendimenti osservati e rendimenti attesi con CAPM e verifica dell'ipotesi nulla: alpha = 0 tramite test F sulla significatività del coefficiente relativo all'intercetta;
- analisi di serie storiche: test di autocorrelazione di Ljung-Box, selezione tramite criterio AIC del miglior modello ARIMA, test di stazionarietà Augmented Dickey-Fuller e calcolo del Value at Risk. 
