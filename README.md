<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="Glevia - timer bossow & metinow">
    <title>Glevia - timer bossow & metinow</title>
    <link rel='shortcut icon'
          href='static/favicon.ico'>

    
 

</head>


<body>
<div class="alert">
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span> 
  Zezwól na powiadomienia żeby strona poprawnie działała. Jeżeli strona nie wyświetla się poprawnie , wyczyść cookies i pamięć podręczną, przeładuj strone.

</div>
<nav class="navbar navbar-expand-md navbar-dark bg-dark">
    <a class="navbar-brand" href="#">Vidgar - timer bossow & metinow</a>
</nav>
<img src="static/logo.png" class="center" alt="Glevia"/>

<main role="main" class="container">
    <div class="col-xl timery">
		<h6 style="color:white">Głośność dźwięku:</h6>
		<input type="range" min="0" max="1" value="0.5" step="0.1" id="slider">
		<h6 style="color:white">Powiadomienie przed (sekundy):</h6>
		<input type="number" min="1" value="120" id="czas">
		<br>
		<br>
		<label for="sel1"><h4 style="color:white">Wybierz bossa/metina:</h4> </label>
		<h4>
        <div class="row">
            <div class="col-xl-10 col-lg-9 col-md-9 col-sm-12 col-xs-12">
                <select class="form-control" id="bossControl">
					<option>Test dźwięku i powiadomienia</option>
					<option disabled>+++ BOSSY +++</option>
				
				
				 <option>Królowa Pustyni *Pustynia*</option>
					<option>Skalista Małpa *Kraina Małp*</option>
					<option>Chodząca Małpa *Kraina Małp*</option>
					<option>Lord Małp *Kraina Małp*</option>
					<option>Dziewięć Ogonów *Góra Sohan*</option>
					<option>Ognisty Król *Piekło*</option>
					<option>Reinkar, Zjawa *Świątynia Hwang*</option>
					<option>Olbrzymi Duch Drzewa *Red Las* </option>
                  
                    <option disabled>+++ METINY +++</option>
					
					<option>Metin Tu-Young *Red las*</option>
					<option>Metin Jeon-Un *Red las*</option>
					
                </select>
            </div>
            <div class="col-xl-2 col-lg-3 col-md-3 col-sm-12 col-xs-12">
                <button class="btn btn-danger float-right btnresetall" >Zresetuj wszystko</button>
            </div>
        </div>
		<!--<div>
		
		</div> -->
        <div class="card-group">
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH1</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH2</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH3</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH4</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
        </div>
        <div class="card-group">
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH5</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH6</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH7</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
            <div class="card">
                <div class="card-body boss">
                    <h4 class="card-title"><span class="bossName"></span> - CH8</h4>
                    <span class="timer">--:--</span> <br/><br/>
                    <button class="btn btn-primary btnon">Przełącz</button>
                    <button class="btn btn-warning btnreset">Zresetuj</button>
                </div>
            </div>
			</h4>
        </div>
    </div>
</main>
<script src="static/zegarek.js"></script>
</body>
</html>
