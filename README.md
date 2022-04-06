2palleeeee.html
Chi ha accesso
Non condiviso
Proprietà di sistema
Tipo
HTML
Dimensioni
626 byte
Spazio di archiviazione utilizzato
626 byte
Posizione
HTML
Proprietario
io
Data modifica
31 mar 2022 da me
Aperto
5 apr 2022 da me
Data creazione
31 mar 2022 con Google Drive Web
Aggiungi una descrizione
I visualizzatori possono scaricare
<html>

<div class="box"></div>
<style>
{
  height: 100%;
}
body {
  padding: 32px 0;
  height: 100%;
  /* Center box */
  display: grid;
  place-content: center;
}
.box {
  width: 75px;
  height: 75px;
  background: slateblue;
  padding: 8px;
  display: grid;
  place-content: center;
  color: white;
  text-align: center;
  border-radius: 50%;
}
  @keyframes bounce {
    from {
      transform: translateY(0px);
    }
    to {
      transform: translateY(-20px);
    }
  }

  .box {
    animation:
      bounce 300ms
      alternate infinite
      cubic-bezier(.2, .65, .6, 1);
  }
</style>

<div class="box"></div>
</html>
