## Disclaimer

- Il tutto è puramente a scopo didattico , si prega di non utilizzarlo per scopi malevoli, in tal caso io sono esente da qualsiasi responsabilità
- La macchina utilizzata per la simulazione dell'attacco presenta una architettura ARM64
- Grazie e buon divertimento

# Phishing attack using follina exploit and keylogger injection

Questo progetto ha lo scopo di mostrate come dei mal intenzionati presenti in rete possono sferrare attacchi sfruttando vulnerabilità presenti nei sistemi odierni per prelevare dati sensibili violando la privacy dei soggetti colpiti.

## Tech Stack

**Code:** Virtual studio Code

**VMware:** Kali linux machine

**UTM:** Windows 11 machine

## Run Locally

Clone del progetto

```bash
  git clone https://github.com/AlbertoUrraro/NSexam.git
```

Directory del progetto

```bash
  cd NSexam-main
```

Compile code on cmd

```bash
  g++ main.cpp -o <nomedeciso>.exe
```

Info email

```bash
  Per poter inoltrare l email è necessario abilitare i permessi ad app non protette nel proprio account google
```

Per maggiori dettagli

```bash
   https://github.com/AlbertoUrraro/SSExam/
```

# Descrizione Codice

### Main

![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/main.png)

### System info

![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/systeminfo.png)

### Send Email

![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/Emial.png)

### Keylogger

![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/key1.png)
![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/key2.png)
![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/key3.png)
![](https://github.com/AlbertoUrraro/SSExam/blob/main/Immagini%20/key4.png)

## Sviluppi Futuri

    -  Persistenza del keylogger al riavvio
      - Idea: registri windows usando HKEY_CURRENT_USER

## Made By

- [@Alberto-Urraro]
