# SistemaDeEventos

# Informacion general

##  Integrantes
##### Sebastian Moncada
##### Diego Vera
##### Fabian Huenchunir

const Discord = require("discord.js");
const  client = new Discord.Client();
const config = require("./config.json");

client.on("ready", () => {
   console.log("Estoy listo!");
});

client.on("error", (e) => console.error(e));
client.on("warn", (e) => console.warn(e));
client.on("debug", (e) => console.info(e));
client.login(config.token);

 
 
