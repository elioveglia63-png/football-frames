html_content = '''
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Football Frames</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
        }
        header {
            display: flex;
            align-items: center;
            padding: 20px;
            background-color: #1f1f1f;
        }
        header img {
            height: 50px;
            margin-right: 20px;
        }
        header h1 {
            font-size: 24px;
        }
        section {
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .upload {
            margin-top: 20px;
        }
        .events {
            margin-top: 40px;
        }
        .event {
            background-color: #2a2a2a;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
        }
        [contenteditable] {
            border: 1px dashed #555;
            padding: 5px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/50" alt="Logo Football Frames">
        <h1 contenteditable="true">Football Frames</h1>
    </header>
    <section>
        <h2 contenteditable="true">Galleria Fotografica</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300x200" alt="Foto 1">
            <img src="https://via.placeholder.com/300x200" alt="Foto 2">
            <img src="https://via.placeholder.com/300x200" alt="Foto 3">
        </div>
        <div class="upload">
            <h3 contenteditable="true">Carica una nuova immagine</h3>
            <input type="file" accept="image/*">
        </div>
        <div class="events">
            <h2 contenteditable="true">Eventi in Arrivo</h2>
            <div class="event" contenteditable="true">Partita amichevole - 10 Settembre</div>
            <div class="event" contenteditable="true">Torneo giovanile - 15 Settembre</div>
        </div>
    </section>
</body>
</html>
'''

with open("/mnt/data/index.html", "w", encoding="utf-8") as f:
    f.write(html_content)

print("File index.html generato correttamente.")
