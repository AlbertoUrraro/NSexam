## Disclaimer

- Il tutto è puramente a scopo didattico , si prega di non utilizzarlo per scopi malevoli
- La macchina target deve avere un sistema operativo windows, senza lo stesso l'attacco non andrà a buon fine
- Grazie e buon divertimento

# Phishing attack using the follina exploit and keylogger injection

Questo progetto ha lo scopo di mostrate come dei mal intenzionati presenti in rete possono sferrare attacchi sfruttando vulnerabilità presenti nei sistemi odierni per prelevare dati sensibili violando la privacy dei soggetti colpiti.

## Tech Stack

**Code:** Visual studio Code

**VirtualBox:** Windows 10 machine (target),Kali linux machine(Attacker)

**SEToolkit:** Tool Social-Engineering

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
Script follina guide

```bash
  https://github.com/JohnHammond/msdt-follina
```
Info email mian.cpp

```bash
  Per far si che il codice funzioni è necessario inserire una propria email nei campi 
  
  -string Email_To_Recieve_On = "";
  -string Email_To_Send_From = "";
  
  cosi da avere mittente e destinatario sulla stessa casella postale
  
  Inoltre per poter abilitare l invio dell email da un account google è fondamentale abilitare i permessi 
  ad app non protette , fatto ciò sara possibile creare una password per un app dedicata che andrà inserita nel campo 
  
  -string Password_Of_Sender_Email = "";
```

Per maggiori dettagli del codice

```bash
   https://github.com/AlbertoUrraro/NSexam/tree/main/code
```

Presentazione

```bash
   https://github.com/AlbertoUrraro/NSexam/tree/main/presentazione
```

# Descrizione Codice

### Main

![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/main.png)

### System info

![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/systeminfo.png)

### Send Email

![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/Emial.png)

### Keylogger

![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/key1.png)
![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/key2.png)
![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/key3.png)
![](https://github.com/AlbertoUrraro/NSExam/blob/main/Immagini%20/key4.png)

## Sviluppi Futuri

    -  Persistenza del keylogger al riavvio
      - Idea: registri windows usando HKEY_CURRENT_USER
    - Utilizzo di un server specializzato per la distribuzione di email di fishing 
     

## Made By

- [@Alberto-Urraro]

