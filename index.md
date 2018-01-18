
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>🐛💭🍽- Il Bruco Maisazio</title>
    <style>
        body {
            text-align: center;
        }
        
        p {
            font-size: 20px; font-family: sans-serif;
        }
        
        h1 {
            font-size: 80px; font-family: sans-serif;
        }
        
        h2 {
            font-size: 50px;
        }
        

    </style>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script>
        $(document).ready(function () {

            $("#uovo").click(function () {
                $(".uovo").show(); /* mostra testo */
                $("#uovo").hide(); /* nascondi pulsante */
            });

            $("#bruco").click(function () {
                $(".bruco").show();
                $("#bruco").hide();
            });
            
              $("#ricerca").click(function () {
                $(".ricerca").show();
                $("#ricerca").hide();
            });

            $("#mela").click(function () {
                $(".mela").show();
                $("#mela").hide();
            });

            $("#pere").click(function () {
                $(".pere").show();
                $("#pere").hide();
            });

            $("#prugne").click(function () {
                $(".prugne").show();
                $("#prugne").hide();
            });

            $("#fragole").click(function () {
                $(".fragole").show();
                $("#fragole").hide();
            });

            $("#arance").click(function () {
                $(".arance").show();
                $("#arance").hide();
            });

            $("#tutto").click(function () {
                $(".tutto").show();
                $("#tutto").hide();
            });
            
             $("#pancia").click(function () {
                $(".pancia").show();
                $("#pancia").hide();
            });
            
             $("#foglia").click(function () {
                $(".foglia").show();
                $("#foglia").hide();
            });
            
             $("#forte").click(function () {
                $(".forte").show();
                $("#forte").hide();
            });
            
             $("#farfalla").click(function () {
                $(".farfalla").show();
                $("#farfalla").hide();
            });

        });
    </script>
</head>

<body>
    
    <h1>Il Bruco Maisazio</h1>
    
    <h2>🌌🌛🌱🥚</h2>
    <p class="uovo" hidden>Di notte, su una foglia illuminata dalla luna, c’era un piccolo uovo.</p>
    <button id="uovo">Show</button>

    <h2>🌄☀️🐛💭🍽</h2>
    <p class="bruco" hidden>Ma una bella domenica mattina, quando si levò il sole, caldo e splendente dall’uovo -crac!- uscì un piccolo bruco affamato.</p>
    <button id="bruco">Show</button>
    
    <h2>🐛🚶🔍🍽</h2>
    <p class="ricerca" hidden>…Subito si mise in cammino alla ricerca di cibo.</p>
    <button id="ricerca">Show</button>

    <h2>🍎🐛💭😕</h2>
    <p class="mela" hidden>Lunedì mangiò una mela, ma non riuscì a saziarsi.</p>
    <button id="mela">Show</button>

    <h2>🍐🍐🐛💭😕</h2>
    <p class="pere" hidden>Martedì mangiò due pere, ma non riuscì a saziarsi.</p>
    <button id="pere">Show</button>

    <h2>💜💜💜🐛💭😕</h2>
    <p class="prugne" hidden>Mercoledì mangiò tre prugne, ma non riuscì a saziarsi.</p>
    <button id="prugne">Show</button>

    <h2>🍓🍓🍓🍓🐛💭😕</h2>
    <p class="fragole" hidden>Giovedì mangiò quattro fragole, ma non riuscì a saziarsi.</p>
    <button id="fragole">Show</button>

    <h2>🍊🍊🍊🍊🍊🐛💭😕</h2>
    <p class="arance" hidden>Venerdì mangiò cinque arance, ma non riuscì a saziarsi.</p>
    <button id="arance">Show</button>

    <h2>🍰🍦🥒🧀🥓🍭🍪🌭🍩🍉🐛💭😍</h2>
    <p class="tutto" hidden>Sabato mangiò un dolce al cioccolato, un gelato, un cetriolo, un pezzo di formaggio, una fetta di salame, un lecca-lecca, una fetta di pandolce, una salsiccia, una pastina e una fetta di anguria.</p>
    <button id="tutto">Show</button>
    
    <h2>🌙🐛🗯🤢‼️</h2>
    <p class="pancia" hidden>Alla sera aveva il mal di pancia!</p>
    <button id="pancia">Show</button>
    
    <h2>🌱🐛💭😊</h2>
    <p class="foglia" hidden>Il giorno dopo era di nuovo domenica e il bruco si mise a mangiare una bella foglia verde. Si sentì subito meglio.</p>
    <button id="foglia">Show</button>
    
    <h2>🐛💪</h2>
    <p class="forte" hidden>Adesso non era più affamato, era proprio sazio.
    E non era più tanto piccolo, ma era diventato grande e grosso.</p>
    <button id="forte">Show</button>
    
    <h2>🏗🏠🐛➡️🦋</h2>
    <p class="farfalla" hidden>Allora si costruì una casa molto stretta, chiamata bozzolo, e rimase là dentro per più di due settimane. Poi scavò un buco nel bozzolo, si sforzò di uscire e… Era diventato una meravigliosa farfalla!</p>
    <button id="farfalla">Show</button>

</body>

</html>
