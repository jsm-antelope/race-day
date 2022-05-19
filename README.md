"# race-day" 
let raceNumber = Math.floor(Math.random() * 1000);

const registerEarly = false;

const runnersAge = 9;


if (runnersAge > 18 && registerEarly == true){
  runnerNumber = raceNumber + 1000
} 

if (runnersAge > 18 && registerEarly == true){
      console.log(`you will race at 09:30am, your race number is ${runnerNumber}`)
}  else if (runnersAge > 18 && registerEarly == false) {
      console.log(`you are late, you will race  at 11:00am, your race number is ${raceNumber}`)
}   else if (runnersAge < 18) {
      console.log(`your race will be at 12:30pm, your race number is
${raceNumber}`)
}   else {
    console.log('see the registration desk')
}

 

//runnerNumber
//raceTime

/*
adults are over 18
youths are under 18
runners can register early or late
runners are assigned a race number and start time based on their age and registration 

race number; 
early adults recieve a race number at or above 1000
all others receive a number below 1000

start time;
adult registrants run at 09:30am or 11:00am
  early adults run at 09:30am
  late adults run at 11:00am 
youth registrants run at 12:30pm, regardless of registration.
*/
