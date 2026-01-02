<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Conejo Te Observa</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, sans-serif;
        }

        body {
            background: #000;
            overflow: hidden;
        }

        .overlay {
            position: fixed;
            inset: 0;
            background: url('conejo.jpg') center/cover no-repeat;
            filter: blur(3px) brightness(0.8);
            z-index: -1;
        }

        .container {
            position: absolute;
            width: 100%;
            top: 5vh;
            text-align: center;
            color: white;
        }

        .rabbit {
            width: 250px;
            height: 350px;
            margin: 0 auto 20px;
            background: url('conejo.jpg') center/cover no-repeat;
            border-radius: 20px;
            box-shadow: 0 0 20px rgba(255,0,0,0.4);
            filter: drop-shadow(0px 0px 10px rgba(255,0,0,0.3));
            transition: .4s;
        }

        .rabbit:hover {
            scale: 1.03;
            filter: drop-shadow(0px 0px 20px rgba(255,0,0,0.6));
        }

        .title {
            font-size: 2rem;
            margin-bottom: 20px;
            text-shadow: 0 0 15px red;
        }

        .log {
            width: 80%;
            height: 40vh;
            margin: 10px auto;
            padding: 15px;
            background: rgba(0,0,0,0.6);
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(255,255,255,0.2);
            overflow-y: auto;
        }

        .log p {
            margin: 5px 0;
            line-height: 1.4;
        }

        .input-area {
            margin-top: 15px;
        }

        input {
            padding: 12px;
            width: 60%;
            border: none;
            border-radius: 10px;
            font-size: 1rem;
            outline: none;
            background: rgba(255,255,255,0.15);
            color: white;
        }

        button {
            padding: 12px 20px;
            margin-left: 10px;
            background: red;
            border: none;
            border-radius: 10px;
            color: white;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }

        button:hover {
            background: #ff5555;
        }
    </style>
</head>
<body>

<div class="overlay"></div>

<div class="container">
    <div class="rabbit"></div>

    <h1 class="title">El Conejo Te Escucha</h1>

    <div class="log" id="log"></div>

    <div class="input-area">
        <input type="text" id="question" placeholder="Pregúntale algo al conejo..." autocomplete="off">
        <button onclick="processQuestion()">Enviar</button>
    </div>
</div>

<script>
    let memory = [];

    const patterns = [
        "Eso ya lo sabías antes de preguntarlo, ¿no?",
        "Curiosa elección de palabras… vuelve a leerlas.",
        "A veces la respuesta está en el silencio.",
        "Yo recuerdo más de lo que digo, pero digo menos de lo que sé.",
        "¿Por qué preguntas algo que parece que temes saber?"
    ];

    function generateResponse(question) {
        memory.push(question);

        let keyword = question.split(" ")[0];
        let pattern = patterns[Math.floor(Math.random()*patterns.length)];

        return `Hmmm… ${keyword}… interesante. ${pattern}`;
    }

    function processQuestion() {
        const q = document.getElementById("question");
        const log = document.getElementById("log");

        if (!q.value.trim()) return;

        log.innerHTML += `<p><strong>Tú:</strong> ${q.value}</p>`;

        let response = generateResponse(q.value);
        log.innerHTML += `<p><strong>Conejo:</strong> ${response}</p>`;

        speak(response);

        q.value = "";
        log.scrollTop = log.scrollHeight;
    }

    function speak(text) {
        let msg = new SpeechSynthesisUtterance(text);
        msg.pitch = 0.7;
        msg.rate = 0.9;
        msg.volume = 0.8;
        msg.voice = speechSynthesis.getVoices().find(v => v.lang.includes("es"));
        speechSynthesis.speak(msg);
    }

    // Fix para voces en algunos navegadores
    setTimeout(() => {
        speechSynthesis.getVoices();
    }, 1000);
</script>

</body>
</html>
