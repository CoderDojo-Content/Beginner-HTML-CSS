1. Clicca sull'icona con l'immagine accanto al simbolo **+**. Da qui è possibile vedere le immagini che possono essere utilizzate per il nostro sito ed eventualmente aggiungerne altre. Per il momento utilizziamo l'immagine presente all'interno del progetto. 
2. Selezionamo il file index.html nel pannello del codice, e inseriamo il seguente testo dopo il tag `</ul>`: 
   ```html
      <img src="tito.png" alt="Il cane Tito" width="100px" />
      <p>Questo è Tito e sarà la nostra guida. Come puoi vedere, Tito ama Coderdojo!</p>
   ```
   ![](assets/ImgTito2.png)
 Nota cdhe il tag `<img>` è diverso dagli altri visti finora: 
   * Non c'è un tag di chiusura `</img>`. Invece il tag è di tipo **"autochiudente"**: il tag di apertura ha i caratteri `/>` alla fine. Questo avviene perché non c'è un "inizio" e una "fine" come nel caso in cui si stia inserendo del testo in una pagina. 
   * Il tag contiene al suo interno delle informazioni addizionali nella forma di  **attributi**. L'attributo `src` dice al browser quale file utilizzare per l'immagine. L'attributo `alt` è una breve descrizione dell'immagine che il browser utilizzerà nel caso non riesca a visualizzare l'immagine. 
3. Infine l'attributo `width` ("ampiezza" in inglese) indica la dimensione orizzontale del riquadro dove il browser inserirà l'immagine (in numero di pixel (**px** è l'abbreviazione della parola **pixel**, i piccoli puntini che formano lo schermo dei PC). Prova a cambiare questo numero e osserva cosa succede! Non cancellare le lettere `px`. 
4. Per aggiungere tue immagini al sito web , clicca di nuovo sull'icona dell'immagine e quindi clicca sul pulsante "Add Image". Clicca su "Upload" (in italiano "Caricare") e seleziona "Click To Select Files". Dalla finestra che ti apparirà, seleziona dal tuo computer il file (o i file) da caricare e clicca su "Apri". Una volta terminato clicca su "Done" e quindi su "Save" per salvare il lavoro fatto.

  **Nota:** Controlla i nomi dei tuoi file prima di caricarli e, se necessario, **rinominali**. E' una buna idea usare nomi di file senza spazi, e che siano facili da ricordare e scrivere. Alcune volte quando si scaricano immagini da internet, queste hanno dei nomi molto strani, come per esempio "177823k-iewnf8832n2-3dkewnfwe512.png", impossibili da ricordare e diffici da scrivere!
 ![](assets/UploadFilesWider.png)
5. Una volta che hai caricato i tuoi file, puoi visualizzarli sulla tua pagina usango il tag `<img>` come visto prima. Ovviamente il valore dell'attributo `src` va cambiato in modo che corrisponda al nome del nuovo file. Inoltre va cambiato anche il valore dell'attributo `alt` in modo che contenga la descrizione della nuova immagine. _Importante:_ i valori degli attibuti come il nome del file e il testo alternativo devono essere all'interno delle **virgolette**!



