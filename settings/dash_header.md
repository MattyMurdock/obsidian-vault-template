
```dataviewjs
//https://forum.obsidian.md/t/dataviewjs-get-an-automatic-humanized-morning-afternoon-evening-great-for-user-greetings/33351/4

let morning = [
    "En que vamos a trabajar hoy?!",
    "A trabajar",
    "Es un nuevo dia conchetumare!",
    "No estaria mal un cafesito UwUr",
    "Si las cosas que se hacen fueran faciles, no estarias aqui"
];

let afternoon = [
    "Ya casi acabas!",
    "Mantente Hidratado!",
    "Respira profundo y deja pasar todo mal",
    "Quieres algo de comer?",
    "Tal vez deberias darte un descanso...",
    "Toma un respiro, siempre es bueno despejar la mente..."
];

let evening = [
    "Listo ahora a dormir !",
    "Checa los pendientes de mañana !",
    "No te olvides de guardar todo !",
    "Quieres un cafe?☕",
    "Descansa lo hiciste bien hoy ! UwUr ❤️"
];

const currentHour = moment().format('HH'); 
let greeting; 

if (currentHour >= 19 || currentHour < 5) { 
    greeting = "🌔 Buenas noches! "
        + evening[Math.floor(Math.random()*evening.length)];
} else if (currentHour >= 5 && currentHour < 12) { 
    greeting = "🌞 Buenos dias! " + morning[Math.floor(Math.random()*morning.length)];
} else { 
    greeting = "🌟 Buenas Tardes! "
        + afternoon[Math.floor(Math.random()*afternoon.length)];
} 
dv.paragraph(greeting);
```
