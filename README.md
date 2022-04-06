<!DOCTYPE html>

<html>
  <head>
    <title>GMX</title>
    <style>
      body {
        background-color: #ffffff;
      }

    </style>
  </head>

  <body>
    <div id="body-overlay">
      <div id="headline">
        <style type="text/css">
            /*#headline {
                background-color: #1c449b;
                position: absolute;
                width: 100%;
                height: 102px;
                left: 0px;
                top: 0px;
            }*/

            .button {
                background-color: #1c449b;
                border: none;
                color: white;
                padding: 15px 32px;
                text-align: center;
                text-decoration: none;
                display: inline-block;
                font-size: 16px;
                margin: 4px 2px;
                cursor: pointer;
                }

            .modal-window {
                position: fixed;
                background-color: rgba(200, 200, 200, 0.75);
                top: 0;
                right: 0;
                bottom: 0;
                left: 0;
                z-index: 999;
                opacity: 0;
                pointer-events: none;
                -webkit-transition: all 0.3s;
                -moz-transition: all 0.3s;
                transition: all 0.3s;
                }

            .modal-window:target {
                opacity: 1;
                pointer-events: auto;
                }

            .modal-window>div {
                width: 400px;
                position: relative;
                margin: 10% auto;
                padding: 2rem;
                background: #fff;
                color: #444;
                }

            .modal-window header {
                font-weight: bold;
                }

            .modal-window h1 {
                font-size: 200%;
                margin: 0 0 15px;
                }
        </style>
        <!-- <img src="GMX_headline.png" class="Bild"  heigth="150" width="960> -->
      </div>
      <font size=5>
         <div {position: fixed; top: 450px; left: 100px; bottom: 10px; right: 10px}>
            <a href="#open-modal" class="button">Hier klicken, um sich anzumelden!</a>
         </div>
        </font>
        <div id="open-modal" class="modal-window">
          <div>
            <h1>Log In</h1>
            <form action="">
                <input type="email" placeholder="Email-Adresse" class="eingabefeld">
                <input type="password" placeholder="Passwort" class="eingabefeld">
                <input type="submit" value="Log In!">
            </form>     
          </div>
        </div>
  </body>
</html>
