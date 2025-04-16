const config = { id: 1 };

config.id = 2;
if (true) {
  const config = { id: 3 }; 
  config.id = 4;
  console.log("Inside block:", config.id);
}

console.log("Outside block:", config.id);
