import telebot
token = '1889135384:AAHUdcrCmlTqtl9y9FFlinNHa7PAK_ErwZA'
bot = telebot.Telebot(token)
@bot.message_handler(commands=['start'])
def start_message(message):
bot.send_message(message.chat.id,'Xoş gördük')
.
