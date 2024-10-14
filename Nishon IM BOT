from telegram import Update
from telegram.ext import Application, CommandHandler, ContextTypes

# Tokenni o'zgaruvchi sifatida saqlang
TOKEN = 'YOU TOKEN'

# Botning /start komandasi uchun funksiyani yaratamiz
async def start(update: Update, context: ContextTypes.DEFAULT_TYPE) -> None:
    user = update.message.from_user
    await update.message.reply_text(f'Assalomu Alaykum {user.first_name}! Nishon Ixtisoslashtirilgan maktab botiga xush kelibsiz. Maktabimiz haqida sizni qiziqtirgan har qanday savolingizga ushbu  operatorimiz tomonidan javob olasiz. 1-operator: @ustoz_akt , 2-operator: @davlatx031 , 3-operator: @uralabdiraxmonov . Bizning kanalimiz https://t.me/Nishon_ixtisoslashtirilgan , https://t.me/Davlatbek_Devloper . Bizning YouTube kanalimiz https://www.youtube.com/@nishontumanim')

def main() -> None:
    # Botni yaratamiz va token bilan bog'laymiz
    application = Application.builder().token(TOKEN).build()

    # /start komandasi uchun handler qo'shamiz
    application.add_handler(CommandHandler("start",start))

    # Botni ishga tushiramiz
    application.run_polling()

if __name__ == '__main__':
    main()

    main()

