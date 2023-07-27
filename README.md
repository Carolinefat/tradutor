# tradutor
#  ajudar a melhorar esse codigo um Tradutor de Emoji para Texto voce coloca uma frase e traduz com emoji 
import emoji

def emoji_para_texto(texto_com_emojis):
    return emoji.demojize(texto_com_emojis)

def texto_para_emoji(texto):
    return emoji.emojize(texto)

texto_com_emojis = "Olá! 😃👋🌟"
texto_traduzido = emoji_para_texto(texto_com_emojis)
print("Texto com emojis:", texto_com_emojis)
print("Texto traduzido:", texto_traduzido)

texto_normal = "Eu amo programar em Python! :heart: :snake:"
texto_traduzido_emojis = texto_para_emoji(texto_normal)
print("Texto normal:", texto_normal)
print("Texto traduzido em emojis:", texto_traduzido_emojis)
