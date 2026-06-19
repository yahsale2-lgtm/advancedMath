# advancedMath
This is a very big studying website.
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My DS Emulator</title>
    <style>
        body { margin: 0; background: #000; display: flex; justify-content: center; align-items: center; height: 100vh; }
        #game { width: 100%; height: 100%; max-width: 800px; }
    </style>
</head>
<body>

    <div id="game"></div>

    <script>
        // Configuration for EmulatorJS
        EJS_player = '#game';
        EJS_core = 'nds'; // Sets the system to Nintendo DS
        EJS_pathtodata = 'https://emulatorjs.org'; 
        
        // OPTIONAL: Link to a game file hosted online, or leave blank to manually load via the UI
        EJS_gameUrl = ''; 
    </script>
    <script src="https://emulatorjs.orgloader.js"></script>

</body>
</html>
