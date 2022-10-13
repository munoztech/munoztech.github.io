<html>
    <head>
        <style>
            @import 'https://fonts.googleapis.com/css?family=Holtwood+One+SC';
            * {
                transition-duration: 0.125s
            }
            html {
                /* #ccc lessens visual artifact from border-image */
                background-color: #ccc;
            }
            ul {
                text-align:left;
            }
            #playerCode {
                font-family: 'Holtwood One SC';
                text-align: center;
                width: 700px;
                border: solid;
                border-width: 124px 76px 64px 40px;
                padding: 16px 32px;
                background-color: #ccc;
                border-image: url(/images/level/code_editor_background_border.png) 124 76 64 40 fill round;
                margin: 0 auto;
                margin-bottom: 50px;
            }
            #playerCode > div > div > div {
                display:inline-block;
            }
            #playerCode > div > img {
                width: 240px;
            }
            #playerCode div div > div {
                margin:8px;
                padding:8px;
                background-color:rgba(0, 0, 0, 0.125);
                border-radius:32px;
            }
        </style>
    </head>    
    <body id="playerCode">
        <div>
            <playercode>
                <style>
                    h1 {
                        color: red;
                    }
                    h1 {
                        font-size: 7em;
                    }
                    h2 {
                        /* Change the number to change the size of the header text. */
                        font-size: 3em;
                    }
                    h3 {
                        font-size: 1.5em;
                    }
                    li {
                        font-size:1.5em;
                    }
                </style>
                <h1>Wanted</h1>
                
                <!-- Find an image from the Image Gallery above, or use your own image link. -->
                <img src="https://www.codecombat.com/file/db/thang.type/54eb540b49fa2d5c905ddf1a/portrait.png" id="most-wanted">
                
                <!-- Who is wanted? -->
                <h2>Bomb Bill</h2>
                
                <!-- What are they wanted for? -->
                <h3>For Reckless, Inhuman Crimes:</h3>
                <ul>
                    <li>Exploding</li>
                    <li>Rolling</li>
                    <li>Priming</li>
                    <li>Smoldering</li>
                </ul>
                
                <!-- What is the reward? -->
                <h2>Reward: Some Gold</h2>
                
                <!-- Who are their partners in crime? -->
                <h3>Known Accomplices</h3>
                <div>
                    <div>
                        <img src="https://www.codecombat.com/file/db/thang.type/5432f9d18364d30000d1f943/portrait.png">
                        <h3>Chest o' Gems</h3>
                    </div>
                    
                    <div>
                        <img src="https://www.codecombat.com/file/db/thang.type/53024c7b27471514685d5397/portrait.png">
                        <h3>The Hand</h3>
                    </div>
                    
                    <!-- Add a third accomplice here. Choose whether they are class "captured". -->
                    <div>
                        <img src="http://direct.codecombat.com/file/db/thang.type/52e95a5022efc8e709001743/portrait.png">
                        <h3>cow</h3>
                    </div>
                </div>
                
                <!-- How do want them captured? -->
                <h2>Capture Alive Only</h2>
            </playercode>
        </div>
    </body>
</html>
