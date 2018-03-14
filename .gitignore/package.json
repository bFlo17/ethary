const Discord = require('discord.js');
const bot = new Discord.Client();

var prefix = ("!")

bot.on('ready', function() {
    bot.user.setGame("Ethary");
    console.log("Connectedç");
});  

bot.login("NDIwNzkzNTY0MTA1Mjc3NDYw.DYEFJw.coNJrH5_snPIqcPsOJ1ek8C8GJs");


bot.on('message', message => {
    if (message.content === prefix + "help"){
        message.channel.sendMessage("__Liste des commandes__ : \n -**!help** \n -**!ip** \n -**!mumble** \n -**!twitter**");   
    }

    if (message.content === prefix + "ip"){
        message.reply("**play.etharyuhc.com**");
        console.log("Commande ip effectué");
    }
    if (message.content === prefix + "mumble"){
        message.reply("**__Adresse :__ mumble01.omgserv.com \n __Port :__ 19257**");
        console.log("Commande Mumble effectué");
    }
    if (message.content === prefix + "twitter"){
        message.reply("**__Twitter :__ https://twitter.com/etharyUHC/**");
        console.log("Commande Twitter effectué");
    }    
});        
