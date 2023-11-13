const mineflayer = require('mineflayer');

// Replace with your Minecraft username and server IP
const bot = mineflayer.createBot({
    username: 'person_0',
    host: 'pvpMalia.aternos.me', //this is my server ip
});

bot.on('login', () => {
    console.log('Bot has logged in');
    // Your bot actions can be performed here
});

bot.on('chat', (username, message) => {
    if (username !== bot.username) {
        // When someone sends a message in the game, the bot will respond
        bot.chat(`Hi, ${username}! I'm a Mineflayer bot.`);
    }
});
