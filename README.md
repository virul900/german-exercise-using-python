from googletrans import Translator

translator = Translator()

text = 'hello , how are you'

translated = translator.translate(text, desr='de')

print(translated.text)
