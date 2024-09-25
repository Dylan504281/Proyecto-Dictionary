meme_dict = {
    "CRINGE": "Algo excepcionalmente raro o embarazoso.",
    "LOL": "Una respuesta común a algo gracioso.",
    "ROFL": "Una respuesta a una broma (literalmente: 'Rolling on the floor laughing').",
    "SHEESH": "Expresión de ligera desaprobación o sorpresa.",
    "CREEPY": "Algo aterrador o siniestro.",
    "AGGRO": "Ponerse agresivo o enojado.",
    "LMAO": "Una forma más intensa de decir 'LOL' (literalmente: 'Laughing my ass off').",
    "YOLO": "Una frase que significa 'You only live once' (Solo se vive una vez), utilizada para justificar acciones impulsivas."
}

print("¡Bienvenido al diccionario de memes! Aquí puedes encontrar el significado de las palabras más usadas en internet.")

for i in range(5):
    word = input("Escribe una palabra que no entiendas (¡con mayúsculas!): ")
    if word in meme_dict:
        print(f"¡Ah, '{word}' significa: {meme_dict[word]}")
    else:
        print(f"Lo siento, no encontré '{word}' en mi diccionario. Puedes intentar con otra palabra o añadirla tú mismo.")

print("¡Hasta la próxima! Sigue explorando el mundo de los memes.")
