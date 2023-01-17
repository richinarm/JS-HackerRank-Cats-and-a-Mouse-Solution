function hurdleRace(k, height) {
  let maxNumber = 0;
  let potionsRequired = 0;
  let naturalJumpValue = k;

  //check for tallest hurdle
  for (let i = 0; i < height.length; i++) {
    if (maxNumber < height[i]) {
      maxNumber = height[i];
    }
  }
  //potion uneeded if natural jump height is more or equal tallest //hurdle
  
if(naturalJumpValue >= maxNumber){
  return 0;
}

  else{
    potionsRequired = k - maxNumber;

  //ensuring results is always positive

  if (potionsRequired < 0) {
    potionsRequired = maxNumber - k;
  }

  
  return potionsRequired
  }
  

}


console.log(hurdleRace(7, [2, 5, 4, 5, 2]));


/*A video player plays a game in which the character competes in a hurdle race. Hurdles are of varying heights, and the characters have a maximum height they can jump. There is a magic potion they can take that will increase their maximum jump height by 1 unit for each dose. How many doses of the potion must the character take to be able to jump all of the hurdles. If the character can already clear all of the hurdles, return 0.*/