# Big data for real

Vanlog

http://www.vanlog.it/

claudio ferrara
andrea melloncelli

## Chi è e cosa fa Vanlog

Azienda che fa datascience -> azienda che fa business a partire dai dati.

* Data checkup: capire di cosa abbiamo bisogno (i dati e le infrastrutture)
* Data discovery e trasformazione dei dati: trasformare i nostri dati in
informazioni e risposte. Per fare questo è necessario avere alcuni
indicatori tipo: KPI e data insights, monitoring, profiling (segmentation,
clustering), recommendations (raccomandazioni tipo amazon o youtube),
forecasting (prevedere il futuro)
* Output: trasformare le informazioni a partire dalla materia prima dato:
Automatic reports, interactive web app, multiplatform integration via API, IT
infrastructure.

## Data science courses

Insieme a quantide (azienda cooperativa di vanlog) vengono fatti corsi su R

## Data science workflow

Si prendono dei dati, si importano nel software riordinandoli, e vengono
messi nel ciclo di modellazione trasformazione e visualizzazione dei dati (che
è il ciclo di comprensione), per poi generare un tipo di comunicazione
comprensibile a chi non conosce.

## Strumenti

Si possono usare dei software per la visualizzazione grafica come open for
innovation **knime**.
Oppure usando un linguaggio di programmazione come: scala, python, R.

La differenza è la facilità di utilizzo per quanto riguarda i software grafici,
ma i linguaggi di programmazione hanno una capacità di comunicazione più
potente e flessibili.

Inoltre molto spesso i software grafici sono a pagamento.

Scala sta diventando un linguaggio molto usato per fare data engineering.

## R

Dove imparare questo linguaggio:

* [Datacamp r](https://www.datacamp.com/search?q=r)
* [Libro](http://shop.oreilly.com/product/0636920028352.do)
* [Coursera r](https://www.coursera.org/learn/r-programming)

è un linguaggio di programmazione interpretato.
è tipicamente dinamico.

**Dichiarare variabile**

```R
media <- mean(c(1,2,30))
media
```

```Output
[1] 11
```

**Dichiarare funzioni**
```R
mean_two <- function(x,y) {(x+y)/2}
mean_two(3,5)
```

```Output
[1] 4
```

**Importare librerie**

```R
library(dplyr)
library(tidyr)
library(tidyverse)
```

Questa è la base, se necessarie altre informazioni guarda i link [qui](#r)

## R studio

[Here to download](https://www.rstudio.com/products/rstudio/download/)

Shortcut:

* ctrl+enter esecuzione comando in r console
* F1 estrae informazioni su variabili, librerie e dataset selezionati
* F2 visualizzazione del dataset sotto forma di csv direttamente nella console


## Domande
