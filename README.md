# a-path
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Protected Page</title>
</head>
<body>

<!-- Password form -->
<div id="password-form">
    <form id="password-form" onsubmit="checkPassword(event)">
        <label for="password">Enter Password: </label>
        <input type="password" id="password" name="password" required>
        <button type="submit">Submit</button>
    </form>
</div>

<!-- Content (hidden by default) -->
<div id="content" style="display: none;">
    <p>Another case of a massacre of severe intensity at a public place has been reported, totaling the reported instances of unnatural surges of violence to twenty-two for just this week. Our reporters are present at A-9 at the crystal avenue on Lavender Isle, surrounding the third block of the scene of unrest, the Arrows Through Moon Theatre.</p>
    <p>The man responsible for the unrest is reportedly arrested and calm as of now. According to our reporters, the man claimed that he was under the control of a malevolent being. Bystanders are convinced it is the rumored Cepheus and it is a source of panic for all of the archipelago. The man further claimed that he was helped by a tranquil voice in regaining control of himself. His claims have not helped him in avoiding an arrest as per the reports, a decision strongly appreciated by relatives of the twenty injured and fifteen murdered by the hands of the eighteen-year-old human. Further research has been assured by the authorities but the expanding panic is a major concern for all of Pleonexia.</p>
    <p>We bring you exclusive insights into the convicted man’s claims, especially what was said to him by “a tranquil voice” —</p>
    <blockquote>
        <p>"Wake up. You are not in control. Wake and take hold of yourself. Look around you, what you've done. Smell the iron in the air, the blood on your hands. The screams you have wrested from innocents. I am here, I will help. But first you must WAKE!"</p>
        <footer>— A tranquil voice.</footer>
    </blockquote>
    <p>A̵ ̸t̴r̸a̸n̶q̷u̴i̸l̷ ̴v̶o̵i̷c̸e̷.̵</p>
    <p>Ä̴̺́ ̸̧̈́t̴͎̚r̴̯͐â̵͇n̷͔̿q̵͈̈́ų̷͊ḯ̸ͅl̵̢͠ ̵̼̎v̷̕ͅo̸͇͠ȉ̶͚c̵̜͊ê̷̺.̷̢̇.</p>
    <p>A̸͈͇͎̱̗͆̈́̏͝͝ͅ ̵̡̡̮̞̗̪̬̖͂̒͋̈̈́̅́̐͘ẗ̸̩̠̰̹͓̙̳̟̳́̽r̶̬̩͉̥̩̿́͛̀̀a̸͖̩̘̯͂͛̃n̷̠̗̦̟̬͍͉̤̔̏̈́̀̈́̎̌͆͘q̴͔͎̍̄̀̍u̷̗̜̤̺͖͓̠̓̈̍͌͑͐̑̒̕į̸̻̙̭̯͕̩̮̰̕ļ̶̛̗̪ ̴͉̜̤͔̗͚̹̆̍͆v̷̞͇͉͝o̷̧̠͇̙͇͈͂̅͗̐̈̍í̵̩̬̮̰͙̞̱͇̟̿̒͐̍̊͛́c̷͔̜͓͉͉̫̈́̋͆̆̀̓́́͒ȩ̷͙̬̥̿̚͜.̵͉͔̣͍͘</p>
    <p>À̷̡̱͓͕̟͓͎̩̱̱͇̓̐͂͛̉ ̵̘̥̜̯͔̪̠̖͖̭͖̲͇̑͐̑͗͑̇́̉̋̉̽͘͜͝ͅt̶̮͚͎͎͎̝̰́̀̈́̂̀̀̍͐̈̓̚͝͠͝r̵̝̥̤̤̟͓̊̋̾̀̍͒̕̕͝a̴̧͓͚̥͚͓̬̟̺̺͉̠̻̒n̷̡̡͙̰̼̘͖̭̘͉̲̼̰̥͗̐̀̊͌̏͒́͘͜͝͝q̷̧͈͎̗̹̼̝̗̯̥̪̰̖͎̫̄͛͂̑̓͌̓̀̈̍͝u̵̢͇͕̳̮̻̩͎͛̀i̵͚̻͈͉̖͙̯͛̊̚ļ̴̛̲̘̟̖̤̖̲̪̻̻̋͑̒͊̄̎̊̎̏̎̀̊͝ ̶̢̨̜̞̰͈̲̪̹̣̐̽͆̾͒̋́͝v̷͓̺̤̖̏̈̂̓̚ő̵͓̦̝̟̃̀͛̾̃̓̑̀͒̀̽͠͝ĭ̵̡̧͚̻̫̠̭͎̠̤́̋c̵̮̥̜͚̙̩̘̱̲̰̞̮̖̺͍̎ę̵̧̪̙̣͓̗͌͗͑͛̐͗̽̊.̷̧̖̪̩̱͓̺̗͙̐̒ͅ</p>
    <p>Ą̸̛̼̭͎̲̖̝͕͈̦̭͕̳͈̖̺̺͎́̅̿͊̽̕͝͝ ̵̹̫̒͛͌́̊͝t̷̯͓͇͉̻̯̙̻̱̃̉̑̌͗͒̅̇͆̽̀̑̈́̏̽̔̏̐̈́̔͝r̶̜̮̙͍̰̣͉͖̝̟̮̦̫̦̭̟̦͆̏a̵͙̳̱͚̤͙̻͔͗̋̿̽̋̈́̑̅̇̓̈n̷̛̛͔͍̰̝͙͈̥͕̲̼͙̙͔͆̈́̀͊͊́͋̑̈́̓̃̀̅̎͘͘ͅq̴̻̜͉̹̭̥͈̜͉̫̯̼̠̜̐̓́̃̿̊̍̍̅͌̚͘͠͝ů̴͍͍̠̪̳̘̜͉͕͍̞͜į̶̫͔̲͇͇̘̟̣̼͕̟͆͆͊̉̄̽̈́͊̓̉̏͜͝l̵̦̐̉̎ ̸̨̢̛̛͖̘̦̞̲̗͓͕̖̰͙͍̱̠͑̈́͐̀͂̽͋͒̄̈́͌̑͘͘v̶̨̢̡̲͙̪̺̝̰̣̹͖̤̖̳̯͔̂̃̔̾͛̏̆͝ǫ̴̖̭̩̩̝̫̯̞̬̩͚̤̪̫͖̖̽́̑̚͜͠ỉ̵̡̳̜̖̟͉̜̩̩̬̜̞͚́͑̿͛̀̃̊͑̀͆́͒̕̕͝ͅc̷̛̛̝̪̭̮͈̜̩̣̥̫̤̻̱̹̋̈́̎̀̂̓̄͒̈͗̓̍̾͐̑̋̚̚ͅe̶̱̪͖͉̬̙̹̼͂̓̍̉.̷̢̧̛̭̦̳̮̪͉̙̹͕̗̬̝͇͔̒͗̽̉̽</p>
    <p>A̸̢̛̛̬͎̤͙̝̻͈͚͈̘̮̫̫̹̓͐̅͌̔̋̋͆͋̍̋̽́̾̏̈́̍̾̈́̐̑͋̂̀́̈̚̕͠ ̵̨̡̳͈̩͕̇̄͑̄͗̀̇͜t̸̡̡̙̻̺͉̞̣͇̬͙̫̬͔͙̳̭̻̖̞̮͚̞̦̣̲̼͉̥̳̻̖͔̭̗̞̥̳̼̓̍͌̿̽̃̐̔͠r̷̛̟͕͆a̴̢̡͍̬̦̪͓̳̭̲̤̟̫͙̦̮͆̔̒́̌̓̈̿̀͂̌̿́͌͂̃͌́͊͌͛́͌̎̈́̏͆̍͘̚͘͝͝͝͝ň̶̨̛̛̩͕͓̺̊͋́̂͒̊̈́͌̋̈̾̈̂̃̍̾̚͝ͅq̶̨̡̛̛̼̥̝̫̯̩̬̪̙̙̣͇͙̯̣͇̩̩͎̖̱̐̀̓̏͐̑̄̉̀͑̐̃̾̐͊̏̔̃̓͆̾̐̏͋̒͐̚̚͘͘̕̕̕͝ͅũ̶̝̣͙͙͉͎̬͉͙̹̠̩̣̅̐̈́͋͘͘ͅi̶̩͙̭̲̼̙͕͑̅̏̈́̔̉̎̅͛͂͜l̵̡̨̮̫̤̰̪͎̼̪̦̰̫̲̹̥̫͍̥̦̭̺͖̙͚̬͈͇̖͚̊́̑̋̊̿͊̇̾̅̒̋͒͊̃̈̈́̄̚͝͠ ̶̨̢̛̭͉̲͖̲͚̰͚̳̻͎̭̫̯̗̲̅̆̀̈́́͑̔͗̏͊͂̂̊̚̚̕͝͝ͅv̸̨̢̨͖̰̬̹̼͍̖̪̬̬̭̣͎͉̣͇̱̳̯̭͚̙̭̟̗̙̈́͒̔̍͂͊̊̔̆̄̽̐̽̋͋̆̇̓́́̋̍̍̆̀̓̌͊͐͗̋͗̏̚̕͜͠͝ô̸̧̨̨̨̖̖̻̜͈̙̳̰̣̬͍͇̭̠͉̭̹̰͔̟̫̞̱͖͕͉̣͙̬̒̀͂̿̔̽̅̀̉̿̽̋͐̅̀͋͑̈̂̈́̀͐͌̏̆̋̊̈́̚̚͘̚͜͝͠͝͝i̶͎̝̤̖̘̞̟̜̪̮͓̩͉̬̺̯̻̤͎͎͖̼̘̘͊̇͌͑̈́̆͊̄̒̓͂͋̈̂̓͛̍͋̈́̆͋̉̑́̉̈́͛́̐̑̕̚͝ͅc̸̡̢̛̯̺͇̠̫͖̱͈̗̱̟̺̝̺͍̩͈͈̲͙̖̋͋̑̆̔͂́̊̈̑́͌͂̒̈́̃̕͠ͅę̷͇͉̻͙͍̳̭̱̫̥̥͚͉͆̑̀̂̈̄̐̈́́̈̋̅̐͌̒̈́͐̀̈́.̵̨̨̢̛̪̳̦̯̞̥̫̝̠̘͖̥̖̲̍͆̈́̓͌͛̇̊́͑̈̈́̔̿̈́͋̉̎͑͊͒͛̋̾̑̿̄̎̽͜͝͠͠͝</p>
</div>

<script>
    // Password check function
    function checkPassword(event) {
        event.preventDefault();
        var password = document.getElementById('password').value;
        // Replace 'your_password' with your actual password
        if (password === 'moon') {
            document.getElementById('password-form').style.display = 'none';
            document.getElementById('content').style.display = 'block';
        } else {
            alert('Incorrect password. Please try again.');
        }
    }
</script>

</body>
</html>
