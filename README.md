<!DOCTYPE html>
<html>
  <head>
    <title>Rock-Pper-Scissors</title>
  </head>
  <body>
    <p>Rock-paper-Scissors</p>
    <button onclick="
      const randomNumber=Math.random();
      let computerMove='';
      if(randomNumber >=0 && randomNumber < 1/3){
        computerMove='rock';
      }else if(randomNumber >=1/3 && randomNumber < 2/3){
        computerMove='paper';
      }else if(randomNumber >=2/3 && randomNumber < 1){
        computerMove='scissors';
      }
      console.log(computerMove);
      let result='';
      if(computerMove==='rock'){
        result='Tie';
      }else if(computerMove==='paper'){
        result='you lose';
      }else if(computerMove==='scissors'){
        result='you win';
      }
      alert(`you picked rock.computer picked ${computerMove}.${result}`);
    ">Rock</button>
  <button onclick="
      const randomNumber=Math.random();
      let computerMove='';
      if(randomNumber >=0 && randomNumber < 1/3){
        computerMove='rock';
      }else if(randomNumber >=1/3 && randomNumber < 2/3){
        computerMove='paper';
      }else if(randomNumber >=2/3 && randomNumber < 1){
        computerMove='scissors';
      }
      console.log(computerMove);
      let result='';
      if(computerMove==='rock'){
        result='you win';
      }else if(computerMove==='paper'){
        result='Tie';
      }else if(computerMove==='scissors'){
        result='you lose';
      }
      alert(`you picked paper.computer picked ${computerMove}.${result}`);
      ">Paper</button>
    <button onclick="
      const randomNumber=Math.random();
      let computerMove='';
      if(randomNumber >=0 && randomNumber < 1/3){
        computerMove='rock';
      }else if(randomNumber >=1/3 && randomNumber < 2/3){
        computerMove='paper';
      }else if(randomNumber >=2/3 && randomNumber < 1){
        computerMove='scissors';
      }
      console.log(computerMove);
      let result='';
      if(computerMove==='rock'){
        result='you lose';
      }else if(computerMove==='paper'){
        result='you win';
      }else if(computerMove==='scissors'){
        result='Tie';
      }
      alert(`you picked Scissors.computer picked ${computerMove}.${result}`);
    ">Scissors</button>
    ><script>
      
    </script>

  </body>

</html>
