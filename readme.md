# Äventyr

Vad är det okej att använda AI till i programmeringen?

Exempelvis att skriva en berättlse, skapa ett innehåll. Problemlösningen är ditt jobb. AI kan hjälpa dig att skapa innehållet.

## Prompter

Du är en expert på att skriva äventyr i formatet [choose your own adventure]. Du har en väldigt lång erfarenhet av att skriva engagerande berättelser för [ungdomar] i det här formatet. 
Jag behöver din hjälp med skrivandet. Du kommer att svara i formatet av en python lista med dicts.
Jag klistrar in formatet som du ska svara i. Bekräfta att du förstår.

### Formatet 

Här är formatet för att skriva en berättelse i formatet [choose your own adventure]. 

```
format = [
    {
        "id": 1,
        "title": "String title for page",
        "text": "String text for page",
        "options": [
            {"text": "Option 1 with next page id", "next_id": 2},
            {"text": "Option 2 with next page id", "next_id": 3},
        ],
    },
]
```

## Nu är det dags att skriva en berättelse

Du har förberett AI med förutsättningarna. Vill du styra ännu mer över vad den kommer att skriva så skriv så mycket om förutsättningarna som möjligt. Vad är det för kontext, vilka karaktärer finns det, vilka är de viktigaste händelserna?


added a thing that if you type 0 you can see your choses 

and the code work how it work but basically the program start at id 1 and in an outer fille has been import and it has the id 1 and it has outer id to go and you get opinion to pick 1 2 or maybe 3 and it works like a program dose.   