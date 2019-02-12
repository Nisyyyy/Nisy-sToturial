var Discord = require("discord.js");
var bot = new Discord.Client();

bot.on("ready", () => {
  console.log("You are connected to " + bot.guilds.size + " servers!");
  bot.user.setGame("Subscroob,Like", "https://www.twitch.tv/monstercat")
});



bot.login('TOKEN HERE'); 