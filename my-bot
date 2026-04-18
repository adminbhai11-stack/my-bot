from telegram import Update
from telegram.ext import ApplicationBuilder, CommandHandler, ContextTypes

TOKEN = "8308882365:AAEUnwHm351-nL4_ARNhmFpVE6dD0JxMygk"

async def start(update: Update, context: ContextTypes.DEFAULT_TYPE):
    text = """✨ ᴡᴇʟᴄᴏᴍᴇ ᴛᴏ ᴏᴜʀ ᴄʜᴀɴɴᴇʟ ✨

👋 আমাদের চ্যানেলে স্বাগতম! এখানে সব লেটেস্ট হ্যাক পাবেন..! 🛠️

⚠️ সর্তকতা: এই হ্যাক ভুল কাজে ব্যবহার করলে আমি বা চ্যানেল দায়ী থাকবে না। নিজ দায়িত্বে ব্যবহার করুন..!❤️‍🔥🙏 

🔗 Channel Links:
👉 https://t.me/sagor_70701"""
    await update.message.reply_text(text)

if __name__ == '__main__':
    app = ApplicationBuilder().token(TOKEN).build()
    app.add_handler(CommandHandler("start", start))

    print("Bot is running...")
    app.run_polling()

