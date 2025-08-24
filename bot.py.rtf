{\rtf1\ansi\ansicpg1251\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 import logging\
from telegram.ext import Updater, CommandHandler, MessageHandler, Filters\
import openai\
\
# \uc0\u55357 \u56633  \u1042 \u1057 \u1058 \u1040 \u1042 \u1068  \u1057 \u1042 \u1054 \u1049  \u1058 \u1054 \u1050 \u1045 \u1053 \
TELEGRAM_TOKEN = "\uc0\u1058 \u1042 \u1054 \u1049 _TELEGRAM_TOKEN"\
OPENAI_KEY = "\uc0\u1058 \u1042 \u1054 \u1049 _OPENAI_API_KEY"\
\
openai.api_key = OPENAI_KEY\
\
logging.basicConfig(level=logging.INFO)\
\
# \uc0\u1050 \u1086 \u1084 \u1072 \u1085 \u1076 \u1072  /start\
def start(update, context):\
    update.message.reply_text("\uc0\u1055 \u1088 \u1080 \u1074 \u1077 \u1090 ! \u1071  \u1090 \u1074 \u1086 \u1081  AI-\u1073 \u1086 \u1090 . \u1053 \u1072 \u1087 \u1080 \u1096 \u1080  \u1084 \u1085 \u1077  \u1095 \u1090 \u1086 -\u1085 \u1080 \u1073 \u1091 \u1076 \u1100 .")\
\
# \uc0\u1054 \u1090 \u1074 \u1077 \u1090  \u1085 \u1072  \u1090 \u1077 \u1082 \u1089 \u1090 \
def reply(update, context):\
    user_text = update.message.text\
\
    # \uc0\u1047 \u1072 \u1087 \u1088 \u1086 \u1089  \u1074  ChatGPT\
    response = openai.Completion.create(\
        engine="text-davinci-003",\
        prompt=user_text,\
        max_tokens=150\
    )\
\
    bot_reply = response.choices[0].text.strip()\
    update.message.reply_text(bot_reply)\
\
def main():\
    updater = Updater(TELEGRAM_TOKEN, use_context=True)\
    dp = updater.dispatcher\
\
    dp.add_handler(CommandHandler("start", start))\
    dp.add_handler(MessageHandler(Filters.text & ~Filters.command, reply))\
\
    updater.start_polling()\
    updater.idle()\
\
if __name__ == "__main__":\
    main()\
}