# Theoretical Background

Questa sezione presenta i concetti fondamentali della statistica e del testing di ipotesi.

## Basi di Statistica

- **Media, Moda, Mediana**;
  
$$ \bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i $$

$$ x_i :\forall k \in X( count(k) \leq count(x_i)) $$

$$ x_{\left(\frac{n+1}{2}\right)} $$ 

- **Varianza e Deviazione Standard:** Misure della dispersione dei dati;

$$ \sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2 $$

$$ s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2 $$


## Applicazioni nella Vita Reale

La statistica aiuta a:
- Analizzare dati economici e sociali.
- Prendere decisioni in campo medico e sportivo.

## Progetti di Data Analysis

Fasi principali di un progetto:
- **Data Cleaning:** Pulizia e correzione dei dati.
- **Visualizzazioni:** Creare grafici (ad esempio, istogrammi, scatter plot) per interpretare i dati.
- **Interpretazioni e Predizioni:** Usare i dati per fare previsioni e decisioni informate.

## Ipotesi Statistica e Testing

Quando si analizzano i dati, si formulano ipotesi da testare:
- **Ipotesi Nulla (H₀) vs. Ipotesi Alternativa (H₁)** ovvero ipotesi che non ci sia tra due variabili nessun legame (correlazione), oppure che abbiano qualche tipo di relazione.

Analisi Statistiche:

- **T-test**: Misura la differenza tra le medie dei due gruppi (ing_label 0 e ing_label 1) in termini di errore standard. Un valore assoluto più elevato del t-statistic indica una differenza maggiore tra le medie.
- **Correlazione di Pearson**: Misura la relazione lineare tra due variabili. Il valore varia da -1 a +1: -1: Correlazione lineare negativa perfetta 0: Nessuna correlazione lineare +1: Correlazione lineare positiva perfetta
- **Correlazione di Spearman**: Misura la relazione monotona tra due variabili (cioè, se tendono a incrementare o decrementare insieme, indipendentemente dalla linearità). Anche questa variabile varia da -1 a +1 e le interpretazioni sono simili a quelle della correlazione di Pearson.
- **P-value**: Indica la probabilità di ottenere i risultati osservati (o risultati ancora più estremi) se non esiste una reale differenza tra i gruppi. Un p-value inferiore a 0,05 è generalmente considerato statisticamente significativo, suggerendo che esiste una differenza significativa tra i gruppi.

## Nota Bene

### Forza della Correlazione
- **Descrizione:** Sebbene le variabili possano mostrare relazioni statisticamente significative, ciò non implica che la correlazione sia "forte" (cioè vicina a -1 o +1).
- **e.g.** Immagina il legame tra altezza e peso corporeo. C'e sicuramente una correlazione positiva, tuttavia non è necessariamente una correlazione forte (i.e. una persona alta 1.90 non è necessariamente grassa, e viceversa).

### Direzione della Correlazione
- **Descrizione:** La direzione della correlazione indica se, all'aumentare di una variabile, l'altra tende ad aumentare (correlazione positiva) o a diminuire (correlazione negativa).
- **e.g.** Osserva la correlazione tra il numero di ore di sonno e il consumo di caffè. Le variabili sono correlate. In che modo? In maniera negativa, ovvero "più dormi, meno caffè bevi" – magari perché dopo un buon riposo non hai più bisogno di stimolarti con il caffè, ma anche "più caffé bevi, meno dormi".


### Causalità vs. Correlazione, *cum hoc ergo propter hoc*
- **Descrizione:** Anche se una correlazione è statisticamente significativa, non significa necessariamente che abbia un impatto rilevante nella pratica. Ricorda: correlazione non significa causalità. Solo perché due variabili si muovono insieme, non vuol dire che una causi l'altra.
- **e.g.** Durante i mesi estivi, le vendite di gelato tendono ad aumentare e, allo stesso tempo, si osserva un incremento delle scottature. Il gelato provoca scottature?

[Home](index.md)
