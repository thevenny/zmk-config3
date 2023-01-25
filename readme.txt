Editor grafico e RGB ON!

Compilare il tutto con Git Bash come da istruzioni di ZMK
Una volta importato tutto sulla propria cartella Github si può personalizzare il layout su https://nickcoutsos.github.io/keymap-editor/
Salvare le modifiche in basso a DX e premere il tasto azzurro.
Github comincerà la compilazione, cliccare sul file compilato e scaricare il file firmware.zip che contiene il file .uf2 da flashare.

RETROILLUMINAZIONE LED
Dato che nice!nano è fatto per funzionare in bluetooth a batteria, la retroilluminazione è spenta di default. I led accesi accorcerebbero la vita della batteria da 4 mesi a circa mezz'ora di utilizzo.

Per farla funzionare bisogna incollare il contenuto del file nice_nano.overlay all'interno del file .keymap, ideale dalla riga 12 in poi.
Poi andate nel file reviung41.conf e togliete i due cancelletti alla seconda e terza voce come nel mio file.

Per attivare la retroilluminazione dovete ovviamente settarvi qualche tasto per farlo nel vostro layout, sempre grazie all'editor del link.
Per vedere le opzioni LED dovete cambiare il prefisso al tasto in &rgb_ug 
