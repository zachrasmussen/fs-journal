Morning Challenge - August 10, 2022

function battle(goodTeam, evilTeam){

let gooderTeam = goodTeam.split(' ')
let evilerTEam = evilTeam.split(' ')
console.log(gooderTeam, evilerTeam)

let bestTeam = goooderTEam.map(s => parseInt(s))
let evilestTeam = evilerTeam.map(s => parseInt(s))

console.log('the bestest team', bestestTeam)

let goodSide = [1,2,3,3,4,10]
let badSide = [1,2,2,3,5,10]

let goodTotal = 0
for(let i = 0; i < bestestTeam.length; i++){
    let troopType = bestestTeam[i]
    let multiplier = goodSide[i]
    goodTotal += troopType * multiplier
}
// Or you could write it like this == but they both need to be the same!
let badTotal = 0
badSide.forEach((t, i) => {
    badTotal += evilestTeam[i]* t
})

}

Morning Challenge - August 11, 2022

let option1 = num1 + num2
let option2 = num1 + num3
let option 3 = num2 + num3

if(option1 >= num3 && option2 >= num2 && option3 >= num1) {
    return true
}
return false